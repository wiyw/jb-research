## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

```diff

-1976.0.100.0.0
-  __TEXT.__text: 0x1a30bc
-  __TEXT.__objc_methlist: 0x15ac4
-  __TEXT.__cstring: 0xbe6f
-  __TEXT.__const: 0x4820
-  __TEXT.__oslogstring: 0xefd8
-  __TEXT.__gcc_except_tab: 0x3978
+1976.2.2.0.0
+  __TEXT.__text: 0x1a44b8
+  __TEXT.__objc_methlist: 0x15bfc
+  __TEXT.__cstring: 0xbdbf
+  __TEXT.__const: 0x4870
+  __TEXT.__oslogstring: 0xf294
+  __TEXT.__gcc_except_tab: 0x397c
   __TEXT.__dlopen_cstrs: 0x400
   __TEXT.__ustring: 0x1a0
   __TEXT.__swift5_typeref: 0x1988
-  __TEXT.__swift5_reflstr: 0x1261
+  __TEXT.__swift5_reflstr: 0x1271
   __TEXT.__swift5_assocty: 0x210
   __TEXT.__constg_swiftt: 0x1300
   __TEXT.__swift5_fieldmd: 0x11c8

   __TEXT.__swift_as_ret: 0xec
   __TEXT.__swift_as_cont: 0x1a8
   __TEXT.__swift5_mpenum: 0x60
-  __TEXT.__unwind_info: 0x6780
-  __TEXT.__eh_frame: 0x2618
+  __TEXT.__unwind_info: 0x67e8
+  __TEXT.__eh_frame: 0x2614
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x48e0
-  __DATA_CONST.__objc_classlist: 0x7b0
+  __DATA_CONST.__const: 0x4908
+  __DATA_CONST.__objc_classlist: 0x7b8
   __DATA_CONST.__objc_catlist: 0xa0
-  __DATA_CONST.__objc_protolist: 0x250
+  __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xae98
+  __DATA_CONST.__objc_selrefs: 0xaf28
   __DATA_CONST.__objc_protorefs: 0x70
-  __DATA_CONST.__objc_superrefs: 0x530
+  __DATA_CONST.__objc_superrefs: 0x538
   __DATA_CONST.__objc_arraydata: 0x5d8
-  __DATA_CONST.__got: 0x1a50
-  __AUTH_CONST.__const: 0x4500
+  __DATA_CONST.__got: 0x1a58
+  __AUTH_CONST.__const: 0x4520
   __AUTH_CONST.__cfstring: 0x9ec0
-  __AUTH_CONST.__objc_const: 0x18628
+  __AUTH_CONST.__objc_const: 0x187d8
   __AUTH_CONST.__objc_intobj: 0x6d8
   __AUTH_CONST.__objc_arrayobj: 0x1f8
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_doubleobj: 0x100
-  __AUTH_CONST.__auth_got: 0x1428
-  __AUTH_CONST.__auth_ptr: 0x598
-  __AUTH.__objc_data: 0x34d0
-  __AUTH.__data: 0xf08
-  __DATA.__objc_ivar: 0xd7c
-  __DATA.__data: 0x2890
-  __DATA.__bss: 0x4770
+  __AUTH_CONST.__auth_got: 0x1438
+  __AUTH_CONST.__auth_ptr: 0x5a8
+  __AUTH.__objc_data: 0x1db8
+  __AUTH.__data: 0x610
+  __DATA.__objc_ivar: 0xd88
+  __DATA.__data: 0x28f0
+  __DATA.__bss: 0x4760
   __DATA.__common: 0x68
-  __DATA_DIRTY.__objc_data: 0x1bd0
-  __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x588
+  __DATA_DIRTY.__objc_data: 0x3338
+  __DATA_DIRTY.__data: 0x910
+  __DATA_DIRTY.__bss: 0x5a0
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10688
-  Symbols:   13255
+  Functions: 10717
+  Symbols:   13300
   CStrings:  0
 
Symbols:
+ +[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]
+ +[EKAttachment _volumeIdentifierForURL:]
+ +[EKAutocompletePendingSearch _shouldReturnResultForEvent:considerReadonlyEvents:enforceRecencyCutoff:ignoreScheduledEvents:initialEvent:]
+ +[EKAutocompleteSearch pasteboardResultsFromProvider:ignoreScheduledEvents:]
+ +[EKEventStore _isSuggestedEvent:confirmed:uniqueKey:]
+ +[EKEventSuggestionGenerator eventSuggestionsFromPasteboardItemProvider:referenceDate:]
+ -[EKAttachment _mirroredTemporaryURLForExpandedArchiveContentsOfArchiveAtURL:]
+ -[EKAttachment localURLExpandingArchiveIfNeeded]
+ -[EKEventStore _suggestionsService]
+ -[EKEventStore gatherConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:fromInsertedObjects:deletedObjects:]
+ -[EKEventStore lastDatabaseCommitTimestamp]
+ -[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]
+ -[EKEventStore realAuthorizationStatusForEntityType:]
+ -[EKEventStore setSuggestionsServiceOverride:]
+ -[EKEventStore shouldNotifySuggestionsOfChangesToSuggestedEvents]
+ -[EKEventStore suggestionsServiceOverride]
+ -[EKFrozenReminderObject shouldCheckExistenceBeforeRefresh]
+ -[EKPersistentObject _shouldAllowUnloadingProperties]
+ -[EKPersistentObject shouldCheckExistenceBeforeRefresh]
+ -[EKWeakLinkedSuggestionsService .cxx_destruct]
+ -[EKWeakLinkedSuggestionsService confirmEventByRecordId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService deleteEventByRecordId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService eventFromUniqueId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService init]
+ -[EKWeakLinkedSuggestionsService rejectEventByRecordId:withCompletion:]
+ GCC_except_table100
+ GCC_except_table109
+ GCC_except_table112
+ GCC_except_table118
+ GCC_except_table123
+ GCC_except_table130
+ GCC_except_table134
+ GCC_except_table138
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table162
+ GCC_except_table166
+ GCC_except_table175
+ GCC_except_table177
+ GCC_except_table184
+ GCC_except_table190
+ GCC_except_table193
+ GCC_except_table196
+ GCC_except_table231
+ GCC_except_table235
+ GCC_except_table237
+ GCC_except_table240
+ GCC_except_table243
+ GCC_except_table246
+ GCC_except_table248
+ GCC_except_table250
+ GCC_except_table254
+ GCC_except_table265
+ GCC_except_table267
+ GCC_except_table269
+ GCC_except_table277
+ GCC_except_table280
+ GCC_except_table286
+ GCC_except_table289
+ GCC_except_table322
+ GCC_except_table324
+ GCC_except_table327
+ GCC_except_table355
+ GCC_except_table357
+ GCC_except_table359
+ GCC_except_table361
+ GCC_except_table363
+ GCC_except_table365
+ GCC_except_table370
+ GCC_except_table378
+ GCC_except_table382
+ GCC_except_table384
+ GCC_except_table391
+ GCC_except_table394
+ GCC_except_table402
+ GCC_except_table414
+ GCC_except_table418
+ GCC_except_table423
+ GCC_except_table439
+ GCC_except_table444
+ GCC_except_table450
+ GCC_except_table460
+ GCC_except_table467
+ GCC_except_table470
+ GCC_except_table477
+ GCC_except_table503
+ GCC_except_table505
+ GCC_except_table537
+ GCC_except_table551
+ GCC_except_table556
+ GCC_except_table574
+ GCC_except_table591
+ GCC_except_table595
+ GCC_except_table610
+ GCC_except_table63
+ GCC_except_table642
+ GCC_except_table644
+ GCC_except_table646
+ GCC_except_table67
+ GCC_except_table688
+ GCC_except_table692
+ GCC_except_table694
+ GCC_except_table710
+ GCC_except_table712
+ GCC_except_table720
+ GCC_except_table727
+ GCC_except_table73
+ GCC_except_table734
+ GCC_except_table742
+ GCC_except_table746
+ GCC_except_table748
+ GCC_except_table750
+ GCC_except_table756
+ GCC_except_table758
+ GCC_except_table760
+ GCC_except_table769
+ GCC_except_table773
+ GCC_except_table88
+ GCC_except_table91
+ _NSURLVolumeIdentifierKey
+ _OBJC_CLASS_$_EKWeakLinkedSuggestionsService
+ _OBJC_IVAR_$_EKEventStore._lastDatabaseCommitTimestamp
+ _OBJC_IVAR_$_EKEventStore._suggestionsServiceOverride
+ _OBJC_IVAR_$_EKWeakLinkedSuggestionsService._service
+ _OBJC_METACLASS_$_EKWeakLinkedSuggestionsService
+ _OUTLINED_FUNCTION_35
+ _UnzipArchive
+ __OBJC_$_INSTANCE_METHODS_EKWeakLinkedSuggestionsService
+ __OBJC_$_INSTANCE_VARIABLES_EKWeakLinkedSuggestionsService
+ __OBJC_$_PROP_LIST_EKWeakLinkedSuggestionsService
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EKSuggestionsServiceEventsProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EKSuggestionsServiceEventsProtocol
+ __OBJC_$_PROTOCOL_REFS_EKSuggestionsServiceEventsProtocol
+ __OBJC_CLASS_PROTOCOLS_$_EKWeakLinkedSuggestionsService
+ __OBJC_CLASS_RO_$_EKWeakLinkedSuggestionsService
+ __OBJC_LABEL_PROTOCOL_$_EKSuggestionsServiceEventsProtocol
+ __OBJC_METACLASS_RO_$_EKWeakLinkedSuggestionsService
+ __OBJC_PROTOCOL_$_EKSuggestionsServiceEventsProtocol
+ ___43-[EKEventStore lastDatabaseCommitTimestamp]_block_invoke
+ ___61+[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]_block_invoke
+ ___95-[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]_block_invoke
+ ___95-[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]_block_invoke_2
+ ___block_descriptor_120_e8_32s40s48s56r64r72r80r88r96r104r112r_e124_v56?0i8"NSDictionary"12"NSDictionary"20"NSDictionary"28"CADInMemoryChangeTimestamp"36"CADInMemoryChangeTimestamp"44B52lr56l8r64l8s32l8s40l8r72l8r80l8r88l8r96l8r104l8r112l8s48l8
+ ___block_descriptor_40_e8_32s_e61_q24?0"CalSpotlightQueryResult"8"CalSpotlightQueryResult"16ls32l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e23_v32?0"NSDate"8Q16^B24ls32l8r48l8r56l8s40l8r64l8
+ __expandedArchiveTemporaryDirectoryRootForURL:.cachedRootsByVolume
+ __expandedArchiveTemporaryDirectoryRootForURL:.onceToken
- +[EKEventStore _isConfirmedSuggestedEvent:uniqueKey:]
- -[EKEventStore _SGSuggestionsServiceClass]
- -[EKEventStore confirmSuggestedEvent:]
- -[EKEventStore lastDatabaseTimestamp]
- GCC_except_table107
- GCC_except_table110
- GCC_except_table116
- GCC_except_table119
- GCC_except_table127
- GCC_except_table133
- GCC_except_table139
- GCC_except_table142
- GCC_except_table161
- GCC_except_table165
- GCC_except_table176
- GCC_except_table183
- GCC_except_table189
- GCC_except_table192
- GCC_except_table230
- GCC_except_table234
- GCC_except_table236
- GCC_except_table239
- GCC_except_table242
- GCC_except_table245
- GCC_except_table247
- GCC_except_table249
- GCC_except_table253
- GCC_except_table264
- GCC_except_table266
- GCC_except_table268
- GCC_except_table276
- GCC_except_table279
- GCC_except_table285
- GCC_except_table288
- GCC_except_table321
- GCC_except_table323
- GCC_except_table326
- GCC_except_table354
- GCC_except_table356
- GCC_except_table358
- GCC_except_table360
- GCC_except_table362
- GCC_except_table364
- GCC_except_table369
- GCC_except_table377
- GCC_except_table381
- GCC_except_table383
- GCC_except_table390
- GCC_except_table393
- GCC_except_table396
- GCC_except_table401
- GCC_except_table413
- GCC_except_table417
- GCC_except_table421
- GCC_except_table443
- GCC_except_table452
- GCC_except_table454
- GCC_except_table468
- GCC_except_table478
- GCC_except_table481
- GCC_except_table507
- GCC_except_table509
- GCC_except_table541
- GCC_except_table555
- GCC_except_table562
- GCC_except_table571
- GCC_except_table585
- GCC_except_table592
- GCC_except_table607
- GCC_except_table62
- GCC_except_table639
- GCC_except_table641
- GCC_except_table643
- GCC_except_table685
- GCC_except_table689
- GCC_except_table691
- GCC_except_table707
- GCC_except_table709
- GCC_except_table714
- GCC_except_table72
- GCC_except_table724
- GCC_except_table731
- GCC_except_table739
- GCC_except_table74
- GCC_except_table743
- GCC_except_table745
- GCC_except_table747
- GCC_except_table753
- GCC_except_table755
- GCC_except_table757
- GCC_except_table766
- GCC_except_table770
- GCC_except_table87
- GCC_except_table90
- GCC_except_table97
- ___37-[EKEventStore deleteSuggestedEvent:]_block_invoke
- ___37-[EKEventStore deleteSuggestedEvent:]_block_invoke_2
- ___37-[EKEventStore lastDatabaseTimestamp]_block_invoke
- ___38-[EKEventStore confirmSuggestedEvent:]_block_invoke
- ___38-[EKEventStore confirmSuggestedEvent:]_block_invoke_2
- ___block_descriptor_112_e8_32s40s48r56r64r72r80r88r96r104r_e93_v48?0i8"NSDictionary"12"NSDictionary"20"NSDictionary"28"CADInMemoryChangeTimestamp"36B44lr48l8r56l8s32l8s40l8r64l8r72l8r80l8r88l8r96l8r104l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e23_v32?0"NSDate"8Q16^B24ls32l8s40l8r56l8r64l8s48l8r72l8
```
