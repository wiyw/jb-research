## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/SoftwareUpdateCore`

```diff

-2718.0.18.0.0
-  __TEXT.__text: 0xaf194
-  __TEXT.__objc_methlist: 0x842c
-  __TEXT.__cstring: 0x1620d
+2718.42.1.0.0
+  __TEXT.__text: 0xaf1fc
+  __TEXT.__objc_methlist: 0x845c
+  __TEXT.__cstring: 0x161ed
   __TEXT.__const: 0x1e2
   __TEXT.__gcc_except_tab: 0x764
-  __TEXT.__oslogstring: 0xcef3
+  __TEXT.__oslogstring: 0xce93
   __TEXT.__dlopen_cstrs: 0x41
   __TEXT.__constg_swiftt: 0x50
   __TEXT.__swift5_typeref: 0x43
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x1910
+  __TEXT.__unwind_info: 0x1920
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a60
+  __DATA_CONST.__objc_selrefs: 0x4a80
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x208
   __DATA_CONST.__objc_arraydata: 0xe8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3290
-  Symbols:   5748
+  Functions: 3294
+  Symbols:   5752
   CStrings:  0
 
Symbols:
+ +[SUCoreDescriptor _booleanValueForKey:withAttributes:defaultValues:fallback:]
+ +[SUCoreDescriptor _ullValueForKey:withAttributes:defaultValues:fallback:]
+ -[SUCoreUpdateDownloader _stageDownloadGroups:awaitingAllGroups:withStagingTimeout:reportingProgress:completion:]
+ -[SUCoreUpdateDownloader initWithDelegate:forUpdate:updateUUID:maControl:maControlSplombo:]
```
