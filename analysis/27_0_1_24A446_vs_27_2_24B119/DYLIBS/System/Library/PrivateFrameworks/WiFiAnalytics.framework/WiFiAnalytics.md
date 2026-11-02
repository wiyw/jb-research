## WiFiAnalytics

> `/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics`

```diff

-825.58.0.0.0
-  __TEXT.__text: 0x156090
-  __TEXT.__objc_methlist: 0x10690
-  __TEXT.__const: 0x3d8
+827.3.0.0.0
+  __TEXT.__text: 0x156164
+  __TEXT.__objc_methlist: 0x106a8
+  __TEXT.__const: 0x3e0
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__cstring: 0x14e24
-  __TEXT.__oslogstring: 0x11b30
+  __TEXT.__cstring: 0x14e23
+  __TEXT.__oslogstring: 0x11b46
   __TEXT.__constg_swiftt: 0x1e0
   __TEXT.__swift5_typeref: 0x154
   __TEXT.__swift5_reflstr: 0xb1

   __TEXT.__swift5_capture: 0x1b0
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0x2754
-  __TEXT.__unwind_info: 0x2a38
+  __TEXT.__unwind_info: 0x2a30
   __TEXT.__eh_frame: 0x2d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8ce0
+  __DATA_CONST.__objc_selrefs: 0x8cf0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x390
   __DATA_CONST.__objc_arraydata: 0xa40

   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x8d8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x458
+  __AUTH.__objc_data: 0x408
   __DATA.__objc_ivar: 0xff4
   __DATA.__data: 0x398
-  __DATA.__bss: 0x1c
-  __DATA.__common: 0x410
+  __DATA.__bss: 0x20
   __DATA_DIRTY.__objc_ivar: 0x120
-  __DATA_DIRTY.__objc_data: 0x2b48
+  __DATA_DIRTY.__objc_data: 0x2b98
   __DATA_DIRTY.__data: 0xa0
-  __DATA_DIRTY.__bss: 0x168
-  __DATA_DIRTY.__common: 0xde8
+  __DATA_DIRTY.__bss: 0x170
+  __DATA_DIRTY.__common: 0x11f8
   - /System/Library/Frameworks/CoreData.framework/CoreData
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6053
-  Symbols:   8840
+  Functions: 6056
+  Symbols:   8844
   CStrings:  0
 
Symbols:
+ +[WAUtil setSamplingDisabledForTesting:]
+ -[WAEvent caSamplingPercentage]
+ -[WAEventRoamStatus caSamplingPercentage]
+ __samplingDisabledForTesting
```
