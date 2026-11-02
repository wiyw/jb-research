## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices`

```diff

-3600.68.61.11.11
-  __TEXT.__text: 0x19e234
-  __TEXT.__objc_methlist: 0x1f094
+3605.31.1.11.2
+  __TEXT.__text: 0x1a35d8
+  __TEXT.__objc_methlist: 0x1f544
   __TEXT.__const: 0x3d0
   __TEXT.__dlopen_cstrs: 0x538
-  __TEXT.__gcc_except_tab: 0x21b8
-  __TEXT.__cstring: 0x3d3fa
-  __TEXT.__oslogstring: 0xf5ac
+  __TEXT.__gcc_except_tab: 0x21e0
+  __TEXT.__cstring: 0x3ded9
+  __TEXT.__oslogstring: 0xfd05
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x8170
+  __TEXT.__unwind_info: 0x82a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x85f0
-  __DATA_CONST.__objc_classlist: 0xef8
+  __DATA_CONST.__const: 0x87c0
+  __DATA_CONST.__objc_classlist: 0xf00
   __DATA_CONST.__objc_catlist: 0x2a8
-  __DATA_CONST.__objc_protolist: 0x5e8
+  __DATA_CONST.__objc_protolist: 0x608
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc0f0
-  __DATA_CONST.__objc_protorefs: 0x170
-  __DATA_CONST.__objc_superrefs: 0xf10
-  __DATA_CONST.__objc_arraydata: 0x23a0
-  __DATA_CONST.__got: 0x16d0
-  __AUTH_CONST.__const: 0x3ca0
-  __AUTH_CONST.__cfstring: 0x28480
-  __AUTH_CONST.__objc_const: 0x36340
-  __AUTH_CONST.__objc_intobj: 0x2628
-  __AUTH_CONST.__objc_dictobj: 0xcf8
+  __DATA_CONST.__objc_selrefs: 0xc320
+  __DATA_CONST.__objc_protorefs: 0x178
+  __DATA_CONST.__objc_superrefs: 0xf18
+  __DATA_CONST.__objc_arraydata: 0x2450
+  __DATA_CONST.__got: 0x1700
+  __AUTH_CONST.__const: 0x3e00
+  __AUTH_CONST.__cfstring: 0x28a40
+  __AUTH_CONST.__objc_const: 0x368c8
+  __AUTH_CONST.__objc_intobj: 0x2730
+  __AUTH_CONST.__objc_dictobj: 0xd20
   __AUTH_CONST.__objc_arrayobj: 0x5d0
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0xae8
+  __AUTH_CONST.__auth_got: 0xae0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x8610
-  __AUTH.__data: 0x248
-  __DATA.__objc_ivar: 0x257c
-  __DATA.__data: 0x4800
-  __DATA.__bss: 0x13a0
+  __AUTH.__objc_data: 0x84f8
+  __AUTH.__data: 0x280
+  __DATA.__objc_ivar: 0x25c8
+  __DATA.__data: 0x4988
+  __DATA.__bss: 0x1480
   __DATA.__common: 0x18
-  __DATA_DIRTY.__objc_data: 0xfa0
+  __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x18
-  __DATA_DIRTY.__bss: 0x200
+  __DATA_DIRTY.__bss: 0x1c8
   __DATA_DIRTY.__common: 0xf8
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12116
-  Symbols:   22222
+  Functions: 12257
+  Symbols:   22458
   CStrings:  0
 
Symbols:
+ +[AFFeatureFlags(SWEFeatureFlags) isAceSyncDisabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isAppExclusionsEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isCloudKitCacheMirroredChangeTokensEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isLinwoodModalityConnectionSkipEnabled]
+ +[AFFeatureFlags(SWEFeatureFlags) isSiriCapabilitiesSettleCoalescingDisabled]
+ +[AFFeatureFlags(SWEFeatureFlags) siriAvailabilityOverXPCEnabled]
+ -[AFCompanionDeviceInfo buildVersion]
+ -[AFCompanionDeviceInfo ifpCapableDevice]
+ -[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:]
+ -[AFCompanionDeviceInfo linwoodCapableDevice]
+ -[AFCompanionDeviceInfo linwoodEnabled]
+ -[AFCompanionDeviceInfo siriAvailability]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:]
+ -[AFCompanionDeviceInfo(BackwardCompatibility) initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:]
+ -[AFCompanionDeviceInfo(SiriAvailability) createSiriAvailability]
+ -[AFConnection _cleanupRoutingStandby]
+ -[AFConnection _endUsefulUserFacingResultsIntervalIfNeeded]
+ -[AFConnection _replyMissingDelegateMethodTo:]
+ -[AFConnection _resetSpeechTimingForSpeechRequest:options:systemUptime:]
+ -[AFConnection notifyAppLaunchWillBePresentedToUser]
+ -[AFConnection scdaStandbyDidBegin]
+ -[AFConnection scdaStandbyDidEndAsWon:]
+ -[AFConnection siriDidBecomeEffectivelyActive]
+ -[AFConnection siriDidBecomeEffectivelyInactive]
+ -[AFConnectionClientServiceDelegate notifyAppLaunchWillBePresentedToUser]
+ -[AFConnectionEntitlementCache cacheEntitlement:forPID:pidVersion:bundleID:]
+ -[AFConnectionEntitlementCache hasEntitlement:forPID:pidVersion:]
+ -[AFDictationOptions applicationProcessIdentifier]
+ -[AFDictationOptions setApplicationProcessIdentifier:]
+ -[AFDisambiguationOutcomeDescriptor selectsAll]
+ -[AFDisambiguationOutcomeDescriptor setSelectsAll:]
+ -[AFLocalTurnStatusService .cxx_destruct]
+ -[AFLocalTurnStatusService connection]
+ -[AFLocalTurnStatusService currentLocalTurnStatus:]
+ -[AFLocalTurnStatusService dealloc]
+ -[AFLocalTurnStatusService serviceWithErrorHandler:]
+ -[AFLocalTurnStatusService setConnection:]
+ -[AFMultiArgumentSafetyBlock dealloc]
+ -[AFMultiUserConnection isRecognizeMyVoiceEnabledForAnyUser:]
+ -[AFPreferences _setLinwoodEnabledMeDevice:]
+ -[AFPreferences announceNotificationsInCarPlayTemporarilyDisabled]
+ -[AFPreferences assistantEnabledBeforeRestrictionIsCurrentVersion]
+ -[AFPreferences fetchUseWithSiriEnabledForApp:completion:]
+ -[AFPreferences fetchUseWithSiriStateForApp:completion:]
+ -[AFPreferences linwoodEnabledMeDevice]
+ -[AFPreferences updateUseWithSiriEnabled:forApp:]
+ -[AFRequestInfo myriadElectionIdentity]
+ -[AFSettingsConnection armAnnounceOverrideFollowUpText:reply:]
+ -[AFSettingsConnection forceWeeklyCloudKitSyncWithCompletion:]
+ -[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]
+ -[AFSettingsConnection(Internal) _syncDataWithAnchorKeys:forceReset:reason:completionWithError:]
+ -[AFSiriAnnounceWorkoutVoiceFeedbackRequest performRequestWithResultCompletion:]
+ -[AFSiriAvailability createDictionaryExcludingBootSession]
+ -[AFSiriAvailability initWithDictionary:]
+ -[AFSiriAvailability initWithSiriLanguageCode:]
+ -[AFSiriAvailability isLinwoodAccessRestricted]
+ -[AFSiriAvailability isLinwoodGMSAvailable]
+ -[AFSiriAvailability isLinwoodGMSEnabled]
+ -[AFSiriCapabilitiesServiceClient siriAvailability:]
+ -[AFSiriCapabilitiesServiceClient siriAvailabilitySync]
+ -[AFSpeechRequestOptions isReplyToSiriPrompt]
+ -[AFSpeechRequestOptions myriadElectionIdentity]
+ -[AFSpeechRequestOptions setIsReplyToSiriPrompt:]
+ -[AFSpeechRequestOptions setMyriadElectionIdentity:]
+ -[_AFCompanionDeviceInfoMutation getBuildVersion]
+ -[_AFCompanionDeviceInfoMutation getIfpCapableDevice]
+ -[_AFCompanionDeviceInfoMutation getLinwoodCapableDevice]
+ -[_AFCompanionDeviceInfoMutation getLinwoodEnabled]
+ -[_AFCompanionDeviceInfoMutation getSiriAvailability]
+ -[_AFCompanionDeviceInfoMutation setBuildVersion:]
+ -[_AFCompanionDeviceInfoMutation setIfpCapableDevice:]
+ -[_AFCompanionDeviceInfoMutation setLinwoodCapableDevice:]
+ -[_AFCompanionDeviceInfoMutation setLinwoodEnabled:]
+ -[_AFCompanionDeviceInfoMutation setSiriAvailability:]
+ GCC_except_table10058
+ GCC_except_table10266
+ GCC_except_table10306
+ GCC_except_table10337
+ GCC_except_table10342
+ GCC_except_table10343
+ GCC_except_table10347
+ GCC_except_table10536
+ GCC_except_table10707
+ GCC_except_table10736
+ GCC_except_table10833
+ GCC_except_table10837
+ GCC_except_table10841
+ GCC_except_table10870
+ GCC_except_table1121
+ GCC_except_table11224
+ GCC_except_table11226
+ GCC_except_table11229
+ GCC_except_table11238
+ GCC_except_table11304
+ GCC_except_table11325
+ GCC_except_table11350
+ GCC_except_table11356
+ GCC_except_table11515
+ GCC_except_table11519
+ GCC_except_table11521
+ GCC_except_table11524
+ GCC_except_table11530
+ GCC_except_table11534
+ GCC_except_table11540
+ GCC_except_table11747
+ GCC_except_table1187
+ GCC_except_table1193
+ GCC_except_table12071
+ GCC_except_table12205
+ GCC_except_table12208
+ GCC_except_table12210
+ GCC_except_table1314
+ GCC_except_table1316
+ GCC_except_table1534
+ GCC_except_table1540
+ GCC_except_table1546
+ GCC_except_table1566
+ GCC_except_table1572
+ GCC_except_table1575
+ GCC_except_table1941
+ GCC_except_table2055
+ GCC_except_table2186
+ GCC_except_table2309
+ GCC_except_table2322
+ GCC_except_table2323
+ GCC_except_table2335
+ GCC_except_table2342
+ GCC_except_table2343
+ GCC_except_table2346
+ GCC_except_table2352
+ GCC_except_table238
+ GCC_except_table2399
+ GCC_except_table2401
+ GCC_except_table2403
+ GCC_except_table2421
+ GCC_except_table2427
+ GCC_except_table244
+ GCC_except_table2470
+ GCC_except_table2482
+ GCC_except_table250
+ GCC_except_table264
+ GCC_except_table2725
+ GCC_except_table2738
+ GCC_except_table2742
+ GCC_except_table2754
+ GCC_except_table2758
+ GCC_except_table2871
+ GCC_except_table2873
+ GCC_except_table2951
+ GCC_except_table2995
+ GCC_except_table3361
+ GCC_except_table3368
+ GCC_except_table3374
+ GCC_except_table3376
+ GCC_except_table3378
+ GCC_except_table3423
+ GCC_except_table3425
+ GCC_except_table3431
+ GCC_except_table3437
+ GCC_except_table3441
+ GCC_except_table3447
+ GCC_except_table3454
+ GCC_except_table3456
+ GCC_except_table3461
+ GCC_except_table3463
+ GCC_except_table3468
+ GCC_except_table3480
+ GCC_except_table3483
+ GCC_except_table3497
+ GCC_except_table3499
+ GCC_except_table3501
+ GCC_except_table3503
+ GCC_except_table3505
+ GCC_except_table3507
+ GCC_except_table3509
+ GCC_except_table3555
+ GCC_except_table3581
+ GCC_except_table3638
+ GCC_except_table366
+ GCC_except_table3674
+ GCC_except_table385
+ GCC_except_table389
+ GCC_except_table4079
+ GCC_except_table4368
+ GCC_except_table4569
+ GCC_except_table4577
+ GCC_except_table4635
+ GCC_except_table5011
+ GCC_except_table5015
+ GCC_except_table5060
+ GCC_except_table5066
+ GCC_except_table5091
+ GCC_except_table5097
+ GCC_except_table5312
+ GCC_except_table5432
+ GCC_except_table5465
+ GCC_except_table5468
+ GCC_except_table5545
+ GCC_except_table5549
+ GCC_except_table5559
+ GCC_except_table5570
+ GCC_except_table5583
+ GCC_except_table5668
+ GCC_except_table5670
+ GCC_except_table5694
+ GCC_except_table5810
+ GCC_except_table5873
+ GCC_except_table5876
+ GCC_except_table5880
+ GCC_except_table5897
+ GCC_except_table5911
+ GCC_except_table593
+ GCC_except_table5985
+ GCC_except_table6043
+ GCC_except_table6069
+ GCC_except_table6348
+ GCC_except_table644
+ GCC_except_table6494
+ GCC_except_table6507
+ GCC_except_table6552
+ GCC_except_table6646
+ GCC_except_table6831
+ GCC_except_table6917
+ GCC_except_table6971
+ GCC_except_table7207
+ GCC_except_table7210
+ GCC_except_table7211
+ GCC_except_table7408
+ GCC_except_table7467
+ GCC_except_table7681
+ GCC_except_table7684
+ GCC_except_table7696
+ GCC_except_table7697
+ GCC_except_table7710
+ GCC_except_table7711
+ GCC_except_table7712
+ GCC_except_table7718
+ GCC_except_table7756
+ GCC_except_table7762
+ GCC_except_table7768
+ GCC_except_table7836
+ GCC_except_table7838
+ GCC_except_table7873
+ GCC_except_table7876
+ GCC_except_table7987
+ GCC_except_table8050
+ GCC_except_table8052
+ GCC_except_table8054
+ GCC_except_table8056
+ GCC_except_table8070
+ GCC_except_table8076
+ GCC_except_table8201
+ GCC_except_table8205
+ GCC_except_table8210
+ GCC_except_table845
+ GCC_except_table848
+ GCC_except_table855
+ GCC_except_table8587
+ GCC_except_table8602
+ GCC_except_table8609
+ GCC_except_table8625
+ GCC_except_table8694
+ GCC_except_table8703
+ GCC_except_table8733
+ GCC_except_table8771
+ GCC_except_table8772
+ GCC_except_table8773
+ GCC_except_table8798
+ GCC_except_table8822
+ GCC_except_table9182
+ GCC_except_table9187
+ GCC_except_table9190
+ GCC_except_table9193
+ GCC_except_table9196
+ GCC_except_table9199
+ GCC_except_table9202
+ GCC_except_table9205
+ GCC_except_table9208
+ GCC_except_table9211
+ GCC_except_table9384
+ GCC_except_table9387
+ GCC_except_table9448
+ GCC_except_table9456
+ GCC_except_table9461
+ GCC_except_table9474
+ GCC_except_table9634
+ GCC_except_table9734
+ GCC_except_table986
+ GCC_except_table9923
+ GCC_except_table9928
+ _AFDaemonIsExitingCleanly
+ _AFDaemonWillExitCleanlyNotification
+ _AFIsHomePod
+ _AFIsHomePod.isHomePod
+ _AFIsHomePod.onceToken
+ _AFIsJ265
+ _AFIsJ265.isJ265
+ _AFIsJ265.onceToken
+ _AFIsWaffleiron
+ _AFMeDeviceLinwoodEnablementDidChangeNotification
+ _AFResetDaemonIsExitingCleanlyForTesting
+ _AFSimulateDaemonWillExitCleanlyForTesting
+ _AFSiriActivationOdeonProxyVoiceTrigger
+ _AFSiriWorkoutVoiceFeedbackResultGetFromName
+ _AFSiriWorkoutVoiceFeedbackResultGetFromName.map
+ _AFSiriWorkoutVoiceFeedbackResultGetFromName.onceToken
+ _AFSiriWorkoutVoiceFeedbackResultGetIsValid
+ _AFSiriWorkoutVoiceFeedbackResultGetIsValidAndSpecified
+ _AFSiriWorkoutVoiceFeedbackResultGetName
+ _AFUseWithSiriAvailableForApp
+ _AFUseWithSiriEnabledForApp
+ _AFUseWithSiriSetEnabled
+ _AFVisualIntelligenceCameraRestricted.once
+ _CFBundleCreate
+ _IntentsLibrary.sLib
+ _IntentsLibrary.sOnce
+ _LSBundleProxyFunction
+ _LSSystemApplicationTypeFunction
+ _OBJC_CLASS_$_AFLocalTurnStatusService
+ _OBJC_CLASS_$_NSExtension
+ _OBJC_CLASS_$_SAUIStreamChunk
+ _OBJC_CLASS_$_SCDAElectionIdentity
+ _OBJC_CLASS_$_SCDAFeatureFlags
+ _OBJC_CLASS_$_SCDAStandbyObserver
+ _OBJC_IVAR_$_AFCompanionDeviceInfo._buildVersion
+ _OBJC_IVAR_$_AFCompanionDeviceInfo._ifpCapableDevice
+ _OBJC_IVAR_$_AFCompanionDeviceInfo._linwoodCapableDevice
+ _OBJC_IVAR_$_AFCompanionDeviceInfo._linwoodEnabled
+ _OBJC_IVAR_$_AFCompanionDeviceInfo._siriAvailability
+ _OBJC_IVAR_$_AFConnection._isInRoutingStandby
+ _OBJC_IVAR_$_AFConnectionEntitlementCache._bundleIDToKeyMap
+ _OBJC_IVAR_$_AFDictationOptions._applicationProcessIdentifier
+ _OBJC_IVAR_$_AFDisambiguationOutcomeDescriptor._selectsAll
+ _OBJC_IVAR_$_AFLocalTurnStatusService._connection
+ _OBJC_IVAR_$_AFLocalization._cachedVoiceMaps
+ _OBJC_IVAR_$_AFLocalization._cachedVoiceMapsSource
+ _OBJC_IVAR_$_AFLocalization._voiceMapsLock
+ _OBJC_IVAR_$_AFSpeechRequestOptions._isReplyToSiriPrompt
+ _OBJC_IVAR_$_AFSpeechRequestOptions._myriadElectionIdentity
+ _OBJC_IVAR_$__AFCompanionDeviceInfoMutation._buildVersion
+ _OBJC_IVAR_$__AFCompanionDeviceInfoMutation._ifpCapableDevice
+ _OBJC_IVAR_$__AFCompanionDeviceInfoMutation._linwoodCapableDevice
+ _OBJC_IVAR_$__AFCompanionDeviceInfoMutation._linwoodEnabled
+ _OBJC_IVAR_$__AFCompanionDeviceInfoMutation._siriAvailability
+ _OBJC_METACLASS_$_AFLocalTurnStatusService
+ _TCCLibrary.sLib
+ _TCCLibrary.sOnce
+ __AFBeginExitingCleanly
+ __AFCopyBundleForAppID
+ __AFPreferencesAnnouncementPlatformOverride
+ __AFPreferencesCachedLanguageValue
+ __AFPreferencesIsAnnouncementPlatformOverrideActive
+ __AFPreferencesLanguageCacheGenerationForTesting
+ __AFPreferencesObserveLanguageChanges.observerOnceToken
+ __AFPreferencesSetAnnouncementPlatformOverride
+ __AFPreferencesSetLanguageCacheDidComputeHookForTesting
+ __AFPreferencesSetSiriPersonalContentSetting
+ __AFPreferencesSiriPersonalContentSetting
+ __OBJC_$_CATEGORY_AceObject_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSNull_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CATEGORY_NSURL_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_CLASS_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
+ __OBJC_$_CLASS_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_CLASS_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_INSTANCE_METHODS_AFClockTimer(AFClockTimerMutability|ClockItem)
+ __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(BackwardCompatibility|SiriAvailability|AFCompanionDeviceInfoMutability)
+ __OBJC_$_INSTANCE_METHODS_AFLocalTurnStatusService
+ __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
+ __OBJC_$_INSTANCE_METHODS_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_$_INSTANCE_METHODS_NSArray(AFSecurityDigestibleChunksProvider|AFCollectionUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSDate(AFSecurityDigestibleChunksProvider|AssistantAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSDictionary(AFSecurityDigestibleChunksProvider|AFCollectionUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSNull(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport)
+ __OBJC_$_INSTANCE_METHODS_NSString(AFSecurityDigestibleChunksProvider|AFPreferences|AssistantServices|AFSiriRequest|ShortDescription)
+ __OBJC_$_INSTANCE_METHODS_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_$_INSTANCE_VARIABLES_AFLocalTurnStatusService
+ __OBJC_$_PROP_LIST_AFLocalTurnStatusService
+ __OBJC_$_PROP_LIST_AFPreferences
+ __OBJC_$_PROP_LIST_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROP_LIST_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFLocalTurnStatusServiceInterface
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFPreferencesProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCDAStandbyListening
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AFLocalTurnStatusServiceInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AFPreferencesProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SCDAStandbyListening
+ __OBJC_$_PROTOCOL_REFS_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_REFS_AFPreferencesProviding
+ __OBJC_$_PROTOCOL_REFS_SCDAStandbyListening
+ __OBJC_CATEGORY_PROTOCOLS_$_NSArray_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSDate_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSDictionary_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CATEGORY_PROTOCOLS_$_NSString_$_AFSecurityDigestibleChunksProvider
+ __OBJC_CLASS_PROTOCOLS_$_AFClockTimer(AFClockTimerMutability|ClockItem)
+ __OBJC_CLASS_PROTOCOLS_$_AFPreferences
+ __OBJC_CLASS_PROTOCOLS_$_AceObject(AFSecurityDigestibleChunksProvider|AssistantAdditions|AnalyticsContextVending)
+ __OBJC_CLASS_PROTOCOLS_$_NSNull(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport)
+ __OBJC_CLASS_PROTOCOLS_$_NSURL(AFSecurityDigestibleChunksProvider|AFBundleResourceSupport|AMOSExtensions|STSiriMessage)
+ __OBJC_CLASS_RO_$_AFLocalTurnStatusService
+ __OBJC_LABEL_PROTOCOL_$_AFLocalTurnStatusServiceInterface
+ __OBJC_LABEL_PROTOCOL_$_AFPreferencesInternalProviding
+ __OBJC_LABEL_PROTOCOL_$_AFPreferencesProviding
+ __OBJC_LABEL_PROTOCOL_$_SCDAStandbyListening
+ __OBJC_METACLASS_RO_$_AFLocalTurnStatusService
+ __OBJC_PROTOCOL_$_AFLocalTurnStatusServiceInterface
+ __OBJC_PROTOCOL_$_AFPreferencesInternalProviding
+ __OBJC_PROTOCOL_$_AFPreferencesProviding
+ __OBJC_PROTOCOL_$_SCDAStandbyListening
+ __OBJC_PROTOCOL_REFERENCE_$_AFLocalTurnStatusServiceInterface
+ ___294-[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:]_block_invoke
+ ___35-[AFConnection scdaStandbyDidBegin]_block_invoke
+ ___39-[AFConnection scdaStandbyDidEndAsWon:]_block_invoke
+ ___51-[AFLocalTurnStatusService currentLocalTurnStatus:]_block_invoke
+ ___51-[AFLocalTurnStatusService currentLocalTurnStatus:]_block_invoke_2
+ ___52-[AFSiriCapabilitiesServiceClient siriAvailability:]_block_invoke
+ ___52-[AFSiriCapabilitiesServiceClient siriAvailability:]_block_invoke_2
+ ___55-[AFSiriCapabilitiesServiceClient siriAvailabilitySync]_block_invoke
+ ___55-[AFSiriCapabilitiesServiceClient siriAvailabilitySync]_block_invoke_2
+ ___56-[AFPreferences fetchUseWithSiriStateForApp:completion:]_block_invoke
+ ___56-[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]_block_invoke
+ ___56-[AFSettingsConnection isLinwoodEnabledOnAnyHomeDevice:]_block_invoke_2
+ ___61-[AFMultiUserConnection isRecognizeMyVoiceEnabledForAnyUser:]_block_invoke
+ ___61-[AFMultiUserConnection isRecognizeMyVoiceEnabledForAnyUser:]_block_invoke_2
+ ___62-[AFSettingsConnection armAnnounceOverrideFollowUpText:reply:]_block_invoke
+ ___62-[AFSettingsConnection forceWeeklyCloudKitSyncWithCompletion:]_block_invoke
+ ___73-[AFConnectionClientServiceDelegate notifyAppLaunchWillBePresentedToUser]_block_invoke
+ ___80-[AFSiriAnnounceWorkoutVoiceFeedbackRequest performRequestWithResultCompletion:]_block_invoke
+ ___96-[AFSettingsConnection(Internal) _syncDataWithAnchorKeys:forceReset:reason:completionWithError:]_block_invoke
+ ___AFIsHomePod_block_invoke
+ ___AFIsJ265_block_invoke
+ ___AFSiriActivationOdeonProxyVoiceTrigger_block_invoke
+ ___AFSiriWorkoutVoiceFeedbackResultGetFromName_block_invoke
+ ___AFUseWithSiriAvailableForApp_block_invoke
+ ___AFVisualIntelligenceCameraRestricted_block_invoke
+ ___IntentsLibrary_block_invoke
+ ___TCCLibrary_block_invoke
+ ____AFPreferencesObserveLanguageChanges_block_invoke
+ ____AFPreferencesObserveLanguageChanges_block_invoke_2
+ ___block_descriptor_119_e8_32s40s48s56s64s72s80s88s96s104s_e41_v16?0"<AFCompanionDeviceInfoMutating>"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
+ ___block_descriptor_32_e8_16?0Q8l
+ ___block_descriptor_40_e8_32bs_e21_v24?0Q8"NSString"16ls32l8
+ ___block_descriptor_40_e8_32r_e28_v16?0"AFSiriAvailability"8lr32l8
+ ___block_descriptor_40_e8_32s_e25_v32?0"NSString"8Q16^B24ls32l8
+ ___block_descriptor_48_e8_32bs40r_e28_v16?0"AFSiriAvailability"8ls32l8r40l8
+ ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_90_e8_32s40s48s56s64bs_e33_v16?0"AceObject<SAAceCommand>"8ls32l8s64l8s40l8s48l8s56l8
+ ___block_descriptor_98_e8_32s40s48s56s64s72bs_e5_v8?0ls32l8s72l8s40l8s48l8s56l8s64l8
+ ___initLSBundleProxy_block_invoke
+ ___initLSSystemApplicationType_block_invoke
+ ___initkTCCInfoGranted_block_invoke
+ ___initkTCCInfoService_block_invoke
+ ___initkTCCServiceSiri_block_invoke
+ _classLSBundleProxy
+ _constantLSSystemApplicationType
+ _constantkTCCInfoGranted
+ _constantkTCCInfoService
+ _constantkTCCServiceSiri
+ _getLSBundleProxyClass
+ _getLSSystemApplicationType
+ _getkTCCInfoGranted
+ _getkTCCInfoService
+ _getkTCCServiceSiri
+ _initLSBundleProxy
+ _initLSBundleProxy.sOnce
+ _initLSSystemApplicationType
+ _initLSSystemApplicationType.sOnce
+ _initTCCAccessCopyInformationForBundle
+ _initTCCAccessSetForBundle
+ _initkTCCInfoGranted
+ _initkTCCInfoGranted.sOnce
+ _initkTCCInfoService
+ _initkTCCInfoService.sOnce
+ _initkTCCServiceSiri
+ _initkTCCServiceSiri.sOnce
+ _kAFLinwoodEnabledMeDeviceKey
+ _kAFLocalTurnStatusServiceEntitlement
+ _kAFLocalTurnStatusServiceErrorDomain
+ _kAFLocalTurnStatusServiceMachServiceName
+ _kAFPersonalContentSettingChangedDarwinNotification
+ _kAFSiriTVPersonalContentSettingKey
+ _kTCCInfoGrantedFunction
+ _kTCCInfoServiceFunction
+ _kTCCServiceSiriFunction
+ _sAFDaemonIsExitingCleanly
+ _sLanguageCacheDidComputeHookForTesting
+ _sLanguageCachePublished
+ _sLanguageCaches
+ _sSupportedLanguagesGeneration
+ _sSupportedLanguagesGeneration_block_invoke.token
+ _sSupportedLanguagesLock
+ _softLinkTCCAccessCopyInformationForBundle
+ _softLinkTCCAccessSetForBundle
- +[AFFeatureFlags(SWEFeatureFlags) isHintsEnabled]
- +[AFSiriAvailability fromDictionary:]
- -[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:]
- -[AFConnectionEntitlementCache cacheEntitlement:forPID:bundleID:]
- -[AFConnectionEntitlementCache hasEntitlement:forPID:]
- GCC_except_table10148
- GCC_except_table10188
- GCC_except_table10219
- GCC_except_table10224
- GCC_except_table10225
- GCC_except_table10229
- GCC_except_table10418
- GCC_except_table10589
- GCC_except_table10618
- GCC_except_table10715
- GCC_except_table10719
- GCC_except_table10723
- GCC_except_table10752
- GCC_except_table1103
- GCC_except_table11106
- GCC_except_table11108
- GCC_except_table11111
- GCC_except_table11120
- GCC_except_table11181
- GCC_except_table11202
- GCC_except_table11227
- GCC_except_table11233
- GCC_except_table11377
- GCC_except_table11381
- GCC_except_table11383
- GCC_except_table11386
- GCC_except_table11392
- GCC_except_table11396
- GCC_except_table11402
- GCC_except_table11606
- GCC_except_table1169
- GCC_except_table1175
- GCC_except_table11930
- GCC_except_table12064
- GCC_except_table12067
- GCC_except_table12069
- GCC_except_table1468
- GCC_except_table1481
- GCC_except_table1485
- GCC_except_table1501
- GCC_except_table1606
- GCC_except_table1608
- GCC_except_table1680
- GCC_except_table1724
- GCC_except_table2086
- GCC_except_table2093
- GCC_except_table2099
- GCC_except_table2101
- GCC_except_table2103
- GCC_except_table2148
- GCC_except_table2150
- GCC_except_table2156
- GCC_except_table2162
- GCC_except_table2166
- GCC_except_table2170
- GCC_except_table2173
- GCC_except_table2175
- GCC_except_table2180
- GCC_except_table2182
- GCC_except_table2187
- GCC_except_table2199
- GCC_except_table2202
- GCC_except_table2216
- GCC_except_table2218
- GCC_except_table2220
- GCC_except_table2222
- GCC_except_table2224
- GCC_except_table2226
- GCC_except_table2228
- GCC_except_table2273
- GCC_except_table2299
- GCC_except_table231
- GCC_except_table2356
- GCC_except_table237
- GCC_except_table2389
- GCC_except_table243
- GCC_except_table257
- GCC_except_table2763
- GCC_except_table3051
- GCC_except_table3248
- GCC_except_table3256
- GCC_except_table3314
- GCC_except_table352
- GCC_except_table3691
- GCC_except_table3695
- GCC_except_table370
- GCC_except_table374
- GCC_except_table3740
- GCC_except_table3746
- GCC_except_table3771
- GCC_except_table3777
- GCC_except_table3987
- GCC_except_table4096
- GCC_except_table4107
- GCC_except_table4140
- GCC_except_table4143
- GCC_except_table4220
- GCC_except_table4224
- GCC_except_table4234
- GCC_except_table4245
- GCC_except_table4258
- GCC_except_table4343
- GCC_except_table4345
- GCC_except_table4369
- GCC_except_table4484
- GCC_except_table4547
- GCC_except_table4550
- GCC_except_table4554
- GCC_except_table4571
- GCC_except_table4585
- GCC_except_table4659
- GCC_except_table4717
- GCC_except_table4743
- GCC_except_table5017
- GCC_except_table5160
- GCC_except_table5173
- GCC_except_table5217
- GCC_except_table5311
- GCC_except_table5419
- GCC_except_table5602
- GCC_except_table5639
- GCC_except_table5645
- GCC_except_table5649
- GCC_except_table5669
- GCC_except_table5675
- GCC_except_table5678
- GCC_except_table576
- GCC_except_table6044
- GCC_except_table6158
- GCC_except_table626
- GCC_except_table6289
- GCC_except_table6412
- GCC_except_table6425
- GCC_except_table6426
- GCC_except_table6438
- GCC_except_table6445
- GCC_except_table6446
- GCC_except_table6449
- GCC_except_table6455
- GCC_except_table6502
- GCC_except_table6504
- GCC_except_table6506
- GCC_except_table6524
- GCC_except_table6530
- GCC_except_table6573
- GCC_except_table6585
- GCC_except_table6731
- GCC_except_table6817
- GCC_except_table6871
- GCC_except_table7107
- GCC_except_table7110
- GCC_except_table7111
- GCC_except_table7308
- GCC_except_table7367
- GCC_except_table7581
- GCC_except_table7584
- GCC_except_table7596
- GCC_except_table7597
- GCC_except_table7610
- GCC_except_table7611
- GCC_except_table7612
- GCC_except_table7618
- GCC_except_table7656
- GCC_except_table7662
- GCC_except_table7668
- GCC_except_table7736
- GCC_except_table7738
- GCC_except_table7773
- GCC_except_table7776
- GCC_except_table7887
- GCC_except_table7950
- GCC_except_table7952
- GCC_except_table7954
- GCC_except_table7956
- GCC_except_table7970
- GCC_except_table7976
- GCC_except_table8099
- GCC_except_table8103
- GCC_except_table8108
- GCC_except_table827
- GCC_except_table830
- GCC_except_table837
- GCC_except_table8479
- GCC_except_table8494
- GCC_except_table8501
- GCC_except_table8517
- GCC_except_table8584
- GCC_except_table8593
- GCC_except_table8623
- GCC_except_table8661
- GCC_except_table8662
- GCC_except_table8663
- GCC_except_table8688
- GCC_except_table8712
- GCC_except_table9072
- GCC_except_table9077
- GCC_except_table9080
- GCC_except_table9083
- GCC_except_table9086
- GCC_except_table9089
- GCC_except_table9092
- GCC_except_table9095
- GCC_except_table9266
- GCC_except_table9269
- GCC_except_table9330
- GCC_except_table9338
- GCC_except_table9343
- GCC_except_table9356
- GCC_except_table9516
- GCC_except_table9616
- GCC_except_table968
- GCC_except_table9805
- GCC_except_table9810
- GCC_except_table9940
- _AFIsHorseman.isHorseman
- _AFIsHorseman.onceToken
- _AFPreferencesSupportedDictationLanguages.onceToken
- _AFPreferencesSupportedDictationLanguages.sSupportedDictationLanguages
- _AFPreferencesSupportedDictationLanguagesSet.onceToken
- _AFPreferencesSupportedDictationLanguagesSet.stAllLanguagesSet
- _AFPreferencesSupportedLanguages.onceToken
- _AFPreferencesSupportedLanguages.stAllLanguageCodes
- _AFProcessGetInstanceUUID.instanceUUID
- _OBJC_IVAR_$_AFConnectionEntitlementCache._bundleIDToPIDMap
- __AFPreferencesDictationLanguagePrefixes.onceToken
- __AFPreferencesDictationLanguagePrefixes.sLanguagePrefixes
- __OBJC_$_CATEGORY_AceObject_$_AssistantAdditions
- __OBJC_$_CATEGORY_NSArray_$_AFCollectionUtilities
- __OBJC_$_CATEGORY_NSDate_$_AssistantAdditions
- __OBJC_$_CATEGORY_NSDictionary_$_AFCollectionUtilities
- __OBJC_$_CATEGORY_NSNull_$_AFBundleResourceSupport
- __OBJC_$_CATEGORY_NSString_$_AFPreferences
- __OBJC_$_CATEGORY_NSURL_$_AFBundleResourceSupport
- __OBJC_$_CLASS_METHODS_AFVoiceInfo(AFLocalizationAdditions|SiriTTSServiceAdditions|VSAdditions)
- __OBJC_$_CLASS_METHODS_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_$_CLASS_METHODS_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- __OBJC_$_INSTANCE_METHODS_AFClockTimer(ClockItem|AFClockTimerMutability)
- __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(AFCompanionDeviceInfoMutability)
- __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(AFLocalizationAdditions|SiriTTSServiceAdditions|VSAdditions)
- __OBJC_$_INSTANCE_METHODS_AceObject(AssistantAdditions|AFSecurityDigestibleChunksProvider|AnalyticsContextVending)
- __OBJC_$_INSTANCE_METHODS_NSArray(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSDate(AssistantAdditions|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSDictionary(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSNull(AFBundleResourceSupport|AFSecurityDigestibleChunksProvider)
- __OBJC_$_INSTANCE_METHODS_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_$_INSTANCE_METHODS_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- __OBJC_CLASS_PROTOCOLS_$_AFClockTimer(ClockItem|AFClockTimerMutability)
- __OBJC_CLASS_PROTOCOLS_$_AceObject(AssistantAdditions|AFSecurityDigestibleChunksProvider|AnalyticsContextVending)
- __OBJC_CLASS_PROTOCOLS_$_NSArray(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSDate(AssistantAdditions|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSDictionary(AFCollectionUtilities|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSNull(AFBundleResourceSupport|AFSecurityDigestibleChunksProvider)
- __OBJC_CLASS_PROTOCOLS_$_NSString(AFPreferences|AssistantServices|AFSecurityDigestibleChunksProvider|AFSiriRequest|ShortDescription)
- __OBJC_CLASS_PROTOCOLS_$_NSURL(AFBundleResourceSupport|AMOSExtensions|AFSecurityDigestibleChunksProvider|STSiriMessage)
- ___211-[AFCompanionDeviceInfo initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:]_block_invoke
- ___AFIsHorseman_block_invoke
- ___block_descriptor_100_e8_32s40s48s56s64s72s80s88s_e41_v16?0"<AFCompanionDeviceInfoMutating>"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
- ___block_descriptor_32_e25_v32?0"NSString"8Q16^B24l
- ___block_descriptor_82_e8_32s40s48s56bs_e33_v16?0"AceObject<SAAceCommand>"8ls32l8s56l8s40l8s48l8
- ___block_descriptor_90_e8_32s40s48s56s64bs_e5_v8?0ls32l8s64l8s40l8s48l8s56l8
- _uuid_clear
- _xpc_get_instance
```
