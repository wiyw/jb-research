## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/ANELargeModelCompilerService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-382.15.1.0.0
-  __TEXT.__text: 0x19a28
+382.101.2.0.0
+  __TEXT.__text: 0x19590
   __TEXT.__auth_stubs: 0x890
   __TEXT.__objc_stubs: 0x2280
   __TEXT.__objc_methlist: 0x9ac
   __TEXT.__const: 0x120
-  __TEXT.__cstring: 0x12e6
-  __TEXT.__oslogstring: 0x2571
+  __TEXT.__cstring: 0x12e5
+  __TEXT.__oslogstring: 0x2554
   __TEXT.__objc_classname: 0x19e
-  __TEXT.__objc_methname: 0x25f1
+  __TEXT.__objc_methname: 0x25fa
   __TEXT.__objc_methtype: 0x67b
-  __TEXT.__gcc_except_tab: 0x1274
-  __TEXT.__unwind_info: 0x440
-  __DATA_CONST.__const: 0x348
-  __DATA_CONST.__cfstring: 0x1920
+  __TEXT.__gcc_except_tab: 0x1120
+  __TEXT.__unwind_info: 0x410
+  __DATA_CONST.__const: 0x2f8
+  __DATA_CONST.__cfstring: 0x1940
   __DATA_CONST.__objc_classlist: 0x80
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_intobj: 0x60
   __DATA_CONST.__auth_got: 0x460
   __DATA_CONST.__got: 0x1c0
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0xd48
   __DATA.__objc_selrefs: 0xa90
   __DATA.__objc_ivar: 0x24
   __DATA.__objc_data: 0x500
-  __DATA.__data: 0x400
-  __DATA.__bss: 0x88
+  __DATA.__data: 0x408
+  __DATA.__bss: 0x80
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 311
-  Symbols:   965
+  Functions: 313
+  Symbols:   963
   CStrings:  0
 
Symbols:
+ __ANEStorageProbeFileIsReadable
+ ___chkstk_darwin
+ _kANEFModelMutableClusterIndexKey
+ _objc_msgSend$cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:
+ _pread
- GCC_except_table10
- __43+[_ANEStorageHelper memoryMapWeightAtPath:]_block_invoke
- __72+[_ANEStorageHelper memoryMapModelAtPath:isPrecompiled:modelAttributes:]_block_invoke
- ___block_descriptor_192_e8_32r_e5_v8?0lr32l8
- ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
- _fcntl
- _objc_msgSend$cloneIfWritable:isEncryptedModel:cloneDirectory:
```
