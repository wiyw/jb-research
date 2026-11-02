## TextInputCore

> `/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore`

```diff

-3567.0.0.0.0
-  __TEXT.__text: 0x222810
+3568.1.8.0.0
+  __TEXT.__text: 0x21f140
   __TEXT.__init_offsets: 0xc0
-  __TEXT.__objc_methlist: 0x10af0
+  __TEXT.__objc_methlist: 0x10618
   __TEXT.__dlopen_cstrs: 0x781
   __TEXT.__const: 0x2e40
-  __TEXT.__cstring: 0x1ca14
-  __TEXT.__oslogstring: 0x4479
-  __TEXT.__ustring: 0x7d8
-  __TEXT.__unwind_info: 0x6600
+  __TEXT.__cstring: 0x1c8d8
+  __TEXT.__oslogstring: 0x42db
+  __TEXT.__ustring: 0x7e0
+  __TEXT.__unwind_info: 0x64f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4f30
-  __DATA_CONST.__objc_classlist: 0x858
+  __DATA_CONST.__const: 0x4ea8
+  __DATA_CONST.__objc_classlist: 0x808
   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa088
-  __DATA_CONST.__objc_superrefs: 0x728
+  __DATA_CONST.__objc_selrefs: 0x9ec0
+  __DATA_CONST.__objc_superrefs: 0x6d8
   __DATA_CONST.__objc_arraydata: 0x10a8
-  __DATA_CONST.__got: 0x18b8
-  __AUTH_CONST.__const: 0x8870
-  __AUTH_CONST.__cfstring: 0x13e80
-  __AUTH_CONST.__objc_const: 0x1a680
+  __DATA_CONST.__got: 0x1890
+  __AUTH_CONST.__const: 0x8878
+  __AUTH_CONST.__cfstring: 0x13dc0
+  __AUTH_CONST.__objc_const: 0x19c88
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x3c0
-  __AUTH_CONST.__objc_intobj: 0x6c0
+  __AUTH_CONST.__objc_intobj: 0x690
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1af0
+  __AUTH_CONST.__auth_got: 0x1ac8
   __AUTH_CONST.__auth_ptr: 0x0
   __AUTH.__objc_data: 0x2080
   __AUTH.__data: 0x18
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x20
-  __DATA.__objc_ivar: 0x12c8
+  __DATA.__objc_ivar: 0x1288
   __DATA.__data: 0x22a8
-  __DATA.__bss: 0x1ee0
+  __DATA.__bss: 0x1e20
   __DATA.__common: 0x408
-  __DATA_DIRTY.__objc_data: 0x32f0
+  __DATA_DIRTY.__objc_data: 0x2fd0
   __DATA_DIRTY.__data: 0xb0
-  __DATA_DIRTY.__bss: 0xc50
+  __DATA_DIRTY.__bss: 0xcf0
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libmecabra.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 10539
-  Symbols:   17431
+  Functions: 10446
+  Symbols:   17248
   CStrings:  0
 
Symbols:
+ +[TIChineseExtras stringContainsOffensiveCharacter:]
+ +[TILaunchServicesLookup enumerateInstalledApplicationsWithPreferredLocalizations:block:]
+ +[TILaunchServicesLookup localizedNameForBundleIdentifier:preferredLocalizations:]
+ +[TITextCheckerExemptions(TestingSupport) _resetForTesting]
+ -[TIKeyboardInputManagerLoader releaseAllInputManagersAndLanguageModelResources]
+ -[TIMecabraEnvironment leftDocumentContextForCandidates]
+ -[TIMecabraEnvironmentContextWrapper setStringContext:]
+ -[TIMecabraEnvironmentContextWrapper stringContextIsEmpty]
+ -[TIMecabraEnvironmentContextWrapper stringContext]
+ -[TITextCheckerExemptionsImpl _resetForTesting]
+ -[TITextCheckerExemptionsImpl applyContactDeltaChanges:]
+ -[TITextCheckerExemptionsImpl rebuildAddressBookTokensFromSnapshot:]
+ _CFEqual
+ _CFNotificationCenterGetDistributedCenter
+ _CFNotificationCenterRemoveEveryObserver
+ _MecabraContextSetStringContext
+ _OBJC_IVAR_$_TIMecabraEnvironmentContextWrapper._stringContext
+ _OBJC_IVAR_$_TITextCheckerExemptionsImpl._contactDeltaObserver
+ _TIInputManagerServerOSLogFacility
+ _TIInputManagerServerOSLogFacility.logFacility
+ _TIInputManagerServerOSLogFacility.onceToken
+ __OBJC_$_CLASS_METHODS_TITextCheckerExemptions(TestingSupport)
+ __ZL17apply_token_deltaP10_LXLexiconRKNSt3__16vectorIN2KB6StringENS1_9allocatorIS4_EEEEi
+ __ZL20nameTokensForContactP10_ICContact
+ __ZL28filtered_tokens_for_app_nameP8NSStringRKN2KB16StaticDictionaryE
+ __ZL34preferred_localizations_for_localeRKN2KB6StringE
+ __ZN17AppTrieLoaderImpl22app_name_loading_queueEv
+ __ZN17AppTrieLoaderImpl33distributed_notification_callbackEP22__CFNotificationCenterPvPK10__CFStringPKvPK14__CFDictionary
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB6StringENS_6vectorIS3_NS_9allocatorIS3_EEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE17__deallocate_nodeB9fon220106EPNS_11__hash_nodeIS8_PvEE
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB6StringENS_6vectorIS3_NS_9allocatorIS3_EEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE4findIS3_EENS_15__hash_iteratorIPNS_11__hash_nodeIS8_PvEEEERKT_
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB6StringENS_6vectorIS3_NS_9allocatorIS3_EEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE8__rehashILb1EEEvm
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB6StringENS_6vectorIS3_NS_9allocatorIS3_EEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEED2Ev
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB6StringENS_6vectorIS3_NS_9allocatorIS3_EEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S7_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SC_SG_SE_EENS5_ISC_EEE16__emplace_uniqueB9fon220106IJRKNS_21piecewise_construct_tENS_5tupleIJOS3_EEENSQ_IJEEEEEENSA_INS_15__hash_iteratorIPNS_11__hash_nodeIS8_PvEEEEbEEDpOT_ENKUlRSB_SP_OSS_OST_E_clES14_SP_S15_S16_
+ ___51-[TITextCheckerExemptionsImpl addObserverAssertion]_block_invoke_2
+ ___52+[TIChineseExtras stringContainsOffensiveCharacter:]_block_invoke
+ ___TIInputManagerServerOSLogFacility_block_invoke
+ ____ZN17AppTrieLoaderImpl20perform_initial_loadEv_block_invoke
+ ____ZN17AppTrieLoaderImpl33distributed_notification_callbackEP22__CFNotificationCenterPvPK10__CFStringPKvPK14__CFDictionary_block_invoke
+ ____ZZN17AppTrieLoaderImpl20perform_initial_loadEvENK3$_0clEv_block_invoke
+ ____ZZZN17AppTrieLoaderImpl20perform_initial_loadEvENK3$_0clEvENKUlvE_clEv_block_invoke
+ ___block_descriptor_40_a8_32s_e34_v24?0"NSArray"8"NSDictionary"16ls32l8
+ ___block_descriptor_48_8_32r_e5_v8?0lr32l8
+ ___block_descriptor_56_a8_32c45_ZTSNSt3__110shared_ptrI17AppTrieLoaderImplEE48c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE_e35_v32?0"NSString"8"NSString"16^B24l
+ ___block_descriptor_56_a8_32c55_ZTSKZN17AppTrieLoaderImpl20perform_initial_loadEvE3$_0_e5_v8?0l
+ ___block_descriptor_56_a8_32c68_ZTSKZZN17AppTrieLoaderImpl20perform_initial_loadEvENK3$_0clEvEUlvE__e5_v8?0l
+ ___block_descriptor_57_a8_32s40c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE_e5_v8?0l
+ ___copy_helper_block_a8_32c45_ZTSNSt3__110shared_ptrI17AppTrieLoaderImplEE48c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE
+ ___copy_helper_block_a8_32c55_ZTSKZN17AppTrieLoaderImpl20perform_initial_loadEvE3$_0
+ ___copy_helper_block_a8_32c68_ZTSKZZN17AppTrieLoaderImpl20perform_initial_loadEvENK3$_0clEvEUlvE_
+ ___copy_helper_block_a8_40c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE
+ ___destroy_helper_block_a8_32c45_ZTSNSt3__110shared_ptrI17AppTrieLoaderImplEE48c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE
+ ___destroy_helper_block_a8_32c55_ZTSKZN17AppTrieLoaderImpl20perform_initial_loadEvE3$_0
+ ___destroy_helper_block_a8_32c68_ZTSKZZN17AppTrieLoaderImpl20perform_initial_loadEvENK3$_0clEvEUlvE_
+ ___destroy_helper_block_a8_40c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE
+ ___getLSApplicationRecordClass_block_invoke
+ _getLSApplicationRecordClass
+ _getLSApplicationRecordClass.softClass
+ _malloc_zone_pressure_relief
+ _stringContainsOffensiveCharacter:.offensiveCharacterSet
+ _stringContainsOffensiveCharacter:.onceToken
- +[HCBurstTrie burstTrieFromFile:]
- +[HCHuffmanCoder characterCoderForLocale:]
- +[HCHuffmanCoder coderFromBurstTrieFile:indexTableFile:]
- +[HCHuffmanCoder coderMatchingName:locale:]
- +[HCHuffmanCoder wordCoderForLocale:]
- +[HCIndexTable indexTableFromFile:]
- +[TIDPNgramRecorder enumerateNgramsFromSession:n:usingBlock:]
- +[TIDPWordRecord word:atPosition:coder:]
- +[TILaunchServicesLookup enumerateInstalledApplicationNames:]
- +[TILaunchServicesLookup lookupAppNames]
- +[TILaunchServicesLookup sharedInstance]
- -[HCBurstTrie _createUnderlyingBurstTrie]
- -[HCBurstTrie burstTrie]
- -[HCBurstTrie count]
- -[HCBurstTrie dealloc]
- -[HCBurstTrie init]
- -[HCBurstTrie keysAdded]
- -[HCBurstTrie payloadForKey:]
- -[HCBurstTrie setBurstTrie:]
- -[HCBurstTrie writeToFile:]
- -[HCHuffmanCoder .cxx_destruct]
- -[HCHuffmanCoder burstTrie]
- -[HCHuffmanCoder codeForKey:]
- -[HCHuffmanCoder count]
- -[HCHuffmanCoder indexTable]
- -[HCHuffmanCoder initWithBurstTrie:indexTable:]
- -[HCHuffmanCoder init]
- -[HCHuffmanCoder setBurstTrie:]
- -[HCHuffmanCoder setIndexTable:]
- -[HCHuffmanCoder stringCodeForKey:]
- -[HCHuffmanCoder versionUUID]
- -[HCIndexTable .cxx_construct]
- -[HCIndexTable .cxx_destruct]
- -[HCIndexTable codeAtIndex:]
- -[HCIndexTable count]
- -[HCIndexTable fileHeader]
- -[HCIndexTable huffmanCodesMemoryMappedData]
- -[HCIndexTable huffmanCodes]
- -[HCIndexTable initWithHuffmanCodesMemoryMappedData:]
- -[HCIndexTable init]
- -[HCIndexTable isValid]
- -[HCIndexTable versionUUID]
- -[HCIndexTable writeToFile:]
- -[TIDPNamedEntityTokenRecorder delegate]
- -[TIDPNamedEntityTokenRecorder recordingKey]
- -[TIDPNamedEntityTokenRecorder records]
- -[TIDPNamedEntityTokenRecorder report]
- -[TIDPNgramRecorder _normalizedWordEntryStringForWordEntry:]
- -[TIDPNgramRecorder delegate]
- -[TIDPNgramRecorder initWithTypingSession:aligned:n:shouldDonateNgramSampleRandomly:]
- -[TIDPNgramRecorder randomRecordsLimitedByCount:]
- -[TIDPNgramRecorder randomRecords]
- -[TIDPNgramRecorder recordingKey]
- -[TIDPNgramRecorder records]
- -[TIDPNgramRecorder report]
- -[TIDPNgramRecorder setShouldDonateNgramSampleRandomly:]
- -[TIDPNgramRecorder shouldDonateNgramSampleRandomly]
- -[TIDPNgramRecorderCascading initWithTypingSession:aligned:n:]
- -[TIDPNgramRecorderCascading n]
- -[TIDPNgramRecorderCascading report]
- -[TIDPNgramRecorderCascading setN:]
- -[TIDPNgramRecorderRandom initWithTypingSession:aligned:n:]
- -[TIDPNgramRecorderRandom report]
- -[TIDPNgramWordEntryPair .cxx_destruct]
- -[TIDPNgramWordEntryPair initWithWordString:]
- -[TIDPNgramWordEntryPair initWithWordString:wordEntryAligned:]
- -[TIDPNgramWordEntryPair isStandaloneString]
- -[TIDPNgramWordEntryPair setWordEntryAligned:]
- -[TIDPNgramWordEntryPair setWordString:]
- -[TIDPNgramWordEntryPair wordEntryAligned]
- -[TIDPNgramWordEntryPair wordString]
- -[TIDPRecorder _prepareCharacterCoderMatchingSession]
- -[TIDPRecorder _prepareWordCoderMatchingSession]
- -[TIDPRecorder characterCoder]
- -[TIDPRecorder characterExplodedRecords]
- -[TIDPRecorder wordCoder]
- -[TIDPUnknownTokenRecorder delegate]
- -[TIDPUnknownTokenRecorder recordingKey]
- -[TIDPUnknownTokenRecorder records]
- -[TIDPUnknownTokenRecorder report]
- -[TIDPUnknownTokenWithContextRecorder recordingKey]
- -[TIDPUnknownTokenWithContextRecorder records]
- -[TIDPWordRecord codedWordAsString]
- -[TIDPWordRecord codedWord]
- -[TIDPWordRecord coderVersion]
- -[TIDPWordRecord coder]
- -[TIDPWordRecord setCoder:]
- -[TIDPWordRecord toDPWordRecord]
- -[TILaunchServicesLookup .cxx_destruct]
- -[TILaunchServicesLookup appNames]
- -[TILaunchServicesLookup cacheNames:]
- -[TILaunchServicesLookup cache]
- -[TILaunchServicesLookup dealloc]
- -[TILaunchServicesLookup enumerateAppNames:]
- -[TILaunchServicesLookup handleMemoryPressureLevel:excessMemoryInBytes:]
- -[TILaunchServicesLookup init]
- -[TILaunchServicesLookup keyboardActivityDidTransition:]
- -[TILaunchServicesLookup lastCacheUpdate]
- -[TILaunchServicesLookup resetCache]
- -[TILaunchServicesLookup setCache:]
- -[TILaunchServicesLookup setLastCacheUpdate:]
- -[TILaunchServicesLookup tryCache]
- -[TIMecabraEnvironmentContextWrapper contextString:forRightContext:]
- _CFBurstTrieContains
- _CFBurstTrieCreate
- _CFBurstTrieCreateFromMapBytes
- _CFBurstTrieGetCount
- _CFBurstTrieRelease
- _CFBurstTrieSerializeWithFileDescriptor
- _CoreServicesLibrary
- _MecabraGetLengthForContextString
- _OBJC_CLASS_$_HCBurstTrie
- _OBJC_CLASS_$_HCHuffmanCoder
- _OBJC_CLASS_$_HCIndexTable
- _OBJC_CLASS_$_TIDPNamedEntityTokenRecorder
- _OBJC_CLASS_$_TIDPNgramRecorder
- _OBJC_CLASS_$_TIDPNgramRecorderCascading
- _OBJC_CLASS_$_TIDPNgramRecorderRandom
- _OBJC_CLASS_$_TIDPNgramWordEntryPair
- _OBJC_CLASS_$_TIDPUnknownTokenRecorder
- _OBJC_CLASS_$_TIDPUnknownTokenWithContextRecorder
- _OBJC_CLASS_$__DPNumericDataRecorder
- _OBJC_CLASS_$__DPWordRecord
- _OBJC_CLASS_$__DPWordRecorder
- _OBJC_IVAR_$_HCBurstTrie._burstTrie
- _OBJC_IVAR_$_HCBurstTrie._keysAdded
- _OBJC_IVAR_$_HCHuffmanCoder._burstTrie
- _OBJC_IVAR_$_HCHuffmanCoder._indexTable
- _OBJC_IVAR_$_HCIndexTable._fileHeader
- _OBJC_IVAR_$_HCIndexTable._huffmanCodesMemoryMappedData
- _OBJC_IVAR_$_HCIndexTable._mutableHuffmanCodes
- _OBJC_IVAR_$_HCIndexTable._versionUUID
- _OBJC_IVAR_$_TIDPNgramRecorder._shouldDonateNgramSampleRandomly
- _OBJC_IVAR_$_TIDPNgramRecorderCascading._n
- _OBJC_IVAR_$_TIDPNgramWordEntryPair._wordEntryAligned
- _OBJC_IVAR_$_TIDPNgramWordEntryPair._wordString
- _OBJC_IVAR_$_TIDPRecorder._characterCoder
- _OBJC_IVAR_$_TIDPRecorder._wordCoder
- _OBJC_IVAR_$_TIDPWordRecord._coder
- _OBJC_IVAR_$_TILaunchServicesLookup._cache
- _OBJC_IVAR_$_TILaunchServicesLookup._lastCacheUpdate
- _OBJC_IVAR_$_TITextCheckerExemptionsImpl._contactObserver
- _OBJC_METACLASS_$_HCBurstTrie
- _OBJC_METACLASS_$_HCHuffmanCoder
- _OBJC_METACLASS_$_HCIndexTable
- _OBJC_METACLASS_$_TIDPNamedEntityTokenRecorder
- _OBJC_METACLASS_$_TIDPNgramRecorder
- _OBJC_METACLASS_$_TIDPNgramRecorderCascading
- _OBJC_METACLASS_$_TIDPNgramRecorderRandom
- _OBJC_METACLASS_$_TIDPNgramWordEntryPair
- _OBJC_METACLASS_$_TIDPUnknownTokenRecorder
- _OBJC_METACLASS_$_TIDPUnknownTokenWithContextRecorder
- __OBJC_$_CLASS_METHODS_HCBurstTrie
- __OBJC_$_CLASS_METHODS_HCHuffmanCoder
- __OBJC_$_CLASS_METHODS_HCIndexTable
- __OBJC_$_CLASS_METHODS_TIDPNgramRecorder
- __OBJC_$_INSTANCE_METHODS_HCBurstTrie
- __OBJC_$_INSTANCE_METHODS_HCHuffmanCoder
- __OBJC_$_INSTANCE_METHODS_HCIndexTable
- __OBJC_$_INSTANCE_METHODS_TIDPNamedEntityTokenRecorder
- __OBJC_$_INSTANCE_METHODS_TIDPNgramRecorder
- __OBJC_$_INSTANCE_METHODS_TIDPNgramRecorderCascading
- __OBJC_$_INSTANCE_METHODS_TIDPNgramRecorderRandom
- __OBJC_$_INSTANCE_METHODS_TIDPNgramWordEntryPair
- __OBJC_$_INSTANCE_METHODS_TIDPUnknownTokenRecorder
- __OBJC_$_INSTANCE_METHODS_TIDPUnknownTokenWithContextRecorder
- __OBJC_$_INSTANCE_METHODS_TILaunchServicesLookup
- __OBJC_$_INSTANCE_VARIABLES_HCBurstTrie
- __OBJC_$_INSTANCE_VARIABLES_HCHuffmanCoder
- __OBJC_$_INSTANCE_VARIABLES_HCIndexTable
- __OBJC_$_INSTANCE_VARIABLES_TIDPNgramRecorder
- __OBJC_$_INSTANCE_VARIABLES_TIDPNgramRecorderCascading
- __OBJC_$_INSTANCE_VARIABLES_TIDPNgramWordEntryPair
- __OBJC_$_INSTANCE_VARIABLES_TILaunchServicesLookup
- __OBJC_$_PROP_LIST_HCBurstTrie
- __OBJC_$_PROP_LIST_HCHuffmanCoder
- __OBJC_$_PROP_LIST_HCIndexTable
- __OBJC_$_PROP_LIST_TIDPNgramRecorder
- __OBJC_$_PROP_LIST_TIDPNgramRecorderCascading
- __OBJC_$_PROP_LIST_TIDPNgramWordEntryPair
- __OBJC_$_PROP_LIST_TILaunchServicesLookup
- __OBJC_CLASS_PROTOCOLS_$_TILaunchServicesLookup
- __OBJC_CLASS_RO_$_HCBurstTrie
- __OBJC_CLASS_RO_$_HCHuffmanCoder
- __OBJC_CLASS_RO_$_HCIndexTable
- __OBJC_CLASS_RO_$_TIDPNamedEntityTokenRecorder
- __OBJC_CLASS_RO_$_TIDPNgramRecorder
- __OBJC_CLASS_RO_$_TIDPNgramRecorderCascading
- __OBJC_CLASS_RO_$_TIDPNgramRecorderRandom
- __OBJC_CLASS_RO_$_TIDPNgramWordEntryPair
- __OBJC_CLASS_RO_$_TIDPUnknownTokenRecorder
- __OBJC_CLASS_RO_$_TIDPUnknownTokenWithContextRecorder
- __OBJC_METACLASS_RO_$_HCBurstTrie
- __OBJC_METACLASS_RO_$_HCHuffmanCoder
- __OBJC_METACLASS_RO_$_HCIndexTable
- __OBJC_METACLASS_RO_$_TIDPNamedEntityTokenRecorder
- __OBJC_METACLASS_RO_$_TIDPNgramRecorder
- __OBJC_METACLASS_RO_$_TIDPNgramRecorderCascading
- __OBJC_METACLASS_RO_$_TIDPNgramRecorderRandom
- __OBJC_METACLASS_RO_$_TIDPNgramWordEntryPair
- __OBJC_METACLASS_RO_$_TIDPUnknownTokenRecorder
- __OBJC_METACLASS_RO_$_TIDPUnknownTokenWithContextRecorder
- __ZGVZ23-[HCIndexTable isValid]E12staticHeader
- __ZL21libmecabraLibraryCorePPc
- __ZL42getMecabraContextSetStringContextSymbolLocv
- __ZZ23-[HCIndexTable isValid]E12staticHeader
- __ZZL21libmecabraLibraryCorePPcE16frameworkLibrary
- __ZZL42getMecabraContextSetStringContextSymbolLocvE3ptr
- ___28-[TIDPNgramRecorder records]_block_invoke
- ___40+[TILaunchServicesLookup lookupAppNames]_block_invoke
- ___40+[TILaunchServicesLookup sharedInstance]_block_invoke
- ___40-[TIDPRecorder characterExplodedRecords]_block_invoke
- ___43+[HCHuffmanCoder coderMatchingName:locale:]_block_invoke
- ___46-[TIDPUnknownTokenWithContextRecorder records]_block_invoke
- ___46-[TIDPUnknownTokenWithContextRecorder records]_block_invoke_2
- ____ZL21libmecabraLibraryCorePPc_block_invoke
- ____ZL27background_append_app_namesN2KB10retain_ptrIP10_LXLexiconEERKNS_16StaticDictionaryE_block_invoke
- ____ZL42getMecabraContextSetStringContextSymbolLocv_block_invoke
- ____ZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1__block_invoke
- ____ZZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_ENK3$_0clEv_block_invoke
- ___block_descriptor_144_a8_32c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE48c17_ZTSKN2KB6StringE80c17_ZTSKN2KB6StringE112c17_ZTSKN2KB6StringE_e22_v16?0"NSDictionary"8l
- ___block_descriptor_152_a8_32c85_ZTSKZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_E3$_0_e5_v8?0l
- ___block_descriptor_152_a8_32c98_ZTSKZZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_ENK3$_0clEvEUlvE__e5_v8?0l
- ___block_descriptor_32_e35_B32?0"TIWordEntryAligned"8Q16^B24l
- ___block_descriptor_40_8_32r_e57_v44?0^{__CFURL=}8i16^{__CFLocale=}20^{__CFString=}28^B36lr32l8
- ___block_descriptor_40_8_32s_e27_v24?0"LSBundleProxy"8^B16ls32l8
- ___block_descriptor_48_8_32s40s_e21_v24?0"NSArray"8^B16ls32l8s40l8
- ___block_descriptor_48_a8_32c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE_e22_v24?0"NSString"8^B16l
- ___block_descriptor_48_a8_32r_e5_v8?0lr32l8
- ___copy_helper_block_a8_32c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE
- ___copy_helper_block_a8_32c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE48c17_ZTSKN2KB6StringE80c17_ZTSKN2KB6StringE112c17_ZTSKN2KB6StringE
- ___copy_helper_block_a8_32c85_ZTSKZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_E3$_0
- ___copy_helper_block_a8_32c98_ZTSKZZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_ENK3$_0clEvEUlvE_
- ___destroy_helper_block_a8_32c36_ZTSN2KB10retain_ptrIP10_LXLexiconEE
- ___destroy_helper_block_a8_32c42_ZTSNSt3__18weak_ptrI17AppTrieLoaderImplEE48c17_ZTSKN2KB6StringE80c17_ZTSKN2KB6StringE112c17_ZTSKN2KB6StringE
- ___destroy_helper_block_a8_32c85_ZTSKZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_E3$_0
- ___destroy_helper_block_a8_32c98_ZTSKZZZN17AppTrieLoaderImpl28register_as_contact_observerEN2KB6StringES1_S1_EUb_ENK3$_0clEvEUlvE_
- ___getLSApplicationProxyClass_block_invoke
- ___getLSApplicationWorkspaceClass_block_invoke
- _fileno
- _getLSApplicationProxyClass.softClass
- _getLSApplicationWorkspaceClass.softClass
- _log2
```
