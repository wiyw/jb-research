## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

```diff

-625.1.29.10.33
-  __TEXT.__text: 0xf1258
-  __TEXT.__objc_methlist: 0x8b80
-  __TEXT.__const: 0x2048
-  __TEXT.__gcc_except_tab: 0xc370
-  __TEXT.__cstring: 0x10160
-  __TEXT.__oslogstring: 0xb38c
+625.2.8.10.7
+  __TEXT.__text: 0xf2fc0
+  __TEXT.__objc_methlist: 0x8c88
+  __TEXT.__const: 0x2058
+  __TEXT.__gcc_except_tab: 0xc674
+  __TEXT.__cstring: 0x102e0
+  __TEXT.__oslogstring: 0xb63c
   __TEXT.__dlopen_cstrs: 0xb2
   __TEXT.__constg_swiftt: 0xadc
   __TEXT.__swift5_typeref: 0xf5e

   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_assocty: 0xa0
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x5980
+  __TEXT.__unwind_info: 0x5a98
   __TEXT.__eh_frame: 0x3d68
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3280
+  __DATA_CONST.__const: 0x3328
   __DATA_CONST.__objc_classlist: 0x260
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5130
+  __DATA_CONST.__objc_selrefs: 0x51a8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x1f0
   __DATA_CONST.__objc_arraydata: 0x370
-  __DATA_CONST.__got: 0xa20
+  __DATA_CONST.__got: 0xa28
   __AUTH_CONST.__const: 0x2be8
-  __AUTH_CONST.__cfstring: 0x6500
-  __AUTH_CONST.__objc_const: 0xa828
+  __AUTH_CONST.__cfstring: 0x65c0
+  __AUTH_CONST.__objc_const: 0xa8a8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x3c0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__auth_got: 0xf80
   __AUTH_CONST.__auth_ptr: 0x440
-  __AUTH.__objc_data: 0x168
-  __AUTH.__data: 0x460
-  __DATA.__objc_ivar: 0x638
-  __DATA.__data: 0x1b38
-  __DATA.__bss: 0x1d00
-  __DATA_DIRTY.__objc_data: 0x1590
-  __DATA_DIRTY.__data: 0xc8
-  __DATA_DIRTY.__bss: 0x218
+  __AUTH.__objc_data: 0x98
+  __AUTH.__data: 0xd8
+  __DATA.__objc_ivar: 0x63c
+  __DATA.__data: 0x1b20
+  __DATA.__bss: 0x1ce0
+  __DATA_DIRTY.__objc_data: 0x1660
+  __DATA_DIRTY.__data: 0x468
+  __DATA_DIRTY.__bss: 0x238
   - /System/Library/Frameworks/CloudKit.framework/CloudKit
   - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4938
-  Symbols:   6597
+  Functions: 4972
+  Symbols:   6641
   CStrings:  0
 
Symbols:
+ -[WBBookmarkDBAccess item:isDescendantOfFolderWithType:]
+ -[WBTabCollection deletePebblePinnedSuggestions]
+ -[WBTabCollection localTabGroupWithUUID:]
+ -[WBTabCollection migratePebblePinnedSuggestionsToBookmarkCollection:]
+ -[WBTabCollection pebblePinnedSuggestionsFolderIDIfExists]
+ -[WBTabCollection pebblePinnedSuggestionsFolder]
+ -[WBTabCollection pebblePinnedSuggestions]
+ -[WBTabGroupManager localTabGroupWithUUID:]
+ -[WBWindowState initWithUUID:localTabGroup:sceneID:]
+ -[WebBookmarkCollection _shouldWaitForLockForVersionUpgradeMigrations]
+ -[WebBookmarkCollection _specialIDOfBookmarkWithID:]
+ -[WebBookmarkCollection _tryPerformDatabaseUpdatesWithApplyInMemoryChanges:secureDelete:shouldWaitForLock:updates:]
+ -[WebBookmarkCollection doesBookmark:haveAncestorWithSpecialID:]
+ -[WebBookmarkCollection enumerateBookmarks:andReadingListItems:andPinnedSuggestions:matchingString:usingBlock:]
+ -[WebBookmarkCollection firstPebblePinnedSuggestionWithURLMatchingString:]
+ -[WebBookmarkCollection isBookmarkPebblePinnedSuggestion:]
+ -[WebBookmarkCollection migratePebblePinnedSuggestionsToBookmarkCollection:]
+ -[WebBookmarkCollection pebblePinnedSuggestionsFolder]
+ -[WebBookmarkCollection pebblePinnedSuggestions]
+ -[WebBookmarkReadonlyCollection enumerateBookmarks:andReadingListItems:andPinnedSuggestions:matchingString:usingBlock:]
+ -[WebBookmarkReadonlyCollection isBookmarkPebblePinnedSuggestion:]
+ -[WebBookmarkTabCollection _localTabGroupWithUUID:]
+ GCC_except_table136
+ GCC_except_table224
+ GCC_except_table235
+ GCC_except_table236
+ GCC_except_table246
+ GCC_except_table249
+ GCC_except_table265
+ GCC_except_table276
+ GCC_except_table278
+ GCC_except_table288
+ GCC_except_table304
+ GCC_except_table314
+ GCC_except_table315
+ GCC_except_table322
+ GCC_except_table327
+ GCC_except_table330
+ GCC_except_table331
+ GCC_except_table333
+ GCC_except_table339
+ GCC_except_table345
+ GCC_except_table350
+ GCC_except_table363
+ GCC_except_table374
+ GCC_except_table379
+ GCC_except_table381
+ GCC_except_table386
+ GCC_except_table387
+ GCC_except_table390
+ GCC_except_table395
+ GCC_except_table410
+ GCC_except_table415
+ GCC_except_table424
+ GCC_except_table427
+ GCC_except_table428
+ GCC_except_table429
+ GCC_except_table430
+ GCC_except_table431
+ GCC_except_table432
+ GCC_except_table436
+ GCC_except_table443
+ GCC_except_table447
+ GCC_except_table448
+ GCC_except_table449
+ GCC_except_table450
+ GCC_except_table451
+ GCC_except_table454
+ GCC_except_table467
+ GCC_except_table471
+ GCC_except_table472
+ GCC_except_table473
+ GCC_except_table476
+ GCC_except_table478
+ GCC_except_table479
+ GCC_except_table485
+ GCC_except_table501
+ GCC_except_table503
+ GCC_except_table504
+ GCC_except_table508
+ GCC_except_table519
+ GCC_except_table520
+ GCC_except_table523
+ GCC_except_table524
+ GCC_except_table525
+ GCC_except_table526
+ GCC_except_table527
+ GCC_except_table541
+ GCC_except_table550
+ GCC_except_table563
+ GCC_except_table564
+ GCC_except_table565
+ GCC_except_table576
+ GCC_except_table579
+ GCC_except_table594
+ GCC_except_table595
+ GCC_except_table596
+ GCC_except_table597
+ GCC_except_table598
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table602
+ GCC_except_table603
+ GCC_except_table610
+ GCC_except_table617
+ GCC_except_table618
+ GCC_except_table619
+ _BookmarksPebblePinnedSuggestionsSpecialID
+ _CKBAFolderTypeForBookmark
+ _OBJC_IVAR_$_WebBookmarkCollection._didRequestDatabaseInterrupt
+ _WBBoundedTransactionLockWaitMilliseconds
+ _WBDatabaseBusyTimeoutMilliseconds
+ _WBSCloudBookmarkListRecordNamePinnedSuggestions
+ __ZN12WebBookmarks26BookmarkSQLReadTransactionC1EP7sqlite3PKNSt3__16atomicIbEE
+ __ZN12WebBookmarks26BookmarkSQLReadTransactionC2EP7sqlite3PKNSt3__16atomicIbEE
+ __ZN12WebBookmarks27BookmarkSQLWriteTransactionC1EP7sqlite3NS0_17ShouldWaitForLockEPKNSt3__16atomicIbEE
+ __ZN12WebBookmarks27BookmarkSQLWriteTransactionC2EP7sqlite3NS0_17ShouldWaitForLockEPKNSt3__16atomicIbEE
+ ___111-[WebBookmarkCollection _updateDatabaseIfNewerVersion:wasLaunchedForSyncStringKey:upgradeSelector:versionType:]_block_invoke_2
+ ___115-[WebBookmarkCollection _tryPerformDatabaseUpdatesWithApplyInMemoryChanges:secureDelete:shouldWaitForLock:updates:]_block_invoke
+ ___119-[WebBookmarkReadonlyCollection enumerateBookmarks:andReadingListItems:andPinnedSuggestions:matchingString:usingBlock:]_block_invoke
+ ___41-[WBTabCollection localTabGroupWithUUID:]_block_invoke
+ ___42-[WBTabCollection pebblePinnedSuggestions]_block_invoke
+ ___42-[WBTabCollection pebblePinnedSuggestions]_block_invoke_2
+ ___48-[WBTabCollection deletePebblePinnedSuggestions]_block_invoke
+ ___48-[WBTabCollection deletePebblePinnedSuggestions]_block_invoke_2
+ ___48-[WBTabCollection pebblePinnedSuggestionsFolder]_block_invoke
+ ___48-[WBTabCollection pebblePinnedSuggestionsFolder]_block_invoke_2
+ ___58-[WBTabCollection pebblePinnedSuggestionsFolderIDIfExists]_block_invoke
+ ___58-[WBTabCollection pebblePinnedSuggestionsFolderIDIfExists]_block_invoke_2
+ ___66-[WebBookmarkReadonlyCollection isBookmarkPebblePinnedSuggestion:]_block_invoke
+ ___70-[WBTabCollection migratePebblePinnedSuggestionsToBookmarkCollection:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e14_"NSArray"8?0ls32l8
+ ___block_descriptor_40_ea8_32s_e18_"WebBookmark"8?0ls32l8
+ ___block_descriptor_40_ea8_32s_e5_i8?0ls32l8
+ ___block_descriptor_59_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- -[WebBookmarkCollection enumerateBookmarks:andReadingListItems:matchingString:usingBlock:]
- -[WebBookmarkReadonlyCollection enumerateBookmarks:andReadingListItems:matchingString:usingBlock:]
- GCC_except_table111
- GCC_except_table113
- GCC_except_table183
- GCC_except_table22
- GCC_except_table229
- GCC_except_table233
- GCC_except_table234
- GCC_except_table238
- GCC_except_table250
- GCC_except_table255
- GCC_except_table260
- GCC_except_table267
- GCC_except_table268
- GCC_except_table292
- GCC_except_table293
- GCC_except_table312
- GCC_except_table324
- GCC_except_table328
- GCC_except_table335
- GCC_except_table337
- GCC_except_table340
- GCC_except_table341
- GCC_except_table342
- GCC_except_table343
- GCC_except_table349
- GCC_except_table355
- GCC_except_table360
- GCC_except_table391
- GCC_except_table393
- GCC_except_table394
- GCC_except_table397
- GCC_except_table399
- GCC_except_table400
- GCC_except_table405
- GCC_except_table406
- GCC_except_table420
- GCC_except_table425
- GCC_except_table434
- GCC_except_table437
- GCC_except_table438
- GCC_except_table439
- GCC_except_table440
- GCC_except_table441
- GCC_except_table446
- GCC_except_table457
- GCC_except_table458
- GCC_except_table459
- GCC_except_table460
- GCC_except_table461
- GCC_except_table462
- GCC_except_table463
- GCC_except_table464
- GCC_except_table477
- GCC_except_table482
- GCC_except_table483
- GCC_except_table486
- GCC_except_table488
- GCC_except_table489
- GCC_except_table491
- GCC_except_table495
- GCC_except_table511
- GCC_except_table513
- GCC_except_table514
- GCC_except_table518
- GCC_except_table529
- GCC_except_table530
- GCC_except_table533
- GCC_except_table534
- GCC_except_table535
- GCC_except_table536
- GCC_except_table537
- GCC_except_table560
- GCC_except_table571
- GCC_except_table574
- GCC_except_table575
- GCC_except_table583
- GCC_except_table586
- GCC_except_table589
- GCC_except_table607
- GCC_except_table608
- GCC_except_table609
- __ZN12WebBookmarks26BookmarkSQLReadTransactionC1EP7sqlite3
- __ZN12WebBookmarks26BookmarkSQLReadTransactionC2EP7sqlite3
- __ZN12WebBookmarks27BookmarkSQLWriteTransactionC1EP7sqlite3
- __ZN12WebBookmarks27BookmarkSQLWriteTransactionC2EP7sqlite3
- ___43-[WBTabGroupManager insertUnnamedTabGroup:]_block_invoke_3
- ___97-[WebBookmarkCollection performDatabaseUpdatesWithTransaction:applyInMemoryChanges:secureDelete:]_block_invoke
- ___98-[WebBookmarkReadonlyCollection enumerateBookmarks:andReadingListItems:matchingString:usingBlock:]_block_invoke
- ___block_descriptor_58_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
```
