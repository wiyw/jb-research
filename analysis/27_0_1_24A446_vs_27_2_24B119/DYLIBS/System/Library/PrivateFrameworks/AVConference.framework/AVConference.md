## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

```diff

-2235.63.1.2.0
-  __TEXT.__text: 0x7e0224
-  __TEXT.__objc_methlist: 0x3ac00
+2260.15.1.0.0
+  __TEXT.__text: 0x7e6df4
+  __TEXT.__objc_methlist: 0x3ad90
   __TEXT.__const: 0xc690
-  __TEXT.__cstring: 0x9f9f5
-  __TEXT.__oslogstring: 0x141d50
-  __TEXT.__gcc_except_tab: 0x2d04
+  __TEXT.__cstring: 0x9fe77
+  __TEXT.__oslogstring: 0x144e55
+  __TEXT.__gcc_except_tab: 0x2ddc
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x12608
+  __TEXT.__unwind_info: 0x12678
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x77e0
-  __DATA_CONST.__objc_classlist: 0x14b8
+  __DATA_CONST.__const: 0x77f8
+  __DATA_CONST.__objc_classlist: 0x14b0
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x510
+  __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18d98
+  __DATA_CONST.__objc_selrefs: 0x18ed0
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x1268
+  __DATA_CONST.__objc_superrefs: 0x1260
   __DATA_CONST.__objc_arraydata: 0x27d8
-  __DATA_CONST.__got: 0x1e40
-  __AUTH_CONST.__const: 0x4608
-  __AUTH_CONST.__cfstring: 0x29d00
-  __AUTH_CONST.__objc_const: 0x6d128
+  __DATA_CONST.__got: 0x1de0
+  __AUTH_CONST.__const: 0x4588
+  __AUTH_CONST.__cfstring: 0x29e80
+  __AUTH_CONST.__objc_const: 0x6d3b8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x52f8
   __AUTH_CONST.__objc_arrayobj: 0x1d88
+  __AUTH_CONST.__objc_doubleobj: 0x210
   __AUTH_CONST.__objc_floatobj: 0x30
-  __AUTH_CONST.__objc_doubleobj: 0x200
   __AUTH_CONST.__objc_dictobj: 0x2d0
-  __AUTH_CONST.__auth_got: 0x2c38
+  __AUTH_CONST.__auth_got: 0x2c68
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__data: 0xf8
-  __DATA.__objc_ivar: 0x7714
-  __DATA.__data: 0x7d48
-  __DATA.__bss: 0x950
+  __DATA.__objc_ivar: 0x777c
+  __DATA.__data: 0x1c10
+  __DATA.__bss: 0xf10
   __DATA.__common: 0x55
-  __DATA_DIRTY.__objc_data: 0xcf30
-  __DATA_DIRTY.__data: 0x420
-  __DATA_DIRTY.__bss: 0xae0
+  __DATA_DIRTY.__objc_data: 0xcee0
+  __DATA_DIRTY.__data: 0x6570
+  __DATA_DIRTY.__bss: 0x4c0
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35502
-  Symbols:   42024
+  Functions: 35560
+  Symbols:   42090
   CStrings:  0
 
Symbols:
+ +[VCAVFoundationCapture isZoomSupportedForCaptureDevice:captureSource:]
+ +[VCAudioToolboxAudioComponentMock activeInstanceCount]
+ +[VCAudioToolboxAudioComponentMock isMockingSessionActive]
+ +[VCHardwareSettings supportsClientPreviewPresentationOrientation]
+ +[VCMediaNegotiationBlobV2StreamGroup(Utils) homeKitCameraDefaultsForStreamGroupCamera:]
+ -[AVCPreviewCameraSession setPreviewPresentationOrientation:]
+ -[AVConferencePreview setPreviewPresentationOrientation:]
+ -[CannedEncodedVideoCapture reset]
+ -[CannedRawVideoCapture reset]
+ -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:]
+ -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:]
+ -[VCAVFoundationCapture clearPreviewPresentationOrientation]
+ -[VCAVFoundationCapture clearRemotePresentationOrientation]
+ -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture isClientPreviewPresentationOrientationGoverning]
+ -[VCAVFoundationCapture secondaryCameraRequestSizeForAspectRatio:]
+ -[VCAVFoundationCapture setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]
+ -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]
+ -[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]
+ -[VCAudioSessionAVAS dispatchedIsInputAvailable]
+ -[VCAudioStream reportingAudioJBRampStats]
+ -[VCAudioStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCAudioStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ -[VCAudioToolboxAudioComponentMock autorelease]
+ -[VCAudioToolboxAudioComponentMock release]
+ -[VCAudioToolboxAudioComponentMock retainCount]
+ -[VCAudioToolboxAudioComponentMock retain]
+ -[VCAudioTransmitterConfig setShouldCapBitrateForWatchRelay:]
+ -[VCAudioTransmitterConfig shouldCapBitrateForWatchRelay]
+ -[VCCallSession isRemoteWatchRelayDeviceWithDeviceType:]
+ -[VCConnectionHealthMonitor resetStallDetectionStateAfterMonitoringResumed]
+ -[VCCoreAudio_AudioUnitMock autorelease]
+ -[VCCoreAudio_AudioUnitMock beginSession]
+ -[VCCoreAudio_AudioUnitMock endSession]
+ -[VCCoreAudio_AudioUnitMock isMockingEnabled]
+ -[VCCoreAudio_AudioUnitMock release]
+ -[VCCoreAudio_AudioUnitMock retainCount]
+ -[VCCoreAudio_AudioUnitMock retain]
+ -[VCMediaRecorder hasConfiguredWriter]
+ -[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]
+ -[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]
+ -[VCMockQRServer forwardOnePacketFromListenerSocket:listenerSourceIP:listenerSourcePort:forwarderSocketList:listenerParticipantID:]
+ -[VCMockQRServer stopPacketForwarders]
+ -[VCRTPHistory dealloc]
+ -[VCRemoteVideoState participantId]
+ -[VCRemoteVideoState setParticipantId:]
+ -[VCSession clearRemotePresentationOrientationOnCaptureServer]
+ -[VCSessionPowerPolicy hasPrimaryCameraFrameRateMitigation]
+ -[VCSessionPowerPolicy hasSecondaryCameraFrameRateMitigation]
+ -[VCTransportSessionMultiLink handleListenerEvents:error:result:]
+ -[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]
+ -[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]
+ -[VCVideoCaptureServer clearRemotePresentationOrientation]
+ -[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]
+ -[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedIsClientPreviewPresentationOrientationGoverning]
+ -[VCVideoCaptureServer handleClientPreviewPresentationOrientationMessage:]
+ -[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]
+ -[VCVideoCaptureServer publishCameraUIDChangedForCameraUID:cameraSessionType:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]
+ -[VCVideoStream canReuseTransportsForStreamConfigs:]
+ -[VCVideoStream expectedTransportArrayCountForStreamConfigs:]
+ -[VCVideoStream supportsMaxKeyFrameIntervalDuration]
+ -[VCVideoStream transportArrayContainsRTXTransport]
+ -[VCVideoStream transportStreamCountForStreamConfig:]
+ -[VCVideoStream willCreateRTXTransportForStreamConfig:]
+ -[VCVideoStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCVideoStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ -[VCVideoTransmitterConfig reinitEncoderOnFrameAspectRatioChangeEnabled]
+ -[VCVideoTransmitterConfig setReinitEncoderOnFrameAspectRatioChangeEnabled:]
+ -[VCVideoTransmitterConfig setVtLoggingIdentifier:]
+ -[VCVideoTransmitterConfig vtLoggingIdentifier]
+ GCC_except_table112
+ GCC_except_table164
+ GCC_except_table169
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table217
+ GCC_except_table235
+ GCC_except_table269
+ GCC_except_table272
+ GCC_except_table275
+ GCC_except_table314
+ GCC_except_table318
+ GCC_except_table368
+ GCC_except_table38
+ GCC_except_table452
+ _AVErrorDeviceKey
+ _CVImageBufferGetColorSpace
+ _CVPixelBufferPoolFlush
+ _OBJC_IVAR_$_AVCPacketRelaySocketConnection._isMonitoring
+ _OBJC_IVAR_$_AVConferencePreview._preRegistrationCameraUIDToSession
+ _OBJC_IVAR_$_AVConferencePreview._setPrimarySecondaryInFlightCount
+ _OBJC_IVAR_$_VCAVFoundationCapture._dualCaptureRear1440x1080
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasPreviewPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasVideoPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._lastAttachPerFrameAR
+ _OBJC_IVAR_$_VCAVFoundationCapture._previewPresentationOrientation
+ _OBJC_IVAR_$_VCAudioStreamSendGroup._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCAudioStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._activeInstances
+ _OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._instancesLock
+ _OBJC_IVAR_$_VCAudioTransmitter._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCAudioTransmitterConfig._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCCoreAudio_AudioUnitMock._isImplicitPreferenceSession
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._enqueueLock
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._queueLock
+ _OBJC_IVAR_$_VCMockQRServer._forwarderQueue
+ _OBJC_IVAR_$_VCMockQRServer._forwarderSources
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._congestionKeepHistoryRatio
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._feedbackHistoryMaxLength
+ _OBJC_IVAR_$_VCRedundancyControlAlgorithmVideo._freezeStartTime
+ _OBJC_IVAR_$_VCRemoteVideoState._participantId
+ _OBJC_IVAR_$_VCSession._remoteParticipantsMapLock
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasPreviewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasRemotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequestPID
+ _OBJC_IVAR_$_VCVideoCaptureServer._remotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoStream._didDetectSensitiveContentFired
+ _OBJC_IVAR_$_VCVideoStream._didFlushForInterruptedFrameRun
+ _OBJC_IVAR_$_VCVideoStreamRateAdaptationFeedbackOnly._rateControlFeedbackDrained
+ _OBJC_IVAR_$_VCVideoStreamReceiver._vtLoggingIdentifier
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._hasModulatedTimestampBaseline
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._lastModulatedTimestamp
+ _OBJC_IVAR_$_VCVideoStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCVideoStreamTransmitter._vtLoggingIdentifier
+ _OBJC_IVAR_$_VCVideoTransmitterConfig._reinitEncoderOnFrameAspectRatioChangeEnabled
+ _OBJC_IVAR_$_VCVideoTransmitterConfig._vtLoggingIdentifier
+ _OUTLINED_FUNCTION_82
+ _OUTLINED_FUNCTION_83
+ _VCConnectionIDS_SetLocalLinkTechnology
+ _VCImageQueue_Flush
+ _VCJitterBuffer_GetInitialRampMetrics
+ _VCMediaQueue_RecyclePacket
+ _VCMediaRecorderHistory_HasConfiguredWriter
+ _VCRedundancyControllerVideoCongestionKeepHistoryRatio
+ _VCRemoteVideoManager_FlushQueuesExceptStreamToken
+ _VCRemoteVideoManager_SetParticipantIdForStreamToken
+ _VCStringUtils_AddVTLoggingIdentifier
+ _VCStringUtils_CFStringNotEqual
+ _VCStringUtils_SetVTLoggingIdentifier
+ _VCVideoCaptureServer_ClientPIDFromArguments
+ _VCVideoStreamConfig_SetVTLoggingIdentifier
+ _VTCompressionSessionCreateWithOptions
+ __OBJC_$_INSTANCE_VARIABLES_VCAudioToolboxAudioComponentMock
+ __VCMediaQueue_DrainPendingRecyclePackets
+ __VideoPacketBuffer_SetNeedRefresh
+ ___135-[VCMockQRServer startPacketForwarderWithListenerSocket:listenerSourceIP:listenerSourcePort:forwarderSocketList:listenerParticipantID:]_block_invoke
+ ___38-[VCAudioSessionAVAS isInputAvailable]_block_invoke
+ ___38-[VCAudioSessionAVAS isInputSupported]_block_invoke
+ ___38-[VCMockQRServer stopPacketForwarders]_block_invoke
+ ___44-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke
+ ___57-[AVConferencePreview setPreviewPresentationOrientation:]_block_invoke
+ ___58-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke
+ ___60-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke
+ ___61-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke
+ ___62-[VCVideoStreamRateAdaptationFeedbackOnly startFeedbackSource]_block_invoke_2
+ ___66+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke
+ ___76-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke
+ ___77-[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]_block_invoke
+ ___78-[VCVideoCaptureServer publishCameraUIDChangedForCameraUID:cameraSessionType:]_block_invoke
+ ___78-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]_block_invoke
+ ___80-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke
+ ___86-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:hasSecondary:aspectRatio:]_block_invoke
+ ___VCMediaRecorderHistory_HasConfiguredWriter_block_invoke
+ ___VCRemoteVideoManager_FlushQueuesExceptStreamToken_block_invoke
+ ___VCRemoteVideoManager_SetParticipantIdForStreamToken_block_invoke
+ ___block_descriptor_40_e8_32o_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12ls32l8
+ ___block_descriptor_61_e8_32o40o48o_e5_v8?0ls32l8s40l8s48l8
+ _kForwarderQueueSpecificKey
+ _kVCXPCConnectionTimeoutQueueSpecificKey
+ _kVTCompressionSessionOption_LoggingIdentifier
+ _kVTDecompressionSessionOption_LoggingIdentifier
+ _nw_error_get_error_domain
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
+ _supportsClientPreviewPresentationOrientation.onceToken
+ _supportsClientPreviewPresentationOrientation.resolved
+ _xpc_copy_description
- +[VCHardwareSettings supportsSquarePreviewCapture]
- -[AVCCaptionsClient initWithDelegate:translatorIdentifier:]
- -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:]
- -[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:aspectRatio:]
- -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]
- -[VCAVFoundationCapture squarePreviewAdjustedRequestSizeForCaptureSize:]
- -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]
- -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]
- -[VCAudioCaptionsSpeechTranslator addToCaptionTasksWithError:]
- -[VCAudioCaptionsSpeechTranslator client:didReceiveTranscriptionResult:]
- -[VCAudioCaptionsSpeechTranslator client:didReceiveTranslationResult:]
- -[VCAudioCaptionsSpeechTranslator client:didStopTranslationWithError:]
- -[VCAudioCaptionsSpeechTranslator dealloc]
- -[VCAudioCaptionsSpeechTranslator destroyCaptions]
- -[VCAudioCaptionsSpeechTranslator finishCaptions]
- -[VCAudioCaptionsSpeechTranslator initWithDelegate:isLocal:taskIdentifier:reportingAgent:]
- -[VCAudioCaptionsSpeechTranslator initWithSpeechConfig:]
- -[VCAudioCaptionsSpeechTranslator packageAndSendTranscribedString:withTask:]
- -[VCAudioCaptionsSpeechTranslator packageAndSendTranslatedString:withTask:]
- -[VCAudioCaptionsSpeechTranslator pushSamples:numSamples:hostTime:]
- -[VCAudioCaptionsSpeechTranslator serverDidDisconnectForClient:]
- -[VCAudioCaptionsSpeechTranslator setUpCaptionsWithError:]
- -[VCAudioCaptionsSpeechTranslator setupTranslatorSharedWithError:]
- -[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]
- -[VCAudioCaptionsSpeechTranslator shouldPushSamples]
- -[VCAudioCaptionsSpeechTranslator startCaptionsWithError:]
- -[VCAudioCaptionsSpeechTranslator stopCaptions]
- -[VCAudioCaptionsSpeechTranslator translationDidStartForClient:]
- -[VCAudioManager anyClientNeedsMicInputWithPreferredClient:]
- -[VCAudioManager updateMicAttributionForClient:shouldAdd:]
- -[VCAudioToolboxAudioComponentMock dealloc]
- -[VCCoreAudio_AudioUnitMock dealloc]
- -[VCTransportSessionMultiLink handleListenerEvents:error:]
- -[VCVideoCaptureServer copyLocalScreenAttributesForVideoAttributes:]
- -[VCVideoStreamReceiver gatherInterframeDelayStats:]
- GCC_except_table111
- GCC_except_table168
- GCC_except_table198
- GCC_except_table200
- GCC_except_table220
- GCC_except_table245
- GCC_except_table254
- GCC_except_table257
- GCC_except_table300
- GCC_except_table313
- GCC_except_table36
- GCC_except_table367
- GCC_except_table451
- _OBJC_CLASS_$_VCAudioCaptionsSpeechTranslator
- _OBJC_IVAR_$_VCAVFoundationCapture._clientRequestedSize
- _OBJC_IVAR_$_VCAVFoundationCapture._configuringForCapture
- _OBJC_IVAR_$_VCAVFoundationCapture._squarePreviewOverrideActive
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._currentSourceUpdateNumber
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._currentTranslatedUpdateNumber
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._isStarted
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._transcriptionTimes
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorClient
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorConfiguration
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorStartDuration
- _OBJC_IVAR_$_VCAudioCaptionsSpeechTranslator._translatorStartTime
- _OBJC_IVAR_$_VCAudioManager._hasActiveMicClients
- _OBJC_IVAR_$_VCPowerManager._forceDisableThermal
- _OBJC_IVAR_$_VCVideoStreamReceiver._interframeDelayMonitor
- _OBJC_METACLASS_$_VCAudioCaptionsSpeechTranslator
- _VCAudioUnit_BasebandInstance
- _VCAudioUnit_DefaultOutputInstance
- _VCAudioUnit_RemoteIOInstance
- _VCAudioUnit_SystemAudioInstance
- _VCAudioUnit_VoiceProcessorInstance
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer.flag
- _VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer.onceToken
- _VCFeatureFlagManager_HostSpeechTranslationServer
- _VCFeatureFlagManager_HostSpeechTranslationServer.audioFlag
- _VCFeatureFlagManager_HostSpeechTranslationServer.onceToken
- _VCFeatureFlagManager_HostSpeechTranslationServer.videoFlag
- _VCSpeechTranslation_STSpeechTranslatorClientClass
- _VCSpeechTranslation_STSpeechTranslatorClientClass.onceToken
- _VCSpeechTranslation_STSpeechTranslatorClientClass.speechTranslatorClientClass
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass.onceToken
- _VCSpeechTranslation_STSpeechTranslatorConfigurationClass.speechTranslatorConfigurationClass
- _VCSpeechTranslation_StartServer
- _VCVirtualAVCaptureDevice_OnMediaSample
- __OBJC_$_INSTANCE_METHODS_VCAudioCaptionsSpeechTranslator
- __OBJC_$_INSTANCE_VARIABLES_VCAudioCaptionsSpeechTranslator
- __OBJC_$_PROP_LIST_VCAudioCaptionsSpeechTranslator
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_STSpeechTranslatorClientDelegate
- __OBJC_$_PROTOCOL_REFS_STSpeechTranslatorClientDelegate
- __OBJC_CLASS_PROTOCOLS_$_VCAudioCaptionsSpeechTranslator
- __OBJC_CLASS_RO_$_VCAudioCaptionsSpeechTranslator
- __OBJC_LABEL_PROTOCOL_$_STSpeechTranslatorClientDelegate
- __OBJC_METACLASS_RO_$_VCAudioCaptionsSpeechTranslator
- __OBJC_PROTOCOL_$_STSpeechTranslatorClientDelegate
- __VCSpeechTranslation_LibraryHandle
- __VCSpeechTranslation_LibraryHandle.onceToken
- __VCVideoStreamSendGroup_SecondaryCameraTransfer
- ___30-[VCSession participantForID:]_block_invoke
- ___39-[VCMockQRServer startPacketForwarders]_block_invoke
- ___50+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke
- ___70-[VCAudioCaptionsSpeechTranslator client:didReceiveTranslationResult:]_block_invoke
- ___70-[VCAudioCaptionsSpeechTranslator setupTranslatorStandaloneWithError:]_block_invoke
- ___72-[VCAudioCaptionsSpeechTranslator client:didReceiveTranscriptionResult:]_block_invoke
- ___73-[VCAVFoundationCapture batchSetCameraUIDsPrimary:secondary:aspectRatio:]_block_invoke
- ___78-[VCVideoCaptureServer dispatchedSetCaptureCameraWithToken:cameraSessionType:]_block_invoke_2
- ___VCFeatureFlagManager_HostAudioTranscriptionAnalysisServer_block_invoke
- ___VCFeatureFlagManager_HostSpeechTranslationServer_block_invoke
- ___VCSpeechTranslation_STSpeechTranslatorClientClass_block_invoke
- ___VCSpeechTranslation_STSpeechTranslatorConfigurationClass_block_invoke
- ____VCSpeechTranslation_LibraryHandle_block_invoke
- ___block_descriptor_40_e8_32o_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12ls32l8
- __audioComponentMockLock
- __audioUnitMockLock
- __weakAudioComponentMockInstance
- __weakAudioUnitMockInstance
- _objc_loadWeakRetained
- _supportsSquarePreviewCapture.onceToken
- _supportsSquarePreviewCapture.resolved
```
