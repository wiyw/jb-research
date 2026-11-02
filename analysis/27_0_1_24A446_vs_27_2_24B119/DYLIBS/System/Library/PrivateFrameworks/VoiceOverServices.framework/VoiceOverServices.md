## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

```diff

-3240.9.0.0.0
-  __TEXT.__text: 0x35848
-  __TEXT.__objc_methlist: 0x2fb4
+3245.8.9.0.0
+  __TEXT.__text: 0x36a0c
+  __TEXT.__objc_methlist: 0x301c
   __TEXT.__dlopen_cstrs: 0xf0
-  __TEXT.__const: 0x80
+  __TEXT.__const: 0x90
   __TEXT.__gcc_except_tab: 0x1b0
-  __TEXT.__cstring: 0x7659
-  __TEXT.__oslogstring: 0x4c0
-  __TEXT.__unwind_info: 0x778
+  __TEXT.__cstring: 0x76c8
+  __TEXT.__oslogstring: 0x5a8
+  __TEXT.__unwind_info: 0x788
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2238
+  __DATA_CONST.__objc_selrefs: 0x2278
   __DATA_CONST.__objc_superrefs: 0xa8
   __DATA_CONST.__objc_arraydata: 0x190
   __DATA_CONST.__got: 0x2e8
-  __AUTH_CONST.__const: 0x3ca0
-  __AUTH_CONST.__cfstring: 0x92a0
-  __AUTH_CONST.__objc_const: 0x4480
+  __AUTH_CONST.__const: 0x3d00
+  __AUTH_CONST.__cfstring: 0x9340
+  __AUTH_CONST.__objc_const: 0x44e0
   __AUTH_CONST.__objc_arrayobj: 0x150
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x130
-  __DATA.__data: 0xe70
-  __DATA.__bss: 0xa10
+  __DATA.__objc_ivar: 0x134
+  __DATA.__data: 0xe78
+  __DATA.__bss: 0x9d0
   __DATA_DIRTY.__objc_data: 0x8c0
-  __DATA_DIRTY.__bss: 0x12f0
+  __DATA_DIRTY.__bss: 0x1360
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport

   - /usr/lib/libAccessibility.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1498
-  Symbols:   3370
+  Functions: 1509
+  Symbols:   3390
   CStrings:  0
 
Symbols:
+ +[VOSCommand BraillePanPageDown]
+ +[VOSCommand BraillePanPageUp]
+ +[VOSCommand ReadCurrentItem]
+ -[VOSCommandProfile _coalesceDuplicateProfileCommands]
+ -[VOSCommandProfile _isUnboundProfileCommand:]
+ -[VOSCommandProfile _releaseGesturesShadowedByUnboundCommands]
+ -[VOSCommandProfile requiresResave]
+ -[_VOSProfileMode removeCommand:]
+ GCC_except_table1285
+ GCC_except_table1351
+ GCC_except_table1359
+ GCC_except_table1479
+ GCC_except_table1485
+ _BraillePanPageDown._Command
+ _BraillePanPageDown.onceToken
+ _BraillePanPageUp._Command
+ _BraillePanPageUp.onceToken
+ _OBJC_IVAR_$_VOSCommandProfile._requiresResave
+ _ReadCurrentItem._Command
+ _ReadCurrentItem.onceToken
+ _VOTLogQuickSettings
+ ___29+[VOSCommand ReadCurrentItem]_block_invoke
+ ___30+[VOSCommand BraillePanPageUp]_block_invoke
+ ___32+[VOSCommand BraillePanPageDown]_block_invoke
+ _kVOTEventCommandBraillePanPageDown
+ _kVOTEventCommandBraillePanPageUp
+ _kVOTEventCommandOutputCurrentElement
- GCC_except_table1278
- GCC_except_table1344
- GCC_except_table1352
- GCC_except_table1468
- GCC_except_table1474
- _kVOTEventCommandBraillePlanarPanLeft
- _kVOTEventCommandBraillePlanarPanRight
```
