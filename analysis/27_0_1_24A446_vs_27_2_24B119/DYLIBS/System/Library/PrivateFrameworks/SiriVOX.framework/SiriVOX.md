## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/SiriVOX`

```diff

-3600.52.7.0.0
-  __TEXT.__text: 0x84418
-  __TEXT.__objc_methlist: 0x8b58
+3605.19.1.0.0
+  __TEXT.__text: 0x867c8
+  __TEXT.__objc_methlist: 0x8cb0
   __TEXT.__const: 0x124
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x97
   __TEXT.__swift5_fieldmd: 0x38
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x11850
+  __TEXT.__cstring: 0x11b5e
   __TEXT.__swift5_capture: 0x78
   __TEXT.__swift5_reflstr: 0x16
-  __TEXT.__gcc_except_tab: 0x57c
-  __TEXT.__oslogstring: 0x89be
+  __TEXT.__gcc_except_tab: 0x5e8
+  __TEXT.__oslogstring: 0x8ec0
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__unwind_info: 0x23c8
+  __TEXT.__unwind_info: 0x2460
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2be8
-  __DATA_CONST.__objc_classlist: 0x668
+  __DATA_CONST.__const: 0x2ca8
+  __DATA_CONST.__objc_classlist: 0x678
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d70
+  __DATA_CONST.__objc_selrefs: 0x3e58
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x498
+  __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x980
-  __DATA_CONST.__got: 0x788
-  __AUTH_CONST.__const: 0xc28
-  __AUTH_CONST.__cfstring: 0x5fe0
-  __AUTH_CONST.__objc_const: 0x13688
+  __DATA_CONST.__got: 0x798
+  __AUTH_CONST.__const: 0xc08
+  __AUTH_CONST.__cfstring: 0x6020
+  __AUTH_CONST.__objc_const: 0x13a28
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_dictobj: 0x348
-  __AUTH_CONST.__auth_got: 0x6d8
+  __AUTH_CONST.__auth_got: 0x6e8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x40b0
+  __AUTH.__objc_data: 0x4150
   __AUTH.__data: 0x38
-  __DATA.__objc_ivar: 0xca8
+  __DATA.__objc_ivar: 0xce8
   __DATA.__data: 0x2260
   __DATA.__bss: 0x268
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3142
-  Symbols:   6675
+  Functions: 3187
+  Symbols:   6765
   CStrings:  0
 
Symbols:
+ -[SVXHomePodUIBridgeClientDelegate cancelPendingFollowUpActivation]
+ -[SVXHomePodUIBridgeClientDelegate didFinishPlayback]
+ -[SVXHomePodUIBridgeClientDelegate didPauseTTSForCurrentUserTurn]
+ -[SVXHomePodUIBridgeClientDelegate lasAttendingTimeoutSeconds]
+ -[SVXHomePodUIBridgeClientDelegate setDidPauseTTSForCurrentUserTurn:]
+ -[SVXHomePodUIBridgeClientDelegate setLasAttendingTimeoutSeconds:]
+ -[SVXMissingAssetActivationDecision .cxx_destruct]
+ -[SVXMissingAssetActivationDecision initWithShouldDeclineActivation:promptLocalizationKey:]
+ -[SVXMissingAssetActivationDecision promptLocalizationKey]
+ -[SVXMissingAssetActivationDecision shouldDeclineActivation]
+ -[SVXMissingAssetActivationGuard .cxx_destruct]
+ -[SVXMissingAssetActivationGuard _siriAvailabilityChanged]
+ -[SVXMissingAssetActivationGuard dealloc]
+ -[SVXMissingAssetActivationGuard decisionForActivationIdentifier:]
+ -[SVXMissingAssetActivationGuard initWithAvailabilityReporter:siriAvailabilityProvider:instrumentationUtils:]
+ -[SVXMissingAssetActivationGuard init]
+ -[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]
+ -[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]
+ -[SVXSession _electionLedger]
+ -[SVXSession _isRootRequestHoldToTalk]
+ -[SVXSession _useElectionLedger:]
+ -[SVXSession _waitForLedgerDecisionForElection:usingHandler:]
+ -[SVXSession beginElectionWithIdentity:]
+ -[SVXSession currentActivationContext]
+ -[SVXSession releaseAudioSessionIfIdleForReason:]
+ -[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]
+ -[SVXSession speechSynthesizerDidFinishPlayback]
+ -[SVXSessionUtils isUserInitiatedDeviceActivationWithContext:]
+ -[SVXSiriActivationListenerDelegate initWithSiriActivationListener:mainQueuePerformer:siriActivationSupportPredicate:virtualDeviceManager:instrumentationUtils:activationUtils:]
+ GCC_except_table1147
+ GCC_except_table1162
+ GCC_except_table1218
+ GCC_except_table1489
+ GCC_except_table1631
+ GCC_except_table1632
+ GCC_except_table1662
+ GCC_except_table1668
+ GCC_except_table1669
+ GCC_except_table1700
+ GCC_except_table1804
+ GCC_except_table1806
+ GCC_except_table1807
+ GCC_except_table1914
+ GCC_except_table2079
+ GCC_except_table2104
+ GCC_except_table2241
+ GCC_except_table2364
+ GCC_except_table2366
+ GCC_except_table2368
+ GCC_except_table2384
+ GCC_except_table2385
+ GCC_except_table2513
+ GCC_except_table2517
+ GCC_except_table2519
+ GCC_except_table2522
+ GCC_except_table2828
+ GCC_except_table2983
+ GCC_except_table3058
+ GCC_except_table772
+ _CFNotificationCenterRemoveObserver
+ _OBJC_CLASS_$_SCDAElectionLedger
+ _OBJC_CLASS_$_SISchemaUEIUUFRReady
+ _OBJC_CLASS_$_SVXMissingAssetActivationDecision
+ _OBJC_CLASS_$_SVXMissingAssetActivationGuard
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._attendingStateQueue
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._didPauseTTSForCurrentUserTurn
+ _OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._lasAttendingTimeoutSeconds
+ _OBJC_IVAR_$_SVXMissingAssetActivationDecision._promptLocalizationKey
+ _OBJC_IVAR_$_SVXMissingAssetActivationDecision._shouldDeclineActivation
+ _OBJC_IVAR_$_SVXMissingAssetActivationGuard._availabilityReporter
+ _OBJC_IVAR_$_SVXMissingAssetActivationGuard._instrumentationUtils
+ _OBJC_IVAR_$_SVXMissingAssetActivationGuard._siriAvailability
+ _OBJC_IVAR_$_SVXMissingAssetActivationGuard._siriAvailabilityProvider
+ _OBJC_IVAR_$_SVXSession._electionIdentity
+ _OBJC_IVAR_$_SVXSession._electionLedgerOverride
+ _OBJC_IVAR_$_SVXSession._launchSignpostIsButton
+ _OBJC_IVAR_$_SVXSession._ledgerDeliveryQueue
+ _OBJC_IVAR_$_SVXSession._rootRequestWasHoldToTalk
+ _OBJC_IVAR_$_SVXSessionManager._missingAssetGuard
+ _OBJC_IVAR_$_SVXSessionManager._sessionUtils
+ _OBJC_IVAR_$_SVXSpeechSynthesizer._streamTaskTrackers
+ _OBJC_IVAR_$_SVXSpeechSynthesizer._streamsWithFinishedPlayback
+ _OBJC_METACLASS_$_SVXMissingAssetActivationDecision
+ _OBJC_METACLASS_$_SVXMissingAssetActivationGuard
+ __OBJC_$_INSTANCE_METHODS_SVXMissingAssetActivationDecision
+ __OBJC_$_INSTANCE_METHODS_SVXMissingAssetActivationGuard
+ __OBJC_$_INSTANCE_VARIABLES_SVXMissingAssetActivationDecision
+ __OBJC_$_INSTANCE_VARIABLES_SVXMissingAssetActivationGuard
+ __OBJC_$_PROP_LIST_SVXMissingAssetActivationDecision
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SVXSpeechSynthesisListening
+ __OBJC_CLASS_RO_$_SVXMissingAssetActivationDecision
+ __OBJC_CLASS_RO_$_SVXMissingAssetActivationGuard
+ __OBJC_METACLASS_RO_$_SVXMissingAssetActivationDecision
+ __OBJC_METACLASS_RO_$_SVXMissingAssetActivationGuard
+ __SVXStoreDemoGetLocalizationKeyForStyle2
+ ___118-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]_block_invoke
+ ___27-[SVXSession allTimersIdle]_block_invoke_2
+ ___38-[SVXMissingAssetActivationGuard init]_block_invoke
+ ___46-[SVXHomePodUIBridgeClientDelegate invalidate]_block_invoke
+ ___48-[SVXSession speechSynthesizerDidFinishPlayback]_block_invoke
+ ___49-[SVXSession releaseAudioSessionIfIdleForReason:]_block_invoke
+ ___53-[SVXHomePodUIBridgeClientDelegate didFinishPlayback]_block_invoke
+ ___60-[SVXSession uiBridgeClientShouldActivateForLASWithContext:]_block_invoke
+ ___61-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]_block_invoke
+ ___61-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]_block_invoke_2
+ ___61-[SVXSession uiBridgeClientDidStopAttendingWithoutActivation]_block_invoke
+ ___66-[SVXMissingAssetActivationGuard decisionForActivationIdentifier:]_block_invoke
+ ___66-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]_block_invoke
+ ___67-[SVXHomePodUIBridgeClientDelegate cancelPendingFollowUpActivation]_block_invoke
+ ___67-[SVXSessionManager _activateWithContext:activityState:completion:]_block_invoke
+ ___67-[SVXSessionManager _activateWithContext:activityState:completion:]_block_invoke_2
+ ___69-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceWillStartAttending]_block_invoke
+ ___71-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDetectedSpeechStart:]_block_invoke
+ ___73-[SVXHomePodUIBridgeClientDelegate beginAttendingForFollowUpWithContext:]_block_invoke
+ ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidDetectUserSpeechWithContext:]_block_invoke
+ ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidFinalizeUserTurnWithContext:]_block_invoke
+ ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceReceivedSpeechMitigationResult:]_block_invoke
+ ___90-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDidStopAttendingUnexpectedlyWithReason:]_block_invoke
+ ___block_descriptor_32_e28_"<SVXSiriAvailability>"8?0l
+ ___block_descriptor_48_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e32_v20?0B8"SCDAElectionOutcome"12ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ _objc_release_x3
- -[SVXHomePodUIBridgeClientDelegate willPromptListeningAfterSpeaking]
- -[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]
- -[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]
- -[SVXSiriActivationListenerDelegate _siriAvailabilityChanged]
- -[SVXSiriActivationListenerDelegate initWithSiriActivationListener:mainQueuePerformer:siriActivationSupportPredicate:virtualDeviceManager:instrumentationUtils:activationUtils:siriAvailability:availabilityReporter:]
- GCC_except_table1158
- GCC_except_table1173
- GCC_except_table1229
- GCC_except_table1500
- GCC_except_table1642
- GCC_except_table1643
- GCC_except_table1673
- GCC_except_table1679
- GCC_except_table1680
- GCC_except_table1811
- GCC_except_table1813
- GCC_except_table1814
- GCC_except_table1921
- GCC_except_table2081
- GCC_except_table2214
- GCC_except_table2337
- GCC_except_table2352
- GCC_except_table2353
- GCC_except_table2472
- GCC_except_table2476
- GCC_except_table2478
- GCC_except_table2481
- GCC_except_table2783
- GCC_except_table2938
- GCC_except_table3013
- GCC_except_table783
- _OBJC_IVAR_$_SVXSiriActivationListenerDelegate._availabilityReporter
- _OBJC_IVAR_$_SVXSiriActivationListenerDelegate._siriAvailability
- ___101-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]_block_invoke
```
