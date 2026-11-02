## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/SiriCrossDeviceArbitration`

```diff

-3600.49.15.0.0
-  __TEXT.__text: 0x2f934
-  __TEXT.__objc_methlist: 0x310c
-  __TEXT.__const: 0x1a8
-  __TEXT.__dlopen_cstrs: 0x118
-  __TEXT.__gcc_except_tab: 0x3ac
-  __TEXT.__oslogstring: 0x55b0
-  __TEXT.__cstring: 0x5dd1
-  __TEXT.__unwind_info: 0xe30
+3605.25.1.0.0
+  __TEXT.__text: 0x3d49c
+  __TEXT.__objc_methlist: 0x3d94
+  __TEXT.__const: 0x2e8
+  __TEXT.__dlopen_cstrs: 0x15c
+  __TEXT.__constg_swiftt: 0x54
+  __TEXT.__swift5_typeref: 0x5f
+  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_types: 0x8
+  __TEXT.__cstring: 0x72eb
+  __TEXT.__swift5_capture: 0x10
+  __TEXT.__swift5_reflstr: 0x18
+  __TEXT.__swift5_fieldmd: 0x28
+  __TEXT.__swift_as_entry: 0x4
+  __TEXT.__swift_as_ret: 0x4
+  __TEXT.__swift_as_cont: 0x4
+  __TEXT.__swift5_assocty: 0x18
+  __TEXT.__swift5_proto: 0x4
+  __TEXT.__gcc_except_tab: 0x48c
+  __TEXT.__oslogstring: 0x77f8
+  __TEXT.__unwind_info: 0x1220
+  __TEXT.__eh_frame: 0x70
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1068
-  __DATA_CONST.__objc_classlist: 0x148
-  __DATA_CONST.__objc_protolist: 0x78
+  __DATA_CONST.__const: 0x1518
+  __DATA_CONST.__objc_classlist: 0x1c8
+  __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e10
-  __DATA_CONST.__objc_superrefs: 0x128
+  __DATA_CONST.__objc_selrefs: 0x2448
+  __DATA_CONST.__objc_protorefs: 0x10
+  __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_arraydata: 0x60
-  __DATA_CONST.__got: 0x2e8
-  __AUTH_CONST.__const: 0x2c0
-  __AUTH_CONST.__cfstring: 0x2ea0
-  __AUTH_CONST.__objc_const: 0x5338
+  __DATA_CONST.__got: 0x3b0
+  __AUTH_CONST.__const: 0x578
+  __AUTH_CONST.__cfstring: 0x3940
+  __AUTH_CONST.__objc_const: 0x6bb0
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x438
-  __AUTH_CONST.__auth_ptr: 0x0
-  __DATA.__objc_ivar: 0x4fc
-  __DATA.__data: 0x5d0
-  __DATA.__bss: 0x1b0
-  __DATA_DIRTY.__objc_data: 0xcd0
-  __DATA_DIRTY.__bss: 0x8
+  __AUTH_CONST.__auth_got: 0x578
+  __AUTH_CONST.__auth_ptr: 0x38
+  __DATA.__objc_ivar: 0x630
+  __DATA.__data: 0x30
+  __DATA.__bss: 0x2e0
+  __DATA_DIRTY.__objc_data: 0x11d0
+  __DATA_DIRTY.__data: 0x748
+  __DATA_DIRTY.__bss: 0x18
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
+  - /System/Library/Frameworks/Security.framework/Security
   - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
   - /System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics
   - /System/Library/PrivateFrameworks/SiriCrossDeviceArbitrationFeedback.framework/SiriCrossDeviceArbitrationFeedback

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftMetal.dylib

   - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1241
-  Symbols:   2314
+  Functions: 1598
+  Symbols:   2992
   CStrings:  0
 
Symbols:
+ +[SCDACoordinator(ElectionLedger) mintElectionIdentity]
+ +[SCDADeviceRoutingPriority bestSiriDeviceRoutingTargetInCandidates:winnerDeviceClass:domain:]
+ +[SCDADeviceRoutingPriority canDeviceClass:holdForWinnerClass:]
+ +[SCDADeviceRoutingPriority eligibleStandbyIdsInCandidates:winnerDeviceClass:]
+ +[SCDADeviceRoutingPriority isLocalEligibleRoutingTargetInCandidates:]
+ +[SCDADeviceRoutingPriority isWinnerDecidedLocallyWithoutElectionInCandidates:]
+ +[SCDADeviceRoutingPriority standbyCapablePeersInCandidates:]
+ +[SCDAElectionCandidate candidatesFromReplies:]
+ +[SCDAElectionCandidate candidatesFromReplies:nameResolver:]
+ +[SCDAElectionCandidate candidatesFromResults:]
+ +[SCDAElectionCandidate deviceClassesInCandidates:]
+ +[SCDAElectionCandidate supportsSecureCoding]
+ +[SCDAElectionCandidate winnerIdsIdentifierInCandidates:]
+ +[SCDAElectionDataPublisher clearPublishedElectionData]
+ +[SCDAElectionIdentity identityWithRawValue:]
+ +[SCDAElectionIdentity supportsSecureCoding]
+ +[SCDAElectionLedger sharedLedger]
+ +[SCDAElectionLedgerPublisher initialize]
+ +[SCDAElectionLedgerPublisher startWithEndpointForTesting:]
+ +[SCDAElectionLedgerPublisher start]
+ +[SCDAElectionLedgerReceiver _startWithLedger:listener:requiresPeerEntitlement:]
+ +[SCDAElectionLedgerReceiver initialize]
+ +[SCDAElectionLedgerReceiver startAnonymousReceiverWithLedgerForTesting:]
+ +[SCDAElectionLedgerReceiver startWithLedger:]
+ +[SCDAElectionOutcome supportsSecureCoding]
+ +[SCDAFeatureFlags isDeviceSelectionEnabled]
+ +[SCDAFeatureFlags isElectionLedgerEnabled]
+ +[SCDAFeatureFlags isMonitorDataSiriDeviceRoutingEnabled]
+ +[SCDAFeatureFlags isWatchBoostRebalanceEnabled]
+ +[SCDAFeatureFlags setDeviceSelectionEnabledOverride:]
+ +[SCDAFeatureFlags setElectionLedgerEnabledOverride:]
+ +[SCDAFeatureFlags setMonitorDataSiriDeviceRoutingEnabledOverride:]
+ +[SCDAFeatureFlags setWatchBoostRebalanceEnabledOverride:]
+ +[SCDAMonitor deviceClassesFromElectionData:]
+ +[SCDAStandbyObserver announceStandbyDidBegin]
+ +[SCDAStandbyObserver announceStandbyDidEndAsWon:]
+ +[SCDAStandbyObserver sharedObserver]
+ +[SCDAUtilities setIsATVOverride:]
+ +[SCDAUtilities setIsCommunalOverride:]
+ +[SCDAUtilities shouldAdvertiseEmergencyContinuation]
+ +[SCDAUtilities siriDeviceRoutingMode]
+ -[SCDACoordinator _initiateEmergencyCall]
+ -[SCDACoordinator _maybeEngageRoutingTargetStandby]
+ -[SCDACoordinator init]
+ -[SCDACoordinator(ElectionLedger) _ledgerPublisher]
+ -[SCDACoordinator(ElectionLedger) _publishElectionOutcomeWithDidWin:provisional:]
+ -[SCDACoordinator(ElectionLedger) _publishProvisionalResolutionWithLost:]
+ -[SCDACoordinator(ElectionLedger) _resolveCurrentElectionIdentityAsLostWithReason:]
+ -[SCDACoordinator(ElectionLedger) _tagElectionWithIdentity:origin:]
+ -[SCDACoordinator(ElectionLedger) _useElectionLedgerPublisher:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) currentElectionIdentity]
+ -[SCDACoordinator(ElectionLedger) electionLedger]
+ -[SCDACoordinator(ElectionLedger) setElectionLedger:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromAlertFiringVoiceTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromDirectTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromInTaskVoiceTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromVoiceTriggerAdjusted:withContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromVoiceTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startAdvertisingFromVoiceTriggerWithGoodnessScoreContext:withContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startWatchAdvertisingFromDirectTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(ElectionLedger) startWatchAdvertisingFromVoiceTriggerWithContext:electionIdentity:]
+ -[SCDACoordinator(SiriDeviceRoutingStandby) _clearPendingStandby]
+ -[SCDACoordinator(SiriDeviceRoutingStandby) _endPendingStandbyAnnouncingWon:]
+ -[SCDACoordinator(SiriDeviceRoutingStandby) _engageRoutingTargetStandbyForGeneration:]
+ -[SCDACoordinator(SiriDeviceRoutingStandby) _resolvePendingStandbyAsWon:]
+ -[SCDACoordinator(SiriDeviceRoutingStandby) handleRoutingTargetReleaseWithLost:]
+ -[SCDADevice idsDeviceID]
+ -[SCDADevice setIdsDeviceID:]
+ -[SCDADeviceNameInfo .cxx_destruct]
+ -[SCDADeviceNameInfo description]
+ -[SCDADeviceNameInfo deviceName]
+ -[SCDADeviceNameInfo initWithRoomName:deviceName:]
+ -[SCDADeviceNameInfo roomName]
+ -[SCDAElectionCandidate .cxx_destruct]
+ -[SCDAElectionCandidate copyWithZone:]
+ -[SCDAElectionCandidate deviceClass]
+ -[SCDAElectionCandidate deviceGroup]
+ -[SCDAElectionCandidate deviceName]
+ -[SCDAElectionCandidate encodeWithCoder:]
+ -[SCDAElectionCandidate goodnessScore]
+ -[SCDAElectionCandidate hash]
+ -[SCDAElectionCandidate idsIdentifier]
+ -[SCDAElectionCandidate initWithCoder:]
+ -[SCDAElectionCandidate initWithDictionary:]
+ -[SCDAElectionCandidate initWithIdsIdentifier:goodnessScore:deviceClass:productType:isWinner:isLocalDevice:deviceGroup:userConfidence:pHash:deviceName:]
+ -[SCDAElectionCandidate initWithIdsIdentifier:goodnessScore:deviceClass:productType:isWinner:isLocalDevice:deviceGroup:userConfidence:pHash:deviceName:electionId:]
+ -[SCDAElectionCandidate initWithIdsIdentifier:goodnessScore:deviceClass:productType:isWinner:isLocalDevice:deviceGroup:userConfidence:pHash:deviceName:roomName:]
+ -[SCDAElectionCandidate isEqual:]
+ -[SCDAElectionCandidate isLocalDevice]
+ -[SCDAElectionCandidate isWinner]
+ -[SCDAElectionCandidate pHash]
+ -[SCDAElectionCandidate productType]
+ -[SCDAElectionCandidate roomName]
+ -[SCDAElectionCandidate toDictionary]
+ -[SCDAElectionCandidate userConfidence]
+ -[SCDAElectionDataPublisher publishElectionDataFromReplies:generation:]
+ -[SCDAElectionIdentity copyWithZone:]
+ -[SCDAElectionIdentity description]
+ -[SCDAElectionIdentity encodeWithCoder:]
+ -[SCDAElectionIdentity hash]
+ -[SCDAElectionIdentity initWithCoder:]
+ -[SCDAElectionIdentity initWithRawValue:]
+ -[SCDAElectionIdentity init]
+ -[SCDAElectionIdentity isEqual:]
+ -[SCDAElectionIdentity rawValue]
+ -[SCDAElectionLedger .cxx_destruct]
+ -[SCDAElectionLedger _armTimeoutTimer]
+ -[SCDAElectionLedger _deliverDecision:on:identity:didWin:outcome:source:reason:detail:registeredAt:]
+ -[SCDAElectionLedger _entryForIdentity:]
+ -[SCDAElectionLedger _evaluateTimeouts]
+ -[SCDAElectionLedger _evictEntry:]
+ -[SCDAElectionLedger _parkWaiter:forIdentity:existingEntry:]
+ -[SCDAElectionLedger _parkWaiterForIdentity:entry:reason:detail:deliverOn:completion:]
+ -[SCDAElectionLedger _pruneActivationKinds]
+ -[SCDAElectionLedger _pruneHistory]
+ -[SCDAElectionLedger _registerActivationKind:forIdentity:]
+ -[SCDAElectionLedger _resolveEntry:withOutcome:didWin:observed:]
+ -[SCDAElectionLedger _resolveEntry:withOutcome:didWin:observed:source:]
+ -[SCDAElectionLedger _resolveProvisionalEntry:withResult:]
+ -[SCDAElectionLedger _stateSnapshot]
+ -[SCDAElectionLedger dealloc]
+ -[SCDAElectionLedger debugDescription]
+ -[SCDAElectionLedger decisionForElection:reason:detail:deliverOn:completion:]
+ -[SCDAElectionLedger entryCount]
+ -[SCDAElectionLedger evaluateTimeouts]
+ -[SCDAElectionLedger initWithClock:decisionTimeout:promotionWindow:]
+ -[SCDAElectionLedger invalidate]
+ -[SCDAElectionLedger outstandingWaiterCount]
+ -[SCDAElectionLedger recordOutcome:]
+ -[SCDAElectionLedger recordProvisionalOutcome:]
+ -[SCDAElectionLedger registeredActivationKindCount]
+ -[SCDAElectionLedger resolveProvisionalOutcomeForElectionId:result:]
+ -[SCDAElectionLedger setActivationKind:forElection:]
+ -[SCDAElectionLedgerEntry .cxx_destruct]
+ -[SCDAElectionLedgerEntry deadlineContinuousNanos]
+ -[SCDAElectionLedgerEntry identity]
+ -[SCDAElectionLedgerEntry initWithIdentity:]
+ -[SCDAElectionLedgerEntry outcome]
+ -[SCDAElectionLedgerEntry resolvedAtContinuousNanos]
+ -[SCDAElectionLedgerEntry setDeadlineContinuousNanos:]
+ -[SCDAElectionLedgerEntry setIdentity:]
+ -[SCDAElectionLedgerEntry setOutcome:]
+ -[SCDAElectionLedgerEntry setResolvedAtContinuousNanos:]
+ -[SCDAElectionLedgerEntry setState:]
+ -[SCDAElectionLedgerEntry setWaiters:]
+ -[SCDAElectionLedgerEntry state]
+ -[SCDAElectionLedgerEntry waiters]
+ -[SCDAElectionLedgerPublisher .cxx_destruct]
+ -[SCDAElectionLedgerPublisher _configureConnection:]
+ -[SCDAElectionLedgerPublisher _initWithConnection:requiresPeerVerification:]
+ -[SCDAElectionLedgerPublisher _receiver]
+ -[SCDAElectionLedgerPublisher _verifyPeer:]
+ -[SCDAElectionLedgerPublisher flushPendingPublishes]
+ -[SCDAElectionLedgerPublisher invalidate]
+ -[SCDAElectionLedgerPublisher publishOutcome:provisional:]
+ -[SCDAElectionLedgerPublisher publishProvisionalResolutionForElectionId:result:]
+ -[SCDAElectionLedgerPublisher reconnectToEndpointForTesting:]
+ -[SCDAElectionLedgerPublisher replayRetainedOutcomesWithReply:]
+ -[SCDAElectionLedgerReceiver .cxx_destruct]
+ -[SCDAElectionLedgerReceiver _initWithLedger:listener:requiresPeerEntitlement:]
+ -[SCDAElectionLedgerReceiver _isTornDownSynchronized]
+ -[SCDAElectionLedgerReceiver _requestReplayOverConnection:]
+ -[SCDAElectionLedgerReceiver connectedPublisherCount]
+ -[SCDAElectionLedgerReceiver deliverOutcome:provisional:]
+ -[SCDAElectionLedgerReceiver endpoint]
+ -[SCDAElectionLedgerReceiver invalidate]
+ -[SCDAElectionLedgerReceiver listener:shouldAcceptNewConnection:]
+ -[SCDAElectionLedgerReceiver resolveProvisionalOutcomeForElectionId:holdResult:]
+ -[SCDAElectionLedgerReceiver waitForDeliveredOutcomes]
+ -[SCDAElectionLedgerWaiter .cxx_destruct]
+ -[SCDAElectionLedgerWaiter decisionBlock]
+ -[SCDAElectionLedgerWaiter deliveryQueue]
+ -[SCDAElectionLedgerWaiter detail]
+ -[SCDAElectionLedgerWaiter reason]
+ -[SCDAElectionLedgerWaiter registeredAtContinuousNanos]
+ -[SCDAElectionLedgerWaiter setDecisionBlock:]
+ -[SCDAElectionLedgerWaiter setDeliveryQueue:]
+ -[SCDAElectionLedgerWaiter setDetail:]
+ -[SCDAElectionLedgerWaiter setReason:]
+ -[SCDAElectionLedgerWaiter setRegisteredAtContinuousNanos:]
+ -[SCDAElectionOutcome .cxx_destruct]
+ -[SCDAElectionOutcome candidates]
+ -[SCDAElectionOutcome copyWithZone:]
+ -[SCDAElectionOutcome description]
+ -[SCDAElectionOutcome didWin]
+ -[SCDAElectionOutcome electionId]
+ -[SCDAElectionOutcome encodeWithCoder:]
+ -[SCDAElectionOutcome hash]
+ -[SCDAElectionOutcome identity]
+ -[SCDAElectionOutcome initWithCoder:]
+ -[SCDAElectionOutcome initWithIdentity:electionId:didWin:candidates:resolvedAtContinuousNanos:]
+ -[SCDAElectionOutcome isEqual:]
+ -[SCDAElectionOutcome participatingDeviceClasses]
+ -[SCDAElectionOutcome resolvedAtContinuousNanos]
+ -[SCDAGoodnessScoreEvaluator signedAdjustedBoostForGoodnessScoreContext:]
+ -[SCDAHoldController .cxx_destruct]
+ -[SCDAHoldController _releaseOnQueue:]
+ -[SCDAHoldController _releaseOnQueue:suppressNotification:]
+ -[SCDAHoldController _startWatchdogOnQueue]
+ -[SCDAHoldController currentGeneration]
+ -[SCDAHoldController dealloc]
+ -[SCDAHoldController evaluateAndHoldIfNeededWithEligibility:generation:expectedSenderIdsId:onRelease:]
+ -[SCDAHoldController expectedSenderIdsId]
+ -[SCDAHoldController holdWatchdogTimeout]
+ -[SCDAHoldController init]
+ -[SCDAHoldController isHolding]
+ -[SCDAHoldController onRelease]
+ -[SCDAHoldController queue]
+ -[SCDAHoldController releaseHoldLocallyWithResult:]
+ -[SCDAHoldController releaseHoldWithResult:fromSenderIdsId:]
+ -[SCDAHoldController setCurrentGeneration:]
+ -[SCDAHoldController setExpectedSenderIdsId:]
+ -[SCDAHoldController setHoldWatchdogTimeout:]
+ -[SCDAHoldController setOnRelease:]
+ -[SCDAHoldController setQueue:]
+ -[SCDAHoldController setWatchdog:]
+ -[SCDAHoldController watchdog]
+ -[SCDAMonitor _engageRoutingTargetHoldIfEligible]
+ -[SCDAMonitor _runSyncOnMonitorQueue:]
+ -[SCDAMonitor _setElectionDataForTesting:]
+ -[SCDAMonitor deviceClassesInMostRecentElection]
+ -[SCDAMonitor deviceNameResolver]
+ -[SCDAMonitor initForTesting]
+ -[SCDAMonitor releaseRoutingTargetHoldAsWon:fromSenderIdsId:]
+ -[SCDAMonitor setDeviceNameResolver:]
+ -[SCDARecord idsDeviceID]
+ -[SCDARecord setIdsDeviceID:]
+ -[SCDARecord(InternalDebug) debugDeviceDescription]
+ -[SCDARoutingTargetReleaseObserver .cxx_destruct]
+ -[SCDARoutingTargetReleaseObserver callbackQueue]
+ -[SCDARoutingTargetReleaseObserver dealloc]
+ -[SCDARoutingTargetReleaseObserver delegate]
+ -[SCDARoutingTargetReleaseObserver initWithDelegate:]
+ -[SCDARoutingTargetReleaseObserver observing]
+ -[SCDARoutingTargetReleaseObserver setCallbackQueue:]
+ -[SCDARoutingTargetReleaseObserver setObserving:]
+ -[SCDARoutingTargetReleaseObserver startObserving]
+ -[SCDARoutingTargetReleaseObserver stopObserving]
+ -[SCDAStandbyHoldCoordinator .cxx_destruct]
+ -[SCDAStandbyHoldCoordinator cancelAnyHold]
+ -[SCDAStandbyHoldCoordinator engageHoldIfEligibleInCandidates:generation:onRelease:]
+ -[SCDAStandbyHoldCoordinator init]
+ -[SCDAStandbyHoldCoordinator isHolding]
+ -[SCDAStandbyHoldCoordinator releaseHoldAsWon:fromSenderIdsId:]
+ -[SCDAStandbyObserver .cxx_destruct]
+ -[SCDAStandbyObserver _initSharedObserver]
+ -[SCDAStandbyObserver _listener]
+ -[SCDAStandbyObserver removeListener:]
+ -[SCDAStandbyObserver setListener:]
+ GCC_except_table1007
+ GCC_except_table1080
+ GCC_except_table1132
+ GCC_except_table1135
+ GCC_except_table1139
+ GCC_except_table1144
+ GCC_except_table1171
+ GCC_except_table1215
+ GCC_except_table1235
+ GCC_except_table1256
+ GCC_except_table1320
+ GCC_except_table1321
+ GCC_except_table1419
+ GCC_except_table1422
+ GCC_except_table1434
+ GCC_except_table1467
+ GCC_except_table1469
+ GCC_except_table1545
+ GCC_except_table1546
+ GCC_except_table1552
+ GCC_except_table244
+ GCC_except_table250
+ GCC_except_table513
+ GCC_except_table62
+ GCC_except_table749
+ GCC_except_table758
+ GCC_except_table914
+ GCC_except_table943
+ GCC_except_table947
+ GCC_except_table951
+ OBJC_IVAR_$_SCDACoordinator._currentElectionIdentity
+ OBJC_IVAR_$_SCDACoordinator._delegate
+ OBJC_IVAR_$_SCDACoordinator._electionLedgerOverride
+ OBJC_IVAR_$_SCDACoordinator._electionLedgerPublisher
+ OBJC_IVAR_$_SCDACoordinator._isElectionIdentityHeldForStandby
+ OBJC_IVAR_$_SCDACoordinator._myriadWorkQueue
+ OBJC_IVAR_$_SCDACoordinator._nTimesExtended
+ OBJC_IVAR_$_SCDACoordinator._pendingLedgerElectionId
+ OBJC_IVAR_$_SCDACoordinator._pendingStandbyGeneration
+ OBJC_IVAR_$_SCDACoordinator._pendingStandbyTimer
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFNotificationCenterRemoveEveryObserver
+ _CFRelease
+ _IDSLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ _OBJC_CLASS_$_NSXPCConnection
+ _OBJC_CLASS_$_NSXPCInterface
+ _OBJC_CLASS_$_NSXPCListener
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_SCDADeviceNameInfo
+ _OBJC_CLASS_$_SCDADeviceRoutingPriority
+ _OBJC_CLASS_$_SCDAElectionCandidate
+ _OBJC_CLASS_$_SCDAElectionDataPublisher
+ _OBJC_CLASS_$_SCDAElectionIdentity
+ _OBJC_CLASS_$_SCDAElectionLedger
+ _OBJC_CLASS_$_SCDAElectionLedgerEntry
+ _OBJC_CLASS_$_SCDAElectionLedgerPublisher
+ _OBJC_CLASS_$_SCDAElectionLedgerReceiver
+ _OBJC_CLASS_$_SCDAElectionLedgerWaiter
+ _OBJC_CLASS_$_SCDAElectionOutcome
+ _OBJC_CLASS_$_SCDAFeatureFlags
+ _OBJC_CLASS_$_SCDAHoldController
+ _OBJC_CLASS_$_SCDARoutingTargetReleaseObserver
+ _OBJC_CLASS_$_SCDAStandbyHoldCoordinator
+ _OBJC_CLASS_$_SCDAStandbyObserver
+ _OBJC_IVAR_$_SCDACoordinator._electionDataPublisher
+ _OBJC_IVAR_$_SCDACoordinator._routingTargetReleaseObserver
+ _OBJC_IVAR_$_SCDADevice._idsDeviceID
+ _OBJC_IVAR_$_SCDADeviceNameInfo._deviceName
+ _OBJC_IVAR_$_SCDADeviceNameInfo._roomName
+ _OBJC_IVAR_$_SCDAElectionCandidate._deviceClass
+ _OBJC_IVAR_$_SCDAElectionCandidate._deviceGroup
+ _OBJC_IVAR_$_SCDAElectionCandidate._deviceName
+ _OBJC_IVAR_$_SCDAElectionCandidate._goodnessScore
+ _OBJC_IVAR_$_SCDAElectionCandidate._idsIdentifier
+ _OBJC_IVAR_$_SCDAElectionCandidate._isLocalDevice
+ _OBJC_IVAR_$_SCDAElectionCandidate._isWinner
+ _OBJC_IVAR_$_SCDAElectionCandidate._pHash
+ _OBJC_IVAR_$_SCDAElectionCandidate._productType
+ _OBJC_IVAR_$_SCDAElectionCandidate._roomName
+ _OBJC_IVAR_$_SCDAElectionCandidate._userConfidence
+ _OBJC_IVAR_$_SCDAElectionIdentity._rawValue
+ _OBJC_IVAR_$_SCDAElectionLedger._activationKindOrder
+ _OBJC_IVAR_$_SCDAElectionLedger._activationKinds
+ _OBJC_IVAR_$_SCDAElectionLedger._clock
+ _OBJC_IVAR_$_SCDAElectionLedger._decisionTimeout
+ _OBJC_IVAR_$_SCDAElectionLedger._entries
+ _OBJC_IVAR_$_SCDAElectionLedger._evictedIdentities
+ _OBJC_IVAR_$_SCDAElectionLedger._isInvalidated
+ _OBJC_IVAR_$_SCDAElectionLedger._promotionWindow
+ _OBJC_IVAR_$_SCDAElectionLedger._provisionalIdentity
+ _OBJC_IVAR_$_SCDAElectionLedger._stateQueue
+ _OBJC_IVAR_$_SCDAElectionLedger._timer
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._deadlineContinuousNanos
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._identity
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._outcome
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._resolvedAtContinuousNanos
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._state
+ _OBJC_IVAR_$_SCDAElectionLedgerEntry._waiters
+ _OBJC_IVAR_$_SCDAElectionLedgerPublisher._connection
+ _OBJC_IVAR_$_SCDAElectionLedgerPublisher._replayHistory
+ _OBJC_IVAR_$_SCDAElectionLedgerPublisher._requiresPeerVerification
+ _OBJC_IVAR_$_SCDAElectionLedgerPublisher._stateQueue
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._connections
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._deliveryQueue
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._isTornDown
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._ledger
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._listener
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._requiresPeerEntitlement
+ _OBJC_IVAR_$_SCDAElectionLedgerReceiver._stateQueue
+ _OBJC_IVAR_$_SCDAElectionLedgerWaiter._decisionBlock
+ _OBJC_IVAR_$_SCDAElectionLedgerWaiter._deliveryQueue
+ _OBJC_IVAR_$_SCDAElectionLedgerWaiter._detail
+ _OBJC_IVAR_$_SCDAElectionLedgerWaiter._reason
+ _OBJC_IVAR_$_SCDAElectionLedgerWaiter._registeredAtContinuousNanos
+ _OBJC_IVAR_$_SCDAElectionOutcome._candidates
+ _OBJC_IVAR_$_SCDAElectionOutcome._didWin
+ _OBJC_IVAR_$_SCDAElectionOutcome._electionId
+ _OBJC_IVAR_$_SCDAElectionOutcome._identity
+ _OBJC_IVAR_$_SCDAElectionOutcome._resolvedAtContinuousNanos
+ _OBJC_IVAR_$_SCDAHoldController._currentGeneration
+ _OBJC_IVAR_$_SCDAHoldController._expectedSenderIdsId
+ _OBJC_IVAR_$_SCDAHoldController._holdWatchdogTimeout
+ _OBJC_IVAR_$_SCDAHoldController._onRelease
+ _OBJC_IVAR_$_SCDAHoldController._queue
+ _OBJC_IVAR_$_SCDAHoldController._watchdog
+ _OBJC_IVAR_$_SCDAMonitor._deviceNameResolver
+ _OBJC_IVAR_$_SCDAMonitor._holdCoordinator
+ _OBJC_IVAR_$_SCDAMonitor._mostRecentElectionData
+ _OBJC_IVAR_$_SCDARecord._idsDeviceID
+ _OBJC_IVAR_$_SCDARoutingTargetReleaseObserver._callbackQueue
+ _OBJC_IVAR_$_SCDARoutingTargetReleaseObserver._delegate
+ _OBJC_IVAR_$_SCDARoutingTargetReleaseObserver._observing
+ _OBJC_IVAR_$_SCDAStandbyHoldCoordinator._holdController
+ _OBJC_IVAR_$_SCDAStandbyObserver._listener
+ _OBJC_METACLASS_$_SCDADeviceNameInfo
+ _OBJC_METACLASS_$_SCDADeviceRoutingPriority
+ _OBJC_METACLASS_$_SCDAElectionCandidate
+ _OBJC_METACLASS_$_SCDAElectionDataPublisher
+ _OBJC_METACLASS_$_SCDAElectionIdentity
+ _OBJC_METACLASS_$_SCDAElectionLedger
+ _OBJC_METACLASS_$_SCDAElectionLedgerEntry
+ _OBJC_METACLASS_$_SCDAElectionLedgerPublisher
+ _OBJC_METACLASS_$_SCDAElectionLedgerReceiver
+ _OBJC_METACLASS_$_SCDAElectionLedgerWaiter
+ _OBJC_METACLASS_$_SCDAElectionOutcome
+ _OBJC_METACLASS_$_SCDAFeatureFlags
+ _OBJC_METACLASS_$_SCDAHoldController
+ _OBJC_METACLASS_$_SCDARoutingTargetReleaseObserver
+ _OBJC_METACLASS_$_SCDAStandbyHoldCoordinator
+ _OBJC_METACLASS_$_SCDAStandbyObserver
+ _OUTLINED_FUNCTION_0
+ _SCDACanHandleEmergencyFlow
+ _SCDACanHostCarPlaySession
+ _SCDADecodeBoundedInt
+ _SCDADeviceClassDisplayName
+ _SCDADeviceRoutingDomainIdentifier
+ _SCDAElectionActivationKindArbitrates
+ _SCDAElectionActivationKindConflict
+ _SCDAElectionActivationKindDescription
+ _SCDAElectionActivationKindMissing
+ _SCDAElectionActivationKindSetConflictHandlerForTesting
+ _SCDAElectionDataKeyGeneration
+ _SCDAElectionDataKeyResults
+ _SCDAElectionEntryKeyDeviceClass
+ _SCDAElectionEntryKeyDeviceGroup
+ _SCDAElectionEntryKeyDeviceName
+ _SCDAElectionEntryKeyGoodness
+ _SCDAElectionEntryKeyIdsIdentifier
+ _SCDAElectionEntryKeyIsLocalDevice
+ _SCDAElectionEntryKeyIsWinner
+ _SCDAElectionEntryKeyPHash
+ _SCDAElectionEntryKeyProductType
+ _SCDAElectionEntryKeyRoomName
+ _SCDAElectionEntryKeyUserConfidence
+ _SCDAElectionIdentityMissing
+ _SCDAElectionIdentityReplaced
+ _SCDAElectionIdentitySetMissingHandlerForTesting
+ _SCDAElectionIdentitySetReplacedHandlerForTesting
+ _SCDAElectionLedgerAllowEntitlement
+ _SCDAElectionLedgerContinuousNanos
+ _SCDAElectionLedgerContinuousNanos.onceToken
+ _SCDAElectionLedgerContinuousNanos.timebase
+ _SCDAElectionLedgerDefaultDecisionTimeout
+ _SCDAElectionLedgerDefaultPromotionWindow
+ _SCDAElectionLedgerHistoryMaxAge
+ _SCDAElectionLedgerHistoryMaxCount
+ _SCDAElectionLedgerMachServiceName
+ _SCDAElectionLedgerPeerHasEntitlement
+ _SCDAElectionLedgerPublisherReplayHistoryMaxCount
+ _SCDAElectionLedgerTransportAllowedClasses
+ _SCDAElectionOriginDescription
+ _SCDAElectionWaitReasonDescription
+ _SCDAFeatureFlagSetOverride
+ _SCDAFeatureFlagValue
+ _SCDAHoldResultDescription
+ _SCDALiveReceivers
+ _SCDALiveReceivers.liveReceivers
+ _SCDALiveReceivers.onceToken
+ _SCDALivenessOutcome
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
+ __Block_copy
+ __Block_release
+ __OBJC_$_CLASS_METHODS_SCDACoordinator(ElectionLedger|SiriDeviceRoutingStandby)
+ __OBJC_$_CLASS_METHODS_SCDADeviceRoutingPriority
+ __OBJC_$_CLASS_METHODS_SCDAElectionCandidate
+ __OBJC_$_CLASS_METHODS_SCDAElectionDataPublisher
+ __OBJC_$_CLASS_METHODS_SCDAElectionIdentity
+ __OBJC_$_CLASS_METHODS_SCDAElectionLedger
+ __OBJC_$_CLASS_METHODS_SCDAElectionLedgerPublisher
+ __OBJC_$_CLASS_METHODS_SCDAElectionLedgerReceiver
+ __OBJC_$_CLASS_METHODS_SCDAElectionOutcome
+ __OBJC_$_CLASS_METHODS_SCDAFeatureFlags
+ __OBJC_$_CLASS_METHODS_SCDAStandbyObserver
+ __OBJC_$_CLASS_PROP_LIST_SCDAElectionCandidate
+ __OBJC_$_CLASS_PROP_LIST_SCDAElectionIdentity
+ __OBJC_$_CLASS_PROP_LIST_SCDAElectionOutcome
+ __OBJC_$_INSTANCE_METHODS_SCDACoordinator(ElectionLedger|SiriDeviceRoutingStandby)
+ __OBJC_$_INSTANCE_METHODS_SCDADeviceNameInfo
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionCandidate
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionDataPublisher
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionIdentity
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionLedger
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionLedgerEntry
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionLedgerPublisher
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionLedgerReceiver
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionLedgerWaiter
+ __OBJC_$_INSTANCE_METHODS_SCDAElectionOutcome
+ __OBJC_$_INSTANCE_METHODS_SCDAHoldController
+ __OBJC_$_INSTANCE_METHODS_SCDARoutingTargetReleaseObserver
+ __OBJC_$_INSTANCE_METHODS_SCDAStandbyHoldCoordinator
+ __OBJC_$_INSTANCE_METHODS_SCDAStandbyObserver
+ __OBJC_$_INSTANCE_VARIABLES_SCDADeviceNameInfo
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionCandidate
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionIdentity
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionLedger
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionLedgerEntry
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionLedgerPublisher
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionLedgerReceiver
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionLedgerWaiter
+ __OBJC_$_INSTANCE_VARIABLES_SCDAElectionOutcome
+ __OBJC_$_INSTANCE_VARIABLES_SCDAHoldController
+ __OBJC_$_INSTANCE_VARIABLES_SCDARoutingTargetReleaseObserver
+ __OBJC_$_INSTANCE_VARIABLES_SCDAStandbyHoldCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_SCDAStandbyObserver
+ __OBJC_$_PROP_LIST_SCDADeviceNameInfo
+ __OBJC_$_PROP_LIST_SCDAElectionCandidate
+ __OBJC_$_PROP_LIST_SCDAElectionIdentity
+ __OBJC_$_PROP_LIST_SCDAElectionLedgerEntry
+ __OBJC_$_PROP_LIST_SCDAElectionLedgerPublisher
+ __OBJC_$_PROP_LIST_SCDAElectionLedgerReceiver
+ __OBJC_$_PROP_LIST_SCDAElectionLedgerWaiter
+ __OBJC_$_PROP_LIST_SCDAElectionOutcome
+ __OBJC_$_PROP_LIST_SCDAHoldController
+ __OBJC_$_PROP_LIST_SCDARoutingTargetReleaseObserver
+ __OBJC_$_PROP_LIST_SCDAStandbyHoldCoordinator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCDAElectionLedgerPublisherProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCDAElectionLedgerReceiverProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCDARoutingTargetReleaseHandling
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SCDAElectionLedgerPublisherProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SCDAElectionLedgerReceiverProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SCDARoutingTargetReleaseHandling
+ __OBJC_$_PROTOCOL_REFS_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_REFS_SCDAElectionLedgerPublisherProtocol
+ __OBJC_$_PROTOCOL_REFS_SCDAElectionLedgerReceiverProtocol
+ __OBJC_$_PROTOCOL_REFS_SCDARoutingTargetReleaseHandling
+ __OBJC_CLASS_PROTOCOLS_$_SCDACoordinator(ElectionLedger|SiriDeviceRoutingStandby)
+ __OBJC_CLASS_PROTOCOLS_$_SCDAElectionCandidate
+ __OBJC_CLASS_PROTOCOLS_$_SCDAElectionIdentity
+ __OBJC_CLASS_PROTOCOLS_$_SCDAElectionLedgerPublisher
+ __OBJC_CLASS_PROTOCOLS_$_SCDAElectionLedgerReceiver
+ __OBJC_CLASS_PROTOCOLS_$_SCDAElectionOutcome
+ __OBJC_CLASS_RO_$_SCDADeviceNameInfo
+ __OBJC_CLASS_RO_$_SCDADeviceRoutingPriority
+ __OBJC_CLASS_RO_$_SCDAElectionCandidate
+ __OBJC_CLASS_RO_$_SCDAElectionDataPublisher
+ __OBJC_CLASS_RO_$_SCDAElectionIdentity
+ __OBJC_CLASS_RO_$_SCDAElectionLedger
+ __OBJC_CLASS_RO_$_SCDAElectionLedgerEntry
+ __OBJC_CLASS_RO_$_SCDAElectionLedgerPublisher
+ __OBJC_CLASS_RO_$_SCDAElectionLedgerReceiver
+ __OBJC_CLASS_RO_$_SCDAElectionLedgerWaiter
+ __OBJC_CLASS_RO_$_SCDAElectionOutcome
+ __OBJC_CLASS_RO_$_SCDAFeatureFlags
+ __OBJC_CLASS_RO_$_SCDAHoldController
+ __OBJC_CLASS_RO_$_SCDARoutingTargetReleaseObserver
+ __OBJC_CLASS_RO_$_SCDAStandbyHoldCoordinator
+ __OBJC_CLASS_RO_$_SCDAStandbyObserver
+ __OBJC_LABEL_PROTOCOL_$_NSXPCListenerDelegate
+ __OBJC_LABEL_PROTOCOL_$_SCDAElectionLedgerPublisherProtocol
+ __OBJC_LABEL_PROTOCOL_$_SCDAElectionLedgerReceiverProtocol
+ __OBJC_LABEL_PROTOCOL_$_SCDARoutingTargetReleaseHandling
+ __OBJC_METACLASS_RO_$_SCDADeviceNameInfo
+ __OBJC_METACLASS_RO_$_SCDADeviceRoutingPriority
+ __OBJC_METACLASS_RO_$_SCDAElectionCandidate
+ __OBJC_METACLASS_RO_$_SCDAElectionDataPublisher
+ __OBJC_METACLASS_RO_$_SCDAElectionIdentity
+ __OBJC_METACLASS_RO_$_SCDAElectionLedger
+ __OBJC_METACLASS_RO_$_SCDAElectionLedgerEntry
+ __OBJC_METACLASS_RO_$_SCDAElectionLedgerPublisher
+ __OBJC_METACLASS_RO_$_SCDAElectionLedgerReceiver
+ __OBJC_METACLASS_RO_$_SCDAElectionLedgerWaiter
+ __OBJC_METACLASS_RO_$_SCDAElectionOutcome
+ __OBJC_METACLASS_RO_$_SCDAFeatureFlags
+ __OBJC_METACLASS_RO_$_SCDAHoldController
+ __OBJC_METACLASS_RO_$_SCDARoutingTargetReleaseObserver
+ __OBJC_METACLASS_RO_$_SCDAStandbyHoldCoordinator
+ __OBJC_METACLASS_RO_$_SCDAStandbyObserver
+ __OBJC_PROTOCOL_$_NSXPCListenerDelegate
+ __OBJC_PROTOCOL_$_SCDAElectionLedgerPublisherProtocol
+ __OBJC_PROTOCOL_$_SCDAElectionLedgerReceiverProtocol
+ __OBJC_PROTOCOL_$_SCDARoutingTargetReleaseHandling
+ __OBJC_PROTOCOL_REFERENCE_$_SCDAElectionLedgerPublisherProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_SCDAElectionLedgerReceiverProtocol
+ __SCDABestIdsIdMatching
+ __SCDABestRoutingTargetIdsId
+ __SCDAReleaseLostCallback
+ __SCDAReleaseWonCallback
+ ___100-[SCDAElectionLedger _deliverDecision:on:identity:didWin:outcome:source:reason:detail:registeredAt:]_block_invoke
+ ___102-[SCDAHoldController evaluateAndHoldIfNeededWithEligibility:generation:expectedSenderIdsId:onRelease:]_block_invoke
+ ___29-[SCDAElectionLedger dealloc]_block_invoke
+ ___31-[SCDAHoldController isHolding]_block_invoke
+ ___32-[SCDAElectionLedger entryCount]_block_invoke
+ ___32-[SCDAElectionLedger invalidate]_block_invoke
+ ___34+[SCDAElectionLedger sharedLedger]_block_invoke
+ ___35-[SCDAElectionLedger _pruneHistory]_block_invoke
+ ___36-[SCDACoordinator initWithDelegate:]_block_invoke_2
+ ___36-[SCDAElectionLedger recordOutcome:]_block_invoke
+ ___37+[SCDAStandbyObserver sharedObserver]_block_invoke
+ ___38-[SCDAElectionLedger debugDescription]_block_invoke
+ ___38-[SCDAElectionLedger evaluateTimeouts]_block_invoke
+ ___40-[SCDAElectionLedgerPublisher _receiver]_block_invoke
+ ___40-[SCDAElectionLedgerReceiver invalidate]_block_invoke
+ ___41-[SCDAElectionLedgerPublisher invalidate]_block_invoke
+ ___42-[SCDAMonitor _setElectionDataForTesting:]_block_invoke
+ ___43-[SCDAHoldController _startWatchdogOnQueue]_block_invoke
+ ___44-[SCDAElectionLedger outstandingWaiterCount]_block_invoke
+ ___47-[SCDAElectionLedger recordProvisionalOutcome:]_block_invoke
+ ___48-[SCDAMonitor deviceClassesInMostRecentElection]_block_invoke
+ ___49-[SCDAMonitor _engageRoutingTargetHoldIfEligible]_block_invoke
+ ___51-[SCDAElectionLedger registeredActivationKindCount]_block_invoke
+ ___51-[SCDAHoldController releaseHoldLocallyWithResult:]_block_invoke
+ ___52-[SCDAElectionLedger setActivationKind:forElection:]_block_invoke
+ ___52-[SCDAElectionLedgerPublisher _configureConnection:]_block_invoke
+ ___52-[SCDAElectionLedgerPublisher flushPendingPublishes]_block_invoke
+ ___53-[SCDAElectionLedgerReceiver _isTornDownSynchronized]_block_invoke
+ ___53-[SCDAElectionLedgerReceiver connectedPublisherCount]_block_invoke
+ ___54-[SCDAElectionLedgerReceiver waitForDeliveredOutcomes]_block_invoke
+ ___57-[SCDAElectionLedgerReceiver deliverOutcome:provisional:]_block_invoke
+ ___58-[SCDAElectionLedgerPublisher publishOutcome:provisional:]_block_invoke
+ ___59-[SCDAElectionLedgerReceiver _requestReplayOverConnection:]_block_invoke
+ ___59-[SCDAElectionLedgerReceiver _requestReplayOverConnection:]_block_invoke_2
+ ___60-[SCDAHoldController releaseHoldWithResult:fromSenderIdsId:]_block_invoke
+ ___61-[SCDAElectionLedgerPublisher reconnectToEndpointForTesting:]_block_invoke
+ ___63-[SCDAElectionLedgerPublisher replayRetainedOutcomesWithReply:]_block_invoke
+ ___65-[SCDAElectionLedgerReceiver listener:shouldAcceptNewConnection:]_block_invoke
+ ___65-[SCDAElectionLedgerReceiver listener:shouldAcceptNewConnection:]_block_invoke_2
+ ___65-[SCDAElectionLedgerReceiver listener:shouldAcceptNewConnection:]_block_invoke_3
+ ___65-[SCDAElectionLedgerReceiver listener:shouldAcceptNewConnection:]_block_invoke_4
+ ___68-[SCDAElectionLedger initWithClock:decisionTimeout:promotionWindow:]_block_invoke
+ ___68-[SCDAElectionLedger initWithClock:decisionTimeout:promotionWindow:]_block_invoke_2
+ ___68-[SCDAElectionLedger resolveProvisionalOutcomeForElectionId:result:]_block_invoke
+ ___77-[SCDAElectionLedger decisionForElection:reason:detail:deliverOn:completion:]_block_invoke
+ ___80-[SCDACoordinator(SiriDeviceRoutingStandby) handleRoutingTargetReleaseWithLost:]_block_invoke
+ ___80-[SCDAElectionLedgerPublisher publishProvisionalResolutionForElectionId:result:]_block_invoke
+ ___80-[SCDAElectionLedgerReceiver resolveProvisionalOutcomeForElectionId:holdResult:]_block_invoke
+ ___84-[SCDAStandbyHoldCoordinator engageHoldIfEligibleInCandidates:generation:onRelease:]_block_invoke
+ ___86-[SCDACoordinator(SiriDeviceRoutingStandby) _engageRoutingTargetStandbyForGeneration:]_block_invoke
+ ___IDSLibraryCore_block_invoke
+ ___SCDAElectionLedgerContinuousNanos_block_invoke
+ ___SCDALiveReceivers_block_invoke
+ ____SCDABestRoutingTargetIdsId_block_invoke
+ ____SCDAEmergencyCapableIdsId_block_invoke
+ ____SCDAReleaseLostCallback_block_invoke
+ ____SCDAReleaseWonCallback_block_invoke
+ ___block_descriptor_32_e31_B16?0"SCDAElectionCandidate"8l
+ ___block_descriptor_32_e5_Q8?0l
+ ___block_descriptor_32_e61_q24?0"SCDAElectionLedgerEntry"8"SCDAElectionLedgerEntry"16l
+ ___block_descriptor_33_e31_B16?0"SCDAElectionCandidate"8l
+ ___block_descriptor_40_e8_32bs_e8_v16?0q8ls32l8
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSArray"8lw32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
+ ___block_descriptor_48_e8_32w_e8_v16?0q8lw32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___block_descriptor_56_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_64_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___block_descriptor_73_e8_32s40s48bs56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___getIDSCopyLocalDeviceUniqueIDSymbolLoc_block_invoke
+ ___getWPHeySiriNeedsIdentitySymbolLoc_block_invoke
+ ___getWPHeySiriRPIdentitySymbolLoc_block_invoke
+ ___kCFBooleanTrue
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy16_8
+ __activationKindConflictHandler
+ __deviceSelectionEnabledOverride
+ __electionLedgerEnabledOverride
+ __isATVOverride
+ __isCommunalOverride
+ __liveReceiversLock
+ __missingIdentityHandler
+ __monitorDataSiriDeviceRoutingEnabledOverride
+ __os_log_fault_impl
+ __overrideLock
+ __replacedIdentityHandler
+ __swiftImmortalRefCount
+ _associated conformance So23SCDADeviceRoutingDomainVs12CaseIterable26SiriCrossDeviceArbitration8AllCasessACP_Sl
+ _audit_stringIDS
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _getIDSCopyLocalDeviceUniqueIDSymbolLoc.ptr
+ _getWPHeySiriNeedsIdentity
+ _getWPHeySiriNeedsIdentitySymbolLoc.ptr
+ _getWPHeySiriRPIdentitySymbolLoc.ptr
+ _init.lastMinted
+ _kSCDAHoldQueueKey
+ _kSCDAMonitorQueueKey
+ _mach_continuous_time
+ _objc_opt_self
+ _objc_retain_x7
+ _sharedLedger.onceToken
+ _sharedLedger.sharedLedger
+ _sharedObserver.onceToken
+ _sharedObserver.sharedObserver
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_release
+ _swift_release_x20
+ _swift_release_x8
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic $ss12CaseIterableP
+ _symbolic Say_____G So23SCDADeviceRoutingDomainV
+ _symbolic Sb
+ _symbolic ScCy__________G 26SiriCrossDeviceArbitration22MyriadElectionDecisionV s5NeverO
+ _symbolic So19SCDAElectionOutcomeC
+ _symbolic _____ 26SiriCrossDeviceArbitration22MyriadElectionDecisionV
+ _symbolic _____ So23SCDADeviceRoutingDomainV
+ _type_layout_string 26SiriCrossDeviceArbitration22MyriadElectionDecisionV
- +[SCDAUtilities isWatchBoostRebalanceEnabled]
- +[SCDAUtilities setWatchBoostRebalanceEnabledOverride:]
- -[SCDACoordinator _writeElectionDataToDefaults]
- -[SCDACoordinator injectAdvertisementForTesting:forDevice:]
- -[SCDACoordinator myriadSession:]
- -[SCDACoordinator resetMyriadCoordinator:]
- -[SCDACoordinator startAdvertisingEmergencySignal]
- -[SCDACoordinator startListeningToEmergencySignal]
- -[SCDACoordinator stateAsString:]
- -[SCDACoordinator updateRepliesWith:id:data:]
- -[SCDARecord(InternalDebug) deviceName]
- GCC_except_table1013
- GCC_except_table1034
- GCC_except_table1098
- GCC_except_table1126
- GCC_except_table1129
- GCC_except_table1141
- GCC_except_table1217
- GCC_except_table1218
- GCC_except_table1224
- GCC_except_table241
- GCC_except_table247
- GCC_except_table505
- GCC_except_table61
- GCC_except_table734
- GCC_except_table780
- GCC_except_table849
- GCC_except_table864
- GCC_except_table912
- GCC_except_table915
- GCC_except_table922
- GCC_except_table949
- GCC_except_table993
- _OBJC_IVAR_$_SCDACoordinator._delegate
- _OBJC_IVAR_$_SCDACoordinator._myriadWorkQueue
- _OBJC_IVAR_$_SCDACoordinator._nTimesExtended
- __OBJC_$_CLASS_METHODS_SCDACoordinator
- __OBJC_$_INSTANCE_METHODS_SCDACoordinator
- __OBJC_$_PROP_LIST_SCDACoordinator
- __OBJC_CLASS_PROTOCOLS_$_SCDACoordinator
- ___42-[SCDACoordinator resetMyriadCoordinator:]_block_invoke
- ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
- _getWPHeySiriKeyManufacturerData
```
