## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils`

```diff

-900.58.0.0.0
-  __TEXT.__text: 0x117568
-  __TEXT.__objc_methlist: 0xa040
-  __TEXT.__cstring: 0x1d6f7
+910.31.0.0.0
+  __TEXT.__text: 0x118ec8
+  __TEXT.__objc_methlist: 0xa120
+  __TEXT.__cstring: 0x1d8de
   __TEXT.__const: 0x229c
-  __TEXT.__gcc_except_tab: 0x1ba0
-  __TEXT.__oslogstring: 0x49b7
-  __TEXT.__unwind_info: 0x39d8
+  __TEXT.__gcc_except_tab: 0x1bcc
+  __TEXT.__oslogstring: 0x4a72
+  __TEXT.__unwind_info: 0x3a50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x29c0
+  __DATA_CONST.__const: 0x2a58
   __DATA_CONST.__objc_classlist: 0x350
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x158
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5120
+  __DATA_CONST.__objc_selrefs: 0x51e0
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x240
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x6c0
-  __AUTH_CONST.__const: 0x2828
-  __AUTH_CONST.__cfstring: 0x4540
-  __AUTH_CONST.__objc_const: 0x13c40
+  __DATA_CONST.__got: 0x6c8
+  __AUTH_CONST.__const: 0x28a8
+  __AUTH_CONST.__cfstring: 0x45c0
+  __AUTH_CONST.__objc_const: 0x13cc0
   __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1858
+  __AUTH_CONST.__auth_got: 0x1870
   __AUTH_CONST.__auth_ptr: 0x0
   __AUTH.__objc_data: 0x2030
   __AUTH.__data: 0xa00
-  __DATA.__objc_ivar: 0x1510
+  __DATA.__objc_ivar: 0x1514
   __DATA.__data: 0x2f50
-  __DATA.__bss: 0x13f8
+  __DATA.__bss: 0x1400
   __DATA.__common: 0x2a
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__data: 0x88

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5789
-  Symbols:   10202
+  Functions: 5821
+  Symbols:   10246
   CStrings:  0
 
Symbols:
+ +[CUFile deletePath:dispatchQueue:completionHandler:]
+ +[CUFile deletePath:error:]
+ +[CUFile renameWithOldPath:newPath:dispatchQueue:completionHandler:]
+ +[CUFile renameWithOldPath:newPath:error:]
+ +[CUFile validatedFilename:error:]
+ +[CUOPACK encodeObjectAsDispatchData:flags:error:]
+ -[CUNANDataSession _scheduleWFAStopTimeout]
+ -[CUNANDataSession _scheduleWFAStop]
+ -[CUPairingSession appInfoPostAuth]
+ -[CUPairingSession setAppInfoPostAuth:]
+ -[CUSystemMonitor systemNameSync]
+ GCC_except_table1032
+ GCC_except_table1351
+ GCC_except_table1386
+ GCC_except_table1391
+ GCC_except_table1392
+ GCC_except_table1395
+ GCC_except_table1442
+ GCC_except_table1443
+ GCC_except_table1474
+ GCC_except_table1477
+ GCC_except_table1483
+ GCC_except_table1488
+ GCC_except_table1491
+ GCC_except_table1539
+ GCC_except_table1540
+ GCC_except_table2289
+ GCC_except_table2290
+ GCC_except_table2313
+ GCC_except_table2358
+ GCC_except_table2442
+ GCC_except_table2466
+ GCC_except_table2503
+ GCC_except_table2507
+ GCC_except_table2574
+ GCC_except_table2575
+ GCC_except_table2577
+ GCC_except_table2578
+ GCC_except_table2580
+ GCC_except_table2585
+ GCC_except_table2589
+ GCC_except_table2592
+ GCC_except_table2595
+ GCC_except_table2598
+ GCC_except_table2605
+ GCC_except_table2608
+ GCC_except_table2622
+ GCC_except_table2683
+ GCC_except_table3017
+ GCC_except_table3018
+ GCC_except_table3106
+ GCC_except_table3128
+ GCC_except_table3162
+ GCC_except_table3166
+ GCC_except_table3210
+ GCC_except_table3213
+ GCC_except_table3216
+ GCC_except_table3238
+ GCC_except_table3246
+ GCC_except_table3251
+ GCC_except_table3257
+ GCC_except_table3530
+ GCC_except_table3586
+ GCC_except_table3960
+ GCC_except_table4008
+ GCC_except_table4273
+ GCC_except_table4331
+ GCC_except_table4338
+ GCC_except_table4346
+ GCC_except_table4461
+ GCC_except_table4488
+ GCC_except_table4489
+ GCC_except_table4551
+ GCC_except_table4555
+ GCC_except_table4559
+ GCC_except_table4582
+ GCC_except_table4656
+ GCC_except_table4657
+ GCC_except_table4658
+ GCC_except_table4659
+ GCC_except_table4661
+ GCC_except_table4663
+ GCC_except_table4665
+ GCC_except_table4671
+ GCC_except_table4685
+ GCC_except_table4694
+ GCC_except_table4695
+ GCC_except_table4703
+ GCC_except_table4717
+ GCC_except_table4721
+ GCC_except_table4723
+ GCC_except_table4724
+ GCC_except_table4725
+ GCC_except_table4726
+ GCC_except_table4727
+ GCC_except_table4729
+ GCC_except_table4730
+ GCC_except_table4731
+ GCC_except_table4732
+ GCC_except_table4733
+ GCC_except_table4734
+ GCC_except_table4735
+ GCC_except_table4736
+ GCC_except_table4737
+ GCC_except_table4738
+ GCC_except_table4739
+ GCC_except_table4740
+ GCC_except_table4741
+ GCC_except_table4743
+ GCC_except_table4744
+ GCC_except_table4745
+ GCC_except_table4747
+ GCC_except_table5295
+ GCC_except_table5308
+ GCC_except_table5377
+ GCC_except_table5381
+ GCC_except_table5386
+ GCC_except_table5405
+ GCC_except_table5414
+ GCC_except_table5663
+ GCC_except_table5664
+ GCC_except_table5677
+ GCC_except_table704
+ GCC_except_table811
+ GCC_except_table826
+ GCC_except_table828
+ GCC_except_table831
+ _CFDataSetLength
+ _OBJC_IVAR_$_CUPairingSession._appInfoPostAuth
+ _OPACKEncoderCreateDispatchData
+ __BonjourAdvertiserApplyString
+ __GlobalInitialize
+ __OPACKEncodeRoot
+ __OPACKEncoderDispatchDataCallback
+ __OPACKEncoderDispatchDataFlushScratch
+ __PairingSessionLimitPeerInfo
+ ___36-[CUNANDataSession _scheduleWFAStop]_block_invoke
+ ___53+[CUFile deletePath:dispatchQueue:completionHandler:]_block_invoke
+ ___68+[CUFile renameWithOldPath:newPath:dispatchQueue:completionHandler:]_block_invoke
+ ___BonjourAdvertiserSetDomain_block_invoke
+ ___BonjourAdvertiserSetFlags_block_invoke
+ ___BonjourAdvertiserSetInterfaceIndex_block_invoke
+ ___BonjourAdvertiserSetInterfaceName_block_invoke
+ ___BonjourAdvertiserSetName_block_invoke
+ ___BonjourAdvertiserSetP2P_block_invoke
+ ___BonjourAdvertiserSetPort_block_invoke
+ ___BonjourAdvertiserSetServiceType_block_invoke
+ ___BonjourAdvertiserSetTXTRecord_block_invoke
+ ___BonjourAdvertiserSetTrafficFlags_block_invoke
+ ____BonjourAdvertiserApplyString_block_invoke
+ ____OPACKEncoderDispatchDataCallback_block_invoke
+ ___block_descriptor_32_e142_v24?0^{BonjourAdvertiserPrivate={__CFRuntimeBase=QAQ}^{LogCategory}^{_DNSServiceRef_t}I^{__CFData}?^{__CFString}qIQC*QI[17c]*Ci**SCI}8*16l
+ ___block_descriptor_41_e5_v8?0l
+ ___block_descriptor_56_e5_v8?0l
+ ___block_descriptor_57_e8_32b_e5_v8?0ls32l8
+ __dispatch_data_empty
+ _dispatch_data_create
+ _dispatch_data_create_concat
+ _gGlobalInitOnce
- GCC_except_table1020
- GCC_except_table1339
- GCC_except_table1374
- GCC_except_table1379
- GCC_except_table1380
- GCC_except_table1383
- GCC_except_table1430
- GCC_except_table1431
- GCC_except_table1462
- GCC_except_table1465
- GCC_except_table1471
- GCC_except_table1476
- GCC_except_table1479
- GCC_except_table1527
- GCC_except_table1528
- GCC_except_table2267
- GCC_except_table2268
- GCC_except_table2291
- GCC_except_table2336
- GCC_except_table2420
- GCC_except_table2444
- GCC_except_table2481
- GCC_except_table2485
- GCC_except_table2552
- GCC_except_table2553
- GCC_except_table2555
- GCC_except_table2556
- GCC_except_table2558
- GCC_except_table2563
- GCC_except_table2567
- GCC_except_table2570
- GCC_except_table2573
- GCC_except_table2576
- GCC_except_table2583
- GCC_except_table2586
- GCC_except_table2600
- GCC_except_table2661
- GCC_except_table2993
- GCC_except_table2994
- GCC_except_table3082
- GCC_except_table3104
- GCC_except_table3138
- GCC_except_table3142
- GCC_except_table3186
- GCC_except_table3189
- GCC_except_table3190
- GCC_except_table3192
- GCC_except_table3222
- GCC_except_table3227
- GCC_except_table3233
- GCC_except_table3506
- GCC_except_table3562
- GCC_except_table3935
- GCC_except_table3983
- GCC_except_table4248
- GCC_except_table4306
- GCC_except_table4313
- GCC_except_table4321
- GCC_except_table4436
- GCC_except_table4463
- GCC_except_table4464
- GCC_except_table4526
- GCC_except_table4530
- GCC_except_table4532
- GCC_except_table4534
- GCC_except_table4631
- GCC_except_table4632
- GCC_except_table4633
- GCC_except_table4634
- GCC_except_table4636
- GCC_except_table4638
- GCC_except_table4640
- GCC_except_table4642
- GCC_except_table4646
- GCC_except_table4648
- GCC_except_table4660
- GCC_except_table4669
- GCC_except_table4670
- GCC_except_table4672
- GCC_except_table4674
- GCC_except_table4676
- GCC_except_table4677
- GCC_except_table4678
- GCC_except_table4679
- GCC_except_table4681
- GCC_except_table4682
- GCC_except_table4683
- GCC_except_table4690
- GCC_except_table4693
- GCC_except_table4696
- GCC_except_table4700
- GCC_except_table4705
- GCC_except_table4709
- GCC_except_table4710
- GCC_except_table4711
- GCC_except_table4712
- GCC_except_table4713
- GCC_except_table4714
- GCC_except_table4716
- GCC_except_table4719
- GCC_except_table4720
- GCC_except_table5346
- GCC_except_table5350
- GCC_except_table5355
- GCC_except_table5373
- GCC_except_table5382
- GCC_except_table5631
- GCC_except_table5632
- GCC_except_table5645
- GCC_except_table692
- GCC_except_table799
- GCC_except_table814
- GCC_except_table816
- GCC_except_table819
- __GlobalEnsureInitialized
```
