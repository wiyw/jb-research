## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

```diff

-4838.0.125.0.0
-  __TEXT.__text: 0x12dc8c
-  __TEXT.__objc_methlist: 0xe9dc
+4838.42.2.0.0
+  __TEXT.__text: 0x12e7b8
+  __TEXT.__objc_methlist: 0xeabc
   __TEXT.__const: 0x88a
-  __TEXT.__cstring: 0x14ea2
-  __TEXT.__gcc_except_tab: 0x8b24
+  __TEXT.__cstring: 0x15005
+  __TEXT.__gcc_except_tab: 0x8b64
   __TEXT.__oslogstring: 0xe394
   __TEXT.__dlopen_cstrs: 0x793
-  __TEXT.__ustring: 0x21e
+  __TEXT.__ustring: 0x288
   __TEXT.__swift5_typeref: 0xb4
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_reflstr: 0x45

   __TEXT.__swift_as_entry: 0x4
   __TEXT.__swift_as_ret: 0x4
   __TEXT.__swift_as_cont: 0xc
-  __TEXT.__unwind_info: 0x5948
+  __TEXT.__unwind_info: 0x59b0
   __TEXT.__eh_frame: 0xa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6220
+  __DATA_CONST.__const: 0x62a8
   __DATA_CONST.__objc_classlist: 0x698
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x2a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x70e0
+  __DATA_CONST.__objc_selrefs: 0x7160
   __DATA_CONST.__objc_protorefs: 0x158
   __DATA_CONST.__objc_superrefs: 0x550
   __DATA_CONST.__objc_arraydata: 0xab0
-  __DATA_CONST.__got: 0xb18
-  __AUTH_CONST.__const: 0x1da8
-  __AUTH_CONST.__cfstring: 0x115e0
-  __AUTH_CONST.__objc_const: 0x25060
+  __DATA_CONST.__got: 0xb20
+  __AUTH_CONST.__const: 0x1dc8
+  __AUTH_CONST.__cfstring: 0x11720
+  __AUTH_CONST.__objc_const: 0x25128
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__auth_got: 0xeb0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x25f8
+  __AUTH.__objc_data: 0x1a90
   __AUTH.__data: 0x10
   __DATA.__objc_ivar: 0x10d8
   __DATA.__data: 0x23f0
-  __DATA.__bss: 0xc30
+  __DATA.__bss: 0xc50
   __DATA.__common: 0x39
-  __DATA_DIRTY.__objc_data: 0x1bf8
+  __DATA_DIRTY.__objc_data: 0x2760
   __DATA_DIRTY.__data: 0x1
-  __DATA_DIRTY.__bss: 0x2e8
+  __DATA_DIRTY.__bss: 0x2d0
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
-  Functions: 7467
-  Symbols:   11218
+  Functions: 7491
+  Symbols:   11248
   CStrings:  0
 
Symbols:
+ +[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]
+ -[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]
+ -[FPAccessControlManager withServicerProxy:]
+ -[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]
+ -[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]
+ -[FPItemManager _fetchParentsForItemID:recursively:synchronously:completionHandler:]
+ -[FPItemManager fetchOperationServiceForProviderDomainID:synchronously:handler:]
+ -[FPItemManager parentItemIDsForItemID:recursively:error:]
+ -[FPItemManager parentsForItemID:recursively:error:]
+ -[FPProviderDomain owningApplicationIsInstallationHeld]
+ -[FPProviderDomain setOwningApplicationIsInstallationHeld:]
+ -[FPProviderDomain spotlightIndexName]
+ -[FPProviderDomainChangesReceiver _t_setCachedProviderDomainsByID:]
+ -[NSFileProviderDomain migrationState]
+ -[NSFileProviderDomain setMigrationState:]
+ -[NSURL(FPFSHelpers) fp_URLWithNoFollow]
+ -[NSURL(FPFSHelpers) fp_hasNoFollow]
+ GCC_except_table144
+ _FPKnownFolderTransitionedCategoryIdentifier
+ _FPKnownFolderTransitionedPreviousPathKey
+ _FPKnownFolderTransitionedShowActionIdentifier
+ _FPSpotlightIndexNamePrefix
+ _GSSTORAGE_FP_PROVIDER_CONTENT_VERSION_XATTR_NAME
+ _OBJC_IVAR_$_FPProviderDomain._owningApplicationIsInstallationHeld
+ _OBJC_IVAR_$_NSFileProviderDomain._migrationState
+ ___44-[FPAccessControlManager withServicerProxy:]_block_invoke
+ ___52-[FPItemManager parentsForItemID:recursively:error:]_block_invoke
+ ___58-[FPItemManager parentItemIDsForItemID:recursively:error:]_block_invoke
+ ___80-[FPItemManager fetchOperationServiceForProviderDomainID:synchronously:handler:]_block_invoke
+ ___84-[FPItemManager _fetchParentsForItemID:recursively:synchronously:completionHandler:]_block_invoke
+ ___88-[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]_block_invoke
+ ___90-[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]_block_invoke
+ ___90-[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]_block_invoke_2
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke_2
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke_3
+ ___99+[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8
+ ___block_descriptor_56_e8_32s40s48bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8s48l8s40l8
+ ___block_descriptor_58_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_66_e8_32s40s48bs_e52_v24?0"FPService<FPXOperationService>"8"NSError"16ls48l8s32l8s40l8
+ ___fpfs_supports_appDomainMigration_block_invoke
+ _fp_bundleRecord.kFPBundleRecordAssociatedObjectKey
+ _fpfs_supports_appDomainMigration
+ _fpfs_supports_appDomainMigration.feature_enabled
+ _fpfs_supports_appDomainMigration.once_token
+ _kFileProviderSupersededAppReplacementEntitlement
- -[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]
- GCC_except_table104
- GCC_except_table137
- _OBJC_IVAR_$_FPXPCAutomaticErrorProxy._retainCounter
- _OBJC_IVAR_$_FPXPCAutomaticErrorProxy._retainSelfWhileMessageIsPending
- ___66-[FPItemManager fetchOperationServiceForProviderDomainID:handler:]_block_invoke
- ___70-[FPItemManager _fetchParentsForItemID:recursively:completionHandler:]_block_invoke
- ___75-[FPItemManager fetchParentItemIDsForItemID:recursively:completionHandler:]_block_invoke
- ___75-[FPItemManager fetchParentItemIDsForItemID:recursively:completionHandler:]_block_invoke_2
- ___76-[FPAccessControlManager revokeAccessToAllItemsForBundle:completionHandler:]_block_invoke_3
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke_2
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke_3
- ___80-[FPAccessControlManager bundleIdentifiersWithAccessToAnyItemCompletionHandler:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e49_v24?0"<FPDAccessControlServicing>"8"NSError"16ls48l8s32l8s40l8
- ___block_descriptor_57_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
- ___block_descriptor_65_e8_32s40s48bs_e52_v24?0"FPService<FPXOperationService>"8"NSError"16ls48l8s32l8s40l8
- _kFPBundleRecordAssociatedObjectKey
```
