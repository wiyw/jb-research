## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

```diff

-625.1.29.10.33
-  __TEXT.__text: 0x1ed910
-  __TEXT.__objc_methlist: 0xd134
-  __TEXT.__const: 0x7aa4
-  __TEXT.__gcc_except_tab: 0x77c8
-  __TEXT.__cstring: 0x17067
+625.2.8.10.7
+  __TEXT.__text: 0x1f77c4
+  __TEXT.__objc_methlist: 0xd35c
+  __TEXT.__const: 0x7d84
+  __TEXT.__gcc_except_tab: 0x7974
+  __TEXT.__cstring: 0x17247
   __TEXT.__ustring: 0x2784
-  __TEXT.__oslogstring: 0xe371
+  __TEXT.__oslogstring: 0xe7f1
   __TEXT.__dlopen_cstrs: 0x157
-  __TEXT.__constg_swiftt: 0x21f4
-  __TEXT.__swift5_typeref: 0x25c2
-  __TEXT.__swift5_reflstr: 0x14fb
-  __TEXT.__swift5_fieldmd: 0x1990
-  __TEXT.__swift5_builtin: 0x140
-  __TEXT.__swift5_assocty: 0x608
-  __TEXT.__swift5_proto: 0x4c8
-  __TEXT.__swift5_types: 0x210
+  __TEXT.__constg_swiftt: 0x2380
+  __TEXT.__swift5_typeref: 0x2706
+  __TEXT.__swift5_reflstr: 0x156b
+  __TEXT.__swift5_fieldmd: 0x1a30
+  __TEXT.__swift5_builtin: 0x17c
+  __TEXT.__swift5_assocty: 0x638
+  __TEXT.__swift5_proto: 0x4e0
+  __TEXT.__swift5_types: 0x224
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__swift_as_entry: 0x32c
-  __TEXT.__swift_as_ret: 0x37c
+  __TEXT.__swift_as_entry: 0x328
+  __TEXT.__swift_as_ret: 0x378
   __TEXT.__swift_as_cont: 0x704
-  __TEXT.__swift5_capture: 0x1490
-  __TEXT.__swift5_protos: 0x2c
+  __TEXT.__swift5_capture: 0x154c
+  __TEXT.__swift5_protos: 0x30
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x9b80
-  __TEXT.__eh_frame: 0xa430
+  __TEXT.__unwind_info: 0x9e40
+  __TEXT.__eh_frame: 0xa760
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x59c0
-  __DATA_CONST.__objc_classlist: 0x6f8
+  __DATA_CONST.__const: 0x5ba8
+  __DATA_CONST.__objc_classlist: 0x708
   __DATA_CONST.__objc_catlist: 0x160
   __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7610
+  __DATA_CONST.__objc_selrefs: 0x7720
   __DATA_CONST.__objc_protorefs: 0xf8
   __DATA_CONST.__objc_superrefs: 0x4c0
   __DATA_CONST.__objc_arraydata: 0x2aa0
-  __DATA_CONST.__got: 0x13b0
-  __AUTH_CONST.__const: 0xb048
-  __AUTH_CONST.__cfstring: 0x1af20
-  __AUTH_CONST.__objc_const: 0x16318
+  __DATA_CONST.__got: 0x13c8
+  __AUTH_CONST.__const: 0xb3f8
+  __AUTH_CONST.__cfstring: 0x1afc0
+  __AUTH_CONST.__objc_const: 0x165f0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x930
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_arrayobj: 0x5a0
-  __AUTH_CONST.__auth_got: 0x21b8
-  __AUTH_CONST.__auth_ptr: 0x9c0
-  __AUTH.__objc_data: 0x2220
-  __AUTH.__data: 0x1010
-  __DATA.__objc_ivar: 0xd30
-  __DATA.__data: 0x3560
-  __DATA.__bss: 0xa420
-  __DATA.__common: 0x88
-  __DATA_DIRTY.__objc_data: 0x2980
-  __DATA_DIRTY.__data: 0xdc8
-  __DATA_DIRTY.__bss: 0x690
+  __AUTH_CONST.__auth_got: 0x21c8
+  __AUTH_CONST.__auth_ptr: 0x9d0
+  __AUTH.__objc_data: 0x748
+  __AUTH.__data: 0x2c8
+  __DATA.__objc_ivar: 0xd34
+  __DATA.__data: 0x37c0
+  __DATA.__bss: 0xa720
+  __DATA.__common: 0xa8
+  __DATA_DIRTY.__objc_data: 0x45e0
+  __DATA_DIRTY.__data: 0x1bb8
+  __DATA_DIRTY.__bss: 0x6b0
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/AppIntents.framework/AppIntents

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11247
-  Symbols:   12027
+  Functions: 11471
+  Symbols:   12130
   CStrings:  0
 
Symbols:
+ +[NSURLSessionConfiguration(SafariCoreExtras) safari_persistentStateSessionConfiguration]
+ +[WBSFeatureAvailability automaticPasswordChangeShouldAlwaysRecommend]
+ +[WBSFeatureAvailability isAutomaticPasswordChangeTestFestModeEnabled]
+ +[WBSFeatureAvailability setAutomaticPasswordChangeTestFestModeEnabled:]
+ +[WBSSavedAccount isDebugAccountForAutomaticPasswordChangeForDomain:]
+ +[WBSSavedAccount isUUIDHighLevelDomain:]
+ -[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]
+ -[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]
+ -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]
+ -[WBSFileVaultRecoveryKeyListenerProxy _synchronousRemoteObjectProxyWithErrorHandler:]
+ -[WBSFileVaultRecoveryKeyListenerProxy deleteRecoveryKeyForVolumeID:serialNumber:error:]
+ -[WBSFileVaultRecoveryKeyListenerProxy recoveryKeyForVolumeID:serialNumber:error:]
+ -[WBSFileVaultRecoveryKeyListenerProxy recoveryKeysForSerialNumber:error:]
+ -[WBSFileVaultRecoveryKeyListenerProxy saveRecoveryKeyWithRequest:error:]
+ -[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]
+ -[WBSPasswordWarningTopFraudTargets emailProviderFraudTargets]
+ -[WBSPasswordWarningTopFraudTargets initWithHighPriorityTargets:targets:financialTargets:emailProviderFraudTargets:]
+ -[WBSSavedAccount _adoptSidecarDataFromSavedAccount:]
+ -[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]
+ -[WBSSavedAccountStore _savedAccountConflictingWithSavedAccountOnInternalQueue:afterUpdatingUsername:password:]
+ -[WBSSavedAccountStore canSaveUser:password:forProtectionSpace:highLevelDomain:notes:customTitle:groupID:completionHandler:]
+ -[WBSSavedAccountStore canSaveUser:password:forUserTypedSite:notes:customTitle:groupID:completionHandler:]
+ -[WBSSavedAccountTreeMatch pruneFileVaultRecoveryKeyTrees]
+ GCC_except_table114
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table123
+ GCC_except_table127
+ GCC_except_table130
+ GCC_except_table133
+ GCC_except_table136
+ GCC_except_table138
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table144
+ GCC_except_table150
+ GCC_except_table152
+ GCC_except_table154
+ GCC_except_table156
+ GCC_except_table158
+ GCC_except_table160
+ GCC_except_table162
+ GCC_except_table164
+ GCC_except_table166
+ GCC_except_table172
+ GCC_except_table174
+ GCC_except_table178
+ GCC_except_table180
+ GCC_except_table182
+ GCC_except_table186
+ GCC_except_table188
+ GCC_except_table190
+ GCC_except_table192
+ GCC_except_table194
+ GCC_except_table196
+ GCC_except_table198
+ GCC_except_table200
+ GCC_except_table202
+ GCC_except_table204
+ GCC_except_table210
+ GCC_except_table212
+ GCC_except_table218
+ GCC_except_table220
+ GCC_except_table222
+ GCC_except_table224
+ GCC_except_table226
+ GCC_except_table229
+ GCC_except_table231
+ GCC_except_table232
+ GCC_except_table234
+ GCC_except_table235
+ GCC_except_table237
+ GCC_except_table239
+ GCC_except_table242
+ GCC_except_table244
+ GCC_except_table247
+ GCC_except_table251
+ GCC_except_table256
+ GCC_except_table258
+ GCC_except_table260
+ GCC_except_table265
+ GCC_except_table270
+ GCC_except_table275
+ GCC_except_table278
+ GCC_except_table280
+ GCC_except_table282
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table297
+ GCC_except_table313
+ GCC_except_table321
+ GCC_except_table323
+ GCC_except_table325
+ GCC_except_table327
+ GCC_except_table333
+ GCC_except_table345
+ GCC_except_table350
+ GCC_except_table352
+ GCC_except_table354
+ GCC_except_table356
+ GCC_except_table361
+ GCC_except_table364
+ GCC_except_table378
+ GCC_except_table380
+ GCC_except_table382
+ GCC_except_table384
+ GCC_except_table386
+ GCC_except_table388
+ GCC_except_table391
+ GCC_except_table393
+ GCC_except_table395
+ GCC_except_table397
+ GCC_except_table407
+ GCC_except_table416
+ GCC_except_table420
+ GCC_except_table422
+ GCC_except_table428
+ GCC_except_table431
+ GCC_except_table436
+ GCC_except_table439
+ GCC_except_table442
+ GCC_except_table444
+ GCC_except_table447
+ GCC_except_table449
+ GCC_except_table453
+ GCC_except_table456
+ GCC_except_table458
+ GCC_except_table461
+ GCC_except_table465
+ GCC_except_table468
+ GCC_except_table480
+ GCC_except_table484
+ GCC_except_table486
+ GCC_except_table488
+ GCC_except_table490
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table496
+ GCC_except_table498
+ GCC_except_table500
+ GCC_except_table502
+ GCC_except_table504
+ GCC_except_table76
+ GCC_except_table89
+ _OBJC_CLASS_$_WBSGuidedBrowsingNavigationEvent
+ _OBJC_CLASS_$_WBSRunLoopCoalescedUpdate
+ _OBJC_IVAR_$_WBSPasswordWarningTopFraudTargets._emailProviderFraudTargets
+ _OBJC_METACLASS_$_WBSGuidedBrowsingNavigationEvent
+ _OBJC_METACLASS_$_WBSRunLoopCoalescedUpdate
+ _WBSAutomaticPasswordChangeDebugLogAutoFilledDataKey
+ _WBSCloudBookmarkListRecordNamePinnedSuggestions
+ _WBSOSLogSearchFeatureAvailability
+ _WBSOSLogSearchFeatureAvailability.log
+ _WBSOSLogSearchFeatureAvailability.onceToken
+ _WBSTimeUntilNextTwiceDailyAnalyticsReportForKey
+ __CLASS_METHODS_WBSGuidedBrowsingNavigationEvent
+ __CLASS_PROPERTIES_WBSGuidedBrowsingNavigationEvent
+ __DATA_WBSGuidedBrowsingNavigationEvent
+ __DATA_WBSRunLoopCoalescedUpdate
+ __INSTANCE_METHODS_WBSGuidedBrowsingNavigationEvent
+ __INSTANCE_METHODS_WBSRunLoopCoalescedUpdate
+ __IVARS_WBSGuidedBrowsingNavigationEvent
+ __IVARS_WBSRunLoopCoalescedUpdate
+ __IVARS__TtCE10SafariCoreV15Synchronization5MutexP33_5EB6CF0E21105A7FACDF3B64E2151CBD10SendingBox
+ __METACLASS_DATA_WBSGuidedBrowsingNavigationEvent
+ __METACLASS_DATA_WBSRunLoopCoalescedUpdate
+ __OBJC_$_INSTANCE_METHODS_WBSAnalyticsLogger(ForegroundReturnAnalyticsLogger)
+ __OBJC_$_INSTANCE_METHODS_WBSSavedAccountChangeRequest(SafariCore)
+ __PROPERTIES_WBSGuidedBrowsingNavigationEvent
+ __PROPERTIES_WBSRunLoopCoalescedUpdate
+ __PROTOCOLS_WBSGuidedBrowsingNavigationEvent
+ __ZL30configureCommonSessionSettingsP25NSURLSessionConfiguration
+ __ZZ72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]E12containerURL
+ __ZZ72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]E9onceToken
+ ___111-[WBSSavedAccountStore _savedAccountConflictingWithSavedAccountOnInternalQueue:afterUpdatingUsername:password:]_block_invoke
+ ___124-[WBSSavedAccountStore canSaveUser:password:forProtectionSpace:highLevelDomain:notes:customTitle:groupID:completionHandler:]_block_invoke
+ ___49-[WBSSavedAccount lastUsedDateForSite:inContext:]_block_invoke
+ ___58-[WBSSavedAccountTreeMatch pruneFileVaultRecoveryKeyTrees]_block_invoke
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_2
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_3
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_4
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_5
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_6
+ ___69-[WBSPasswordWarningManager _getAllWarningsOnWorkQueueForcingUpdate:]_block_invoke_7
+ ___72-[NSFileManager(SafariNSFileManagerExtras) safari_pebbleSafariContainer]_block_invoke
+ ___73-[WBSFileVaultRecoveryKeyListenerProxy saveRecoveryKeyWithRequest:error:]_block_invoke
+ ___73-[WBSFileVaultRecoveryKeyListenerProxy saveRecoveryKeyWithRequest:error:]_block_invoke_2
+ ___74-[WBSFileVaultRecoveryKeyListenerProxy recoveryKeysForSerialNumber:error:]_block_invoke
+ ___74-[WBSFileVaultRecoveryKeyListenerProxy recoveryKeysForSerialNumber:error:]_block_invoke_2
+ ___81-[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]_block_invoke
+ ___81-[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]_block_invoke_2
+ ___82-[WBSFileVaultRecoveryKeyListenerProxy recoveryKeyForVolumeID:serialNumber:error:]_block_invoke
+ ___82-[WBSFileVaultRecoveryKeyListenerProxy recoveryKeyForVolumeID:serialNumber:error:]_block_invoke_2
+ ___86-[WBSFileVaultRecoveryKeyListenerProxy _synchronousRemoteObjectProxyWithErrorHandler:]_block_invoke
+ ___88-[WBSFileVaultRecoveryKeyListenerProxy deleteRecoveryKeyForVolumeID:serialNumber:error:]_block_invoke
+ ___88-[WBSFileVaultRecoveryKeyListenerProxy deleteRecoveryKeyForVolumeID:serialNumber:error:]_block_invoke_2
+ ___94-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]_block_invoke
+ ___94-[WBSSavedAccountStore canSaveUser:password:forUserTypedSite:notes:customTitle:groupID:error:]_block_invoke
+ ___96-[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]_block_invoke
+ ___96-[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]_block_invoke_2
+ ___WBSOSLogSearchFeatureAvailability_block_invoke
+ ___block_descriptor_32_e30_B16?0"WBSSavedAccountMatch"8l
+ ___block_descriptor_32_e32_B32?0"WBSSavedAccount"8Q16^B24l
+ ___block_descriptor_40_e8_32bs_e36_v16?0"WBSSavedAccountMatchResult"8ls32l8
+ ___block_descriptor_40_e8_32r_e49_v32?0q8"<WBSSavedAccountSidecarInternal>"16^B24lr32l8
+ ___block_descriptor_41_e8_32s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8
+ ___block_descriptor_48_e8_32r40r_e17_v16?0"NSError"8lr32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e8_v12?0B8lr40l8s32l8
+ ___block_descriptor_56_e8_32r40r48r_e29_v24?0"NSArray"8"NSError"16lr32l8r40l8r48l8
+ ___block_descriptor_56_e8_32r40r48r_e45_v24?0"WBSFileVaultRecoveryKey"8"NSError"16lr32l8r40l8r48l8
+ ___block_descriptor_56_e8_32s40r48r_e20_v20?0B8"NSError"12lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
+ ___block_descriptor_56_e8_32s40s48r_e46_v32?0"NSString"8"NSMutableDictionary"16^B24lr48l8s32l8s40l8
+ ___block_descriptor_73_e8_32s40s48s56s64r_e42_v32?0"NSString"8"WBSSavedAccount"16^B24ls32l8s40l8s48l8s56l8r64l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80s88bs_e5_v8?0ls32l8s40l8s48l8s88l8s56l8s64l8s72l8s80l8
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.242Tm
+ ___swift_closure_destructor.252Tm
+ ___swift_closure_destructor.433Tm
+ ___swift_closure_destructor.491Tm
+ ___swift_closure_destructor.54Tm
+ ___swift_closure_destructor.58Tm
+ ___swift_closure_destructor.611Tm
+ ___unnamed_2
+ _associated conformance So13NSRunLoopModeaSHSCSQ
+ _associated conformance So13NSRunLoopModeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So13NSRunLoopModeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _automaticPasswordChangeTestFestModeEnabled
+ _container_get_path
+ _container_query_set_group_identifiers
+ _finalizeSyncResult
+ _symbolic $s10SafariCore45WBSAutomaticPasswordChangeCompletionReportingP
+ _symbolic SS_So8NSObjectCt
+ _symbolic Shy_____G 10Foundation4UUIDV
+ _symbolic So25WBSRunLoopCoalescedUpdateCSgXw
+ _symbolic _____ 10SafariCore32WBSGuidedBrowsingNavigationEventC
+ _symbolic _____ 15Synchronization5MutexV10SafariCoreE10SendingBox33_5EB6CF0E21105A7FACDF3B64E2151CBDLLC
+ _symbolic _____ So13NSRunLoopModea
+ _symbolic _____ So35WBSAnalyticsForegroundReturnOutcomeV
+ _symbolic _____ So43WBSAnalyticsForegroundReturnAwayDurationBinV
+ _symbolic _____SgXwz_Xx 10SafariCore27WBSGuidedBrowsingControllerC
+ _symbolic ______pIeghg_ 10SafariCore39WBSGuidedBrowsingUIRegistrationProtocolP
+ _symbolic _____m 10SafariCore32WBSGuidedBrowsingNavigationEventC
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySbG 15Synchronization6AtomicV
+ _symbolic _____yShy_____GG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____ySo15NSXPCConnectionCSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So13NSRunLoopModea
+ _symbolic _____yxG 15Synchronization5MutexVAARi_zrlE
- +[WBSFeatureAvailability isAllowFavoritesInFrequentlyVisitedEnabled]
- +[WBSFeatureAvailability isAllowLogOnURLsInFrequentlyVisitedEnabled]
- +[WBSFeatureAvailability isDropOutliersInFrequentlyVisitedEnabled]
- -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]
- -[WBSPasswordWarningTopFraudTargets initWithHighPriorityTargets:targets:financialTargets:]
- -[WBSWellKnownChangePasswordURLFallbackController didFinishLoad]
- GCC_except_table115
- GCC_except_table122
- GCC_except_table124
- GCC_except_table125
- GCC_except_table128
- GCC_except_table132
- GCC_except_table134
- GCC_except_table135
- GCC_except_table139
- GCC_except_table141
- GCC_except_table143
- GCC_except_table145
- GCC_except_table151
- GCC_except_table153
- GCC_except_table155
- GCC_except_table157
- GCC_except_table159
- GCC_except_table161
- GCC_except_table163
- GCC_except_table165
- GCC_except_table171
- GCC_except_table173
- GCC_except_table175
- GCC_except_table177
- GCC_except_table183
- GCC_except_table187
- GCC_except_table189
- GCC_except_table191
- GCC_except_table193
- GCC_except_table195
- GCC_except_table197
- GCC_except_table199
- GCC_except_table201
- GCC_except_table203
- GCC_except_table205
- GCC_except_table211
- GCC_except_table213
- GCC_except_table219
- GCC_except_table221
- GCC_except_table223
- GCC_except_table225
- GCC_except_table227
- GCC_except_table230
- GCC_except_table233
- GCC_except_table236
- GCC_except_table238
- GCC_except_table240
- GCC_except_table241
- GCC_except_table243
- GCC_except_table246
- GCC_except_table252
- GCC_except_table257
- GCC_except_table259
- GCC_except_table263
- GCC_except_table266
- GCC_except_table271
- GCC_except_table277
- GCC_except_table279
- GCC_except_table281
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table296
- GCC_except_table304
- GCC_except_table311
- GCC_except_table322
- GCC_except_table324
- GCC_except_table326
- GCC_except_table330
- GCC_except_table335
- GCC_except_table344
- GCC_except_table346
- GCC_except_table351
- GCC_except_table353
- GCC_except_table355
- GCC_except_table357
- GCC_except_table362
- GCC_except_table377
- GCC_except_table379
- GCC_except_table381
- GCC_except_table383
- GCC_except_table385
- GCC_except_table387
- GCC_except_table390
- GCC_except_table392
- GCC_except_table394
- GCC_except_table396
- GCC_except_table406
- GCC_except_table411
- GCC_except_table415
- GCC_except_table418
- GCC_except_table424
- GCC_except_table429
- GCC_except_table437
- GCC_except_table440
- GCC_except_table443
- GCC_except_table445
- GCC_except_table448
- GCC_except_table450
- GCC_except_table454
- GCC_except_table460
- GCC_except_table464
- GCC_except_table467
- GCC_except_table469
- GCC_except_table481
- GCC_except_table485
- GCC_except_table487
- GCC_except_table489
- GCC_except_table491
- GCC_except_table493
- GCC_except_table495
- GCC_except_table497
- GCC_except_table499
- GCC_except_table501
- GCC_except_table503
- GCC_except_table67
- GCC_except_table78
- GCC_except_table82
- GCC_except_table91
- _WBSEnableDropOutliersInFrequentlyVisitedKey
- _WBSFrequentlyVisitedSitesAllowLogonURLsPreferenceKey
- _WBSFrequentlyVisitedSitesAllowSitesFromFavoritesPreferenceKey
- __OBJC_$_CLASS_PROP_LIST_NSURLSessionConfiguration_$_SafariCoreExtras
- __OBJC_$_INSTANCE_METHODS_WBSAnalyticsLogger
- __OBJC_$_INSTANCE_METHODS_WBSSavedAccountChangeRequest
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_2
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_3
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_4
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_5
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_6
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_7
- ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_8
- ___79-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]_block_invoke
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88r96r_e5_v8?0ls32l8s40l8r88l8r96l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_48_e8_32s40s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8s40l8
- ___swift_closure_destructor.236Tm
- ___swift_closure_destructor.246Tm
- ___swift_closure_destructor.427Tm
- ___swift_closure_destructor.485Tm
- ___swift_closure_destructor.53Tm
- ___swift_closure_destructor.57Tm
- ___swift_closure_destructor.605Tm
- _symbolic So15NSXPCConnectionC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10SafariCore26WBSLocalizedPluralVariableV
```
