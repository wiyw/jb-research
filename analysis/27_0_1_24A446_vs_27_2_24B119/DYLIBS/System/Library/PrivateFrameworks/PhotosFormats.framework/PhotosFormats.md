## PhotosFormats

> `/System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0xde05c
-  __TEXT.__objc_methlist: 0xcfc0
+916.57.154.0.0
+  __TEXT.__text: 0xe0288
+  __TEXT.__objc_methlist: 0xd210
   __TEXT.__const: 0x33a0
   __TEXT.__dlopen_cstrs: 0x1b7
-  __TEXT.__cstring: 0xe147
+  __TEXT.__cstring: 0xe1f2
   __TEXT.__constg_swiftt: 0xa0
   __TEXT.__swift5_typeref: 0xeb
   __TEXT.__swift5_reflstr: 0x162
   __TEXT.__swift5_fieldmd: 0xf4
   __TEXT.__swift5_proto: 0x2c
   __TEXT.__swift5_types: 0x10
-  __TEXT.__gcc_except_tab: 0x2da4
-  __TEXT.__oslogstring: 0x7954
+  __TEXT.__gcc_except_tab: 0x2e30
+  __TEXT.__oslogstring: 0x7c8e
   __TEXT.__ustring: 0x44
-  __TEXT.__unwind_info: 0x3580
+  __TEXT.__unwind_info: 0x35f8
   __TEXT.__eh_frame: 0x380
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2b18
-  __DATA_CONST.__objc_classlist: 0x590
+  __DATA_CONST.__const: 0x2b20
+  __DATA_CONST.__objc_classlist: 0x5a0
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x64f0
+  __DATA_CONST.__objc_selrefs: 0x6568
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x3c0
+  __DATA_CONST.__objc_superrefs: 0x3d0
   __DATA_CONST.__objc_arraydata: 0x800
-  __DATA_CONST.__got: 0x17a0
+  __DATA_CONST.__got: 0x17f8
   __AUTH_CONST.__const: 0x1da8
-  __AUTH_CONST.__cfstring: 0xcc80
-  __AUTH_CONST.__objc_const: 0x15380
+  __AUTH_CONST.__cfstring: 0xcd00
+  __AUTH_CONST.__objc_const: 0x156d8
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__objc_intobj: 0x900
+  __AUTH_CONST.__objc_intobj: 0x918
   __AUTH_CONST.__objc_arrayobj: 0x348
   __AUTH_CONST.__objc_doubleobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0x208
-  __AUTH_CONST.__auth_got: 0x10e8
+  __AUTH_CONST.__auth_got: 0x10f0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x7a0
-  __AUTH.__data: 0xd0
-  __DATA.__objc_ivar: 0xd8c
-  __DATA.__data: 0xe58
-  __DATA.__bss: 0x1270
+  __DATA.__objc_ivar: 0xdb4
+  __DATA.__data: 0xd0
+  __DATA.__bss: 0x12d0
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x3020
-  __DATA_DIRTY.__bss: 0x858
+  __DATA_DIRTY.__objc_data: 0x3860
+  __DATA_DIRTY.__data: 0xe58
+  __DATA_DIRTY.__bss: 0x838
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5090
-  Symbols:   9739
+  Functions: 5143
+  Symbols:   9831
   CStrings:  0
 
Symbols:
+ +[PFContentProvenanceEmbeddedImageWriter outputContentTypeForRegularImageContentType:]
+ +[PFImageMetadataChangePolicySetStarRating policyWithStarRating:]
+ +[PFImageMetadataChangePolicySetStarRating supportsSecureCoding]
+ +[PFImageMetadataChangePolicySetTitle policyWithTitle:]
+ +[PFImageMetadataChangePolicySetTitle supportsSecureCoding]
+ +[PFSharingUtilities addStarRating:toAVMetadata:]
+ +[PFSharingUtilities addTitle:toAVMetadata:]
+ -[PFAssetBundle setStarRating:]
+ -[PFAssetBundle starRating]
+ -[PFContentProvenanceProcessedImageInfo certificateChainDERData]
+ -[PFContentProvenanceProcessedImageInfo setCertificateChainDERData:]
+ -[PFImageMetadataBuilder setStarRating:]
+ -[PFImageMetadataChangePolicySetStarRating .cxx_destruct]
+ -[PFImageMetadataChangePolicySetStarRating encodeWithCoder:]
+ -[PFImageMetadataChangePolicySetStarRating initWithCoder:]
+ -[PFImageMetadataChangePolicySetStarRating metadataNeedsProcessing:]
+ -[PFImageMetadataChangePolicySetStarRating processMetadata:]
+ -[PFImageMetadataChangePolicySetStarRating setStarRating:]
+ -[PFImageMetadataChangePolicySetStarRating starRating]
+ -[PFImageMetadataChangePolicySetTitle .cxx_destruct]
+ -[PFImageMetadataChangePolicySetTitle encodeWithCoder:]
+ -[PFImageMetadataChangePolicySetTitle initWithCoder:]
+ -[PFImageMetadataChangePolicySetTitle metadataNeedsProcessing:]
+ -[PFImageMetadataChangePolicySetTitle processMetadata:]
+ -[PFImageMetadataChangePolicySetTitle setTitle:]
+ -[PFImageMetadataChangePolicySetTitle title]
+ -[PFMetadata sizeAndDateResourceValues]
+ -[PFMetadata starRating]
+ -[PFMetadataBuilder setStarRating:]
+ -[PFMetadataBuilder starRating]
+ -[PFMetadataImage starRating]
+ -[PFMetadataMovie starRating]
+ -[PFSharingRemakerOptions customStarRating]
+ -[PFSharingRemakerOptions customTitle]
+ -[PFSharingRemakerOptions setCustomStarRating:]
+ -[PFSharingRemakerOptions setCustomTitle:]
+ -[PFSharingRemakerOptions setShouldStripRating:]
+ -[PFSharingRemakerOptions setShouldStripTitle:]
+ -[PFSharingRemakerOptions shouldStripRating]
+ -[PFSharingRemakerOptions shouldStripTitle]
+ -[PFVideoMetadataBuilder starRatingItem]
+ -[PFVideoSharingOperation customStarRating]
+ -[PFVideoSharingOperation customTitle]
+ -[PFVideoSharingOperation setCustomStarRating:]
+ -[PFVideoSharingOperation setCustomTitle:]
+ -[PFVideoSharingOperation setShouldStripRating:]
+ -[PFVideoSharingOperation setShouldStripTitle:]
+ -[PFVideoSharingOperation shouldStripRating]
+ -[PFVideoSharingOperation shouldStripTitle]
+ GCC_except_table1164
+ GCC_except_table1545
+ GCC_except_table1552
+ GCC_except_table1555
+ GCC_except_table1590
+ GCC_except_table1604
+ GCC_except_table1710
+ GCC_except_table1763
+ GCC_except_table1784
+ GCC_except_table1786
+ GCC_except_table1862
+ GCC_except_table1866
+ GCC_except_table1877
+ GCC_except_table1916
+ GCC_except_table1918
+ GCC_except_table1944
+ GCC_except_table1955
+ GCC_except_table1981
+ GCC_except_table1989
+ GCC_except_table1992
+ GCC_except_table2032
+ GCC_except_table2037
+ GCC_except_table2042
+ GCC_except_table2053
+ GCC_except_table2158
+ GCC_except_table2189
+ GCC_except_table2199
+ GCC_except_table2205
+ GCC_except_table2209
+ GCC_except_table2223
+ GCC_except_table2287
+ GCC_except_table2296
+ GCC_except_table2316
+ GCC_except_table2392
+ GCC_except_table2395
+ GCC_except_table2402
+ GCC_except_table2506
+ GCC_except_table2522
+ GCC_except_table2620
+ GCC_except_table2621
+ GCC_except_table2628
+ GCC_except_table2630
+ GCC_except_table2631
+ GCC_except_table2633
+ GCC_except_table2636
+ GCC_except_table2680
+ GCC_except_table2703
+ GCC_except_table2705
+ GCC_except_table2833
+ GCC_except_table303
+ GCC_except_table3114
+ GCC_except_table3180
+ GCC_except_table3181
+ GCC_except_table3184
+ GCC_except_table3187
+ GCC_except_table3193
+ GCC_except_table3195
+ GCC_except_table3196
+ GCC_except_table3197
+ GCC_except_table3199
+ GCC_except_table3200
+ GCC_except_table3207
+ GCC_except_table3208
+ GCC_except_table3209
+ GCC_except_table3210
+ GCC_except_table3212
+ GCC_except_table3213
+ GCC_except_table3214
+ GCC_except_table3216
+ GCC_except_table3224
+ GCC_except_table3226
+ GCC_except_table3229
+ GCC_except_table3232
+ GCC_except_table3239
+ GCC_except_table3240
+ GCC_except_table3241
+ GCC_except_table3263
+ GCC_except_table3265
+ GCC_except_table3266
+ GCC_except_table3272
+ GCC_except_table3273
+ GCC_except_table3274
+ GCC_except_table3275
+ GCC_except_table3276
+ GCC_except_table3282
+ GCC_except_table3285
+ GCC_except_table3342
+ GCC_except_table3489
+ GCC_except_table3493
+ GCC_except_table3495
+ GCC_except_table3496
+ GCC_except_table3499
+ GCC_except_table3500
+ GCC_except_table3504
+ GCC_except_table3510
+ GCC_except_table3517
+ GCC_except_table3520
+ GCC_except_table3521
+ GCC_except_table3528
+ GCC_except_table3529
+ GCC_except_table3530
+ GCC_except_table3536
+ GCC_except_table3543
+ GCC_except_table3544
+ GCC_except_table3561
+ GCC_except_table3607
+ GCC_except_table3611
+ GCC_except_table3614
+ GCC_except_table3615
+ GCC_except_table3665
+ GCC_except_table3674
+ GCC_except_table3749
+ GCC_except_table3817
+ GCC_except_table3819
+ GCC_except_table3836
+ GCC_except_table3846
+ GCC_except_table3861
+ GCC_except_table3863
+ GCC_except_table3952
+ GCC_except_table4187
+ GCC_except_table4189
+ GCC_except_table4191
+ GCC_except_table4198
+ GCC_except_table4203
+ GCC_except_table4213
+ GCC_except_table4291
+ GCC_except_table4293
+ GCC_except_table4300
+ GCC_except_table4304
+ GCC_except_table4311
+ GCC_except_table4313
+ GCC_except_table4315
+ GCC_except_table4316
+ GCC_except_table4317
+ GCC_except_table4324
+ GCC_except_table4325
+ GCC_except_table4328
+ GCC_except_table4333
+ GCC_except_table4334
+ GCC_except_table4337
+ GCC_except_table4340
+ GCC_except_table4353
+ GCC_except_table4360
+ GCC_except_table4366
+ GCC_except_table4375
+ GCC_except_table4404
+ GCC_except_table4409
+ GCC_except_table4410
+ GCC_except_table4411
+ GCC_except_table4412
+ GCC_except_table4413
+ GCC_except_table4415
+ GCC_except_table4420
+ GCC_except_table4421
+ GCC_except_table4423
+ GCC_except_table4424
+ GCC_except_table4426
+ GCC_except_table4427
+ GCC_except_table4428
+ GCC_except_table4429
+ GCC_except_table4430
+ GCC_except_table4431
+ GCC_except_table4433
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4437
+ GCC_except_table4438
+ GCC_except_table4441
+ GCC_except_table4513
+ GCC_except_table4580
+ GCC_except_table4586
+ GCC_except_table4655
+ GCC_except_table4659
+ GCC_except_table4665
+ GCC_except_table4683
+ GCC_except_table4699
+ GCC_except_table4700
+ GCC_except_table4701
+ GCC_except_table4703
+ GCC_except_table4705
+ GCC_except_table4983
+ GCC_except_table4990
+ GCC_except_table4992
+ GCC_except_table668
+ GCC_except_table671
+ GCC_except_table731
+ GCC_except_table738
+ GCC_except_table782
+ GCC_except_table783
+ GCC_except_table792
+ GCC_except_table798
+ GCC_except_table799
+ GCC_except_table800
+ GCC_except_table803
+ GCC_except_table807
+ GCC_except_table808
+ GCC_except_table809
+ GCC_except_table810
+ GCC_except_table811
+ GCC_except_table817
+ GCC_except_table823
+ GCC_except_table824
+ GCC_except_table835
+ GCC_except_table836
+ GCC_except_table837
+ GCC_except_table838
+ GCC_except_table840
+ GCC_except_table841
+ GCC_except_table842
+ GCC_except_table843
+ GCC_except_table844
+ GCC_except_table847
+ GCC_except_table849
+ GCC_except_table850
+ GCC_except_table851
+ GCC_except_table852
+ GCC_except_table861
+ GCC_except_table875
+ GCC_except_table877
+ GCC_except_table878
+ GCC_except_table879
+ _AVMetadataIdentifierQuickTimeMetadataRatingUser
+ _AVMetadataQuickTimeMetadataKeyRatingUser
+ _CMPhotoCodecSessionPoolFlush
+ _NSURLContentModificationDateKey
+ _NSURLCreationDateKey
+ _NSURLFileSizeKey
+ _NSURLIsAliasFileKey
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetStarRating
+ _OBJC_CLASS_$_PFImageMetadataChangePolicySetTitle
+ _OBJC_IVAR_$_PFContentProvenanceProcessedImageInfo._certificateChainDERData
+ _OBJC_IVAR_$_PFImageMetadataChangePolicySetStarRating._starRating
+ _OBJC_IVAR_$_PFImageMetadataChangePolicySetTitle._title
+ _OBJC_IVAR_$_PFMetadata._sizeAndDateResourceValues
+ _OBJC_IVAR_$_PFMetadataBuilder._starRating
+ _OBJC_IVAR_$_PFSharingRemakerOptions._customStarRating
+ _OBJC_IVAR_$_PFSharingRemakerOptions._customTitle
+ _OBJC_IVAR_$_PFSharingRemakerOptions._shouldStripRating
+ _OBJC_IVAR_$_PFSharingRemakerOptions._shouldStripTitle
+ _OBJC_IVAR_$_PFVideoSharingOperation._customStarRating
+ _OBJC_IVAR_$_PFVideoSharingOperation._customTitle
+ _OBJC_IVAR_$_PFVideoSharingOperation._shouldStripRating
+ _OBJC_IVAR_$_PFVideoSharingOperation._shouldStripTitle
+ _OBJC_METACLASS_$_PFImageMetadataChangePolicySetStarRating
+ _OBJC_METACLASS_$_PFImageMetadataChangePolicySetTitle
+ _PFAssetBundleMetadataStarRatingKey
+ _PFFigDecodeOptionsWithMaxPixelSize
+ _PFFigEncodeOptionsWithTilingEnabled
+ _PFMetadataRealPathFromFileAlias
+ _PFPosterSanitizedNormalizedFrame
+ __OBJC_$_CLASS_METHODS_PFContentProvenanceEmbeddedImageWriter
+ __OBJC_$_CLASS_METHODS_PFImageMetadataChangePolicySetStarRating
+ __OBJC_$_CLASS_METHODS_PFImageMetadataChangePolicySetTitle
+ __OBJC_$_INSTANCE_METHODS_PFImageMetadataChangePolicySetStarRating
+ __OBJC_$_INSTANCE_METHODS_PFImageMetadataChangePolicySetTitle
+ __OBJC_$_INSTANCE_VARIABLES_PFImageMetadataChangePolicySetStarRating
+ __OBJC_$_INSTANCE_VARIABLES_PFImageMetadataChangePolicySetTitle
+ __OBJC_$_PROP_LIST_PFImageMetadataChangePolicySetStarRating
+ __OBJC_$_PROP_LIST_PFImageMetadataChangePolicySetTitle
+ __OBJC_CLASS_RO_$_PFImageMetadataChangePolicySetStarRating
+ __OBJC_CLASS_RO_$_PFImageMetadataChangePolicySetTitle
+ __OBJC_METACLASS_RO_$_PFImageMetadataChangePolicySetStarRating
+ __OBJC_METACLASS_RO_$_PFImageMetadataChangePolicySetTitle
+ __PFDecodeImageFromSource
+ ___29-[PFMetadataMovie starRating]_block_invoke
+ ___42-[PFVideoSharingOperation setCustomTitle:]_block_invoke
+ ___47-[PFVideoSharingOperation setCustomStarRating:]_block_invoke
+ ___47-[PFVideoSharingOperation setShouldStripTitle:]_block_invoke
+ ___48-[PFVideoSharingOperation setShouldStripRating:]_block_invoke
+ ___block_descriptor_104_e8_32s40r48r56r64r72r80r88r96r_e5_v8?0lr40l8s32l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8
+ _kCGImagePropertyIPTCStarRating
+ _kCMPhotoCompressionOption_Tiling
+ _kCMPhotoDecompressionOption_ApplyTransform
+ _kCMPhotoDecompressionOption_MaxPixelSize
+ _kCMPhotoProvenanceResult_CertificateChainData
- -[PFContentProvenanceResourceInfo developmentStatus]
- -[PFContentProvenanceResourceInfo timestampStatus]
- -[PFImageMetadataBuilder setPeopleNames:]
- -[PFMetadataBuilder combinedKeywordsAndPeople]
- -[PFMetadataBuilder peopleNames]
- -[PFMetadataBuilder setPeopleNames:]
- GCC_except_table1142
- GCC_except_table1520
- GCC_except_table1527
- GCC_except_table1530
- GCC_except_table1565
- GCC_except_table1579
- GCC_except_table1685
- GCC_except_table1738
- GCC_except_table1759
- GCC_except_table1761
- GCC_except_table1837
- GCC_except_table1841
- GCC_except_table1852
- GCC_except_table1891
- GCC_except_table1893
- GCC_except_table1919
- GCC_except_table1930
- GCC_except_table1956
- GCC_except_table1964
- GCC_except_table1967
- GCC_except_table1982
- GCC_except_table2012
- GCC_except_table2017
- GCC_except_table2028
- GCC_except_table2131
- GCC_except_table2162
- GCC_except_table2169
- GCC_except_table2172
- GCC_except_table2178
- GCC_except_table2182
- GCC_except_table2260
- GCC_except_table2269
- GCC_except_table2289
- GCC_except_table2357
- GCC_except_table2360
- GCC_except_table2367
- GCC_except_table2471
- GCC_except_table2487
- GCC_except_table2583
- GCC_except_table2584
- GCC_except_table2591
- GCC_except_table2593
- GCC_except_table2594
- GCC_except_table2596
- GCC_except_table2599
- GCC_except_table2643
- GCC_except_table2666
- GCC_except_table2668
- GCC_except_table2796
- GCC_except_table285
- GCC_except_table3076
- GCC_except_table3142
- GCC_except_table3143
- GCC_except_table3146
- GCC_except_table3148
- GCC_except_table3149
- GCC_except_table3153
- GCC_except_table3155
- GCC_except_table3157
- GCC_except_table3158
- GCC_except_table3159
- GCC_except_table3161
- GCC_except_table3162
- GCC_except_table3169
- GCC_except_table3170
- GCC_except_table3171
- GCC_except_table3172
- GCC_except_table3174
- GCC_except_table3175
- GCC_except_table3176
- GCC_except_table3178
- GCC_except_table3188
- GCC_except_table3194
- GCC_except_table3201
- GCC_except_table3202
- GCC_except_table3203
- GCC_except_table3225
- GCC_except_table3227
- GCC_except_table3228
- GCC_except_table3234
- GCC_except_table3235
- GCC_except_table3236
- GCC_except_table3237
- GCC_except_table3238
- GCC_except_table3244
- GCC_except_table3247
- GCC_except_table3304
- GCC_except_table3451
- GCC_except_table3453
- GCC_except_table3454
- GCC_except_table3455
- GCC_except_table3457
- GCC_except_table3458
- GCC_except_table3460
- GCC_except_table3461
- GCC_except_table3462
- GCC_except_table3466
- GCC_except_table3472
- GCC_except_table3479
- GCC_except_table3482
- GCC_except_table3483
- GCC_except_table3485
- GCC_except_table3490
- GCC_except_table3505
- GCC_except_table3506
- GCC_except_table3569
- GCC_except_table3573
- GCC_except_table3576
- GCC_except_table3577
- GCC_except_table3627
- GCC_except_table3636
- GCC_except_table3711
- GCC_except_table3779
- GCC_except_table3781
- GCC_except_table3798
- GCC_except_table3808
- GCC_except_table3823
- GCC_except_table3825
- GCC_except_table3914
- GCC_except_table4149
- GCC_except_table4151
- GCC_except_table4153
- GCC_except_table4160
- GCC_except_table4165
- GCC_except_table4175
- GCC_except_table4246
- GCC_except_table4247
- GCC_except_table4248
- GCC_except_table4252
- GCC_except_table4254
- GCC_except_table4261
- GCC_except_table4262
- GCC_except_table4265
- GCC_except_table4272
- GCC_except_table4274
- GCC_except_table4276
- GCC_except_table4277
- GCC_except_table4278
- GCC_except_table4289
- GCC_except_table4294
- GCC_except_table4295
- GCC_except_table4297
- GCC_except_table4298
- GCC_except_table4314
- GCC_except_table4321
- GCC_except_table4327
- GCC_except_table4331
- GCC_except_table4371
- GCC_except_table4372
- GCC_except_table4373
- GCC_except_table4374
- GCC_except_table4376
- GCC_except_table4381
- GCC_except_table4382
- GCC_except_table4384
- GCC_except_table4385
- GCC_except_table4387
- GCC_except_table4388
- GCC_except_table4389
- GCC_except_table4390
- GCC_except_table4391
- GCC_except_table4392
- GCC_except_table4394
- GCC_except_table4396
- GCC_except_table4397
- GCC_except_table4398
- GCC_except_table4399
- GCC_except_table4402
- GCC_except_table4474
- GCC_except_table4541
- GCC_except_table4547
- GCC_except_table4616
- GCC_except_table4620
- GCC_except_table4622
- GCC_except_table4625
- GCC_except_table4626
- GCC_except_table4644
- GCC_except_table4660
- GCC_except_table4662
- GCC_except_table4666
- GCC_except_table4930
- GCC_except_table4937
- GCC_except_table4939
- GCC_except_table633
- GCC_except_table649
- GCC_except_table710
- GCC_except_table717
- GCC_except_table756
- GCC_except_table760
- GCC_except_table761
- GCC_except_table770
- GCC_except_table773
- GCC_except_table774
- GCC_except_table776
- GCC_except_table777
- GCC_except_table781
- GCC_except_table785
- GCC_except_table786
- GCC_except_table787
- GCC_except_table788
- GCC_except_table789
- GCC_except_table790
- GCC_except_table801
- GCC_except_table802
- GCC_except_table806
- GCC_except_table813
- GCC_except_table814
- GCC_except_table815
- GCC_except_table816
- GCC_except_table819
- GCC_except_table820
- GCC_except_table821
- GCC_except_table822
- GCC_except_table825
- GCC_except_table827
- GCC_except_table829
- GCC_except_table830
- GCC_except_table839
- GCC_except_table853
- GCC_except_table855
- GCC_except_table857
- _OBJC_IVAR_$_PFContentProvenanceResourceInfo._developmentStatus
- _OBJC_IVAR_$_PFContentProvenanceResourceInfo._timestampStatus
- _OBJC_IVAR_$_PFMetadataBuilder._peopleNames
- ___block_descriptor_88_e8_32s40r48r56r64r72r80r_e5_v8?0lr40l8s32l8r48l8r56l8r64l8r72l8r80l8
- _kCGImagePropertyIPTCExtPersonInImage
```
