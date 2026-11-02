## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

```diff

-655.0.109.0.0
-  __TEXT.__text: 0xfc8dc
-  __TEXT.__objc_methlist: 0xa388
-  __TEXT.__const: 0x3458
-  __TEXT.__cstring: 0xa8cc
-  __TEXT.__oslogstring: 0xc07a
-  __TEXT.__gcc_except_tab: 0x1b2c
-  __TEXT.__swift5_typeref: 0x1560
-  __TEXT.__constg_swiftt: 0xde8
+655.1.14.1.0
+  __TEXT.__text: 0x108f00
+  __TEXT.__objc_methlist: 0xa4c0
+  __TEXT.__const: 0x3618
+  __TEXT.__cstring: 0xaa2c
+  __TEXT.__oslogstring: 0xc82a
+  __TEXT.__gcc_except_tab: 0x1bb0
+  __TEXT.__constg_swiftt: 0xe30
+  __TEXT.__swift5_typeref: 0x175e
   __TEXT.__swift5_builtin: 0xf0
-  __TEXT.__swift5_reflstr: 0x7de
-  __TEXT.__swift5_fieldmd: 0xa00
+  __TEXT.__swift5_reflstr: 0x7fe
+  __TEXT.__swift5_fieldmd: 0xa44
   __TEXT.__swift5_assocty: 0x138
   __TEXT.__swift5_proto: 0x214
-  __TEXT.__swift5_types: 0xf4
-  __TEXT.__swift5_capture: 0xb08
+  __TEXT.__swift5_types: 0xfc
+  __TEXT.__swift5_capture: 0xc28
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__swift_as_entry: 0x170
-  __TEXT.__swift_as_ret: 0x1ac
-  __TEXT.__swift_as_cont: 0x250
+  __TEXT.__swift_as_entry: 0x198
+  __TEXT.__swift_as_ret: 0x1d4
+  __TEXT.__swift_as_cont: 0x284
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x3fb8
-  __TEXT.__eh_frame: 0x4220
+  __TEXT.__unwind_info: 0x42c0
+  __TEXT.__eh_frame: 0x4aac
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1da0
-  __DATA_CONST.__objc_classlist: 0x6f0
+  __DATA_CONST.__const: 0x1f20
+  __DATA_CONST.__objc_classlist: 0x6f8
   __DATA_CONST.__objc_catlist: 0x40
-  __DATA_CONST.__objc_protolist: 0x240
+  __DATA_CONST.__objc_protolist: 0x250
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x54d8
-  __DATA_CONST.__objc_protorefs: 0x138
+  __DATA_CONST.__objc_selrefs: 0x5548
+  __DATA_CONST.__objc_protorefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x4d0
   __DATA_CONST.__objc_arraydata: 0x260
-  __DATA_CONST.__got: 0xed8
-  __AUTH_CONST.__const: 0x3660
-  __AUTH_CONST.__cfstring: 0x9b20
-  __AUTH_CONST.__objc_const: 0x13588
+  __DATA_CONST.__got: 0xf00
+  __AUTH_CONST.__const: 0x39c0
+  __AUTH_CONST.__cfstring: 0x9aa0
+  __AUTH_CONST.__objc_const: 0x13660
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x1328
-  __AUTH_CONST.__auth_ptr: 0x4d0
-  __AUTH.__objc_data: 0x3248
-  __AUTH.__data: 0x500
-  __DATA.__objc_ivar: 0x7e0
-  __DATA.__data: 0x2210
+  __AUTH_CONST.__auth_got: 0x1410
+  __AUTH_CONST.__auth_ptr: 0x4d8
+  __AUTH.__objc_data: 0x32b8
+  __AUTH.__data: 0x508
+  __DATA.__objc_ivar: 0x7e4
+  __DATA.__data: 0x2360
   __DATA.__bss: 0x3fa0
-  __DATA.__common: 0xd0
+  __DATA.__common: 0xe8
   __DATA_DIRTY.__objc_data: 0x1f40
-  __DATA_DIRTY.__data: 0x278
+  __DATA_DIRTY.__data: 0x2c0
   __DATA_DIRTY.__bss: 0x1c0
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5985
-  Symbols:   6829
+  Functions: 6155
+  Symbols:   6907
   CStrings:  0
 
Symbols:
+ +[STExpressIntroductionUserObjC localUser]
+ +[STExpressIntroductionUserObjC remoteUserWithDSID:]
+ +[STExpressIntroductionUserObjC supportsSecureCoding]
+ -[STAppInfoCache isMigratedToNewScreenTime]
+ -[STConversation _allHandlesAreManagingParents:]
+ -[STConversation _isManagingParentHandle:]
+ -[STConversation allowableByContactsHandles:allowingManagingParentsWhenBlocked:]
+ -[STConversationContext allowsManagingParentsWhenBlocked]
+ -[STConversationContext setAllowsManagingParentsWhenBlocked:]
+ -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:shouldBeAllowedWhenBlocked:currentApplicationState:emergencyModeEnabled:]
+ -[STDowntimeClient initWithScreenTimeSettings:]
+ -[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]
+ -[STDowntimeClient isEurekaEnabled]
+ -[STDowntimeClient newScreenTimeEnabledAndMigratedWithError:]
+ -[STDowntimeClient screenTimeSettingsLock]
+ -[STDowntimeClient screenTimeSettings]
+ -[STDowntimeClient setScreenTimeSettings:]
+ -[STDowntimeClient setScreenTimeSettingsLock:]
+ -[STDowntimeClient setWorkQueue:]
+ -[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]
+ -[STDowntimeClient workQueue]
+ -[STExpressIntroductionSettingsDefaultsObjC managementHasStrictPolicy]
+ -[STExpressIntroductionSettingsDefaultsObjC managementIsManaged]
+ -[STExpressIntroductionSettingsDefaultsObjC setManagementHasStrictPolicy:]
+ -[STExpressIntroductionSettingsDefaultsObjC setManagementIsManaged:]
+ -[STExpressIntroductionUserObjC .cxx_destruct]
+ -[STExpressIntroductionUserObjC dsid]
+ -[STExpressIntroductionUserObjC encodeWithCoder:]
+ -[STExpressIntroductionUserObjC initWithCoder:]
+ -[STExpressIntroductionUserObjC initWithDSID:]
+ -[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]
+ -[STManagementState migrationEligibilityWithForceRefresh:completionHandler:]
+ -[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]
+ -[STManagementState screenTimeSettingsLock]
+ -[STManagementState setScreenTimeSettingsLock:]
+ -[STPINController authenticateUsingCurrentStoreWithPIN:completionHandler:]
+ -[STPINController beginTimeoutUntilDate:]
+ -[STPINController dealloc]
+ -[STRegulatoryContentPrivacyRestrictionsPolicy setTracksDataLinkingAcrossCompanies:]
+ -[STRegulatoryContentPrivacyRestrictionsPolicy tracksDataLinkingAcrossCompanies]
+ GCC_except_table100
+ GCC_except_table124
+ GCC_except_table127
+ GCC_except_table130
+ GCC_except_table133
+ GCC_except_table142
+ GCC_except_table145
+ GCC_except_table192
+ GCC_except_table195
+ GCC_except_table207
+ GCC_except_table216
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table40
+ GCC_except_table55
+ GCC_except_table59
+ GCC_except_table62
+ GCC_except_table65
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table69
+ _OBJC_CLASS_$_STAppDataMigrator
+ _OBJC_CLASS_$_STExpressIntroductionUserObjC
+ _OBJC_IVAR_$_STConversationContext._allowsManagingParentsWhenBlocked
+ _OBJC_IVAR_$_STDowntimeClient._screenTimeSettings
+ _OBJC_IVAR_$_STDowntimeClient._screenTimeSettingsLock
+ _OBJC_IVAR_$_STDowntimeClient._workQueue
+ _OBJC_IVAR_$_STExpressIntroductionSettingsDefaultsObjC._managementHasStrictPolicy
+ _OBJC_IVAR_$_STExpressIntroductionSettingsDefaultsObjC._managementIsManaged
+ _OBJC_IVAR_$_STExpressIntroductionUserObjC._dsid
+ _OBJC_IVAR_$_STManagementState._screenTimeSettingsLock
+ _OBJC_IVAR_$_STPINController._timeoutGeneration
+ _OBJC_IVAR_$_STRegulatoryContentPrivacyRestrictionsPolicy._tracksDataLinkingAcrossCompanies
+ _OBJC_METACLASS_$_STAppDataMigrator
+ _OBJC_METACLASS_$_STExpressIntroductionUserObjC
+ _STDisplayableBundleIdentifiers
+ _STUserDefaultsKeyUpgradeEligibilityActiveWindowSeconds
+ __CLASS_METHODS_STAppDataMigrator
+ __DATA_STAppDataMigrator
+ __INSTANCE_METHODS_STAppDataMigrator
+ __METACLASS_DATA_STAppDataMigrator
+ __OBJC_$_CLASS_METHODS_STExpressIntroductionUserObjC
+ __OBJC_$_CLASS_PROP_LIST_STExpressIntroductionUserObjC
+ __OBJC_$_INSTANCE_METHODS_STExpressIntroductionUserObjC
+ __OBJC_$_INSTANCE_VARIABLES_STExpressIntroductionUserObjC
+ __OBJC_$_PROP_LIST_STExpressIntroductionUserObjC
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_STAppDataMigratorCategoryProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STAppDataMigratorCategoryProviding
+ __OBJC_$_PROTOCOL_REFS_STAppDataMigratorCategoryProviding
+ __OBJC_CLASS_PROTOCOLS_$_STExpressIntroductionUserObjC
+ __OBJC_CLASS_RO_$_STExpressIntroductionUserObjC
+ __OBJC_LABEL_PROTOCOL_$_STAppDataMigratorCategoryProviding
+ __OBJC_METACLASS_RO_$_STExpressIntroductionUserObjC
+ __OBJC_PROTOCOL_$_STAppDataMigratorCategoryProviding
+ ___74-[STPINController authenticateUsingCurrentStoreWithPIN:completionHandler:]_block_invoke
+ ___74-[STPINController authenticateUsingCurrentStoreWithPIN:completionHandler:]_block_invoke_2
+ ___74-[STPINController authenticateUsingCurrentStoreWithPIN:completionHandler:]_block_invoke_3
+ ___76-[STManagementState migrationEligibilityWithForceRefresh:completionHandler:]_block_invoke
+ ___76-[STManagementState migrationEligibilityWithForceRefresh:completionHandler:]_block_invoke_2
+ ___79-[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]_block_invoke
+ ___79-[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]_block_invoke_2
+ ___79-[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]_block_invoke_3
+ ___79-[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]_block_invoke_4
+ ___79-[STDowntimeClient isDowntimeEnabledForUserID:callbackQueue:completionHandler:]_block_invoke_5
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_2
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_3
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_4
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_5
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_6
+ ___84-[STDowntimeClient toggleOnDemandDowntimeForUserID:callbackQueue:completionHandler:]_block_invoke_7
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_2
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_3
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_4
+ ___93-[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]_block_invoke
+ ___93-[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e20_v24?0"NSError"8q16ls32l8
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8lr40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e20_v20?0B8"NSError"12lr40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___swift_closure_destructor.175Tm
+ ___swift_closure_destructor.19Tm
+ ___swift_closure_destructor.47Tm
+ __swift_implicitisolationactor_to_executor_cast
+ _dispatch_get_global_queue
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _flat unique So34STAppDataMigratorCategoryProviding_p
+ _get_enum_tag_for_layout_string 14ScreenTimeCore17SettingsLoadState33_569ED91C29686B3D33BD755617EE8F1DLLO
+ _keypath_get_selector_hasChildAuthorization
+ _swift_release_n
+ _symbolic S3bIegyyy_
+ _symbolic SDySSSo10CTCategoryCG
+ _symbolic ScCySDySSSo10CTCategoryCG______pG s5ErrorP
+ _symbolic So17STAppDataMigratorCXMT
+ _symbolic So29STExpressIntroductionUserObjCC
+ _symbolic So41STExpressIntroductionSettingsDefaultsObjCC
+ _symbolic _____ 14ScreenTimeCore019ExpressIntroductionaB14SettingsLoaderO
+ _symbolic _____ 14ScreenTimeCore17SettingsLoadState33_569ED91C29686B3D33BD755617EE8F1DLLO
+ _symbolic _____ 26ScreenTimeSettingsServices0abC0C
+ _symbolic _____14passcodePolicy______14migrationStateAA018childAuthorizationB0t 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
+ _symbolic _____14passcodePolicy______14migrationStateAA018childAuthorizationB0tSg 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
+ _symbolic _____A2AIeyByyy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C8DowntimeV16EnablementPolicyO
+ _symbolic ______p So34STAppDataMigratorCategoryProvidingP
+ _symbolic _____ySSSo10CTCategoryCG s18_DictionaryStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _symbolic _____ySo11STBlueprintCG s11_SetStorageC
+ _symbolic _____ySo21STBlueprintUsageLimitCG s11_SetStorageC
+ _symbolic _____ySo24STBlueprintConfigurationCG s11_SetStorageC
+ _symbolic _____ySo8NSNumberCACG s18_DictionaryStorageC
+ _symbolic _____y_____14passcodePolicy______14migrationStateAB018childAuthorizationB0t_____G 11Observation12ObservationsV 26ScreenTimeSettingsServices0cdE0C13FeaturePolicyO AF9MigrationV5StateO s5NeverO
+ _symbolic _____y_____14passcodePolicy______14migrationStateAB018childAuthorizationB0t______G 11Observation12ObservationsV8IteratorV 26ScreenTimeSettingsServices0deF0C13FeaturePolicyO AH9MigrationV5StateO s5NeverO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s5ErrorP
+ _type_layout_string 14ScreenTimeCore17SettingsLoadState33_569ED91C29686B3D33BD755617EE8F1DLLO
- +[STFamilyDevice supportsSecureCoding]
- -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:currentApplicationState:emergencyModeEnabled:]
- -[STFamilyDevice .cxx_destruct]
- -[STFamilyDevice canUpgrade]
- -[STFamilyDevice encodeWithCoder:]
- -[STFamilyDevice initWithCoder:]
- -[STFamilyDevice initWithName:ownerAltDSID:osName:osVersion:model:isV2Compatible:canUpgrade:lastUpdatedDate:]
- -[STFamilyDevice isV2Compatible]
- -[STFamilyDevice lastUpdatedDate]
- -[STFamilyDevice model]
- -[STFamilyDevice name]
- -[STFamilyDevice osName]
- -[STFamilyDevice osVersion]
- -[STFamilyDevice ownerAltDSID]
- -[STFamilyDevice setCanUpgrade:]
- -[STFamilyDevice setIsV2Compatible:]
- -[STFamilyDevice setLastUpdatedDate:]
- -[STFamilyDevice setModel:]
- -[STFamilyDevice setName:]
- -[STFamilyDevice setOsName:]
- -[STFamilyDevice setOsVersion:]
- -[STFamilyDevice setOwnerAltDSID:]
- -[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]
- -[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]
- -[STManagementState screenTimeSettingsOnce]
- -[STManagementState setScreenTimeSettingsOnce:]
- GCC_except_table102
- GCC_except_table126
- GCC_except_table129
- GCC_except_table132
- GCC_except_table135
- GCC_except_table147
- GCC_except_table150
- GCC_except_table197
- GCC_except_table200
- GCC_except_table213
- GCC_except_table219
- GCC_except_table44
- GCC_except_table54
- GCC_except_table61
- GCC_except_table63
- GCC_except_table64
- GCC_except_table7
- GCC_except_table71
- _OBJC_CLASS_$_STFamilyDevice
- _OBJC_IVAR_$_STFamilyDevice._canUpgrade
- _OBJC_IVAR_$_STFamilyDevice._isV2Compatible
- _OBJC_IVAR_$_STFamilyDevice._lastUpdatedDate
- _OBJC_IVAR_$_STFamilyDevice._model
- _OBJC_IVAR_$_STFamilyDevice._name
- _OBJC_IVAR_$_STFamilyDevice._osName
- _OBJC_IVAR_$_STFamilyDevice._osVersion
- _OBJC_IVAR_$_STFamilyDevice._ownerAltDSID
- _OBJC_IVAR_$_STManagementState._screenTimeSettingsOnce
- _OBJC_METACLASS_$_STFamilyDevice
- __OBJC_$_CLASS_METHODS_STFamilyDevice
- __OBJC_$_CLASS_PROP_LIST_STFamilyDevice
- __OBJC_$_INSTANCE_METHODS_STFamilyDevice
- __OBJC_$_INSTANCE_VARIABLES_STFamilyDevice
- __OBJC_$_PROP_LIST_STFamilyDevice
- __OBJC_CLASS_PROTOCOLS_$_STFamilyDevice
- __OBJC_CLASS_RO_$_STFamilyDevice
- __OBJC_METACLASS_RO_$_STFamilyDevice
- ___100-[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]_block_invoke
- ___100-[STManagementState isFamilyMemberEligibleForMigrationUIWithAltDSID:forceRefresh:completionHandler:]_block_invoke_2
- ___39-[STManagementState screenTimeSettings]_block_invoke
- ___47-[STDowntimeClient isDowntimeEnabledForUserID:]_block_invoke_2
- ___48-[STManagementState initWithScreenTimeSettings:]_block_invoke
- ___70-[STDowntimeClient toggleOnDemandDowntimeForUserID:completionHandler:]_block_invoke_2
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke_2
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke_3
- ___91-[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]_block_invoke
- ___91-[STManagementState familyDevicesForAltDSID:forceRefresh:ineligibleOnly:completionHandler:]_block_invoke_2
- ___swift_closure_destructor.129Tm
- ___swift_closure_destructor.18Tm
- ___swift_closure_destructor.32Tm
- _symbolic S2bIegyy_
- _symbolic _____14passcodePolicy______14migrationStatet 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
- _symbolic _____14passcodePolicy______14migrationStatetSg 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
- _symbolic _____AAIeyByy_ 10ObjectiveC8ObjCBoolV
- _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C
- _symbolic _____y_____14passcodePolicy______14migrationStatet_____G 11Observation12ObservationsV 26ScreenTimeSettingsServices0cdE0C13FeaturePolicyO AF9MigrationV5StateO s5NeverO
- _symbolic _____y_____14passcodePolicy______14migrationStatet______G 11Observation12ObservationsV8IteratorV 26ScreenTimeSettingsServices0deF0C13FeaturePolicyO AH9MigrationV5StateO s5NeverO
```
