## AVFCapture

> `/System/Library/PrivateFrameworks/AVFCapture.framework/AVFCapture`

```diff

-764.22.14.0.0
-  __TEXT.__text: 0x1454a8
-  __TEXT.__objc_methlist: 0x113cc
-  __TEXT.__const: 0xf02
-  __TEXT.__gcc_except_tab: 0x314c
-  __TEXT.__cstring: 0x2f009
-  __TEXT.__oslogstring: 0xa75e
+764.42.8.0.0
+  __TEXT.__text: 0x1480c8
+  __TEXT.__objc_methlist: 0x116bc
+  __TEXT.__const: 0xf42
+  __TEXT.__gcc_except_tab: 0x3170
+  __TEXT.__cstring: 0x2f969
+  __TEXT.__oslogstring: 0xb3be
   __TEXT.__dlopen_cstrs: 0x274
   __TEXT.__ustring: 0x54
   __TEXT.__swift5_typeref: 0xef

   __TEXT.__swift5_reflstr: 0x24
   __TEXT.__swift5_fieldmd: 0x50
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x5768
+  __TEXT.__unwind_info: 0x5808
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9458
-  __DATA_CONST.__objc_classlist: 0x6c8
+  __DATA_CONST.__const: 0x9480
+  __DATA_CONST.__objc_classlist: 0x6d8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x91d8
+  __DATA_CONST.__objc_selrefs: 0x9358
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x5f0
-  __DATA_CONST.__objc_arraydata: 0x4a8
-  __DATA_CONST.__got: 0x2fa0
-  __AUTH_CONST.__const: 0xe10
-  __AUTH_CONST.__cfstring: 0x16be0
-  __AUTH_CONST.__objc_const: 0x1cac8
-  __AUTH_CONST.__objc_intobj: 0xb70
+  __DATA_CONST.__objc_superrefs: 0x600
+  __DATA_CONST.__objc_arraydata: 0x520
+  __DATA_CONST.__got: 0x2fe8
+  __AUTH_CONST.__const: 0xe70
+  __AUTH_CONST.__cfstring: 0x16e20
+  __AUTH_CONST.__objc_const: 0x1ce88
+  __AUTH_CONST.__objc_intobj: 0xba0
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__objc_arrayobj: 0x3a8
+  __AUTH_CONST.__objc_arrayobj: 0x408
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0x1170
+  __AUTH_CONST.__auth_got: 0x1188
   __AUTH_CONST.__auth_ptr: 0x38
-  __AUTH.__objc_data: 0x2910
-  __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x1ec8
-  __DATA.__data: 0xe48
-  __DATA.__bss: 0x900
-  __DATA.__common: 0x1c0
-  __DATA_DIRTY.__objc_data: 0x1ae0
-  __DATA_DIRTY.__data: 0x178
+  __AUTH.__objc_data: 0xdb8
+  __DATA.__objc_ivar: 0x1efc
+  __DATA.__data: 0xe50
+  __DATA.__bss: 0x940
+  __DATA.__common: 0x1e0
+  __DATA_DIRTY.__objc_data: 0x36d8
+  __DATA_DIRTY.__data: 0x198
   __DATA_DIRTY.__bss: 0x4e8
   __DATA_DIRTY.__common: 0x160
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7817
-  Symbols:   14430
+  Functions: 7891
+  Symbols:   14554
   CStrings:  0
 
Symbols:
+ +[AVCaptureDevice moduleSealedStateForDeviceType:position:]
+ +[AVCapturePersonalPhotographerSessionFinishCoordinator inactivityTimeoutForSystemPressureState:]
+ +[AVCaptureProprietaryDefaultsSingleton migrateDefaultsFromAppBundleID:newAppBundleID:]
+ +[AVCaptureResolvedPhotoSettings resolvedSettingsWithUniqueID:photoDimensions:rawPhotoDimensions:previewDimensions:embeddedThumbnailDimensions:rawEmbeddedThumbnailDimensions:livePhotoMovieEnabled:livePhotoMovieDimensions:livePhotoAssetIdentifier:portraitEffectsMatteDimensions:hairSegmentationMatteDimensions:skinSegmentationMatteDimensions:teethSegmentationMatteDimensions:glassesSegmentationMatteDimensions:spatialOverCapturePhotoDimensions:turboModeEnabled:flashEnabled:redEyeReductionEnabled:HDREnabled:adjustedPhotoFiltersEnabled:EV0PhotoDeliveryEnabled:stillImageStabilizationEnabled:virtualDeviceFusionEnabled:squareCropEnabled:deferredPhotoProxyDimensions:photoProcessingTimeRange:contentAwareDistortionCorrectionEnabled:spatialPhotoCaptureEnabled:photoManifest:digitalFlashUserInterfaceHints:digitalFlashUserInterfaceRGBEstimate:captureBeforeResolvingSettingsEnabled:secureSigningPhotoCapturePhotoEnabled:personalPhotographerDuplicateInfo:]
+ +[AVMetadataDeviceProximityDetectionObject deviceProximityDetectionWithDeviceDictionary:input:time:]
+ +[AVMetadataLightSourceEstimationObject lightSourceEstimationWithDictionary:input:time:]
+ -[AVCaptureConnection _additionalContentRotationDegreesForV68ThirdPartyCompatibility]
+ -[AVCaptureConnection _setV68ThirdPartyCompatibilityVideoRotationAngle:]
+ -[AVCaptureConnection _supportsV68ThirdPartyCompatibilityRotation]
+ -[AVCaptureConnection _v68ThirdPartyCompatibilityRotationMode]
+ -[AVCaptureConnection _v68ThirdPartyCompatibilityVideoRotationAngle]
+ -[AVCaptureDevice moduleSealedState]
+ -[AVCaptureDevice supportedMetadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureDeviceRotationCoordinator _handleDevicePrimaryDisplayRegionDidChangeNotification:]
+ -[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]
+ -[AVCaptureDeviceRotationCoordinator _initWithDeviceWithoutPreviewLayer:]
+ -[AVCaptureFigVideoDevice moduleSealedState]
+ -[AVCaptureFigVideoDevice supportedMetadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput _metadataIdentifiersForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput deviceProximityDetectionDeviceTypes]
+ -[AVCaptureMetadataOutput deviceProximityDetectionTargetFrameRate]
+ -[AVCaptureMetadataOutput lightSourceEstimationAmbientLuminance]
+ -[AVCaptureMetadataOutput lightSourceEstimationTargetFrameRate]
+ -[AVCaptureMetadataOutput metadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVCaptureMetadataOutput perceptionTestModeEnabled]
+ -[AVCaptureMetadataOutput setDeviceProximityDetectionDeviceTypes:]
+ -[AVCaptureMetadataOutput setLightSourceEstimationAmbientLuminance:]
+ -[AVCaptureMetadataOutput setMetadataObjectTypesForPerceptionThumbnailChannel:]
+ -[AVCaptureMetadataOutput setPerceptionTestModeEnabled:]
+ -[AVCaptureMetadataOutput supportedMetadataObjectTypesForPerceptionThumbnailChannel]
+ -[AVCaptureMovieFileOutput _updateConstituentDeviceSwitchingBehaviorForSourceDevice:]
+ -[AVCapturePersonalPhotographerSessionFinishCoordinator finishWithRequest:expectedSettingsIDs:error:]
+ -[AVCapturePersonalPhotographerSessionFinishCoordinator initWithInactivityTimeout:completionHandler:]
+ -[AVCapturePersonalPhotographerSessionFinishCoordinator recordStillComplete]
+ -[AVCapturePersonalPhotographerSessionResults _isPhotoRegisteredWithSettingsIDNumber:]
+ -[AVCapturePersonalPhotographerSessionResults _timestampsForSettingsIDs:]
+ -[AVCapturePersonalPhotographerSessionResults isPhotoRegisteredForDeletionWithSettingsID:]
+ -[AVCapturePersonalPhotographerSessionResults isPhotoRegisteredWithSettingsID:]
+ -[AVCapturePersonalPhotographerSessionResults registerPhotoSettingsIDForDeletion:]
+ -[AVCapturePersonalPhotographerSessionResults registerPhotoTimestamp:forSettingsID:]
+ -[AVCapturePersonalPhotographerSessionResults registerPhotoWithSettingsID:]
+ -[AVCapturePersonalPhotographerSessionResults systemRecommendedPhotosToDeleteBySettingsID]
+ -[AVCapturePersonalPhotographerSessionResults systemRecommendedPhotosToSaveBySettingsID]
+ -[AVCaptureProprietaryDefaultsSingleton migrateDefaultsFromAppBundleID:newAppBundleID:]
+ -[AVCaptureResolvedPhotoSettings _initWithUniqueID:photoDimensions:rawPhotoDimensions:previewDimensions:embeddedThumbnailDimensions:rawEmbeddedThumbnailDimensions:livePhotoMovieEnabled:livePhotoMovieDimensions:livePhotoAssetIdentifier:portraitEffectsMatteDimensions:hairSegmentationMatteDimensions:skinSegmentationMatteDimensions:teethSegmentationMatteDimensions:glassesSegmentationMatteDimensions:spatialOverCapturePhotoDimensions:turboModeEnabled:flashEnabled:redEyeReductionEnabled:HDREnabled:adjustedPhotoFiltersEnabled:EV0PhotoDeliveryEnabled:stillImageStabilizationEnabled:virtualDeviceFusionEnabled:squareCropEnabled:deferredPhotoProxyDimensions:photoProcessingTimeRange:contentAwareDistortionCorrectionEnabled:spatialPhotoCaptureEnabled:photoManifest:digitalFlashUserInterfaceHints:digitalFlashUserInterfaceRGBEstimate:captureBeforeResolvingSettingsEnabled:secureSigningPhotoCapturePhotoEnabled:personalPhotographerDuplicateInfo:]
+ -[AVCaptureResolvedPhotoSettings personalPhotographerDuplicateInfo]
+ -[AVCaptureSession _setUpAndUpdateV68ThirdPartyCompatibilityRotationAsynchronouslyIfNeededForDevice:]
+ -[AVCaptureSession _setUpV68ThirdPartyCompatibilityRotationCoordinatorForDevice:]
+ -[AVCaptureSession _tearDownV68ThirdPartyCompatibilityRotationCoordinatorIfUnusedForDeviceUniqueID:]
+ -[AVCaptureSession _updateV68ThirdPartyCompatibilityRotationForAllConnections]
+ -[AVCaptureSession _v68ThirdPartyCompatibilityRotationIsNeededForDeviceUniqueID:]
+ -[AVMetadataDeviceProximityDetectionObject confidence]
+ -[AVMetadataDeviceProximityDetectionObject copyWithZone:]
+ -[AVMetadataDeviceProximityDetectionObject description]
+ -[AVMetadataDeviceProximityDetectionObject deviceID]
+ -[AVMetadataDeviceProximityDetectionObject deviceType]
+ -[AVMetadataDeviceProximityDetectionObject initDerivedMetadataObjectFromMetadataObject:withTransform:isVideoMirrored:rollAdjustment:]
+ -[AVMetadataDeviceProximityDetectionObject initWithDeviceDictionary:sourceCaptureInput:time:]
+ -[AVMetadataDeviceProximityDetectionObject pose]
+ -[AVMetadataFaceObject hasLookingAtCameraConfidence]
+ -[AVMetadataFaceObject lookingAtCameraConfidence]
+ -[AVMetadataFaceObjectInternal hasLookingAtCameraConfidence]
+ -[AVMetadataFaceObjectInternal lookingAtCameraConfidence]
+ -[AVMetadataFaceObjectInternal setHasLookingAtCameraConfidence:]
+ -[AVMetadataFaceObjectInternal setLookingAtCameraConfidence:]
+ -[AVMetadataLightSourceEstimationObject copyWithZone:]
+ -[AVMetadataLightSourceEstimationObject dealloc]
+ -[AVMetadataLightSourceEstimationObject description]
+ -[AVMetadataLightSourceEstimationObject initDerivedMetadataObjectFromMetadataObject:withTransform:isVideoMirrored:rollAdjustment:]
+ -[AVMetadataLightSourceEstimationObject initWithLightSourceEstimationDictionary:sourceCaptureInput:time:]
+ -[AVMetadataLightSourceEstimationObject payload]
+ -[AVMetadataObject sentToPerceptionThumbnailChannel]
+ -[AVMetadataObjectInternal sentToPerceptionThumbnailChannel]
+ -[AVMetadataObjectInternal setSentToPerceptionThumbnailChannel:]
+ GCC_except_table101
+ GCC_except_table1026
+ GCC_except_table1032
+ GCC_except_table1040
+ GCC_except_table1050
+ GCC_except_table143
+ GCC_except_table146
+ GCC_except_table151
+ GCC_except_table152
+ GCC_except_table157
+ GCC_except_table158
+ GCC_except_table171
+ GCC_except_table172
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table175
+ GCC_except_table176
+ GCC_except_table184
+ GCC_except_table190
+ GCC_except_table192
+ GCC_except_table194
+ GCC_except_table195
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table208
+ GCC_except_table212
+ GCC_except_table222
+ GCC_except_table227
+ GCC_except_table231
+ GCC_except_table232
+ GCC_except_table235
+ GCC_except_table236
+ GCC_except_table246
+ GCC_except_table247
+ GCC_except_table252
+ GCC_except_table267
+ GCC_except_table276
+ GCC_except_table282
+ GCC_except_table291
+ GCC_except_table303
+ GCC_except_table308
+ GCC_except_table311
+ GCC_except_table317
+ GCC_except_table320
+ GCC_except_table341
+ GCC_except_table347
+ GCC_except_table353
+ GCC_except_table357
+ GCC_except_table360
+ GCC_except_table364
+ GCC_except_table373
+ GCC_except_table377
+ GCC_except_table387
+ GCC_except_table390
+ GCC_except_table396
+ GCC_except_table405
+ GCC_except_table426
+ GCC_except_table441
+ GCC_except_table450
+ GCC_except_table466
+ GCC_except_table489
+ GCC_except_table499
+ GCC_except_table511
+ GCC_except_table531
+ GCC_except_table534
+ GCC_except_table55
+ GCC_except_table560
+ GCC_except_table564
+ GCC_except_table577
+ GCC_except_table585
+ GCC_except_table593
+ GCC_except_table599
+ GCC_except_table6
+ GCC_except_table604
+ GCC_except_table611
+ GCC_except_table618
+ GCC_except_table628
+ GCC_except_table642
+ GCC_except_table665
+ GCC_except_table676
+ GCC_except_table686
+ GCC_except_table700
+ GCC_except_table710
+ GCC_except_table722
+ GCC_except_table741
+ GCC_except_table762
+ GCC_except_table765
+ GCC_except_table803
+ GCC_except_table805
+ GCC_except_table807
+ GCC_except_table809
+ GCC_except_table836
+ GCC_except_table848
+ GCC_except_table850
+ GCC_except_table852
+ GCC_except_table858
+ GCC_except_table860
+ GCC_except_table903
+ GCC_except_table907
+ GCC_except_table96
+ GCC_except_table974
+ GCC_except_table976
+ GCC_except_table978
+ GCC_except_table980
+ _AVCaptureClientHasEntitlement.checkDisableContinuityCameraHostOnceToken
+ _AVCaptureClientHasEntitlement.checkMigrateDefaultsOnceToken
+ _AVCaptureClientHasEntitlement.disableContinuityCameraHostAllowed
+ _AVCaptureClientHasEntitlement.migrateDefaults
+ _AVCaptureDevicePrimaryDisplayRegionDidChangeNotification
+ _AVCaptureDeviceTypeBuiltInInnerUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInOuterUltraWideCamera
+ _AVCaptureEntitlementProprietaryDefaultsMigration
+ _AVCaptureEntitlementToggleContinuityCaptureEnablement
+ _AVCaptureV68ThirdPartyCompatibilityEnabled
+ _AVCaptureV68ThirdPartyCompatibilityEnabled.sAnswer
+ _AVCaptureV68ThirdPartyCompatibilityEnabled.sOnceToken
+ _AVCaptureV68ThirdPartyCompatibilityShouldRotateVDO
+ _AVCaptureV68ThirdPartyCompatibilityShouldRotateVDO.sAnswer
+ _AVCaptureV68ThirdPartyCompatibilityShouldRotateVDO.sOnceToken
+ _AVControlCenterVideoEffectsRingLightOnboardingTipSignalPreferenceKey
+ _AVMetadataObjectTypeDeviceProximityDetection
+ _AVMetadataObjectTypeLightSourceEstimation
+ _CFPreferencesCopyAppValue
+ _CMTimeCopyDescription
+ _FigCaptureProprietaryDefaultsRingLightOnboardingTipSignalKey
+ _FigCaptureSkipTTR
+ _FigCaptureSourceRemoteGetPersonalizationStateForPosition
+ _OBJC_CLASS_$_AVMetadataDeviceProximityDetectionObject
+ _OBJC_CLASS_$_AVMetadataLightSourceEstimationObject
+ _OBJC_IVAR_$_AVCaptureConnectionInternal.v68CompatibilityCoordinatorAngle
+ _OBJC_IVAR_$_AVCaptureConnectionInternal.v68CompatibilityEnabledForConnection
+ _OBJC_IVAR_$_AVCaptureDeviceRotationCoordinator._suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer
+ _OBJC_IVAR_$_AVCaptureMetadataOutputInternal.deviceProximityDetectionDeviceTypes
+ _OBJC_IVAR_$_AVCaptureMetadataOutputInternal.lightSourceEstimationAmbientLuminance
+ _OBJC_IVAR_$_AVCaptureMetadataOutputInternal.metadataObjectTypesForPerceptionThumbnailChannel
+ _OBJC_IVAR_$_AVCaptureMetadataOutputInternal.perceptionTestModeEnabled
+ _OBJC_IVAR_$_AVCaptureMovieFileOutputInternal.deviceExposesOmahaConstituentDevices
+ _OBJC_IVAR_$_AVCaptureMovieFileOutputInternal.deviceIsBravoVariant
+ _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionFinishCoordinator._expectedSetOfSettingsIDsCommitted
+ _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._capturedSettingsIDs
+ _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._systemRecommendedPhotosToDeleteBySettingsID
+ _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._systemRecommendedPhotosToSaveBySettingsID
+ _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._timestampsBySettingsID
+ _OBJC_IVAR_$_AVCaptureResolvedPhotoSettingsInternal.personalPhotographerDuplicateInfo
+ _OBJC_IVAR_$_AVCaptureSessionInternal.thirdPartyCompatibilityRotationCoordinatorsByDeviceUniqueID
+ _OBJC_IVAR_$_AVControlCenterModuleState._isOptedInForRingLight
+ _OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._confidence
+ _OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._deviceID
+ _OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._deviceType
+ _OBJC_IVAR_$_AVMetadataDeviceProximityDetectionObject._pose
+ _OBJC_IVAR_$_AVMetadataFaceObjectInternal._hasLookingAtCameraConfidence
+ _OBJC_IVAR_$_AVMetadataFaceObjectInternal._lookingAtCameraConfidence
+ _OBJC_IVAR_$_AVMetadataLightSourceEstimationObject._payload
+ _OBJC_IVAR_$_AVMetadataObjectInternal._sentToPerceptionThumbnailChannel
+ _OBJC_METACLASS_$_AVMetadataDeviceProximityDetectionObject
+ _OBJC_METACLASS_$_AVMetadataLightSourceEstimationObject
+ _OUTLINED_FUNCTION_129
+ _OUTLINED_FUNCTION_130
+ _OUTLINED_FUNCTION_131
+ _OUTLINED_FUNCTION_132
+ _OUTLINED_FUNCTION_133
+ _OUTLINED_FUNCTION_134
+ _OUTLINED_FUNCTION_135
+ _OUTLINED_FUNCTION_136
+ __OBJC_$_CLASS_METHODS_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_CLASS_METHODS_AVMetadataLightSourceEstimationObject
+ __OBJC_$_INSTANCE_METHODS_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_INSTANCE_METHODS_AVMetadataLightSourceEstimationObject
+ __OBJC_$_INSTANCE_VARIABLES_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_INSTANCE_VARIABLES_AVMetadataLightSourceEstimationObject
+ __OBJC_$_PROP_LIST_AVMetadataDeviceProximityDetectionObject
+ __OBJC_$_PROP_LIST_AVMetadataLightSourceEstimationObject
+ __OBJC_CLASS_PROTOCOLS_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_CLASS_PROTOCOLS_$_AVMetadataLightSourceEstimationObject
+ __OBJC_CLASS_RO_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_CLASS_RO_$_AVMetadataLightSourceEstimationObject
+ __OBJC_METACLASS_RO_$_AVMetadataDeviceProximityDetectionObject
+ __OBJC_METACLASS_RO_$_AVMetadataLightSourceEstimationObject
+ ___100-[AVCaptureSession _tearDownV68ThirdPartyCompatibilityRotationCoordinatorIfUnusedForDeviceUniqueID:]_block_invoke
+ ___101-[AVCapturePersonalPhotographerSessionFinishCoordinator initWithInactivityTimeout:completionHandler:]_block_invoke
+ ___101-[AVCaptureSession _setUpAndUpdateV68ThirdPartyCompatibilityRotationAsynchronouslyIfNeededForDevice:]_block_invoke
+ ___135-[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]_block_invoke
+ ___135-[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]_block_invoke_2
+ ___135-[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]_block_invoke_3
+ ___135-[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]_block_invoke_4
+ ___135-[AVCaptureDeviceRotationCoordinator _initWithDevice:previewLayer:suppliesVideoRotationAngleForHorizonLevelPreviewWithoutPreviewLayer:]_block_invoke_5
+ ___73-[AVControlCenterModuleState _proprietaryDefaultChanged:keyPath:context:]_block_invoke_2
+ ___87-[AVCaptureProprietaryDefaultsSingleton migrateDefaultsFromAppBundleID:newAppBundleID:]_block_invoke
+ ___AVCaptureV68ThirdPartyCompatibilityEnabled_block_invoke
+ ___AVCaptureV68ThirdPartyCompatibilityShouldRotateVDO_block_invoke
+ ____personalizationStateForPosition_block_invoke
+ ___block_descriptor_40_e8_32o_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12ls32l8
+ ___block_descriptor_48_e8_32o40w_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12ls32l8w40l8
+ ___block_descriptor_64_e8_32o40o48o56r_e5_v8?0ls32l8r56l8s40l8s48l8
+ __personalizationStateForPosition.sPersonalizationStatesByPosition
+ __personalizationStateForPosition.sPersonalizationStatesByPositionOnceToken
+ _fvd_clampFrameDuration
+ _gAVCapturePersonalPhotographerSessionResultsTrace
+ _kFigCaptureSampleBufferAttachmentKey_DeviceProximityDetection
+ _kFigCaptureSampleBufferAttachmentKey_LightSourceEstimation
+ _kFigCaptureSessionDidFinishPersonalPhotographerSessionCaptureKey_PresentationTimestamp
+ _kFigCaptureSessionDidFinishPersonalPhotographerSessionCaptureKey_SettingsID
+ _kFigCaptureSessionWillBeginCaptureNotificationPayloadKey_PersonalPhotographerDuplicateInfo
+ _kFigCaptureStreamDetectedObjectKey_SentToPerceptionThumbnailChannel
+ _kFigCaptureStreamMetadata_LookingAtCameraConfidenceLevel
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_ConfidenceLevel
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_DeviceID
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_DeviceType
+ _kFigCaptureStreamSecureDetectedProximityDeviceKey_PoseMatrix
+ _kFigCaptureStreamSecureDetectedProximityDevicesKey_DevicesArray
- +[AVCaptureResolvedPhotoSettings resolvedSettingsWithUniqueID:photoDimensions:rawPhotoDimensions:previewDimensions:embeddedThumbnailDimensions:rawEmbeddedThumbnailDimensions:livePhotoMovieEnabled:livePhotoMovieDimensions:livePhotoAssetIdentifier:portraitEffectsMatteDimensions:hairSegmentationMatteDimensions:skinSegmentationMatteDimensions:teethSegmentationMatteDimensions:glassesSegmentationMatteDimensions:spatialOverCapturePhotoDimensions:turboModeEnabled:flashEnabled:redEyeReductionEnabled:HDREnabled:adjustedPhotoFiltersEnabled:EV0PhotoDeliveryEnabled:stillImageStabilizationEnabled:virtualDeviceFusionEnabled:squareCropEnabled:deferredPhotoProxyDimensions:photoProcessingTimeRange:contentAwareDistortionCorrectionEnabled:spatialPhotoCaptureEnabled:photoManifest:digitalFlashUserInterfaceHints:digitalFlashUserInterfaceRGBEstimate:captureBeforeResolvingSettingsEnabled:secureSigningPhotoCapturePhotoEnabled:]
- -[AVCaptureMovieFileOutput _updateBravoCameraSelectionBehaviorForSourceDevice:]
- -[AVCapturePersonalPhotographerSessionFinishCoordinator _addExpectedTimestamp:]
- -[AVCapturePersonalPhotographerSessionFinishCoordinator finishWithRequest:expectedTimestamps:error:]
- -[AVCapturePersonalPhotographerSessionFinishCoordinator initWithCompletionHandler:]
- -[AVCapturePersonalPhotographerSessionFinishCoordinator recordStillCompleteForSettingsID:timestamp:]
- -[AVCapturePersonalPhotographerSessionResults _isPhotoRegisteredWithTimestampNSValue:]
- -[AVCapturePersonalPhotographerSessionResults isPhotoRegisteredForDeletionWithTimestamp:]
- -[AVCapturePersonalPhotographerSessionResults isPhotoRegisteredWithTimestamp:]
- -[AVCapturePersonalPhotographerSessionResults registerPhotoCapturedWithTimestamp:]
- -[AVCapturePersonalPhotographerSessionResults registerPhotoTimestampForDeletion:]
- -[AVCaptureResolvedPhotoSettings _initWithUniqueID:photoDimensions:rawPhotoDimensions:previewDimensions:embeddedThumbnailDimensions:rawEmbeddedThumbnailDimensions:livePhotoMovieEnabled:livePhotoMovieDimensions:livePhotoAssetIdentifier:portraitEffectsMatteDimensions:hairSegmentationMatteDimensions:skinSegmentationMatteDimensions:teethSegmentationMatteDimensions:glassesSegmentationMatteDimensions:spatialOverCapturePhotoDimensions:turboModeEnabled:flashEnabled:redEyeReductionEnabled:HDREnabled:adjustedPhotoFiltersEnabled:EV0PhotoDeliveryEnabled:stillImageStabilizationEnabled:virtualDeviceFusionEnabled:squareCropEnabled:deferredPhotoProxyDimensions:photoProcessingTimeRange:contentAwareDistortionCorrectionEnabled:spatialPhotoCaptureEnabled:photoManifest:digitalFlashUserInterfaceHints:digitalFlashUserInterfaceRGBEstimate:captureBeforeResolvingSettingsEnabled:secureSigningPhotoCapturePhotoEnabled:]
- -[AVControlCenterModuleState ringLightAutoColorEnabled]
- -[AVControlCenterModuleState ringLightRecommendedColor]
- -[AVControlCenterModuleState setRingLightAutoColorEnabled:]
- GCC_except_table100
- GCC_except_table1023
- GCC_except_table1029
- GCC_except_table1037
- GCC_except_table1047
- GCC_except_table112
- GCC_except_table131
- GCC_except_table136
- GCC_except_table139
- GCC_except_table147
- GCC_except_table148
- GCC_except_table149
- GCC_except_table150
- GCC_except_table161
- GCC_except_table163
- GCC_except_table165
- GCC_except_table169
- GCC_except_table170
- GCC_except_table178
- GCC_except_table181
- GCC_except_table182
- GCC_except_table189
- GCC_except_table191
- GCC_except_table2
- GCC_except_table205
- GCC_except_table206
- GCC_except_table207
- GCC_except_table215
- GCC_except_table217
- GCC_except_table228
- GCC_except_table229
- GCC_except_table230
- GCC_except_table233
- GCC_except_table234
- GCC_except_table239
- GCC_except_table250
- GCC_except_table265
- GCC_except_table274
- GCC_except_table280
- GCC_except_table289
- GCC_except_table30
- GCC_except_table306
- GCC_except_table309
- GCC_except_table315
- GCC_except_table318
- GCC_except_table339
- GCC_except_table345
- GCC_except_table350
- GCC_except_table351
- GCC_except_table355
- GCC_except_table358
- GCC_except_table362
- GCC_except_table369
- GCC_except_table385
- GCC_except_table388
- GCC_except_table394
- GCC_except_table403
- GCC_except_table424
- GCC_except_table435
- GCC_except_table448
- GCC_except_table464
- GCC_except_table487
- GCC_except_table497
- GCC_except_table509
- GCC_except_table52
- GCC_except_table529
- GCC_except_table532
- GCC_except_table557
- GCC_except_table558
- GCC_except_table562
- GCC_except_table575
- GCC_except_table583
- GCC_except_table591
- GCC_except_table597
- GCC_except_table602
- GCC_except_table609
- GCC_except_table616
- GCC_except_table626
- GCC_except_table640
- GCC_except_table663
- GCC_except_table674
- GCC_except_table684
- GCC_except_table698
- GCC_except_table708
- GCC_except_table720
- GCC_except_table739
- GCC_except_table760
- GCC_except_table763
- GCC_except_table800
- GCC_except_table802
- GCC_except_table804
- GCC_except_table806
- GCC_except_table833
- GCC_except_table845
- GCC_except_table847
- GCC_except_table849
- GCC_except_table855
- GCC_except_table857
- GCC_except_table900
- GCC_except_table904
- GCC_except_table971
- GCC_except_table973
- GCC_except_table975
- GCC_except_table977
- _AVCaptureSessionVideoInputDeviceVideoZoomFactorChangedContext
- _AVControlCenterVideoEffectsModuleGetDisplayRingLightColorForBundleID
- _AVControlCenterVideoEffectsModuleGetDisplayRingLightRecommendedNitsFloorForBundleID
- _AVControlCenterVideoEffectsModuleGetRingLightColorRecommendationEnabledForBundleID
- _AVControlCenterVideoEffectsModuleSetDisplayRingLightColorForBundleID
- _AVControlCenterVideoEffectsModuleSetRingLightColorRecommendationEnabledForBundleID
- _AVControlCenterVideoEffectsRingLightAutoColorEnabledPreferenceKey
- _AVControlCenterVideoEffectsRingLightBiasPreferenceKey
- _AVControlCenterVideoEffectsRingLightRecommendedColorPreferenceKey
- _FigCaptureProprietaryDefaultsRingLightAutoColorEnabledKey
- _FigCaptureProprietaryDefaultsRingLightBiasKey
- _FigCaptureProprietaryDefaultsRingLightRecommendedColorKey
- _FigCaptureRingLightAutoColorEnabledDefault
- _FigCaptureRingLightBiasDefault
- _FigCaptureRingLightRecommendedColorDefault
- _FigCaptureShaderPreloadingInProgress
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionFinishCoordinator._expectedSetOfTimestampsCommitted
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionFinishCoordinator._settingsIDByTimestamp
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionFinishCoordinator._unmappedExpectedTimestamps
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._capturedPhotos
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._systemRecommendedPhotosToDeleteByTimestamp
- _OBJC_IVAR_$_AVCapturePersonalPhotographerSessionResults._systemRecommendedPhotosToSaveByTimestamp
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightAutoColorEnabled
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightAutoColorEnabledKey
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightBias
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightBiasKey
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightRecommendedColor
- _OBJC_IVAR_$_AVControlCenterModuleState._ringLightRecommendedColorKey
- ___64-[AVControlCenterModuleState installProprietaryDefaultsHandlers]_block_invoke_39
- ___64-[AVControlCenterModuleState installProprietaryDefaultsHandlers]_block_invoke_40
- ___64-[AVControlCenterModuleState installProprietaryDefaultsHandlers]_block_invoke_41
- ___66-[AVCaptureDeviceRotationCoordinator initWithDevice:previewLayer:]_block_invoke
- ___66-[AVCaptureDeviceRotationCoordinator initWithDevice:previewLayer:]_block_invoke_2
- ___66-[AVCaptureDeviceRotationCoordinator initWithDevice:previewLayer:]_block_invoke_3
- ___66-[AVCaptureDeviceRotationCoordinator initWithDevice:previewLayer:]_block_invoke_4
- ___66-[AVCaptureDeviceRotationCoordinator initWithDevice:previewLayer:]_block_invoke_5
- ___67-[AVCaptureFigVideoDevice setExposureTargetBias:completionHandler:]_block_invoke_2
- ___83-[AVCapturePersonalPhotographerSessionFinishCoordinator initWithCompletionHandler:]_block_invoke
- ___block_descriptor_40_e8_32o_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12ls32l8
- ___block_descriptor_48_e8_32o40w_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12ls32l8w40l8
- ___block_descriptor_53_e8_32o40r_e5_v8?0ls32l8r40l8
```
