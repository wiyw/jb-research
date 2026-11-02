## uarpd

> `/usr/libexec/uarpd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.2.3.0.0
-  __TEXT.__text: 0xa42ac
+1587.40.33.0.0
+  __TEXT.__text: 0xa6b74
   __TEXT.__auth_stubs: 0xa90
-  __TEXT.__objc_stubs: 0xa7a0
-  __TEXT.__objc_methlist: 0x8820
-  __TEXT.__objc_methname: 0xf56a
-  __TEXT.__objc_classname: 0x1d20
-  __TEXT.__cstring: 0xb112
-  __TEXT.__objc_methtype: 0x2ad1
-  __TEXT.__const: 0x140
+  __TEXT.__objc_stubs: 0xad00
+  __TEXT.__objc_methlist: 0x8a00
+  __TEXT.__objc_methname: 0xfad0
+  __TEXT.__objc_classname: 0x1d25
+  __TEXT.__cstring: 0xb6ee
+  __TEXT.__objc_methtype: 0x2b3a
+  __TEXT.__const: 0x138
   __TEXT.__gcc_except_tab: 0x1ec
-  __TEXT.__oslogstring: 0x9566
-  __TEXT.__info_plist: 0x3eb
-  __TEXT.__unwind_info: 0x2410
-  __DATA_CONST.__const: 0x10e0
-  __DATA_CONST.__cfstring: 0x56a0
+  __TEXT.__oslogstring: 0x98fd
+  __TEXT.__info_plist: 0x3f1
+  __TEXT.__unwind_info: 0x2480
+  __DATA_CONST.__const: 0x1108
+  __DATA_CONST.__cfstring: 0x5700
   __DATA_CONST.__objc_classlist: 0x610
-  __DATA_CONST.__objc_catlist: 0x10
+  __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x30

   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__auth_got: 0x558
-  __DATA_CONST.__got: 0x658
-  __DATA.__objc_const: 0x10910
-  __DATA.__objc_selrefs: 0x3218
-  __DATA.__objc_ivar: 0xb74
+  __DATA_CONST.__got: 0x668
+  __DATA.__objc_const: 0x10a48
+  __DATA.__objc_selrefs: 0x3370
+  __DATA.__objc_ivar: 0xb88
   __DATA.__objc_data: 0x3ca0
   __DATA.__data: 0x548
   __DATA.__bss: 0x1178

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 3979
-  Symbols:   239
+  Functions: 4030
+  Symbols:   241
   CStrings:  0
 
Symbols:
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$_UARPHostEndpointProperties
```
