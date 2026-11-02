## MobileInstallation

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation`

```diff

-1674.2.1.0.0
-  __TEXT.__text: 0x274dc
-  __TEXT.__objc_methlist: 0x13c4
+1680.40.14.0.0
+  __TEXT.__text: 0x2971c
+  __TEXT.__objc_methlist: 0x1454
   __TEXT.__const: 0x110
-  __TEXT.__cstring: 0x50d6
-  __TEXT.__gcc_except_tab: 0xc74
+  __TEXT.__cstring: 0x5155
+  __TEXT.__gcc_except_tab: 0xd1c
   __TEXT.__oslogstring: 0x43
-  __TEXT.__unwind_info: 0xd30
+  __TEXT.__unwind_info: 0xe08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xda0
+  __DATA_CONST.__objc_selrefs: 0xdd0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0xa8
   __DATA_CONST.__got: 0x1c8
   __AUTH_CONST.__const: 0xe0
-  __AUTH_CONST.__cfstring: 0x2b00
-  __AUTH_CONST.__objc_const: 0x1a00
+  __AUTH_CONST.__cfstring: 0x2b80
+  __AUTH_CONST.__objc_const: 0x1a30
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__auth_got: 0x4b0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x50
   __DATA.__objc_ivar: 0x118
   __DATA.__data: 0x240
-  __DATA.__bss: 0x60
+  __DATA.__bss: 0x70
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x2d0
-  __DATA_DIRTY.__bss: 0x20
+  __DATA_DIRTY.__objc_data: 0x320
+  __DATA_DIRTY.__bss: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/Security.framework/Security

   - /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 845
-  Symbols:   1384
+  Functions: 890
+  Symbols:   1435
   CStrings:  0
 
Symbols:
+ -[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]
+ -[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]
+ -[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]
+ -[MIInstallerClient removeAppReplacementStateForApp:completion:]
+ -[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]
+ -[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]
+ GCC_except_table326
+ GCC_except_table331
+ GCC_except_table336
+ GCC_except_table339
+ GCC_except_table342
+ GCC_except_table345
+ GCC_except_table351
+ GCC_except_table371
+ GCC_except_table378
+ GCC_except_table380
+ GCC_except_table386
+ GCC_except_table392
+ GCC_except_table394
+ GCC_except_table396
+ GCC_except_table407
+ GCC_except_table411
+ GCC_except_table413
+ GCC_except_table415
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table421
+ GCC_except_table423
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table436
+ GCC_except_table440
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table468
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table476
+ GCC_except_table478
+ GCC_except_table499
+ GCC_except_table510
+ GCC_except_table512
+ GCC_except_table514
+ GCC_except_table516
+ GCC_except_table518
+ GCC_except_table520
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table526
+ GCC_except_table528
+ GCC_except_table530
+ GCC_except_table532
+ GCC_except_table534
+ GCC_except_table536
+ GCC_except_table538
+ GCC_except_table540
+ GCC_except_table542
+ GCC_except_table544
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeExtensionEntitlement
+ _MIHasHomeKitEntitlement
+ _MobileInstallationEndAppReplacement
+ _MobileInstallationPrepareAppReplacement
+ _MobileInstallationPushReplacementInfo
+ _MobileInstallationRemoveAppReplacementState
+ _MobileInstallationSetAppLaunchProhibited
+ _MobileInstallationSetAppReplacementStatus
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_2
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_3
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_4
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_2
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_3
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_4
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_2
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_3
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_4
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_2
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_3
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_4
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_2
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_3
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_4
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_2
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_3
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_4
+ ___MobileInstallationEndAppReplacement_block_invoke
+ ___MobileInstallationPrepareAppReplacement_block_invoke
+ ___MobileInstallationPushReplacementInfo_block_invoke
+ ___MobileInstallationRemoveAppReplacementState_block_invoke
+ ___MobileInstallationSetAppLaunchProhibited_block_invoke
+ ___MobileInstallationSetAppReplacementStatus_block_invoke
- GCC_except_table296
- GCC_except_table301
- GCC_except_table306
- GCC_except_table309
- GCC_except_table312
- GCC_except_table315
- GCC_except_table318
- GCC_except_table321
- GCC_except_table341
- GCC_except_table350
- GCC_except_table356
- GCC_except_table362
- GCC_except_table364
- GCC_except_table366
- GCC_except_table370
- GCC_except_table377
- GCC_except_table381
- GCC_except_table383
- GCC_except_table385
- GCC_except_table387
- GCC_except_table389
- GCC_except_table391
- GCC_except_table393
- GCC_except_table395
- GCC_except_table398
- GCC_except_table402
- GCC_except_table404
- GCC_except_table406
- GCC_except_table408
- GCC_except_table410
- GCC_except_table412
- GCC_except_table414
- GCC_except_table416
- GCC_except_table418
- GCC_except_table420
- GCC_except_table422
- GCC_except_table454
- GCC_except_table456
- GCC_except_table460
- GCC_except_table464
- GCC_except_table469
- GCC_except_table480
- GCC_except_table488
- GCC_except_table496
- GCC_except_table498
- GCC_except_table500
- GCC_except_table502
```
