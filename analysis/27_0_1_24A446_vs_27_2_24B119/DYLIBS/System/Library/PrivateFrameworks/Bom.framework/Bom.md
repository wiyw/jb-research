## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Bom`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-279.0.0.0.0
-  __TEXT.__text: 0x5b4f0
+280.0.0.0.0
+  __TEXT.__text: 0x5bad8
   __TEXT.__cstring: 0x129e3
   __TEXT.__const: 0x1728
   __TEXT.__oslogstring: 0x103e

   __AUTH_CONST.__cfstring: 0x11c0
   __AUTH_CONST.__auth_got: 0xc68
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__data: 0x160
   __DATA.__data: 0x168
   __DATA.__bss: 0x8dc
+  __DATA_DIRTY.__data: 0x160
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
   - /usr/lib/libAppleArchive.dylib

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libbz2.1.0.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1100
-  Symbols:   1561
+  Functions: 1101
+  Symbols:   1562
   CStrings:  0
 
Symbols:
+ _BOMStreamWriteUInt64
+ __BOMCopierSanitizePath
- __copyDataFork
```
