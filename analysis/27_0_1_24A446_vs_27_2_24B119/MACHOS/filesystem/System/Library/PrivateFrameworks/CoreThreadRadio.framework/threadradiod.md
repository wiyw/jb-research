## threadradiod

> `/System/Library/PrivateFrameworks/CoreThreadRadio.framework/threadradiod`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-442.0.0.0.0
-  __TEXT.__text: 0x41cb24
-  __TEXT.__auth_stubs: 0x12bd0
-  __TEXT.__objc_stubs: 0xa100
+446.0.4.0.0
+  __TEXT.__text: 0x41faf8
+  __TEXT.__auth_stubs: 0x12bf0
+  __TEXT.__objc_stubs: 0xa180
   __TEXT.__init_offsets: 0xb4
-  __TEXT.__objc_methlist: 0x6aa4
-  __TEXT.__gcc_except_tab: 0x2a39c
-  __TEXT.__const: 0x8664
-  __TEXT.__oslogstring: 0x28004
-  __TEXT.__cstring: 0x37256
+  __TEXT.__objc_methlist: 0x6ae4
+  __TEXT.__gcc_except_tab: 0x2a7f0
+  __TEXT.__const: 0x86a4
+  __TEXT.__oslogstring: 0x28cd9
+  __TEXT.__cstring: 0x37523
   __TEXT.__objc_classname: 0x6eb
-  __TEXT.__objc_methname: 0xf7d7
-  __TEXT.__objc_methtype: 0x4451
+  __TEXT.__objc_methname: 0xf8d1
+  __TEXT.__objc_methtype: 0x4467
   __TEXT.__swift5_typeref: 0x572
   __TEXT.__swift5_capture: 0x60c
   __TEXT.__swift5_fieldmd: 0x130

   __TEXT.__swift_as_entry: 0xac
   __TEXT.__swift_as_ret: 0x88
   __TEXT.__swift_as_cont: 0x1dc
-  __TEXT.__info_plist: 0x41b
-  __TEXT.__unwind_info: 0x126a0
+  __TEXT.__info_plist: 0x421
+  __TEXT.__unwind_info: 0x12710
   __TEXT.__eh_frame: 0x1f60
   __DATA_CONST.__const: 0xdcc8
-  __DATA_CONST.__cfstring: 0x6ce0
+  __DATA_CONST.__cfstring: 0x6de0
   __DATA_CONST.__objc_classlist: 0x190
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x140
-  __DATA_CONST.__auth_got: 0x9600
+  __DATA_CONST.__auth_got: 0x9610
   __DATA_CONST.__got: 0xbc0
   __DATA_CONST.__auth_ptr: 0x240
-  __DATA.__objc_const: 0x8b38
-  __DATA.__objc_selrefs: 0x3890
-  __DATA.__objc_ivar: 0x558
+  __DATA.__objc_const: 0x8b68
+  __DATA.__objc_selrefs: 0x38c0
+  __DATA.__objc_ivar: 0x55c
   __DATA.__objc_data: 0x1060
   __DATA.__data: 0xa39
   __DATA.__common: 0x3eec0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 18296
-  Symbols:   24095
+  Functions: 18306
+  Symbols:   24118
   CStrings:  0
 
Symbols:
+ -[THThreadNetworkCredentialsStoreLocalClient isValidTLVType:length:value:availableLength:]
+ -[THThreadNetworkCredentialsStoreLocalClient validateDataSetStructure:]
+ -[ThreadNetworkManagerInstance aodIntegrityPreviousCheckPending]
+ -[ThreadNetworkManagerInstance credentialTlvMaskForDataSet:]
+ -[ThreadNetworkManagerInstance dataSet:retainsTlvsOf:]
+ -[ThreadNetworkManagerInstance getActiveTimestampFromDataSet:]
+ -[ThreadNetworkManagerInstance setAodIntegrityPreviousCheckPending:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreThreadRadio/install/Symbols/BuiltProducts/libopenthread-ftd.a(heap-0f747e41226482d301b012c4009d050a.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreThreadRadio/install/Symbols/BuiltProducts/libopenthread-ftd.a(heap-b7bc1e5ca63c0bc1cbfecc051573a328.o)
+ GCC_except_table343
+ OBJC_IVAR_$_ThreadNetworkManagerInstance._aodIntegrityPreviousCheckPending
+ THDataSetIsValidTlv
+ THIsValidChannelTlv
+ THIsValidFixedLengthTlv
+ _$s7Network9NWBrowserC10DescriptorO7OptionsV10DeviceTypeV13homeAccessoryAIvgZ
+ _OUTLINED_FUNCTION_38
+ _THDataSetIsValidTlv
+ _THIsValidChannelTlv
+ _THIsValidFixedLengthTlv
+ __117-[THThreadNetworkCredentialsKeychainBackingStore retrieveActiveDataSetRecordWithTLVsForThreadBorderAgent:completion:]_block_invoke
+ __ZN20Ctr_NCPNetworkInfo_tD1Ev
+ __ZN2ot10KeyManager8ClearKekEv
+ __ZNK2ot10KeyManager8IsKekSetEv
+ ___150-[THThreadNetworkCredentialsStoreLocalClient storeThreadNetworkCredentialActiveDataSet:network:credentials:credentialsDataSet:waitForSync:completion:]_block_invoke_3
+ _objc_msgSend$credentialTlvMaskForDataSet:
+ _objc_msgSend$dataSet:retainsTlvsOf:
+ _objc_msgSend$getActiveTimestampFromDataSet:
+ _objc_msgSend$isValidTLVType:length:value:availableLength:
+ _objc_msgSend$validateDataSetStructure:
+ _thInspectDataSet
+ thInspectDataSet
- -[THThreadNetworkCredentialsKeychainBackingStore parsedChannelFromData:len:currentPos:debugDescription:error:]
- -[THThreadNetworkCredentialsStoreLocalClient parsedChannelFromData:len:currentPos:debugDescription:error:]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreThreadRadio/install/Symbols/BuiltProducts/libopenthread-ftd.a(heap-907cf6985676bcfa85796b69de7a3ca2.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreThreadRadio/install/Symbols/BuiltProducts/libopenthread-ftd.a(heap-e09d5eb68d8170f36b42857da0a1dc1e.o)
- GCC_except_table307
- GCC_except_table323
- GCC_except_table547
- _objc_msgSend$parsedChannelFromData:len:currentPos:debugDescription:error:
```
