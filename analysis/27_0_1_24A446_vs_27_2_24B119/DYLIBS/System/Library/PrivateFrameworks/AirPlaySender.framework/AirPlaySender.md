## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

```diff

-980.77.1.2.0
-  __TEXT.__text: 0x244090
-  __TEXT.__objc_methlist: 0x7ec
-  __TEXT.__cstring: 0x8ec83
-  __TEXT.__const: 0x61f0
-  __TEXT.__gcc_except_tab: 0xa88
-  __TEXT.__dlopen_cstrs: 0x5c1
+1005.13.1.1.0
+  __TEXT.__text: 0x248854
+  __TEXT.__objc_methlist: 0x81c
+  __TEXT.__cstring: 0x901f4
+  __TEXT.__const: 0x6190
+  __TEXT.__gcc_except_tab: 0xaf4
+  __TEXT.__dlopen_cstrs: 0x61a
   __TEXT.__oslogstring: 0x1009
-  __TEXT.__unwind_info: 0x58c0
+  __TEXT.__unwind_info: 0x5988
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x76a8
+  __DATA_CONST.__const: 0x77f8
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb08
+  __DATA_CONST.__objc_selrefs: 0xb78
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x170
-  __DATA_CONST.__got: 0x2388
-  __AUTH_CONST.__const: 0x7780
-  __AUTH_CONST.__cfstring: 0x148e0
+  __DATA_CONST.__got: 0x23d8
+  __AUTH_CONST.__const: 0x77d0
+  __AUTH_CONST.__cfstring: 0x14ac0
   __AUTH_CONST.__objc_const: 0xed0
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_intobj: 0x150

   __AUTH.__objc_data: 0x190
   __AUTH.__data: 0x878
   __DATA.__objc_ivar: 0x88
-  __DATA.__data: 0x18690
-  __DATA.__bss: 0x608
+  __DATA.__data: 0x18620
+  __DATA.__bss: 0x618
   __DATA.__common: 0xa04
   __DATA_DIRTY.__objc_data: 0xa0
-  __DATA_DIRTY.__data: 0xf78
+  __DATA_DIRTY.__data: 0xfe8
   __DATA_DIRTY.__bss: 0x788
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
   - /System/Library/Frameworks/CoreAudio.framework/CoreAudio

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 11443
-  Symbols:   8664
+  Functions: 11505
+  Symbols:   8723
   CStrings:  0
 
Symbols:
+ -[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeer:groupID:]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeersForGroup:peers:]
+ -[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]
+ GCC_except_table131
+ GCC_except_table26
+ GCC_except_table31
+ GCC_except_table33
+ GCC_except_table50
+ _APCarPlayCarNeedsVTAlwaysActive
+ _APEndpointCopyAudioOutputLatencyMsForStream
+ _APEndpointPayloadRequiresCompositionRefresh
+ _APPairingClientCoreUtilsCopyMigratableUngroupedPeers
+ _APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo
+ _APPairingClientCoreUtilsMigrateUngroupedPeers
+ _APPairingClientCoreUtilsPatchUnpairedPeerWithGroupID
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
+ _APSCMTimeMakeWithRTPTimestamp
+ _APSGetSurroundRoleFromClusterMemberID
+ _APSIsHomeAccessory
+ _APSIsHomeTheaterSurroundEnabled
+ _APSIsUpdateInfoForwardingEnabled
+ _APSenderSessionGetFallbackToInfraReasonForUnselectedTransport
+ _APTDiagnosticSendStreamInfo
+ _APTNANDataSessionGetDatapathRSSI
+ _APTransportConnectionQoSFromSocketQoS
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _APTransportTrafficCapturePrepareForCollection
+ _FigCFNumberGetCFIndex
+ _FigCFSetGetCount
+ _FigEndpointSetProperty
+ _OBJC_CLASS_$_CUSystemMonitor
+ ___60-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke
+ ___63-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke
+ ___APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke
+ ___APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke_2
+ ___APPairingClientCoreUtilsMigrateUngroupedPeers_block_invoke
+ ___block_descriptor_40_e8_32o_e15_v24?0r^v8r^v16ls32l8
+ ___block_descriptor_48_e8_32o40o_e29_v32?0"CUPairedPeer"8Q16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32o40r_e29_v24?0"NSArray"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32o40r_e34_v32?0"NSString"8"NSArray"16^B24ls32l8r40l8
+ ___block_descriptor_56_e15_v24?0r^v8r^v16l
+ ___carEndpoint_handleVideoPlayerBackButtonEvent_block_invoke
+ ___coreUtilsPairing_updatePairingGroupInfoIfNeeded_block_invoke_2
+ ___endpointCluster_reconcileResponsiveAudioTransports_block_invoke
+ ___endpoint_performRemoteTeardown_block_invoke
+ ___endpoint_performRemoteTeardown_block_invoke_2
+ ___endpoint_performRemoteTeardown_block_invoke_3
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_2
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_3
+ ___manager_create_block_invoke_6
+ _airPlayDescription_isAppleHomeAccessory
+ _bufferedAudioEngine_isHoseClusterBuddy
+ _carManager_reportBonjourEventToCarKit
+ _carManager_reportBonjourSuccessIfNeeded
+ _emp_demoteEndpoint
+ _endpointAggregate_handleAudioStreamResumed
+ _endpointCluster_activateSubEndpointForcingTransportIfNeeded
+ _endpointCluster_copyActivatedSubEndpointsByTransportType
+ _endpointCluster_copyActivationOptionsForcingTransportType
+ _endpointCluster_copyForcedTransportForResponsiveAudio
+ _endpointCluster_failDelayMSecsForFailureCount.kFailDelayLadderPercent
+ _endpointCluster_failureCountForSubEndpoint
+ _endpoint_forwardUpdateInfo
+ _endpoint_handleAudioStreamResumed
+ _endpoint_startPowerSourceMonitorIfNeeded
+ _endpoint_stopPowerSourceMonitor
+ _endpoint_updateInactivityTimer
+ _kAPEndpointAggregateCreationOptionKey_ClusterType
+ _kAPEndpointCommandForwardToVideoPlayback_Params
+ _kAPEndpointCommandForwardToVideoPlayback_ParamsKey_Action
+ _kAPEndpointCommandForwardToVideoPlayback_ParamsVal_FadeOut
+ _kAPEndpointCoreAnalyticsDictionaryKey_IsWireless
+ _kAPEndpointDescriptionProperty_SurroundRole
+ _kAPEndpointProperty_AudioOutputLatencyMs
+ _kAPEndpointProperty_SurroundRole
+ _kAPEndpointStreamBufferedAudioEngineCreationOption_ForceFirstRemoteMediaTime
+ _kAPEndpointStreamConnectionKey_QoS
+ _kAPSDynamicLatencyManagerVariantIdentifier_B525
+ _kAPSEndpointStreamAudioHoseRegistrarRegistrationOption_SurroundRole
+ _kFigEndpointActivateOptionKey_ForcedTransportType
+ _kFigEndpointCarPlayVideoPlaybackButton_BackButton
+ _kFigEndpointCarPlayVideoPlaybackButton_HideVideoButton
+ _kFigEndpointCarPlayVideoPlaybackPlayerEvent_ButtonTapped
+ _kFigEndpointForcedTransportType_Infra
+ _kFigEndpointNotification_CarPlayVideoPlaybackPlayerEvent
+ _kFigEndpointProperty_CarPlayScreenFadeDurationInSeconds
+ _kFigEndpointSubType_HomeAccessory
+ _objc_release_x26
+ _objc_release_x27
+ _objc_retain_x8
+ _sessionfactory_RemoveAirPlaySession
+ _sessionfactory_RemoveSessionClient
- GCC_except_table127
- GCC_except_table48
- _APSEndpointStreamAudioHoseRegistrarRegisterProtocolDriverHoseLegacy
- _APSKeyHolderCreateEncryptionKeysForStream
- _APTDiagnosticMulticastDataToAllHosts
- _APTransportTrafficCaptureFlushForSysdiagnose
- _OUTLINED_FUNCTION_272
- _OUTLINED_FUNCTION_273
- _OUTLINED_FUNCTION_274
- _OUTLINED_FUNCTION_275
- _OUTLINED_FUNCTION_276
- _OUTLINED_FUNCTION_277
- _OUTLINED_FUNCTION_278
- _OUTLINED_FUNCTION_279
- _OUTLINED_FUNCTION_280
- ___block_descriptor_48_e15_v24?0r^v8r^v16l
- ___endpoint_prepareLocalTeardown_block_invoke
- ___endpoint_prepareLocalTeardown_block_invoke_2
- ___endpoint_prepareLocalTeardown_block_invoke_3
- ___epp_EnsureAuthorizedWithCompletionCallback_block_invoke_2
- _apsession_getNANRSSI
- _audioStream_preWarmNANDataSession
- _bufferedAudioEngine_isHoseInStereoPair
- _carManager_isDisconnectCausedBySignalInterference
- _carManager_reportBonjourFailureToCarKit
- _endpointCluster_getNumSubEndpointsActivated
- _endpoint_startInactivityTimer
- _kAPCarPlayCarServicesInterface_FailureInfoConnectionPhase_Discovery
- _kAPCarPlayCarServicesInterface_FailureInfoConnectionPhase_Running
- _kAPCarPlayCarServicesInterface_FailureInfoDiscoveryType_Bonjour
- _kAPCarPlayCarServicesInterface_FailureInfoKey_TransportType
- _kAPCarPlayCarServicesInterface_FailureInfoReason_ConnectionReset
- _kAPCarPlayCarServicesInterface_FailureInfoReason_NoBonjourRecord
- _kAPCarPlayCarServicesInterface_FailureInfoReason_NoConnectCmd
- _kAPCarPlayCarServicesInterface_FailureInfoReason_WiFiLinkUnusable
```
