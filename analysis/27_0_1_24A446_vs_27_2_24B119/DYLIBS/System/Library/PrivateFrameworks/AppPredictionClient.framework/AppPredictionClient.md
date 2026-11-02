## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient`

```diff

-671.0.2.0.1
-  __TEXT.__text: 0x18c558
-  __TEXT.__objc_methlist: 0x18f44
-  __TEXT.__const: 0x708
-  __TEXT.__cstring: 0x1c3ab
-  __TEXT.__oslogstring: 0x179bc
-  __TEXT.__gcc_except_tab: 0x2038
+678.0.1.0.0
+  __TEXT.__text: 0x190d8c
+  __TEXT.__objc_methlist: 0x190bc
+  __TEXT.__const: 0x710
+  __TEXT.__cstring: 0x1c96f
+  __TEXT.__oslogstring: 0x180dc
+  __TEXT.__gcc_except_tab: 0x20ac
   __TEXT.__dlopen_cstrs: 0x491
   __TEXT.__ustring: 0x18a
-  __TEXT.__unwind_info: 0x6910
+  __TEXT.__unwind_info: 0x6998
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x63f0
+  __DATA_CONST.__const: 0x6490
   __DATA_CONST.__objc_classlist: 0xe40
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa0f8
+  __DATA_CONST.__objc_selrefs: 0xa200
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0xc48
-  __DATA_CONST.__objc_arraydata: 0xb28
-  __DATA_CONST.__got: 0x1718
-  __AUTH_CONST.__const: 0x2b00
-  __AUTH_CONST.__cfstring: 0x155a0
-  __AUTH_CONST.__objc_const: 0x46178
+  __DATA_CONST.__objc_arraydata: 0xb48
+  __DATA_CONST.__got: 0x1730
+  __AUTH_CONST.__const: 0x2ba0
+  __AUTH_CONST.__cfstring: 0x15680
+  __AUTH_CONST.__objc_const: 0x462b0
   __AUTH_CONST.__objc_intobj: 0xa68
   __AUTH_CONST.__objc_arrayobj: 0x708
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__objc_dictobj: 0x168
+  __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__auth_got: 0x790
   __AUTH_CONST.__auth_ptr: 0x0
   __AUTH.__objc_data: 0x4740
-  __DATA.__objc_ivar: 0x1c98
+  __DATA.__objc_ivar: 0x1cb8
   __DATA.__data: 0x1cf0
-  __DATA.__bss: 0x438
+  __DATA.__bss: 0x448
   __DATA_DIRTY.__objc_data: 0x4740
   __DATA_DIRTY.__data: 0x88
-  __DATA_DIRTY.__bss: 0x258
+  __DATA_DIRTY.__bss: 0x278
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10921
-  Symbols:   16827
+  Functions: 10981
+  Symbols:   16896
   CStrings:  0
 
Symbols:
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedForClient:]
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedOnTvOS]
+ +[ATXDefaultHomeScreenItemProducerUtilities remoteWidgetsFromPairedDeviceRanking:size:personalityToDescriptorDictionary:]
+ +[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:assets:]
+ +[ATXDefaultHomeScreenItemProducerUtilities widgetsByInterleavingWidgets:withWidgets:limit:usedPersonalities:usedAppBundleIds:]
+ -[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]
+ -[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedForAllAppsOverLastDays:]
+ -[ATXDefaultHomeScreenItemManager _pairedDeviceRankedWidgetsForClientIdentity:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _hasPairedDeviceImportForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _pairedDevicePathForVariant:sourceDeviceIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer importedWidgetSmartStacksByPathForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer pairedDeviceWidgetSmartStackForVariant:relationshipIdentifier:maximumAge:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:size:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _tvOSRequiredWidgetsKeyForOnboarding:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultHomeScreenItemProducer _computeNewlyInstalledThresholdsIfNeeded]
+ -[ATXDefaultHomeScreenItemProducer _onboardingStacksProducerForSmartStackRequest:]
+ -[ATXDefaultHomeScreenItemProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]
+ -[ATXInformationStore fetchAllDistinctWidgetsIgnoringIntentWithTimelineDonations]
+ -[ATXWidgetSmartStackResponse setSourceDeviceIdentifier:]
+ -[ATXWidgetSmartStackResponse sourceDeviceIdentifier]
+ GCC_except_table236
+ GCC_except_table240
+ GCC_except_table244
+ GCC_except_table248
+ GCC_except_table252
+ GCC_except_table255
+ GCC_except_table259
+ GCC_except_table262
+ GCC_except_table266
+ GCC_except_table275
+ GCC_except_table280
+ GCC_except_table284
+ GCC_except_table288
+ GCC_except_table291
+ GCC_except_table294
+ GCC_except_table298
+ GCC_except_table302
+ GCC_except_table305
+ _ATXCanonicalContainerBundleIdForWidgetDedup
+ _ATXCanonicalContainerBundleIdForWidgetDedup.aliases
+ _ATXCanonicalContainerBundleIdForWidgetDedup.onceToken
+ _OBJC_CLASS_$_CHSRemoteDeviceService
+ _OBJC_CLASS_$_NSOrderedSet
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._pairedDevicePathPrefix
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._widgetSuggesterClient
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._pairedDeviceRankedWidgets
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._newInstallThreshold
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._pairedDeviceRankedWidgets
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._widgetInstallDateThreshold
+ _OBJC_IVAR_$_ATXHomeScreenConfigCache._usesDefaultRootPath
+ _OBJC_IVAR_$_ATXWidgetSmartStackResponse._sourceDeviceIdentifier
+ ___103-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]_block_invoke
+ ___105-[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___107-[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]_block_invoke
+ ___114-[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke_2
+ ___196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke_2
+ ___55-[ATXDefaultHomeScreenItemProducer _personalizedUpdate]_block_invoke
+ ___78-[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedForAllAppsOverLastDays:]_block_invoke
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke_2
+ ___78-[ATXInformationStore _fetchDistinctWidgetsIgnoringIntentWithQuery:sinceDate:]_block_invoke_3
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke_2
+ ___80-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLastDays:withFilter:]_block_invoke_3
+ ___86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke
+ ___86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke_2
+ ___88+[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:assets:]_block_invoke
+ ___ATXCanonicalContainerBundleIdForWidgetDedup_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e49_v24?0"ATXWidgetSmartStackResponse"8"NSError"16ls40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e29_v16?0"NSMutableDictionary"8lr40l8s32l8
+ ___block_descriptor_48_e8_32s40s_e29_v16?0"NSMutableDictionary"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e30_B16?0"ATXWidgetPersonality"8ls32l8
+ ___pairedDeviceIdentifiersByRelationship_block_invoke
+ ___sharedWidgetSuggesterClient_block_invoke
+ _cachePath
+ _canonicalDeviceIdentifier
+ _isNilOrArrayOfWidgets
+ _isWellFormedSmartStackResponse
+ _kATXAppLaunchesSmartStackLookbackDays
+ _kATXPairedDeviceWidgetRankingMaximumAge
+ _pairedDeviceIdentifiersByRelationship
+ _pairedDeviceIdentifiersByRelationship.lock
+ _pairedDeviceIdentifiersByRelationship.onceToken
+ _sharedWidgetSuggesterClient.client
+ _sharedWidgetSuggesterClient.onceToken
- +[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:]
- -[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]
- -[ATXDefaultHomeScreenItemOnboardingStacksProducer _firstWidgetThatIsntUsedYet:usedPersonalities:]
- GCC_except_table234
- GCC_except_table238
- GCC_except_table242
- GCC_except_table246
- GCC_except_table250
- GCC_except_table253
- GCC_except_table257
- GCC_except_table260
- GCC_except_table264
- GCC_except_table273
- GCC_except_table278
- GCC_except_table28
- GCC_except_table282
- GCC_except_table286
- GCC_except_table289
- GCC_except_table292
- GCC_except_table296
- GCC_except_table300
- GCC_except_table303
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke_2
- ___67-[ATXInformationStore fetchDistinctWidgetsIgnoringIntentSinceDate:]_block_invoke_3
- ___71-[ATXWidgetDescriptorCache _queue_fetchAllDescriptorMetadataWithError:]_block_invoke
- ___79-[ATXAppLaunches rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysForAllApps]_block_invoke
- ___79-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]_block_invoke
- ___81+[ATXDefaultHomeScreenItemProducerUtilities similarThirdPartyWidgetsForPosition:]_block_invoke
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke_2
- ___81-[ATXAppLaunches _rawLaunchCountAndDistinctDaysLaunchedOverLast28DaysWithFilter:]_block_invoke_3
- ___86-[ATXDefaultHomeScreenItemManager fetchWidgetSmartStackWithRequest:completionHandler:]_block_invoke_2
```
