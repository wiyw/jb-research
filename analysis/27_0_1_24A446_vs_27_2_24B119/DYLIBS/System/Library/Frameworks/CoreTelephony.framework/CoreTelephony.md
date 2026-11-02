## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony`

```diff

-13487.7.0.0.0
-  __TEXT.__text: 0x1d02f0
-  __TEXT.__objc_methlist: 0x1f7ec
+13499.0.0.0.0
+  __TEXT.__text: 0x1d0e64
+  __TEXT.__objc_methlist: 0x1f8b4
   __TEXT.__const: 0x1736
-  __TEXT.__gcc_except_tab: 0x254fc
-  __TEXT.__cstring: 0x21e78
+  __TEXT.__gcc_except_tab: 0x256b0
+  __TEXT.__cstring: 0x21ec8
   __TEXT.__oslogstring: 0x50a6
   __TEXT.__swift5_typeref: 0x2b4
   __TEXT.__constg_swiftt: 0x140

   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x30
-  __TEXT.__unwind_info: 0x10e28
+  __TEXT.__unwind_info: 0x10ec0
   __TEXT.__eh_frame: 0x370
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x7858
-  __DATA_CONST.__objc_classlist: 0x1950
+  __DATA_CONST.__objc_classlist: 0x1960
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x288
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8880
+  __DATA_CONST.__objc_selrefs: 0x88a8
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x1d28
+  __DATA_CONST.__objc_superrefs: 0x1d48
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0xc38
   __AUTH_CONST.__const: 0x2718
-  __AUTH_CONST.__cfstring: 0x20b20
-  __AUTH_CONST.__objc_const: 0x36fd0
+  __AUTH_CONST.__cfstring: 0x20ba0
+  __AUTH_CONST.__objc_const: 0x37130
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__auth_got: 0xf70
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xd1b0
+  __AUTH.__objc_data: 0xcfa8
   __AUTH.__data: 0xb0
   __DATA.__objc_ivar: 0x16ac
   __DATA.__data: 0x2360
   __DATA.__bss: 0x800
   __DATA.__common: 0x10
-  __DATA_DIRTY.__objc_data: 0x2b20
+  __DATA_DIRTY.__objc_data: 0x2dc8
   __DATA_DIRTY.__data: 0x90
   __DATA_DIRTY.__bss: 0x12c8
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 13021
-  Symbols:   24053
+  Functions: 13037
+  Symbols:   24083
   CStrings:  0
 
Symbols:
+ +[CTXPCMigrateAppDataRequest allowedClassesForArguments]
+ +[CTXPCMigrateAppDataRequest isSensitiveMessage]
+ +[CTXPCMigrateAppDataResponse allowedClassesForArguments]
+ -[CTXPCMigrateAppDataRequest ct_shortName]
+ -[CTXPCMigrateAppDataRequest destinationBundleID]
+ -[CTXPCMigrateAppDataRequest initWithSourceBundleID:destinationBundleID:]
+ -[CTXPCMigrateAppDataRequest performRequestWithHandler:completionHandler:]
+ -[CTXPCMigrateAppDataRequest requiredEntitlement]
+ -[CTXPCMigrateAppDataRequest sourceBundleID]
+ -[CTXPCMigrateAppDataResponse ct_shortName]
+ -[CTXPCMigrateAppDataResponse initWithSuccess:]
+ -[CTXPCMigrateAppDataResponse success]
+ -[CoreTelephonyClient(AppMigration) migrateAppDataFromBundleID:toBundleID:completion:]
+ _OBJC_CLASS_$_CTXPCMigrateAppDataRequest
+ _OBJC_CLASS_$_CTXPCMigrateAppDataResponse
+ _OBJC_METACLASS_$_CTXPCMigrateAppDataRequest
+ _OBJC_METACLASS_$_CTXPCMigrateAppDataResponse
+ __OBJC_$_CLASS_METHODS_CTXPCMigrateAppDataRequest
+ __OBJC_$_CLASS_METHODS_CTXPCMigrateAppDataResponse
+ __OBJC_$_INSTANCE_METHODS_CTXPCMigrateAppDataRequest
+ __OBJC_$_INSTANCE_METHODS_CTXPCMigrateAppDataResponse
+ __OBJC_$_INSTANCE_METHODS_CoreTelephonyClient(hiddenData|Data|Settings|Emergency|CellMonitor|Call|Lazuli|SMS|DataUsage|CarrierBundlePrivate|CarrierBundle|Radio|FaceTime|SIMToolkit|Subscriber|CarrierServices|PrivateNetwork|RemotePlan|Provisioning|EnhancedLQM|PNR|Capabilities|Registration|UserIntent|Satellite|DataUsagePolicy|DeviceManagement|QuickSwitch_UI|EmergencyAlerts|Stewie|PlanTransfer|Bootstrap|AppMigration|CellularPlanStatusHint|InternalSettings|Vinyl|QuickSwitch|QuickSwitchInternal|TravelPrediction|SuppServices|Voicemail|CellularUsagePolicy|Phonebook|Postponement|CrossPlatformTransfer|CellularPlanManager|SimHardwareConfiguration|Eos|AuthenticationToken)
+ __OBJC_$_PROP_LIST_CTXPCMigrateAppDataRequest
+ __OBJC_$_PROP_LIST_CTXPCMigrateAppDataResponse
+ __OBJC_CLASS_RO_$_CTXPCMigrateAppDataRequest
+ __OBJC_CLASS_RO_$_CTXPCMigrateAppDataResponse
+ __OBJC_METACLASS_RO_$_CTXPCMigrateAppDataRequest
+ __OBJC_METACLASS_RO_$_CTXPCMigrateAppDataResponse
+ ___74-[CTXPCMigrateAppDataRequest performRequestWithHandler:completionHandler:]_block_invoke
+ ___86-[CoreTelephonyClient(AppMigration) migrateAppDataFromBundleID:toBundleID:completion:]_block_invoke
+ ___86-[CoreTelephonyClient(AppMigration) migrateAppDataFromBundleID:toBundleID:completion:]_block_invoke_2
- __OBJC_$_INSTANCE_METHODS_CoreTelephonyClient(hiddenData|Data|Settings|Emergency|CellMonitor|Call|Lazuli|SMS|DataUsage|CarrierBundlePrivate|CarrierBundle|Radio|FaceTime|SIMToolkit|Subscriber|CarrierServices|PrivateNetwork|RemotePlan|Provisioning|EnhancedLQM|PNR|Capabilities|Registration|UserIntent|Satellite|DataUsagePolicy|DeviceManagement|QuickSwitch_UI|EmergencyAlerts|Stewie|PlanTransfer|Bootstrap|CellularPlanStatusHint|InternalSettings|Vinyl|QuickSwitch|QuickSwitchInternal|TravelPrediction|SuppServices|Voicemail|CellularUsagePolicy|Phonebook|Postponement|CrossPlatformTransfer|CellularPlanManager|SimHardwareConfiguration|Eos|AuthenticationToken)
```
