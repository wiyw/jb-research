## Diagnostic-8288

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8288.appex/Diagnostic-8288`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-60.0.0.0.0
-  __TEXT.__text: 0xe074
+62.0.0.0.0
+  __TEXT.__text: 0x13108
   __TEXT.__auth_stubs: 0x6c0
-  __TEXT.__objc_stubs: 0x3c0
+  __TEXT.__objc_stubs: 0x3e0
   __TEXT.__objc_methlist: 0x50
   __TEXT.__cstring: 0x32a5
-  __TEXT.__gcc_except_tab: 0x16fc
+  __TEXT.__gcc_except_tab: 0x2274
   __TEXT.__const: 0x18
-  __TEXT.__oslogstring: 0x1d
+  __TEXT.__oslogstring: 0x30
   __TEXT.__objc_classname: 0x1a
-  __TEXT.__objc_methname: 0x231
+  __TEXT.__objc_methname: 0x23c
   __TEXT.__objc_methtype: 0xd4
-  __TEXT.__unwind_info: 0x430
-  __DATA_CONST.__const: 0x4a0
+  __TEXT.__unwind_info: 0x428
+  __DATA_CONST.__const: 0x4d8
   __DATA_CONST.__cfstring: 0x2340
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x370
   __DATA_CONST.__got: 0x2f8
   __DATA.__objc_const: 0xd8
-  __DATA.__objc_selrefs: 0x108
+  __DATA.__objc_selrefs: 0x110
   __DATA.__objc_ivar: 0x8
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
Symbols:
+ __os_log_error_impl
- _NSLog
```
