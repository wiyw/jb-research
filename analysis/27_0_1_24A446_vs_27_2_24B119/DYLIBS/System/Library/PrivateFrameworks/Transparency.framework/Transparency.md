## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

```diff

-1766.0.60.0.0
-  __TEXT.__text: 0x7db84
-  __TEXT.__objc_methlist: 0x4a90
-  __TEXT.__cstring: 0x303c
-  __TEXT.__const: 0x4a80
-  __TEXT.__gcc_except_tab: 0x4ec
-  __TEXT.__oslogstring: 0x1e5b
-  __TEXT.__swift5_typeref: 0x1050
-  __TEXT.__swift5_reflstr: 0x95a
+1766.40.58.0.0
+  __TEXT.__text: 0x82a64
+  __TEXT.__objc_methlist: 0x4b70
+  __TEXT.__cstring: 0x313c
+  __TEXT.__const: 0x4ee0
+  __TEXT.__gcc_except_tab: 0x518
+  __TEXT.__oslogstring: 0x229b
+  __TEXT.__swift5_typeref: 0x10e4
+  __TEXT.__swift5_reflstr: 0x9ca
   __TEXT.__swift5_assocty: 0x260
-  __TEXT.__constg_swiftt: 0xad8
+  __TEXT.__constg_swiftt: 0xb44
   __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_proto: 0x3a8
-  __TEXT.__swift5_types: 0xf0
-  __TEXT.__swift_as_entry: 0x120
-  __TEXT.__swift_as_ret: 0xfc
-  __TEXT.__swift_as_cont: 0x200
-  __TEXT.__swift5_fieldmd: 0xcb0
+  __TEXT.__swift5_proto: 0x3c4
+  __TEXT.__swift5_types: 0xf8
+  __TEXT.__swift_as_entry: 0x148
+  __TEXT.__swift_as_ret: 0x11c
+  __TEXT.__swift_as_cont: 0x248
+  __TEXT.__swift5_fieldmd: 0xd90
   __TEXT.__swift5_protos: 0xc
-  __TEXT.__swift5_acfuncs: 0x168
+  __TEXT.__swift5_acfuncs: 0x1b8
   __TEXT.__swift5_capture: 0x2c4
-  __TEXT.__unwind_info: 0x2c00
-  __TEXT.__eh_frame: 0x35b0
+  __TEXT.__unwind_info: 0x2d50
+  __TEXT.__eh_frame: 0x3840
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1640
+  __DATA_CONST.__const: 0x1690
   __DATA_CONST.__objc_classlist: 0x268
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2030
+  __DATA_CONST.__objc_selrefs: 0x20b8
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x180
-  __DATA_CONST.__got: 0x650
-  __AUTH_CONST.__const: 0x3df8
-  __AUTH_CONST.__cfstring: 0x3a80
-  __AUTH_CONST.__objc_const: 0x8020
+  __DATA_CONST.__got: 0x668
+  __AUTH_CONST.__const: 0x4118
+  __AUTH_CONST.__cfstring: 0x3ac0
+  __AUTH_CONST.__objc_const: 0x8140
   __AUTH_CONST.__objc_intobj: 0x1e0
-  __AUTH_CONST.__auth_got: 0xc90
+  __AUTH_CONST.__auth_got: 0xcb8
   __AUTH_CONST.__auth_ptr: 0x390
-  __AUTH.__objc_data: 0x2d8
-  __AUTH.__data: 0x548
-  __DATA.__objc_ivar: 0x3b0
-  __DATA.__data: 0x1090
-  __DATA.__bss: 0x7250
+  __AUTH.__data: 0x98
+  __DATA.__objc_ivar: 0x3c8
+  __DATA.__data: 0x9f0
+  __DATA.__bss: 0x7600
   __DATA.__common: 0x10
-  __DATA_DIRTY.__objc_data: 0x1af8
-  __DATA_DIRTY.__data: 0x230
-  __DATA_DIRTY.__bss: 0x910
+  __DATA_DIRTY.__objc_data: 0x1dd0
+  __DATA_DIRTY.__data: 0xe58
+  __DATA_DIRTY.__bss: 0x920
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Contacts.framework/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3793
-  Symbols:   3565
+  Functions: 3922
+  Symbols:   3612
   CStrings:  0
 
Symbols:
+ +[TransparencyXPCConnection nowNs]
+ -[KTQueryOptions queryReason]
+ -[KTQueryOptions setQueryReason:]
+ -[KTVerifierResult showsTreeResetWarning]
+ -[KTVerifierResult updateTreeResetInProgress:]
+ -[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:isFailureIgnoredForDate:]
+ -[TransparencyAnalytics fuzzyDaysSinceDate:]
+ -[TransparencyXPCConnection dropConnectionForGeneration:]
+ -[TransparencyXPCConnection firstSuppressedNs]
+ -[TransparencyXPCConnection flushSuppressedPeerExits:]
+ -[TransparencyXPCConnection generation]
+ -[TransparencyXPCConnection lastPeerExitLogNs]
+ -[TransparencyXPCConnection lastSuppressedNs]
+ -[TransparencyXPCConnection logPeerExit:]
+ -[TransparencyXPCConnection setFirstSuppressedNs:]
+ -[TransparencyXPCConnection setGeneration:]
+ -[TransparencyXPCConnection setLastPeerExitLogNs:]
+ -[TransparencyXPCConnection setLastSuppressedNs:]
+ -[TransparencyXPCConnection setSuppressedPeerExits:]
+ -[TransparencyXPCConnection suppressedPeerExits]
+ GCC_except_table11
+ GCC_except_table160
+ GCC_except_table188
+ GCC_except_table221
+ GCC_except_table23
+ GCC_except_table32
+ GCC_except_table7
+ _NSDebugDescriptionErrorKey
+ _NSInvalidArchiveOperationException
+ _OBJC_CLASS_$_NSException
+ _OBJC_IVAR_$_KTQueryOptions._queryReason
+ _OBJC_IVAR_$_TransparencyXPCConnection._firstSuppressedNs
+ _OBJC_IVAR_$_TransparencyXPCConnection._generation
+ _OBJC_IVAR_$_TransparencyXPCConnection._lastPeerExitLogNs
+ _OBJC_IVAR_$_TransparencyXPCConnection._lastSuppressedNs
+ _OBJC_IVAR_$_TransparencyXPCConnection._suppressedPeerExits
+ ___27-[KTIDSData initWithCoder:]_block_invoke
+ ___29-[KTIDSData encodeWithCoder:]_block_invoke
+ ___30-[KTIDSDataURI initWithCoder:]_block_invoke
+ ___32-[KTIDSDataURI encodeWithCoder:]_block_invoke
+ ___41-[TransparencyXPCConnection logPeerExit:]_block_invoke
+ ___43-[KTIDSDataURI initWithIDSData:ktResponse:]_block_invoke
+ ___46-[KTVerifierResult updateTreeResetInProgress:]_block_invoke
+ ___51-[SoftwareTransparency sysdiagnoseInfo:completion:]_block_invoke_2
+ ___54-[TransparencyXPCConnection flushSuppressedPeerExits:]_block_invoke
+ ___87-[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:isFailureIgnoredForDate:]_block_invoke
+ ___88-[SoftwareTransparency verifyExpiringProofs:forDigest:configuration:counter:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_56_e8_32s40w_e5_v8?0lw40l8s32l8
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _clock_gettime_nsec_np
+ _dispatch_after
+ _dispatch_time
+ _kTransparencyStaticKeyStoreContactExternalURI
+ _symbolic Say_____G 12Transparency15CKVLastRanEntryV
+ _symbolic _____ 12Transparency15CKVLastRanEntryV
+ _symbolic _____ 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic xSay_____G______p_____Rz_____RzlIetMHgozo_ 12Transparency15CKVLastRanEntryV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic xSay_____G______p_____RzlIetWHgozo_ 12Transparency15CKVLastRanEntryV s5ErrorP AA21CKVDiagnosticsServiceP
- -[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:]
- -[SoftwareTransparency verifyExpiringProofs:for:counter:completion:]
- GCC_except_table154
- GCC_except_table16
- GCC_except_table182
- GCC_except_table215
- GCC_except_table25
- GCC_except_table3
- GCC_except_table6
- GCC_except_table88
- _KTIDStaticKeyStoreEntryChanged
- _KTIDStaticKeyStoreEntryIdentifier
- ___63-[KTVerifierResult updateWithStaticKeyEnforcedPeerEnforcement:]_block_invoke
- ___68-[SoftwareTransparency verifyExpiringProofs:for:counter:completion:]_block_invoke
- ___swift_get_extra_inhabitant_index.13Tm
- ___swift_store_extra_inhabitant_index.14Tm
```
