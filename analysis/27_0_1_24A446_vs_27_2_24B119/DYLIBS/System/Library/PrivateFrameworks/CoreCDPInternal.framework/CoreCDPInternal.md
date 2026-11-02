## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

```diff

-447.0.0.0.0
-  __TEXT.__text: 0x8dda4
-  __TEXT.__objc_methlist: 0x568c
+448.125.10.0.0
+  __TEXT.__text: 0x907e0
+  __TEXT.__objc_methlist: 0x5804
   __TEXT.__const: 0x888
-  __TEXT.__oslogstring: 0x14a9e
-  __TEXT.__cstring: 0xe0c5
-  __TEXT.__gcc_except_tab: 0xb68
+  __TEXT.__oslogstring: 0x1510e
+  __TEXT.__cstring: 0xe6b5
+  __TEXT.__gcc_except_tab: 0xb94
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__swift5_typeref: 0x3b7
   __TEXT.__swift5_fieldmd: 0x80

   __TEXT.__swift_as_entry: 0x60
   __TEXT.__swift_as_ret: 0x58
   __TEXT.__swift_as_cont: 0x68
-  __TEXT.__unwind_info: 0x1e10
-  __TEXT.__eh_frame: 0x8f0
+  __TEXT.__unwind_info: 0x1ed0
+  __TEXT.__eh_frame: 0x918
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x25c8
-  __DATA_CONST.__objc_classlist: 0x298
+  __DATA_CONST.__const: 0x26d8
+  __DATA_CONST.__objc_classlist: 0x2a0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x188
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3908
+  __DATA_CONST.__objc_selrefs: 0x3a18
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x160
   __DATA_CONST.__objc_arraydata: 0x220
-  __DATA_CONST.__got: 0x10f0
-  __AUTH_CONST.__const: 0xad0
-  __AUTH_CONST.__cfstring: 0x9520
-  __AUTH_CONST.__objc_const: 0x100b0
+  __DATA_CONST.__got: 0x1148
+  __AUTH_CONST.__const: 0xb10
+  __AUTH_CONST.__cfstring: 0x9960
+  __AUTH_CONST.__objc_const: 0x10260
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x960
+  __AUTH_CONST.__auth_got: 0x968
   __AUTH_CONST.__auth_ptr: 0x1c8
-  __AUTH.__objc_data: 0x120
-  __DATA.__objc_ivar: 0x3b0
+  __AUTH.__objc_data: 0x170
+  __DATA.__objc_ivar: 0x3d0
   __DATA.__data: 0x1220
   __DATA.__bss: 0x490
   __DATA_DIRTY.__objc_data: 0x19b0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
+  - /usr/lib/swift/libswiftAVFoundation.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib
   - /usr/lib/swift/libswiftCompression.dylib
   - /usr/lib/swift/libswiftCore.dylib

   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftCoreImage.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftCoreMIDI.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftIntents.dylib
   - /usr/lib/swift/libswiftMetal.dylib
   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3159
-  Symbols:   4153
+  Functions: 3220
+  Symbols:   4235
   CStrings:  0
 
Symbols:
+ +[CDPDPCSController _flagsForValidateTelemetry:]
+ +[CDPDPCSController passwordVersionsWereComparedForValidateTelemetry:]
+ +[CDPDPCSController primaryAttemptsRemainingForValidateTelemetry:]
+ +[CDPDPCSController recordGenerationIsAheadOfAccountForValidateTelemetry:]
+ +[CDPDPCSController wrappingKeyNeededRepairForValidateTelemetry:]
+ +[CDPDPCSController wrappingKeyWasRebuiltForValidateTelemetry:]
+ +[CDPDXPCListener _isAppleBinaryOrInternalBuildWithCodeSignFlags:isInternalBuild:]
+ -[CDPContext(Daemon) hasConfirmedPDPIneligibility]
+ -[CDPDAsyncSecureBackupEnableTracker .cxx_destruct]
+ -[CDPDAsyncSecureBackupEnableTracker _recordOutcomeWithReason:]
+ -[CDPDAsyncSecureBackupEnableTracker _timeOutCurrentWaiter]
+ -[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]
+ -[CDPDAsyncSecureBackupEnableTracker enableStarted]
+ -[CDPDAsyncSecureBackupEnableTracker recordDidEnable:error:]
+ -[CDPDAsyncSecureBackupEnableTracker recordEnableStarted]
+ -[CDPDPCSController _sendGeneratePDPBlob:completion:]
+ -[CDPDPCSController _sendSetupPDPIdentities:completion:]
+ -[CDPDPDPRecoveryController retirePDPFollowUpIfAccountConfirmedIneligible]
+ -[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]
+ -[CDPDStateMachine _attemptLegacyIntermissionFallbackWithCompletion:]
+ -[CDPDStateMachine _attemptNativeIntermissionSalvageAfterSetupError:completion:]
+ -[CDPDStateMachine _attemptPreOctagonPDPSetupWithCompletion:continuation:]
+ -[CDPDStateMachine _finishSignInWithSecretTeardownShouldComplete:cloudDataProtectionEnabled:error:completion:]
+ -[CDPDStateMachine _makeDeferredSOSStateMachineWithContext:]
+ -[CDPDStateMachine _markRepairPairReported]
+ -[CDPDStateMachine _sendDBRDetectionEventsWithDetails:healthState:]
+ -[CDPDStateMachine _sendDBRRepairEntryEventWithDetails:validationError:includeRepairContext:]
+ -[CDPDStateMachine initWithContext:uiProvider:asyncSecureBackupEnableTracker:]
+ -[CDPDXPCListener _isAppleBinaryOrInternalBuildConnection:]
+ GCC_except_table29
+ GCC_except_table32
+ GCC_except_table48
+ GCC_except_table50
+ GCC_except_table52
+ GCC_except_table54
+ _CDPDAsyncSecureBackupEnableTrackerErrorDomain
+ _OBJC_CLASS_$_CDPDAsyncSecureBackupEnableTracker
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._didRecordOutcome
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._enableStarted
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._lock
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._outcomeReason
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._waiter
+ _OBJC_IVAR_$_CDPDStateMachine._asyncSecureBackupEnableTracker
+ _OBJC_IVAR_$_CDPDStateMachine._pdpDetectionEventsAlreadySent
+ _OBJC_IVAR_$_CDPDStateMachine._pdpRepairPairAlreadySent
+ _OBJC_METACLASS_$_CDPDAsyncSecureBackupEnableTracker
+ _SecTaskGetCodeSignStatus
+ __OBJC_$_CLASS_METHODS_CDPDPCSController
+ __OBJC_$_INSTANCE_METHODS_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_INSTANCE_VARIABLES_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_PROP_LIST_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_CLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_METACLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ ___110-[CDPDStateMachine _finishSignInWithSecretTeardownShouldComplete:cloudDataProtectionEnabled:error:completion:]_block_invoke
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke_2
+ ___54-[CDPDStateMachine _attemptPDPFallbackWithCompletion:]_block_invoke_2
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_2
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_3
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_4
+ ___57-[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]_block_invoke
+ ___69-[CDPDStateMachine _attemptLegacyIntermissionFallbackWithCompletion:]_block_invoke
+ ___74-[CDPDStateMachine _attemptPreOctagonPDPSetupWithCompletion:continuation:]_block_invoke
+ ___79-[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]_block_invoke
+ ___80-[CDPDStateMachine _attemptNativeIntermissionSalvageAfterSetupError:completion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e20_v24?0q8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32bs40r_e30_v24?0"NSNumber"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e37_v32?0Q8"NSDictionary"16"NSError"24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48w_e35_v16?0?<v?"NSNumber""NSError">8lw48l8s32l8r40l8
+ ___block_descriptor_56_e8_32s40s48r_e33_v16?0?<v?"NSData""NSError">8ls32l8s40l8r48l8
+ ___block_descriptor_57_e8_32s40s48bs_e20_v20?0"NSError"8B16ls48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56bs_e20_v20?0"NSError"8B16ls32l8s40l8s48l8s56l8
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_CoreCDPInternal
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_CoreCDPInternal
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_CoreCDPInternal
+ _kAAAnalyticsEventCustodianHealthCheckOwnerCleanupOrphanedCustodian
+ _kCDPAnalyticsPDPRecordGenerationAheadEvent
+ _kCDPAnalyticsPDPRecordGenerationCheckSkippedEvent
+ _kCDPAnalyticsPDPWrappingKeyRepairEvent
+ _kDataAccessRecoveryContactSuggestionFamily
+ _kDataAccessRecoveryContactSuggestionMegadome
+ _kPCSDBRTelemetryFlags
+ _kPCSDBRTelemetryLocalPasswordVersion
+ _kPCSDBRTelemetryPrimaryAttemptsRemaining
+ _kPCSDBRTelemetryRecordPasswordVersion
- GCC_except_table30
- GCC_except_table38
- GCC_except_table40
- GCC_except_table47
- ___70-[CDPDClientHandler setUserVisibleKeychainSyncEnabled:withCompletion:]_block_invoke_2
- ___77-[CDPDClientHandler removeNonViewAwarePeersFromCircleWithContext:completion:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16ls32l8
- ___block_descriptor_48_e8_32s40bs_e37_v32?0Q8"NSDictionary"16"NSError"24ls40l8s32l8
- ___block_descriptor_56_e8_32s40s48bs_e20_v20?0"NSError"8B16ls32l8s40l8s48l8
```
