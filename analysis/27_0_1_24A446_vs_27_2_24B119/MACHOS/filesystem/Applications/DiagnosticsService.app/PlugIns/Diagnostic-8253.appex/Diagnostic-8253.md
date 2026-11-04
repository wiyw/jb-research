## Diagnostic-8253

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8253.appex/Diagnostic-8253`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-60.0.0.0.0
-  __TEXT.__text: 0x13820
-  __TEXT.__auth_stubs: 0x710
+62.0.0.0.0
+  __TEXT.__text: 0x19d90
+  __TEXT.__auth_stubs: 0x730
   __TEXT.__objc_stubs: 0x860
   __TEXT.__objc_methlist: 0xf8
-  __TEXT.__gcc_except_tab: 0x2358
-  __TEXT.__const: 0x58
+  __TEXT.__const: 0x60
+  __TEXT.__gcc_except_tab: 0x30fc
   __TEXT.__cstring: 0x3f1c
+  __TEXT.__oslogstring: 0xb
   __TEXT.__objc_classname: 0x1c
   __TEXT.__objc_methname: 0x633
   __TEXT.__objc_methtype: 0x7d1
-  __TEXT.__unwind_info: 0x630
-  __DATA_CONST.__const: 0x518
+  __TEXT.__unwind_info: 0x628
+  __DATA_CONST.__const: 0x550
   __DATA_CONST.__cfstring: 0x33a0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x120
   __DATA_CONST.__objc_arraydata: 0x40
   __DATA_CONST.__objc_dictobj: 0xa0
-  __DATA_CONST.__auth_got: 0x398
-  __DATA_CONST.__got: 0x328
+  __DATA_CONST.__auth_got: 0x3a8
+  __DATA_CONST.__got: 0x330
   __DATA.__objc_const: 0x278
   __DATA.__objc_selrefs: 0x240
   __DATA.__objc_ivar: 0x3c

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 217
-  Symbols:   361
+  Symbols:   364
   CStrings:  0
 
Symbols:
+ __os_log_default
+ __os_log_error_impl
+ __os_log_impl
+ _os_log_type_enabled
- _NSLog
```
