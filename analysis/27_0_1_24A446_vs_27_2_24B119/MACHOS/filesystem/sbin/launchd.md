## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-3298.2.1.0.0
-  __TEXT.__text: 0x5b82c
-  __TEXT.__auth_stubs: 0x2700
+3298.42.1.0.0
+  __TEXT.__text: 0x5bb40
+  __TEXT.__auth_stubs: 0x2720
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x20c
   __TEXT.__const: 0x500
   __TEXT.__launchd: 0x1
-  __TEXT.__info_plist: 0x4cc
+  __TEXT.__info_plist: 0x4d3
   __TEXT.__constg_swiftt: 0xf8
   __TEXT.__swift5_typeref: 0x5e
   __TEXT.__swift5_reflstr: 0x1a
   __TEXT.__swift5_fieldmd: 0x60
   __TEXT.__swift5_proto: 0x8
   __TEXT.__swift5_types: 0xc
-  __TEXT.__cstring: 0x16a2c
+  __TEXT.__cstring: 0x16986
   __TEXT.__swift5_capture: 0x14
   __TEXT.__objc_methtype: 0xf
   __TEXT.__objc_classname: 0x212
   __TEXT.__objc_methname: 0x1c
-  __TEXT.__gcc_except_tab: 0xc0
+  __TEXT.__gcc_except_tab: 0xf8
   __TEXT.__oslogstring: 0xd5
-  __TEXT.__config: 0x2a71
+  __TEXT.__config: 0x2a50
   __TEXT.__dof_launchd: 0x67c
-  __TEXT.__unwind_info: 0x1150
+  __TEXT.__unwind_info: 0x1138
   __TEXT.__eh_frame: 0x210
-  __DATA_CONST.__const: 0x5a68
+  __DATA_CONST.__const: 0x59e8
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0xb0
-  __DATA_CONST.__auth_got: 0x1388
+  __DATA_CONST.__auth_got: 0x1398
   __DATA_CONST.__got: 0x210
   __DATA_CONST.__auth_ptr: 0xa0
   __DATA.__objc_const: 0xdf0

   __DATA.__os_assumes_log: 0x8
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xdf8
-  __DATA.__common: 0x7f0
+  __DATA.__common: 0x7f8
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
-  Functions: 1489
-  Symbols:   710
+  Functions: 1484
+  Symbols:   712
   CStrings:  0
 
Symbols:
+ _fstatfs
+ _objc_release_x26
```
