## nearbyd

> `/usr/libexec/nearbyd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__info_plist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`

```diff

-569.0.0.0.0
-  __TEXT.__text: 0x55aab0
-  __TEXT.__auth_stubs: 0x30d0
-  __TEXT.__objc_stubs: 0x17500
-  __TEXT.__init_offsets: 0x6fc
-  __TEXT.__objc_methlist: 0xf85c
-  __TEXT.__gcc_except_tab: 0x55600
-  __TEXT.__const: 0x3fa9b0
-  __TEXT.__cstring: 0x38c82
-  __TEXT.__objc_methname: 0x23925
-  __TEXT.__oslogstring: 0x63a1a
-  __TEXT.__objc_classname: 0x20be
-  __TEXT.__objc_methtype: 0x22ded
+575.0.10.0.0
+  __TEXT.__text: 0x5a8d90
+  __TEXT.__auth_stubs: 0x35b0
+  __TEXT.__objc_stubs: 0x18480
+  __TEXT.__init_offsets: 0x704
+  __TEXT.__objc_methlist: 0x10104
+  __TEXT.__gcc_except_tab: 0x5798c
+  __TEXT.__const: 0x3fc0d0
+  __TEXT.__cstring: 0x3a461
+  __TEXT.__objc_methname: 0x255e5
+  __TEXT.__oslogstring: 0x68acd
+  __TEXT.__objc_classname: 0x2386
+  __TEXT.__objc_methtype: 0x2445b
   __TEXT.__ustring: 0x60
-  __TEXT.__swift5_typeref: 0x7ec
-  __TEXT.__swift5_capture: 0x574
-  __TEXT.__swift5_reflstr: 0x695
-  __TEXT.__swift5_assocty: 0xa8
-  __TEXT.__constg_swiftt: 0x9c0
+  __TEXT.__swift5_typeref: 0xcec
+  __TEXT.__swift5_capture: 0xc54
+  __TEXT.__swift5_reflstr: 0xe06
+  __TEXT.__swift5_assocty: 0x120
+  __TEXT.__constg_swiftt: 0x13b4
   __TEXT.__swift5_builtin: 0x64
-  __TEXT.__swift5_fieldmd: 0x644
-  __TEXT.__swift5_proto: 0x48
-  __TEXT.__swift5_types: 0x4c
+  __TEXT.__swift5_fieldmd: 0xc4c
+  __TEXT.__swift5_proto: 0xd0
+  __TEXT.__swift5_types: 0xa0
   __TEXT.__swift_as_entry: 0x60
   __TEXT.__swift_as_ret: 0x2c
   __TEXT.__swift_as_cont: 0x80
+  __TEXT.__swift5_protos: 0x4
   __TEXT.__info_plist: 0x40e
-  __TEXT.__unwind_info: 0x1d068
-  __TEXT.__eh_frame: 0x5a0
-  __DATA_CONST.__const: 0x1f4b8
-  __DATA_CONST.__cfstring: 0x17520
-  __DATA_CONST.__objc_classlist: 0x640
+  __TEXT.__unwind_info: 0x1e0d8
+  __TEXT.__eh_frame: 0x728
+  __DATA_CONST.__const: 0x21668
+  __DATA_CONST.__cfstring: 0x17d60
+  __DATA_CONST.__objc_classlist: 0x690
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x330
+  __DATA_CONST.__objc_protolist: 0x358
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0xb8
-  __DATA_CONST.__objc_superrefs: 0x538
-  __DATA_CONST.__objc_arraydata: 0x480
+  __DATA_CONST.__objc_protorefs: 0xc8
+  __DATA_CONST.__objc_superrefs: 0x540
+  __DATA_CONST.__objc_arraydata: 0x490
   __DATA_CONST.__objc_arrayobj: 0x228
-  __DATA_CONST.__objc_intobj: 0x990
+  __DATA_CONST.__objc_intobj: 0x978
   __DATA_CONST.__objc_dictobj: 0xa0
-  __DATA_CONST.__auth_got: 0x1880
-  __DATA_CONST.__got: 0xe60
-  __DATA_CONST.__auth_ptr: 0x300
-  __DATA.__objc_const: 0x1b800
-  __DATA.__objc_selrefs: 0x7180
-  __DATA.__objc_ivar: 0x1a1c
-  __DATA.__objc_data: 0x4a18
-  __DATA.__data: 0x42cc
-  __DATA.__bss: 0xe6b0
-  __DATA.__common: 0xe80
+  __DATA_CONST.__auth_got: 0x1af0
+  __DATA_CONST.__got: 0xf38
+  __DATA_CONST.__auth_ptr: 0x408
+  __DATA.__objc_const: 0x1c948
+  __DATA.__objc_selrefs: 0x7588
+  __DATA.__objc_ivar: 0x1a94
+  __DATA.__objc_data: 0x5890
+  __DATA.__data: 0x49dc
+  __DATA.__bss: 0x100f0
+  __DATA.__common: 0xf98
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/ActivityKit.framework/ActivityKit
+  - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

   - /usr/lib/libprotobuf-lite.dylib
   - /usr/lib/libprotobuf.dylib
   - /usr/lib/libz.1.dylib
+  - /usr/lib/swift/libswiftAccelerate.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 23573
-  Symbols:   1309
+  Functions: 24820
+  Symbols:   1442
   CStrings:  0
 
Symbols:
+ _$s10Foundation4DataV15_RepresentationOys5UInt8VSicig
+ _$s10Foundation4UUIDV10uuidStringACSgSSh_tcfC
+ _$s10Foundation4UUIDV10uuidStringSSvg
+ _$s10Foundation4UUIDVACycfC
+ _$s10Foundation4UUIDVMa
+ _$s10Foundation4UUIDVMn
+ _$s10Foundation4UUIDVSHAAMc
+ _$s2IDs12IdentifiablePTl
+ _$s2os6LoggerV9isEnabled4typeSbSo0a5_log_E2_ta_tF
+ _$s7Combine14AnyCancellableC5store2inyShyACGz_tF
+ _$s7Combine14AnyCancellableCMn
+ _$s7Combine9PublishedV12initialValueACyxGx_tcfC
+ _$s7Combine9PublishedV14projectedValueAC9PublisherVyx_Gvg
+ _$s7Combine9PublishedV18_enclosingInstance7wrapped7storagexqd___s24ReferenceWritableKeyPathCyqd__xGAHyqd__ACyxGGtcRld__CluigZ
+ _$s7Combine9PublishedV18_enclosingInstance7wrapped7storagexqd___s24ReferenceWritableKeyPathCyqd__xGAHyqd__ACyxGGtcRld__CluisZ
+ _$s7Combine9PublishedV9PublisherVMn
+ _$s7Combine9PublishedV9PublisherVyx_GAadAMc
+ _$s7Combine9PublishedVMa
+ _$s7Combine9PublishedVMn
+ _$s7Combine9PublisherPAAs5NeverO7FailureRtzrlE4sink12receiveValueAA14AnyCancellableCy6OutputQzc_tF
+ _$s8Dispatch0A12TimeIntervalO12millisecondsyACSicACmFWC
+ _$s8Dispatch0A12TimeIntervalOMa
+ _$s8Dispatch0A4TimeV3nowACyFZ
+ _$s8Dispatch0A4TimeV8advanced2byAcA0aB8IntervalO_tF
+ _$s8Dispatch0A4TimeVMa
+ _$s8Dispatch0A9PredicateO7onQueueyACSo17OS_dispatch_queueCcACmFWC
+ _$s8Dispatch0A9PredicateOMa
+ _$s8Dispatch1poiyAA0A4TimeVAD_SdtF
+ _$s8Dispatch25_dispatchPreconditionTestySbAA0A9PredicateOF
+ _$sSD10FoundationE36_unconditionallyBridgeFromObjectiveCySDyxq_GSo12NSDictionaryCSgFZ
+ _$sSD11descriptionSSvg
+ _$sSH13_rawHashValue4seedS2i_tFTj
+ _$sSL1goiySbx_xtFZTq
+ _$sSL1loiySbx_xtFZTq
+ _$sSL2geoiySbx_xtFZTq
+ _$sSL2leoiySbx_xtFZTq
+ _$sSLMp
+ _$sSLSQTb
+ _$sSS10describingSSx_tclufC
+ _$sSS16debugDescriptionSSvg
+ _$sSS9hasPrefixySbSSF
+ _$sSa034_makeUniqueAndReserveCapacityIfNotB0yyFyXl_Ts5
+ _$sSa16_createNewBuffer14bufferIsUnique15minimumCapacity13growForAppendySb_SiSbtFyXl_Ts5
+ _$sSa37_appendElementAssumeUniqueAndCapacity_03newB0ySi_xntFyXl_Ts5
+ _$sSbN
+ _$sSd5write2toyxz_ts16TextOutputStreamRzlF
+ _$sSdN
+ _$sSh11descriptionSSvg
+ _$sSiN
+ _$sSis23CustomStringConvertiblesWP
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _$sSo17OS_dispatch_queueC8DispatchE10AttributesVMa
+ _$sSo17OS_dispatch_queueC8DispatchE10AttributesVMn
+ _$sSo17OS_dispatch_queueC8DispatchE10AttributesVs10SetAlgebraACMc
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline3qos5flags7executeyAC0D4TimeV_AC0D3QoSVAC0D13WorkItemFlagsVyyXBtF
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO7inherityA2EmFWC
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyOMa
+ _$sSo17OS_dispatch_queueC8DispatchE4sync7executexxyKXE_tKlF
+ _$sSo17OS_dispatch_queueC8DispatchE5label3qos10attributes20autoreleaseFrequency6targetABSS_AC0D3QoSVAbCE10AttributesVAbCE011AutoreleaseI0OABSgtcfC
+ _$sSy10FoundationE8containsySbqd__SyRd__lF
+ _$ss018_bridgeAnyObjectToB0yypyXlSgF
+ _$ss10_HashTableV11startBucketAB0D0Vvg
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss11AnyHashableV13_rawHashValue4seedS2i_tF
+ _$ss11AnyHashableV2eeoiySbAB_ABtFZ
+ _$ss11AnyHashableVMn
+ _$ss11AnyHashableVN
+ _$ss11AnyHashableVSHsWP
+ _$ss11AnyHashableVyABxcSHRzlufC
+ _$ss11_SetStorageC4copy8originalAByxGs05__RawaB0C_tFZ
+ _$ss11_SetStorageC6resize8original8capacity4moveAByxGs05__RawaB0C_SiSbtFZ
+ _$ss11_SetStorageCMn
+ _$ss12IdentifiableMp
+ _$ss12IdentifiableP2IDAB_SHTn
+ _$ss12IdentifiableP2id2IDQzvgTq
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
+ _$ss18_DictionaryStorageC4copy8originalAByxq_Gs05__RawaB0C_tFZ
+ _$ss18_DictionaryStorageC6resize8original8capacity4moveAByxq_Gs05__RawaB0C_SiSbtFZ
+ _$ss21_findStringSwitchCase5cases6stringSiSays06StaticB0VG_SStF
+ _$ss23CustomStringConvertibleMp
+ _$ss23CustomStringConvertibleP11descriptionSSvgTj
+ _$ss23CustomStringConvertibleP11descriptionSSvgTq
+ _$ss26DefaultStringInterpolationVN
+ _$ss26DefaultStringInterpolationVs16TextOutputStreamsWP
+ _$ss28CustomDebugStringConvertibleMp
+ _$ss28CustomDebugStringConvertibleP16debugDescriptionSSvgTq
+ _$ss4Int8Vs23CustomStringConvertiblesWP
+ _$ss50ELEMENT_TYPE_OF_SET_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _$ss53KEY_TYPE_OF_DICTIONARY_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _$ss5ErrorP5_codeSivgTj
+ _$ss6HasherV8_combineyys6UInt64VF
+ _$ss6UInt64VN
+ _$ss6UInt64Vs23CustomStringConvertiblesWP
+ _$sytWV
+ _$syycWV
+ _CBDiscoveryFlagsToString
+ _CFPreferencesCopyValue
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
+ _NSSelectorFromString
+ _OBJC_CLASS_$_BLSBacklight
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _RPOptionSenderID
+ _RPOptionSenderIDSDeviceID
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
+ _swift_allocBox
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_dynamicCast
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getKeyPath
+ _swift_isEscapingClosureAtFileLocation
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x8
+ _swift_storeEnumTagSinglePayloadGeneric
- _CBConnectPeripheralOptionConnectionUseCase
```
