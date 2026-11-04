## Diagnostic-8276

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8276.appex/Diagnostic-8276`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-60.0.0.0.0
-  __TEXT.__text: 0x1c1e8
+62.0.0.0.0
+  __TEXT.__text: 0x21e48
   __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_stubs: 0x1c00
   __TEXT.__objc_methlist: 0x8a4
-  __TEXT.__gcc_except_tab: 0x2e74
-  __TEXT.__const: 0x123
+  __TEXT.__gcc_except_tab: 0x3b14
+  __TEXT.__const: 0x140
   __TEXT.__objc_methname: 0x229b
-  __TEXT.__cstring: 0x472c
+  __TEXT.__cstring: 0x44c1
   __TEXT.__objc_classname: 0xb4
   __TEXT.__objc_methtype: 0xa12
-  __TEXT.__oslogstring: 0x11d
-  __TEXT.__unwind_info: 0x828
-  __DATA_CONST.__const: 0x608
-  __DATA_CONST.__cfstring: 0x3660
+  __TEXT.__oslogstring: 0x3d3
+  __TEXT.__unwind_info: 0x820
+  __DATA_CONST.__const: 0x640
+  __DATA_CONST.__cfstring: 0x3520
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
Symbols:
+ __os_log_error_impl
+ _objc_retain_x26
- _NSLog
- _objc_retain_x24
```
