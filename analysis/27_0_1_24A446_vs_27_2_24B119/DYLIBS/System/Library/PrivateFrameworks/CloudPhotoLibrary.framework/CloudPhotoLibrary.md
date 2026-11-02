## CloudPhotoLibrary

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x1cbee8
-  __TEXT.__objc_methlist: 0x15d54
+916.57.154.0.0
+  __TEXT.__text: 0x1cc410
+  __TEXT.__objc_methlist: 0x15d04
   __TEXT.__const: 0x328
-  __TEXT.__gcc_except_tab: 0x4d78
-  __TEXT.__oslogstring: 0x16d40
-  __TEXT.__cstring: 0x181b9
+  __TEXT.__gcc_except_tab: 0x4d4c
+  __TEXT.__oslogstring: 0x16db8
+  __TEXT.__cstring: 0x182b0
+  __TEXT.__ustring: 0xc
   __TEXT.__unwind_info: 0x6d60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x1b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9318
+  __DATA_CONST.__objc_selrefs: 0x9308
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x940
-  __DATA_CONST.__objc_arraydata: 0x1448
+  __DATA_CONST.__objc_arraydata: 0x14c8
   __DATA_CONST.__got: 0xb48
   __AUTH_CONST.__const: 0x2cc0
-  __AUTH_CONST.__cfstring: 0x17d60
-  __AUTH_CONST.__objc_const: 0x239e8
-  __AUTH_CONST.__objc_intobj: 0x798
+  __AUTH_CONST.__cfstring: 0x17ee0
+  __AUTH_CONST.__objc_const: 0x23aa8
+  __AUTH_CONST.__objc_intobj: 0x7e0
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__objc_dictobj: 0x140
+  __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_floatobj: 0x50
-  __AUTH_CONST.__auth_got: 0x7a8
+  __AUTH_CONST.__auth_got: 0x7a0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x1c28
-  __DATA.__data: 0x1680
-  __DATA.__bss: 0xc98
+  __DATA.__objc_ivar: 0x1c3c
+  __DATA.__data: 0x130
+  __DATA.__bss: 0xc88
   __DATA.__common: 0x30
-  __DATA_DIRTY.__objc_data: 0x62c0
-  __DATA_DIRTY.__bss: 0x390
+  __DATA_DIRTY.__objc_data: 0x6310
+  __DATA_DIRTY.__data: 0x1550
+  __DATA_DIRTY.__bss: 0x3a0
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcupolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9798
-  Symbols:   15566
+  Functions: 9801
+  Symbols:   15574
   CStrings:  0
 
Symbols:
+ +[CPLShare scopeTypeForShareURL:]
+ -[CPLEngineLibrary containerHasBeenWipedDueToEncryptedDataReset]
+ -[CPLEngineLibrary setContainerHasBeenWipedDueToEncryptedDataReset:]
+ -[CPLEngineScheduler _disableSynchronizationBecauseContainerHasBeenWipedDueToEncryptedDataResetLocked]
+ -[CPLEngineScheduler noteContainerHasBeenWipedDueToEncryptedDataReset]
+ -[CPLNetworkState isSufficientlyDifferentFromNetworkState:]
+ -[CPLPostChange lastUserEditedDate]
+ -[CPLPostChange setLastUserEditedDate:]
+ -[CPLPushToTransportScopeTask _contributorsUpdatesInTransaction:localChanges:]
+ -[CPLPushToTransportScopeTask _updateContributors:localChanges:]
+ -[CPLStatus containerHasBeenWipedDueToEncryptedDataReset]
+ -[CPLStatus setContainerHasBeenWipedDueToEncryptedDataReset:]
+ -[CPLSyncSession report:]
+ -[CPLSyncSession reportCount:direction:]
+ -[CPLTextCommentChange lastUserEditedDate]
+ -[CPLTextCommentChange setLastUserEditedDate:]
+ -[CPLUploadPushedChangesTask _setScopeHasChangesToPullFromTransportInTransaction:]
+ GCC_except_table1125
+ GCC_except_table1208
+ GCC_except_table1262
+ GCC_except_table1267
+ GCC_except_table1313
+ GCC_except_table1333
+ GCC_except_table1507
+ GCC_except_table1556
+ GCC_except_table1562
+ GCC_except_table1569
+ GCC_except_table1579
+ GCC_except_table1586
+ GCC_except_table1589
+ GCC_except_table1592
+ GCC_except_table1604
+ GCC_except_table1686
+ GCC_except_table1774
+ GCC_except_table2026
+ GCC_except_table2034
+ GCC_except_table2260
+ GCC_except_table2261
+ GCC_except_table2264
+ GCC_except_table2271
+ GCC_except_table2275
+ GCC_except_table2302
+ GCC_except_table2309
+ GCC_except_table2319
+ GCC_except_table2322
+ GCC_except_table2511
+ GCC_except_table2610
+ GCC_except_table2676
+ GCC_except_table2684
+ GCC_except_table2725
+ GCC_except_table2817
+ GCC_except_table2824
+ GCC_except_table2977
+ GCC_except_table3066
+ GCC_except_table3358
+ GCC_except_table3360
+ GCC_except_table3465
+ GCC_except_table3476
+ GCC_except_table3531
+ GCC_except_table3533
+ GCC_except_table3646
+ GCC_except_table3670
+ GCC_except_table3758
+ GCC_except_table3764
+ GCC_except_table3925
+ GCC_except_table3972
+ GCC_except_table4217
+ GCC_except_table4297
+ GCC_except_table4299
+ GCC_except_table4308
+ GCC_except_table4514
+ GCC_except_table4528
+ GCC_except_table4686
+ GCC_except_table4716
+ GCC_except_table4747
+ GCC_except_table4765
+ GCC_except_table4772
+ GCC_except_table4780
+ GCC_except_table4782
+ GCC_except_table4798
+ GCC_except_table4801
+ GCC_except_table5175
+ GCC_except_table5209
+ GCC_except_table5211
+ GCC_except_table5237
+ GCC_except_table5371
+ GCC_except_table5381
+ GCC_except_table5438
+ GCC_except_table5441
+ GCC_except_table5619
+ GCC_except_table5627
+ GCC_except_table5717
+ GCC_except_table5721
+ GCC_except_table5727
+ GCC_except_table5734
+ GCC_except_table5749
+ GCC_except_table5750
+ GCC_except_table5756
+ GCC_except_table5802
+ GCC_except_table5808
+ GCC_except_table5812
+ GCC_except_table5843
+ GCC_except_table5845
+ GCC_except_table5847
+ GCC_except_table5849
+ GCC_except_table5851
+ GCC_except_table5855
+ GCC_except_table5867
+ GCC_except_table5868
+ GCC_except_table5870
+ GCC_except_table5915
+ GCC_except_table5917
+ GCC_except_table5919
+ GCC_except_table5931
+ GCC_except_table6081
+ GCC_except_table6123
+ GCC_except_table6133
+ GCC_except_table6134
+ GCC_except_table6193
+ GCC_except_table6196
+ GCC_except_table6281
+ GCC_except_table6283
+ GCC_except_table6299
+ GCC_except_table6322
+ GCC_except_table6338
+ GCC_except_table6340
+ GCC_except_table6502
+ GCC_except_table6530
+ GCC_except_table6573
+ GCC_except_table6593
+ GCC_except_table6619
+ GCC_except_table6630
+ GCC_except_table6651
+ GCC_except_table6671
+ GCC_except_table6675
+ GCC_except_table6701
+ GCC_except_table6733
+ GCC_except_table6773
+ GCC_except_table6838
+ GCC_except_table6864
+ GCC_except_table6868
+ GCC_except_table6877
+ GCC_except_table6895
+ GCC_except_table6908
+ GCC_except_table6913
+ GCC_except_table6921
+ GCC_except_table6922
+ GCC_except_table6936
+ GCC_except_table6991
+ GCC_except_table7116
+ GCC_except_table7130
+ GCC_except_table7133
+ GCC_except_table7260
+ GCC_except_table7262
+ GCC_except_table7268
+ GCC_except_table7271
+ GCC_except_table7648
+ GCC_except_table7690
+ GCC_except_table7694
+ GCC_except_table7696
+ GCC_except_table7711
+ GCC_except_table7717
+ GCC_except_table7725
+ GCC_except_table7731
+ GCC_except_table7735
+ GCC_except_table7743
+ GCC_except_table7746
+ GCC_except_table775
+ GCC_except_table7773
+ GCC_except_table7796
+ GCC_except_table780
+ GCC_except_table7831
+ GCC_except_table786
+ GCC_except_table7862
+ GCC_except_table7873
+ GCC_except_table7896
+ GCC_except_table7898
+ GCC_except_table7900
+ GCC_except_table7931
+ GCC_except_table7982
+ GCC_except_table8126
+ GCC_except_table8152
+ GCC_except_table817
+ GCC_except_table8182
+ GCC_except_table833
+ GCC_except_table8339
+ GCC_except_table8341
+ GCC_except_table8371
+ GCC_except_table8380
+ GCC_except_table8385
+ GCC_except_table8401
+ GCC_except_table8415
+ GCC_except_table8425
+ GCC_except_table8430
+ GCC_except_table8514
+ GCC_except_table8601
+ GCC_except_table864
+ GCC_except_table8660
+ GCC_except_table8741
+ GCC_except_table8750
+ GCC_except_table8764
+ GCC_except_table8783
+ GCC_except_table8804
+ GCC_except_table884
+ GCC_except_table8851
+ GCC_except_table8855
+ GCC_except_table8859
+ GCC_except_table890
+ GCC_except_table8939
+ GCC_except_table899
+ GCC_except_table908
+ GCC_except_table920
+ _CPLRecordModificationDatePrecision
+ _OBJC_IVAR_$_CPLEngineScheduler._lastSessionFailedBecauseOfNetwork
+ _OBJC_IVAR_$_CPLPostChange._lastUserEditedDate
+ _OBJC_IVAR_$_CPLPushToTransportScopeTask._cloudCache
+ _OBJC_IVAR_$_CPLPushToTransportScopeTask._idMapping
+ _OBJC_IVAR_$_CPLTextCommentChange._lastUserEditedDate
+ _OBJC_IVAR_$_CPLUploadPushedChangesTask._hasNotedScopeNeedsToPullFromTransport
+ ___57-[CPLStatus containerHasBeenWipedDueToEncryptedDataReset]_block_invoke
+ ___61-[CPLStatus setContainerHasBeenWipedDueToEncryptedDataReset:]_block_invoke
+ ___64-[CPLPushToTransportScopeTask _updateContributors:localChanges:]_block_invoke
+ ___64-[CPLPushToTransportScopeTask _updateContributors:localChanges:]_block_invoke_2
+ ___70-[CPLEngineScheduler noteContainerHasBeenWipedDueToEncryptedDataReset]_block_invoke
+ ___78-[CPLPushToTransportScopeTask _contributorsUpdatesInTransaction:localChanges:]_block_invoke
+ ___82-[CPLUploadPushedChangesTask _setScopeHasChangesToPullFromTransportInTransaction:]_block_invoke
+ ___82-[CPLUploadPushedChangesTask _setScopeHasChangesToPullFromTransportInTransaction:]_block_invoke_2
+ ___block_descriptor_72_e8_32s40r48r56r64r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8r40l8r48l8r56l8r64l8
+ ___block_descriptor_72_e8_32s40s48s56r64r_e9_B16?0^8ls32l8s40l8r56l8s48l8r64l8
+ ___block_descriptor_80_e8_32s40s48r56r64r72r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8s40l8r48l8r56l8r64l8r72l8
+ ___block_descriptor_80_e8_32s40s48r56r64r72r_e5_v8?0ls32l8s40l8r48l8r56l8r64l8r72l8
+ ___block_descriptor_88_e8_32s40s48s56r64r72r80r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8s40l8s48l8r56l8r64l8r72l8r80l8
- -[CPLEngineLibrary containerHasBeenWiped]
- -[CPLEngineLibrary setContainerHasBeenWiped:]
- -[CPLEngineScheduler _disableSynchronizationBecauseContainerHasBeenWipedLocked]
- -[CPLEngineScheduler noteContainerHasBeenWiped]
- -[CPLNetworkState isSufficentlyDifferentFromNetworkState:]
- -[CPLPushToTransportScopeTask _contributorsUpdatesInTransaction:]
- -[CPLPushToTransportScopeTask _updateContributors:]
- -[CPLStatus containerHasBeenWiped]
- -[CPLStatus setContainerHasBeenWiped:]
- -[CPLUploadPushedChangesTask _canUseOverQuotaRule]
- -[CPLUploadPushedChangesTask _checkForRecordExistence]
- -[CPLUploadPushedChangesTask _copyResourceChangeFromChange:toChange:fingerprintScheme:error:]
- -[CPLUploadPushedChangesTask _noteSuccessfulUpdateInTransaction:]
- -[CPLUploadPushedChangesTask _reenqueueExtractedBatchWithRejectedRecords:extractedBatch:error:]
- GCC_except_table1123
- GCC_except_table1206
- GCC_except_table1260
- GCC_except_table1265
- GCC_except_table1311
- GCC_except_table1329
- GCC_except_table1505
- GCC_except_table1554
- GCC_except_table1558
- GCC_except_table1565
- GCC_except_table1575
- GCC_except_table1584
- GCC_except_table1587
- GCC_except_table1590
- GCC_except_table1596
- GCC_except_table1684
- GCC_except_table1772
- GCC_except_table2024
- GCC_except_table2032
- GCC_except_table2258
- GCC_except_table2259
- GCC_except_table2262
- GCC_except_table2269
- GCC_except_table2273
- GCC_except_table2300
- GCC_except_table2307
- GCC_except_table2317
- GCC_except_table2320
- GCC_except_table2509
- GCC_except_table2608
- GCC_except_table2674
- GCC_except_table2682
- GCC_except_table2723
- GCC_except_table2815
- GCC_except_table2822
- GCC_except_table2975
- GCC_except_table3064
- GCC_except_table3354
- GCC_except_table3356
- GCC_except_table3461
- GCC_except_table3472
- GCC_except_table3527
- GCC_except_table3529
- GCC_except_table3642
- GCC_except_table3666
- GCC_except_table3748
- GCC_except_table3754
- GCC_except_table3921
- GCC_except_table3968
- GCC_except_table4213
- GCC_except_table4289
- GCC_except_table4295
- GCC_except_table4304
- GCC_except_table4509
- GCC_except_table4523
- GCC_except_table4681
- GCC_except_table4711
- GCC_except_table4742
- GCC_except_table4760
- GCC_except_table4767
- GCC_except_table4775
- GCC_except_table4777
- GCC_except_table4791
- GCC_except_table4793
- GCC_except_table5170
- GCC_except_table5204
- GCC_except_table5206
- GCC_except_table5232
- GCC_except_table5366
- GCC_except_table5376
- GCC_except_table5433
- GCC_except_table5436
- GCC_except_table5614
- GCC_except_table5622
- GCC_except_table5712
- GCC_except_table5716
- GCC_except_table5722
- GCC_except_table5729
- GCC_except_table5744
- GCC_except_table5745
- GCC_except_table5751
- GCC_except_table5797
- GCC_except_table5803
- GCC_except_table5807
- GCC_except_table5833
- GCC_except_table5840
- GCC_except_table5842
- GCC_except_table5844
- GCC_except_table5846
- GCC_except_table5848
- GCC_except_table5850
- GCC_except_table5860
- GCC_except_table5862
- GCC_except_table5910
- GCC_except_table5912
- GCC_except_table5914
- GCC_except_table5926
- GCC_except_table6076
- GCC_except_table6118
- GCC_except_table6128
- GCC_except_table6129
- GCC_except_table6188
- GCC_except_table6191
- GCC_except_table6276
- GCC_except_table6278
- GCC_except_table6294
- GCC_except_table6317
- GCC_except_table6333
- GCC_except_table6335
- GCC_except_table6495
- GCC_except_table6523
- GCC_except_table6566
- GCC_except_table6586
- GCC_except_table6612
- GCC_except_table6623
- GCC_except_table6644
- GCC_except_table6664
- GCC_except_table6668
- GCC_except_table6694
- GCC_except_table6726
- GCC_except_table6766
- GCC_except_table6831
- GCC_except_table6857
- GCC_except_table6861
- GCC_except_table6870
- GCC_except_table6888
- GCC_except_table6901
- GCC_except_table6906
- GCC_except_table6914
- GCC_except_table6915
- GCC_except_table6929
- GCC_except_table6984
- GCC_except_table7109
- GCC_except_table7123
- GCC_except_table7126
- GCC_except_table7253
- GCC_except_table7255
- GCC_except_table7257
- GCC_except_table7261
- GCC_except_table7641
- GCC_except_table7683
- GCC_except_table7687
- GCC_except_table7689
- GCC_except_table7704
- GCC_except_table771
- GCC_except_table7710
- GCC_except_table7718
- GCC_except_table7724
- GCC_except_table7728
- GCC_except_table7736
- GCC_except_table7739
- GCC_except_table7759
- GCC_except_table776
- GCC_except_table7789
- GCC_except_table782
- GCC_except_table7824
- GCC_except_table7855
- GCC_except_table7866
- GCC_except_table7886
- GCC_except_table7889
- GCC_except_table7891
- GCC_except_table7924
- GCC_except_table793
- GCC_except_table7975
- GCC_except_table8119
- GCC_except_table8145
- GCC_except_table8175
- GCC_except_table823
- GCC_except_table8332
- GCC_except_table8334
- GCC_except_table8364
- GCC_except_table8373
- GCC_except_table8378
- GCC_except_table8394
- GCC_except_table8408
- GCC_except_table8418
- GCC_except_table842
- GCC_except_table8423
- GCC_except_table8507
- GCC_except_table8594
- GCC_except_table8653
- GCC_except_table8731
- GCC_except_table8746
- GCC_except_table8768
- GCC_except_table8774
- GCC_except_table8793
- GCC_except_table8803
- GCC_except_table882
- GCC_except_table8845
- GCC_except_table8852
- GCC_except_table8856
- GCC_except_table888
- GCC_except_table8936
- GCC_except_table897
- GCC_except_table906
- GCC_except_table918
- _OBJC_IVAR_$_CPLUploadPushedChangesTask._hasPushedSomeChanges
- ___34-[CPLStatus containerHasBeenWiped]_block_invoke
- ___38-[CPLStatus setContainerHasBeenWiped:]_block_invoke
- ___47-[CPLEngineScheduler noteContainerHasBeenWiped]_block_invoke
- ___51-[CPLPushToTransportScopeTask _updateContributors:]_block_invoke
- ___51-[CPLPushToTransportScopeTask _updateContributors:]_block_invoke_2
- ___65-[CPLPushToTransportScopeTask _contributorsUpdatesInTransaction:]_block_invoke
- ___93-[CPLUploadPushedChangesTask _copyResourceChangeFromChange:toChange:fingerprintScheme:error:]_block_invoke
- ___block_descriptor_64_e8_32s40r48r56r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8r40l8r48l8r56l8
- ___block_descriptor_72_e8_32s40s48r56r64r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8s40l8r48l8r56l8r64l8
- ___block_descriptor_72_e8_32s40s48s56r64r_e64_B48?0"CPLRecordChange"8"CPLRecordChange"16"NSString"24:32:40lr56l8s32l8r64l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56r64r_e9_B16?0^8ls32l8s40l8s48l8r56l8r64l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e35_v16?0"CPLEngineStoreTransaction"8ls32l8s40l8s48l8r56l8r64l8r72l8
- __os_feature_enabled_impl
```
