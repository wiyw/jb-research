## PhotosGraph

> `/System/Library/PrivateFrameworks/PhotosGraph.framework/PhotosGraph`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x620bc8
-  __TEXT.__objc_methlist: 0x2c1b4
-  __TEXT.__const: 0x1c760
+916.57.154.0.0
+  __TEXT.__text: 0x625620
+  __TEXT.__objc_methlist: 0x2c5cc
+  __TEXT.__const: 0x1c800
   __TEXT.__swift5_typeref: 0x8738
   __TEXT.__swift5_reflstr: 0x743a
   __TEXT.__swift5_assocty: 0x5c0

   __TEXT.__swift5_protos: 0xa4
   __TEXT.__swift5_proto: 0x1260
   __TEXT.__swift5_types: 0xc40
-  __TEXT.__cstring: 0x33f3a
+  __TEXT.__cstring: 0x34479
   __TEXT.__swift5_capture: 0x2dd8
-  __TEXT.__oslogstring: 0x27bd1
+  __TEXT.__oslogstring: 0x28397
   __TEXT.__swift_as_entry: 0xec
   __TEXT.__swift_as_ret: 0xe0
   __TEXT.__swift_as_cont: 0x260
   __TEXT.__swift5_mpenum: 0x80
-  __TEXT.__gcc_except_tab: 0x118e0
+  __TEXT.__gcc_except_tab: 0x11aa0
   __TEXT.__ustring: 0x7e6
-  __TEXT.__unwind_info: 0x11810
-  __TEXT.__eh_frame: 0xfd44
+  __TEXT.__unwind_info: 0x118f0
+  __TEXT.__eh_frame: 0xfe34
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd1e8
-  __DATA_CONST.__objc_classlist: 0x2ce0
+  __DATA_CONST.__const: 0xd258
+  __DATA_CONST.__objc_classlist: 0x2d10
   __DATA_CONST.__objc_catlist: 0x98
-  __DATA_CONST.__objc_protolist: 0x460
+  __DATA_CONST.__objc_protolist: 0x468
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12948
+  __DATA_CONST.__objc_selrefs: 0x12a48
   __DATA_CONST.__objc_protorefs: 0xf8
-  __DATA_CONST.__objc_superrefs: 0x1490
-  __DATA_CONST.__objc_arraydata: 0x38c0
-  __DATA_CONST.__got: 0x3af8
-  __AUTH_CONST.__const: 0x1bc60
-  __AUTH_CONST.__cfstring: 0x255e0
-  __AUTH_CONST.__objc_const: 0x66d38
-  __AUTH_CONST.__objc_intobj: 0x3318
-  __AUTH_CONST.__objc_arrayobj: 0x1cf8
+  __DATA_CONST.__objc_superrefs: 0x14b0
+  __DATA_CONST.__objc_arraydata: 0x38e0
+  __DATA_CONST.__got: 0x3b28
+  __AUTH_CONST.__const: 0x1bca0
+  __AUTH_CONST.__cfstring: 0x25660
+  __AUTH_CONST.__objc_const: 0x67710
+  __AUTH_CONST.__objc_intobj: 0x3378
+  __AUTH_CONST.__objc_arrayobj: 0x1d28
   __AUTH_CONST.__objc_doubleobj: 0x2b0
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_floatobj: 0x30
-  __AUTH_CONST.__auth_got: 0x2468
+  __AUTH_CONST.__auth_got: 0x2470
   __AUTH_CONST.__auth_ptr: 0x10b0
-  __AUTH.__objc_data: 0x6938
+  __AUTH.__objc_data: 0x6a28
   __AUTH.__data: 0xc3f0
-  __DATA.__objc_ivar: 0x2d84
+  __DATA.__objc_ivar: 0x2de4
   __DATA.__data: 0x60a8
   __DATA.__bss: 0x199b8
   __DATA.__common: 0x238
-  __DATA_DIRTY.__objc_data: 0x13100
-  __DATA_DIRTY.__data: 0x4da0
+  __DATA_DIRTY.__objc_data: 0x131f0
+  __DATA_DIRTY.__data: 0x4dd0
   __DATA_DIRTY.__bss: 0x8670
   __DATA_DIRTY.__common: 0x3a0
   - /System/Library/Frameworks/CoreData.framework/CoreData

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 26501
-  Symbols:   32808
+  Functions: 26594
+  Symbols:   32967
   CStrings:  0
 
Symbols:
+ +[PGAmbientGroupWallpaperSuggester suggestionSubtypes]
+ +[PGAmbientGroupWallpaperSuggester suggestionTypes]
+ +[PGGroupWallpaperSuggester assetPrefilteringInternalPredicate]
+ +[PGGroupWallpaperSuggester candidate:passesFilteringWithContext:curationContext:statistics:]
+ +[PGGroupWallpaperSuggester filtersForTopSuggestions]
+ +[PGGroupWallpaperSuggester personPrefilteringInternalPredicateWithContext:]
+ +[PGGroupWallpaperSuggester petPrefilteringInternalPredicateWithContext:]
+ +[PGGroupWallpaperSuggester suggestionSubtypes]
+ +[PGGroupWallpaperSuggester suggestionTypes]
+ +[PGTopGroupWallpaperSuggester filtersForTopSuggestions]
+ +[PGTopGroupWallpaperSuggester suggestionSubtypes]
+ +[PGUserDefaults groupWallpaperEnabled]
+ -[PGAmbientGroupWallpaperSuggester setupFilteringContexts]
+ -[PGGroupWallpaperSuggester .cxx_destruct]
+ -[PGGroupWallpaperSuggester _logPosterFilteringStatistics:]
+ -[PGGroupWallpaperSuggester candidatesForSocialGroup:withNumberOfPeople:progressReporter:]
+ -[PGGroupWallpaperSuggester fetchFilteredExclusiveAssetsForSocialGroup:]
+ -[PGGroupWallpaperSuggester fetchFilteredFacesByAssetLocalIdentifierForAssets:detectionType:]
+ -[PGGroupWallpaperSuggester fetchPersonsForSocialGroup:]
+ -[PGGroupWallpaperSuggester fetchSocialGroups]
+ -[PGGroupWallpaperSuggester initWithSession:]
+ -[PGGroupWallpaperSuggester primaryFilteringContext]
+ -[PGGroupWallpaperSuggester rankedAndDedupedCandidatesFromCandidates:progressReporter:]
+ -[PGGroupWallpaperSuggester secondaryFilteringContext]
+ -[PGGroupWallpaperSuggester setPrimaryFilteringContext:]
+ -[PGGroupWallpaperSuggester setSecondaryFilteringContext:]
+ -[PGGroupWallpaperSuggester setupFilteringContexts]
+ -[PGGroupWallpaperSuggester sortedCandidatesBySocialGroupLocalIdentifierFromSocialGroups:personsBySocialGroupLocalIdentifierCache:progressReporter:]
+ -[PGGroupWallpaperSuggester suggestionsWithOptions:progress:]
+ -[PGGroupWallpaperSuggesterFilteringContext _commonInitWithOrientation:]
+ -[PGGroupWallpaperSuggesterFilteringContext absoluteMinimumWallpaperScore]
+ -[PGGroupWallpaperSuggesterFilteringContext bypassCropScoreCheck]
+ -[PGGroupWallpaperSuggesterFilteringContext copyWithZone:]
+ -[PGGroupWallpaperSuggesterFilteringContext ignoreClockOverlap]
+ -[PGGroupWallpaperSuggesterFilteringContext initForAmbient]
+ -[PGGroupWallpaperSuggesterFilteringContext initForGroupsInOrientation:]
+ -[PGGroupWallpaperSuggesterFilteringContext initForTopGroupsInOrientation:]
+ -[PGGroupWallpaperSuggesterFilteringContext maximumCropZoomRatio]
+ -[PGGroupWallpaperSuggesterFilteringContext maximumLowLightScore]
+ -[PGGroupWallpaperSuggesterFilteringContext minimumCropScore]
+ -[PGGroupWallpaperSuggesterFilteringContext minimumWallpaperScore]
+ -[PGGroupWallpaperSuggesterFilteringContext orientation]
+ -[PGGroupWallpaperSuggesterFilteringContext personMaximumFaceRoll]
+ -[PGGroupWallpaperSuggesterFilteringContext personMaximumFaceSize]
+ -[PGGroupWallpaperSuggesterFilteringContext personMinimumFaceQuality]
+ -[PGGroupWallpaperSuggesterFilteringContext personMinimumFaceSize]
+ -[PGGroupWallpaperSuggesterFilteringContext personRequiresNoBlink]
+ -[PGGroupWallpaperSuggesterFilteringContext personRequiresSmile]
+ -[PGGroupWallpaperSuggesterFilteringContext petMaximumFaceSize]
+ -[PGGroupWallpaperSuggesterFilteringContext petMinimumFaceSize]
+ -[PGGroupWallpaperSuggesterFilteringContext setAbsoluteMinimumWallpaperScore:]
+ -[PGGroupWallpaperSuggesterFilteringContext setBypassCropScoreCheck:]
+ -[PGGroupWallpaperSuggesterFilteringContext setIgnoreClockOverlap:]
+ -[PGGroupWallpaperSuggesterFilteringContext setMaximumCropZoomRatio:]
+ -[PGGroupWallpaperSuggesterFilteringContext setMaximumLowLightScore:]
+ -[PGGroupWallpaperSuggesterFilteringContext setMinimumCropScore:]
+ -[PGGroupWallpaperSuggesterFilteringContext setMinimumWallpaperScore:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonMaximumFaceRoll:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonMaximumFaceSize:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonMinimumFaceQuality:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonMinimumFaceSize:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonRequiresNoBlink:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPersonRequiresSmile:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPetMaximumFaceSize:]
+ -[PGGroupWallpaperSuggesterFilteringContext setPetMinimumFaceSize:]
+ -[PGGroupWallpaperSuggesterFilteringContext setTimeIntervalForCandidateDeduping:]
+ -[PGGroupWallpaperSuggesterFilteringContext timeIntervalForCandidateDeduping]
+ -[PGGroupWallpaperSuggestion .cxx_destruct]
+ -[PGGroupWallpaperSuggestion initWithPersonLocalIdentifiers:type:subtype:asset:]
+ -[PGGroupWallpaperSuggestion suggestedPersonLocalIdentifiers]
+ -[PGGroupWallpaperSuggestionCandidate .cxx_destruct]
+ -[PGGroupWallpaperSuggestionCandidate asset]
+ -[PGGroupWallpaperSuggestionCandidate cropResult]
+ -[PGGroupWallpaperSuggestionCandidate faces]
+ -[PGGroupWallpaperSuggestionCandidate initWithFaces:inAsset:]
+ -[PGTopGroupWallpaperSuggester setupFilteringContexts]
+ GCC_except_table10155
+ GCC_except_table10162
+ GCC_except_table10182
+ GCC_except_table10203
+ GCC_except_table10228
+ GCC_except_table10236
+ GCC_except_table10259
+ GCC_except_table10274
+ GCC_except_table10286
+ GCC_except_table10289
+ GCC_except_table10309
+ GCC_except_table10320
+ GCC_except_table10336
+ GCC_except_table10342
+ GCC_except_table10348
+ GCC_except_table10351
+ GCC_except_table10372
+ GCC_except_table10450
+ GCC_except_table10512
+ GCC_except_table10513
+ GCC_except_table10514
+ GCC_except_table10515
+ GCC_except_table10516
+ GCC_except_table10517
+ GCC_except_table10549
+ GCC_except_table10606
+ GCC_except_table10608
+ GCC_except_table10631
+ GCC_except_table10646
+ GCC_except_table10669
+ GCC_except_table10696
+ GCC_except_table10699
+ GCC_except_table10745
+ GCC_except_table10770
+ GCC_except_table10804
+ GCC_except_table10816
+ GCC_except_table10826
+ GCC_except_table10828
+ GCC_except_table10832
+ GCC_except_table10914
+ GCC_except_table10919
+ GCC_except_table10977
+ GCC_except_table10982
+ GCC_except_table10992
+ GCC_except_table10998
+ GCC_except_table11000
+ GCC_except_table11007
+ GCC_except_table11045
+ GCC_except_table11104
+ GCC_except_table11234
+ GCC_except_table11238
+ GCC_except_table11257
+ GCC_except_table11537
+ GCC_except_table11585
+ GCC_except_table11613
+ GCC_except_table11670
+ GCC_except_table11677
+ GCC_except_table11710
+ GCC_except_table11712
+ GCC_except_table11718
+ GCC_except_table11733
+ GCC_except_table11740
+ GCC_except_table11751
+ GCC_except_table11939
+ GCC_except_table11948
+ GCC_except_table11949
+ GCC_except_table11972
+ GCC_except_table11981
+ GCC_except_table11994
+ GCC_except_table12005
+ GCC_except_table12033
+ GCC_except_table12045
+ GCC_except_table12139
+ GCC_except_table12309
+ GCC_except_table12428
+ GCC_except_table12429
+ GCC_except_table12442
+ GCC_except_table12445
+ GCC_except_table12456
+ GCC_except_table12458
+ GCC_except_table12461
+ GCC_except_table12464
+ GCC_except_table12468
+ GCC_except_table12471
+ GCC_except_table12474
+ GCC_except_table12530
+ GCC_except_table12541
+ GCC_except_table12655
+ GCC_except_table12668
+ GCC_except_table12696
+ GCC_except_table12750
+ GCC_except_table12752
+ GCC_except_table12768
+ GCC_except_table12774
+ GCC_except_table12813
+ GCC_except_table12817
+ GCC_except_table12849
+ GCC_except_table12854
+ GCC_except_table12910
+ GCC_except_table13004
+ GCC_except_table13087
+ GCC_except_table13092
+ GCC_except_table13130
+ GCC_except_table13137
+ GCC_except_table13163
+ GCC_except_table13165
+ GCC_except_table13167
+ GCC_except_table13234
+ GCC_except_table13265
+ GCC_except_table13275
+ GCC_except_table13290
+ GCC_except_table13300
+ GCC_except_table13320
+ GCC_except_table13334
+ GCC_except_table13337
+ GCC_except_table13353
+ GCC_except_table13361
+ GCC_except_table13363
+ GCC_except_table13365
+ GCC_except_table13422
+ GCC_except_table13424
+ GCC_except_table13464
+ GCC_except_table13493
+ GCC_except_table13497
+ GCC_except_table13502
+ GCC_except_table13510
+ GCC_except_table13722
+ GCC_except_table13727
+ GCC_except_table13732
+ GCC_except_table13743
+ GCC_except_table13752
+ GCC_except_table13755
+ GCC_except_table13757
+ GCC_except_table13798
+ GCC_except_table13800
+ GCC_except_table13804
+ GCC_except_table13814
+ GCC_except_table13821
+ GCC_except_table13833
+ GCC_except_table13855
+ GCC_except_table13911
+ GCC_except_table13921
+ GCC_except_table13924
+ GCC_except_table13947
+ GCC_except_table13959
+ GCC_except_table13962
+ GCC_except_table13971
+ GCC_except_table13976
+ GCC_except_table13977
+ GCC_except_table13990
+ GCC_except_table13995
+ GCC_except_table14005
+ GCC_except_table14248
+ GCC_except_table14250
+ GCC_except_table14252
+ GCC_except_table14256
+ GCC_except_table14315
+ GCC_except_table2064
+ GCC_except_table2244
+ GCC_except_table2306
+ GCC_except_table2323
+ GCC_except_table2328
+ GCC_except_table2332
+ GCC_except_table2337
+ GCC_except_table2339
+ GCC_except_table2360
+ GCC_except_table2417
+ GCC_except_table2624
+ GCC_except_table2698
+ GCC_except_table2729
+ GCC_except_table2755
+ GCC_except_table2759
+ GCC_except_table2766
+ GCC_except_table2793
+ GCC_except_table2801
+ GCC_except_table2873
+ GCC_except_table2891
+ GCC_except_table2905
+ GCC_except_table3019
+ GCC_except_table3220
+ GCC_except_table3222
+ GCC_except_table3225
+ GCC_except_table3323
+ GCC_except_table3380
+ GCC_except_table3415
+ GCC_except_table3434
+ GCC_except_table3494
+ GCC_except_table3501
+ GCC_except_table3505
+ GCC_except_table3509
+ GCC_except_table3512
+ GCC_except_table3516
+ GCC_except_table3586
+ GCC_except_table3594
+ GCC_except_table3598
+ GCC_except_table3606
+ GCC_except_table3613
+ GCC_except_table3683
+ GCC_except_table3693
+ GCC_except_table3694
+ GCC_except_table3700
+ GCC_except_table3746
+ GCC_except_table3759
+ GCC_except_table3788
+ GCC_except_table3801
+ GCC_except_table3803
+ GCC_except_table3820
+ GCC_except_table3884
+ GCC_except_table3889
+ GCC_except_table3944
+ GCC_except_table3945
+ GCC_except_table3946
+ GCC_except_table3978
+ GCC_except_table4008
+ GCC_except_table4016
+ GCC_except_table4047
+ GCC_except_table4052
+ GCC_except_table4054
+ GCC_except_table4056
+ GCC_except_table4059
+ GCC_except_table4070
+ GCC_except_table4140
+ GCC_except_table4145
+ GCC_except_table4156
+ GCC_except_table4167
+ GCC_except_table4177
+ GCC_except_table4179
+ GCC_except_table4276
+ GCC_except_table4278
+ GCC_except_table4285
+ GCC_except_table4340
+ GCC_except_table4374
+ GCC_except_table4383
+ GCC_except_table4405
+ GCC_except_table4421
+ GCC_except_table4423
+ GCC_except_table4429
+ GCC_except_table4430
+ GCC_except_table4434
+ GCC_except_table4448
+ GCC_except_table4452
+ GCC_except_table4456
+ GCC_except_table4457
+ GCC_except_table4458
+ GCC_except_table4495
+ GCC_except_table4514
+ GCC_except_table4547
+ GCC_except_table4556
+ GCC_except_table4762
+ GCC_except_table4766
+ GCC_except_table4777
+ GCC_except_table4780
+ GCC_except_table4843
+ GCC_except_table4845
+ GCC_except_table4849
+ GCC_except_table4852
+ GCC_except_table4860
+ GCC_except_table4939
+ GCC_except_table4965
+ GCC_except_table4967
+ GCC_except_table4969
+ GCC_except_table4971
+ GCC_except_table4973
+ GCC_except_table5030
+ GCC_except_table5229
+ GCC_except_table5244
+ GCC_except_table5245
+ GCC_except_table5355
+ GCC_except_table5360
+ GCC_except_table5364
+ GCC_except_table5368
+ GCC_except_table5377
+ GCC_except_table5379
+ GCC_except_table5410
+ GCC_except_table5411
+ GCC_except_table5412
+ GCC_except_table5413
+ GCC_except_table5414
+ GCC_except_table5415
+ GCC_except_table5425
+ GCC_except_table5427
+ GCC_except_table5433
+ GCC_except_table5442
+ GCC_except_table5487
+ GCC_except_table5491
+ GCC_except_table5688
+ GCC_except_table5711
+ GCC_except_table5714
+ GCC_except_table5783
+ GCC_except_table5789
+ GCC_except_table5816
+ GCC_except_table5851
+ GCC_except_table5864
+ GCC_except_table5874
+ GCC_except_table5879
+ GCC_except_table5984
+ GCC_except_table5994
+ GCC_except_table5997
+ GCC_except_table6004
+ GCC_except_table6028
+ GCC_except_table6082
+ GCC_except_table6086
+ GCC_except_table6088
+ GCC_except_table6090
+ GCC_except_table6095
+ GCC_except_table6097
+ GCC_except_table6141
+ GCC_except_table6153
+ GCC_except_table6154
+ GCC_except_table6158
+ GCC_except_table6192
+ GCC_except_table6217
+ GCC_except_table6257
+ GCC_except_table6259
+ GCC_except_table6267
+ GCC_except_table6270
+ GCC_except_table6291
+ GCC_except_table6297
+ GCC_except_table6305
+ GCC_except_table6324
+ GCC_except_table6384
+ GCC_except_table6388
+ GCC_except_table6390
+ GCC_except_table6396
+ GCC_except_table6397
+ GCC_except_table6401
+ GCC_except_table6403
+ GCC_except_table6423
+ GCC_except_table6461
+ GCC_except_table6492
+ GCC_except_table6494
+ GCC_except_table6541
+ GCC_except_table6545
+ GCC_except_table6549
+ GCC_except_table6552
+ GCC_except_table6555
+ GCC_except_table6558
+ GCC_except_table6560
+ GCC_except_table6565
+ GCC_except_table6575
+ GCC_except_table6608
+ GCC_except_table6612
+ GCC_except_table6619
+ GCC_except_table6708
+ GCC_except_table6812
+ GCC_except_table6817
+ GCC_except_table6819
+ GCC_except_table6827
+ GCC_except_table6833
+ GCC_except_table6843
+ GCC_except_table6849
+ GCC_except_table6878
+ GCC_except_table6880
+ GCC_except_table6882
+ GCC_except_table6887
+ GCC_except_table6892
+ GCC_except_table6895
+ GCC_except_table6898
+ GCC_except_table6902
+ GCC_except_table6970
+ GCC_except_table6977
+ GCC_except_table6981
+ GCC_except_table6983
+ GCC_except_table7020
+ GCC_except_table7030
+ GCC_except_table7031
+ GCC_except_table7033
+ GCC_except_table7034
+ GCC_except_table7035
+ GCC_except_table7036
+ GCC_except_table7039
+ GCC_except_table7126
+ GCC_except_table7135
+ GCC_except_table7144
+ GCC_except_table7166
+ GCC_except_table7251
+ GCC_except_table7310
+ GCC_except_table7312
+ GCC_except_table7315
+ GCC_except_table7317
+ GCC_except_table7320
+ GCC_except_table7358
+ GCC_except_table7383
+ GCC_except_table7385
+ GCC_except_table7387
+ GCC_except_table7389
+ GCC_except_table7391
+ GCC_except_table7479
+ GCC_except_table7495
+ GCC_except_table7498
+ GCC_except_table7597
+ GCC_except_table7624
+ GCC_except_table7629
+ GCC_except_table7655
+ GCC_except_table7656
+ GCC_except_table7675
+ GCC_except_table7765
+ GCC_except_table7767
+ GCC_except_table7786
+ GCC_except_table7791
+ GCC_except_table7799
+ GCC_except_table7939
+ GCC_except_table7942
+ GCC_except_table7959
+ GCC_except_table7963
+ GCC_except_table8012
+ GCC_except_table8016
+ GCC_except_table8018
+ GCC_except_table8019
+ GCC_except_table8029
+ GCC_except_table8072
+ GCC_except_table8122
+ GCC_except_table8130
+ GCC_except_table8142
+ GCC_except_table8148
+ GCC_except_table8156
+ GCC_except_table8157
+ GCC_except_table8161
+ GCC_except_table8165
+ GCC_except_table8176
+ GCC_except_table8178
+ GCC_except_table8282
+ GCC_except_table8463
+ GCC_except_table8466
+ GCC_except_table8469
+ GCC_except_table8477
+ GCC_except_table8483
+ GCC_except_table8493
+ GCC_except_table8495
+ GCC_except_table8497
+ GCC_except_table8547
+ GCC_except_table8583
+ GCC_except_table8621
+ GCC_except_table8687
+ GCC_except_table8785
+ GCC_except_table8794
+ GCC_except_table8808
+ GCC_except_table8965
+ GCC_except_table9104
+ GCC_except_table9106
+ GCC_except_table9129
+ GCC_except_table9171
+ GCC_except_table9201
+ GCC_except_table9211
+ GCC_except_table9283
+ GCC_except_table9287
+ GCC_except_table9288
+ GCC_except_table9289
+ GCC_except_table9409
+ GCC_except_table9466
+ GCC_except_table9519
+ GCC_except_table9522
+ GCC_except_table9524
+ GCC_except_table9638
+ GCC_except_table9642
+ GCC_except_table9648
+ GCC_except_table9652
+ GCC_except_table9688
+ GCC_except_table9694
+ GCC_except_table9697
+ GCC_except_table9712
+ GCC_except_table9758
+ GCC_except_table9850
+ GCC_except_table9851
+ GCC_except_table9854
+ GCC_except_table9911
+ GCC_except_table9916
+ _OBJC_CLASS_$_PGAmbientGroupWallpaperSuggester
+ _OBJC_CLASS_$_PGGroupWallpaperSuggester
+ _OBJC_CLASS_$_PGGroupWallpaperSuggesterFilteringContext
+ _OBJC_CLASS_$_PGGroupWallpaperSuggestion
+ _OBJC_CLASS_$_PGGroupWallpaperSuggestionCandidate
+ _OBJC_CLASS_$_PGTopGroupWallpaperSuggester
+ _OBJC_IVAR_$_PGGroupWallpaperSuggester._assetGater
+ _OBJC_IVAR_$_PGGroupWallpaperSuggester._primaryFilteringContext
+ _OBJC_IVAR_$_PGGroupWallpaperSuggester._secondaryFilteringContext
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._absoluteMinimumWallpaperScore
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._bypassCropScoreCheck
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._ignoreClockOverlap
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._maximumCropZoomRatio
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._maximumLowLightScore
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._minimumCropScore
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._minimumWallpaperScore
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._orientation
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personMaximumFaceRoll
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personMaximumFaceSize
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personMinimumFaceQuality
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personMinimumFaceSize
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personRequiresNoBlink
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._personRequiresSmile
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._petMaximumFaceSize
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._petMinimumFaceSize
+ _OBJC_IVAR_$_PGGroupWallpaperSuggesterFilteringContext._timeIntervalForCandidateDeduping
+ _OBJC_IVAR_$_PGGroupWallpaperSuggestion._suggestedPersonLocalIdentifiers
+ _OBJC_IVAR_$_PGGroupWallpaperSuggestionCandidate._asset
+ _OBJC_IVAR_$_PGGroupWallpaperSuggestionCandidate._cropResult
+ _OBJC_IVAR_$_PGGroupWallpaperSuggestionCandidate._faces
+ _OBJC_METACLASS_$_PGAmbientGroupWallpaperSuggester
+ _OBJC_METACLASS_$_PGGroupWallpaperSuggester
+ _OBJC_METACLASS_$_PGGroupWallpaperSuggesterFilteringContext
+ _OBJC_METACLASS_$_PGGroupWallpaperSuggestion
+ _OBJC_METACLASS_$_PGGroupWallpaperSuggestionCandidate
+ _OBJC_METACLASS_$_PGTopGroupWallpaperSuggester
+ __OBJC_$_CLASS_METHODS_PGAmbientGroupWallpaperSuggester
+ __OBJC_$_CLASS_METHODS_PGGroupWallpaperSuggester
+ __OBJC_$_CLASS_METHODS_PGTopGroupWallpaperSuggester
+ __OBJC_$_INSTANCE_METHODS_PGAmbientGroupWallpaperSuggester
+ __OBJC_$_INSTANCE_METHODS_PGGroupWallpaperSuggester
+ __OBJC_$_INSTANCE_METHODS_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_$_INSTANCE_METHODS_PGGroupWallpaperSuggestion
+ __OBJC_$_INSTANCE_METHODS_PGGroupWallpaperSuggestionCandidate
+ __OBJC_$_INSTANCE_METHODS_PGTopGroupWallpaperSuggester
+ __OBJC_$_INSTANCE_VARIABLES_PGGroupWallpaperSuggester
+ __OBJC_$_INSTANCE_VARIABLES_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_$_INSTANCE_VARIABLES_PGGroupWallpaperSuggestion
+ __OBJC_$_INSTANCE_VARIABLES_PGGroupWallpaperSuggestionCandidate
+ __OBJC_$_PROP_LIST_PGAmbientGroupWallpaperSuggester
+ __OBJC_$_PROP_LIST_PGGroupWallpaperSuggester
+ __OBJC_$_PROP_LIST_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_$_PROP_LIST_PGGroupWallpaperSuggesterProtocol
+ __OBJC_$_PROP_LIST_PGGroupWallpaperSuggestionCandidate
+ __OBJC_$_PROP_LIST_PGTopGroupWallpaperSuggester
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PGGroupWallpaperSuggesterProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PGGroupWallpaperSuggesterProtocol
+ __OBJC_$_PROTOCOL_REFS_PGGroupWallpaperSuggesterProtocol
+ __OBJC_CLASS_PROTOCOLS_$_PGAmbientGroupWallpaperSuggester
+ __OBJC_CLASS_PROTOCOLS_$_PGGroupWallpaperSuggester
+ __OBJC_CLASS_PROTOCOLS_$_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_CLASS_PROTOCOLS_$_PGTopGroupWallpaperSuggester
+ __OBJC_CLASS_RO_$_PGAmbientGroupWallpaperSuggester
+ __OBJC_CLASS_RO_$_PGGroupWallpaperSuggester
+ __OBJC_CLASS_RO_$_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_CLASS_RO_$_PGGroupWallpaperSuggestion
+ __OBJC_CLASS_RO_$_PGGroupWallpaperSuggestionCandidate
+ __OBJC_CLASS_RO_$_PGTopGroupWallpaperSuggester
+ __OBJC_LABEL_PROTOCOL_$_PGGroupWallpaperSuggesterProtocol
+ __OBJC_METACLASS_RO_$_PGAmbientGroupWallpaperSuggester
+ __OBJC_METACLASS_RO_$_PGGroupWallpaperSuggester
+ __OBJC_METACLASS_RO_$_PGGroupWallpaperSuggesterFilteringContext
+ __OBJC_METACLASS_RO_$_PGGroupWallpaperSuggestion
+ __OBJC_METACLASS_RO_$_PGGroupWallpaperSuggestionCandidate
+ __OBJC_METACLASS_RO_$_PGTopGroupWallpaperSuggester
+ __OBJC_PROTOCOL_$_PGGroupWallpaperSuggesterProtocol
+ ___61-[PGGroupWallpaperSuggester suggestionsWithOptions:progress:]_block_invoke
+ ___87-[PGGroupWallpaperSuggester rankedAndDedupedCandidatesFromCandidates:progressReporter:]_block_invoke
+ ___87-[PGGroupWallpaperSuggester rankedAndDedupedCandidatesFromCandidates:progressReporter:]_block_invoke_2
+ ___90-[PGGroupWallpaperSuggester candidatesForSocialGroup:withNumberOfPeople:progressReporter:]_block_invoke
+ ___block_descriptor_120_e8_32s40s48s56s64s72s80r88r96r104r_e33_v32?0"PHAsset"8"NSArray"16^B24lr80l8r88l8s32l8s40l8s48l8s56l8s64l8r96l8r104l8s72l8
+ ___block_descriptor_124_e8_32s40s48s56s64s72r80r_e34_v32?0"NSString"8"NSArray"16^B24ls32l8r72l8s40l8r80l8s48l8s56l8s64l8
+ ___block_descriptor_32_e85_d24?0"PGGroupWallpaperSuggestionCandidate"8"PGGroupWallpaperSuggestionCandidate"16l
- -[PGMonthEnrichmentRule _legacyVisibilityStateForItemPromotedToMonths:]
- GCC_except_table10112
- GCC_except_table10119
- GCC_except_table10139
- GCC_except_table10160
- GCC_except_table10173
- GCC_except_table10185
- GCC_except_table10193
- GCC_except_table10231
- GCC_except_table10243
- GCC_except_table10246
- GCC_except_table10266
- GCC_except_table10277
- GCC_except_table10293
- GCC_except_table10299
- GCC_except_table10305
- GCC_except_table10308
- GCC_except_table10329
- GCC_except_table10407
- GCC_except_table10469
- GCC_except_table10470
- GCC_except_table10471
- GCC_except_table10472
- GCC_except_table10473
- GCC_except_table10474
- GCC_except_table10506
- GCC_except_table10563
- GCC_except_table10565
- GCC_except_table10588
- GCC_except_table10603
- GCC_except_table10626
- GCC_except_table10653
- GCC_except_table10656
- GCC_except_table10702
- GCC_except_table10727
- GCC_except_table10761
- GCC_except_table10773
- GCC_except_table10783
- GCC_except_table10785
- GCC_except_table10789
- GCC_except_table10871
- GCC_except_table10876
- GCC_except_table10934
- GCC_except_table10939
- GCC_except_table10949
- GCC_except_table10955
- GCC_except_table10957
- GCC_except_table10964
- GCC_except_table11002
- GCC_except_table11061
- GCC_except_table11191
- GCC_except_table11195
- GCC_except_table11214
- GCC_except_table11494
- GCC_except_table11542
- GCC_except_table11570
- GCC_except_table11627
- GCC_except_table11634
- GCC_except_table11665
- GCC_except_table11667
- GCC_except_table11669
- GCC_except_table11675
- GCC_except_table11690
- GCC_except_table11697
- GCC_except_table11896
- GCC_except_table11905
- GCC_except_table11906
- GCC_except_table11929
- GCC_except_table11938
- GCC_except_table11951
- GCC_except_table11962
- GCC_except_table12060
- GCC_except_table12230
- GCC_except_table12349
- GCC_except_table12350
- GCC_except_table12363
- GCC_except_table12366
- GCC_except_table12377
- GCC_except_table12379
- GCC_except_table12382
- GCC_except_table12385
- GCC_except_table12389
- GCC_except_table12392
- GCC_except_table12395
- GCC_except_table12451
- GCC_except_table12462
- GCC_except_table12576
- GCC_except_table12589
- GCC_except_table12617
- GCC_except_table12671
- GCC_except_table12673
- GCC_except_table12689
- GCC_except_table12695
- GCC_except_table12734
- GCC_except_table12738
- GCC_except_table12770
- GCC_except_table12775
- GCC_except_table12831
- GCC_except_table12925
- GCC_except_table13008
- GCC_except_table13013
- GCC_except_table13051
- GCC_except_table13058
- GCC_except_table13084
- GCC_except_table13086
- GCC_except_table13088
- GCC_except_table13142
- GCC_except_table13155
- GCC_except_table13186
- GCC_except_table13196
- GCC_except_table13211
- GCC_except_table13241
- GCC_except_table13255
- GCC_except_table13258
- GCC_except_table13274
- GCC_except_table13282
- GCC_except_table13284
- GCC_except_table13286
- GCC_except_table13343
- GCC_except_table13345
- GCC_except_table13385
- GCC_except_table13414
- GCC_except_table13418
- GCC_except_table13423
- GCC_except_table13431
- GCC_except_table13642
- GCC_except_table13647
- GCC_except_table13652
- GCC_except_table13663
- GCC_except_table13672
- GCC_except_table13673
- GCC_except_table13675
- GCC_except_table13677
- GCC_except_table13718
- GCC_except_table13720
- GCC_except_table13724
- GCC_except_table13734
- GCC_except_table13741
- GCC_except_table13775
- GCC_except_table13831
- GCC_except_table13841
- GCC_except_table13844
- GCC_except_table13867
- GCC_except_table13879
- GCC_except_table13882
- GCC_except_table13891
- GCC_except_table13896
- GCC_except_table13897
- GCC_except_table13910
- GCC_except_table13915
- GCC_except_table13925
- GCC_except_table14168
- GCC_except_table14170
- GCC_except_table14172
- GCC_except_table14176
- GCC_except_table14235
- GCC_except_table2061
- GCC_except_table2241
- GCC_except_table2300
- GCC_except_table2320
- GCC_except_table2325
- GCC_except_table2329
- GCC_except_table2334
- GCC_except_table2336
- GCC_except_table2357
- GCC_except_table2376
- GCC_except_table2583
- GCC_except_table2657
- GCC_except_table2688
- GCC_except_table2714
- GCC_except_table2718
- GCC_except_table2725
- GCC_except_table2752
- GCC_except_table2760
- GCC_except_table2832
- GCC_except_table2850
- GCC_except_table2864
- GCC_except_table2978
- GCC_except_table3179
- GCC_except_table3181
- GCC_except_table3184
- GCC_except_table3282
- GCC_except_table3339
- GCC_except_table3374
- GCC_except_table3393
- GCC_except_table3453
- GCC_except_table3460
- GCC_except_table3464
- GCC_except_table3468
- GCC_except_table3471
- GCC_except_table3475
- GCC_except_table3545
- GCC_except_table3553
- GCC_except_table3557
- GCC_except_table3565
- GCC_except_table3572
- GCC_except_table3642
- GCC_except_table3652
- GCC_except_table3653
- GCC_except_table3659
- GCC_except_table3705
- GCC_except_table3718
- GCC_except_table3747
- GCC_except_table3760
- GCC_except_table3762
- GCC_except_table3779
- GCC_except_table3843
- GCC_except_table3848
- GCC_except_table3903
- GCC_except_table3904
- GCC_except_table3905
- GCC_except_table3937
- GCC_except_table3967
- GCC_except_table3975
- GCC_except_table4006
- GCC_except_table4011
- GCC_except_table4013
- GCC_except_table4015
- GCC_except_table4018
- GCC_except_table4029
- GCC_except_table4099
- GCC_except_table4104
- GCC_except_table4115
- GCC_except_table4126
- GCC_except_table4136
- GCC_except_table4138
- GCC_except_table4196
- GCC_except_table4235
- GCC_except_table4244
- GCC_except_table4299
- GCC_except_table4333
- GCC_except_table4342
- GCC_except_table4364
- GCC_except_table4376
- GCC_except_table4380
- GCC_except_table4382
- GCC_except_table4388
- GCC_except_table4389
- GCC_except_table4393
- GCC_except_table4407
- GCC_except_table4411
- GCC_except_table4415
- GCC_except_table4416
- GCC_except_table4454
- GCC_except_table4473
- GCC_except_table4506
- GCC_except_table4515
- GCC_except_table4721
- GCC_except_table4725
- GCC_except_table4736
- GCC_except_table4739
- GCC_except_table4802
- GCC_except_table4804
- GCC_except_table4808
- GCC_except_table4811
- GCC_except_table4819
- GCC_except_table4898
- GCC_except_table4924
- GCC_except_table4926
- GCC_except_table4928
- GCC_except_table4930
- GCC_except_table4932
- GCC_except_table4989
- GCC_except_table5188
- GCC_except_table5203
- GCC_except_table5204
- GCC_except_table5314
- GCC_except_table5319
- GCC_except_table5323
- GCC_except_table5327
- GCC_except_table5336
- GCC_except_table5338
- GCC_except_table5369
- GCC_except_table5370
- GCC_except_table5371
- GCC_except_table5372
- GCC_except_table5373
- GCC_except_table5374
- GCC_except_table5384
- GCC_except_table5386
- GCC_except_table5392
- GCC_except_table5401
- GCC_except_table5446
- GCC_except_table5450
- GCC_except_table5647
- GCC_except_table5670
- GCC_except_table5673
- GCC_except_table5734
- GCC_except_table5742
- GCC_except_table5748
- GCC_except_table5810
- GCC_except_table5823
- GCC_except_table5833
- GCC_except_table5838
- GCC_except_table5943
- GCC_except_table5953
- GCC_except_table5956
- GCC_except_table5963
- GCC_except_table5987
- GCC_except_table6041
- GCC_except_table6045
- GCC_except_table6047
- GCC_except_table6049
- GCC_except_table6054
- GCC_except_table6056
- GCC_except_table6076
- GCC_except_table6100
- GCC_except_table6112
- GCC_except_table6113
- GCC_except_table6151
- GCC_except_table6176
- GCC_except_table6216
- GCC_except_table6218
- GCC_except_table6226
- GCC_except_table6229
- GCC_except_table6250
- GCC_except_table6256
- GCC_except_table6264
- GCC_except_table6283
- GCC_except_table6343
- GCC_except_table6347
- GCC_except_table6349
- GCC_except_table6355
- GCC_except_table6356
- GCC_except_table6360
- GCC_except_table6362
- GCC_except_table6382
- GCC_except_table6420
- GCC_except_table6451
- GCC_except_table6453
- GCC_except_table6500
- GCC_except_table6504
- GCC_except_table6508
- GCC_except_table6511
- GCC_except_table6514
- GCC_except_table6517
- GCC_except_table6519
- GCC_except_table6524
- GCC_except_table6534
- GCC_except_table6567
- GCC_except_table6571
- GCC_except_table6578
- GCC_except_table6667
- GCC_except_table6771
- GCC_except_table6776
- GCC_except_table6778
- GCC_except_table6786
- GCC_except_table6792
- GCC_except_table6802
- GCC_except_table6808
- GCC_except_table6837
- GCC_except_table6839
- GCC_except_table6841
- GCC_except_table6846
- GCC_except_table6851
- GCC_except_table6854
- GCC_except_table6857
- GCC_except_table6861
- GCC_except_table6929
- GCC_except_table6936
- GCC_except_table6940
- GCC_except_table6942
- GCC_except_table6979
- GCC_except_table6989
- GCC_except_table6990
- GCC_except_table6992
- GCC_except_table6993
- GCC_except_table6994
- GCC_except_table6995
- GCC_except_table6998
- GCC_except_table7085
- GCC_except_table7094
- GCC_except_table7103
- GCC_except_table7125
- GCC_except_table7207
- GCC_except_table7266
- GCC_except_table7268
- GCC_except_table7271
- GCC_except_table7273
- GCC_except_table7276
- GCC_except_table7314
- GCC_except_table7339
- GCC_except_table7341
- GCC_except_table7343
- GCC_except_table7345
- GCC_except_table7347
- GCC_except_table7435
- GCC_except_table7451
- GCC_except_table7454
- GCC_except_table7553
- GCC_except_table7580
- GCC_except_table7585
- GCC_except_table7611
- GCC_except_table7612
- GCC_except_table7631
- GCC_except_table7721
- GCC_except_table7723
- GCC_except_table7742
- GCC_except_table7747
- GCC_except_table7755
- GCC_except_table7895
- GCC_except_table7898
- GCC_except_table7915
- GCC_except_table7919
- GCC_except_table7968
- GCC_except_table7972
- GCC_except_table7974
- GCC_except_table7975
- GCC_except_table7985
- GCC_except_table8028
- GCC_except_table8078
- GCC_except_table8086
- GCC_except_table8098
- GCC_except_table8104
- GCC_except_table8112
- GCC_except_table8113
- GCC_except_table8117
- GCC_except_table8121
- GCC_except_table8132
- GCC_except_table8134
- GCC_except_table8238
- GCC_except_table8381
- GCC_except_table8419
- GCC_except_table8422
- GCC_except_table8433
- GCC_except_table8439
- GCC_except_table8449
- GCC_except_table8451
- GCC_except_table8453
- GCC_except_table8503
- GCC_except_table8533
- GCC_except_table8539
- GCC_except_table8643
- GCC_except_table8741
- GCC_except_table8750
- GCC_except_table8764
- GCC_except_table8921
- GCC_except_table9041
- GCC_except_table9060
- GCC_except_table9062
- GCC_except_table9127
- GCC_except_table9157
- GCC_except_table9167
- GCC_except_table9239
- GCC_except_table9243
- GCC_except_table9244
- GCC_except_table9245
- GCC_except_table9366
- GCC_except_table9423
- GCC_except_table9476
- GCC_except_table9479
- GCC_except_table9481
- GCC_except_table9595
- GCC_except_table9599
- GCC_except_table9605
- GCC_except_table9609
- GCC_except_table9645
- GCC_except_table9651
- GCC_except_table9654
- GCC_except_table9669
- GCC_except_table9715
- GCC_except_table9807
- GCC_except_table9808
- GCC_except_table9811
- GCC_except_table9868
- GCC_except_table9873
- __os_feature_enabled_impl
```
