# Decompiled sources

`decompiled/CoreGraphics.c` and `decompiled/ImageIO.c` are whole-program
exports from Ghidra's `CppExporter` (**File > Export Program... > C/C++**).
They are meant to be searched and read alongside the Ghidra project, not
compiled.

## Size

| File | Lines | Functions (approx.) |
| :--- | ----: | ------------------: |
| `27.0.1/decompiled/CoreGraphics.c` | 1,258,625 | 11,064 |
| `27.0.1/decompiled/ImageIO.c` | 1,159,763 | 12,058 |
| `27.2/decompiled/CoreGraphics.c` | 1,261,896 | 11,087 |
| `27.2/decompiled/ImageIO.c` | 1,164,028 | 12,114 |

The function count is the number of top-level definitions matching a
`type name(args)` pattern; treat it as an estimate.

## What the export contains

Each file starts with the standard Ghidra type preamble:

```c
typedef unsigned char   undefined;
typedef unsigned char    bool;
typedef unsigned char    byte;
typedef unsigned int    dword;
...
```

Then come placeholder declarations for classes and structures Ghidra could
only identify by name:

```c
typedef struct DisplayListXMLWriterEntryState DisplayListXMLWriterEntryState, *PDisplayListXMLWriterEntryState;

struct DisplayListXMLWriterEntryState { // PlaceHolder Class Structure
};
```

Function bodies use demangled C++/Swift names, for example:

```
CG11DisplayList30enumerateAllResourcesWithBlockEbU13block_pointerFvPKNS_19DisplayListResourceEE_block_invoke
CG11PDFPageCore15readAnnotationsEv_block_invoke
CGImageComputeHDRGainMap
CGImageConvertHDRPixelBufferToSDR
```

`CG...` names are Objective-C/C++ methods and functions; `_block_invoke`
suffixes are block literals; `_cold` suffixes are cold-path copies.

## Searching it

```sh
# Locate a symbol or family
grep -n 'CGPDF' 27.2/decompiled/CoreGraphics.c | head -40
grep -n 'DisplayList' 27.2/decompiled/CoreGraphics.c | head -40

# Find a function body by its mangled name fragment
grep -n 'readAnnotations' 27.2/decompiled/CoreGraphics.c

# ImageIO HDR and metadata paths
grep -n 'HDRGainMap' 27.2/decompiled/ImageIO.c | head
grep -n 'IIODictionary' 27.2/decompiled/ImageIO.c | head
```

Search the two versions and diff the hits to spot changed logic:

```sh
grep -n 'HDRGainMap' 27.0.1/decompiled/ImageIO.c
grep -n 'HDRGainMap' 27.2/decompiled/ImageIO.c
```

For structural comparisons, the `analysis/.../DYLIBS/` reports are faster
than diffing million-line C files.

## Limitations

- Types are reconstructed. Expect `undefined`, `undefined4`, `long`, and
  placeholder structs where the real type is not recoverable.
- `arm64e` pointer-authentication instructions are disassembled as ordinary
  AArch64; authenticated pointer operations may look unusual.
- Inlining, Swift thunks, and optimized tail calls can make control flow hard
  to follow.
- The export is not valid, compilable C. Do not try to build it.
- Names reflect what Ghidra could recover. Unnamed functions appear as
  `FUN_<address>` and improve only if you rename them in the project.

## Recommended workflow

1. Use the `.c` files for fast text search and orientation.
2. Open the same function in the Ghidra project to follow references, rename
   symbols, and retype variables.
3. Keep notes in the Ghidra project rather than editing the exported `.c`.
4. Re-export only when you want a fresh snapshot of analysis changes.

See [ghidra.md](ghidra.md) for project creation and export steps.
