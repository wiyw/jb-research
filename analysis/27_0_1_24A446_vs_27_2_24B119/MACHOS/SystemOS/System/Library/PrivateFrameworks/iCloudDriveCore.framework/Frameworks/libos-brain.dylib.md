## libos-brain.dylib

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Frameworks/libos-brain.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

```diff

-5168.0.55.0.0
-  __TEXT.__text: 0x20b830
-  __TEXT.__auth_stubs: 0x2a20
-  __TEXT.__objc_stubs: 0x1f60
-  __TEXT.__objc_methlist: 0xd0c
-  __TEXT.__objc_methname: 0x3c72
-  __TEXT.__objc_classname: 0x418
-  __TEXT.__cstring: 0x4382
-  __TEXT.__objc_methtype: 0x11ff
-  __TEXT.__const: 0xcfb8
-  __TEXT.__swift5_typeref: 0x5322
-  __TEXT.__swift5_reflstr: 0x34bd
+5168.40.162.0.0
+  __TEXT.__text: 0x22bf08
+  __TEXT.__auth_stubs: 0x2a60
+  __TEXT.__objc_stubs: 0x2040
+  __TEXT.__objc_methlist: 0xda4
+  __TEXT.__objc_methname: 0x3cf8
+  __TEXT.__objc_classname: 0x438
+  __TEXT.__cstring: 0x45e2
+  __TEXT.__objc_methtype: 0x135f
+  __TEXT.__const: 0xd3e8
+  __TEXT.__swift5_typeref: 0x5688
+  __TEXT.__swift5_capture: 0x1ca4
+  __TEXT.__swift5_reflstr: 0x3652
   __TEXT.__swift5_assocty: 0xfa8
-  __TEXT.__constg_swiftt: 0x4528
-  __TEXT.__swift5_fieldmd: 0x2e88
-  __TEXT.__swift5_proto: 0x900
-  __TEXT.__swift5_types: 0x2e4
-  __TEXT.__swift_as_entry: 0x590
-  __TEXT.__swift_as_ret: 0x65c
-  __TEXT.__oslogstring: 0x855d
+  __TEXT.__constg_swiftt: 0x477c
+  __TEXT.__swift5_fieldmd: 0x3004
+  __TEXT.__oslogstring: 0x8628
+  __TEXT.__swift5_proto: 0x90c
+  __TEXT.__swift5_types: 0x2fc
+  __TEXT.__swift_as_entry: 0x61c
+  __TEXT.__swift_as_ret: 0x708
   __TEXT.__swift5_builtin: 0x190
-  __TEXT.__swift5_capture: 0x1850
-  __TEXT.__swift_as_cont: 0xcbc
+  __TEXT.__swift_as_cont: 0xe30
   __TEXT.__swift5_mpenum: 0x30
-  __TEXT.__swift5_protos: 0x164
-  __TEXT.__unwind_info: 0x62f8
-  __TEXT.__eh_frame: 0x117f0
-  __DATA_CONST.__const: 0x81e0
-  __DATA_CONST.__objc_classlist: 0x90
+  __TEXT.__swift5_protos: 0x16c
+  __TEXT.__unwind_info: 0x6990
+  __TEXT.__eh_frame: 0x12f68
+  __DATA_CONST.__const: 0x8c10
+  __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa48
+  __DATA_CONST.__objc_selrefs: 0xaa0
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x18
-  __DATA_CONST.__auth_got: 0x1518
-  __DATA_CONST.__got: 0x748
-  __DATA_CONST.__auth_ptr: 0x3210
-  __DATA.__objc_const: 0x5700
-  __DATA.__objc_ivar: 0x9c
-  __DATA.__objc_data: 0x498
-  __DATA.__data: 0x5088
-  __DATA.__common: 0xaf0
-  __DATA.__bss: 0x111e0
+  __DATA_CONST.__auth_got: 0x1538
+  __DATA_CONST.__got: 0x758
+  __DATA_CONST.__auth_ptr: 0x32d0
+  __DATA.__objc_const: 0x58d8
+  __DATA.__objc_ivar: 0x90
+  __DATA.__objc_data: 0x4a0
+  __DATA.__data: 0x5340
+  __DATA.__common: 0xb00
+  __DATA.__bss: 0x11300
   - /System/Library/Frameworks/CloudKit.framework/CloudKit
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6969
-  Symbols:   2121
+  Functions: 7382
+  Symbols:   2171
   CStrings:  0
 
Symbols:
+ -[iCDCreateItemContext clientKey]
+ -[iCDCreateItemContext initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:clientKey:]
+ -[iCDDeleteItemContext clientKey]
+ -[iCDDeleteItemContext initWithZoneName:zoneOwner:itemIDString:serverChangeToken:progress:clientKey:]
+ -[iCDModifyItemContext clientKey]
+ -[iCDModifyItemContext initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneName:parentZoneOwner:parentIDString:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:clientKey:]
+ OBJC_IVAR_$_iCDCreateItemContext._clientKey
+ OBJC_IVAR_$_iCDDeleteItemContext._clientKey
+ OBJC_IVAR_$_iCDModifyItemContext._clientKey
+ _PQLSqliteErrorDomain
+ __DATA__TtC8os_brain12TaskRegistry
+ __IVARS__TtC8os_brain12TaskRegistry
+ __METACLASS_DATA__TtC8os_brain12TaskRegistry
+ ___swift_memcpy120_8
+ ___swift_project_boxed_opaque_existential_1Tm
+ __swift_closure_destructor.112Tm
+ __swift_closure_destructor.13Tm
+ __swift_closure_destructor.20Tm
+ __swift_closure_destructor.22Tm
+ __swift_closure_destructor.31Tm
+ __swift_closure_destructor.404Tm
+ __swift_closure_destructor.40Tm
+ __swift_closure_destructor.52Tm
+ __swift_closure_destructor.85Tm
+ __swift_exist.box.addr_destructor.392Tm
+ _exit
+ _objc_msgSend$appLibraryRootNeedsCreationForAppLibraryID:completionHandler:
+ _objc_msgSend$clientKey
+ _objc_msgSend$quotaCategoryMUpperBound
+ _objc_msgSend$quotaCategorySUpperBound
+ _objc_msgSend$quotaCategoryXSUpperBound
+ _objc_msgSend$reviveAndSignalFPForRootItemID:zoneName:ownerName:completionHandler:
+ _objc_msgSend$setShouldCloneFileInAssetCache:
+ _objc_msgSend$setSqliteErrorHandler:
+ _objc_msgSend$zoneAndAppLibraryConsolidationFlagsForItemIDString:zoneName:ownerName:completionHandler:
+ _objc_msgSend$zoneAndAppLibraryRootNeedsCreationForZoneName:ownerName:completionHandler:
+ _objc_msgSend$zoneHasSyncedDownWithoutError:ownerName:completionHandler:
+ _objc_msgSend$zoneNeedsCreation:ownerName:completionHandler:
+ _objc_retain_x4
+ _swift_isaMask
+ _symbolic $s12common_brain22ZoneLifecycleProvidingP
+ _symbolic $s8os_brain20TaskRegistryProtocolP
+ _symbolic 21FetchRecordsOperation_____QzIeghH_Iegg______yyt______pGIeghg_Ieghggg_ 12common_brain23ServerContainerProtocolP s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic G0G0R6__
+ _symbolic Ieg_
+ _symbolic SDy_____Say_____GG 12common_brain14ZoneIdentifierO 03os_B012TaskRegistryC5Entry33_20662B8427504A7D2BD0236C5B295C51LLV
+ _symbolic SDy__________G 10Foundation4UUIDV 12common_brain14ZoneIdentifierO
+ _symbolic Say_____10rootItemID______4zonetG0A5Items_ShyACG5zonest 12common_brain14ItemIdentifierO AA04ZoneD0O
+ _symbolic Sb17zoneNeedsCreation_Sb014appLibraryRootbC0t
+ _symbolic Sb17zoneNeedsCreation_Sb04rootbC0Sb14isConsolidatedt
+ _symbolic ScCySb17zoneNeedsCreation_Sb014appLibraryRootbC0t_____G s5NeverO
+ _symbolic ScCySb17zoneNeedsCreation_Sb04rootbC0Sb14isConsolidatedt_____G s5NeverO
+ _symbolic Shy_____G 12common_brain14ItemIdentifierO
+ _symbolic _____ 12common_brain18PrerequisiteTargetV
+ _symbolic _____ 12common_brain19PrerequisiteRecordsV
+ _symbolic _____ 8os_brain12TaskRegistryC
+ _symbolic _____ 8os_brain12TaskRegistryC5Entry33_20662B8427504A7D2BD0236C5B295C51LLV
+ _symbolic _____ 8os_brain17QuotaErrorContextV
+ _symbolic _____ 8os_brain19QuotaSizeThresholdsO
+ _symbolic _____ s5Int64V
+ _symbolic _____10rootItemID______4zonet 12common_brain14ItemIdentifierO AA04ZoneD0O
+ _symbolic _____16contentSignature______Sg4sizet 10Foundation4DataV s5Int64V
+ _symbolic _____17oldItemIdentifier_AA03newbC0t 12common_brain14ItemIdentifierO
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
+ _symbolic ___________t 10Foundation4UUIDV 12common_brain14ZoneIdentifierO
+ _symbolic ______p 8os_brain20TaskRegistryProtocolP
+ _symbolic _____y6Record_____Qz16ContainerManager______0B4Type_____22ModifyRecordsOperation_____0A5Error_____QZG s6ResultOsRi_zRi0_zrlE 12common_brain32SyncUpIndependentJobStageHandlerP AC014CleanSubshareshI8ProtocolP AC022ServerContainerManagerL0P AC0mnL0P AC0M22ModifyRecordsOperationP
+ _symbolic _____ySS______pG s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____y_____10rootItemID______4zonetG s23_ContiguousArrayStorageC 12common_brain14ItemIdentifierO AC04ZoneG0O
+ _symbolic _____y_____G s11_SetStorageC 12common_brain14ItemIdentifierO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12common_brain18PrerequisiteTargetV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 8os_brain12TaskRegistryC5Entry33_20662B8427504A7D2BD0236C5B295C51LLV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 12common_brain14ZoneIdentifierO 03os_D012TaskRegistryC5Entry33_20662B8427504A7D2BD0236C5B295C51LLV
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4UUIDV 12common_brain14ZoneIdentifierO
+ _symbolic _____y_ytGSg7content______Sg4sizet 12common_brain14FileSystemItemV25AssetReferenceWithContextV s5Int64V
+ _symbolic ytIegr_
+ _type_layout_string 12common_brain12ServerRecordRzlAA19PrerequisiteRecordsVyxG
+ _type_layout_string 8os_brain17QuotaErrorContextV
- -[iCDCreateItemContext appLibraryIsConsolidated]
- -[iCDCreateItemContext appLibraryRootNeedsCreation]
- -[iCDCreateItemContext initWithReserverItemIDString:reservedFileProviderIdentifier:parentZoneName:parentZoneOwner:parentIDString:primaryZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:symlinkTarget:parentShareState:shareRootItemIdentifierString:parentPCSChainState:parentSharePermissions:initialItem:resetItem:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:]
- -[iCDCreateItemContext primaryZoneNeedsCreation]
- -[iCDDeleteItemContext initWithZoneName:zoneOwner:itemIDString:serverChangeToken:progress:]
- -[iCDModifyItemContext appLibraryIsConsolidated]
- -[iCDModifyItemContext appLibraryRootNeedsCreation]
- -[iCDModifyItemContext initWithResetItem:forceParentShared:zoneName:zoneOwner:itemIDString:parentZoneNeedsCreation:appLibraryRootNeedsCreation:appLibraryIsConsolidated:parentZoneName:parentZoneOwner:parentIDString:isInDocumentScope:trashPutBackPath:trashPutbackItemIDString:progress:]
- -[iCDModifyItemContext parentZoneNeedsCreation]
- OBJC_IVAR_$_iCDCreateItemContext._appLibraryIsConsolidated
- OBJC_IVAR_$_iCDCreateItemContext._appLibraryRootNeedsCreation
- OBJC_IVAR_$_iCDCreateItemContext._primaryZoneNeedsCreation
- OBJC_IVAR_$_iCDModifyItemContext._appLibraryIsConsolidated
- OBJC_IVAR_$_iCDModifyItemContext._appLibraryRootNeedsCreation
- OBJC_IVAR_$_iCDModifyItemContext._parentZoneNeedsCreation
- __swift_closure_destructor.10Tm
- __swift_closure_destructor.37Tm
- __swift_closure_destructor.67Tm
- __swift_exist.box.addr_destructor.243Tm
- __swift_exist.box.addr_destructor.261Tm
- _objc_msgSend$appLibraryIsConsolidated
- _objc_msgSend$appLibraryRootNeedsCreation
- _objc_msgSend$hasSyncedDownZoneSinceStartup:ownerName:completionHandler:
- _objc_msgSend$parentZoneNeedsCreation
- _objc_msgSend$primaryZoneNeedsCreation
- _symbolic G0G0R8__
- _symbolic _____17newItemIdentifier_t 12common_brain14ItemIdentifierO
- _symbolic _____y_ytGSg7content_t 12common_brain14FileSystemItemV25AssetReferenceWithContextV
```
