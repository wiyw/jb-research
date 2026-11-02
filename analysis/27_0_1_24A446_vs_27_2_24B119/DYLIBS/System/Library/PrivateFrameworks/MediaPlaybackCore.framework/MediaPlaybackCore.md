## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore`

```diff

-26110.26.31.301.0
-  __TEXT.__text: 0x4a197c
-  __TEXT.__objc_methlist: 0x17e10
+26210.26.40.301.0
+  __TEXT.__text: 0x4aed6c
+  __TEXT.__objc_methlist: 0x17f60
   __TEXT.__dlopen_cstrs: 0x114
-  __TEXT.__const: 0x10870
-  __TEXT.__oslogstring: 0x4c598
-  __TEXT.__cstring: 0x25ad1
-  __TEXT.__swift5_typeref: 0x547a
-  __TEXT.__swift5_capture: 0xaee4
-  __TEXT.__constg_swiftt: 0x7b40
-  __TEXT.__swift5_reflstr: 0x5a02
-  __TEXT.__swift5_fieldmd: 0x569c
+  __TEXT.__const: 0x10a80
+  __TEXT.__oslogstring: 0x4d157
+  __TEXT.__cstring: 0x26063
+  __TEXT.__swift5_typeref: 0x54d0
+  __TEXT.__swift5_capture: 0xb1bc
+  __TEXT.__constg_swiftt: 0x7bdc
+  __TEXT.__swift5_reflstr: 0x5b02
+  __TEXT.__swift5_fieldmd: 0x5718
   __TEXT.__swift5_builtin: 0x6f4
-  __TEXT.__swift5_mpenum: 0xf0
+  __TEXT.__swift5_mpenum: 0x130
   __TEXT.__swift5_assocty: 0xbc0
-  __TEXT.__swift5_proto: 0x92c
-  __TEXT.__swift5_types: 0x564
-  __TEXT.__swift_as_entry: 0x4a4
-  __TEXT.__swift_as_ret: 0x5bc
-  __TEXT.__swift_as_cont: 0xe14
+  __TEXT.__swift5_proto: 0x934
+  __TEXT.__swift5_types: 0x568
+  __TEXT.__swift_as_entry: 0x4b8
+  __TEXT.__swift_as_ret: 0x5e0
+  __TEXT.__swift_as_cont: 0xe54
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5988
+  __TEXT.__gcc_except_tab: 0x5a6c
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0xdd78
-  __TEXT.__eh_frame: 0x10284
+  __TEXT.__unwind_info: 0xdae8
+  __TEXT.__eh_frame: 0x105b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9380
+  __DATA_CONST.__const: 0x9498
   __DATA_CONST.__objc_classlist: 0xd30
   __DATA_CONST.__objc_catlist: 0x298
   __DATA_CONST.__objc_protolist: 0x7f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xcb40
+  __DATA_CONST.__objc_selrefs: 0xcc18
   __DATA_CONST.__objc_protorefs: 0x3a0
-  __DATA_CONST.__objc_superrefs: 0x6d0
-  __DATA_CONST.__objc_arraydata: 0x290
-  __DATA_CONST.__got: 0x3458
-  __AUTH_CONST.__const: 0x23858
-  __AUTH_CONST.__cfstring: 0x1ea00
-  __AUTH_CONST.__objc_const: 0x34770
-  __AUTH_CONST.__objc_intobj: 0x888
-  __AUTH_CONST.__objc_arrayobj: 0x288
+  __DATA_CONST.__objc_superrefs: 0x6d8
+  __DATA_CONST.__objc_arraydata: 0x288
+  __DATA_CONST.__got: 0x34a0
+  __AUTH_CONST.__const: 0x24018
+  __AUTH_CONST.__cfstring: 0x1ede0
+  __AUTH_CONST.__objc_const: 0x349d0
+  __AUTH_CONST.__objc_intobj: 0x8a0
+  __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x3448
-  __AUTH_CONST.__auth_ptr: 0xdf0
+  __AUTH_CONST.__objc_doubleobj: 0x60
+  __AUTH_CONST.__auth_got: 0x34a0
+  __AUTH_CONST.__auth_ptr: 0xdf8
   __AUTH.__objc_data: 0x5a40
-  __AUTH.__data: 0x40b0
-  __DATA.__objc_ivar: 0x1ac4
-  __DATA.__data: 0x72b0
-  __DATA.__bss: 0xf438
-  __DATA.__common: 0x240
-  __DATA_DIRTY.__objc_data: 0x3590
-  __DATA_DIRTY.__data: 0x4548
+  __AUTH.__data: 0x40f0
+  __DATA.__objc_ivar: 0x1adc
+  __DATA.__data: 0x7310
+  __DATA.__bss: 0xf538
+  __DATA.__common: 0x238
+  __DATA_DIRTY.__objc_data: 0x3598
+  __DATA_DIRTY.__data: 0x45d8
   __DATA_DIRTY.__bss: 0x1328
   __DATA_DIRTY.__common: 0xc8
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24465
-  Symbols:   18657
+  Functions: 24731
+  Symbols:   18718
   CStrings:  0
 
Symbols:
+ +[MPCAssistantRemoteControlDestination companionLocalFallbackPolicy]
+ +[_MPCVideoViewControllerMediaFoundationImplementation keyPathsForValuesAffectingCustomControlItems]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSMetadataItemInMetadata:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]
+ -[MPCAudioAssetTypeSelector descriptionForExpectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:applyJitterTreatment:expectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:applyJitterTreatment:explanation:]
+ -[MPCFuture _removeInvalidHandler:]
+ -[MPCFuture invalidHandlers]
+ -[MPCFutureInvalidationToken dealloc]
+ -[MPCFutureInvalidationToken handler]
+ -[MPCFutureInvalidationToken setHandler:]
+ -[MPCModelGenericAVItem _albumForPreReleaseTreatment]
+ -[MPCModelGenericAVItem _hasPendingDeferredLeaseAcquisition]
+ -[MPCModelGenericAVItem _setHasPendingDeferredLeaseAcquisition:]
+ -[MPCModelGenericAVItem expectedAlbumAvailableDateTime]
+ -[MPCModelGenericAVItem leaseAcquisitionJitterTime]
+ -[MPCModelGenericAVItem shouldApplyJitterTreatment]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDurationWithCompletionHandler:]
+ -[MPCModelStorePlaybackItemsRequest setVersionHashesByStoreID:]
+ -[MPCModelStorePlaybackItemsRequest versionHashesByStoreID]
+ -[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]
+ -[MPCPlaybackErrorController playbackDidSucceedForItem:]
+ -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]
+ -[_MPCControllerPropertyProxy .cxx_destruct]
+ -[_MPCControllerPropertyProxy customControlItems]
+ -[_MPCControllerPropertyProxy setCustomControlItems:]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]
+ -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:userInitiated:timeStamp:]
+ -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:primaryTime:timeStamp:]
+ -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:timeStamp:]
+ -[_MPCVideoViewControllerMediaFoundationImplementation customControlItems]
+ -[_MPCVideoViewControllerMediaFoundationImplementation setCustomControlItems:]
+ GCC_except_table1002
+ GCC_except_table1005
+ GCC_except_table1192
+ GCC_except_table1196
+ GCC_except_table1198
+ GCC_except_table1366
+ GCC_except_table1368
+ GCC_except_table1415
+ GCC_except_table1426
+ GCC_except_table1433
+ GCC_except_table1440
+ GCC_except_table1477
+ GCC_except_table1489
+ GCC_except_table1498
+ GCC_except_table1541
+ GCC_except_table1714
+ GCC_except_table1716
+ GCC_except_table1734
+ GCC_except_table1804
+ GCC_except_table1890
+ GCC_except_table1891
+ GCC_except_table2002
+ GCC_except_table2022
+ GCC_except_table2024
+ GCC_except_table2052
+ GCC_except_table2068
+ GCC_except_table2071
+ GCC_except_table2082
+ GCC_except_table2092
+ GCC_except_table2207
+ GCC_except_table2258
+ GCC_except_table2262
+ GCC_except_table2265
+ GCC_except_table2291
+ GCC_except_table2315
+ GCC_except_table2347
+ GCC_except_table2427
+ GCC_except_table2614
+ GCC_except_table2642
+ GCC_except_table2669
+ GCC_except_table2814
+ GCC_except_table2842
+ GCC_except_table2843
+ GCC_except_table2870
+ GCC_except_table2875
+ GCC_except_table2879
+ GCC_except_table2883
+ GCC_except_table2885
+ GCC_except_table2888
+ GCC_except_table2923
+ GCC_except_table2928
+ GCC_except_table2934
+ GCC_except_table2940
+ GCC_except_table2945
+ GCC_except_table2948
+ GCC_except_table2951
+ GCC_except_table2971
+ GCC_except_table2979
+ GCC_except_table3022
+ GCC_except_table3108
+ GCC_except_table3112
+ GCC_except_table3123
+ GCC_except_table3124
+ GCC_except_table3148
+ GCC_except_table3156
+ GCC_except_table3197
+ GCC_except_table3198
+ GCC_except_table3214
+ GCC_except_table3271
+ GCC_except_table3289
+ GCC_except_table3298
+ GCC_except_table3340
+ GCC_except_table3342
+ GCC_except_table3360
+ GCC_except_table3364
+ GCC_except_table3408
+ GCC_except_table3453
+ GCC_except_table3458
+ GCC_except_table355
+ GCC_except_table357
+ GCC_except_table3611
+ GCC_except_table3618
+ GCC_except_table3643
+ GCC_except_table3647
+ GCC_except_table3657
+ GCC_except_table3714
+ GCC_except_table3719
+ GCC_except_table3723
+ GCC_except_table3793
+ GCC_except_table3890
+ GCC_except_table3894
+ GCC_except_table3905
+ GCC_except_table3921
+ GCC_except_table3927
+ GCC_except_table3936
+ GCC_except_table403
+ GCC_except_table4064
+ GCC_except_table411
+ GCC_except_table4110
+ GCC_except_table4111
+ GCC_except_table4130
+ GCC_except_table4139
+ GCC_except_table4162
+ GCC_except_table4164
+ GCC_except_table4178
+ GCC_except_table419
+ GCC_except_table4201
+ GCC_except_table4212
+ GCC_except_table428
+ GCC_except_table4301
+ GCC_except_table4320
+ GCC_except_table4333
+ GCC_except_table4344
+ GCC_except_table4375
+ GCC_except_table4546
+ GCC_except_table4547
+ GCC_except_table4725
+ GCC_except_table4760
+ GCC_except_table4762
+ GCC_except_table4770
+ GCC_except_table4778
+ GCC_except_table4793
+ GCC_except_table4801
+ GCC_except_table4809
+ GCC_except_table4819
+ GCC_except_table4834
+ GCC_except_table4878
+ GCC_except_table4892
+ GCC_except_table4908
+ GCC_except_table4911
+ GCC_except_table4917
+ GCC_except_table4969
+ GCC_except_table5007
+ GCC_except_table5095
+ GCC_except_table512
+ GCC_except_table5196
+ GCC_except_table528
+ GCC_except_table529
+ GCC_except_table5439
+ GCC_except_table5440
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table5516
+ GCC_except_table5608
+ GCC_except_table5760
+ GCC_except_table5785
+ GCC_except_table5902
+ GCC_except_table5983
+ GCC_except_table5991
+ GCC_except_table5992
+ GCC_except_table6056
+ GCC_except_table6081
+ GCC_except_table6116
+ GCC_except_table6119
+ GCC_except_table6122
+ GCC_except_table6208
+ GCC_except_table6425
+ GCC_except_table6442
+ GCC_except_table6490
+ GCC_except_table6503
+ GCC_except_table7019
+ GCC_except_table7353
+ GCC_except_table7368
+ GCC_except_table7462
+ GCC_except_table7471
+ GCC_except_table7560
+ GCC_except_table7567
+ GCC_except_table7585
+ GCC_except_table7636
+ GCC_except_table7637
+ GCC_except_table7640
+ GCC_except_table7645
+ GCC_except_table7661
+ GCC_except_table797
+ GCC_except_table853
+ GCC_except_table929
+ GCC_except_table963
+ GCC_except_table970
+ GCC_except_table972
+ GCC_except_table985
+ GCC_except_table989
+ GCC_except_table995
+ GCC_except_table999
+ _MPCHLSAudioAssetMetadataDictionaryKey
+ _MPCPlaybackEngineEventPayloadKeyInterstitialPrimaryPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryEndPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryStartPosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePrimaryPosition
+ _MPHomeMonitorCurrentHomeDidChangeNotification
+ _MPHomeMonitorHomeUsersDidChangeNotification
+ _MPModelPropertyAlbumExpectedReleaseDateComponents
+ _NSURLFileSizeKey
+ _NSURLIsRegularFileKey
+ _OBJC_CLASS_$_NSPointerArray
+ _OBJC_IVAR_$_MPCFuture._invalidHandlers
+ _OBJC_IVAR_$_MPCFutureInvalidationToken._handler
+ _OBJC_IVAR_$_MPCModelStorePlaybackItemsRequest._versionHashesByStoreID
+ _OBJC_IVAR_$_MPCPlaybackAccountManager._accountsUpdateQueue
+ _OBJC_IVAR_$__MPCControllerPropertyProxy._customControlItems
+ _OBJC_IVAR_$__MPCMediaRemotePublisher._hostingSharedSessionIDInitialized
+ _OBJC_IVAR_$__MPCModelStorePlaybackItemsRequestAccumulator_Legacy._hasHandledStoreResponse
+ _OUTLINED_FUNCTION_500
+ _OUTLINED_FUNCTION_501
+ _OUTLINED_FUNCTION_621
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke_2
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke_3
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern _locked_progressiveSectionWithoutVersionHash:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke_2
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke_3
+ ___115-[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]_block_invoke
+ ___119-[MPCAssistantRemoteControlDestination resolveWithRouteIdentifiers:allowedPlaybackTargets:audioRoutingInfo:completion:]_block_invoke_2
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke_4
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_2
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_3
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_4
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_5
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_6
+ ___35-[MPCFuture _removeInvalidHandler:]_block_invoke
+ ___36+[MPCPlaybackEngine preheatPlayback]_block_invoke_2
+ ___57-[MPCPlaybackAccountManager performAfterLoadingAccounts:]_block_invoke
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_4
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_5
+ ___86-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]_block_invoke
+ ___88-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]_block_invoke
+ ___89-[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]_block_invoke
+ ___89-[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]_block_invoke
+ ___98-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e36_v24?0"AVMetadataItem"8"NSError"16ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0d8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0q8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e9_v16?0^v8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e18_16?0"NSString"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e34_v24?0"NSDictionary"8"NSError"16lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_61_e8_32s40s48s_e49_v16?0"MPIdentifierSet<MPMutableIdentifierSet>"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
+ ___swift_closure_destructor.70Tm
+ _arc4random
+ _associated conformance 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLVSHAASQ
+ _symbolic Sb7success_______pSg4itemSdSg9startTimeAE012primaryStartD0Sd03endD0AE0e3EndD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
+ _symbolic _____ 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _symbolic _____Iegr_ 17MediaPlaybackCore12PlayingStateC
+ _symbolic _____ySDy_____So11SHSignatureCGG 2os21OSAllocatedUnfairLockV 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 10Foundation3URLV
+ _type_layout_string SNySdG
- -[AVURLAsset(MPCHLSSessionData) mpc_HLSAVMetadataItemInMetadata:]
- -[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]
- -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:]
- -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:explanation:]
- -[MPCFuture invalidBlocks]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTime]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDuration]
- -[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]
- -[MPCPlayerItemConfigurator _HLSMetadataForAsset:error:]
- -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]
- -[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]
- -[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]
- -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:toTime:userInitiated:timeStamp:]
- -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:timeStamp:]
- -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:toTime:timeStamp:]
- GCC_except_table1000
- GCC_except_table1187
- GCC_except_table1191
- GCC_except_table1193
- GCC_except_table1361
- GCC_except_table1363
- GCC_except_table1410
- GCC_except_table1421
- GCC_except_table1428
- GCC_except_table1435
- GCC_except_table1472
- GCC_except_table1484
- GCC_except_table1493
- GCC_except_table1536
- GCC_except_table1709
- GCC_except_table1711
- GCC_except_table1724
- GCC_except_table1799
- GCC_except_table1885
- GCC_except_table1886
- GCC_except_table1997
- GCC_except_table2017
- GCC_except_table2019
- GCC_except_table2047
- GCC_except_table2056
- GCC_except_table2063
- GCC_except_table2077
- GCC_except_table2087
- GCC_except_table2202
- GCC_except_table2253
- GCC_except_table2257
- GCC_except_table2260
- GCC_except_table2286
- GCC_except_table2310
- GCC_except_table2342
- GCC_except_table2422
- GCC_except_table2609
- GCC_except_table2637
- GCC_except_table2664
- GCC_except_table2807
- GCC_except_table2828
- GCC_except_table2836
- GCC_except_table2861
- GCC_except_table2863
- GCC_except_table2872
- GCC_except_table2874
- GCC_except_table2876
- GCC_except_table2878
- GCC_except_table2907
- GCC_except_table2919
- GCC_except_table2921
- GCC_except_table2925
- GCC_except_table2931
- GCC_except_table2936
- GCC_except_table2942
- GCC_except_table2962
- GCC_except_table2970
- GCC_except_table3013
- GCC_except_table3099
- GCC_except_table3103
- GCC_except_table3114
- GCC_except_table3115
- GCC_except_table3139
- GCC_except_table3147
- GCC_except_table3188
- GCC_except_table3189
- GCC_except_table3205
- GCC_except_table3262
- GCC_except_table3280
- GCC_except_table3287
- GCC_except_table3329
- GCC_except_table3331
- GCC_except_table3338
- GCC_except_table3353
- GCC_except_table3391
- GCC_except_table3436
- GCC_except_table3441
- GCC_except_table351
- GCC_except_table353
- GCC_except_table3569
- GCC_except_table3597
- GCC_except_table3622
- GCC_except_table3626
- GCC_except_table3636
- GCC_except_table3693
- GCC_except_table3698
- GCC_except_table3702
- GCC_except_table3772
- GCC_except_table3869
- GCC_except_table3873
- GCC_except_table3884
- GCC_except_table3900
- GCC_except_table3906
- GCC_except_table3915
- GCC_except_table399
- GCC_except_table4043
- GCC_except_table407
- GCC_except_table4087
- GCC_except_table4088
- GCC_except_table4089
- GCC_except_table4118
- GCC_except_table4136
- GCC_except_table4141
- GCC_except_table4143
- GCC_except_table415
- GCC_except_table4180
- GCC_except_table4191
- GCC_except_table424
- GCC_except_table4280
- GCC_except_table4299
- GCC_except_table4312
- GCC_except_table4323
- GCC_except_table4354
- GCC_except_table4525
- GCC_except_table4526
- GCC_except_table4704
- GCC_except_table4739
- GCC_except_table4741
- GCC_except_table4749
- GCC_except_table4757
- GCC_except_table4772
- GCC_except_table4780
- GCC_except_table4788
- GCC_except_table4798
- GCC_except_table4813
- GCC_except_table4857
- GCC_except_table4872
- GCC_except_table4888
- GCC_except_table4891
- GCC_except_table4897
- GCC_except_table4949
- GCC_except_table4987
- GCC_except_table507
- GCC_except_table5074
- GCC_except_table5175
- GCC_except_table523
- GCC_except_table524
- GCC_except_table540
- GCC_except_table541
- GCC_except_table5413
- GCC_except_table5414
- GCC_except_table5489
- GCC_except_table5580
- GCC_except_table5732
- GCC_except_table5757
- GCC_except_table5874
- GCC_except_table5955
- GCC_except_table5963
- GCC_except_table5964
- GCC_except_table6028
- GCC_except_table6053
- GCC_except_table6088
- GCC_except_table6091
- GCC_except_table6094
- GCC_except_table6180
- GCC_except_table6397
- GCC_except_table6414
- GCC_except_table6462
- GCC_except_table6475
- GCC_except_table6991
- GCC_except_table7325
- GCC_except_table7335
- GCC_except_table7428
- GCC_except_table7437
- GCC_except_table7521
- GCC_except_table7528
- GCC_except_table7546
- GCC_except_table7597
- GCC_except_table7598
- GCC_except_table7601
- GCC_except_table7606
- GCC_except_table7622
- GCC_except_table792
- GCC_except_table848
- GCC_except_table924
- GCC_except_table955
- GCC_except_table958
- GCC_except_table967
- GCC_except_table980
- GCC_except_table984
- GCC_except_table990
- GCC_except_table994
- GCC_except_table997
- _OBJC_IVAR_$_MPCFuture._invalidBlocks
- _OUTLINED_FUNCTION_498
- _OUTLINED_FUNCTION_499
- ___114-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy _locked_resolveContentDescriptorsUsingServerObjectDatabase]_block_invoke_3
- ___114-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy _locked_resolveContentDescriptorsUsingServerObjectDatabase]_block_invoke_4
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_2
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_3
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_4
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_5
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_6
- ___68-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]_block_invoke
- ___80-[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke_2
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke_3
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke_2
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke_3
- ___block_descriptor_41_e8_32s_e18_16?0"NSString"8ls32l8
- ___block_descriptor_53_e8_32s40s_e49_v16?0"MPIdentifierSet<MPMutableIdentifierSet>"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0lr48l8s32l8r56l8s40l8
- ___swift_memcpy72_8
- ___swift_memcpy73_8
- _objc_release_x10
- _swift_retain_x11
- _symbolic Sb7success_______pSg4itemSdSg9startTimeSd03endD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
- _symbolic yt______pIgrzo_ s5ErrorP
```
