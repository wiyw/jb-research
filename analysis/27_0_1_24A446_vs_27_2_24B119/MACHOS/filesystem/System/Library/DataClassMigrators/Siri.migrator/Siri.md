## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-3600.68.61.11.11
-  __TEXT.__text: 0x3f80
-  __TEXT.__auth_stubs: 0x470
-  __TEXT.__objc_stubs: 0xbc0
-  __TEXT.__objc_methlist: 0x1d0
+3605.31.1.11.2
+  __TEXT.__text: 0x4734
+  __TEXT.__auth_stubs: 0x4c0
+  __TEXT.__objc_stubs: 0xc60
+  __TEXT.__objc_methlist: 0x218
   __TEXT.__const: 0x34
-  __TEXT.__cstring: 0x90c
-  __TEXT.__oslogstring: 0xa79
+  __TEXT.__cstring: 0xa14
+  __TEXT.__oslogstring: 0xf28
   __TEXT.__objc_classname: 0xd
-  __TEXT.__objc_methname: 0x9d3
-  __TEXT.__objc_methtype: 0x47
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__objc_methname: 0xbc6
+  __TEXT.__objc_methtype: 0x90
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__const: 0x10
-  __DATA_CONST.__cfstring: 0x680
+  __DATA_CONST.__cfstring: 0x740
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x240
-  __DATA_CONST.__got: 0x130
+  __DATA_CONST.__auth_got: 0x268
+  __DATA_CONST.__got: 0x138
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x318
+  __DATA.__objc_selrefs: 0x340
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 40
-  Symbols:   121
+  Functions: 46
+  Symbols:   126
   CStrings:  0
 
Symbols:
+ _AFIsHomePod
+ _AFIsLinwoodEnabled
+ _TCCAccessReset
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x27
+ _objc_retain_x5
- _AFIsHorseman
- _objc_release_x25
- _objc_retain_x25
```
