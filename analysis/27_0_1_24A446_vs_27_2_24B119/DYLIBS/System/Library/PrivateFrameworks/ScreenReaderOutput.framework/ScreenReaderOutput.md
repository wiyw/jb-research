## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReaderOutput.framework/ScreenReaderOutput`

```diff

-465.0.0.0.0
-  __TEXT.__text: 0x9cbf4
-  __TEXT.__objc_methlist: 0x9008
-  __TEXT.__const: 0x183c
-  __TEXT.__cstring: 0x5b79
+467.3.4.0.0
+  __TEXT.__text: 0x9f070
+  __TEXT.__objc_methlist: 0x9328
+  __TEXT.__const: 0x184c
+  __TEXT.__cstring: 0x5bf5
   __TEXT.__swift5_typeref: 0xeec
   __TEXT.__constg_swiftt: 0x960
   __TEXT.__swift5_builtin: 0xb4
   __TEXT.__swift5_types: 0xa4
-  __TEXT.__oslogstring: 0x287d
+  __TEXT.__oslogstring: 0x287a
   __TEXT.__swift5_reflstr: 0x605
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_fieldmd: 0x7f8

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x9c
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x193c
+  __TEXT.__gcc_except_tab: 0x1984
   __TEXT.__ustring: 0x9e
-  __TEXT.__unwind_info: 0x28b8
+  __TEXT.__unwind_info: 0x2948
   __TEXT.__eh_frame: 0xa30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1270
+  __DATA_CONST.__const: 0x1310
   __DATA_CONST.__objc_classlist: 0x328
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4780
+  __DATA_CONST.__objc_selrefs: 0x48c0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x380
   __DATA_CONST.__got: 0x790
-  __AUTH_CONST.__const: 0x32a0
-  __AUTH_CONST.__cfstring: 0x5680
-  __AUTH_CONST.__objc_const: 0xbc58
+  __AUTH_CONST.__const: 0x3280
+  __AUTH_CONST.__cfstring: 0x5720
+  __AUTH_CONST.__objc_const: 0xbdd0
   __AUTH_CONST.__objc_intobj: 0xa68
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH_CONST.__auth_ptr: 0x2c8
   __AUTH.__objc_data: 0x360
   __AUTH.__data: 0x80
-  __DATA.__objc_ivar: 0x8c8
-  __DATA.__data: 0x1680
-  __DATA.__bss: 0x1100
+  __DATA.__objc_ivar: 0x8dc
+  __DATA.__data: 0x1690
+  __DATA.__bss: 0x10f0
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x1d10
   __DATA_DIRTY.__data: 0xc20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3974
-  Symbols:   5771
+  Functions: 4032
+  Symbols:   5840
   CStrings:  0
 
Symbols:
+ -[SCROBrailleClient setTabularFocusRow:col:]
+ -[SCROBrailleClient setTabularZoomLevel:]
+ -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ -[SCROBrailleClientXPC setTabularFocusRow:col:]
+ -[SCROBrailleClientXPC setTabularZoomLevel:]
+ -[SCROBrailleDisplay _cancelPendingCellWrites]
+ -[SCROBrailleDisplay _getStructuredStatusCellIndex:forRawRouterIndex:]
+ -[SCROBrailleDisplay _linePanWindow]
+ -[SCROBrailleDisplay _structuredBraillePanWindow:isBackward:]
+ -[SCROBrailleDisplay _structuredBraillePlanarPanIsPageUp:]
+ -[SCROBrailleDisplay handleCommandTabularZoomInEvent:forDispatcher:]
+ -[SCROBrailleDisplay handleCommandTabularZoomOutEvent:forDispatcher:]
+ -[SCROBrailleDisplayCommandDispatcher _handleTabularZoomInEvent:]
+ -[SCROBrailleDisplayCommandDispatcher _handleTabularZoomOutEvent:]
+ -[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]
+ -[SCROBrailleDisplayManager _eventQueue_stepTabularZoomIn:]
+ -[SCROBrailleDisplayManager brailleDisplay:didPlanarPanPageDown:elementToken:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:didPlanarPanPageUp:elementToken:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:tabularZoomInWithKey:]
+ -[SCROBrailleDisplayManager brailleDisplay:tabularZoomOutWithKey:]
+ -[SCROBrailleDisplayManager setTabularFocusRow:col:]
+ -[SCROBrailleDisplayManager setTabularZoomLevel:]
+ -[SCROBrailleDisplayManager tabularZoomDidChange:]
+ -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandler handleTabularZoomDidChange:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandlerXPC handleTabularZoomDidChange:]
+ -[SCROBrailleHandlerXPC setTabularFocusRow:col:]
+ -[SCROBrailleHandlerXPC setTabularZoomLevel:]
+ -[SCROBrailleKey _resetTabularCellRoute]
+ -[SCROBrailleKey isTabularCellRoute]
+ -[SCROBrailleKey setIsTabularCellRoute:]
+ -[SCROBrailleKey setTabularCellCol:]
+ -[SCROBrailleKey setTabularCellRow:]
+ -[SCROBrailleKey tabularCellCol]
+ -[SCROBrailleKey tabularCellRow]
+ -[SCROMobileBrailleDisplayInputManager _storedUserDefaultsForModelIdentifier:]
+ -[SCROMobileBrailleDisplayInputManager _userDefaultsForDisplayWithToken:]
+ -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:productName:driverIdentifier:]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject modelIdentifierForPlist]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject setModelIdentifierForPlist:]
+ GCC_except_table1025
+ GCC_except_table1089
+ GCC_except_table1091
+ GCC_except_table1093
+ GCC_except_table1095
+ GCC_except_table1162
+ GCC_except_table1190
+ GCC_except_table1195
+ GCC_except_table1199
+ GCC_except_table1202
+ GCC_except_table1204
+ GCC_except_table1235
+ GCC_except_table1242
+ GCC_except_table128
+ GCC_except_table129
+ GCC_except_table132
+ GCC_except_table1374
+ GCC_except_table1587
+ GCC_except_table1711
+ GCC_except_table1850
+ GCC_except_table1852
+ GCC_except_table1860
+ GCC_except_table1870
+ GCC_except_table1954
+ GCC_except_table1999
+ GCC_except_table2003
+ GCC_except_table2115
+ GCC_except_table2136
+ GCC_except_table2141
+ GCC_except_table2147
+ GCC_except_table2246
+ GCC_except_table2433
+ GCC_except_table2451
+ GCC_except_table2567
+ GCC_except_table2568
+ GCC_except_table2569
+ GCC_except_table2573
+ GCC_except_table2578
+ GCC_except_table2579
+ GCC_except_table2580
+ GCC_except_table2581
+ GCC_except_table2582
+ GCC_except_table2584
+ GCC_except_table2585
+ GCC_except_table2586
+ GCC_except_table2590
+ GCC_except_table2595
+ GCC_except_table2597
+ GCC_except_table2600
+ GCC_except_table2948
+ GCC_except_table2964
+ GCC_except_table2983
+ GCC_except_table2984
+ GCC_except_table2985
+ GCC_except_table3048
+ GCC_except_table3050
+ GCC_except_table3052
+ GCC_except_table3053
+ GCC_except_table3055
+ GCC_except_table3057
+ GCC_except_table444
+ GCC_except_table456
+ GCC_except_table488
+ GCC_except_table489
+ GCC_except_table511
+ GCC_except_table512
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table542
+ GCC_except_table545
+ GCC_except_table548
+ GCC_except_table549
+ GCC_except_table552
+ GCC_except_table562
+ GCC_except_table582
+ GCC_except_table585
+ GCC_except_table593
+ GCC_except_table595
+ GCC_except_table601
+ GCC_except_table617
+ GCC_except_table620
+ GCC_except_table624
+ GCC_except_table625
+ GCC_except_table627
+ GCC_except_table631
+ GCC_except_table64
+ GCC_except_table649
+ GCC_except_table650
+ GCC_except_table653
+ GCC_except_table851
+ GCC_except_table892
+ GCC_except_table894
+ OBJC_IVAR_$_SCROBrailleDisplay._driverModelIdentifierForAnalytics
+ OBJC_IVAR_$_SCROBrailleKey._isTabularCellRoute
+ OBJC_IVAR_$_SCROBrailleKey._tabularCellCol
+ OBJC_IVAR_$_SCROBrailleKey._tabularCellRow
+ _OBJC_IVAR_$_SCROMobileBrailleDisplayInputManagerCacheObject._modelIdentifierForPlist
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BRLLayoutManagerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SCROBrailleDisplayDelegate
+ ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke
+ ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke_2
+ ___104-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]_block_invoke
+ ___104-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]_block_invoke_2
+ ___105-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]_block_invoke
+ ___105-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]_block_invoke_2
+ ___116-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]_block_invoke
+ ___116-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]_block_invoke_2
+ ___49-[SCROBrailleDisplayManager setTabularZoomLevel:]_block_invoke
+ ___52-[SCROBrailleDisplayManager setTabularFocusRow:col:]_block_invoke
+ ___52-[SCROBrailleHandlerXPC handleTabularZoomDidChange:]_block_invoke
+ ___59-[SCROBrailleDisplayManager _eventQueue_stepTabularZoomIn:]_block_invoke
+ ___92-[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]_block_invoke
+ ___94-[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]_block_invoke
+ ___95-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___96-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_73_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_80_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_81_e8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ _kSCROBrailleDisplayModelIdentifierForAnalytics
+ _kSCROBraillePrintTextRowsAttribute
- -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:]
- GCC_except_table1062
- GCC_except_table1064
- GCC_except_table1066
- GCC_except_table1068
- GCC_except_table1130
- GCC_except_table1158
- GCC_except_table1163
- GCC_except_table1167
- GCC_except_table1170
- GCC_except_table1172
- GCC_except_table1203
- GCC_except_table1210
- GCC_except_table126
- GCC_except_table127
- GCC_except_table130
- GCC_except_table1332
- GCC_except_table1537
- GCC_except_table1657
- GCC_except_table1796
- GCC_except_table1798
- GCC_except_table1806
- GCC_except_table1816
- GCC_except_table1900
- GCC_except_table1945
- GCC_except_table1949
- GCC_except_table2061
- GCC_except_table2082
- GCC_except_table2087
- GCC_except_table2093
- GCC_except_table2192
- GCC_except_table2379
- GCC_except_table2397
- GCC_except_table2513
- GCC_except_table2514
- GCC_except_table2515
- GCC_except_table2519
- GCC_except_table2524
- GCC_except_table2525
- GCC_except_table2526
- GCC_except_table2527
- GCC_except_table2528
- GCC_except_table2530
- GCC_except_table2531
- GCC_except_table2532
- GCC_except_table2536
- GCC_except_table2541
- GCC_except_table2543
- GCC_except_table2546
- GCC_except_table2890
- GCC_except_table2906
- GCC_except_table2925
- GCC_except_table2926
- GCC_except_table2927
- GCC_except_table2990
- GCC_except_table2992
- GCC_except_table2994
- GCC_except_table2995
- GCC_except_table2997
- GCC_except_table2999
- GCC_except_table438
- GCC_except_table449
- GCC_except_table481
- GCC_except_table482
- GCC_except_table502
- GCC_except_table503
- GCC_except_table513
- GCC_except_table515
- GCC_except_table533
- GCC_except_table534
- GCC_except_table536
- GCC_except_table539
- GCC_except_table540
- GCC_except_table553
- GCC_except_table573
- GCC_except_table575
- GCC_except_table576
- GCC_except_table586
- GCC_except_table592
- GCC_except_table606
- GCC_except_table607
- GCC_except_table608
- GCC_except_table609
- GCC_except_table611
- GCC_except_table62
- GCC_except_table622
- GCC_except_table640
- GCC_except_table641
- GCC_except_table644
- GCC_except_table824
- GCC_except_table865
- GCC_except_table867
- GCC_except_table998
- ___82-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]_block_invoke
- ___83-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]_block_invoke
- ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___isBrailleXPCOn_block_invoke
- _isBrailleXPCOn
- _isBrailleXPCOn.brailleXPCOn
- _isBrailleXPCOn.onceToken
```
