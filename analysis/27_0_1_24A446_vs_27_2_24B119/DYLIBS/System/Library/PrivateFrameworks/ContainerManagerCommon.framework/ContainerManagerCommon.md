## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon`

```diff

-833.0.8.0.1
-  __TEXT.__text: 0xf3018
-  __TEXT.__objc_methlist: 0xae74
-  __TEXT.__const: 0x13b0
-  __TEXT.__cstring: 0x9585
-  __TEXT.__swift5_typeref: 0x6d3
-  __TEXT.__oslogstring: 0xe983
-  __TEXT.__constg_swiftt: 0x670
-  __TEXT.__swift5_reflstr: 0x3da
-  __TEXT.__swift5_fieldmd: 0x4c8
-  __TEXT.__swift5_builtin: 0x104
+833.40.18.0.1
+  __TEXT.__text: 0x10b69c
+  __TEXT.__objc_methlist: 0xb634
+  __TEXT.__const: 0x1620
+  __TEXT.__cstring: 0xa13c
+  __TEXT.__swift5_typeref: 0x889
+  __TEXT.__oslogstring: 0x10329
+  __TEXT.__constg_swiftt: 0x7b0
+  __TEXT.__swift5_reflstr: 0x56a
+  __TEXT.__swift5_fieldmd: 0x644
+  __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_assocty: 0x138
   __TEXT.__swift5_proto: 0xb0
-  __TEXT.__swift5_types: 0x98
+  __TEXT.__swift5_types: 0xb8
+  __TEXT.__swift5_capture: 0xa8
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__swift5_capture: 0x78
   __TEXT.__swift5_protos: 0x18
-  __TEXT.__gcc_except_tab: 0x2498
+  __TEXT.__gcc_except_tab: 0x255c
   __TEXT.__ustring: 0x16c
-  __TEXT.__unwind_info: 0x2508
-  __TEXT.__eh_frame: 0x5d8
+  __TEXT.__unwind_info: 0x27a0
+  __TEXT.__eh_frame: 0xa74
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x18d8
-  __DATA_CONST.__objc_classlist: 0x5c0
-  __DATA_CONST.__objc_catlist: 0x28
-  __DATA_CONST.__objc_protolist: 0x528
+  __DATA_CONST.__const: 0x1960
+  __DATA_CONST.__objc_classlist: 0x5e8
+  __DATA_CONST.__objc_catlist: 0x30
+  __DATA_CONST.__objc_protolist: 0x620
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3770
-  __DATA_CONST.__objc_protorefs: 0xc8
+  __DATA_CONST.__objc_selrefs: 0x3a28
+  __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0x4a8
-  __DATA_CONST.__objc_arraydata: 0x2e0
-  __DATA_CONST.__got: 0x500
-  __AUTH_CONST.__const: 0x12c8
-  __AUTH_CONST.__cfstring: 0x4d40
-  __AUTH_CONST.__objc_const: 0x17058
+  __DATA_CONST.__objc_arraydata: 0x2e8
+  __DATA_CONST.__got: 0x548
+  __AUTH_CONST.__const: 0x15c0
+  __AUTH_CONST.__cfstring: 0x4e60
+  __AUTH_CONST.__objc_const: 0x17da0
   __AUTH_CONST.__objc_dictobj: 0x118
-  __AUTH_CONST.__objc_intobj: 0x1590
+  __AUTH_CONST.__objc_intobj: 0x15a8
   __AUTH_CONST.__objc_arrayobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x12d0
-  __AUTH_CONST.__auth_ptr: 0x2a0
-  __AUTH.__objc_data: 0xd70
-  __AUTH.__data: 0xd0
-  __DATA.__objc_ivar: 0xc10
-  __DATA.__data: 0x3bb0
+  __AUTH_CONST.__auth_got: 0x1448
+  __AUTH_CONST.__auth_ptr: 0x310
+  __AUTH.__objc_data: 0xea8
+  __AUTH.__data: 0x1b8
+  __DATA.__objc_ivar: 0xc5c
+  __DATA.__data: 0x3db0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xef8
-  __DATA_DIRTY.__objc_data: 0x3020
-  __DATA_DIRTY.__data: 0x448
-  __DATA_DIRTY.__bss: 0x6b0
+  __DATA.__bss: 0xe38
+  __DATA.__common: 0x48
+  __DATA_DIRTY.__objc_data: 0x3198
+  __DATA_DIRTY.__data: 0x568
+  __DATA_DIRTY.__bss: 0x7f0
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3659
-  Symbols:   6904
+  Functions: 3932
+  Symbols:   7095
   CStrings:  0
 
Symbols:
+ +[MCMConcreteContainerIdentity containerIdentityWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:transient:userIdentityCache:error:]
+ +[MCMConcreteContainerIdentity containerIdentityWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:userIdentityCache:error:]
+ +[MCMConcreteContainerIdentityForLibsystem containerIdentityWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:containerPathIdentifier:existed:transient:userIdentityCache:error:]
+ +[MCMContainerCacheEntry metadataReadErrorIsInconclusive:]
+ +[MCMContainerCacheEntry verificationErrorIsRecoverable:]
+ +[MCMContainerCacheEntry(xattr) _identityRecordFromLegacyXattrsForFileHandle:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) _removeLegacyIdentityXattrsForFileHandle:]
+ +[MCMContainerCacheEntry(xattr) identityRecordForFileHandle:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) identityRecordForURL:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) removeIdentityRecordForURL:]
+ +[MCMContainerCacheEntry(xattr) setIdentityRecord:forFileHandle:]
+ +[MCMContainerCacheEntry(xattr) setIdentityRecord:forURL:]
+ +[MCMContainerFactory lookupErrorPermitsCreation:]
+ +[MCMContainerIdentity containerIdentityWithIdentifier:containerConfig:platform:posixOwnership:instanceUUID:userIdentityCache:error:]
+ +[MCMContainerIdentity containerIdentityWithUserIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:transient:userIdentityCache:error:]
+ +[MCMContainerIdentity containerIdentityWithUserIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:userIdentityCache:error:]
+ +[MCMContainerSchema containerSchemaWithMetadata:finalContainerPath:dataProtectionClass:libraryRepair:error:]
+ +[MCMPOSIXUser _getCachedUID:GID:name:flush:error:onCacheMiss:]
+ +[MCMPOSIXUser _posixUserWithUID:GID:name:error:]
+ +[MCMPOSIXUser _validatedHomeDirectoryURLFromURL:redactName:resolvable:]
+ +[MCMPOSIXUser posixUserWithUID:GID:error:]
+ +[MCMPOSIXUser unvalidatedPOSIXUserWithUID:GID:unvalidatedHomeDirectoryURL:]
+ +[NSUUID(MCMUUIDIsNull) MCM_null]
+ -[MCMChildParentMapCache _lock_childIdentifiersForParentIdentifier:]
+ -[MCMChildParentMapCache lock_cache]
+ -[MCMChildParentMapCache removeMappingsForIdentifier:]
+ -[MCMClientIdentity isAllowedToSupersedeContainer]
+ -[MCMCommandQuery coexistingInstances]
+ -[MCMCommandQuery defaultInstanceUUID]
+ -[MCMCommandQuery instanceUUID]
+ -[MCMConcreteContainerIdentity initWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:transient:userIdentityCache:error:]
+ -[MCMConcreteContainerIdentity initWithVersion1And2And3PlistDictionary:containerIdentity:error:]
+ -[MCMConcreteContainerIdentityForLibsystem initWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:containerPathIdentifier:existed:transient:userIdentityCache:error:]
+ -[MCMContainerCache _claimContainer:forInstanceUUID:classCache:error:]
+ -[MCMContainerCache _missingContainerErrorForClassCache:]
+ -[MCMContainerCache _unreadableContainerError]
+ -[MCMContainerCache entriesForContainerIdentityIgnoringInstance:error:]
+ -[MCMContainerCache entryForContainerIdentity:classCache:mutationAllowed:coexistingInstances:error:]
+ -[MCMContainerCache entryForContainerIdentity:classCache:mutationAllowed:error:]
+ -[MCMContainerCache removeContainerForUserIdentity:contentClass:containerIdentity:containerPath:transient:error:]
+ -[MCMContainerCacheEntry _fabricateMetadataForContainerPath:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:userIdentityCache:]
+ -[MCMContainerCacheEntry _metadataFromContainerPath:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:userIdentityCache:]
+ -[MCMContainerCacheEntry initFromContainerPath:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:userIdentityCache:]
+ -[MCMContainerCacheEntry initWithIdentifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:userIdentityCache:]
+ -[MCMContainerCacheEntry instanceUUID]
+ -[MCMContainerClassCache _concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:instanceUUID:uuid:metadata:]
+ -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:out_deferred:]
+ -[MCMContainerClassCache _lock_addIdentityToInstanceIndex:]
+ -[MCMContainerClassCache _lock_removeIdentityFromInstanceIndex:]
+ -[MCMContainerClassCache _noteUnreadableContainer]
+ -[MCMContainerClassCache _resetUnreadableContainers]
+ -[MCMContainerClassCache cacheEntriesForIdentityIgnoringInstance:]
+ -[MCMContainerClassCache cacheEntryForIdentity:multiInstance:]
+ -[MCMContainerClassCache hasUnreadableContainers]
+ -[MCMContainerClassCache lock_instanceIndex]
+ -[MCMContainerClassCache removeCacheEntryForIdentity:containerPath:]
+ -[MCMContainerConfiguration deleteCorruptContainers]
+ -[MCMContainerConfiguration exclusiveInstance]
+ -[MCMContainerConfiguration supportsTransient]
+ -[MCMContainerConfiguration usesInstanceUUID]
+ -[MCMContainerFactory containerForContainerIdentity:createIfNecessary:coexistingInstances:error:]
+ -[MCMContainerIdentity initWithUserIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:transient:userIdentityCache:error:]
+ -[MCMContainerIdentity initWithVersion1PlistDictionary:posixOwnership:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentity initWithVersion2PlistDictionary:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentity initWithVersion3PlistDictionary:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentityMinimal identityByChangingInstanceUUID:]
+ -[MCMContainerIdentityMinimal initWithUserIdentity:identifier:containerConfig:platform:posixOwnership:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentityMinimal initWithVersion1PlistDictionary:posixOwnership:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentityMinimal initWithVersion2PlistDictionary:instanceUUID:userIdentityCache:error:]
+ -[MCMContainerIdentityMinimal initWithVersion3PlistDictionary:userIdentityCache:error:]
+ -[MCMContainerIdentityMinimal instanceUUID]
+ -[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]
+ -[MCMContainerMigrator _repairMetadataDataProtectionWithContainerConfig:context:]
+ -[MCMContainerMigrator queueUnlockDeferredMigrationsWithContext:]
+ -[MCMContainerSchema initWithMetadata:finalContainerPath:dataProtectionClass:libraryRepair:error:]
+ -[MCMEntitlements canSupersedeContainer]
+ -[MCMEntitlements isAllowedToSupersedeContainer]
+ -[MCMError errorByChangingType:]
+ -[MCMMetadata metadataByChangingSuperseded:]
+ -[MCMMetadata metadataByClearingPersistedStatus]
+ -[MCMMetadata superseded]
+ -[MCMMetadataMinimal instanceUUID]
+ -[MCMPOSIXPermission posixUserWithError:]
+ -[MCMPOSIXUser initWithUID:primaryGID:homeDirectoryURL:unvalidatedHomeDirectoryURL:name:roleUser:validatedUser:]
+ -[MCMPOSIXUser validatedUser]
+ -[MCMResultContainerFromPath initWithUUID:containerPathIdentifier:identifier:containerConfig:POSIXUser:personaUniqueString:sandboxToken:existed:url:info:transient:userManagedAssetsRelPath:creator:posixOwnership:instanceUUID:relativePath:]
+ -[MCMResultWithContainerBase initWithUUID:containerPathIdentifier:identifier:containerConfig:POSIXUser:personaUniqueString:sandboxToken:existed:url:info:transient:userManagedAssetsRelPath:creator:posixOwnership:instanceUUID:]
+ -[MCMResultWithContainerBase instanceUUID]
+ -[MCMXPCMessageQuery coexistingInstances]
+ -[MCMXPCMessageQuery defaultInstanceUUID]
+ -[MCMXPCMessageQuery instanceUUID]
+ -[NSUUID(MCMUUIDIsNull) MCM_isNull]
+ GCC_except_table1013
+ GCC_except_table1047
+ GCC_except_table1049
+ GCC_except_table1105
+ GCC_except_table1114
+ GCC_except_table1118
+ GCC_except_table1168
+ GCC_except_table1185
+ GCC_except_table1191
+ GCC_except_table1196
+ GCC_except_table1199
+ GCC_except_table1205
+ GCC_except_table1207
+ GCC_except_table1209
+ GCC_except_table1211
+ GCC_except_table1214
+ GCC_except_table1220
+ GCC_except_table1222
+ GCC_except_table1224
+ GCC_except_table1230
+ GCC_except_table1233
+ GCC_except_table1243
+ GCC_except_table1258
+ GCC_except_table1262
+ GCC_except_table1264
+ GCC_except_table1319
+ GCC_except_table1329
+ GCC_except_table1360
+ GCC_except_table1601
+ GCC_except_table1754
+ GCC_except_table1758
+ GCC_except_table1912
+ GCC_except_table1918
+ GCC_except_table2022
+ GCC_except_table2160
+ GCC_except_table2303
+ GCC_except_table2320
+ GCC_except_table2321
+ GCC_except_table2386
+ GCC_except_table2440
+ GCC_except_table2456
+ GCC_except_table2477
+ GCC_except_table2546
+ GCC_except_table2558
+ GCC_except_table2627
+ GCC_except_table2639
+ GCC_except_table2664
+ GCC_except_table2687
+ GCC_except_table2697
+ GCC_except_table2722
+ GCC_except_table2725
+ GCC_except_table2728
+ GCC_except_table2733
+ GCC_except_table2784
+ GCC_except_table2788
+ GCC_except_table2955
+ GCC_except_table2959
+ GCC_except_table3039
+ GCC_except_table315
+ GCC_except_table343
+ GCC_except_table352
+ GCC_except_table371
+ GCC_except_table394
+ GCC_except_table403
+ GCC_except_table500
+ GCC_except_table688
+ GCC_except_table785
+ GCC_except_table879
+ GCC_except_table957
+ _MCMCompareDataProtectionClassTarget
+ _MCMGetDataProtectionClass
+ _MCMMigrationTypeRepairMetadataDataProtection
+ _MCMParentBundleKey
+ _MCMSetDataProtectionClass
+ _MCM_null.onceToken
+ _MCM_null.uuid
+ _MKBDeviceUnlockedSinceBoot
+ _OBJC_CLASS_$_MCMCommandSupersedeContainer
+ _OBJC_CLASS_$_MCMContainerIdentityRecord
+ _OBJC_CLASS_$_MCMContainerSupersession
+ _OBJC_CLASS_$_MCMMetadataDataProtectionRepair
+ _OBJC_CLASS_$__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ _OBJC_IVAR_$_MCMChildParentMapCache._cacheLock
+ _OBJC_IVAR_$_MCMChildParentMapCache._lock_cache
+ _OBJC_IVAR_$_MCMCommandQuery._coexistingInstances
+ _OBJC_IVAR_$_MCMCommandQuery._defaultInstanceUUID
+ _OBJC_IVAR_$_MCMCommandQuery._instanceUUID
+ _OBJC_IVAR_$_MCMContainerCacheEntry._instanceUUID
+ _OBJC_IVAR_$_MCMContainerClassCache._lock_instanceIndex
+ _OBJC_IVAR_$_MCMContainerClassCache._lock_unreadableCount
+ _OBJC_IVAR_$_MCMContainerConfiguration._deleteCorruptContainers
+ _OBJC_IVAR_$_MCMContainerConfiguration._exclusiveInstance
+ _OBJC_IVAR_$_MCMContainerConfiguration._supportsTransient
+ _OBJC_IVAR_$_MCMContainerConfiguration._usesInstanceUUID
+ _OBJC_IVAR_$_MCMContainerIdentityMinimal._instanceUUID
+ _OBJC_IVAR_$_MCMMetadata._superseded
+ _OBJC_IVAR_$_MCMPOSIXPermission._lock_posixUser
+ _OBJC_IVAR_$_MCMPOSIXPermission._posixUserLock
+ _OBJC_IVAR_$_MCMPOSIXUser._validatedUser
+ _OBJC_IVAR_$_MCMResultWithContainerBase._instanceUUID
+ _OBJC_IVAR_$_MCMXPCMessageQuery._coexistingInstances
+ _OBJC_IVAR_$_MCMXPCMessageQuery._defaultInstanceUUID
+ _OBJC_IVAR_$_MCMXPCMessageQuery._instanceUUID
+ _OBJC_METACLASS_$_MCMCommandSupersedeContainer
+ _OBJC_METACLASS_$_MCMContainerIdentityRecord
+ _OBJC_METACLASS_$_MCMContainerSupersession
+ _OBJC_METACLASS_$_MCMMetadataDataProtectionRepair
+ _OBJC_METACLASS_$__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ __CLASS_METHODS_MCMCommandSupersedeContainer
+ __DATA_MCMCommandSupersedeContainer
+ __DATA_MCMContainerIdentityRecord
+ __DATA_MCMContainerSupersession
+ __DATA_MCMMetadataDataProtectionRepair
+ __DATA__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ __INSTANCE_METHODS_MCMCommandSupersedeContainer
+ __INSTANCE_METHODS_MCMContainerIdentityRecord
+ __INSTANCE_METHODS_MCMContainerSupersession
+ __INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __INSTANCE_METHODS__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ __IVARS_MCMCommandSupersedeContainer
+ __IVARS_MCMContainerIdentityRecord
+ __IVARS_MCMContainerSupersession
+ __IVARS_MCMMetadataDataProtectionRepair
+ __IVARS__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ __MCMCrashIfClassUsesInstanceUUID
+ __METACLASS_DATA_MCMCommandSupersedeContainer
+ __METACLASS_DATA_MCMContainerIdentityRecord
+ __METACLASS_DATA_MCMContainerSupersession
+ __METACLASS_DATA_MCMMetadataDataProtectionRepair
+ __METACLASS_DATA__TtC22ContainerManagerCommon31MCMXPCMessageSupersedeContainer
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSUUID_$_MCMUUIDIsNull
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUUID_$_MCMUUIDIsNull
+ __OBJC_$_CATEGORY_NSUUID_$_MCMUUIDIsNull
+ __OBJC_$_CLASS_METHODS_MCMContainerFactory
+ __OBJC_$_PROP_LIST_MCMContainerIdentityHasInstanceUUID
+ __OBJC_$_PROP_LIST_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROP_LIST_NSUUID_$_MCMUUIDIsNull
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MCMContainerIdentityHasInstanceUUID
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MCMContainerIdentityHasInstanceUUID
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_REFS_MCMContainerIdentityHasInstanceUUID
+ __OBJC_$_PROTOCOL_REFS_MCMMetadataDataProtectionRepair
+ __OBJC_LABEL_PROTOCOL_$_MCMContainerIdentityHasInstanceUUID
+ __OBJC_LABEL_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __OBJC_PROTOCOL_$_MCMContainerIdentityHasInstanceUUID
+ __OBJC_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __PROPERTIES_MCMCommandSupersedeContainer
+ __PROPERTIES_MCMContainerIdentityRecord
+ __PROPERTIES_MCMContainerSupersession
+ __PROPERTIES_MCMMetadataDataProtectionRepair
+ __PROTOCOLS_MCMMetadataDataProtectionRepair
+ ___113-[MCMContainerCache removeContainerForUserIdentity:contentClass:containerIdentity:containerPath:transient:error:]_block_invoke
+ ___33+[NSUUID(MCMUUIDIsNull) MCM_null]_block_invoke
+ ___43+[MCMPOSIXUser posixUserWithUID:GID:error:]_block_invoke
+ ___49+[MCMPOSIXUser _posixUserWithUID:GID:name:error:]_block_invoke
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_2
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_3
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_4
+ ___63+[MCMPOSIXUser _getCachedUID:GID:name:flush:error:onCacheMiss:]_block_invoke
+ ___65-[MCMContainerMigrator queueUnlockDeferredMigrationsWithContext:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e8_v12?0i8ls32l8
+ ___block_descriptor_48_e23_"MCMPOSIXUser"16?0^8l
+ ___block_descriptor_48_e8_32s_e23_"MCMPOSIXUser"16?0^8ls32l8
+ ___block_descriptor_64_e8_32bs40r48r56r_e5_v8?0lr40l8r48l8r56l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56r_e5_v8?0lr48l8s32l8s40l8r56l8
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_memcpy40_8
+ ___swift_project_boxed_opaque_existential_0
+ __getCachedUID:GID:name:flush:error:onCacheMiss:.cacheByName
+ __getCachedUID:GID:name:flush:error:onCacheMiss:.cacheByUID
+ __getCachedUID:GID:name:flush:error:onCacheMiss:.cacheByUIDGID
+ __getCachedUID:GID:name:flush:error:onCacheMiss:.onceToken
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ _container_get_instance_uuid
+ _flat unique So11MCMMetadata_p
+ _flat unique So14MCMFileManager_p
+ _flat unique So17MCMCommandContext_p
+ _flat unique So22MCMContainerCacheEntry_p
+ _memchr
+ _notify_cancel
+ _swift_allocBox
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getExistentialTypeMetadata
+ _swift_retain_x25
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_unknownObjectRetain_n
+ _symbolic SRy_____G s5UInt8V
+ _symbolic SS_ypt
+ _symbolic So24MCMContainerSupersessionC
+ _symbolic So38MCMXPCMessageWithConcreteContainerBaseC
+ _symbolic So40MCMConcreteContainerIdentityForLibsystemCSg
+ _symbolic So6NSUUIDCSg
+ _symbolic _____ 22ContainerManagerCommon022MCMXPCMessageSupersedeA0C
+ _symbolic _____ 22ContainerManagerCommon23MCMCommandSupersedePlanO
+ _symbolic _____ 22ContainerManagerCommon23MCMCommandSupersedePlanO9PreflightO
+ _symbolic _____ 22ContainerManagerCommon27MCMCommandSupersedeExecutorV
+ _symbolic _____ 22ContainerManagerCommon27MCMCommandSupersedeExecutorV8Progress33_E7A3FEDC1F76939CD5C7857805CE17D5LLV
+ _symbolic _____ 22ContainerManagerCommon29MCMCommandSupersedeResumptionV
+ _symbolic _____ 22ContainerManagerCommon29MCMCommandSupersedeResumptionV5FoundV
+ _symbolic _____ So17container_error_ta
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic ______p So11MCMMetadataP
+ _symbolic ______p So14MCMFileManagerP
+ _symbolic ______p So17MCMCommandContextP
+ _symbolic ______p So22MCMContainerCacheEntryP
+ _symbolic ______pSg So11MCMMetadataP
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySo15MCMUserIdentityCG s11_SetStorageC
+ _symbolic _____y_____G s16IteratorSequenceV 10Foundation017NSFastEnumerationA0V
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
+ _type_layout_string 22ContainerManagerCommon23MCMCommandSupersedePlanO9PreflightO
+ _type_layout_string 22ContainerManagerCommon27MCMCommandSupersedeExecutorV
+ _type_layout_string 22ContainerManagerCommon29MCMCommandSupersedeResumptionV
+ _type_layout_string 22ContainerManagerCommon29MCMCommandSupersedeResumptionV5FoundV
+ _type_layout_string So17container_error_ta
+ _uuid_parse
- +[MCMConcreteContainerIdentity containerIdentityWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:transient:userIdentityCache:error:]
- +[MCMConcreteContainerIdentityForLibsystem containerIdentityWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:containerPathIdentifier:existed:transient:userIdentityCache:error:]
- +[MCMContainerCacheEntry(xattr) UUIDForFileHandle:]
- +[MCMContainerCacheEntry(xattr) UUIDForURL:]
- +[MCMContainerCacheEntry(xattr) identifierForFileHandle:]
- +[MCMContainerCacheEntry(xattr) identifierForURL:]
- +[MCMContainerCacheEntry(xattr) schemaVersionForFileHandle:]
- +[MCMContainerCacheEntry(xattr) schemaVersionForURL:]
- +[MCMContainerCacheEntry(xattr) setIdentifier:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setIdentifier:forURL:]
- +[MCMContainerCacheEntry(xattr) setSchemaVersion:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setSchemaVersion:forURL:]
- +[MCMContainerCacheEntry(xattr) setUUID:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setUUID:forURL:]
- +[MCMContainerSchema containerSchemaWithMetadata:finalContainerPath:dataProtectionClass:libraryRepair:]
- +[MCMPOSIXUser _getCachedUID:GID:name:flush:onCacheMiss:]
- +[MCMPOSIXUser _posixUserWithUID:GID:name:]
- -[MCMChildParentMapCache cache]
- -[MCMCommandUserDataMigration _replaceContainer:withContainer:changingParentIdentifier:]
- -[MCMConcreteContainerIdentity initWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:transient:userIdentityCache:error:]
- -[MCMConcreteContainerIdentity initWithVersion1And2PlistDictionary:containerIdentity:error:]
- -[MCMConcreteContainerIdentityForLibsystem initWithUUID:userIdentity:identifier:containerConfig:platform:posixOwnership:containerPathIdentifier:existed:transient:userIdentityCache:error:]
- -[MCMContainerCacheEntry _fabricateMetadataForContainerPath:identifier:uuid:schemaVersion:posixOwnership:userIdentityCache:]
- -[MCMContainerCacheEntry _metadataFromContainerPath:identifier:uuid:schemaVersion:posixOwnership:userIdentityCache:]
- -[MCMContainerCacheEntry initFromContainerPath:identifier:uuid:schemaVersion:posixOwnership:userIdentityCache:]
- -[MCMContainerCacheEntry initWithIdentifier:containerPath:schemaVersion:posixOwnership:uuid:metadata:userIdentityCache:]
- -[MCMContainerClassCache _concurrent_generateCacheEntryWithURL:identifier:containerPath:schemaVersion:posixOwnership:uuid:metadata:]
- -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:containerPath:]
- -[MCMContainerClassCache cacheEntryForIdentity:]
- -[MCMContainerIdentity initWithUserIdentity:identifier:containerConfig:platform:posixOwnership:transient:userIdentityCache:error:]
- -[MCMContainerIdentity initWithVersion1PlistDictionary:posixOwnership:userIdentityCache:error:]
- -[MCMContainerIdentity initWithVersion2PlistDictionary:userIdentityCache:error:]
- -[MCMContainerIdentityMinimal initWithUserIdentity:identifier:containerConfig:platform:posixOwnership:userIdentityCache:error:]
- -[MCMContainerIdentityMinimal initWithVersion1PlistDictionary:posixOwnership:userIdentityCache:error:]
- -[MCMContainerIdentityMinimal initWithVersion2PlistDictionary:userIdentityCache:error:]
- -[MCMContainerSchema initWithMetadata:finalContainerPath:dataProtectionClass:libraryRepair:]
- -[MCMPOSIXPermission initWithUID:GID:mode:isNull:]
- -[MCMPOSIXPermission posixUser]
- -[MCMPOSIXUser initWithUID:primaryGID:homeDirectoryURL:unvalidatedHomeDirectoryURL:name:roleUser:]
- -[MCMResultContainerFromPath initWithUUID:containerPathIdentifier:identifier:containerConfig:POSIXUser:personaUniqueString:sandboxToken:existed:url:info:transient:userManagedAssetsRelPath:creator:posixOwnership:relativePath:]
- -[MCMResultWithContainerBase initWithUUID:containerPathIdentifier:identifier:containerConfig:POSIXUser:personaUniqueString:sandboxToken:existed:url:info:transient:userManagedAssetsRelPath:creator:posixOwnership:]
- GCC_except_table1021
- GCC_except_table1023
- GCC_except_table1079
- GCC_except_table1088
- GCC_except_table1092
- GCC_except_table1141
- GCC_except_table1142
- GCC_except_table1158
- GCC_except_table1160
- GCC_except_table1164
- GCC_except_table1169
- GCC_except_table1172
- GCC_except_table1178
- GCC_except_table1180
- GCC_except_table1182
- GCC_except_table1184
- GCC_except_table1189
- GCC_except_table1193
- GCC_except_table1195
- GCC_except_table1197
- GCC_except_table1203
- GCC_except_table1206
- GCC_except_table1208
- GCC_except_table1231
- GCC_except_table1237
- GCC_except_table1292
- GCC_except_table1302
- GCC_except_table1333
- GCC_except_table1571
- GCC_except_table1721
- GCC_except_table1725
- GCC_except_table1879
- GCC_except_table1885
- GCC_except_table1987
- GCC_except_table2121
- GCC_except_table2262
- GCC_except_table2279
- GCC_except_table2280
- GCC_except_table2345
- GCC_except_table2391
- GCC_except_table2407
- GCC_except_table2428
- GCC_except_table2497
- GCC_except_table2509
- GCC_except_table2578
- GCC_except_table2588
- GCC_except_table2613
- GCC_except_table2636
- GCC_except_table2646
- GCC_except_table2670
- GCC_except_table2672
- GCC_except_table2675
- GCC_except_table2680
- GCC_except_table2726
- GCC_except_table2730
- GCC_except_table2896
- GCC_except_table2899
- GCC_except_table2976
- GCC_except_table305
- GCC_except_table323
- GCC_except_table342
- GCC_except_table361
- GCC_except_table384
- GCC_except_table393
- GCC_except_table490
- GCC_except_table677
- GCC_except_table763
- GCC_except_table865
- GCC_except_table942
- GCC_except_table990
- _OBJC_IVAR_$_MCMChildParentMapCache._cache
- _OBJC_IVAR_$_MCMPOSIXPermission._posixUser
- ___37+[MCMPOSIXUser posixUserWithUID:GID:]_block_invoke
- ___39-[MCMChildParentMapCache capturedState]_block_invoke
- ___43+[MCMPOSIXUser _posixUserWithUID:GID:name:]_block_invoke
- ___57+[MCMPOSIXUser _getCachedUID:GID:name:flush:onCacheMiss:]_block_invoke
- ___99-[MCMContainerCache removeContainerForUserIdentity:contentClass:containerIdentity:transient:error:]_block_invoke
- ___block_descriptor_48_e19_"MCMPOSIXUser"8?0l
- ___block_descriptor_48_e8_32s_e19_"MCMPOSIXUser"8?0ls32l8
- __getCachedUID:GID:name:flush:onCacheMiss:.cacheByName
- __getCachedUID:GID:name:flush:onCacheMiss:.cacheByUID
- __getCachedUID:GID:name:flush:onCacheMiss:.cacheByUIDGID
- __getCachedUID:GID:name:flush:onCacheMiss:.onceToken
```
