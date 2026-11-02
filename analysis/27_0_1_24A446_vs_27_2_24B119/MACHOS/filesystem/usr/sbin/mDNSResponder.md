## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3111.0.5.0.1
-  __TEXT.__text: 0x10abd4
+3111.40.45.0.0
+  __TEXT.__text: 0x10b75c
   __TEXT.__auth_stubs: 0x2fc0
   __TEXT.__objc_stubs: 0x20c0
   __TEXT.__objc_methlist: 0x694
-  __TEXT.__cstring: 0x17aed
-  __TEXT.__const: 0x14bc
-  __TEXT.__gcc_except_tab: 0x37c
-  __TEXT.__oslogstring: 0x210ca
+  __TEXT.__cstring: 0x17b50
+  __TEXT.__const: 0x14f4
+  __TEXT.__gcc_except_tab: 0x3a8
+  __TEXT.__oslogstring: 0x212b6
   __TEXT.__objc_classname: 0x646
   __TEXT.__objc_methname: 0x1e32
   __TEXT.__objc_methtype: 0x64d
-  __TEXT.__unwind_info: 0x16e0
+  __TEXT.__unwind_info: 0x16e8
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x6238
   __DATA_CONST.__cfstring: 0x1200

   - /usr/lib/libnetworkextension.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 1872
-  Symbols:   4153
+  Functions: 1876
+  Symbols:   4158
   CStrings:  0
 
Symbols:
+ GCC_except_table1122
+ GCC_except_table1253
+ GCC_except_table1259
+ GCC_except_table1422
+ GCC_except_table1605
+ GCC_except_table1838
+ GCC_except_table489
+ _CacheRecordDecrementIneligibleForRecycling
+ _CacheRecordIncrementIneligibleForRecycling
+ ___block_descriptor_56_e8_32s40bs48r_e8_v12?0B8ls32l8r48l8s40l8
+ __resolved_cache_update_tracking
+ _domain_name_labels_length_with_limit
+ _regRecordAddTSRRecord
- GCC_except_table1250
- GCC_except_table1256
- GCC_except_table1419
- GCC_except_table1602
- GCC_except_table1835
- GCC_except_table487
- ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls32l8s40l8
- _add_record_to_service
```
