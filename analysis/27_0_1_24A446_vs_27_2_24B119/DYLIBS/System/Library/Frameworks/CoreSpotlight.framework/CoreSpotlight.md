## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

```diff

-2459.105.0.0.0
-  __TEXT.__text: 0x17c888
-  __TEXT.__objc_methlist: 0x14400
-  __TEXT.__const: 0xef8
-  __TEXT.__gcc_except_tab: 0x9480
-  __TEXT.__cstring: 0x2bc05
-  __TEXT.__oslogstring: 0xbb7e
+2465.1.9.0.0
+  __TEXT.__text: 0x1805c8
+  __TEXT.__objc_methlist: 0x147d8
+  __TEXT.__const: 0xf08
+  __TEXT.__cstring: 0x2bedd
+  __TEXT.__gcc_except_tab: 0x9718
+  __TEXT.__oslogstring: 0xbfee
   __TEXT.__ustring: 0x218e
-  __TEXT.__dlopen_cstrs: 0x526
+  __TEXT.__dlopen_cstrs: 0x4c4
   __TEXT.__constg_swiftt: 0x1bc
   __TEXT.__swift5_typeref: 0x2ba
   __TEXT.__swift5_reflstr: 0x8e

   __TEXT.__swift_as_cont: 0xc
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x5f40
+  __TEXT.__unwind_info: 0x6070
   __TEXT.__eh_frame: 0x210
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x65a8
-  __DATA_CONST.__objc_classlist: 0xa90
+  __DATA_CONST.__const: 0x6718
+  __DATA_CONST.__objc_classlist: 0xab8
   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa4b0
+  __DATA_CONST.__objc_selrefs: 0xa620
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x720
+  __DATA_CONST.__objc_superrefs: 0x748
   __DATA_CONST.__objc_arraydata: 0x11290
-  __DATA_CONST.__got: 0xe50
-  __AUTH_CONST.__const: 0x23f0
-  __AUTH_CONST.__cfstring: 0x2de60
-  __AUTH_CONST.__objc_const: 0x1f780
+  __DATA_CONST.__got: 0xe78
+  __AUTH_CONST.__const: 0x2430
+  __AUTH_CONST.__cfstring: 0x2e140
+  __AUTH_CONST.__objc_const: 0x20120
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x3ae0
   __AUTH_CONST.__objc_dictobj: 0xaf78
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_doubleobj: 0x180
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0x1148
+  __AUTH_CONST.__auth_got: 0x1160
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x5b90
+  __AUTH.__objc_data: 0x57a8
   __AUTH.__data: 0x3a0
-  __AUTH.__thread_vars: 0x48
-  __AUTH.__thread_bss: 0x18
-  __DATA.__objc_ivar: 0x13f8
-  __DATA.__data: 0x1c58
-  __DATA.__bss: 0x1990
-  __DATA_DIRTY.__objc_data: 0xe10
+  __AUTH.__thread_vars: 0x60
+  __AUTH.__thread_bss: 0x28
+  __DATA.__objc_ivar: 0x146c
+  __DATA.__data: 0x1c60
+  __DATA.__bss: 0x19a0
+  __DATA_DIRTY.__objc_data: 0x1388
   __DATA_DIRTY.__data: 0x20
   __DATA_DIRTY.__bss: 0xa808
   __DATA_DIRTY.__common: 0x18

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8858
-  Symbols:   14501
+  Functions: 8959
+  Symbols:   14692
   CStrings:  0
 
Symbols:
+ +[CSBundleFilterAttributeBackfillGroup supportsSecureCoding]
+ +[CSBundleFilterAttributeBackfillResult supportsSecureCoding]
+ +[CSBundleFilterEvaluationReply supportsSecureCoding]
+ +[CSBundleFilterEvaluationRequest supportsSecureCoding]
+ +[CSBundleFilterFileProviderContainerGroup supportsSecureCoding]
+ +[CSSearchConnection _test_connection]
+ +[CSSearchConnection _test_setGameModeSuspended:]
+ +[_CSSearchPipelineExecutor executeNextStage:index:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:searchableIndex:boundVariables:extractValueConfigs:completion:]
+ +[_CSSearchPipelineExecutor executePipeline:configuration:typedCompletion:]
+ +[_CSSearchPipelineExecutor executePipeline:customStageHandler:promptedStageHandler:searchableIndex:completion:]
+ +[_CSSearchPipelineExecutor executeStage:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:searchableIndex:boundVariables:completion:]
+ +[_CSSearchPipelineExecutor executeStagesInOrder:pipeline:customStageHandler:promptedStageHandler:searchableIndex:completion:]
+ -[CSBundleFilterAttributeBackfillGroup .cxx_destruct]
+ -[CSBundleFilterAttributeBackfillGroup attributeName]
+ -[CSBundleFilterAttributeBackfillGroup bundleID]
+ -[CSBundleFilterAttributeBackfillGroup encodeWithCoder:]
+ -[CSBundleFilterAttributeBackfillGroup identifiers]
+ -[CSBundleFilterAttributeBackfillGroup initWithBundleID:attributeName:protectionClass:identifiers:]
+ -[CSBundleFilterAttributeBackfillGroup initWithCoder:]
+ -[CSBundleFilterAttributeBackfillGroup protectionClass]
+ -[CSBundleFilterAttributeBackfillResult .cxx_destruct]
+ -[CSBundleFilterAttributeBackfillResult bundleID]
+ -[CSBundleFilterAttributeBackfillResult confirmedAbsentIdentifiers]
+ -[CSBundleFilterAttributeBackfillResult encodeWithCoder:]
+ -[CSBundleFilterAttributeBackfillResult initWithBundleID:resolvedValues:confirmedAbsentIdentifiers:]
+ -[CSBundleFilterAttributeBackfillResult initWithCoder:]
+ -[CSBundleFilterAttributeBackfillResult resolvedValues]
+ -[CSBundleFilterEvaluationReply .cxx_destruct]
+ -[CSBundleFilterEvaluationReply attributeBackfillResults]
+ -[CSBundleFilterEvaluationReply encodeWithCoder:]
+ -[CSBundleFilterEvaluationReply excludedAppBundleIdentifiers]
+ -[CSBundleFilterEvaluationReply fileProviderMatchedIdentifiers]
+ -[CSBundleFilterEvaluationReply fileProviderUnresolvedIdentifiers]
+ -[CSBundleFilterEvaluationReply hiddenAppBundleIdentifiers]
+ -[CSBundleFilterEvaluationReply initWithCoder:]
+ -[CSBundleFilterEvaluationReply initWithFileProviderMatchedIdentifiers:fileProviderUnresolvedIdentifiers:lockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:mdmRestrictedBundleIdentifiers:excludedAppBundleIdentifiers:attributeBackfillResults:]
+ -[CSBundleFilterEvaluationReply lockedAppBundleIdentifiers]
+ -[CSBundleFilterEvaluationReply mdmRestrictedBundleIdentifiers]
+ -[CSBundleFilterEvaluationRequest .cxx_destruct]
+ -[CSBundleFilterEvaluationRequest attributeBackfillGroups]
+ -[CSBundleFilterEvaluationRequest encodeWithCoder:]
+ -[CSBundleFilterEvaluationRequest fileProviderContainerGroups]
+ -[CSBundleFilterEvaluationRequest fileProviderExcludedBundleIDs]
+ -[CSBundleFilterEvaluationRequest initWithCoder:]
+ -[CSBundleFilterEvaluationRequest initWithFileProviderContainerGroups:fileProviderExcludedBundleIDs:needsAppProtectionBundleIDs:needsMDMRestrictedBundleIDs:needsExcludedAppBundleIDs:attributeBackfillGroups:]
+ -[CSBundleFilterEvaluationRequest needsAppProtectionBundleIDs]
+ -[CSBundleFilterEvaluationRequest needsExcludedAppBundleIDs]
+ -[CSBundleFilterEvaluationRequest needsMDMRestrictedBundleIDs]
+ -[CSBundleFilterFileProviderContainerGroup .cxx_destruct]
+ -[CSBundleFilterFileProviderContainerGroup bundleID]
+ -[CSBundleFilterFileProviderContainerGroup encodeWithCoder:]
+ -[CSBundleFilterFileProviderContainerGroup identifiers]
+ -[CSBundleFilterFileProviderContainerGroup initWithBundleID:identifiers:knownOIDPaths:]
+ -[CSBundleFilterFileProviderContainerGroup initWithCoder:]
+ -[CSBundleFilterFileProviderContainerGroup knownOIDPaths]
+ -[CSCoder abandonBuildPastStackReserve]
+ -[CSCoder abandoned]
+ -[CSFileProviderContainerCache containerOIDsForOwnerBundleIDs:]
+ -[CSInlineDonation _errorWithCode:description:underlying:]
+ -[CSSearchConnection _test_issueAndCancelDummyQueryWithID:]
+ -[CSSearchQuery didResolveFriendlyAttributeNames:resolvedFetchAttributes:]
+ -[CSSearchQueryContext allDisabledBundlesSet]
+ -[CSSearchQueryContext federationDisabledBundles]
+ -[CSSearchQueryContext predicateFrameworkGenerated]
+ -[CSSearchQueryContext predicateSearchToolGenerated]
+ -[CSSearchQueryContext setFederationDisabledBundles:]
+ -[CSSearchQueryContext setPredicateFrameworkGenerated:]
+ -[CSSearchQueryContext setPredicateSearchToolGenerated:]
+ -[CSSearchableIndex _evaluateFilters:completionHandler:]
+ -[CSSearchableItem filteringResult]
+ -[CSSearchableItem setFilteringResult:]
+ -[_CSHydrationStage applyDelegateReplacementForIdentifier:atIndex:handledSnapshot:into:]
+ -[_CSHydrationStage collectDelegateItems:requested:into:]
+ -[_CSHydrationStage dispatchDelegateHydration:index:identifiersByBundle:group:collectInto:]
+ -[_CSHydrationStage dispatchDelegateHydrationForBundleIdentifiers:delegate:index:variant:group:collectInto:]
+ -[_CSHydrationStage hydrateItemViaDataProvider:bundleID:contentTypes:timeout:index:completion:]
+ -[_CSHydrationStage hydrateItemWithIdentifier:bundleID:path:contentTypes:timeout:maxFileSize:allowFileSystem:index:completion:]
+ -[_CSHydrationStage remainingIdentifiers:notHandledIn:]
+ -[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]
+ -[_CSSearchPipelineExecutionContext searchableIndex]
+ -[_CSSearchPipelineExecutionContext setSearchableIndex:]
+ GCC_except_table101
+ GCC_except_table1071
+ GCC_except_table108
+ GCC_except_table112
+ GCC_except_table119
+ GCC_except_table129
+ GCC_except_table136
+ GCC_except_table140
+ GCC_except_table141
+ GCC_except_table145
+ GCC_except_table148
+ GCC_except_table151
+ GCC_except_table152
+ GCC_except_table161
+ GCC_except_table1645
+ GCC_except_table1651
+ GCC_except_table177
+ GCC_except_table182
+ GCC_except_table186
+ GCC_except_table198
+ GCC_except_table203
+ GCC_except_table206
+ GCC_except_table207
+ GCC_except_table214
+ GCC_except_table233
+ GCC_except_table234
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table240
+ GCC_except_table241
+ GCC_except_table242
+ GCC_except_table254
+ GCC_except_table259
+ GCC_except_table264
+ GCC_except_table274
+ GCC_except_table279
+ GCC_except_table288
+ GCC_except_table289
+ GCC_except_table29
+ GCC_except_table299
+ GCC_except_table303
+ GCC_except_table304
+ GCC_except_table308
+ GCC_except_table312
+ GCC_except_table318
+ GCC_except_table320
+ GCC_except_table321
+ GCC_except_table322
+ GCC_except_table337
+ GCC_except_table340
+ GCC_except_table341
+ GCC_except_table342
+ GCC_except_table345
+ GCC_except_table346
+ GCC_except_table347
+ GCC_except_table354
+ GCC_except_table355
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table366
+ GCC_except_table369
+ GCC_except_table373
+ GCC_except_table379
+ GCC_except_table382
+ GCC_except_table387
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table395
+ GCC_except_table397
+ GCC_except_table400
+ GCC_except_table403
+ GCC_except_table477
+ GCC_except_table478
+ GCC_except_table479
+ GCC_except_table487
+ GCC_except_table529
+ GCC_except_table576
+ GCC_except_table65
+ GCC_except_table72
+ GCC_except_table93
+ _CSShouldTraceMessagesDonation
+ _NSURLFileSizeKey
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillGroup
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillResult
+ _OBJC_CLASS_$_CSBundleFilterEvaluationReply
+ _OBJC_CLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_CLASS_$_CSBundleFilterFileProviderContainerGroup
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillGroup._attributeName
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillGroup._bundleID
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillGroup._identifiers
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillGroup._protectionClass
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillResult._bundleID
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillResult._confirmedAbsentIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterAttributeBackfillResult._resolvedValues
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._attributeBackfillResults
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._excludedAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._fileProviderMatchedIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._fileProviderUnresolvedIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._hiddenAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._lockedAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationReply._mdmRestrictedBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._attributeBackfillGroups
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._fileProviderContainerGroups
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._fileProviderExcludedBundleIDs
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._needsAppProtectionBundleIDs
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._needsExcludedAppBundleIDs
+ _OBJC_IVAR_$_CSBundleFilterEvaluationRequest._needsMDMRestrictedBundleIDs
+ _OBJC_IVAR_$_CSBundleFilterFileProviderContainerGroup._bundleID
+ _OBJC_IVAR_$_CSBundleFilterFileProviderContainerGroup._identifiers
+ _OBJC_IVAR_$_CSBundleFilterFileProviderContainerGroup._knownOIDPaths
+ _OBJC_IVAR_$_CSCoder._abandoned
+ _OBJC_IVAR_$_CSFileProviderDomainMonitor._savedRemovedCount
+ _OBJC_IVAR_$_CSSearchQueryContext._allDisabledBundlesSet
+ _OBJC_IVAR_$_CSSearchQueryContext._federationDisabledBundles
+ _OBJC_IVAR_$_CSSearchableItem._filteringResult
+ _OBJC_IVAR_$__CSSearchPipelineExecutionContext._searchableIndex
+ _OBJC_METACLASS_$_CSBundleFilterAttributeBackfillGroup
+ _OBJC_METACLASS_$_CSBundleFilterAttributeBackfillResult
+ _OBJC_METACLASS_$_CSBundleFilterEvaluationReply
+ _OBJC_METACLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_METACLASS_$_CSBundleFilterFileProviderContainerGroup
+ _PRBuildQueryTree
+ __MDPlistContainerAbandonBuild
+ __MDPlistContainerAddNullValue
+ __MDPlistContainerAllocFailure
+ __OBJC_$_CLASS_METHODS_CSBundleFilterAttributeBackfillGroup
+ __OBJC_$_CLASS_METHODS_CSBundleFilterAttributeBackfillResult
+ __OBJC_$_CLASS_METHODS_CSBundleFilterEvaluationReply
+ __OBJC_$_CLASS_METHODS_CSBundleFilterEvaluationRequest
+ __OBJC_$_CLASS_METHODS_CSBundleFilterFileProviderContainerGroup
+ __OBJC_$_CLASS_PROP_LIST_CSBundleFilterAttributeBackfillGroup
+ __OBJC_$_CLASS_PROP_LIST_CSBundleFilterAttributeBackfillResult
+ __OBJC_$_CLASS_PROP_LIST_CSBundleFilterEvaluationReply
+ __OBJC_$_CLASS_PROP_LIST_CSBundleFilterEvaluationRequest
+ __OBJC_$_CLASS_PROP_LIST_CSBundleFilterFileProviderContainerGroup
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterAttributeBackfillGroup
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterAttributeBackfillResult
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterEvaluationReply
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterEvaluationRequest
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterFileProviderContainerGroup
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterAttributeBackfillGroup
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterAttributeBackfillResult
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterEvaluationReply
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterEvaluationRequest
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterFileProviderContainerGroup
+ __OBJC_$_PROP_LIST_CSBundleFilterAttributeBackfillGroup
+ __OBJC_$_PROP_LIST_CSBundleFilterAttributeBackfillResult
+ __OBJC_$_PROP_LIST_CSBundleFilterEvaluationReply
+ __OBJC_$_PROP_LIST_CSBundleFilterEvaluationRequest
+ __OBJC_$_PROP_LIST_CSBundleFilterFileProviderContainerGroup
+ __OBJC_CLASS_PROTOCOLS_$_CSBundleFilterAttributeBackfillGroup
+ __OBJC_CLASS_PROTOCOLS_$_CSBundleFilterAttributeBackfillResult
+ __OBJC_CLASS_PROTOCOLS_$_CSBundleFilterEvaluationReply
+ __OBJC_CLASS_PROTOCOLS_$_CSBundleFilterEvaluationRequest
+ __OBJC_CLASS_PROTOCOLS_$_CSBundleFilterFileProviderContainerGroup
+ __OBJC_CLASS_RO_$_CSBundleFilterAttributeBackfillGroup
+ __OBJC_CLASS_RO_$_CSBundleFilterAttributeBackfillResult
+ __OBJC_CLASS_RO_$_CSBundleFilterEvaluationReply
+ __OBJC_CLASS_RO_$_CSBundleFilterEvaluationRequest
+ __OBJC_CLASS_RO_$_CSBundleFilterFileProviderContainerGroup
+ __OBJC_METACLASS_RO_$_CSBundleFilterAttributeBackfillGroup
+ __OBJC_METACLASS_RO_$_CSBundleFilterAttributeBackfillResult
+ __OBJC_METACLASS_RO_$_CSBundleFilterEvaluationReply
+ __OBJC_METACLASS_RO_$_CSBundleFilterEvaluationRequest
+ __OBJC_METACLASS_RO_$_CSBundleFilterFileProviderContainerGroup
+ ___108-[_CSHydrationStage dispatchDelegateHydrationForBundleIdentifiers:delegate:index:variant:group:collectInto:]_block_invoke
+ ___108-[_CSHydrationStage dispatchDelegateHydrationForBundleIdentifiers:delegate:index:variant:group:collectInto:]_block_invoke_2
+ ___112+[_CSSearchPipelineExecutor executePipeline:customStageHandler:promptedStageHandler:searchableIndex:completion:]_block_invoke
+ ___127-[_CSHydrationStage hydrateItemWithIdentifier:bundleID:path:contentTypes:timeout:maxFileSize:allowFileSystem:index:completion:]_block_invoke
+ ___177-[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke
+ ___177-[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke_2
+ ___177-[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke_3
+ ___177-[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke_4
+ ___177-[_CSHydrationStage runIndexHydrationForInput:identifiersByBundle:handledSnapshot:index:context:hydrationAttributes:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke_5
+ ___196+[_CSSearchPipelineExecutor executeNextStage:index:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:searchableIndex:boundVariables:extractValueConfigs:completion:]_block_invoke
+ ___49+[CSSearchConnection _test_setGameModeSuspended:]_block_invoke
+ ___49+[CSSearchConnection _test_setGameModeSuspended:]_block_invoke_2
+ ___56-[CSSearchableIndex _evaluateFilters:completionHandler:]_block_invoke
+ ___56-[CSSearchableIndex _evaluateFilters:completionHandler:]_block_invoke_2
+ ___56-[CSSearchableIndex _evaluateFilters:completionHandler:]_block_invoke_3
+ ___56-[CSSearchableIndex _evaluateFilters:completionHandler:]_block_invoke_4
+ ___63-[CSFileProviderContainerCache containerOIDsForOwnerBundleIDs:]_block_invoke
+ ___63-[CSFileProviderContainerCache containerOIDsForOwnerBundleIDs:]_block_invoke_2
+ ___74-[CSSearchQuery didResolveFriendlyAttributeNames:resolvedFetchAttributes:]_block_invoke
+ ___75+[_CSSearchPipelineExecutor executePipeline:configuration:typedCompletion:]_block_invoke
+ ___75+[_CSSearchPipelineExecutor executePipeline:configuration:typedCompletion:]_block_invoke_2
+ ___block_descriptor_113_ea8_32s40s48s56s64s72s80s88bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___block_descriptor_137_ea8_32s40s48s56s64s72s80s88s96s104s112bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_144_e8_32s40s48s56s64s72s80s88s96s104s112bs120bs_e20_v24?08"NSError"16ls32l8s112l8s40l8s48l8s56l8s64l8s72l8s80l8s120l8s88l8s96l8s104l8
+ ___block_descriptor_145_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s120l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_222_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144s152s160w_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8w160l8s104l8s112l8s120l8s128l8s136l8s144l8s152l8
+ ___block_descriptor_33_e5_v8?0l
+ ___block_descriptor_40_e8_32s_e41_B24?0"CSTopHitResult"8"NSDictionary"16ls32l8
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8s40l8
+ ___block_descriptor_48_ea8_32s40r_e5_B8?0ls32l8r40l8
+ ___block_descriptor_52_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s_e19_v32?0{?=*Q{?=IC}}8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s_e26_v48?0r*8Q16{?=*Q{?=IC}}24ls32l8s40l8
+ ___block_descriptor_72_ea8_32s40s48s56s64bs_e17_v16?0"NSArray"8ls64l8s32l8s40l8s48l8s56l8
+ ___decodeObject_block_invoke
+ ___decodeObject_block_invoke_2
+ ___decodeObject_block_invoke_3
+ ___decodeObject_block_invoke_4
+ ___dropHomeWeakRetrievalItems_block_invoke
+ ___getSSHomeItemBelowRetrievalThresholdsSymbolLoc_block_invoke
+ ___logForCSLogCategoryDonationTracing_block_invoke
+ _coderStackFloor
+ _decodeObject
+ _encodeStackFloor.memo
+ _encodeStackFloor.memo$tlv$init
+ _getSSHomeItemBelowRetrievalThresholdsSymbolLoc.ptr
+ _logForCSLogCategoryDonationTracing
+ _logForCSLogCategoryDonationTracing.onceToken
+ _logForCSLogCategoryDonationTracing.sDonationTracingLog
+ _objc_retain_x10
+ _pthread_get_stackaddr_np
+ _pthread_get_stacksize_np
+ _pthread_self
+ _quotedValue
+ _reportDecodeStackHeadroomExhausted.rejectionCount
+ _reportEncodeStackHeadroomExhausted.rejectionCount
+ _representativeUTIForSelector
+ _sDonationXPCTraceID
- +[_CSSearchPipelineExecutor executeNextStage:index:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:boundVariables:extractValueConfigs:completion:]
- +[_CSSearchPipelineExecutor executeStage:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:boundVariables:completion:]
- +[_CSSearchPipelineExecutor executeStagesInOrder:pipeline:customStageHandler:promptedStageHandler:completion:]
- -[CSInlineDonation _logErrorWithCode:description:underlying:]
- -[CSSearchQuery didResolveFriendlyAttributeNames:fromFetchAttributes:]
- -[CSSearchableItemAttributeSet(CSPrivateAttributes) _standardizeProcessorAttributesForBundle:protectionClass:isUpdate:]
- -[_CSHydrationStage hydrateItemViaDataProvider:bundleID:contentTypes:timeout:completion:]
- -[_CSHydrationStage hydrateItemWithIdentifier:bundleID:path:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]
- GCC_except_table102
- GCC_except_table103
- GCC_except_table1072
- GCC_except_table120
- GCC_except_table130
- GCC_except_table133
- GCC_except_table138
- GCC_except_table143
- GCC_except_table146
- GCC_except_table150
- GCC_except_table157
- GCC_except_table162
- GCC_except_table163
- GCC_except_table1648
- GCC_except_table1654
- GCC_except_table178
- GCC_except_table179
- GCC_except_table184
- GCC_except_table189
- GCC_except_table192
- GCC_except_table197
- GCC_except_table205
- GCC_except_table212
- GCC_except_table216
- GCC_except_table220
- GCC_except_table235
- GCC_except_table244
- GCC_except_table249
- GCC_except_table253
- GCC_except_table255
- GCC_except_table256
- GCC_except_table265
- GCC_except_table271
- GCC_except_table272
- GCC_except_table275
- GCC_except_table281
- GCC_except_table285
- GCC_except_table290
- GCC_except_table298
- GCC_except_table300
- GCC_except_table301
- GCC_except_table302
- GCC_except_table31
- GCC_except_table315
- GCC_except_table316
- GCC_except_table319
- GCC_except_table323
- GCC_except_table327
- GCC_except_table328
- GCC_except_table331
- GCC_except_table332
- GCC_except_table335
- GCC_except_table336
- GCC_except_table357
- GCC_except_table360
- GCC_except_table365
- GCC_except_table367
- GCC_except_table372
- GCC_except_table375
- GCC_except_table380
- GCC_except_table384
- GCC_except_table388
- GCC_except_table390
- GCC_except_table393
- GCC_except_table396
- GCC_except_table470
- GCC_except_table471
- GCC_except_table472
- GCC_except_table473
- GCC_except_table517
- GCC_except_table52
- GCC_except_table53
- GCC_except_table564
- GCC_except_table63
- GCC_except_table742
- GCC_except_table87
- GCC_except_table92
- GCC_except_table97
- _PRBuildDefaultQueryTree
- _PRBuildHomeQueryTree
- _PRBuildMailQueryTree
- _PRBuildMessagesQueryTree
- _PRBuildPhotosQueryTree
- _SpotlightKnowledgeLibraryCore.frameworkLibrary
- ___121-[_CSHydrationStage hydrateItemWithIdentifier:bundleID:path:contentTypes:timeout:maxFileSize:allowFileSystem:completion:]_block_invoke
- ___180+[_CSSearchPipelineExecutor executeNextStage:index:stageResults:stageMap:attributeTranslator:customStageHandler:promptedStageHandler:boundVariables:extractValueConfigs:completion:]_block_invoke
- ___51-[_CSHydrationStage executeWithContext:completion:]_block_invoke_2
- ___51-[_CSHydrationStage executeWithContext:completion:]_block_invoke_3
- ___51-[_CSHydrationStage executeWithContext:completion:]_block_invoke_4
- ___51-[_CSHydrationStage executeWithContext:completion:]_block_invoke_5
- ___61+[_CSSearchPipelineExecutor executePipeline:typedCompletion:]_block_invoke
- ___61+[_CSSearchPipelineExecutor executePipeline:typedCompletion:]_block_invoke_2
- ___70-[CSSearchQuery didResolveFriendlyAttributeNames:fromFetchAttributes:]_block_invoke
- ___96+[_CSSearchPipelineExecutor executePipeline:customStageHandler:promptedStageHandler:completion:]_block_invoke
- ___SpotlightKnowledgeLibraryCore_block_invoke
- ____CSDecodeObject_block_invoke
- ____CSDecodeObject_block_invoke_2
- ____CSDecodeObject_block_invoke_3
- ____CSDecodeObject_block_invoke_4
- ___block_descriptor_136_e8_32s40s48s56s64s72s80s88s96s104bs112bs_e20_v24?08"NSError"16ls32l8s104l8s40l8s48l8s56l8s64l8s72l8s80l8s112l8s88l8s96l8
- ___block_descriptor_145_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8
- ___block_descriptor_209_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144s152w_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8w152l8s96l8s104l8s112l8s120l8s128l8s136l8s144l8
- ___block_descriptor_48_e8_32s40s_e19_v32?0{?=*Q{?=IC}}8ls32l8s40l8
- ___block_descriptor_97_ea8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
- ___getSKGAttributeProcessorClass_block_invoke
- _audit_stringSpotlightKnowledge
- _getSKGAttributeProcessorClass.softClass
```
