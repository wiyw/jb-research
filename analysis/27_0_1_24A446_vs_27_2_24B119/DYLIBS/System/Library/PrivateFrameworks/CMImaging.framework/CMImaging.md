## CMImaging

> `/System/Library/PrivateFrameworks/CMImaging.framework/CMImaging`

```diff

-764.22.14.0.0
-  __TEXT.__text: 0x1f422c
-  __TEXT.__objc_methlist: 0x112a4
-  __TEXT.__cstring: 0x2330a
-  __TEXT.__const: 0x7140
+764.42.8.0.0
+  __TEXT.__text: 0x1f696c
+  __TEXT.__objc_methlist: 0x1135c
+  __TEXT.__cstring: 0x23553
+  __TEXT.__const: 0x7180
   __TEXT.__gcc_except_tab: 0x14a8
   __TEXT.__oslogstring: 0x4caa
   __TEXT.__dlopen_cstrs: 0x50
-  __TEXT.__unwind_info: 0x3aa0
+  __TEXT.__unwind_info: 0x3ad8
   __TEXT.__eh_frame: 0x6e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1b40
-  __DATA_CONST.__objc_classlist: 0x768
+  __DATA_CONST.__const: 0x1ba0
+  __DATA_CONST.__objc_classlist: 0x770
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x1d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7858
+  __DATA_CONST.__objc_selrefs: 0x78b0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x5d0
+  __DATA_CONST.__objc_superrefs: 0x5d8
   __DATA_CONST.__objc_arraydata: 0x6a8
-  __DATA_CONST.__got: 0xe78
+  __DATA_CONST.__got: 0xec8
   __AUTH_CONST.__const: 0xc30
-  __AUTH_CONST.__cfstring: 0x8da0
-  __AUTH_CONST.__objc_const: 0x27a78
+  __AUTH_CONST.__cfstring: 0x8f80
+  __AUTH_CONST.__objc_const: 0x27c00
   __AUTH_CONST.__objc_intobj: 0xfc0
   __AUTH_CONST.__objc_arrayobj: 0x138
-  __AUTH_CONST.__objc_floatobj: 0xe0
+  __AUTH_CONST.__objc_floatobj: 0xd0
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x1300
-  __AUTH_CONST.__auth_got: 0xc40
+  __AUTH_CONST.__auth_got: 0xc48
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xcd0
-  __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x2030
-  __DATA.__data: 0x12f98
+  __AUTH.__objc_data: 0x50
+  __DATA.__objc_ivar: 0x2048
+  __DATA.__data: 0x11950
   __DATA.__common: 0x1e0
-  __DATA.__bss: 0xe8
-  __DATA_DIRTY.__objc_data: 0x3d40
-  __DATA_DIRTY.__common: 0x120
-  __DATA_DIRTY.__bss: 0x1e8
+  __DATA.__bss: 0xd8
+  __DATA_DIRTY.__objc_data: 0x4a10
+  __DATA_DIRTY.__data: 0x1650
+  __DATA_DIRTY.__common: 0x140
+  __DATA_DIRTY.__bss: 0x1f8
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9565
-  Symbols:   11324
+  Functions: 9594
+  Symbols:   11372
   CStrings:  0
 
Symbols:
+ +[CMIStylesMetadataInterpolator initialize]
+ -[CMILCBDatabase databaseVersion]
+ -[CMILCBDatabase distortion]
+ -[CMILCBDatabase updateDistortion:]
+ -[CMILCBEntry blemishType]
+ -[CMILCBEntry correctionPatch]
+ -[CMILCBEntry decodeCommonFieldsWithCoder:]
+ -[CMILCBEntry decodeCorrectionFeaturesWithCoder:]
+ -[CMILCBEntry decodeV4FieldsWithCoder:]
+ -[CMILCBEntry decodeV5FieldsWithCoder:]
+ -[CMILCBEntry initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:blemishType:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:correctionPatch:]
+ -[CMIStylesMetadataInterpolator .cxx_destruct]
+ -[CMIStylesMetadataInterpolator _smartStyleUtilitiesForFloat16Coefficients:]
+ -[CMIStylesMetadataInterpolator initWithOptionalMetalCommandQueue:]
+ -[CMIStylesMetadataInterpolator init]
+ -[CMIStylesMetadataInterpolator interpolateStylesMetadataFromStartFrameMetadataDict:startFrameTime:endFrameMetadataDict:endFrameTime:frameTimesToInterpolate:]
+ _CMIStylesMetadataKey_FaceROIs
+ _CMIStylesMetadataKey_SmartStyleMetadata
+ _CMIStylesMetadataKey_TextureStyleMetadata
+ _CMTimeCompare
+ _OBJC_CLASS_$_CMIStylesMetadataInterpolator
+ _OBJC_IVAR_$_CMILCBDatabase._databaseVersion
+ _OBJC_IVAR_$_CMILCBDatabase._distortion
+ _OBJC_IVAR_$_CMILCBEntry._blemishType
+ _OBJC_IVAR_$_CMILCBEntry._correctionPatch
+ _OBJC_IVAR_$_CMIStylesMetadataInterpolator._commandQueue
+ _OBJC_IVAR_$_CMIStylesMetadataInterpolator._smartStyleUtilities
+ _OBJC_IVAR_$_CMIStylesMetadataInterpolator._smartStyleUtilitiesCreationAttempted
+ _OBJC_METACLASS_$_CMIStylesMetadataInterpolator
+ __OBJC_$_CLASS_METHODS_CMIStylesMetadataInterpolator
+ __OBJC_$_INSTANCE_METHODS_CMIStylesMetadataInterpolator
+ __OBJC_$_INSTANCE_VARIABLES_CMIStylesMetadataInterpolator
+ __OBJC_CLASS_RO_$_CMIStylesMetadataInterpolator
+ __OBJC_METACLASS_RO_$_CMIStylesMetadataInterpolator
+ ___158-[CMIStylesMetadataInterpolator interpolateStylesMetadataFromStartFrameMetadataDict:startFrameTime:endFrameMetadataDict:endFrameTime:frameTimesToInterpolate:]_block_invoke
+ ___158-[CMIStylesMetadataInterpolator interpolateStylesMetadataFromStartFrameMetadataDict:startFrameTime:endFrameMetadataDict:endFrameTime:frameTimesToInterpolate:]_block_invoke_2
+ ___block_descriptor_36_e53_"NSDictionary"24?0"NSDictionary"8"NSDictionary"16l
+ ___block_descriptor_52_e8_32s40s_e28_"NSNumber"16?0"NSString"8ls32l8s40l8
+ ___smi_interpolateFaceROI_block_invoke
+ _fmodf
+ _gStylesMetadataInterpolatorTrace
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleFaceAttitudeMetadata
+ _kFigCaptureSampleBufferAttachedMediaKey_TextureStyleImageStatistics
+ _kFigCaptureStreamLCBKey_OpticalCenterForLensX
+ _kFigCaptureStreamLCBKey_OpticalCenterForLensY
+ _kFigCaptureStreamLCBKey_RadialDistortionEnabled
+ _kFigCaptureStreamLCBKey_RadialDistortionK1
+ _kFigCaptureStreamLCBKey_RadialDistortionK2
+ _kFigCaptureStreamLCBKey_RadialDistortionK3
+ _kFigCaptureStreamLCBKey_RadialDistortionMaxR
+ _kFigCaptureStreamLCBKey_RadialDistortionRPeak
+ _smi_interpolatePeopleByFaceID
- -[CMILCBEntry initWithKey:position:radius:defocusRadius:particleDistance:apertureRatio:focusLensPosition:oisShift:opticalCenter:detectionCount:relativeToLens:lastDetectionGravityVector:lastDetectionTimeStamp:shouldCorrect:correctionFeatures:]
- -[CMILCBEntry relativeToLens]
- _OBJC_IVAR_$_CMILCBEntry._relativeToLens
- _objc_retain_x6
```
