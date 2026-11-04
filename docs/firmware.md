# Firmware acquisition and extraction

The IPSWs and the extracted `data/` trees are excluded from git, so a fresh
clone only contains the decompiled sources, the tracked dylibs, and the diff
reports. Use [`ipsw`](https://blacktop.github.io/ipsw) (blacktop) to download
and extract everything again.

## Install the tooling

```sh
brew install ipsw
```

## Download the IPSWs

Both images are for `iPhone17,3`. Pin the build to make the download
reproducible and write the IPSW into the version's `data/` directory:

```sh
ipsw download ipsw --device iPhone17,3 --build 24A446 --confirm --output 27.0.1/data
ipsw download ipsw --device iPhone17,3 --build 24B119 --confirm --output 27.2/data
```

`--version 27.0.1` / `--version 27.2` also works, but `--build` selects the
exact image recorded in this repo.

Verify each download against the committed checksum:

```sh
(cd 27.0.1/data && shasum -a 1 -c ../checksums.txt.sha1)
(cd 27.2/data && shasum -a 1 -c ../checksums.txt.sha1)
```

## Extract the dyld shared cache

`ipsw` writes the cache into a `<build>__<device>` folder next to the IPSW:

```sh
ipsw extract --dyld --dyld-arch arm64e \
  --output 27.0.1/data \
  27.0.1/data/iPhone17,3_27.0.1_24A446_Restore.ipsw

ipsw extract --dyld --dyld-arch arm64e \
  --output 27.2/data \
  27.2/data/iPhone17,3_27.2_24B119_Restore.ipsw
```

This produces `27.0.1/data/24A446__iPhone17,3/dyld_shared_cache_arm64e` and
`27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e`, plus the matching
subcache, atlas, and symbols files. Keep the subcaches in the same directory;
`ipsw dyld` reads them automatically.

## Extract individual dylibs

Pass the dyld image name (basename) as the second argument:

```sh
DSC=27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e

ipsw dyld extract "$DSC" CoreGraphics  -o 27.2/extracted_dylibs
ipsw dyld extract "$DSC" ImageIO       -o 27.2/extracted_dylibs
ipsw dyld extract "$DSC" IMCore        -o 27.2/extracted_dylibs
ipsw dyld extract "$DSC" IMDPersistence -o 27.2/extracted_dylibs
ipsw dyld extract "$DSC" libxpc.dylib  -o 27.2/extracted_dylibs
```

Repeat with the `24A446__iPhone17,3` cache for the 27.0.1 copies. The result
is an `arm64e` Mach-O shared library per image, ready to import into Ghidra.

`CoreGraphics`, `ImageIO`, `IMCore`, `IMDPersistence`, and `libxpc.dylib` are
tracked in git. The `data/` directories are ignored (see `.gitignore`).

## Reproduce the diff report

```sh
ipsw diff \
  27.0.1/data/iPhone17,3_27.0.1_24A446_Restore.ipsw \
  27.2/data/iPhone17,3_27.2_24B119_Restore.ipsw \
  --output analysis/27_0_1_24A446_vs_27_2_24B119 \
  --markdown --fw
```

See [analysis.md](analysis.md) for how to read the generated reports.
