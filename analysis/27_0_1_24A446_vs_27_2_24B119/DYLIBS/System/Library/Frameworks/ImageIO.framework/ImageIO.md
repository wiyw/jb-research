## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

```diff

-2851.0.0.0.0
-  __TEXT.__text: 0x5035b4
-  __TEXT.__objc_methlist: 0xd58
-  __TEXT.__const: 0x49ed0
-  __TEXT.__gcc_except_tab: 0x229c0
-  __TEXT.__cstring: 0xa6a6d
+2851.1.8.0.0
+  __TEXT.__text: 0x509444
+  __TEXT.__objc_methlist: 0xd68
+  __TEXT.__const: 0x4a070
+  __TEXT.__gcc_except_tab: 0x22bec
+  __TEXT.__cstring: 0xa777d
   __TEXT.__oslogstring: 0x17
   __TEXT.__constg_swiftt: 0x26a4
   __TEXT.__swift5_typeref: 0x3d88

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0x13890
-  __TEXT.__eh_frame: 0x921c
+  __TEXT.__unwind_info: 0x13950
+  __TEXT.__eh_frame: 0x925c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4b818
+  __DATA_CONST.__const: 0x4b890
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_selrefs: 0xb48
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x470
-  __DATA_CONST.__got: 0xaa8
-  __AUTH_CONST.__const: 0x4f290
-  __AUTH_CONST.__cfstring: 0x36000
+  __DATA_CONST.__got: 0xb18
+  __AUTH_CONST.__const: 0x4f498
+  __AUTH_CONST.__cfstring: 0x36100
   __AUTH_CONST.__objc_const: 0x11d0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x6d8
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x2f78
+  __AUTH_CONST.__auth_got: 0x2fc0
   __AUTH_CONST.__auth_ptr: 0x1280
   __AUTH.__objc_data: 0x370
-  __AUTH.__data: 0x15d8
+  __AUTH.__data: 0x15c8
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x1
   __DATA.__objc_ivar: 0xa4
-  __DATA.__data: 0x65f0
-  __DATA.__bss: 0x30e40
-  __DATA.__common: 0x2270
-  __DATA_DIRTY.__data: 0x3b0
+  __DATA.__data: 0x6790
+  __DATA.__bss: 0x30a30
+  __DATA.__common: 0x2268
+  __DATA_DIRTY.__data: 0x3c0
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0xbe8
-  __DATA_DIRTY.__common: 0xff0
+  __DATA_DIRTY.__bss: 0x1058
+  __DATA_DIRTY.__common: 0xff8
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/ColorSync
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
-  Functions: 23179
-  Symbols:   24417
+  Functions: 23242
+  Symbols:   24492
   CStrings:  0
 
Symbols:
+ -[IIO_CXMLParser dealloc]
+ GCC_except_table179
+ GCC_except_table217
+ _CGColorSpaceContainsISO5Metadata
+ _CGColorSpaceCreateWithCopyOfDataAndMetadata
+ _CGImageCopyColorSyncISO5Metadata
+ _CGImageGetContentAverageLightLevelNits
+ _ColorSyncProfileCopyISO5Metadata
+ _ColorSyncProfileCreateCopyWithISO5Metadata
+ _ColorSyncProfileGetContentHeadroom
+ _ColorSyncProfileGetISO5AverageLightLevel
+ _IIOImageIsHDR
+ _IIO_ColorSpaceCreateWithICCDataAndISO5Metadata
+ _IIO_CreateColorSpaceCopyWithColorSyncISO5Metadata
+ _IIO_CreateISO5MetadataInfo
+ _IIO_CreateImageCopyWithColorSyncISO5Metadata
+ _IIO_CreateMergedISO5Metadata
+ _IIO_FloatsMatch
+ _IIO_GetCLLFromISO5Dict
+ _IIO_GetMDCVLuminanceFromISO5Dict
+ __Z21CreateReader_DDS_ASTCv
+ __Z22CreateReader_RawCameraP13IIODictionary
+ __ZL18IIO_GetFloatForKeyPK14__CFDictionaryPK10__CFString
+ __ZL19DDSDXGIFormatIsASTCj
+ __ZL21IIO_ApplyCheckNonZeroPKvS0_Pv
+ __ZL24IIO_CreateNeutralISO5KeyPK10__CFString
+ __ZL25IIO_ApplyNeutralISO5EntryPKvS0_Pv
+ __ZL26IIO_ISO5CategoryDictsMatchPK14__CFDictionaryS1_PKPK10__CFStringj
+ __ZL29HEIFCopyColorSyncISO5MetadataP7CGImage
+ __ZL29IIO_ApplyNeutralISO5KeyRenamePKvS0_Pv
+ __ZL31dds_dx9_packed_format_for_masksjjjjj
+ __ZN10IIO_Reader19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ __ZN11OFDDocument5closeEv
+ __ZN11OFDTemplate5closeEv
+ __ZN11OutOfBoundsD0Ev
+ __ZN11OutOfBoundsD1Ev
+ __ZN12BCReadPlugin21decode1010102toRGBA16EP19IIOImageReadSessionP13vImage_Buffer
+ __ZN12BCReadPlugin22decodePacked16toRGBA16EP19IIOImageReadSessionP13vImage_Bufferj
+ __ZN12BCReadPlugin24decodeUncompressedToRGBAEP19IIOImageReadSessionP13vImage_Buffer
+ __ZN13HEIFMainImage23getMaxContentLightLevelEv
+ __ZN13HEIFMainImage28hasISO5ContentLightLevelInfoEv
+ __ZN13HEIFMainImage34getISO5MasteringDisplayColorVolumeEv
+ __ZN13HEIFMainImage34hasISO5MasteringDisplayColorVolumeEv
+ __ZN13IIOReadPlugin29willApplyOrientationTransformEv
+ __ZN14ASTCTextureImp24MetalFormatForDXGIFormatEj
+ __ZN14HEIFReadPlugin29willApplyOrientationTransformEv
+ __ZN14IIO_Reader_RAD27hasCustomCompareOptionsProcEv
+ __ZN15IIO_Reader_HEIF19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ __ZN20IIOPixelConverterRGBC1E13IIO_PixelTypehhhhhS0_hhPKcbb
+ __ZN20IIOPixelConverterRGBC2E13IIO_PixelTypehhhhhS0_hhPKcbb
+ __ZN7GPSCopy13checkCapacityEPhm
+ __ZN7GPSCopy15pointerToOffsetEm
+ __ZN7GPSCopy15read32UncheckedEPh
+ __ZN7GPSCopy22checkInitializedLengthEPhm
+ __ZNKSt9exception4whatEv
+ __ZNSt9exceptionD2Ev
+ __ZTI11OutOfBounds
+ __ZTS11OutOfBounds
+ __ZTV11OutOfBounds
+ __ZZL16DDSASTCBlockDimsjPhS_E4dims
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE3hdr
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE3ldr
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE4srgb
+ _iptc_AIPromptInformation
+ _iptc_AIPromptWriterName
+ _kCGColorSpaceExtendedRange
+ _kCGImagePropertyIPTCExtAIPromptInformation
+ _kCGImagePropertyIPTCExtAIPromptWriterName
+ _kColorSyncAverageLightLevel
+ _kColorSyncAverageLuminance
+ _kColorSyncCCVInfo
+ _kColorSyncCLLInfo
+ _kColorSyncCRWLInfo
+ _kColorSyncDerivedISO5Metadata
+ _kColorSyncMDCVInfo
+ _kColorSyncMaxLightLevel
+ _kColorSyncMaxLuminance
+ _kColorSyncMinLuminance
+ _kColorSyncPrimaries
+ _kColorSyncReferenceWhite
+ _kIIOICCISO5MetadataPropertyKey
+ _sniffDDS
+ _unzClose
+ _vImageConvert_RGBFFFtoRGBAFFFF
- GCC_except_table181
- GCC_except_table185
- GCC_except_table215
- __ZN19IIOReader_RawCameraC1EP13IIODictionary
- __ZN20IIOPixelConverterRGBC1E13IIO_PixelTypehhhhhS0_hhPKc
- __ZN20IIOPixelConverterRGBC2E13IIO_PixelTypehhhhhS0_hhPKc
- __ZN7GPSCopy6read32EPh
- _sniffBC
- _sniffOlympusRaw
```
