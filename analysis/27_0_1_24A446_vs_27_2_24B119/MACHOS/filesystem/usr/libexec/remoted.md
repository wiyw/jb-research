## remoted

> `/usr/libexec/remoted`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-245.0.7.0.0
-  __TEXT.__text: 0x3d5f4
+245.40.9.0.0
+  __TEXT.__text: 0x3d6fc
   __TEXT.__auth_stubs: 0x1860
-  __TEXT.__objc_stubs: 0x24a0
-  __TEXT.__objc_methlist: 0x1560
+  __TEXT.__objc_stubs: 0x2520
+  __TEXT.__objc_methlist: 0x1590
   __TEXT.__const: 0x22a
-  __TEXT.__oslogstring: 0x8502
-  __TEXT.__cstring: 0x21d9
-  __TEXT.__objc_methname: 0x254c
+  __TEXT.__oslogstring: 0x85d2
+  __TEXT.__cstring: 0x2243
+  __TEXT.__objc_methname: 0x259a
   __TEXT.__objc_classname: 0x2c9
   __TEXT.__objc_methtype: 0x79b
-  __TEXT.__gcc_except_tab: 0x1120
-  __TEXT.__info_plist: 0x407
+  __TEXT.__gcc_except_tab: 0x1098
+  __TEXT.__info_plist: 0x40d
   __TEXT.__unwind_info: 0xdd0
-  __DATA_CONST.__const: 0x12c8
-  __DATA_CONST.__cfstring: 0xea0
+  __DATA_CONST.__const: 0x12b0
+  __DATA_CONST.__cfstring: 0xf00
   __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__auth_got: 0xc40
   __DATA_CONST.__got: 0x250
-  __DATA.__objc_const: 0x2810
-  __DATA.__objc_selrefs: 0x980
-  __DATA.__objc_ivar: 0x21c
+  __DATA.__objc_const: 0x2850
+  __DATA.__objc_selrefs: 0x9a0
+  __DATA.__objc_ivar: 0x220
   __DATA.__objc_data: 0x870
   __DATA.__data: 0x6d4
-  __DATA.__bss: 0x3b8
+  __DATA.__bss: 0x3c8
   __DATA.__common: 0x38
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1376
+  Functions: 1385
   Symbols:   492
   CStrings:  0
 
Symbols:
+ _MGGetBoolAnswer
- _IORegistryEntryFromPath
```
