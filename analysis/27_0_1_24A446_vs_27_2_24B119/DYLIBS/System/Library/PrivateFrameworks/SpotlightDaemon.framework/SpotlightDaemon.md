## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/SpotlightDaemon`

```diff

-2459.105.0.0.0
-  __TEXT.__text: 0xc463c
-  __TEXT.__objc_methlist: 0x4bd4
-  __TEXT.__const: 0x3e8
-  __TEXT.__cstring: 0x991b
-  __TEXT.__gcc_except_tab: 0x4a1c
-  __TEXT.__oslogstring: 0xd359
-  __TEXT.__dlopen_cstrs: 0x4a
-  __TEXT.__unwind_info: 0x2900
+2465.1.9.0.0
+  __TEXT.__text: 0xcae84
+  __TEXT.__objc_methlist: 0x4e04
+  __TEXT.__const: 0x410
+  __TEXT.__cstring: 0x9f53
+  __TEXT.__gcc_except_tab: 0x4a80
+  __TEXT.__oslogstring: 0xd788
+  __TEXT.__dlopen_cstrs: 0xf4
+  __TEXT.__unwind_info: 0x2a78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x47b0
-  __DATA_CONST.__objc_classlist: 0x1b0
+  __DATA_CONST.__const: 0x4980
+  __DATA_CONST.__objc_classlist: 0x1d0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d18
+  __DATA_CONST.__objc_selrefs: 0x3f00
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x138
-  __DATA_CONST.__objc_arraydata: 0x310
-  __DATA_CONST.__got: 0xbf8
-  __AUTH_CONST.__const: 0x1328
-  __AUTH_CONST.__cfstring: 0x7fa0
-  __AUTH_CONST.__objc_const: 0x6128
+  __DATA_CONST.__objc_superrefs: 0x150
+  __DATA_CONST.__objc_arraydata: 0x318
+  __DATA_CONST.__got: 0xc38
+  __AUTH_CONST.__const: 0x1428
+  __AUTH_CONST.__cfstring: 0x8320
+  __AUTH_CONST.__objc_const: 0x6540
   __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__objc_arrayobj: 0x3a8
+  __AUTH_CONST.__objc_arrayobj: 0x3c0
   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1120
+  __AUTH_CONST.__auth_got: 0x1140
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0x540
-  __DATA.__data: 0x418
-  __DATA.__bss: 0x160
+  __AUTH.__objc_data: 0x280
+  __DATA.__objc_ivar: 0x56c
+  __DATA.__data: 0x410
+  __DATA.__bss: 0x198
   __DATA.__common: 0x4
   __DATA_DIRTY.__objc_data: 0xfa0
-  __DATA_DIRTY.__data: 0x158
-  __DATA_DIRTY.__bss: 0x6d8
+  __DATA_DIRTY.__data: 0x160
+  __DATA_DIRTY.__bss: 0x750
   __DATA_DIRTY.__common: 0x18
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3378
-  Symbols:   5048
+  Functions: 3477
+  Symbols:   5216
   CStrings:  0
 
Symbols:
+ +[CSAccessMetricsRegistry sharedRegistry]
+ +[CSAccessMetricsReporter reportAccessForClient:target:kind:]
+ -[CSAccessMetricsRegistry .cxx_destruct]
+ -[CSAccessMetricsRegistry claimFirstSightOfClient:target:kind:]
+ -[CSAccessMetricsRegistry init]
+ -[CSAccessTuple .cxx_destruct]
+ -[CSAccessTuple hash]
+ -[CSAccessTuple initWithClient:target:kind:]
+ -[CSAccessTuple isEqual:]
+ -[CSBundleFilterEscalatedIdentifiers .cxx_destruct]
+ -[CSBundleFilterEscalatedIdentifiers excludedAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers fileProviderExcludedBundleIDs]
+ -[CSBundleFilterEscalatedIdentifiers hiddenAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers initWithLockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:mdmRestrictedBundleIdentifiers:excludedAppBundleIdentifiers:fileProviderExcludedBundleIDs:]
+ -[CSBundleFilterEscalatedIdentifiers lockedAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers mdmRestrictedBundleIdentifiers]
+ -[MDSearchableIndexService _decodeAttributeBackfillResultForGroup:plistBytes:]
+ -[MDSearchableIndexService _decodeBundleFilterEvaluationRequest:error:]
+ -[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]
+ -[MDSearchableIndexService _mergeFileProviderExcludedBundleIDsForRequest:lockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:excludedAppBundleIdentifiers:]
+ -[MDSearchableIndexService _processIndexDataForBundle:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:completionHandler:]
+ -[MDSearchableIndexService _rejectIfDisallowedBundleID:]
+ -[MDSearchableIndexService _rejectIfNotInternal:reason:]
+ -[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]
+ -[MDSearchableIndexService _resolveEscalatedIdentifiersForRequest:]
+ -[MDSearchableIndexService _resolveExcludedAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]
+ -[MDSearchableIndexService _resolveHiddenAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveLockedAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveMDMRestrictedBundleIdentifiers]
+ -[MDSearchableIndexService _sendBundleFilterEvaluationReply:overConnection:indexID:evaluationReply:attributeBackfillResults:evaluationError:escalated:]
+ -[MDSearchableIndexService _validateAttributeBackfillGroup:]
+ -[MDSearchableIndexService _validateAttributeBackfillGroupsInRequest:]
+ -[MDSearchableIndexService _validateBundleFilterEvaluationRequest:]
+ -[MDSearchableIndexService _validateFileProviderContainerGroup:]
+ -[MDSearchableIndexService _validateFileProviderContainerGroupsInRequest:]
+ -[MDSearchableIndexService evaluateFilters:]
+ -[SPConcreteCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]
+ -[SPConcreteCoreSpotlightIndexer _oidPath:containsAnyOID:]
+ -[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]
+ -[SPCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]
+ -[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]
+ -[SPCoreSpotlightTask _knownDisabledBundleIDsFromBundleIDs:excludingFPBundleIDs:]
+ -[SPCoreSpotlightTask _makeNotificationSourcesQueryStringWithBundleIDs:]
+ -[SPCoreSpotlightTask _makePrefsQueryStringWithPrefsDisabledBundles:]
+ GCC_except_table1004
+ GCC_except_table102
+ GCC_except_table1033
+ GCC_except_table1034
+ GCC_except_table104
+ GCC_except_table1043
+ GCC_except_table1059
+ GCC_except_table1100
+ GCC_except_table1105
+ GCC_except_table1156
+ GCC_except_table1190
+ GCC_except_table1196
+ GCC_except_table1197
+ GCC_except_table1203
+ GCC_except_table1204
+ GCC_except_table1205
+ GCC_except_table1206
+ GCC_except_table1217
+ GCC_except_table1232
+ GCC_except_table1238
+ GCC_except_table1242
+ GCC_except_table1256
+ GCC_except_table127
+ GCC_except_table1272
+ GCC_except_table1279
+ GCC_except_table128
+ GCC_except_table1286
+ GCC_except_table129
+ GCC_except_table1293
+ GCC_except_table131
+ GCC_except_table1317
+ GCC_except_table1395
+ GCC_except_table1396
+ GCC_except_table1398
+ GCC_except_table1405
+ GCC_except_table1468
+ GCC_except_table1475
+ GCC_except_table1602
+ GCC_except_table1603
+ GCC_except_table176
+ GCC_except_table177
+ GCC_except_table178
+ GCC_except_table179
+ GCC_except_table180
+ GCC_except_table181
+ GCC_except_table182
+ GCC_except_table183
+ GCC_except_table184
+ GCC_except_table185
+ GCC_except_table186
+ GCC_except_table187
+ GCC_except_table188
+ GCC_except_table189
+ GCC_except_table19
+ GCC_except_table190
+ GCC_except_table192
+ GCC_except_table193
+ GCC_except_table194
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table198
+ GCC_except_table199
+ GCC_except_table200
+ GCC_except_table201
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table207
+ GCC_except_table324
+ GCC_except_table342
+ GCC_except_table348
+ GCC_except_table382
+ GCC_except_table396
+ GCC_except_table429
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table457
+ GCC_except_table47
+ GCC_except_table486
+ GCC_except_table487
+ GCC_except_table502
+ GCC_except_table503
+ GCC_except_table53
+ GCC_except_table533
+ GCC_except_table557
+ GCC_except_table571
+ GCC_except_table574
+ GCC_except_table585
+ GCC_except_table586
+ GCC_except_table587
+ GCC_except_table60
+ GCC_except_table625
+ GCC_except_table639
+ GCC_except_table64
+ GCC_except_table65
+ GCC_except_table651
+ GCC_except_table674
+ GCC_except_table680
+ GCC_except_table699
+ GCC_except_table70
+ GCC_except_table700
+ GCC_except_table710
+ GCC_except_table743
+ GCC_except_table768
+ GCC_except_table769
+ GCC_except_table770
+ GCC_except_table79
+ GCC_except_table796
+ GCC_except_table82
+ GCC_except_table862
+ GCC_except_table87
+ GCC_except_table88
+ GCC_except_table886
+ GCC_except_table908
+ GCC_except_table912
+ GCC_except_table916
+ GCC_except_table94
+ GCC_except_table944
+ GCC_except_table973
+ GCC_except_table98
+ _CSAccessMetricsReportQuery
+ _CSAccessMetricsSendQueue.onceToken
+ _CSAccessMetricsSendQueue.queue
+ _CSShouldTraceMessagesDonation
+ _MDItemEventSourceBundleIdentifier
+ _OBJC_CLASS_$_CSAccessMetricsRegistry
+ _OBJC_CLASS_$_CSAccessMetricsReporter
+ _OBJC_CLASS_$_CSAccessTuple
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillResult
+ _OBJC_CLASS_$_CSBundleFilterEscalatedIdentifiers
+ _OBJC_CLASS_$_CSBundleFilterEvaluationReply
+ _OBJC_CLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_IVAR_$_CSAccessMetricsRegistry._lock
+ _OBJC_IVAR_$_CSAccessMetricsRegistry._seen
+ _OBJC_IVAR_$_CSAccessTuple._client
+ _OBJC_IVAR_$_CSAccessTuple._hash
+ _OBJC_IVAR_$_CSAccessTuple._kind
+ _OBJC_IVAR_$_CSAccessTuple._target
+ _OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._excludedAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._fileProviderExcludedBundleIDs
+ _OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._hiddenAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._lockedAppBundleIdentifiers
+ _OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._mdmRestrictedBundleIdentifiers
+ _OBJC_METACLASS_$_CSAccessMetricsRegistry
+ _OBJC_METACLASS_$_CSAccessMetricsReporter
+ _OBJC_METACLASS_$_CSAccessTuple
+ _OBJC_METACLASS_$_CSBundleFilterEscalatedIdentifiers
+ _SPBundleFilterAllowedAttributeBackfillAttributeNames.onceToken
+ _SPBundleFilterAllowedAttributeBackfillAttributeNames.sAllowed
+ _SpotlightServicesLibraryCore.frameworkLibrary
+ __MDPlistContainerAllocFailure
+ __OBJC_$_CLASS_METHODS_CSAccessMetricsRegistry
+ __OBJC_$_CLASS_METHODS_CSAccessMetricsReporter
+ __OBJC_$_INSTANCE_METHODS_CSAccessMetricsRegistry
+ __OBJC_$_INSTANCE_METHODS_CSAccessTuple
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterEscalatedIdentifiers
+ __OBJC_$_INSTANCE_VARIABLES_CSAccessMetricsRegistry
+ __OBJC_$_INSTANCE_VARIABLES_CSAccessTuple
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterEscalatedIdentifiers
+ __OBJC_$_PROP_LIST_CSBundleFilterEscalatedIdentifiers
+ __OBJC_CLASS_RO_$_CSAccessMetricsRegistry
+ __OBJC_CLASS_RO_$_CSAccessMetricsReporter
+ __OBJC_CLASS_RO_$_CSAccessTuple
+ __OBJC_CLASS_RO_$_CSBundleFilterEscalatedIdentifiers
+ __OBJC_METACLASS_RO_$_CSAccessMetricsRegistry
+ __OBJC_METACLASS_RO_$_CSAccessMetricsReporter
+ __OBJC_METACLASS_RO_$_CSAccessTuple
+ __OBJC_METACLASS_RO_$_CSBundleFilterEscalatedIdentifiers
+ __SDEventMonitorSetUserInfoError
+ ___101-[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]_block_invoke
+ ___101-[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]_block_invoke_2
+ ___107-[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]_block_invoke
+ ___107-[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]_block_invoke_2
+ ___107-[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]_block_invoke_3
+ ___137-[SPCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]_block_invoke
+ ___137-[SPCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]_block_invoke_2
+ ___145-[SPConcreteCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]_block_invoke
+ ___145-[SPConcreteCoreSpotlightIndexer _matchFileProviderContainerExclusionsForBundleID:identifiers:knownOIDPaths:excludedBundleIDs:completionHandler:]_block_invoke_2
+ ___234-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke
+ ___234-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke_2
+ ___234-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke_3
+ ___234-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke_4
+ ___234-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke_5
+ ___242-[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke
+ ___242-[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:donationXPCTraceID:deletes:canCreateNewIndex:completionHandler:]_block_invoke_2
+ ___41+[CSAccessMetricsRegistry sharedRegistry]_block_invoke
+ ___44-[MDSearchableIndexService evaluateFilters:]_block_invoke
+ ___58-[SPConcreteCoreSpotlightIndexer _oidPath:containsAnyOID:]_block_invoke
+ ___88-[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]_block_invoke
+ ___88-[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]_block_invoke_2
+ ___CSAccessMetricsSendQueue_block_invoke
+ ___CSAccessMetricsSend_block_invoke
+ ___CSAccessMetricsSend_block_invoke_2
+ ___MDQueryCreateStringByAddingBackslashEscapes
+ ___SPBundleFilterAllowedAttributeBackfillAttributeNames_block_invoke
+ ___SpotlightServicesLibraryCore_block_invoke
+ ____bgst_queue_block_invoke
+ ___bgst_complete_task_block_invoke
+ ___bgst_expire_task_block_invoke
+ ___bgst_register_task_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s_e63_v32?0"CSBundleFilterEvaluationReply"8"NSArray"16"NSError"24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_160_e8_32s40s48s56s64s72s80r88r96r104r112r120w_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40lw120l8r80l8r88l8s32l8s40l8r96l8r104l8r112l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_162_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s120l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104s112s120r128r136r_e40_v16?0"SPConcreteCoreSpotlightIndexer"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8r120l8r128l8r136l8
+ ___block_descriptor_202_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136bs144w_e18_v20?0^{__SI=}8C16lw144l8s136l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8s128l8
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSArray"8lr40l8s32l8
+ ___block_descriptor_48_e8_32s40s_e25_v16?0"OSLogEventProxy"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e37_v24?0Q8"OSLogEventStreamPosition"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48s_e35_v32?0"NSString"8"NSString"16^B24ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32bs40r48r56r_e5_v8?0ls32l8r40l8r48l8r56l8
+ ___block_descriptor_64_e8_32s40s48r_e5_v8?0ls32l8r48l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_73_e8_32s40s48s56r64r_e5_v8?0lr56l8r64l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e20_v24?08"NSError"16ls32l8s40l8r64l8r72l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e41_v32?0"NSArray"8"NSArray"16"NSError"24lr64l8r72l8s32l8s40l8s48l8s56l8
+ ___getSSCopyExcludedAppBundleIDsFromPreferencesCacheSymbolLoc_block_invoke
+ ___isWellFormedBundleID_block_invoke
+ ___logForCSLogCategoryDonationTracing_block_invoke
+ ___syslogCollectSlice_block_invoke
+ ___syslogMakeStream_block_invoke
+ __bgst_queue
+ __bgst_queue.onceToken
+ __bgst_queue.queue
+ __oidPath:containsAnyOID:.nonDigits
+ __oidPath:containsAnyOID:.onceToken
+ _audit_stringSpotlightServices
+ _bgst_complete_task
+ _bgst_expire_task
+ _bgst_register_task
+ _bundleIDsPassingGrammar
+ _getSSCopyExcludedAppBundleIDsFromPreferencesCacheSymbolLoc.ptr
+ _isWellFormedBundleID
+ _isWellFormedBundleID.allowed
+ _isWellFormedBundleID.once
+ _kSPUserActivityPurgeTargets_block_invoke_11.registered
+ _kSyslogSliceDurations
+ _logForCSLogCategoryDonationTracing
+ _logForCSLogCategoryDonationTracing.onceToken
+ _logForCSLogCategoryDonationTracing.sDonationTracingLog
+ _sharedRegistry.onceToken
+ _sharedRegistry.sharedInstance
+ _stringQueryTemplatesOnly
+ _syslogDateString
+ _syslogEventTimestamp
+ _syslogFileGeneration
+ _syslogLocalTimeString
+ _syslogLossMarker
+ _syslogRotateGenerations
+ _syslogSliceStamp
+ _syslogWriteHeader
+ _syslogWriteLine
+ _syslogWriteTrailer
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
- -[MDSearchableIndexService _processIndexDataForBundle:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:completionHandler:]
- -[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]
- -[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]
- -[SPCoreSpotlightTask _makePrefsQueryStringWithBundleIDs:prefsDisabledBundles:]
- GCC_except_table1012
- GCC_except_table1013
- GCC_except_table1022
- GCC_except_table1038
- GCC_except_table1039
- GCC_except_table105
- GCC_except_table108
- GCC_except_table1083
- GCC_except_table1088
- GCC_except_table113
- GCC_except_table1139
- GCC_except_table114
- GCC_except_table1173
- GCC_except_table1179
- GCC_except_table1180
- GCC_except_table1186
- GCC_except_table1187
- GCC_except_table1188
- GCC_except_table1189
- GCC_except_table1198
- GCC_except_table1200
- GCC_except_table1221
- GCC_except_table1225
- GCC_except_table123
- GCC_except_table1239
- GCC_except_table124
- GCC_except_table125
- GCC_except_table1255
- GCC_except_table1262
- GCC_except_table1269
- GCC_except_table1276
- GCC_except_table1283
- GCC_except_table134
- GCC_except_table135
- GCC_except_table136
- GCC_except_table1378
- GCC_except_table1379
- GCC_except_table138
- GCC_except_table1381
- GCC_except_table1388
- GCC_except_table1448
- GCC_except_table1455
- GCC_except_table150
- GCC_except_table151
- GCC_except_table152
- GCC_except_table153
- GCC_except_table154
- GCC_except_table155
- GCC_except_table156
- GCC_except_table157
- GCC_except_table158
- GCC_except_table1582
- GCC_except_table1583
- GCC_except_table161
- GCC_except_table162
- GCC_except_table163
- GCC_except_table165
- GCC_except_table166
- GCC_except_table314
- GCC_except_table322
- GCC_except_table338
- GCC_except_table362
- GCC_except_table386
- GCC_except_table419
- GCC_except_table420
- GCC_except_table424
- GCC_except_table447
- GCC_except_table45
- GCC_except_table476
- GCC_except_table477
- GCC_except_table48
- GCC_except_table492
- GCC_except_table493
- GCC_except_table50
- GCC_except_table52
- GCC_except_table523
- GCC_except_table547
- GCC_except_table561
- GCC_except_table564
- GCC_except_table575
- GCC_except_table576
- GCC_except_table577
- GCC_except_table59
- GCC_except_table615
- GCC_except_table629
- GCC_except_table63
- GCC_except_table640
- GCC_except_table659
- GCC_except_table665
- GCC_except_table684
- GCC_except_table685
- GCC_except_table695
- GCC_except_table723
- GCC_except_table748
- GCC_except_table749
- GCC_except_table750
- GCC_except_table77
- GCC_except_table776
- GCC_except_table78
- GCC_except_table842
- GCC_except_table86
- GCC_except_table866
- GCC_except_table887
- GCC_except_table89
- GCC_except_table891
- GCC_except_table895
- GCC_except_table90
- GCC_except_table923
- GCC_except_table952
- GCC_except_table96
- GCC_except_table983
- _OUTLINED_FUNCTION_46
- __SDEventMonitorErrorMake
- ___215-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke
- ___215-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke_2
- ___215-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke_3
- ___215-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke_4
- ___215-[SPConcreteCoreSpotlightIndexer indexFromBundle:fromClient:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke_5
- ___223-[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke
- ___223-[SPCoreSpotlightIndexer indexFromBundle:fromClient:protectionClass:personaID:options:items:itemsText:itemsHTML:clientState:expectedClientState:clientStateName:donationTimestamp:deletes:canCreateNewIndex:completionHandler:]_block_invoke_2
- ___block_descriptor_152_e8_32s40s48s56s64s72r80r88r96r104r112w_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40lw112l8r72l8s32l8r80l8r88l8r96l8r104l8s40l8s48l8s56l8s64l8
- ___block_descriptor_154_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s120l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
- ___block_descriptor_160_e8_32s40s48s56s64s72s80s88s96s104s112s120r128r136r_e40_v16?0"SPConcreteCoreSpotlightIndexer"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8r120l8r128l8r136l8
- ___block_descriptor_194_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136bs144w_e18_v20?0^{__SI=}8C16lw144l8s136l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8s128l8
- ___block_descriptor_40_e8_32s_e25_v16?0"OSLogEventProxy"8ls32l8
- ___block_descriptor_40_e8_32s_e37_v24?0Q8"OSLogEventStreamPosition"16ls32l8
- ___block_descriptor_72_e8_32s40s48s56r64r_e5_v8?0lr56l8r64l8s32l8s40l8s48l8
- ___collectSpotlightLogs_block_invoke_2
```
