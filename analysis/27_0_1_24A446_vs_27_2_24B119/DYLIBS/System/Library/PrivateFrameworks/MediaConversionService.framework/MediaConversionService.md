## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x1e05c
-  __TEXT.__objc_methlist: 0x1eec
+916.57.154.0.0
+  __TEXT.__text: 0x1f210
+  __TEXT.__objc_methlist: 0x2004
   __TEXT.__const: 0xc0
-  __TEXT.__gcc_except_tab: 0x5a0
-  __TEXT.__cstring: 0x5970
-  __TEXT.__oslogstring: 0x28ca
-  __TEXT.__unwind_info: 0x778
+  __TEXT.__gcc_except_tab: 0x5c0
+  __TEXT.__cstring: 0x5c3d
+  __TEXT.__oslogstring: 0x2985
+  __TEXT.__unwind_info: 0x7c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xcd8
+  __DATA_CONST.__const: 0xd20
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1638
+  __DATA_CONST.__objc_selrefs: 0x16f8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x60
-  __DATA_CONST.__objc_arraydata: 0x578
-  __DATA_CONST.__got: 0x3b8
+  __DATA_CONST.__objc_arraydata: 0x5b8
+  __DATA_CONST.__got: 0x3d0
   __AUTH_CONST.__const: 0x140
-  __AUTH_CONST.__cfstring: 0x3460
-  __AUTH_CONST.__objc_const: 0x2f88
-  __AUTH_CONST.__objc_intobj: 0x198
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__cfstring: 0x35c0
+  __AUTH_CONST.__objc_const: 0x30d8
+  __AUTH_CONST.__objc_intobj: 0x1c8
+  __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x250
-  __DATA.__data: 0x4a8
+  __DATA.__objc_ivar: 0x26c
   __DATA.__bss: 0x50
-  __DATA_DIRTY.__objc_data: 0x730
+  __DATA_DIRTY.__objc_data: 0x7d0
+  __DATA_DIRTY.__data: 0x4a8
   __DATA_DIRTY.__bss: 0x20
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 708
-  Symbols:   1496
+  Functions: 736
+  Symbols:   1542
   CStrings:  0
 
Symbols:
+ -[PAMediaConversionServiceContentProvenanceValidationResult certificateChainDERData]
+ -[PAMediaConversionServiceContentProvenanceValidationResult setCertificateChainDERData:]
+ -[PHMediaFormatConversionCompositeRequest requiresStarRatingMetadataChange]
+ -[PHMediaFormatConversionCompositeRequest requiresTitleMetadataChange]
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
+ -[PHMediaFormatConversionRequest _provenanceRenderOutputType]
+ -[PHMediaFormatConversionRequest provenanceRenderSourceURL]
+ -[PHMediaFormatConversionRequest requiresStarRatingMetadataChange]
+ -[PHMediaFormatConversionRequest requiresTitleMetadataChange]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceRenderURL:processedOriginalDestinationURL:sidecarURL:]
+ -[PHMediaFormatConversionRequest setStarRatingMetadataBehavior:withStarRating:]
+ -[PHMediaFormatConversionRequest setTitleMetadataBehavior:withTitle:]
+ -[PHMediaFormatConversionRequest starRatingMetadataBehavior]
+ -[PHMediaFormatConversionRequest starRating]
+ -[PHMediaFormatConversionRequest titleMetadataBehavior]
+ -[PHMediaFormatConversionRequest title]
+ -[PHMediaFormatConversionSource checkForStarRatingData]
+ -[PHMediaFormatConversionSource checkForTitleData]
+ -[PHMediaFormatConversionSource markStarRatingMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource markTitleMetadataAsCheckedWithStatus:]
+ -[PHMediaFormatConversionSource setStarRatingMetadataStatus:]
+ -[PHMediaFormatConversionSource setTitleMetadataStatus:]
+ -[PHMediaFormatConversionSource sourceStarRatingMetadataStatus]
+ -[PHMediaFormatConversionSource sourceTitleMetadataStatus]
+ -[PHMediaFormatConversionSource starRatingMetadataStatus]
+ -[PHMediaFormatConversionSource titleMetadataStatus]
+ GCC_except_table142
+ GCC_except_table157
+ GCC_except_table161
+ GCC_except_table164
+ GCC_except_table174
+ GCC_except_table180
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table432
+ GCC_except_table434
+ GCC_except_table436
+ GCC_except_table438
+ GCC_except_table440
+ GCC_except_table442
+ GCC_except_table444
+ GCC_except_table446
+ GCC_except_table561
+ GCC_except_table569
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table689
+ GCC_except_table691
+ GCC_except_table694
+ GCC_except_table696
+ GCC_except_table709
+ GCC_except_table97
+ GCC_except_table99
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetKeywords
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetStarRating
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetTitle
+ _OBJC_IVAR_$_PAMediaConversionServiceContentProvenanceValidationResult._certificateChainDERData
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceRenderSourceURL
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._starRating
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._starRatingMetadataBehavior
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._title
+ _OBJC_IVAR_$_PHMediaFormatConversionRequest._titleMetadataBehavior
+ _OBJC_IVAR_$_PHMediaFormatConversionSource._starRatingMetadataStatus
+ _OBJC_IVAR_$_PHMediaFormatConversionSource._titleMetadataStatus
+ _PAMediaConversionErrorIsProvenanceProcessingError
+ _PAMediaConversionIsProvenanceClientUpgradeRequiredError
+ _PAMediaConversionServiceOptionAVMetadataIncludeRatingKey
+ _PAMediaConversionServiceOptionAVMetadataIncludeTitleKey
+ _PAMediaConversionServiceOptionAVMetadataRatingKey
+ _PAMediaConversionServiceProvenanceCertificateChainDataKey
+ _PAMediaConversionServiceProvenanceRetryableKey
+ _PAProvenanceCloudAppErrorIsTransient
+ _PFErrorOrUnderlyingErrorMatchesCodesByDomain
+ ___157-[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
+ ___70-[PHMediaFormatConversionCompositeRequest requiresTitleMetadataChange]_block_invoke
+ ___75-[PHMediaFormatConversionCompositeRequest requiresStarRatingMetadataChange]_block_invoke
- -[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
- -[PHMediaFormatConversionRequest provenanceAdjustedRenderSourceURL]
- -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:]
- GCC_except_table137
- GCC_except_table152
- GCC_except_table154
- GCC_except_table156
- GCC_except_table169
- GCC_except_table175
- GCC_except_table404
- GCC_except_table406
- GCC_except_table408
- GCC_except_table410
- GCC_except_table412
- GCC_except_table414
- GCC_except_table416
- GCC_except_table418
- GCC_except_table533
- GCC_except_table541
- GCC_except_table571
- GCC_except_table573
- GCC_except_table661
- GCC_except_table663
- GCC_except_table666
- GCC_except_table668
- GCC_except_table681
- GCC_except_table92
- GCC_except_table94
- _OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceAdjustedRenderSourceURL
- ___165-[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
```
