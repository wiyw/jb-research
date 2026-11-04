# Dylib inventory

The binaries in `extracted_dylibs/` are `arm64e` Mach-O shared libraries pulled
from the dyld shared cache. This page records what they are, their versions,
and useful ways to inspect or compare them.

## What each library is

| Library | Load path | Role |
| :------ | :-------- | :--- |
| `CoreGraphics` | `/System/Library/Frameworks/CoreGraphics.framework/CoreGraphics` | 2D drawing, color, PDF, and display-list framework |
| `ImageIO` | `/System/Library/Frameworks/ImageIO.framework/ImageIO` | Image decoding/encoding and metadata framework |
| `IMCore` | `/System/Library/PrivateFrameworks/IMCore.framework/IMCore` | Messages core logic (private) |
| `IMDPersistence` | `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence` | Messages persistence layer (private) |
| `libxpc.dylib` | `/usr/lib/system/libxpc.dylib` | XPC runtime |

## Versions

Mach-O `current version` and `LC_SOURCE_VERSION`:

| Library | 27.0.1 current | 27.0.1 source | 27.2 current | 27.2 source |
| :------ | :------------- | :------------ | :----------- | :---------- |
| `CoreGraphics` | 2050.0.0 | 2050.0 | 2050.1.6 | 2050.1.6 |
| `ImageIO` | 1.0.0 | 2851.0 | 1.0.0 | 2851.1.8 |
| `IMCore` | 800.0.0 | 1491.100.1.2.28 | 800.0.0 | 1491.200.101.2.5 |
| `IMDPersistence` | 800.0.0 | 1491.100.1.2.28 | 800.0.0 | 1491.200.101.2.5 |
| `libxpc.dylib` | 3298.2.1 | 3298.2.1 | 3298.42.1 | 3298.42.1 |

`ImageIO` keeps a `1.0.0` current version across both releases; use
`LC_SOURCE_VERSION` to distinguish builds.

## UUIDs and sizes

| Library | Version | Size (bytes) | LC_UUID |
| :------ | :------ | -----------: | :------ |
| `CoreGraphics` | 27.0.1 | 9,949,872 | `CF583D9C-9E49-3959-8C09-1E7141C57781` |
| `ImageIO` | 27.0.1 | 10,132,160 | `997FF300-8BC9-36C7-8424-68AE6743E952` |
| `IMCore` | 27.0.1 | 4,669,072 | `1FA63302-874F-3F73-994C-7039574107B6` |
| `IMDPersistence` | 27.0.1 | 5,033,528 | `A6D08D81-26FC-3E23-8BED-6301DFC62580` |
| `libxpc.dylib` | 27.0.1 | 647,376 | `2F319DF2-DF97-31F1-920A-AC20D14E1737` |
| `CoreGraphics` | 27.2 | 9,971,120 | `314A6344-864D-33EB-8A8C-F8279D3014C8` |
| `ImageIO` | 27.2 | 10,154,328 | `14E3AACA-BA2E-3442-8757-289304A16D93` |
| `IMCore` | 27.2 | 4,688,864 | `52F95823-5F3B-330B-B358-2518A54852F3` |
| `IMDPersistence` | 27.2 | 4,838,264 | `67C10ABB-09EB-3423-BDA9-75FF197FD5B0` |
| `libxpc.dylib` | 27.2 | 647,376 | `9BA91DF0-39A5-3C28-B96E-BE2463C5C793` |

## SHA-256

```
cee7cb84cd377fefdce848f28dc68f98ca9e142575a09c107def3dcdd5da4c0e  27.0.1/extracted_dylibs/CoreGraphics
781d875fd939e3796d3286de5fab08aa9ac5d06666993cdaad850a31cbeb9449  27.0.1/extracted_dylibs/ImageIO
7f45648bbc5a6bbd5d54f081fae09b885e7c7fabf6d07c98ccec864827bc39ca  27.0.1/extracted_dylibs/IMCore
72c6df97bee8085d9471deaf619da2b69b9eea41770bbd5ab13dce2493389628  27.0.1/extracted_dylibs/IMDPersistence
fcb22567f49db851a6d755554bb4efc2987ac90290c706eeea8850ff7cea3d4e  27.0.1/extracted_dylibs/libxpc.dylib
588db108542ebd93e70845b58b79c1c1dc344f0b2e9fc04bd31d28610a6c81fa  27.2/extracted_dylibs/CoreGraphics
5c241221344338cded9fc3210b1d206aba6397f80041e5e166df24c88c061571  27.2/extracted_dylibs/ImageIO
a96581815460099100e32e245632a9070d121e33c27544c717a2976e6acfee26  27.2/extracted_dylibs/IMCore
248bd5de732c942b83dab5dc0738acb7c5890eb4263cd62e12fd4b38b2446dc5  27.2/extracted_dylibs/IMDPersistence
39f9cdd63b84a8975fe6d7362a191459b53031ef1f0b2023e638f6f39cb71f40  27.2/extracted_dylibs/libxpc.dylib
```

## Inspect a binary

```sh
# Basic file type, architecture, and load path
file 27.2/extracted_dylibs/CoreGraphics
otool -D 27.2/extracted_dylibs/CoreGraphics

# Header, load commands, linked libraries
otool -hv 27.2/extracted_dylibs/CoreGraphics
otool -L  27.2/extracted_dylibs/CoreGraphics

# UUID, source version, and deployment target
otool -l 27.2/extracted_dylibs/CoreGraphics | grep -A3 LC_UUID
otool -l 27.2/extracted_dylibs/CoreGraphics | grep -A2 LC_SOURCE_VERSION
ipsw macho info 27.2/extracted_dylibs/CoreGraphics

# Symbols and strings
nm -gU 27.2/extracted_dylibs/CoreGraphics | head
strings 27.2/extracted_dylibs/CoreGraphics | grep -i pdf | head

# Objective-C headers (use the shared cache, not the standalone Mach-O)
ipsw class-dump 27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e \
  /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics --headers \
  --output /tmp/cg-headers
```

`ipsw class-dump` works against the shared cache plus the image path. Running
it on a standalone extracted Mach-O can fail because the image was linked for
the cache address space.

## Compare two versions

```sh
# Whole-file identity
shasum -a 256 27.0.1/extracted_dylibs/CoreGraphics \
              27.2/extracted_dylibs/CoreGraphics

# Section and version deltas
ipsw macho info 27.0.1/extracted_dylibs/CoreGraphics
ipsw macho info 27.2/extracted_dylibs/CoreGraphics

# ObjC surface changes between cache versions
ipsw class-dump 27.2/data/24B119__iPhone17,3/dyld_shared_cache_arm64e \
  /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics \
  --diff 27.0.1/data/24A446__iPhone17,3/dyld_shared_cache_arm64e
```

The generated per-image reports under `analysis/.../DYLIBS/` already contain
the size and content deltas for the shared cache; use these commands for a
deeper look at a specific library.
