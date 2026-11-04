# Troubleshooting

## Firmware download and checksums

**`shasum: ... No such file or directory`**

The checksum file lists only the IPSW basename, so run it from the directory
that contains the IPSW:

```sh
(cd 27.0.1/data && shasum -a 1 -c ../checksums.txt.sha1)
```

**Checksum mismatch**

Re-download with the build pinned. Do not use `--latest`, which can move to a
different build:

```sh
ipsw download ipsw --device iPhone17,3 --build 24A446 --confirm --output 27.0.1/data
```

**`ipsw download` picks the wrong device/build**

Use both `--device iPhone17,3` and `--build`. Check the candidate URL first:

```sh
ipsw download ipsw --device iPhone17,3 --build 24A446 --urls
```

## Shared cache extraction

**`ipsw dyld extract` says `image ... not found in cache`**

Pass the dyld image name (basename), not the filesystem path:

```sh
# Works
ipsw dyld extract <DSC> libxpc.dylib -o out

# Fails
ipsw dyld extract <DSC> /usr/lib/system/libxpc.dylib -o out
```

For `ipsw class-dump`, the opposite is true: use the shared cache plus the
image path.

**Missing subcaches**

Keep the `dyld_shared_cache_arm64e` file and all `.NN` subcache/atlas/symbols
files in the same directory. Moving only the main file produces read failures.

**Extraction output is tiny or truncated**

The main cache file is small. Most content lives in subcaches; extract from a
complete `--dyld --dyld-arch arm64e` output directory.

## Missing dylibs after a clone

All published dylibs (`CoreGraphics`, `ImageIO`, `IMCore`, `IMDPersistence`,
and `libxpc.dylib`) are tracked, so they should appear after cloning. If one is
missing, restore it from the cache as described in [firmware.md](firmware.md).

## Ghidra

**The project will not open / `ghidra.gpr` is missing**

The project is untracked by design. Recreate it as described in
[ghidra.md](ghidra.md): create a non-shared project named `ghidra` in the repo
root, then import the dylibs.

**Import or analysis is very slow**

CoreGraphics and ImageIO are large. Import one binary at a time, let
auto-analysis finish, and increase memory if needed:

```sh
GHIDRA_HEADLESS_MAXMEM=8G \
  /opt/homebrew/Cellar/ghidra/12.2/libexec/support/analyzeHeadless \
  . ghidra -import 27.2/extracted_dylibs/CoreGraphics -overwrite
```

For the GUI, increase the Java heap in `support/launch.properties` in your
Ghidra install.

**Addresses look wrong or class-dump fails on the extracted Mach-O**

Extracted dylibs keep their shared-cache addresses. Some tools expect a normal
Mach-O base address. Use the shared cache with `ipsw class-dump`:

```sh
ipsw class-dump 27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e \
  /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
```

**The exported C will not compile**

Expected. The `.c` files are Ghidra pseudocode with placeholder types. Treat
them as searchable reference; use the Ghidra project for analysis.

## ipsw diff

**The diff takes a long time or uses too much disk**

`ipsw diff` caches its database under `~/Library/Caches/ipsw/diffs`. Limit or
disable it:

```sh
ipsw diff old.ipsw new.ipsw --markdown -o out --cache-max-size 2GiB
ipsw diff old.ipsw new.ipsw --markdown -o out --no-cache
```

**Counts do not match the committed report**

The committed report was generated with `--fw`. Re-run with the same options
and the same build pair; different `ipsw` versions can also change the
wording and grouping.

## vphone

**The launchpad is blocked by macOS**

Use the notarized `vphone-launchpad-<version>-notarized.zip` asset. CI-built
zips are not notarized and are blocked on first open. See
[vphone.md](vphone.md).

**The VM will not boot**

Confirm the host settings were applied in Recovery and that you rebooted:

```sh
csrutil enable --without debug
csrutil allow-research-guests enable
```

Then check the launchpad's Host Setup and the firmware/cloudOS pairing in the
upstream compatibility table.

**Need more diagnostic output**

Use the launchpad's serial/console view. Captured logs are snapshots, not live
logs, and none are tracked in this repository.
