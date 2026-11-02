## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

```diff

-866.0.0.0.0
-  __TEXT.__text: 0xa0878
-  __TEXT.__objc_methlist: 0x3898
-  __TEXT.__const: 0x3258
-  __TEXT.__oslogstring: 0x2474
-  __TEXT.__cstring: 0x428c
+866.2.4.0.0
+  __TEXT.__text: 0xa3968
+  __TEXT.__objc_methlist: 0x3a08
+  __TEXT.__const: 0x3398
+  __TEXT.__oslogstring: 0x24c3
+  __TEXT.__cstring: 0x444c
   __TEXT.__gcc_except_tab: 0x1484
-  __TEXT.__swift5_typeref: 0x1182
-  __TEXT.__swift5_fieldmd: 0x988
-  __TEXT.__constg_swiftt: 0xeac
+  __TEXT.__swift5_typeref: 0x11c0
+  __TEXT.__swift5_fieldmd: 0xa38
+  __TEXT.__constg_swiftt: 0xfc0
   __TEXT.__swift5_builtin: 0xf0
-  __TEXT.__swift5_reflstr: 0x66e
+  __TEXT.__swift5_reflstr: 0x6ee
   __TEXT.__swift5_assocty: 0x218
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_proto: 0x1dc
-  __TEXT.__swift5_types: 0x114
-  __TEXT.__swift5_capture: 0x740
-  __TEXT.__swift_as_entry: 0x140
-  __TEXT.__swift_as_ret: 0x208
-  __TEXT.__swift_as_cont: 0x430
+  __TEXT.__swift5_types: 0x128
+  __TEXT.__swift5_capture: 0x794
+  __TEXT.__swift_as_entry: 0x144
+  __TEXT.__swift_as_ret: 0x20c
+  __TEXT.__swift_as_cont: 0x43c
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x2d30
-  __TEXT.__eh_frame: 0x4cd8
+  __TEXT.__unwind_info: 0x2e28
+  __TEXT.__eh_frame: 0x4e48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1eb0
-  __DATA_CONST.__objc_classlist: 0x530
+  __DATA_CONST.__const: 0x1ef0
+  __DATA_CONST.__objc_classlist: 0x560
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2688
+  __DATA_CONST.__objc_selrefs: 0x26c0
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x1b8
+  __DATA_CONST.__objc_superrefs: 0x1c0
   __DATA_CONST.__objc_arraydata: 0x78
-  __DATA_CONST.__got: 0xd18
-  __AUTH_CONST.__const: 0x2838
-  __AUTH_CONST.__cfstring: 0x2a40
-  __AUTH_CONST.__objc_const: 0x80f8
+  __DATA_CONST.__got: 0xd38
+  __AUTH_CONST.__const: 0x2968
+  __AUTH_CONST.__cfstring: 0x2a80
+  __AUTH_CONST.__objc_const: 0x8438
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_arrayobj: 0xa8
-  __AUTH_CONST.__auth_got: 0x1238
-  __AUTH_CONST.__auth_ptr: 0x688
-  __AUTH.__objc_data: 0xf00
-  __AUTH.__data: 0x50
-  __DATA.__objc_ivar: 0x220
-  __DATA.__data: 0x8b0
+  __AUTH_CONST.__auth_got: 0x1260
+  __AUTH_CONST.__auth_ptr: 0x6a0
+  __AUTH.__objc_data: 0x12b0
+  __AUTH.__data: 0xf0
+  __DATA.__objc_ivar: 0x224
+  __DATA.__data: 0x8c8
   __DATA.__bss: 0x1d40
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x3420
+  __DATA_DIRTY.__objc_data: 0x3428
   __DATA_DIRTY.__data: 0x10c0
-  __DATA_DIRTY.__bss: 0x1d10
+  __DATA_DIRTY.__bss: 0x1d20
   __DATA_DIRTY.__common: 0x18
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/AppIntents.framework/AppIntents

   - /System/Library/PrivateFrameworks/BluetoothManager.framework/BluetoothManager
   - /System/Library/PrivateFrameworks/CarKit.framework/CarKit
   - /System/Library/PrivateFrameworks/CellularPlanManager.framework/CellularPlanManager
+  - /System/Library/PrivateFrameworks/EligibilityQuorum.framework/EligibilityQuorum
   - /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle
   - /System/Library/PrivateFrameworks/FindMyDevice.framework/FindMyDevice
   - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3315
-  Symbols:   3458
+  Functions: 3401
+  Symbols:   3519
   CStrings:  0
 
Symbols:
+ +[TPSRegulatoryImageManager fetchELabelURLsForAccessoryModel:completion:]
+ -[TPSBundleIdsCondition .cxx_destruct]
+ -[TPSBundleIdsCondition init]
+ -[TPSBundleIdsCondition requestingBundleId]
+ -[TPSBundleIdsCondition setRequestingBundleId:]
+ -[TPSBundleIdsCondition targetingValidations]
+ -[TPSDeliveryPrecondition applyRequestingBundleId:]
+ -[TPSPairedHomeAccessoryValidation validateWithCompletion:]
+ -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]
+ -[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]
+ -[TPSTipsManager welcomeCollectionOverrideFromContentPackage:]
+ GCC_except_table123
+ GCC_except_table36
+ GCC_except_table46
+ GCC_except_table54
+ GCC_except_table62
+ _HMHomeManagerHomeAccessoryAddedNotification
+ _OBJC_CLASS_$_TPSAudioIntelligenceEligibilityValidation
+ _OBJC_CLASS_$_TPSBundleIdsCondition
+ _OBJC_CLASS_$_TPSBundleIdsValidation
+ _OBJC_CLASS_$_TPSLiveRewindEligibilityValidation
+ _OBJC_CLASS_$_TPSPairedHomeAccessoryValidation
+ _OBJC_CLASS_$_TPSSiriNotesEligibilityValidation
+ _OBJC_IVAR_$_TPSBundleIdsCondition._requestingBundleId
+ _OBJC_METACLASS_$_TPSAudioIntelligenceEligibilityValidation
+ _OBJC_METACLASS_$_TPSBundleIdsCondition
+ _OBJC_METACLASS_$_TPSBundleIdsValidation
+ _OBJC_METACLASS_$_TPSLiveRewindEligibilityValidation
+ _OBJC_METACLASS_$_TPSPairedHomeAccessoryValidation
+ _OBJC_METACLASS_$_TPSSiriNotesEligibilityValidation
+ _TPSCommonDefinesCollectionNameHardware
+ _TPSCommonDefinesCollectionOverrideMajorVersion
+ _TPSHMManagerHomeAccessoryAddedNotificationString
+ __DATA_TPSAudioIntelligenceEligibilityValidation
+ __DATA_TPSBundleIdsValidation
+ __DATA_TPSLiveRewindEligibilityValidation
+ __DATA_TPSSiriNotesEligibilityValidation
+ __INSTANCE_METHODS_TPSAudioIntelligenceEligibilityValidation
+ __INSTANCE_METHODS_TPSBundleIdsValidation
+ __INSTANCE_METHODS_TPSLiveRewindEligibilityValidation
+ __INSTANCE_METHODS_TPSSiriNotesEligibilityValidation
+ __IVARS_TPSAudioIntelligenceEligibilityValidation
+ __IVARS_TPSBundleIdsValidation
+ __METACLASS_DATA_TPSAudioIntelligenceEligibilityValidation
+ __METACLASS_DATA_TPSBundleIdsValidation
+ __METACLASS_DATA_TPSLiveRewindEligibilityValidation
+ __METACLASS_DATA_TPSSiriNotesEligibilityValidation
+ __OBJC_$_INSTANCE_METHODS_TPSBundleIdsCondition
+ __OBJC_$_INSTANCE_METHODS_TPSPairedHomeAccessoryValidation
+ __OBJC_$_INSTANCE_VARIABLES_TPSBundleIdsCondition
+ __OBJC_$_PROP_LIST_TPSBundleIdsCondition
+ __OBJC_CLASS_RO_$_TPSBundleIdsCondition
+ __OBJC_CLASS_RO_$_TPSPairedHomeAccessoryValidation
+ __OBJC_METACLASS_RO_$_TPSBundleIdsCondition
+ __OBJC_METACLASS_RO_$_TPSPairedHomeAccessoryValidation
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_2
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_3
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_4
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_5
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_6
+ ___45-[TPSBundleIdsCondition targetingValidations]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_2
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_3
+ ___block_descriptor_112_e8_32s40s48s56s64r72r80r88r96r104w_e24_v16?0?<v?"NSError">8lw104l8s32l8s40l8s48l8r64l8r72l8r80l8s56l8r88l8r96l8
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"TPSInclusivityInfo"8Q16^B24ls32l8s40l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80w_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8w80l8s40l8s48l8s56l8s64l8s72l8
+ ___swift_memcpy8_8
+ _get_enum_tag_for_layout_string 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
+ _kTPSCapabilityLiveRewindEligibility
+ _kTPSCapabilitySiriNotesEligibility
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic _____ 10TipsDaemon19BundleIdsValidationC
+ _symbolic _____ 10TipsDaemon30SiriNotesEligibilityValidationC
+ _symbolic _____ 10TipsDaemon31LiveRewindEligibilityValidationC
+ _symbolic _____ 10TipsDaemon38AudioIntelligenceEligibilityValidationC
+ _symbolic _____ 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
+ _symbolic _____XDXMT 10TipsDaemon38AudioIntelligenceEligibilityValidationC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854N6CD00F8LLO
+ _type_layout_string 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
- -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]
- -[TPSTipsManager processClientConditions:targetingCache:completionHandler:]
- GCC_except_table122
- GCC_except_table33
- GCC_except_table35
- GCC_except_table45
- GCC_except_table53
- GCC_except_table61
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_2
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_3
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_4
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_5
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_6
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_2
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_3
- ___block_descriptor_104_e8_32s40s48s56r64r72r80r88r96w_e24_v16?0?<v?"NSError">8lw96l8s32l8s40l8r56l8r64l8r72l8s48l8r80l8r88l8
- ___block_descriptor_80_e8_32s40s48s56s64s72w_e39_v32?0"NSString"8"NSDictionary"16^B24lw72l8s32l8s40l8s48l8s56l8s64l8
- _symbolic _____Sg 18AppIntentsServices0bC0O14InterfaceIdiomO
```
