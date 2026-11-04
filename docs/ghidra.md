# Ghidra setup

The Ghidra project database is intentionally not tracked. `.gitignore` ignores
`ghidra.*`, which covers both `ghidra.gpr` and the `ghidra.rep/` database.
Opening the repository after a fresh clone therefore requires creating the
project and importing the dylibs again. The committed `decompiled/*.c` files
are the expected output of that process.

## Install Ghidra

```sh
brew install ghidra
```

This installs Ghidra and a compatible JDK. Launch it with `ghidraRun`.

## Create the project

1. Start Ghidra and choose **File > New Project...**.
2. Select **Non-Shared Project**.
3. Set the project directory to the repository root and the project name to
   `ghidra`. This recreates `ghidra.gpr` and `ghidra.rep/` in the same place
   the ignore rules expect.
4. Click **Finish**.

If you prefer another name, use it, but keep the resulting `.gpr`/`.rep` out
of git or extend `.gitignore` accordingly.

## Import the dylibs

For each extracted binary (`27.0.1/extracted_dylibs/`, `27.2/extracted_dylibs/`):

1. **File > Import File...** and select the dylib.
2. Keep the detected format. Extracted dylibs are plain Mach-O `arm64e`
   images, so Ghidra's built-in Mach-O loader is used. If Ghidra asks whether
   the file is a dyld shared cache, choose the normal Mach-O import, not the
   cache loader.
3. Accept the default language/compiler spec (`AARCH64`).
4. When prompted, run the default auto-analysis. This can take several
   minutes for CoreGraphics and ImageIO.

To analyze without the GUI for importing and inspection:

```sh
GHIDRA=/opt/homebrew/Cellar/ghidra/12.2/libexec
"$GHIDRA/support/analyzeHeadless" . ghidra \
  -import 27.2/extracted_dylibs/CoreGraphics -overwrite
```

The headless analyzer imports and analyzes, but it does not have a built-in
`C/C++` export step. Use the GUI exporter below to regenerate the `.c` files.

## Export the decompiled C

The committed `CoreGraphics.c` and `ImageIO.c` were produced with Ghidra's
`CppExporter` (the **C/C++** export format):

1. Open the analyzed program in the CodeBrowser.
2. **File > Export Program...**
3. Set **Format** to **C/C++**.
4. Enable **Create C File (.c)** and the other options you want (type
   definitions and referenced globals match the committed output).
5. Export to `decompiled/CoreGraphics.c` or `decompiled/ImageIO.c` in the
   appropriate version directory.

The exported file starts with Ghidra's `typedef unsigned char undefined;`
block and placeholder class structures, which is expected.

## Rebuilding from scratch

A short end-to-end path:

```sh
# 1. Fetch and extract firmware (see firmware.md)
# 2. Create project "ghidra" in the repo root
ghidraRun
# 3. Import each extracted dylib, run auto-analysis
# 4. Export each program as C/C++ into the version's decompiled/ directory
```

## Notes

- Ghidra decompiles `arm64e` pointer-authentication instructions as ordinary
  AArch64; expect some `undefined` types in the output.
- The binaries are stripped of source-level names. Rename functions and
  structures in the project as you identify them; the project stays local.
- The `ghidra.rep/` directory can be large. Do not commit it, and consider
  excluding it from backups if space is tight.
