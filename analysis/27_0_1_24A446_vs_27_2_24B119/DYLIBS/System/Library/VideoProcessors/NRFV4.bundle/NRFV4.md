## NRFV4

> `/System/Library/VideoProcessors/NRFV4.bundle/NRFV4`

```diff

-764.22.14.0.0
-  __TEXT.__text: 0x27c598
-  __TEXT.__objc_methlist: 0x14718
-  __TEXT.__const: 0x103260
-  __TEXT.__cstring: 0x36bfa
+764.42.8.0.0
+  __TEXT.__text: 0x280220
+  __TEXT.__objc_methlist: 0x14850
+  __TEXT.__const: 0x1032a0
+  __TEXT.__cstring: 0x37051
   __TEXT.__oslogstring: 0x21e64
-  __TEXT.__gcc_except_tab: 0x1850
+  __TEXT.__gcc_except_tab: 0x1860
   __TEXT.__dlopen_cstrs: 0x10c
-  __TEXT.__unwind_info: 0x54d8
+  __TEXT.__unwind_info: 0x5528
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x14d8
+  __DATA_CONST.__const: 0x14f8
   __DATA_CONST.__objc_classlist: 0xf28
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x77f0
+  __DATA_CONST.__objc_selrefs: 0x78d0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xbe8
   __DATA_CONST.__objc_arraydata: 0xfe0
-  __DATA_CONST.__got: 0xf90
-  __AUTH_CONST.__const: 0x9c0
-  __AUTH_CONST.__cfstring: 0x15cc0
-  __AUTH_CONST.__objc_const: 0x40208
+  __DATA_CONST.__got: 0xfa0
+  __AUTH_CONST.__const: 0x9e0
+  __AUTH_CONST.__cfstring: 0x15f40
+  __AUTH_CONST.__objc_const: 0x40508
   __AUTH_CONST.__objc_floatobj: 0x140
   __AUTH_CONST.__objc_doubleobj: 0xa0
   __AUTH_CONST.__objc_arrayobj: 0xd68
   __AUTH_CONST.__objc_intobj: 0xa38
   __AUTH_CONST.__objc_dictobj: 0x500
-  __AUTH_CONST.__auth_got: 0x880
+  __AUTH_CONST.__auth_got: 0x888
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x1220
-  __DATA.__objc_ivar: 0x4420
+  __AUTH.__objc_data: 0xff0
+  __DATA.__objc_ivar: 0x445c
   __DATA.__data: 0xcc8
-  __DATA.__common: 0x44
+  __DATA.__common: 0x40
   __DATA.__bss: 0x28
-  __DATA_DIRTY.__objc_data: 0x8570
+  __DATA_DIRTY.__objc_data: 0x87a0
   __DATA_DIRTY.__bss: 0x178
-  __DATA_DIRTY.__common: 0xf8
+  __DATA_DIRTY.__common: 0x100
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
   - /System/Library/Frameworks/CoreMedia.framework/CoreMedia

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15236
-  Symbols:   15748
+  Functions: 15305
+  Symbols:   15796
   CStrings:  0
 
Symbols:
+ +[CMISoftwareFlashRenderingCommon getFlashProjGains:outputVector:outputValid:]
+ -[LCBBlock createMetalTexture:pixelFormat:width:height:arrayLength:]
+ -[LCBConfig distortionEnabled]
+ -[LCBConfig distortionSafetyMargin]
+ -[LCBConfig distortionValidSourceMargin]
+ -[LCBConfig getDistortionConfig:]
+ -[LCBConfig k1]
+ -[LCBConfig k2]
+ -[LCBConfig k3]
+ -[LCBConfig maxR]
+ -[LCBConfig overlapDistanceScale]
+ -[LCBConfig overlapModeForExtraction]
+ -[LCBConfig patchCorrectionEnabled]
+ -[LCBConfig rPeak]
+ -[LCBCorrection createCorrectionMapForLevel:filteredLCBsForLevel:correctionLUT:patchAtlas:previousLevel:config:error:]
+ -[LCBExtractor runExtractorForEntries:neighbors:inputTexture:levelIndex:loresTexture:loresLevelIndex:config:lscMetadata:outPatchAtlas:error:]
+ -[LCBFiltering temporalFilteringUpdateDatabase:detectionResultsForLevels:extractionSetForLevels:extractionResultsForLevels:patchAtlasesForLevels:config:didUpdateDatabase:error:]
+ -[LCBPerFrameFilteringResults initWithFilteredLCBsBuf:correctionLUT:patchAtlas:]
+ -[LCBPerFrameFilteringResults patchAtlas]
+ -[LCBPyramid warpAfterDemosaic:config:error:]
+ -[LCBPyramidShaders warpAfterDemosaic]
+ -[LCBTransformedEntry initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:blemishType:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:correctionPatch:config:]
+ -[LCBTransformedEntry pyramidPositionForLevel:]
+ -[LCBTransformedEntry withDetectionCountIncrementedAndUpdatedFeatures:updatedRadius:updatedPatch:]
+ -[NRFFrameMetadata manualAWBEnabled]
+ -[NRFFrameMetadata setManualAWBEnabled:]
+ -[SoftISPCalibrationConfig(LCB) getLCBConfigForInputFrame:inputOriginWithinSensorInBayerPixels:inputDimensionsWithinSensorInBayerPixels:correctionEnabled:firstPixel:awb:]
+ -[SoftISPCalibrationConfig(LCB) populateLCBDistortionFieldsInCalibrationConfig:forInputFrame:bounds:lcbConfig:]
+ -[SoftISPInputFrame bayerBinningFactor]
+ _FigCaptureSkipTTR
+ _FigDebugIsInternalBuild
+ _LCBDistortionMaxInvertibleRadius
+ _LCBDistortionMaxR
+ _OBJC_CLASS_$_NSNull
+ _OBJC_IVAR_$_LCBConfig._distortionEnabled
+ _OBJC_IVAR_$_LCBConfig._distortionSafetyMargin
+ _OBJC_IVAR_$_LCBConfig._distortionValidSourceMargin
+ _OBJC_IVAR_$_LCBConfig._k1
+ _OBJC_IVAR_$_LCBConfig._k2
+ _OBJC_IVAR_$_LCBConfig._k3
+ _OBJC_IVAR_$_LCBConfig._maxR
+ _OBJC_IVAR_$_LCBConfig._overlapDistanceScale
+ _OBJC_IVAR_$_LCBConfig._overlapModeForExtraction
+ _OBJC_IVAR_$_LCBConfig._patchCorrectionEnabled
+ _OBJC_IVAR_$_LCBConfig._rPeak
+ _OBJC_IVAR_$_LCBPerFrameFilteringResults._patchAtlas
+ _OBJC_IVAR_$_LCBPyramidShaders._warpAfterDemosaic
+ _OBJC_IVAR_$_NRFFrameMetadata._manualAWBEnabled
+ _OBJC_IVAR_$_SoftISPInputFrame._bayerBinningFactor
+ ___131-[LCBMitigation runOnInputYRGBTexture:inputPyramidLevel:targetSushiTexture:config:lscMetadata:lcbDatabase:didUpdateDatabase:error:]_block_invoke
+ ___block_descriptor_32_e11_q24?0816l
+ _convertV3FocusPixelCrosstalkToV2
+ _getValidatedLSCGainGrid
+ _kFigCaptureStreamMetadata_BayerBinningFactor
+ _validateFocusPixelMapData
- -[LCBCorrection createCorrectionMapForLevel:filteredLCBsForLevel:correctionLUT:previousLevel:config:error:]
- -[LCBExtractor runExtractorForEntries:inputTexture:levelIndex:loresTexture:loresLevelIndex:config:lscMetadata:error:]
- -[LCBFiltering temporalFilteringUpdateDatabase:detectionResultsForLevels:extractionSetForLevels:extractionResultsForLevels:config:didUpdateDatabase:error:]
- -[LCBPerFrameFilteringResults initWithFilteredLCBsBuf:correctionLUT:]
- -[LCBTransformedEntry initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:relativeToLens:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:config:]
- -[SoftISPCalibrationConfig(LCB) getLCBConfigForInputFrame:bounds:correctionEnabled:awb:]
- _FigCaptureShaderPreloadingInProgress
```
