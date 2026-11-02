## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

```diff

-3600.55.37.11.4
-  __TEXT.__text: 0x74408
-  __TEXT.__objc_methlist: 0x6fa4
-  __TEXT.__const: 0x11dc
-  __TEXT.__cstring: 0xcc42
-  __TEXT.__oslogstring: 0x934c
-  __TEXT.__gcc_except_tab: 0xc8c
+3605.31.1.11.2
+  __TEXT.__text: 0x77668
+  __TEXT.__objc_methlist: 0x73f4
+  __TEXT.__const: 0x124c
+  __TEXT.__cstring: 0xd2a2
+  __TEXT.__oslogstring: 0x9bc3
+  __TEXT.__gcc_except_tab: 0xd00
   __TEXT.__dlopen_cstrs: 0x1bc
   __TEXT.__swift5_typeref: 0x77a
   __TEXT.__constg_swiftt: 0x42c

   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x14
   __TEXT.__swift_as_cont: 0x8c
-  __TEXT.__unwind_info: 0x1ea8
+  __TEXT.__unwind_info: 0x1f70
   __TEXT.__eh_frame: 0xf58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1808
-  __DATA_CONST.__objc_classlist: 0x390
+  __DATA_CONST.__const: 0x1918
+  __DATA_CONST.__objc_classlist: 0x3a8
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x1d8
+  __DATA_CONST.__objc_protolist: 0x1e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3528
+  __DATA_CONST.__objc_selrefs: 0x36a0
   __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0x2c8
+  __DATA_CONST.__objc_superrefs: 0x2e8
   __DATA_CONST.__objc_arraydata: 0x510
-  __DATA_CONST.__got: 0xa80
+  __DATA_CONST.__got: 0xaa8
   __AUTH_CONST.__const: 0x14b0
-  __AUTH_CONST.__cfstring: 0x5000
-  __AUTH_CONST.__objc_const: 0xb188
+  __AUTH_CONST.__cfstring: 0x51c0
+  __AUTH_CONST.__objc_const: 0xb7c0
   __AUTH_CONST.__objc_intobj: 0x978
   __AUTH_CONST.__objc_dictobj: 0x118
-  __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0xbd8
+  __AUTH_CONST.__auth_got: 0xbf8
   __AUTH_CONST.__auth_ptr: 0x1a0
-  __AUTH.__objc_data: 0x20a0
+  __AUTH.__objc_data: 0x2190
   __AUTH.__data: 0x118
-  __DATA.__objc_ivar: 0x720
-  __DATA.__data: 0x16a0
-  __DATA.__bss: 0x648
+  __DATA.__objc_ivar: 0x770
+  __DATA.__data: 0x1710
+  __DATA.__bss: 0x658
   __DATA.__common: 0x270
   __DATA_DIRTY.__objc_data: 0x5f0
   __DATA_DIRTY.__bss: 0x10

   - /System/Library/PrivateFrameworks/IAP.framework/IAP
   - /System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience
   - /System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth
+  - /System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit
   - /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog
   - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
   - /System/Library/PrivateFrameworks/SAObjects.framework/SAObjects

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2906
-  Symbols:   4644
+  Functions: 3011
+  Symbols:   4796
   CStrings:  0
 
Symbols:
+ +[SASActivationDecision shouldContinueActivationForCondition:errorNotification:activationDeclinedHandler:]
+ +[SASDeviceSelectionController _resetSignalObserverSetupForTesting]
+ +[SASDeviceSelectionController setupSignalObservers]
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isCampoEnabled]
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isCrossSessionContinuityEnabled]
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isDashboardCampoEnabled]
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isLinwoodEnabled]
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isThirdPartyAppModelsEnabled]
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isContinuousConversationHomepodEnabled]
+ -[SASActivationCondition setUserNotificationPresenter:]
+ -[SASActivationCondition userNotificationPresenter]
+ -[SASActivationRequest isAutoPromptRequest]
+ -[SASDeviceSelectionController .cxx_destruct]
+ -[SASDeviceSelectionController _selectDeviceWithSignals:completion:]
+ -[SASDeviceSelectionController _triggerSignalForActivationRequest:isSiriDisplayed:isSiriSpeaking:]
+ -[SASDeviceSelectionController _triggerTypeForActivationRequest:]
+ -[SASDeviceSelectionController activateForInTaskRequest:isVisible:]
+ -[SASDeviceSelectionController activateForRequest:visible:]
+ -[SASDeviceSelectionController activateForRequest:withTimeout:visible:]
+ -[SASDeviceSelectionController activateForRequest:withTimeout:visible:idleAndQuiet:]
+ -[SASDeviceSelectionController canceledByMyriad]
+ -[SASDeviceSelectionController initWithDelegate:]
+ -[SASHeater _replacePreheatBlock:]
+ -[SASHeater _scheduleBlockAfterTimeInterval:]
+ -[SASHeater init]
+ -[SASHeater preheatQueue]
+ -[SASHeater prepareForUseAfterTimeInterval:buttonDownTimestamp:]
+ -[SASHeater setPreheatQueue:]
+ -[SASMyriadController _goodnessScoreContextWithTimerFiring:alarmFiring:]
+ -[SASMyriadController _primeMTAlarmManagerState]
+ -[SASMyriadController _primeMTTimerManagerState]
+ -[SASMyriadController _runOnMyriadWorkQueueWithSelf:]
+ -[SASMyriadController activateForRequest:withTimeout:visible:idleAndQuiet:]
+ -[SASMyriadWatchController activateForRequest:withTimeout:visible:idleAndQuiet:]
+ -[SASPresentationManager _presentationsLock_cancelPrewarmCancellationTimer]
+ -[SASPresentationManager _presentationsLock_startPrewarmCancellationTimer]
+ -[SASPresentationManager prewarmCancellationBlock]
+ -[SASPresentationManager setPrewarmCancellationBlock:]
+ -[SASPresentationManager unregisterSiriPresentation:withIdentifier:]
+ -[SASRequestOptions isOdeonProxyVoiceTrigger]
+ -[SASRequestOptions setIsOdeonProxyVoiceTrigger:]
+ -[SASRequestOptions setTriggerDuration:]
+ -[SASRequestOptions setTriggeredPhrase:]
+ -[SASRequestOptions setTwoShotFeedbackDelay:]
+ -[SASRequestOptions triggerDuration]
+ -[SASRequestOptions triggeredPhrase]
+ -[SASRequestOptions twoShotFeedbackDelay]
+ -[SASSignalServer prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]
+ -[SASSignalServer registerActivationOutcomeListenerWithIdentifier:]
+ -[SASSignalServer unregisterActivationOutcomeListenerWithIdentifier:]
+ -[SASSystemState _demoModeIsSupported]
+ -[SASSystemState _inNanoPressDemoMode]
+ -[SASSystemState _inSecureDemoModeWithError:]
+ -[SASSystemState _inStoreDemoMode]
+ -[SASSystemState _shouldShowDemoSiriAI]
+ -[SASSystemState isInDemoMode]
+ -[SiriActivationOutcomeListener .cxx_destruct]
+ -[SiriActivationOutcomeListener activationSourceDidReceiveDeclinedActivation]
+ -[SiriActivationOutcomeListener dealloc]
+ -[SiriActivationOutcomeListener delegate]
+ -[SiriActivationOutcomeListener dispatchDelegateCallbacksOnMainQueue]
+ -[SiriActivationOutcomeListener initWithDelegate:dispatchCallbacksOnMainQueue:]
+ -[SiriActivationOutcomeListener invalidate]
+ -[SiriActivationOutcomeListener setDelegate:]
+ -[SiriActivationOutcomeListener setDispatchDelegateCallbacksOnMainQueue:]
+ -[SiriActivationOutcomeListener setSource:]
+ -[SiriActivationOutcomeListener source]
+ -[SiriActivationService _notifyListenersOfDeclinedActivation]
+ -[SiriActivationService activationOutcomeListeners]
+ -[SiriActivationService prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]
+ -[SiriActivationService registerActivationOutcomeListenerServer:identifier:]
+ -[SiriActivationService setActivationOutcomeListeners:]
+ -[SiriActivationService unregisterActivationOutcomeListenerWithIdentifier:]
+ -[SiriActivationService unregisterSiriPresentation:withIdentifier:]
+ -[SiriActivationSource siriActivationDeclined]
+ -[SiriSimpleActivationSource .cxx_destruct]
+ -[SiriSimpleActivationSource initAsOutcomeReceiverWithDelegate:]
+ -[SiriSimpleActivationSource siriActivationDeclined]
+ -[SiriTVActivationSource _clearOdeonProxyVoiceTriggerState]
+ -[SiriTVActivationSource didRecognizeButtonSinglePressUp]
+ -[SiriTVActivationSource didRecognizeLongPressInteraction:]
+ -[SiriTVActivationSource setIsOdeonProxyVoiceTrigger:]
+ -[SiriTVActivationSource setTriggerDuration:]
+ -[SiriTVActivationSource setTriggeredPhrase:]
+ -[SiriTVActivationSource setTwoShotFeedbackDelay:]
+ -[SiriTVLongPressButtonContext SAFLongPressButtonContext]
+ -[SiriTVLongPressButtonContext isOdeonProxyVoiceTrigger]
+ -[SiriTVLongPressButtonContext setIsOdeonProxyVoiceTrigger:]
+ -[SiriTVLongPressButtonContext setTriggerDuration:]
+ -[SiriTVLongPressButtonContext setTriggeredPhrase:]
+ -[SiriTVLongPressButtonContext setTwoShotFeedbackDelay:]
+ -[SiriTVLongPressButtonContext triggerDuration]
+ -[SiriTVLongPressButtonContext triggeredPhrase]
+ -[SiriTVLongPressButtonContext twoShotFeedbackDelay]
+ GCC_except_table10
+ GCC_except_table111
+ GCC_except_table112
+ GCC_except_table16
+ GCC_except_table163
+ GCC_except_table33
+ GCC_except_table38
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table48
+ GCC_except_table49
+ GCC_except_table56
+ GCC_except_table71
+ GCC_except_table82
+ GCC_except_table84
+ _AFIsATVOnly
+ _CFPreferencesGetAppBooleanValue
+ _NSStringFromAFSiriUnavailabilityReasons
+ _OBJC_CLASS_$_DeviceSelectionSiriSessionSignal
+ _OBJC_CLASS_$_DeviceSelectionTriggerSignal
+ _OBJC_CLASS_$_MSDKDemoState
+ _OBJC_CLASS_$_SAFTVLongPressButtonContext
+ _OBJC_CLASS_$_SASDeviceSelectionController
+ _OBJC_CLASS_$_SRUIFIntelligenceFlowFeatureFlag
+ _OBJC_CLASS_$_SiriActivationOutcomeListener
+ _OBJC_IVAR_$_SASActivationCondition._userNotificationPresenter
+ _OBJC_IVAR_$_SASDeviceSelectionController._canceledByMyriad
+ _OBJC_IVAR_$_SASDeviceSelectionController._delegate
+ _OBJC_IVAR_$_SASHeater._lock
+ _OBJC_IVAR_$_SASHeater._preheatBlock
+ _OBJC_IVAR_$_SASHeater._preheatQueue
+ _OBJC_IVAR_$_SASPresentationManager._prewarmCancellationBlock
+ _OBJC_IVAR_$_SASRequestOptions._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SASRequestOptions._triggerDuration
+ _OBJC_IVAR_$_SASRequestOptions._triggeredPhrase
+ _OBJC_IVAR_$_SASRequestOptions._twoShotFeedbackDelay
+ _OBJC_IVAR_$_SiriActivationOutcomeListener._delegate
+ _OBJC_IVAR_$_SiriActivationOutcomeListener._dispatchDelegateCallbacksOnMainQueue
+ _OBJC_IVAR_$_SiriActivationOutcomeListener._source
+ _OBJC_IVAR_$_SiriActivationService._activationOutcomeListeners
+ _OBJC_IVAR_$_SiriSimpleActivationSource._isOutcomeReceiver
+ _OBJC_IVAR_$_SiriSimpleActivationSource._outcomeDelegate
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._isOdeonProxyVoiceTrigger
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._triggerDuration
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._triggeredPhrase
+ _OBJC_IVAR_$_SiriTVLongPressButtonContext._twoShotFeedbackDelay
+ _OBJC_METACLASS_$_SASDeviceSelectionController
+ _OBJC_METACLASS_$_SRUIFIntelligenceFlowFeatureFlag
+ _OBJC_METACLASS_$_SiriActivationOutcomeListener
+ _SAFTVRemoteTypeFromSiriTVRemoteType
+ _SASDeviceSelectionSignalObserverLock
+ _SASDeviceSelectionSignalObserversAreSetUp
+ __OBJC_$_CLASS_METHODS_SASDeviceSelectionController
+ __OBJC_$_CLASS_METHODS_SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags)
+ __OBJC_$_INSTANCE_METHODS_SASDeviceSelectionController
+ __OBJC_$_INSTANCE_METHODS_SiriActivationOutcomeListener
+ __OBJC_$_INSTANCE_VARIABLES_SASDeviceSelectionController
+ __OBJC_$_INSTANCE_VARIABLES_SiriActivationOutcomeListener
+ __OBJC_$_INSTANCE_VARIABLES_SiriSimpleActivationSource
+ __OBJC_$_PROP_LIST_SASDeviceSelectionController
+ __OBJC_$_PROP_LIST_SiriActivationOutcomeListener
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SiriSimpleActivationSourceOutcomeDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SiriSimpleActivationSourceOutcomeDelegate
+ __OBJC_$_PROTOCOL_REFS_SiriSimpleActivationSourceOutcomeDelegate
+ __OBJC_CLASS_PROTOCOLS_$_SASDeviceSelectionController
+ __OBJC_CLASS_PROTOCOLS_$_SiriActivationOutcomeListener
+ __OBJC_CLASS_RO_$_SASDeviceSelectionController
+ __OBJC_CLASS_RO_$_SRUIFIntelligenceFlowFeatureFlag
+ __OBJC_CLASS_RO_$_SiriActivationOutcomeListener
+ __OBJC_LABEL_PROTOCOL_$_SiriSimpleActivationSourceOutcomeDelegate
+ __OBJC_METACLASS_RO_$_SASDeviceSelectionController
+ __OBJC_METACLASS_RO_$_SRUIFIntelligenceFlowFeatureFlag
+ __OBJC_METACLASS_RO_$_SiriActivationOutcomeListener
+ __OBJC_PROTOCOL_$_SiriSimpleActivationSourceOutcomeDelegate
+ ___106+[SASActivationDecision shouldContinueActivationForCondition:errorNotification:activationDeclinedHandler:]_block_invoke
+ ___45-[SASHeater _scheduleBlockAfterTimeInterval:]_block_invoke
+ ___45-[SASHeater _scheduleBlockAfterTimeInterval:]_block_invoke_2
+ ___47+[SASPresentationServer _unregisterConnection:]_block_invoke
+ ___48-[SASMyriadController _primeMTAlarmManagerState]_block_invoke
+ ___48-[SASMyriadController _primeMTAlarmManagerState]_block_invoke_2
+ ___48-[SASMyriadController _primeMTTimerManagerState]_block_invoke
+ ___48-[SASMyriadController _primeMTTimerManagerState]_block_invoke_2
+ ___52+[SASDeviceSelectionController setupSignalObservers]_block_invoke
+ ___53-[SASMyriadController _runOnMyriadWorkQueueWithSelf:]_block_invoke
+ ___61-[SiriActivationService _notifyListenersOfDeclinedActivation]_block_invoke
+ ___61-[SiriActivationService handleActivationRequest:systemState:]_block_invoke_2
+ ___75-[SASMyriadController activateForRequest:withTimeout:visible:idleAndQuiet:]_block_invoke
+ ___77-[SiriActivationOutcomeListener activationSourceDidReceiveDeclinedActivation]_block_invoke
+ ___84-[SASDeviceSelectionController activateForRequest:withTimeout:visible:idleAndQuiet:]_block_invoke
+ ___84-[SASDeviceSelectionController activateForRequest:withTimeout:visible:idleAndQuiet:]_block_invoke_2
+ ___block_descriptor_32_e42_v32?0"NSString"8"SASSignalServer"16^B24l
+ ___block_descriptor_40_e8_32s_e29_v16?0"SASMyriadController"8ls32l8
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSArray"8lw32l8
+ ___block_descriptor_40_e8_32w_e43_v24?0"DeviceSelectionDevice"8"NSError"16lw32l8
+ ___block_descriptor_41_e8_32s_e29_v16?0"BSServiceConnection"8ls32l8
+ ___block_descriptor_41_e8_32w_e42_v16?0"<BSServiceConnectionConfiguring>"8lw32l8
+ ___block_descriptor_49_e8_32s40w_e29_v16?0"BSServiceConnection"8lw40l8s32l8
+ _activationOutcomeListenerLock
+ _dispatch_block_cancel
+ _shouldContinueActivationForCondition:errorNotification:activationDeclinedHandler:.log
+ _shouldContinueActivationForCondition:errorNotification:activationDeclinedHandler:.once
- +[SASActivationDecision shouldContinueActivationForCondition:errorNotification:]
- -[SASHeater preheatTimer]
- -[SASHeater setPreheatTimer:]
- -[SASMyriadController activateForRequest:withTimeout:visible:quiet:]
- -[SASMyriadWatchController activateForRequest:withTimeout:visible:quiet:]
- -[SASPresentationManager unregisterSiriPresentationWithIdentifier:]
- -[SiriActivationService _performDeviceSelectionWithActivation:withSystemState:withOptions:]
- -[SiriActivationService _performLegacyDeviceSelectionActivation:withSystemState:presentationIdentifier:]
- -[SiriActivationService _sendActivationTriggerToDeviceSelection:withSystemState:]
- -[SiriActivationService _setupDeviceSelectionSignalObservers]
- -[SiriActivationService unregisterSiriPresentationIdentifier:]
- GCC_except_table100
- GCC_except_table105
- GCC_except_table15
- GCC_except_table164
- GCC_except_table26
- GCC_except_table31
- GCC_except_table34
- GCC_except_table37
- GCC_except_table39
- GCC_except_table40
- GCC_except_table47
- GCC_except_table67
- GCC_except_table76
- GCC_except_table79
- _OBJC_CLASS_$_DeviceSelectionContext
- _OBJC_CLASS_$_DeviceSelectionTriggerSource
- _OBJC_CLASS_$_NSConstantDoubleNumber
- _OBJC_IVAR_$_SASHeater._preheatTimer
- ___31-[SASHeater _cancelPreparation]_block_invoke
- ___32-[SASRemoteRequestManager _init]_block_invoke_6
- ___32-[SASRemoteRequestManager _init]_block_invoke_7
- ___32-[SASRemoteRequestManager _init]_block_invoke_8
- ___32-[SASRemoteRequestManager _init]_block_invoke_9
- ___44-[SASHeater prepareForUseAfterTimeInterval:]_block_invoke
- ___61-[SiriActivationService _setupDeviceSelectionSignalObservers]_block_invoke
- ___68-[SASMyriadController activateForRequest:withTimeout:visible:quiet:]_block_invoke
- ___80+[SASActivationDecision shouldContinueActivationForCondition:errorNotification:]_block_invoke
- ___81-[SiriActivationService _sendActivationTriggerToDeviceSelection:withSystemState:]_block_invoke
- ___91-[SiriActivationService _performDeviceSelectionWithActivation:withSystemState:withOptions:]_block_invoke
- ___block_descriptor_40_e8_32s_e43_v24?0"DeviceSelectionDevice"8"NSError"16ls32l8
- _shouldContinueActivationForCondition:errorNotification:.log
- _shouldContinueActivationForCondition:errorNotification:.once
```
