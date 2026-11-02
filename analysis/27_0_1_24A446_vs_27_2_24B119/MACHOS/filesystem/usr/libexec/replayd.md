## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__info_plist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-740.63.1.2.0
-  __TEXT.__text: 0xb929c
+765.15.2.0.0
+  __TEXT.__text: 0xbaecc
   __TEXT.__auth_stubs: 0x1920
-  __TEXT.__objc_stubs: 0xf0e0
-  __TEXT.__objc_methlist: 0x73c8
+  __TEXT.__objc_stubs: 0xf340
+  __TEXT.__objc_methlist: 0x74b0
   __TEXT.__const: 0x3e4
   __TEXT.__gcc_except_tab: 0xfc8
-  __TEXT.__objc_methname: 0x15d0c
-  __TEXT.__oslogstring: 0x1634a
-  __TEXT.__cstring: 0x17b48
+  __TEXT.__objc_methname: 0x15f9b
+  __TEXT.__oslogstring: 0x16809
+  __TEXT.__cstring: 0x17d26
   __TEXT.__objc_classname: 0xa44
-  __TEXT.__objc_methtype: 0x4403
+  __TEXT.__objc_methtype: 0x4410
   __TEXT.__info_plist: 0x4f8
-  __TEXT.__unwind_info: 0x2310
-  __DATA_CONST.__const: 0x2ab8
-  __DATA_CONST.__cfstring: 0x5ce0
+  __TEXT.__unwind_info: 0x2378
+  __DATA_CONST.__const: 0x2b00
+  __DATA_CONST.__cfstring: 0x5d40
   __DATA_CONST.__objc_classlist: 0x278
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x130

   __DATA_CONST.__auth_got: 0xca0
   __DATA_CONST.__got: 0xc88
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x11310
-  __DATA.__objc_selrefs: 0x4690
-  __DATA.__objc_ivar: 0xd7c
+  __DATA.__objc_const: 0x113b8
+  __DATA.__objc_selrefs: 0x4728
+  __DATA.__objc_ivar: 0xd88
   __DATA.__objc_data: 0x18b0
   __DATA.__data: 0xe54
   __DATA.__bss: 0x268

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3639
+  Functions: 3683
   Symbols:   802
   CStrings:  0
 
Symbols:
+ __exit
- _notify_register_check
```
