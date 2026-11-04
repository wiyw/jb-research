# jb-research

Reverse-engineering research notes and artifacts for iOS, focused on the
`iPhone17,3` (vresearch / virtual device) firmware line. The repository
collects extracted binaries, Ghidra decompilation output, and a
version-to-version diff of the iOS 27.0.1 and 27.2 release images.

## Firmware inputs

| iOS | Build | Device | IPSW |
| :-- | :---- | :----- | :--- |
| 27.0.1 | 24A446 | iPhone17,3 | `iPhone17,3_27.0.1_24A446_Restore.ipsw` |
| 27.2 | 24B119 | iPhone17,3 | `iPhone17,3_27.2_24B119_Restore.ipsw` |

SHA-1 checksums are recorded in the per-version `checksums.txt.sha1` files.
The IPSWs and extracted `data/` trees are excluded from version control, so
download them after cloning.

## Quick start

```sh
brew install ipsw ghidra

# Download the two restore images (checksums in each checksums.txt.sha1)
ipsw download ipsw --device iPhone17,3 --build 24A446 --confirm --output 27.0.1/data
ipsw download ipsw --device iPhone17,3 --build 24B119 --confirm --output 27.2/data

# Extract the dyld shared cache
ipsw extract --dyld --dyld-arch arm64e -o 27.0.1/data \
  27.0.1/data/iPhone17,3_27.0.1_24A446_Restore.ipsw
ipsw extract --dyld --dyld-arch arm64e -o 27.2/data \
  27.2/data/iPhone17,3_27.2_24B119_Restore.ipsw

# Pull a dylib out of the cache
ipsw dyld extract 27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e \
  CoreGraphics -o 27.2/extracted_dylibs
```

Full instructions: [firmware.md](docs/firmware.md).

## Repository layout

```
27.0.1/                     iOS 27.0.1 artifacts
   checksums.txt.sha1       IPSW checksum
   data/                    Downloaded IPSW and extracted cache (untracked)
   extracted_dylibs/        Mach-O arm64e dylibs pulled from the shared cache
   decompiled/              Ghidra pseudocode for CoreGraphics and ImageIO
27.2/                       iOS 27.2 artifacts (same layout)
analysis/
   27_0_1_24A446_vs_27_2_24B119/
      README.md              Version diff report
      KEXTS/                 Per-kext diff reports
      MACHOS/                Per-Mach-O diff reports (AppOS, ExclaveOS,
                             SystemOS, filesystem)
      DYLIBS/                Per-dylib diff reports
docs/                       Setup, analysis, and assessment guides
ghidra.gpr                  Local Ghidra project (ignored; recreate per docs/ghidra.md)
```

## Decompiled frameworks

`decompiled/CoreGraphics.c` and `decompiled/ImageIO.c` are Ghidra `C/C++`
exports of the corresponding dylibs for each firmware version. The binaries
live in `extracted_dylibs/`:

- `CoreGraphics` (tracked)
- `ImageIO` (tracked)
- `IMCore` (tracked)
- `IMDPersistence` (tracked)
- `libxpc.dylib` (tracked)

All binaries are 64-bit `arm64e` Mach-O shared libraries.

## Ghidra project

The Ghidra project is intentionally untracked: `.gitignore` excludes
`ghidra.*`, including `ghidra.gpr` and `ghidra.rep/`. A fresh clone will not
open the project until you recreate it.

1. Create a non-shared project named `ghidra` in the repository root.
2. Import each `extracted_dylibs/` binary and run the default auto-analysis.
3. Export the analyzed program with **File > Export Program... > C/C++** to
   reproduce `decompiled/*.c`.

Step-by-step instructions, including headless analysis: [ghidra.md](docs/ghidra.md).

## Version analysis

`analysis/27_0_1_24A446_vs_27_2_24B119/` compares the two releases across the
kernel, kexts, Mach-O images, and the dyld shared cache. The top-level report
summarizes:

- Kernel version and build timestamps
- New, removed, and updated kexts
- Per-filesystem, SystemOS, AppOS, and ExclaveOS Mach-O changes
- WebKit and dylib changes in the dyld shared cache

See [analysis.md](docs/analysis.md) for how the report was generated and how
to read the per-file diffs. For a curated summary, see
[findings.md](docs/findings.md); for the AppIntents security assessment, see
[assessment.md](docs/assessment.md).

## Virtual device

The virtual device is a `vresearch101` iOS guest running through the notarized
[vphone-launchpad](https://github.com/Lakr233/vphone-cli/releases) build on
Apple Silicon. Boot and serial logs are captured locally and are not tracked in
this repository; they include iBoot load messages, kernel panic output, host
security configuration, and the entitlements used for research guests.

Host setup and VM creation: [vphone.md](docs/vphone.md).

## Documentation

| Guide | Contents |
| :---- | :------- |
| [firmware.md](docs/firmware.md) | Download IPSWs, verify checksums, extract the cache and dylibs |
| [ghidra.md](docs/ghidra.md) | Recreate the untracked Ghidra project and export decompiled C |
| [binaries.md](docs/binaries.md) | Dylib inventory, UUIDs, checksums, and inspection commands |
| [decompiled-sources.md](docs/decompiled-sources.md) | Structure of the Ghidra C exports and how to search them |
| [analysis.md](docs/analysis.md) | Generate and read the version diff reports |
| [assessment.md](docs/assessment.md) | AppIntents binary diff and security assessment (27.0.1 to 27.2) |
| [findings.md](docs/findings.md) | Curated 27.0.1 to 27.2 release diff highlights |
| [vphone.md](docs/vphone.md) | Notarized vphone-launchpad setup and VM boot |
| [glossary.md](docs/glossary.md) | Firmware, Mach-O, and tooling terminology |
| [troubleshooting.md](docs/troubleshooting.md) | Common download, extraction, Ghidra, and vphone issues |

## License

Released under the GNU Affero General Public License v3.0. See `LICENSE`.

## Disclaimer

These materials are provided for security research and educational purposes
only. Firmware and decompiled code remain the property of their respective
owners.
