## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

```diff

-360.75.1.4.0
-  __TEXT.__text: 0x2548d8
+385.10.1.0.0
+  __TEXT.__text: 0x25db5c
   __TEXT.__delay_helper: 0x304
   __TEXT.__lazy_helpers: 0xfc
-  __TEXT.__objc_methlist: 0x88d0
-  __TEXT.__cstring: 0x38f4b
-  __TEXT.__const: 0x1d08
-  __TEXT.__gcc_except_tab: 0x4eb4
-  __TEXT.__oslogstring: 0x50325
+  __TEXT.__objc_methlist: 0x8c18
+  __TEXT.__cstring: 0x39bc8
+  __TEXT.__const: 0x1d30
+  __TEXT.__gcc_except_tab: 0x5028
+  __TEXT.__oslogstring: 0x52afd
   __TEXT.__dlopen_cstrs: 0x613
-  __TEXT.__unwind_info: 0x5f98
+  __TEXT.__unwind_info: 0x60e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7248
-  __DATA_CONST.__objc_classlist: 0x310
+  __DATA_CONST.__const: 0x73c0
+  __DATA_CONST.__objc_classlist: 0x330
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x54c8
+  __DATA_CONST.__objc_selrefs: 0x5688
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x2e0
+  __DATA_CONST.__objc_superrefs: 0x300
   __DATA_CONST.__objc_arraydata: 0xf8
-  __DATA_CONST.__got: 0xd10
-  __AUTH_CONST.__const: 0x4988
-  __AUTH_CONST.__cfstring: 0x1c080
-  __AUTH_CONST.__objc_const: 0xcf28
+  __DATA_CONST.__got: 0xd38
+  __AUTH_CONST.__const: 0x4a28
+  __AUTH_CONST.__cfstring: 0x1c4c0
+  __AUTH_CONST.__objc_const: 0xd630
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x78

   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1d10
-  __AUTH.__data: 0x5f0
-  __DATA.__objc_ivar: 0xc78
-  __DATA.__data: 0x1410
-  __DATA.__bss: 0x1380
+  __AUTH.__objc_data: 0x18b0
+  __AUTH.__data: 0x630
+  __DATA.__objc_ivar: 0xcf0
+  __DATA.__data: 0x1450
+  __DATA.__bss: 0x13c8
   __DATA.__common: 0x5d0
-  __DATA_DIRTY.__objc_data: 0x190
+  __DATA_DIRTY.__objc_data: 0x730
   __DATA_DIRTY.__bss: 0xce8
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 10089
-  Symbols:   13525
+  Functions: 10252
+  Symbols:   13721
   CStrings:  0
 
Symbols:
+ +[MXRoutingPrewarmingController sharedSystemMusicPrewarmingController]
+ +[MXSessionManager donateMatchRingtoneVolumeDisabledSignal]
+ +[MXSessionManager(Utilities) sendVolumeFollowingToggleSnapshotTelemetry]
+ +[MXSessionResumptionContext canExcludeSessionFromActiveSessionList:forResumingSession:]
+ -[MXAirPlayPredictedRouting sessionHasPebbleInteractionPredictedRoutes:]
+ -[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]
+ -[MXCoreSessionBase getPreferredOutputSampleRatePointer]
+ -[MXCoreSessionBase preferredOutputSampleRate]
+ -[MXCoreSessionBase prefersAggressiveEchoCancellation]
+ -[MXCoreSessionBase setPreferredOutputSampleRate:]
+ -[MXCoreSessionBase setPrefersAggressiveEchoCancellation:]
+ -[MXCoreSessionBase setSampleRateAndBufferSizeForOnDemandVAD]
+ -[MXCustomEndpointCache clearCachedEndpointsForProtocol:]
+ -[MXMDEExtensionRequest .cxx_destruct]
+ -[MXMDEExtensionRequest completeWithReplyError:result:]
+ -[MXMDEExtensionRequest dealloc]
+ -[MXMDEExtensionRequest failUnresponsiveWithError:]
+ -[MXMDEExtensionRequest initWithOperation:instance:timeoutNsec:completion:]
+ -[MXMDEExtensionRequest remoteProxyForConnection:]
+ -[MXMDEExtensionRequest resolveUnresponsive:error:result:]
+ -[MXMDEPendingExtensionRequest completeWithError:result:]
+ -[MXMDEPendingExtensionRequest completeWithError:result:beforeSendingResult:]
+ -[MXMDEPendingExtensionRequest dealloc]
+ -[MXMDEPendingExtensionRequest initWithClientConnection:objectID:resultOpCode:requestID:]
+ -[MXRoutingPrewarmingController cancelPrewarmingIfNotIdle:]
+ -[MXRoutingPrewarmingController dealloc]
+ -[MXRoutingPrewarmingController finishPrewarmBlock]
+ -[MXRoutingPrewarmingController initWithRoutingContextUUID:]
+ -[MXRoutingPrewarmingController predictedRoutesDidChange:forBundleID:]
+ -[MXRoutingPrewarmingController prewarmFinishedWithChannel:predictedRoutes:]
+ -[MXRoutingPrewarmingController prewarmingState]
+ -[MXRoutingPrewarmingController routingContextUUID]
+ -[MXRoutingPrewarmingController sessionDidStartPlaying:shouldMuteSession:]
+ -[MXRoutingPrewarmingController sessionRequiresPrewarming:]
+ -[MXRoutingPrewarmingController setFinishPrewarmBlock:]
+ -[MXRoutingPrewarmingControllerImpl bundleID]
+ -[MXRoutingPrewarmingControllerImpl cancelBlock]
+ -[MXRoutingPrewarmingControllerImpl channel]
+ -[MXRoutingPrewarmingControllerImpl dealloc]
+ -[MXRoutingPrewarmingControllerImpl finishPrewarmBlock]
+ -[MXRoutingPrewarmingControllerImpl prewarmedRouteUUIDs]
+ -[MXRoutingPrewarmingControllerImpl prewarmingState]
+ -[MXRoutingPrewarmingControllerImpl setBundleID:]
+ -[MXRoutingPrewarmingControllerImpl setCancelBlock:]
+ -[MXRoutingPrewarmingControllerImpl setChannel:]
+ -[MXRoutingPrewarmingControllerImpl setFinishPrewarmBlock:]
+ -[MXRoutingPrewarmingControllerImpl setPrewarmedRouteUUIDs:]
+ -[MXRoutingPrewarmingControllerImpl setPrewarmingState:]
+ -[MXSessionManager alarmVolumeChangedOnPersonalRoute]
+ -[MXSessionManager populatePrimaryRouteConfig:routesInfo:systemAudioContextUUID:volumeButtonClientSession:]
+ -[MXSessionManager ringtoneVolumeChangedOnPersonalRoute]
+ -[MXSessionManager setAlarmVolumeChangedOnPersonalRoute:]
+ -[MXSessionManager setRingtoneVolumeChangedOnPersonalRoute:]
+ -[MXSessionManager(Utilities) canSessionsCoexistDueToSharePlay:victim:]
+ -[MXSessionManager(Utilities) updateSampleRateAndBufferSizeForOnDemandVADIfNeeded:]
+ -[MXSystemCastingExtensionInstance noteUnresponsiveExtensionForOperation:error:]
+ -[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]
+ -[MXSystemCastingExtensionManager copyMirroringSystemCastingInstance]
+ -[MXSystemController hasEntitlementForRemoteDeviceControlByConversationApp]
+ -[MXSystemController setHasEntitlementForRemoteDeviceControlByConversationApp:]
+ -[MXSystemMediaCastingController_Client flushPendingHandlersWithError:]
+ -[MXSystemMediaCastingController_Client handleAsyncResult:]
+ -[MXSystemMediaCastingController_Client registerPendingHandler:]
+ -[MXSystemMediaCastingController_Client takePendingHandlerForRequestID:]
+ -[MXVolumeManager(RestingMediaVolume) startRestingMediaVolumeTimer]
+ -[MXVolumeManager(RestingMediaVolume) stopRestingMediaVolumeTimer:]
+ -[MXVolumeManager(RestingMediaVolume) updateMediaVolume:updateHigherThreshold:]
+ GCC_except_table105
+ GCC_except_table109
+ GCC_except_table118
+ GCC_except_table125
+ GCC_except_table138
+ GCC_except_table145
+ GCC_except_table146
+ GCC_except_table725
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table85
+ GCC_except_table90
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotification
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotificationParameter_AudioCategory
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotificationParameter_Enabled
+ _AVSystemController_RemoteDeviceControlIsAllowedDidChangeNotification
+ _AVSystemController_RemoteDeviceControlIsAllowedDidChangeNotificationParameter_Reason
+ _AudioObjectSetPropertyData
+ _CMSMDeviceState_ItsAHomeAccessory
+ _CMSMNotificationUtility_PostMatchRingtoneVolumeToggleDidChange
+ _CMSMVAUtility_IsPersonalAudioDeviceOrCarKitInUse
+ _CMSMVAUtility_SetPrefersAggressiveEchoCancellation
+ _FigCFArrayGetFirstIndexOfValue
+ _FigStarkModeSanitizeVideoFadeDuration
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled.onceToken
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled.sIsAdditiveRoutingSessionFormatEnabled
+ _MX_FeatureFlags_IsBundleIDPredictedRoutingEnabled.isBundleIDPredictedRoutingEnabled
+ _MX_FeatureFlags_IsBundleIDPredictedRoutingEnabled.onceToken
+ _MX_FeatureFlags_IsTopologyPrewarmingEnabled
+ _MX_FeatureFlags_IsTopologyPrewarmingEnabled.isTopologyPrewarming
+ _MX_FeatureFlags_IsTopologyPrewarmingEnabled.onceToken
+ _OBJC_CLASS_$_MXMDEExtensionRequest
+ _OBJC_CLASS_$_MXMDEPendingExtensionRequest
+ _OBJC_CLASS_$_MXRoutingPrewarmingController
+ _OBJC_CLASS_$_MXRoutingPrewarmingControllerImpl
+ _OBJC_IVAR_$_MXAirPlayPredictedRoutesRegistry.mPebbleInteractionInitiatedRoutes
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredOutputSampleRate
+ _OBJC_IVAR_$_MXCoreSessionBase._prefersAggressiveEchoCancellation
+ _OBJC_IVAR_$_MXMDEExtensionRequest._completion
+ _OBJC_IVAR_$_MXMDEExtensionRequest._done
+ _OBJC_IVAR_$_MXMDEExtensionRequest._instance
+ _OBJC_IVAR_$_MXMDEExtensionRequest._lock
+ _OBJC_IVAR_$_MXMDEExtensionRequest._operation
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._clientConnection
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._done
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._lock
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._objectID
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._requestID
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._resultOpCode
+ _OBJC_IVAR_$_MXRoutingPrewarmingController._routingContextUUID
+ _OBJC_IVAR_$_MXRoutingPrewarmingController.mPrewarmingControllerImpl
+ _OBJC_IVAR_$_MXRoutingPrewarmingController.mRoutingContextController
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._bundleID
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._cancelBlock
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._channel
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._finishPrewarmBlock
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._prewarmedRouteUUIDs
+ _OBJC_IVAR_$_MXRoutingPrewarmingControllerImpl._prewarmingState
+ _OBJC_IVAR_$_MXSessionManager._alarmVolumeChangedOnPersonalRoute
+ _OBJC_IVAR_$_MXSessionManager._ringtoneVolumeChangedOnPersonalRoute
+ _OBJC_IVAR_$_MXSystemController._hasEntitlementForRemoteDeviceControlByConversationApp
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.nextRequestID
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingHandlers
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingLock
+ _OBJC_IVAR_$_MXVolumeManager.mRestingVolumeTimer
+ _OBJC_IVAR_$_MXVolumeManager.mTimerDuration
+ _OBJC_METACLASS_$_MXMDEExtensionRequest
+ _OBJC_METACLASS_$_MXMDEPendingExtensionRequest
+ _OBJC_METACLASS_$_MXRoutingPrewarmingController
+ _OBJC_METACLASS_$_MXRoutingPrewarmingControllerImpl
+ _OUTLINED_FUNCTION_162
+ _OUTLINED_FUNCTION_163
+ _OUTLINED_FUNCTION_164
+ _OUTLINED_FUNCTION_165
+ _OUTLINED_FUNCTION_166
+ _PVMGetMappedRouteIdentifier
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeIn
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeOut
+ __OBJC_$_CLASS_METHODS_MXRoutingPrewarmingController
+ __OBJC_$_CLASS_METHODS_MXSessionManager(InterruptionActionMapper|DuckingUtilities|CameraAttributionInformationUtilities|MXSessionManagerContinuityScreenOutputPortUtilities|PickableRoutes|Common|VAUtilities|OnHeadBluetoothAccessoryPortUtilities|Utilities|ActivationUtilities)
+ __OBJC_$_CLASS_METHODS_MXSessionResumptionContext
+ __OBJC_$_INSTANCE_METHODS_MXMDEExtensionRequest
+ __OBJC_$_INSTANCE_METHODS_MXMDEPendingExtensionRequest
+ __OBJC_$_INSTANCE_METHODS_MXRoutingPrewarmingController
+ __OBJC_$_INSTANCE_METHODS_MXRoutingPrewarmingControllerImpl
+ __OBJC_$_INSTANCE_METHODS_MXVolumeManager(Internal|RestingMediaVolume)
+ __OBJC_$_INSTANCE_VARIABLES_MXMDEExtensionRequest
+ __OBJC_$_INSTANCE_VARIABLES_MXMDEPendingExtensionRequest
+ __OBJC_$_INSTANCE_VARIABLES_MXRoutingPrewarmingController
+ __OBJC_$_INSTANCE_VARIABLES_MXRoutingPrewarmingControllerImpl
+ __OBJC_$_INSTANCE_VARIABLES_MXVolumeManager
+ __OBJC_$_PROP_LIST_MXRoutingPrewarmingController
+ __OBJC_$_PROP_LIST_MXRoutingPrewarmingControllerImpl
+ __OBJC_CLASS_RO_$_MXMDEExtensionRequest
+ __OBJC_CLASS_RO_$_MXMDEPendingExtensionRequest
+ __OBJC_CLASS_RO_$_MXRoutingPrewarmingController
+ __OBJC_CLASS_RO_$_MXRoutingPrewarmingControllerImpl
+ __OBJC_METACLASS_RO_$_MXMDEExtensionRequest
+ __OBJC_METACLASS_RO_$_MXMDEPendingExtensionRequest
+ __OBJC_METACLASS_RO_$_MXRoutingPrewarmingController
+ __OBJC_METACLASS_RO_$_MXRoutingPrewarmingControllerImpl
+ ___112-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]_block_invoke_2
+ ___50-[MXMDEExtensionRequest remoteProxyForConnection:]_block_invoke
+ ___59-[MXRoutingPrewarmingController cancelPrewarmingIfNotIdle:]_block_invoke
+ ___67-[MXVolumeManager(RestingMediaVolume) startRestingMediaVolumeTimer]_block_invoke
+ ___67-[MXVolumeManager(RestingMediaVolume) stopRestingMediaVolumeTimer:]_block_invoke
+ ___70+[MXRoutingPrewarmingController sharedSystemMusicPrewarmingController]_block_invoke
+ ___70-[MXRoutingPrewarmingController predictedRoutesDidChange:forBundleID:]_block_invoke
+ ___70-[MXRoutingPrewarmingController predictedRoutesDidChange:forBundleID:]_block_invoke_2
+ ___75-[MXMDEExtensionRequest initWithOperation:instance:timeoutNsec:completion:]_block_invoke
+ ___82-[MXSystemMediaCastingController_Client mediaSourceDataForKeys:completionHandler:]_block_invoke
+ ___84-[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]_block_invoke
+ ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke
+ ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_2
+ ___89-[MXSystemMediaCastingController_Client sendData:forApplicationID:withCompletionHandler:]_block_invoke
+ ___92-[MXSystemMediaCastingController_Client sendApplicationLaunchMessage:withCompletionHandler:]_block_invoke
+ ___CMSMVAUtility_CreateMusicVADIfNeeded_block_invoke
+ ___MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled_block_invoke
+ ___MX_FeatureFlags_IsBundleIDPredictedRoutingEnabled_block_invoke
+ ___MX_FeatureFlags_IsTopologyPrewarmingEnabled_block_invoke
+ ___PVMSetCurrentState_block_invoke
+ ___block_descriptor_137_e8_32b_e5_v8?0ls32l8
+ ___block_descriptor_194_e5_v8?0l
+ ___block_descriptor_40_e8_32b_e34_v24?0"NSError"8"NSDictionary"16ls32l8
+ ___block_descriptor_40_e8_32o_e20_v24?0"NSError"816ls32l8
+ ___block_descriptor_40_e8_32o_e22_v16?0"NSDictionary"8ls32l8
+ ___block_descriptor_40_e8_32o_e34_v24?0"NSError"8"NSDictionary"16ls32l8
+ ___block_descriptor_40_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_44_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_48_e8_32o40b_e34_v24?0"NSError"8"NSDictionary"16ls40l8s32l8
+ ___block_descriptor_48_e8_32o40o_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_48_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_56_e8_32o40o48w_e36_v16?0"MXRoutingPrewarmingChannel"8ls32l8w48l8s40l8
+ ___block_descriptor_56_e8_32o40o48w_e5_v8?0ls32l8s40l8w48l8
+ ___block_descriptor_81_e8_32r_e5_v8?0lr32l8
+ ___fsm_beginVideoCrossfadeForScreenTransition_block_invoke
+ ___getBMDiscoverabilitySignalsClass_block_invoke
+ _cmsmGetMaxVoiceOverVolumeOnVADUID
+ _cmsmShouldJBLSystemSoundSetMediaVolumeOnSiriOutputVAD
+ _dispatch_suspend
+ _fsm_postCarPlayShellFadeNotification
+ _fsm_postStateChangedOnAllHandlers
+ _getBMDiscoverabilitySignalsClass.softClass
+ _getRestingMediaVolumeReasonAsString
+ _kFigEndpointDescriptorKey_AudioRouteSubType_HomeAccessory
+ _kMXDiscoverabilitySignal_MatchRingtoneVolumeDisabledContentIdentifier
+ _kMXSessionAudioCategory_HomeDeviceCriticalAlert
+ _kMXSessionProperty_PrefersAggressiveEchoCancellation
+ _kMXSystemControllerNotificationKey_MatchRingtoneVolumeToggleDidChange_AudioCategory
+ _kMXSystemControllerNotificationKey_MatchRingtoneVolumeToggleDidChange_Enabled
+ _kMXSystemControllerNotificationKey_RemoteDeviceControlIsAllowedDidChange_Reason
+ _kMXSystemControllerNotification_MatchRingtoneVolumeToggleDidChange
+ _kMXSystemControllerNotification_RemoteDeviceControlIsAllowedDidChange
+ _kMXSystemMediaCastingControllerMsgParam_RequestID
+ _kMXSystemMediaCastingControllerReplyParam_ErrorCode
+ _kMXSystemMediaCastingControllerReplyParam_Result
+ _mxsmccs_CopyActiveClient
+ _sharedSystemMusicPrewarmingController.onceToken
+ _sharedSystemMusicPrewarmingController.sharedController
+ _xpc_retain
- +[MXSessionManager sendTelemetryForMatchRingtoneVolumeToggleChange]
- -[MXCoreSession getPreferredOutputSampleRatePointer]
- -[MXCoreSession preferredOutputSampleRate]
- -[MXCoreSession setPreferredOutputSampleRate:]
- GCC_except_table115
- GCC_except_table120
- GCC_except_table126
- GCC_except_table128
- GCC_except_table137
- GCC_except_table143
- GCC_except_table144
- GCC_except_table239
- GCC_except_table62
- GCC_except_table64
- GCC_except_table720
- GCC_except_table76
- _CMSystemSoundMgrGetMaxVoiceOverVolumeOnSystemLocalVAD
- _FigRoutingContextUtilities_CopyPredictedEndpoints
- _OBJC_IVAR_$_MXCoreSession._preferredOutputSampleRate
- __OBJC_$_CLASS_METHODS_MXSessionManager
- __OBJC_$_INSTANCE_METHODS_MXVolumeManager(Internal)
- ___FigRoutingContextUtilities_CopyPredictedEndpoints_block_invoke
- ___block_descriptor_129_e8_32b_e5_v8?0ls32l8
- ___block_descriptor_40_e8_32b_e20_v24?0"NSError"816ls32l8
- ___block_descriptor_40_e8_32b_e22_v16?0"NSDictionary"8ls32l8
- ___block_descriptor_48_e8_32o40b_e22_v16?0"NSDictionary"8ls40l8s32l8
- ___block_descriptor_48_e8_32o40o_e20_v24?0"NSError"816ls32l8s40l8
- ___block_descriptor_48_e8_32o40r_e22_v16?0"NSDictionary"8lr40l8s32l8
- ___block_descriptor_56_e8_32o40o48r_e22_v16?0"NSDictionary"8lr48l8s32l8s40l8
- ___block_descriptor_57_e8_32r_e5_v8?0lr32l8
- _customEndpoint_getFeaturesFromModelID.audioAndScreenModelIDs
- _vaemConvertToScalarInVAD
```
