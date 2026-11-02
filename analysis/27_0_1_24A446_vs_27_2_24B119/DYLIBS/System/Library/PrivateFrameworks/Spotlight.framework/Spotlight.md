## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

```diff

-2459.105.0.0.0
-  __TEXT.__text: 0x9bec0
-  __TEXT.__objc_methlist: 0x2ad4
-  __TEXT.__const: 0xe24
-  __TEXT.__oslogstring: 0x5608
-  __TEXT.__cstring: 0x35cc
-  __TEXT.__gcc_except_tab: 0x5564
+2465.1.9.0.0
+  __TEXT.__text: 0xa39d4
+  __TEXT.__objc_methlist: 0x2d7c
+  __TEXT.__const: 0xe74
+  __TEXT.__oslogstring: 0x57d2
+  __TEXT.__cstring: 0x36cc
+  __TEXT.__gcc_except_tab: 0x5834
   __TEXT.__ustring: 0x6
-  __TEXT.__swift5_typeref: 0x7bc
-  __TEXT.__swift5_fieldmd: 0x298
-  __TEXT.__constg_swiftt: 0x414
-  __TEXT.__swift5_reflstr: 0x334
+  __TEXT.__swift5_typeref: 0x7da
+  __TEXT.__swift5_fieldmd: 0x28c
+  __TEXT.__constg_swiftt: 0x3fc
+  __TEXT.__swift5_reflstr: 0x324
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_proto: 0x50
   __TEXT.__swift5_types: 0x38
-  __TEXT.__swift_as_entry: 0x98
+  __TEXT.__swift_as_entry: 0x9c
   __TEXT.__swift_as_ret: 0x78
-  __TEXT.__swift_as_cont: 0x118
-  __TEXT.__swift5_capture: 0x3c8
+  __TEXT.__swift_as_cont: 0x114
+  __TEXT.__swift5_capture: 0x3f4
   __TEXT.__swift5_assocty: 0x60
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__unwind_info: 0x17e8
-  __TEXT.__eh_frame: 0x1130
+  __TEXT.__unwind_info: 0x18a0
+  __TEXT.__eh_frame: 0x1200
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe28
-  __DATA_CONST.__objc_classlist: 0x140
+  __DATA_CONST.__const: 0xe30
+  __DATA_CONST.__objc_classlist: 0x158
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2e40
+  __DATA_CONST.__objc_selrefs: 0x30a8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0xa0
+  __DATA_CONST.__objc_superrefs: 0xa8
   __DATA_CONST.__objc_arraydata: 0x3e8
-  __DATA_CONST.__got: 0x18f0
-  __AUTH_CONST.__const: 0x1400
-  __AUTH_CONST.__cfstring: 0x3000
-  __AUTH_CONST.__objc_const: 0x4710
+  __DATA_CONST.__got: 0x1948
+  __AUTH_CONST.__const: 0x14e8
+  __AUTH_CONST.__cfstring: 0x30a0
+  __AUTH_CONST.__objc_const: 0x4ea0
   __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__objc_intobj: 0x258
+  __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x12f0
+  __AUTH_CONST.__auth_got: 0x13a8
   __AUTH_CONST.__auth_ptr: 0x2b0
-  __AUTH.__objc_data: 0xe8
-  __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x3c4
-  __DATA.__data: 0x750
-  __DATA.__bss: 0x8d0
-  __DATA_DIRTY.__objc_data: 0xe60
-  __DATA_DIRTY.__data: 0x2f0
-  __DATA_DIRTY.__bss: 0x6b0
+  __AUTH.__objc_data: 0x558
+  __AUTH.__data: 0x50
+  __DATA.__objc_ivar: 0x440
+  __DATA.__data: 0x6d8
+  __DATA.__bss: 0xa20
+  __DATA_DIRTY.__objc_data: 0xad0
+  __DATA_DIRTY.__data: 0x360
+  __DATA_DIRTY.__bss: 0x5d0
   __DATA_DIRTY.__common: 0x50
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/Contacts.framework/Contacts

   - /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
   - /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage
   - /System/Library/Frameworks/SafariServices.framework/SafariServices
+  - /System/Library/Frameworks/Security.framework/Security
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers
   - /System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient
+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection
   - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
   - /System/Library/PrivateFrameworks/Calculate.framework/Calculate
   - /System/Library/PrivateFrameworks/ClipServices.framework/ClipServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1714
-  Symbols:   3184
+  Functions: 1812
+  Symbols:   3338
   CStrings:  0
 
Symbols:
+ +[SPBundleFilter applyFiltering:context:]
+ +[SPKGenerativeSearchMailQueryBase appScopeBundleIdentifiers]
+ +[SPKGenerativeSearchSiriTranscriptQuery appScopeBundleIdentifiers]
+ -[SFGenerativeSearchResultContainer classForCoder]
+ -[SFGenerativeSearchResultContainer classForKeyedArchiver]
+ -[SPBundleFilterResolvedDimensions .cxx_destruct]
+ -[SPBundleFilterResolvedDimensions allowedSet]
+ -[SPBundleFilterResolvedDimensions disableSearchInSpotlightActive]
+ -[SPBundleFilterResolvedDimensions disableSearchInSpotlightBypassSet]
+ -[SPBundleFilterResolvedDimensions eventSourceActive]
+ -[SPBundleFilterResolvedDimensions eventSourceExemptSet]
+ -[SPBundleFilterResolvedDimensions excludedSet]
+ -[SPBundleFilterResolvedDimensions fileProviderBundleIDs]
+ -[SPBundleFilterResolvedDimensions fileProviderRequested]
+ -[SPBundleFilterResolvedDimensions hiddenSet]
+ -[SPBundleFilterResolvedDimensions indexLookupReachable]
+ -[SPBundleFilterResolvedDimensions initWithContext:]
+ -[SPBundleFilterResolvedDimensions installedAppSet]
+ -[SPBundleFilterResolvedDimensions lockedSet]
+ -[SPBundleFilterResolvedDimensions mdmActive]
+ -[SPBundleFilterResolvedDimensions mdmRestrictedSet]
+ -[SPBundleFilterResolvedDimensions needsAppProtectionServerXPC]
+ -[SPBundleFilterResolvedDimensions needsExcludedAppServerXPC]
+ -[SPBundleFilterResolvedDimensions needsMDMServerXPC]
+ -[SPBundleFilterResolvedDimensions notificationSourceActive]
+ -[SPBundleFilterResolvedDimensions relatedAppActive]
+ -[SPBundleFilterResolvedDimensions relatedAppAttributeComplete]
+ -[SPBundleFilterResolvedDimensions relatedAppInstalledActive]
+ -[SPBundleFilterResolvedDimensions resolveBundleListDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions resolveIOSOnlyDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions resolveSourceAttributeDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions setExcludedSet:]
+ -[SPBundleFilterResolvedDimensions setHiddenSet:]
+ -[SPBundleFilterResolvedDimensions setLockedSet:]
+ -[SPBundleFilterResolvedDimensions setMdmRestrictedSet:]
+ -[SPBundleFilteringContext .cxx_destruct]
+ -[SPBundleFilteringContext allowedAppBundleIDs]
+ -[SPBundleFilteringContext disableSearchInSpotlightBypassBundleIDs]
+ -[SPBundleFilteringContext disabledOptions]
+ -[SPBundleFilteringContext enabledOptions]
+ -[SPBundleFilteringContext eventSourceExemptBundleIDs]
+ -[SPBundleFilteringContext excludedAppBundleIDs]
+ -[SPBundleFilteringContext hiddenAppBundleIDs]
+ -[SPBundleFilteringContext lockedAppBundleIDs]
+ -[SPBundleFilteringContext maximumEffortLevel]
+ -[SPBundleFilteringContext relatedAppBundleIdentifierAttributeComplete]
+ -[SPBundleFilteringContext setAllowedAppBundleIDs:]
+ -[SPBundleFilteringContext setDisableSearchInSpotlightBypassBundleIDs:]
+ -[SPBundleFilteringContext setDisabledOptions:]
+ -[SPBundleFilteringContext setEnabledOptions:]
+ -[SPBundleFilteringContext setEventSourceExemptBundleIDs:]
+ -[SPBundleFilteringContext setExcludedAppBundleIDs:]
+ -[SPBundleFilteringContext setHiddenAppBundleIDs:]
+ -[SPBundleFilteringContext setLockedAppBundleIDs:]
+ -[SPBundleFilteringContext setMaximumEffortLevel:]
+ -[SPBundleFilteringContext setRelatedAppBundleIdentifierAttributeComplete:]
+ -[SPClientSession dealloc]
+ GCC_except_table120
+ GCC_except_table130
+ GCC_except_table64
+ GCC_except_table68
+ GCC_except_table70
+ GCC_except_table78
+ _CFArrayGetTypeID
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFNotificationCenterRemoveObserver
+ _CFPreferencesSynchronize
+ _OBJC_CLASS_$_APApplication
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillGroup
+ _OBJC_CLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_CLASS_$_CSBundleFilterFileProviderContainerGroup
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_SPBundleFilter
+ _OBJC_CLASS_$_SPBundleFilterResolvedDimensions
+ _OBJC_CLASS_$_SPBundleFilteringContext
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._allowedSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._disableSearchInSpotlightActive
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._disableSearchInSpotlightBypassSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._eventSourceActive
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._eventSourceExemptSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._excludedSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._fileProviderBundleIDs
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._fileProviderRequested
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._hiddenSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._indexLookupReachable
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._installedAppSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._lockedSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._mdmActive
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._mdmRestrictedSet
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsAppProtectionServerXPC
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsExcludedAppServerXPC
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsMDMServerXPC
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._notificationSourceActive
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppActive
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppAttributeComplete
+ _OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppInstalledActive
+ _OBJC_IVAR_$_SPBundleFilteringContext._allowedAppBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._disableSearchInSpotlightBypassBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._disabledOptions
+ _OBJC_IVAR_$_SPBundleFilteringContext._enabledOptions
+ _OBJC_IVAR_$_SPBundleFilteringContext._eventSourceExemptBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._excludedAppBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._hiddenAppBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._lockedAppBundleIDs
+ _OBJC_IVAR_$_SPBundleFilteringContext._maximumEffortLevel
+ _OBJC_IVAR_$_SPBundleFilteringContext._relatedAppBundleIdentifierAttributeComplete
+ _OBJC_METACLASS_$_SPBundleFilter
+ _OBJC_METACLASS_$_SPBundleFilterResolvedDimensions
+ _OBJC_METACLASS_$_SPBundleFilteringContext
+ _SPBundleFilterAliasClasses.classes
+ _SPBundleFilterAliasClasses.onceToken
+ _SPBundleFilterCheckDisabledSets
+ _SPBundleFilterComputeIOSOnlyResults
+ _SPBundleFilterComputeSourceAttributeResults
+ _SPBundleFilterEntitlementArrayContainsSuite
+ _SPBundleFilterErrorDomain
+ _SPBundleFilterEvaluateBundleIDLists
+ _SPBundleFilterEvaluateRelatedAppBundleIdentifier
+ _SPBundleFilterExpandAliasClasses
+ _SPBundleFilterHasAppProtectionReadAccess.hasAccess
+ _SPBundleFilterHasAppProtectionReadAccess.onceToken
+ _SPBundleFilterHasSpotlightUIPreferencesReadAccess.hasAccess
+ _SPBundleFilterHasSpotlightUIPreferencesReadAccess.onceToken
+ _SPBundleFilterIndexLookupAttributeNeeded
+ _SPBundleFilterItemNeedsFileProviderContainerCheck
+ _SPBundleFilterItemsInState
+ _SPBundleFilterOptionIsActive
+ _SPBundleFilterRunServerXPCStep
+ _SPBundleFilterStringEquals
+ _SSAppExclusionsEnabled
+ _SSCopyExcludedAppBundleIDsFromPreferencesCache
+ _SSGetDisabledAppSet
+ _SSGetDisabledBundleSet
+ _SSInvalidateAppExclusionsDisabledIDsCache
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateFromSelf
+ __OBJC_$_CLASS_METHODS_SPBundleFilter
+ __OBJC_$_CLASS_METHODS_SPGenerativeSearchClient(Spotlight|Spotlight)
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilterResolvedDimensions
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilteringContext
+ __OBJC_$_INSTANCE_METHODS_SPGenerativeSearchClient(Spotlight|Spotlight)
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilterResolvedDimensions
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilteringContext
+ __OBJC_$_PROP_LIST_SPBundleFilterResolvedDimensions
+ __OBJC_$_PROP_LIST_SPBundleFilteringContext
+ __OBJC_CLASS_RO_$_SPBundleFilter
+ __OBJC_CLASS_RO_$_SPBundleFilterResolvedDimensions
+ __OBJC_CLASS_RO_$_SPBundleFilteringContext
+ __OBJC_METACLASS_RO_$_SPBundleFilter
+ __OBJC_METACLASS_RO_$_SPBundleFilterResolvedDimensions
+ __OBJC_METACLASS_RO_$_SPBundleFilteringContext
+ __SPTCCSiriAccessChangedCallback
+ ___27-[SPClientSession activate]_block_invoke_2
+ ___SPBundleFilterAliasClasses_block_invoke
+ ___SPBundleFilterAwaitServerXPCReply_block_invoke
+ ___SPBundleFilterHasAppProtectionReadAccess_block_invoke
+ ___SPBundleFilterHasSpotlightUIPreferencesReadAccess_block_invoke
+ ___SPBundleFilterMergeAttributeBackfillResults_block_invoke
+ ____SPTCCSiriAccessChangedCallback_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
+ ___block_descriptor_64_e8_32s40r48r56r_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16lr40l8r48l8r56l8s32l8
+ ___swift_closure_destructor.157Tm
+ ___swift_closure_destructorTm
+ ___swift_project_boxed_opaque_existential_1
+ _activate.sTCCObserverOnce
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
+ _notify_cancel
+ _objc_setProperty_nonatomic_copy
+ _swift_beginAccess
+ _swift_endAccess
+ _swift_retain_x27
+ _symbolic _____y_____GSg 12HybridSearch15ComposableQueryV AA11MailContentV
+ _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 12HybridSearch15ComposableQueryV AC11MailContentV
- -[SPClientSession disabledBundleIds]
- -[SPSearchQueryContext(GenerativeSearch) appScopeBundleIdentifier]
- -[SPSearchQueryContext(GenerativeSearch) appScopeEntity]
- -[SPSearchQueryContext(GenerativeSearch) isAppScopedSearch]
- GCC_except_table103
- GCC_except_table111
- GCC_except_table121
- GCC_except_table131
- GCC_except_table18
- GCC_except_table65
- GCC_except_table67
- GCC_except_table69
- GCC_except_table79
- _OBJC_CLASS_$_SPSearchAppEntity
- _SPGetDisabledAppSet
- _SPGetDisabledBundleSet
- __INSTANCE_METHODS_SPGenerativeSearchClient
- __OBJC_$_CLASS_METHODS_SPGenerativeSearchClient(Spotlight)
- ___39-[SPCSSearchQuery slowFetchAttributes:]_block_invoke_2
- ___block_descriptor_40_ea8_32s_e37_v32?0"SPSearchTopHitResult"8Q16^B24ls32l8
- ___block_descriptor_56_ea8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- ___swift_closure_destructor.186Tm
- _symbolic _____ 12HybridSearch15RetrievalResultV
```
