## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-3288.2.1.0.0
-  __TEXT.__text: 0xe51f4
+3288.42.1.0.0
+  __TEXT.__text: 0xe590c
   __TEXT.__auth_stubs: 0x1050
   __TEXT.__objc_stubs: 0x1240
   __TEXT.__objc_methlist: 0x83c
   __TEXT.__const: 0x8bb0
-  __TEXT.__cstring: 0x3b8b3
+  __TEXT.__cstring: 0x3b879
   __TEXT.__objc_methname: 0x1eb1
   __TEXT.__oslogstring: 0x1dd3
   __TEXT.__objc_classname: 0x13d

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x8
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x1b78
+  __TEXT.__unwind_info: 0x1ba8
   __DATA_CONST.__const: 0x1240
-  __DATA_CONST.__cfstring: 0x3a0
+  __DATA_CONST.__cfstring: 0x3c0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3287
-  Symbols:   1567
+  Symbols:   1568
   CStrings:  0
 
Symbols:
+ _decrement_dstream_id_for_deletion
+ _fsck_repairs_count
+ _fsck_volume_partial_abort
- _decrement_dstream_id_for_deletion_ex
- _iteratively_remove_extents_of_file
```
