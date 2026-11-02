## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-3288.2.1.0.0
-  __TEXT.__text: 0x56b04
+3288.42.1.0.0
+  __TEXT.__text: 0x56ea4
   __TEXT.__auth_stubs: 0xc00
-  __TEXT.__cstring: 0x1a6d8
+  __TEXT.__cstring: 0x1a6df
   __TEXT.__const: 0x8730
-  __TEXT.__unwind_info: 0xba8
+  __TEXT.__unwind_info: 0xbc0
   __DATA_CONST.__const: 0x620
-  __DATA_CONST.__cfstring: 0x200
+  __DATA_CONST.__cfstring: 0x220
   __DATA_CONST.__auth_got: 0x600
   __DATA_CONST.__got: 0x68
   __DATA_CONST.__auth_ptr: 0x68

   - /System/Library/PrivateFrameworks/FSKit.framework/FSKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libutil.dylib
-  Functions: 989
+  Functions: 993
   Symbols:   209
   CStrings:  0
 
```
