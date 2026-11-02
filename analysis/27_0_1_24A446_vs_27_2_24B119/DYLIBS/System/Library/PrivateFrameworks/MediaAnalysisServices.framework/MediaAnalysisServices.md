## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

```diff

-435.79.1.5.0
-  __TEXT.__text: 0x3c80c
-  __TEXT.__objc_methlist: 0x4fa4
+460.14.1.2.0
+  __TEXT.__text: 0x3cf70
+  __TEXT.__objc_methlist: 0x5034
   __TEXT.__const: 0xf8
-  __TEXT.__cstring: 0x38be
-  __TEXT.__gcc_except_tab: 0x4448
+  __TEXT.__cstring: 0x399e
+  __TEXT.__gcc_except_tab: 0x44e4
   __TEXT.__oslogstring: 0x2309
   __TEXT.__dlopen_cstrs: 0x417
-  __TEXT.__unwind_info: 0x1c58
+  __TEXT.__unwind_info: 0x1c68
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x430
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1978
+  __DATA_CONST.__objc_selrefs: 0x19f0
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x3f0
-  __DATA_CONST.__got: 0x518
+  __DATA_CONST.__got: 0x520
   __AUTH_CONST.__const: 0x338
-  __AUTH_CONST.__cfstring: 0x4ce0
-  __AUTH_CONST.__objc_const: 0xa248
+  __AUTH_CONST.__cfstring: 0x4e00
+  __AUTH_CONST.__objc_const: 0xa328
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x11d0
-  __DATA.__objc_ivar: 0x5a4
-  __DATA.__data: 0x420
+  __DATA.__objc_ivar: 0x5b4
   __DATA.__bss: 0x90
-  __DATA_DIRTY.__objc_data: 0x1810
+  __DATA_DIRTY.__objc_data: 0x29e0
+  __DATA_DIRTY.__data: 0x420
   __DATA_DIRTY.__bss: 0x80
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1698
-  Symbols:   3465
+  Functions: 1706
+  Symbols:   3481
   CStrings:  0
 
Symbols:
+ -[MADService fileTypeForURL:]
+ -[MADTextTokenizationRequest computeOffsets]
+ -[MADTextTokenizationRequest setComputeOffsets:]
+ -[MADTextTokenizationResult initWithTokenIDs:tokenOffsets:error:]
+ -[MADTextTokenizationResult tokenOffsets]
+ -[MADVideoSafetyClassificationRequest goreFrameCountThreshold]
+ -[MADVideoSafetyClassificationRequest setGoreFrameCountThreshold:]
+ -[MADVideoSafetyClassificationRequest setViolentFrameCountThreshold:]
+ -[MADVideoSafetyClassificationRequest violentFrameCountThreshold]
+ GCC_except_table109
+ GCC_except_table111
+ GCC_except_table120
+ GCC_except_table126
+ GCC_except_table134
+ GCC_except_table137
+ GCC_except_table149
+ GCC_except_table152
+ GCC_except_table155
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table166
+ GCC_except_table173
+ GCC_except_table184
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table69
+ GCC_except_table73
+ GCC_except_table75
+ GCC_except_table82
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_IVAR_$_MADTextTokenizationRequest._computeOffsets
+ _OBJC_IVAR_$_MADTextTokenizationResult._tokenOffsets
+ _OBJC_IVAR_$_MADVideoSafetyClassificationRequest._goreFrameCountThreshold
+ _OBJC_IVAR_$_MADVideoSafetyClassificationRequest._violentFrameCountThreshold
- -[MADTextTokenizationResult initWithTokenIDs:error:]
- GCC_except_table110
- GCC_except_table112
- GCC_except_table121
- GCC_except_table127
- GCC_except_table136
- GCC_except_table146
- GCC_except_table151
- GCC_except_table154
- GCC_except_table156
- GCC_except_table158
- GCC_except_table160
- GCC_except_table162
- GCC_except_table164
- GCC_except_table167
- GCC_except_table174
- GCC_except_table187
- GCC_except_table190
- GCC_except_table72
- GCC_except_table90
```
