## PhotoImaging

> `/System/Library/PrivateFrameworks/PhotoImaging.framework/PhotoImaging`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x29bdd0
+916.57.154.0.0
+  __TEXT.__text: 0x2a1b84
   __TEXT.__delay_helper: 0x1f4
-  __TEXT.__objc_methlist: 0x173c8
-  __TEXT.__const: 0x8d04
+  __TEXT.__objc_methlist: 0x175c8
+  __TEXT.__const: 0x8d54
   __TEXT.__dlopen_cstrs: 0x2a2
-  __TEXT.__swift5_typeref: 0x2d8
-  __TEXT.__cstring: 0x4a6de
   __TEXT.__constg_swiftt: 0x230
-  __TEXT.__swift5_reflstr: 0x35f
-  __TEXT.__swift5_fieldmd: 0x3d4
+  __TEXT.__swift5_typeref: 0x34e
   __TEXT.__swift5_builtin: 0x78
-  __TEXT.__swift5_mpenum: 0x8
+  __TEXT.__swift5_reflstr: 0x38f
+  __TEXT.__swift5_fieldmd: 0x3ec
   __TEXT.__swift5_assocty: 0x90
-  __TEXT.__oslogstring: 0x7d58
+  __TEXT.__swift5_capture: 0x8c
   __TEXT.__swift5_proto: 0xa0
   __TEXT.__swift5_types: 0x38
-  __TEXT.__swift_as_entry: 0x14
-  __TEXT.__swift_as_ret: 0x14
-  __TEXT.__swift_as_cont: 0x28
-  __TEXT.__swift5_capture: 0x50
-  __TEXT.__gcc_except_tab: 0x4ee0
-  __TEXT.__unwind_info: 0x5c58
-  __TEXT.__eh_frame: 0xa50
+  __TEXT.__swift_as_entry: 0x1c
+  __TEXT.__swift_as_ret: 0x1c
+  __TEXT.__swift_as_cont: 0x34
+  __TEXT.__cstring: 0x4aef6
+  __TEXT.__swift5_mpenum: 0x8
+  __TEXT.__oslogstring: 0x8054
+  __TEXT.__gcc_except_tab: 0x4f0c
+  __TEXT.__unwind_info: 0x5d90
+  __TEXT.__eh_frame: 0xb90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x44d0
-  __DATA_CONST.__objc_classlist: 0x11a0
-  __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x1a0
+  __DATA_CONST.__const: 0x4550
+  __DATA_CONST.__objc_classlist: 0x11e0
+  __DATA_CONST.__objc_catlist: 0x50
+  __DATA_CONST.__objc_protolist: 0x1a8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbca0
+  __DATA_CONST.__objc_selrefs: 0xbdd0
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x750
-  __DATA_CONST.__objc_arraydata: 0x9718
-  __DATA_CONST.__got: 0x2830
-  __AUTH_CONST.__const: 0x5648
-  __AUTH_CONST.__cfstring: 0x29bc0
-  __AUTH_CONST.__objc_const: 0x29ad0
+  __DATA_CONST.__objc_superrefs: 0x778
+  __DATA_CONST.__objc_arraydata: 0x8fb8
+  __DATA_CONST.__got: 0x2878
+  __AUTH_CONST.__const: 0x57a0
+  __AUTH_CONST.__cfstring: 0x29c00
+  __AUTH_CONST.__objc_const: 0x2a3b0
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x1668
-  __AUTH_CONST.__objc_dictobj: 0x5c58
-  __AUTH_CONST.__objc_doubleobj: 0xe10
-  __AUTH_CONST.__objc_arrayobj: 0x6c0
-  __AUTH_CONST.__objc_floatobj: 0xd0
-  __AUTH_CONST.__auth_got: 0x1508
-  __AUTH_CONST.__auth_ptr: 0x2f0
-  __AUTH.__objc_data: 0x968
-  __DATA.__objc_ivar: 0x1600
-  __DATA.__data: 0x17f8
-  __DATA.__bss: 0x1a80
-  __DATA_DIRTY.__objc_data: 0xa890
-  __DATA_DIRTY.__data: 0x178
-  __DATA_DIRTY.__bss: 0x258
+  __AUTH_CONST.__objc_intobj: 0x1638
+  __AUTH_CONST.__objc_dictobj: 0x55f0
+  __AUTH_CONST.__objc_doubleobj: 0xdf0
+  __AUTH_CONST.__objc_arrayobj: 0x708
+  __AUTH_CONST.__objc_floatobj: 0xb0
+  __AUTH_CONST.__auth_got: 0x1610
+  __AUTH_CONST.__auth_ptr: 0x300
+  __AUTH.__objc_data: 0x3c0
+  __DATA.__objc_ivar: 0x1624
+  __DATA.__data: 0x444
+  __DATA.__bss: 0x1b20
+  __DATA_DIRTY.__objc_data: 0xb0b8
+  __DATA_DIRTY.__data: 0x1598
+  __DATA_DIRTY.__bss: 0x1e8
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9495
-  Symbols:   16415
+  Functions: 9575
+  Symbols:   16535
   CStrings:  0
 
Symbols:
+ +[NUAssetCapability(PIAudioMix) audioMix]
+ +[NUAssetCapability(PICinematicVideo) cinematicVideo]
+ +[NUAssetCapability(PIPhotographicStyle) photographicStyle]
+ +[NUAssetCapability(PIPortrait) portrait]
+ +[PICinematicVideoUtilities disparityProviderWithQuality:globalRenderingMetadata:inputSize:error:]
+ +[PICleanup cleanupAdjustmentDescriptor]
+ +[PIDefinition_v1 adjustmentDescriptor]
+ +[PIGlobalSettings photosAppEditSettings]
+ +[PIGrain_v1 adjustmentDescriptor]
+ +[PIHighResolutionFusion_v1 adjustmentDescriptor]
+ +[PILevels_v1 adjustmentDescriptor]
+ +[PILivePhotoEffect_v1 adjustmentDescriptor]
+ +[PILivePhotoEffect_v1 flavorDescriptor]
+ +[PILivePhotoEffect_v1 recipeDescriptor]
+ +[PIModularPhotosPipeline_v0 controlDataWithPortraitEffectAdjustment:descriptor:]
+ +[PIModularPhotosPipeline_v0 controlDataWithSemanticStyleAdjustment:]
+ +[PIModularPhotosPipeline_v1 controlDataWithSemanticStyleAdjustment:textureStyleAdjustment:]
+ +[PINoiseReduction_v1 adjustmentDescriptor]
+ +[PIObjectRemoval _instancesForGenerativeEditOperation:context:]
+ +[PIObjectRemoval _nonInstancedOperationsFromComposition:context:]
+ +[PIObjectRemoval _tightImageSpaceBoundsForGenerativeEditOperation:composition:context:error:]
+ +[PIPhotographicStyle adjustmentDescriptor]
+ +[PIPhotographicStyle adjustmentFormat]
+ +[PIPhotographicStyle castDescriptor]
+ +[PIPhotographicStyle connectPhotographicStyleToPipeline:stylePipeline:primaryInput:adjustmentInput:assetMedia:isVideo:]
+ +[PIPhotographicStyleApply pipelineName]
+ +[PIPhotographicStyleCapability setLivePhotoVideoPhotographicStyleCapability:imageVersion:]
+ +[PIPhotographicStyleLearn pipelineName]
+ +[PIPhotosPipeline pipelineName]
+ +[PIPortrait depthEffectDescriptorForAsset:]
+ +[PIPortrait effectForFilterKind:error:]
+ +[PIPortrait lightingEffectDescriptorForAsset:]
+ +[PIPortrait portraitSettingsDescriptorForAsset:]
+ +[PIPortrait versionedClassForAsset:]
+ +[PIPortrait_v1 filterKindForEffect:error:]
+ +[PIPortrait_v1 portraitSettingsExpressionFunctionClass]
+ +[PIPortrait_v2 filterKindForEffect:error:]
+ +[PIPortrait_v2 lightingEffectAdjustmentDescriptor]
+ +[PIPortrait_v2 portraitSettingsAdjustmentDescriptor]
+ +[PIPortrait_v2 portraitSettingsExpressionFunctionClass]
+ +[PIPrivatePhotosPipeline pipelineName]
+ +[PIRedEye_v1 adjustmentDescriptor]
+ +[PISegmentationLoader _baseLayoutForDisplayContext:ofItem:spatialPhotoEnabled:settlingEffectEnabled:]
+ +[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:displayContext:completion:]
+ +[PISegmentationLoader adoptDynamicLayoutConfiguration:forSegmentationItem:]
+ +[PISegmentationLoader renderPreviewLayerStackFromWallpaperURL:styleCategory:displayContext:completion:]
+ +[PISharpen_v1 adjustmentDescriptor]
+ +[PISmartBlackAndWhite_v1 adjustmentDescriptor]
+ +[PISmartColor_v1 adjustmentDescriptor]
+ +[PISmartCopyPaste pasteAdjustmentDescriptor]
+ +[PISmartTone_v1 adjustmentDescriptor]
+ +[PISmartTone_v1 statisticsDescriptor]
+ +[PISpatialReframe adjustmentDescriptor]
+ +[PIVignette_v1 adjustmentDescriptor]
+ -[PIADMCleanup pipelineName]
+ -[PIADMOutfill pipelineName]
+ -[PIAudioMix_v1 pipelineName]
+ -[PICinematicVideo_v1 pipelineName]
+ -[PICinematicVideo_v2 pipelineName]
+ -[PICleanup pipelineName]
+ -[PICropStraightenAuto_v1 pipelineName]
+ -[PICropStraighten_v1 pipelineName]
+ -[PICurves_v1 pipelineName]
+ -[PIDefinition_v1 pipelineName]
+ -[PIFilterEffect_v1 pipelineName]
+ -[PIGANCleanup pipelineName]
+ -[PIGenerativeEdits pipelineName]
+ -[PIGlobalSettings generativeSeed]
+ -[PIGlobalSettings outfillSafetyEnabled]
+ -[PIGlobalSettings outfillSafetyThreshold]
+ -[PIGlobalSettings setGenerativeSeed:]
+ -[PIGrain_v1 pipelineName]
+ -[PIHighResolutionFusion_v1 pipelineName]
+ -[PIInpaintMaskContext setRequestID:]
+ -[PILevels_v1 pipelineName]
+ -[PILivePhotoEffect_v1 pipelineName]
+ -[PILivePhotoKeyFrame_v1 pipelineName]
+ -[PIManualRedEye_v1 pipelineName]
+ -[PIMute_v1 pipelineName]
+ -[PINoiseReduction_v1 pipelineName]
+ -[PIOrientation_v1 pipelineName]
+ -[PIOutfillPlaceholder pipelineName]
+ -[PIParallaxSegmentationItem needsOutfillSafeEdgesCheck]
+ -[PIPhotographicStyle .cxx_destruct]
+ -[PIPhotographicStyle _versionedClassForAsset:]
+ -[PIPhotographicStyle asset]
+ -[PIPhotographicStyle buildPipeline:error:]
+ -[PIPhotographicStyle initWithAsset:options:]
+ -[PIPhotographicStyle init]
+ -[PIPhotographicStyle options]
+ -[PIPhotographicStyle versionedClassForAsset:]
+ -[PIPhotographicStyleApply _versionedClassForAsset:]
+ -[PIPhotographicStyleApply initWithAsset:options:]
+ -[PIPhotographicStyleApply pipelineName]
+ -[PIPhotographicStyleApplyV1 pipelineName]
+ -[PIPhotographicStyleApplyV2 pipelineName]
+ -[PIPhotographicStyleCapability evaluateForAsset:]
+ -[PIPhotographicStyleLearn _versionedClassForAsset:]
+ -[PIPhotographicStyleLearn initWithAsset:options:]
+ -[PIPhotographicStyleLearn pipelineName]
+ -[PIPhotographicStyleLearnV1 pipelineName]
+ -[PIPhotographicStyleLearnV2 pipelineName]
+ -[PIPhotosPipeline pipelineIsOpaque]
+ -[PIPhotosPipeline pipelineName]
+ -[PIPhotosPipeline_v1 _buildPostGeometryPipeline:media:error:]
+ -[PIPipelineModule pipelineName]
+ -[PIPlaybackRate_v1 pipelineName]
+ -[PIPortrait .cxx_destruct]
+ -[PIPortrait asset]
+ -[PIPortrait buildPipeline:error:]
+ -[PIPortrait hasOption:]
+ -[PIPortrait initWithAsset:options:]
+ -[PIPortrait options]
+ -[PIPortrait pipelineName]
+ -[PIPortraitLightingEffectV1Processor outputImageWithInputs:controlData:error:]
+ -[PIPortraitSettingsExpressionFunction_v2 format]
+ -[PIPortrait_v1 pipelineName]
+ -[PIPosterOutfillSafetyRequest copyWithZone:]
+ -[PIPosterOutfillSafetyRequest initWithSegmentationItem:]
+ -[PIPosterOutfillSafetyRequest initWithSegmentationItem:threshold:]
+ -[PIPosterOutfillSafetyRequest mediaComponentType]
+ -[PIPosterOutfillSafetyRequest submit:]
+ -[PIPosterOutfillSafetyRequest threshold]
+ -[PIPrivatePhotosPipeline_v0 _addVideoPosterFramePipeline:sourceMedia:outputMedia:videoPosterFrameTime:]
+ -[PIPrivatePhotosPipeline_v0 buildFiltersGroupPipeline:temporality:outputMediaFormat:error:]
+ -[PIPrivatePhotosPipeline_v0 buildFiltersPipeline:format:temporality:connections:error:]
+ -[PIPrivatePhotosPipeline_v1 _addVideoPosterFramePipeline:sourceMedia:outputMedia:videoPosterFrameTime:]
+ -[PIPrivatePhotosPipeline_v1 buildFiltersGroupPipeline:temporality:outputMediaFormat:error:]
+ -[PIPrivatePhotosPipeline_v1 buildFiltersPipeline:format:temporality:connections:error:]
+ -[PIRedEye_v1 pipelineName]
+ -[PIRetouchCleanup pipelineName]
+ -[PISegmentationLoader _checkOutfillSafeEdges:completion:]
+ -[PISelectiveColor_v1 pipelineName]
+ -[PISemanticStyleThumbnailApply pipelineName]
+ -[PISharpen_v1 pipelineName]
+ -[PISlowMotion_v1 pipelineName]
+ -[PISmartBlackAndWhite_v1 pipelineName]
+ -[PISmartColor_v1 pipelineName]
+ -[PISmartCopyPaste pipelineName]
+ -[PISmartToneAuto_v1 pipelineName]
+ -[PISmartTone_v1 pipelineName]
+ -[PISpatialReframe pipelineName]
+ -[PITextureStyle pipelineName]
+ -[PITextureStylePipelineProcessor copyWithZone:]
+ -[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:requiresPersonData:]
+ -[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:requiresPersonData:requiresSemanticStyleProperties:]
+ -[PITextureStyleUsageInputConfiguration requiresSemanticStyleProperties]
+ -[PITrim_v1 pipelineName]
+ -[PIVignette_v1 pipelineName]
+ -[PIWhiteBalanceAuto_v1 pipelineName]
+ -[PIWhiteBalance_v1 pipelineName]
+ -[_PIAudioMixCapability evaluateForAsset:]
+ -[_PICinematicVideoCapability _evaluateCinematicCapabilityWithAsset:]
+ -[_PICinematicVideoCapability evaluateForAsset:]
+ -[_PIGrayColorPipelineBuilder pipelineName]
+ -[_PIParallaxCompoundLayerStackResult partialFailureError]
+ -[_PIParallaxCompoundLayerStackResult setPartialFailureError:]
+ -[_PIPhotographicStyleSettingsExpressionFunction evaluateWithArguments:error:]
+ -[_PIPhotographicStyleSettingsExpressionFunction format]
+ -[_PIPortraitCapability _evaluateForImageAsset:]
+ -[_PIPortraitCapability _evaluateForLivePhotoAsset:]
+ -[_PIPortraitCapability evaluateForAsset:]
+ -[_PIPosterOutfillSafetyResult .cxx_destruct]
+ -[_PIPosterOutfillSafetyResult initWithSafeEdges:]
+ -[_PIPosterOutfillSafetyResult safeEdges]
+ -[_PIRAWFaceBalanceAutoProcessor copyWithZone:]
+ GCC_except_table1137
+ GCC_except_table1739
+ GCC_except_table1753
+ GCC_except_table1923
+ GCC_except_table2097
+ GCC_except_table2250
+ GCC_except_table2260
+ GCC_except_table2266
+ GCC_except_table2274
+ GCC_except_table2281
+ GCC_except_table2289
+ GCC_except_table2367
+ GCC_except_table2407
+ GCC_except_table2436
+ GCC_except_table2441
+ GCC_except_table2472
+ GCC_except_table2477
+ GCC_except_table2483
+ GCC_except_table2570
+ GCC_except_table2805
+ GCC_except_table3159
+ GCC_except_table316
+ GCC_except_table3164
+ GCC_except_table3194
+ GCC_except_table3198
+ GCC_except_table3200
+ GCC_except_table3201
+ GCC_except_table3203
+ GCC_except_table3205
+ GCC_except_table3207
+ GCC_except_table3213
+ GCC_except_table3218
+ GCC_except_table3227
+ GCC_except_table3322
+ GCC_except_table3391
+ GCC_except_table3392
+ GCC_except_table3501
+ GCC_except_table3543
+ GCC_except_table3551
+ GCC_except_table3603
+ GCC_except_table3797
+ GCC_except_table3917
+ GCC_except_table3927
+ GCC_except_table3930
+ GCC_except_table3931
+ GCC_except_table394
+ GCC_except_table3943
+ GCC_except_table3990
+ GCC_except_table3999
+ GCC_except_table4027
+ GCC_except_table4051
+ GCC_except_table4279
+ GCC_except_table4451
+ GCC_except_table4540
+ GCC_except_table4641
+ GCC_except_table4665
+ GCC_except_table4669
+ GCC_except_table4788
+ GCC_except_table4831
+ GCC_except_table4833
+ GCC_except_table4857
+ GCC_except_table4879
+ GCC_except_table4983
+ GCC_except_table5040
+ GCC_except_table507
+ GCC_except_table5080
+ GCC_except_table5274
+ GCC_except_table5297
+ GCC_except_table5304
+ GCC_except_table5307
+ GCC_except_table5318
+ GCC_except_table5325
+ GCC_except_table5471
+ GCC_except_table5563
+ GCC_except_table5624
+ GCC_except_table5627
+ GCC_except_table5639
+ GCC_except_table5640
+ GCC_except_table5644
+ GCC_except_table5645
+ GCC_except_table5646
+ GCC_except_table5651
+ GCC_except_table5659
+ GCC_except_table5752
+ GCC_except_table6146
+ GCC_except_table6165
+ GCC_except_table6166
+ GCC_except_table6172
+ GCC_except_table6177
+ GCC_except_table6229
+ GCC_except_table6235
+ GCC_except_table6245
+ GCC_except_table6247
+ GCC_except_table6271
+ GCC_except_table6273
+ GCC_except_table6274
+ GCC_except_table6275
+ GCC_except_table6277
+ GCC_except_table6281
+ GCC_except_table6284
+ GCC_except_table6287
+ GCC_except_table6289
+ GCC_except_table6290
+ GCC_except_table6291
+ GCC_except_table6292
+ GCC_except_table6294
+ GCC_except_table6299
+ GCC_except_table6332
+ GCC_except_table6435
+ GCC_except_table6438
+ GCC_except_table6445
+ GCC_except_table6503
+ GCC_except_table6577
+ GCC_except_table6898
+ GCC_except_table7146
+ GCC_except_table7147
+ GCC_except_table7239
+ GCC_except_table7242
+ GCC_except_table7246
+ GCC_except_table7247
+ GCC_except_table7251
+ GCC_except_table7252
+ GCC_except_table7254
+ GCC_except_table7260
+ GCC_except_table7269
+ GCC_except_table7285
+ GCC_except_table7389
+ GCC_except_table7390
+ GCC_except_table7391
+ GCC_except_table7392
+ GCC_except_table7426
+ GCC_except_table7429
+ GCC_except_table7497
+ GCC_except_table7507
+ GCC_except_table7664
+ GCC_except_table7666
+ GCC_except_table7760
+ GCC_except_table7766
+ GCC_except_table7769
+ GCC_except_table7771
+ GCC_except_table7772
+ GCC_except_table7773
+ GCC_except_table7774
+ GCC_except_table7776
+ GCC_except_table7779
+ GCC_except_table778
+ GCC_except_table7780
+ GCC_except_table7781
+ GCC_except_table7782
+ GCC_except_table7784
+ GCC_except_table7785
+ GCC_except_table7787
+ GCC_except_table7788
+ GCC_except_table7789
+ GCC_except_table7845
+ GCC_except_table7867
+ GCC_except_table7868
+ GCC_except_table7869
+ GCC_except_table789
+ GCC_except_table7904
+ GCC_except_table7905
+ GCC_except_table7908
+ GCC_except_table7911
+ GCC_except_table7956
+ GCC_except_table7958
+ GCC_except_table799
+ GCC_except_table8102
+ GCC_except_table8112
+ GCC_except_table8119
+ GCC_except_table8120
+ GCC_except_table8121
+ GCC_except_table8122
+ GCC_except_table8123
+ GCC_except_table8124
+ GCC_except_table8125
+ GCC_except_table8169
+ GCC_except_table830
+ GCC_except_table8356
+ GCC_except_table8579
+ GCC_except_table8581
+ GCC_except_table8582
+ GCC_except_table8643
+ GCC_except_table8645
+ GCC_except_table8647
+ GCC_except_table8715
+ GCC_except_table8738
+ GCC_except_table8740
+ GCC_except_table8743
+ GCC_except_table8747
+ GCC_except_table8749
+ GCC_except_table8782
+ GCC_except_table8790
+ GCC_except_table8794
+ GCC_except_table8795
+ GCC_except_table8803
+ GCC_except_table8813
+ GCC_except_table8814
+ GCC_except_table8817
+ GCC_except_table8819
+ GCC_except_table8823
+ GCC_except_table8825
+ GCC_except_table8826
+ GCC_except_table8838
+ GCC_except_table893
+ GCC_except_table896
+ GCC_except_table897
+ _NUChannelNameAlternate
+ _OBJC_CLASS_$_NUAssetCapability
+ _OBJC_CLASS_$_PIPhotographicStyle
+ _OBJC_CLASS_$_PIPhotographicStyleApply
+ _OBJC_CLASS_$_PIPhotographicStyleCapability
+ _OBJC_CLASS_$_PIPhotographicStyleLearn
+ _OBJC_CLASS_$_PIPortrait
+ _OBJC_CLASS_$_PIPortraitSettingsExpressionFunction_v2
+ _OBJC_CLASS_$_PIPosterOutfillSafetyRequest
+ _OBJC_CLASS_$__PIAudioMixCapability
+ _OBJC_CLASS_$__PICinematicVideoCapability
+ _OBJC_CLASS_$__PIPhotographicStyleSettingsExpressionFunction
+ _OBJC_CLASS_$__PIPortraitCapability
+ _OBJC_CLASS_$__PIPosterOutfillSafetyResult
+ _OBJC_IVAR_$_PIParallaxCompoundLayerStackRequest._partialFailureError
+ _OBJC_IVAR_$_PIParallaxSegmentationItem._outfillSafeEdges
+ _OBJC_IVAR_$_PIPhotographicStyle._asset
+ _OBJC_IVAR_$_PIPhotographicStyle._options
+ _OBJC_IVAR_$_PIPortrait._asset
+ _OBJC_IVAR_$_PIPortrait._options
+ _OBJC_IVAR_$_PIPosterOutfillSafetyRequest._threshold
+ _OBJC_IVAR_$_PITextureStyleUsageInputConfiguration._requiresSemanticStyleProperties
+ _OBJC_IVAR_$__PIParallaxCompoundLayerStackResult._partialFailureError
+ _OBJC_IVAR_$__PIPosterOutfillSafetyResult._safeEdges
+ _OBJC_METACLASS_$_NUAssetCapability
+ _OBJC_METACLASS_$_PIPhotographicStyle
+ _OBJC_METACLASS_$_PIPhotographicStyleApply
+ _OBJC_METACLASS_$_PIPhotographicStyleCapability
+ _OBJC_METACLASS_$_PIPhotographicStyleLearn
+ _OBJC_METACLASS_$_PIPortrait
+ _OBJC_METACLASS_$_PIPortraitSettingsExpressionFunction_v2
+ _OBJC_METACLASS_$_PIPosterOutfillSafetyRequest
+ _OBJC_METACLASS_$__PIAudioMixCapability
+ _OBJC_METACLASS_$__PICinematicVideoCapability
+ _OBJC_METACLASS_$__PIPhotographicStyleSettingsExpressionFunction
+ _OBJC_METACLASS_$__PIPortraitCapability
+ _OBJC_METACLASS_$__PIPosterOutfillSafetyResult
+ _PIAutoLoopStabilizedVideoGeometry
+ _PICinematicVideoVersionForAsset
+ _PIPhotographicStyleVersionForAsset
+ _PIPortraitVersionForAsset
+ __OBJC_$_CATEGORY_NUAssetCapability_$_PIPortrait
+ __OBJC_$_CLASS_METHODS_NUAssetCapability(PIPortrait|PIAudioMix|PICinematicVideo|PIPhotographicStyle)
+ __OBJC_$_CLASS_METHODS_PIPhotographicStyle
+ __OBJC_$_CLASS_METHODS_PIPhotographicStyleApply
+ __OBJC_$_CLASS_METHODS_PIPhotographicStyleCapability
+ __OBJC_$_CLASS_METHODS_PIPhotographicStyleLearn
+ __OBJC_$_CLASS_METHODS_PIPortrait
+ __OBJC_$_CLASS_METHODS_PIPortrait_v2
+ __OBJC_$_CLASS_PROP_LIST_PIPhotographicStyle
+ __OBJC_$_CLASS_PROP_LIST_PIPhotographicStyleApply
+ __OBJC_$_CLASS_PROP_LIST_PIPhotographicStyleLearn
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyle
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyleApply
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyleCapability
+ __OBJC_$_INSTANCE_METHODS_PIPhotographicStyleLearn
+ __OBJC_$_INSTANCE_METHODS_PIPortrait
+ __OBJC_$_INSTANCE_METHODS_PIPortraitSettingsExpressionFunction_v2
+ __OBJC_$_INSTANCE_METHODS_PIPosterOutfillSafetyRequest(Guardrail)
+ __OBJC_$_INSTANCE_METHODS__PIAudioMixCapability
+ __OBJC_$_INSTANCE_METHODS__PICinematicVideoCapability
+ __OBJC_$_INSTANCE_METHODS__PIPhotographicStyleSettingsExpressionFunction
+ __OBJC_$_INSTANCE_METHODS__PIPortraitCapability
+ __OBJC_$_INSTANCE_METHODS__PIPosterOutfillSafetyResult
+ __OBJC_$_INSTANCE_VARIABLES_PIPhotographicStyle
+ __OBJC_$_INSTANCE_VARIABLES_PIPortrait
+ __OBJC_$_INSTANCE_VARIABLES_PIPosterOutfillSafetyRequest
+ __OBJC_$_INSTANCE_VARIABLES__PIPosterOutfillSafetyResult
+ __OBJC_$_PROP_LIST_PIPhotographicStyle
+ __OBJC_$_PROP_LIST_PIPortrait
+ __OBJC_$_PROP_LIST_PIPosterOutfillSafetyRequest
+ __OBJC_$_PROP_LIST_PIPosterOutfillSafetyResult
+ __OBJC_$_PROP_LIST__PIPosterOutfillSafetyResult
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NUPipelineBuilder
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PIPosterOutfillSafetyResult
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PIPosterOutfillSafetyResult
+ __OBJC_$_PROTOCOL_REFS_PIPosterOutfillSafetyResult
+ __OBJC_CLASS_PROTOCOLS_$_PIPhotographicStyle
+ __OBJC_CLASS_PROTOCOLS_$_PIPortrait
+ __OBJC_CLASS_PROTOCOLS_$__PIPosterOutfillSafetyResult
+ __OBJC_CLASS_RO_$_PIPhotographicStyle
+ __OBJC_CLASS_RO_$_PIPhotographicStyleApply
+ __OBJC_CLASS_RO_$_PIPhotographicStyleCapability
+ __OBJC_CLASS_RO_$_PIPhotographicStyleLearn
+ __OBJC_CLASS_RO_$_PIPortrait
+ __OBJC_CLASS_RO_$_PIPortraitSettingsExpressionFunction_v2
+ __OBJC_CLASS_RO_$_PIPosterOutfillSafetyRequest
+ __OBJC_CLASS_RO_$__PIAudioMixCapability
+ __OBJC_CLASS_RO_$__PICinematicVideoCapability
+ __OBJC_CLASS_RO_$__PIPhotographicStyleSettingsExpressionFunction
+ __OBJC_CLASS_RO_$__PIPortraitCapability
+ __OBJC_CLASS_RO_$__PIPosterOutfillSafetyResult
+ __OBJC_LABEL_PROTOCOL_$_PIPosterOutfillSafetyResult
+ __OBJC_METACLASS_RO_$_PIPhotographicStyle
+ __OBJC_METACLASS_RO_$_PIPhotographicStyleApply
+ __OBJC_METACLASS_RO_$_PIPhotographicStyleCapability
+ __OBJC_METACLASS_RO_$_PIPhotographicStyleLearn
+ __OBJC_METACLASS_RO_$_PIPortrait
+ __OBJC_METACLASS_RO_$_PIPortraitSettingsExpressionFunction_v2
+ __OBJC_METACLASS_RO_$_PIPosterOutfillSafetyRequest
+ __OBJC_METACLASS_RO_$__PIAudioMixCapability
+ __OBJC_METACLASS_RO_$__PICinematicVideoCapability
+ __OBJC_METACLASS_RO_$__PIPhotographicStyleSettingsExpressionFunction
+ __OBJC_METACLASS_RO_$__PIPortraitCapability
+ __OBJC_METACLASS_RO_$__PIPosterOutfillSafetyResult
+ __OBJC_PROTOCOL_$_PIPosterOutfillSafetyResult
+ ___104+[PISegmentationLoader renderPreviewLayerStackFromWallpaperURL:styleCategory:displayContext:completion:]_block_invoke
+ ___105+[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:displayContext:completion:]_block_invoke
+ ___105+[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:displayContext:completion:]_block_invoke_2
+ ___134-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:requiresPersonData:requiresSemanticStyleProperties:]_block_invoke
+ ___134-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:requiresPersonData:requiresSemanticStyleProperties:]_block_invoke_2
+ ___39-[PIPosterOutfillSafetyRequest submit:]_block_invoke
+ ___39-[PIPosterOutfillSafetyRequest submit:]_block_invoke_2
+ ___39-[PIPosterOutfillSafetyRequest submit:]_block_invoke_3
+ ___39-[PIPosterOutfillSafetyRequest submit:]_block_invoke_4
+ ___40+[PIPortrait effectForFilterKind:error:]_block_invoke
+ ___40+[PISpatialReframe adjustmentDescriptor]_block_invoke
+ ___43+[PIPortrait_v1 filterKindForEffect:error:]_block_invoke
+ ___43+[PIPortrait_v2 filterKindForEffect:error:]_block_invoke
+ ___45-[PISegmentationLoader _loadItem:completion:]_block_invoke_3
+ ___48-[PIParallaxSegmentationItem contentsDictionary]_block_invoke
+ ___58-[PISegmentationLoader _checkOutfillSafeEdges:completion:]_block_invoke
+ ___64+[PIObjectRemoval _instancesForGenerativeEditOperation:context:]_block_invoke
+ ___66+[PIObjectRemoval _nonInstancedOperationsFromComposition:context:]_block_invoke
+ ___66+[PIObjectRemoval _nonInstancedOperationsFromComposition:context:]_block_invoke_2
+ ___67-[PIPhotosPipeline_v0 buildPipeline:assetMedia:outputFormat:error:]_block_invoke_3
+ ___79-[PIPortraitLightingEffectV1Processor outputImageWithInputs:controlData:error:]_block_invoke
+ ___79-[PIPortraitLightingEffectV1Processor outputImageWithInputs:controlData:error:]_block_invoke_2
+ ___80+[PISegmentationLoader reloadSegmentationItemFromWallpaperURL:asset:completion:]_block_invoke_2
+ ___88-[PIPrivatePhotosPipeline_v0 buildFiltersPipeline:format:temporality:connections:error:]_block_invoke
+ ___88-[PIPrivatePhotosPipeline_v1 buildFiltersPipeline:format:temporality:connections:error:]_block_invoke
+ ___98+[PICinematicVideoUtilities disparityProviderWithQuality:globalRenderingMetadata:inputSize:error:]_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSNumber"8"NSNumber"16l
+ ___block_descriptor_40_e8_32bs_e27_v24?0"NSSet"8"NSError"16ls32l8
+ ___block_descriptor_44_e8_32r_e49_v16?0"PTDisparityProviderInitializationStatus"8lr32l8
+ ___block_descriptor_56_e8_32s40s48s_e29_v16?0"<NUMutablePipeline>"8ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40bs_e20_v16?0"NUResponse"8ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e44_"NUChannelPortRef"16?0"NUChannelPortRef"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs_e42_v24?0"<PISegmentationItem>"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e37_"NUChannelPortSpec"16?0"NSString"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e44_"NUChannelPortRef"16?0"NUChannelPortRef"8ls32l8s40l8s48l8s56l8
+ ___swift_memcpy90_8
+ __swiftEmptySetSingleton
+ _adjustmentDescriptor.descriptor
+ _adjustmentDescriptor.onceToken
+ _effectForFilterKind:error:.map
+ _effectForFilterKind:error:.onceToken
+ _filterKindForEffect:error:.map
+ _filterKindForEffect:error:.onceToken
+ _swift_release_x21
+ _swift_retain_x19
+ _swift_task_create
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic ShySo8NSNumberCG______pSgIeggg_ s5ErrorP
+ _symbolic So5NSSetCSo7NSErrorCSgIeyByy_
+ _symbolic So7CIImageC
+ _symbolic _____ySo8NSNumberCG s11_SetStorageC
+ _symbolic ytIeAgHr_
+ _type_layout_string So7CGPointV
- +[PIADMCleanup identifier]
- +[PIADMOutfill identifier]
- +[PIAssetLoader evaluateAssetCapabilities:]
- +[PIAssetLoader evaluateImageAssetCapabilities:]
- +[PIAssetLoader evaluateLivePhotoAssetCapabilities:]
- +[PIAssetLoader evaluateLivePhotoVideoAssetCapabilities:]
- +[PIAssetLoader evaluateVideoAssetCapabilities:]
- +[PIAssetLoader loadAsset:options:error:]
- +[PIAudioMix_v1 identifier]
- +[PICinematicVideo_v1 identifier]
- +[PICinematicVideo_v2 identifier]
- +[PICleanup cleanupAdjustmentSchema]
- +[PICropStraightenAuto_v1 identifier]
- +[PICropStraighten_v1 identifier]
- +[PIDefinition_v1 adjustmentSchema]
- +[PIDefinition_v1 identifier]
- +[PIFilterEffect_v1 identifier]
- +[PIGANCleanup identifier]
- +[PIGenerativeEdits identifier]
- +[PIGrain_v1 adjustmentSchema]
- +[PIGrain_v1 identifier]
- +[PIHighResolutionFusion_v1 adjustmentSchema]
- +[PIHighResolutionFusion_v1 identifier]
- +[PILevels_v1 adjustmentSchema]
- +[PILivePhotoEffect_v1 adjustmentSchema]
- +[PILivePhotoEffect_v1 flavorSetting]
- +[PILivePhotoEffect_v1 identifier]
- +[PILivePhotoEffect_v1 recipeSetting]
- +[PILivePhotoKeyFrame_v1 identifier]
- +[PIModularPhotosPipeline_v0 controlDataWithPortraitEffectAdjustment:]
- +[PIMute_v1 identifier]
- +[PINoiseReduction_v1 adjustmentSchema]
- +[PINoiseReduction_v1 identifier]
- +[PIObjectRemoval _instancesForGenerativeEditOperation:]
- +[PIObjectRemoval _nonInstancedOperationsFromComposition:]
- +[PIObjectRemoval _tightImageSpaceBoundsForGenerativeEditOperation:composition:error:]
- +[PIOrientation_v1 identifier]
- +[PIOutfillPlaceholder identifier]
- +[PIPhotographicStyleApplyV1 adjustmentFormat]
- +[PIPhotographicStyleLearnV1 adjustmentDescriptor]
- +[PIPhotographicStyleLearnV1 adjustmentFormat]
- +[PIPhotographicStyleLearnV2 identifier]
- +[PIPhotosPipeline pipelineIdentifier]
- +[PIPhotosPipeline_v1 addPhotographicStyleApplyV2ToPipeline:options:primaryInput:styleInput:adjustmentInput:assetMedia:error:]
- +[PIPhotosPipeline_v1 addPhotographicStyleLearnV2ToPipeline:options:primaryInput:adjustmentInput:assetMedia:error:]
- +[PIPhotosPipeline_v1 connectPhotographicStyleV2ToPipeline:name:primaryInput:adjustmentInput:assetMedia:isVideo:]
- +[PIPlaybackRate_v1 identifier]
- +[PIPrivatePhotosPipeline pipelineIdentifier]
- +[PIRedEye_v1 adjustmentSchema]
- +[PIRetouchCleanup identifier]
- +[PISegmentationLoader _baseLayoutForDisplayContext:ofItem:spatialPhotoEnabled:]
- +[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:completion:]
- +[PISegmentationLoader renderPreviewLayerStackFromWallpaperURL:styleCategory:completion:]
- +[PISharpen_v1 adjustmentSchema]
- +[PISharpen_v1 identifier]
- +[PISlowMotion_v1 identifier]
- +[PISmartBlackAndWhite_v1 adjustmentSchema]
- +[PISmartBlackAndWhite_v1 identifier]
- +[PISmartColor_v1 adjustmentSchema]
- +[PISmartColor_v1 identifier]
- +[PISmartCopyPaste identifier]
- +[PISmartCopyPaste pasteAdjustmentSchema]
- +[PISmartToneAuto_v1 identifier]
- +[PISmartTone_v1 adjustmentSchema]
- +[PISmartTone_v1 identifier]
- +[PISmartTone_v1 statisticsSetting]
- +[PISpatialReframe adjustmentSchema]
- +[PISpatialReframe identifier]
- +[PITextureStyle identifier]
- +[PITrim_v1 identifier]
- +[PIVignette_v1 adjustmentSchema]
- +[PIVignette_v1 identifier]
- +[PIWhiteBalance_v1 identifier]
- +[_PISemanticStyleAdjustmentExpressionFunction adjustmentInfoDescriptor]
- -[PIADMCleanup identifier]
- -[PIADMOutfill identifier]
- -[PIAudioMix_v1 identifier]
- -[PICinematicVideo_v1 identifier]
- -[PICinematicVideo_v2 identifier]
- -[PICleanup identifier]
- -[PICropStraightenAuto_v1 identifier]
- -[PICropStraighten_v1 identifier]
- -[PICurves_v1 identifier]
- -[PIDefinition_v1 identifier]
- -[PIFilterEffect_v1 identifier]
- -[PIGANCleanup identifier]
- -[PIGenerativeEdits identifier]
- -[PIGrain_v1 identifier]
- -[PIHighResolutionFusion_v1 identifier]
- -[PILevels_v1 identifier]
- -[PILivePhotoEffect_v1 identifier]
- -[PILivePhotoKeyFrame_v1 identifier]
- -[PIManualRedEye_v1 identifier]
- -[PIMute_v1 identifier]
- -[PINoiseReduction_v1 identifier]
- -[PIOrientation_v1 identifier]
- -[PIOutfillPlaceholder identifier]
- -[PIPhotographicStyleApplyV1 identifier]
- -[PIPhotographicStyleApplyV2 identifier]
- -[PIPhotographicStyleLearnV1 identifier]
- -[PIPhotographicStyleLearnV2 identifier]
- -[PIPhotosPipeline identifier]
- -[PIPhotosPipeline_v0 _buildVideoPosterFramePipeline:format:sourceMedia:outputMedia:videoPosterFrameTime:]
- -[PIPhotosPipeline_v1 _buildPostGeometryPipeline:error:]
- -[PIPhotosPipeline_v1 _buildVideoPosterFramePipeline:format:sourceMedia:outputMedia:videoPosterFrameTime:]
- -[PIPipelineModule identifier]
- -[PIPlaybackRate_v1 identifier]
- -[PIPortraitLightingEffectV1Processor outputImageWithInputs:settings:error:]
- -[PIPortrait_v1 identifier]
- -[PIPortrait_v2 identifier]
- -[PIPrivatePhotosPipeline_v0 buildFiltersGroupPipeline:temporality:error:]
- -[PIPrivatePhotosPipeline_v0 buildFiltersPipeline:temporality:connections:error:]
- -[PIPrivatePhotosPipeline_v1 buildFiltersGroupPipeline:temporality:error:]
- -[PIPrivatePhotosPipeline_v1 buildFiltersPipeline:temporality:connections:error:]
- -[PIRedEye_v1 identifier]
- -[PIRetouchCleanup identifier]
- -[PISelectiveColor_v1 identifier]
- -[PISemanticStyleSettingsExpressionFunction evaluateWithArguments:error:]
- -[PISemanticStyleSettingsExpressionFunction format]
- -[PISemanticStyleThumbnailApply identifier]
- -[PISharpen_v1 identifier]
- -[PISlowMotion_v1 identifier]
- -[PISmartBlackAndWhite_v1 identifier]
- -[PISmartColor_v1 identifier]
- -[PISmartCopyPaste identifier]
- -[PISmartToneAuto_v1 identifier]
- -[PISmartTone_v1 identifier]
- -[PISpatialReframe identifier]
- -[PITextureStyle identifier]
- -[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]
- -[PITrim_v1 identifier]
- -[PIVignette_v1 identifier]
- -[PIWhiteBalanceAuto_v1 identifier]
- -[PIWhiteBalance_v1 identifier]
- -[_PIGrayColorPipelineBuilder identifier]
- -[_PISemanticStyleAdjustmentExpressionFunction evaluateWithArguments:error:]
- -[_PISemanticStyleAdjustmentExpressionFunction format]
- -[_PITextureStyleSettingsExpressionFunction evaluateWithArguments:error:]
- -[_PITextureStyleSettingsExpressionFunction format]
- GCC_except_table1108
- GCC_except_table1710
- GCC_except_table1724
- GCC_except_table1893
- GCC_except_table2069
- GCC_except_table2223
- GCC_except_table2233
- GCC_except_table2239
- GCC_except_table2247
- GCC_except_table2254
- GCC_except_table2262
- GCC_except_table2340
- GCC_except_table2380
- GCC_except_table2409
- GCC_except_table2414
- GCC_except_table2429
- GCC_except_table2445
- GCC_except_table2450
- GCC_except_table2543
- GCC_except_table2778
- GCC_except_table309
- GCC_except_table3131
- GCC_except_table3136
- GCC_except_table3166
- GCC_except_table3170
- GCC_except_table3172
- GCC_except_table3173
- GCC_except_table3175
- GCC_except_table3177
- GCC_except_table3179
- GCC_except_table3185
- GCC_except_table3190
- GCC_except_table3199
- GCC_except_table3294
- GCC_except_table3363
- GCC_except_table3364
- GCC_except_table3473
- GCC_except_table3515
- GCC_except_table3523
- GCC_except_table3575
- GCC_except_table3790
- GCC_except_table387
- GCC_except_table3909
- GCC_except_table3919
- GCC_except_table3922
- GCC_except_table3923
- GCC_except_table3935
- GCC_except_table3982
- GCC_except_table3991
- GCC_except_table4019
- GCC_except_table4042
- GCC_except_table4272
- GCC_except_table4445
- GCC_except_table4531
- GCC_except_table4634
- GCC_except_table4658
- GCC_except_table4662
- GCC_except_table4781
- GCC_except_table4819
- GCC_except_table4827
- GCC_except_table4851
- GCC_except_table4873
- GCC_except_table4977
- GCC_except_table498
- GCC_except_table5034
- GCC_except_table5074
- GCC_except_table5226
- GCC_except_table5249
- GCC_except_table5256
- GCC_except_table5259
- GCC_except_table5270
- GCC_except_table5277
- GCC_except_table5424
- GCC_except_table5516
- GCC_except_table5577
- GCC_except_table5580
- GCC_except_table5592
- GCC_except_table5593
- GCC_except_table5597
- GCC_except_table5598
- GCC_except_table5599
- GCC_except_table5604
- GCC_except_table5612
- GCC_except_table5705
- GCC_except_table6093
- GCC_except_table6112
- GCC_except_table6113
- GCC_except_table6119
- GCC_except_table6124
- GCC_except_table6176
- GCC_except_table6181
- GCC_except_table6182
- GCC_except_table6192
- GCC_except_table6194
- GCC_except_table6218
- GCC_except_table6220
- GCC_except_table6221
- GCC_except_table6222
- GCC_except_table6224
- GCC_except_table6226
- GCC_except_table6228
- GCC_except_table6231
- GCC_except_table6236
- GCC_except_table6237
- GCC_except_table6238
- GCC_except_table6239
- GCC_except_table6241
- GCC_except_table6246
- GCC_except_table6382
- GCC_except_table6385
- GCC_except_table6451
- GCC_except_table6525
- GCC_except_table6847
- GCC_except_table7095
- GCC_except_table7096
- GCC_except_table7186
- GCC_except_table7189
- GCC_except_table7193
- GCC_except_table7194
- GCC_except_table7198
- GCC_except_table7199
- GCC_except_table7201
- GCC_except_table7207
- GCC_except_table7216
- GCC_except_table7232
- GCC_except_table7283
- GCC_except_table7335
- GCC_except_table7337
- GCC_except_table7338
- GCC_except_table7370
- GCC_except_table7373
- GCC_except_table7441
- GCC_except_table7451
- GCC_except_table7556
- GCC_except_table7609
- GCC_except_table7705
- GCC_except_table7711
- GCC_except_table7714
- GCC_except_table7716
- GCC_except_table7717
- GCC_except_table7718
- GCC_except_table7719
- GCC_except_table7721
- GCC_except_table7724
- GCC_except_table7725
- GCC_except_table7726
- GCC_except_table7727
- GCC_except_table7729
- GCC_except_table7730
- GCC_except_table7732
- GCC_except_table7733
- GCC_except_table7734
- GCC_except_table7735
- GCC_except_table775
- GCC_except_table7798
- GCC_except_table7812
- GCC_except_table7813
- GCC_except_table7814
- GCC_except_table7848
- GCC_except_table7849
- GCC_except_table7850
- GCC_except_table7856
- GCC_except_table786
- GCC_except_table7901
- GCC_except_table796
- GCC_except_table8047
- GCC_except_table8057
- GCC_except_table8064
- GCC_except_table8065
- GCC_except_table8066
- GCC_except_table8067
- GCC_except_table8068
- GCC_except_table8069
- GCC_except_table8070
- GCC_except_table8113
- GCC_except_table816
- GCC_except_table8299
- GCC_except_table8527
- GCC_except_table8529
- GCC_except_table8530
- GCC_except_table8592
- GCC_except_table8594
- GCC_except_table8596
- GCC_except_table863
- GCC_except_table866
- GCC_except_table8666
- GCC_except_table867
- GCC_except_table8689
- GCC_except_table8691
- GCC_except_table8694
- GCC_except_table8698
- GCC_except_table8700
- GCC_except_table8716
- GCC_except_table8733
- GCC_except_table8741
- GCC_except_table8745
- GCC_except_table8746
- GCC_except_table8754
- GCC_except_table8764
- GCC_except_table8768
- GCC_except_table8770
- GCC_except_table8774
- GCC_except_table8776
- GCC_except_table8777
- GCC_except_table8789
- _NUAssetCapabilityAudio
- _NUAssetCapabilityAudioMix
- _NUAssetCapabilityCinematicVideoV1
- _NUAssetCapabilityCinematicVideoV2
- _NUAssetCapabilityHDR
- _NUAssetCapabilityHDRGainMap
- _NUAssetCapabilityPhotographicStyle
- _NUAssetCapabilityPhotographicStyleV1
- _NUAssetCapabilityPhotographicStyleV2
- _NUAssetCapabilityPortraitV1
- _NUAssetCapabilityPortraitV2
- _NUAssetCapabilityRawDecode
- _NUPipelineVariableTargetHeadroom
- _OBJC_CLASS_$_NUAdjustmentSchema
- _OBJC_CLASS_$_NUAspectFitScalePolicy
- _OBJC_CLASS_$_PIAssetLoader
- _OBJC_CLASS_$_PISemanticStyleSettingsExpressionFunction
- _OBJC_CLASS_$__PISemanticStyleAdjustmentExpressionFunction
- _OBJC_CLASS_$__PITextureStyleSettingsExpressionFunction
- _OBJC_IVAR_$_PIParallaxSegmentationItem.outfillSafeEdges
- _OBJC_METACLASS_$_NUAssetLoader
- _OBJC_METACLASS_$_PIAssetLoader
- _OBJC_METACLASS_$_PISemanticStyleSettingsExpressionFunction
- _OBJC_METACLASS_$__PISemanticStyleAdjustmentExpressionFunction
- _OBJC_METACLASS_$__PITextureStyleSettingsExpressionFunction
- __OBJC_$_CLASS_METHODS_PIADMCleanup
- __OBJC_$_CLASS_METHODS_PIADMOutfill
- __OBJC_$_CLASS_METHODS_PIAssetLoader
- __OBJC_$_CLASS_METHODS_PICropStraightenAuto_v1
- __OBJC_$_CLASS_METHODS_PIGANCleanup
- __OBJC_$_CLASS_METHODS_PIOutfillPlaceholder
- __OBJC_$_CLASS_METHODS_PIPhotographicStyleApplyV1
- __OBJC_$_CLASS_METHODS_PIPhotographicStyleLearnV1
- __OBJC_$_CLASS_METHODS__PISemanticStyleAdjustmentExpressionFunction
- __OBJC_$_CLASS_PROP_LIST_PIPhotographicStyleApplyV1
- __OBJC_$_CLASS_PROP_LIST_PIPhotographicStyleLearnV1
- __OBJC_$_INSTANCE_METHODS_PISemanticStyleSettingsExpressionFunction
- __OBJC_$_INSTANCE_METHODS__PISemanticStyleAdjustmentExpressionFunction
- __OBJC_$_INSTANCE_METHODS__PITextureStyleSettingsExpressionFunction
- __OBJC_CLASS_RO_$_PIAssetLoader
- __OBJC_CLASS_RO_$_PISemanticStyleSettingsExpressionFunction
- __OBJC_CLASS_RO_$__PISemanticStyleAdjustmentExpressionFunction
- __OBJC_CLASS_RO_$__PITextureStyleSettingsExpressionFunction
- __OBJC_METACLASS_RO_$_PIAssetLoader
- __OBJC_METACLASS_RO_$_PISemanticStyleSettingsExpressionFunction
- __OBJC_METACLASS_RO_$__PISemanticStyleAdjustmentExpressionFunction
- __OBJC_METACLASS_RO_$__PITextureStyleSettingsExpressionFunction
- ___36+[PISpatialReframe adjustmentSchema]_block_invoke
- ___56+[PIObjectRemoval _instancesForGenerativeEditOperation:]_block_invoke
- ___58+[PIObjectRemoval _nonInstancedOperationsFromComposition:]_block_invoke
- ___58+[PIObjectRemoval _nonInstancedOperationsFromComposition:]_block_invoke_2
- ___76-[PIPortraitLightingEffectV1Processor outputImageWithInputs:settings:error:]_block_invoke
- ___76-[PIPortraitLightingEffectV1Processor outputImageWithInputs:settings:error:]_block_invoke_2
- ___81-[PIPrivatePhotosPipeline_v0 buildFiltersPipeline:temporality:connections:error:]_block_invoke
- ___81-[PIPrivatePhotosPipeline_v1 buildFiltersPipeline:temporality:connections:error:]_block_invoke
- ___89+[PISegmentationLoader renderPreviewLayerStackFromWallpaperURL:styleCategory:completion:]_block_invoke
- ___90+[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:completion:]_block_invoke
- ___90+[PISegmentationLoader _renderPreviewLayerStackFromWallpaperURL:styleCategory:completion:]_block_invoke_2
- ___94-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]_block_invoke
- ___94-[PITextureStyleUsageInputConfiguration initWithRequiredChannels:optionalChannels:personData:]_block_invoke_2
- ___block_descriptor_41_e8_32s_e29_v16?0"<NUMutablePipeline>"8ls32l8
- ___block_descriptor_48_e8_32s_e33_B24?0"<NUMutablePipeline>"8^16ls32l8
- ___block_descriptor_49_e8_32s40s_e44_"NUChannelPortRef"16?0"NUChannelPortRef"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e44_"NUChannelPortRef"16?0"NUChannelPortRef"8ls32l8s40l8s48l8
- ___swift_memcpy89_8
- _adjustmentSchema.onceToken
- _adjustmentSchema.schema
- _type_layout_string So6CGSizeV
```
