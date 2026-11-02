## HealthDaemonFoundation

> `/System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/HealthDaemonFoundation`

```diff

-7027.0.72.2.8
-  __TEXT.__text: 0x73c84
-  __TEXT.__objc_methlist: 0x3d8c
-  __TEXT.__const: 0x2322
-  __TEXT.__cstring: 0x49ba
-  __TEXT.__oslogstring: 0x3696
-  __TEXT.__gcc_except_tab: 0x3034
-  __TEXT.__swift5_typeref: 0xc12
-  __TEXT.__swift5_reflstr: 0x88b
-  __TEXT.__swift5_assocty: 0xd8
-  __TEXT.__constg_swiftt: 0xbb0
+7027.1.56.2.9
+  __TEXT.__text: 0x771a0
+  __TEXT.__objc_methlist: 0x3e34
+  __TEXT.__const: 0x23a2
+  __TEXT.__cstring: 0x4b6b
+  __TEXT.__oslogstring: 0x37e5
+  __TEXT.__gcc_except_tab: 0x3118
+  __TEXT.__swift5_typeref: 0xd2c
+  __TEXT.__swift5_reflstr: 0x90b
+  __TEXT.__swift5_assocty: 0xa8
+  __TEXT.__constg_swiftt: 0xcec
   __TEXT.__swift5_builtin: 0xa0
-  __TEXT.__swift5_fieldmd: 0x938
-  __TEXT.__swift5_proto: 0x10c
-  __TEXT.__swift5_types: 0xb8
-  __TEXT.__swift5_capture: 0x494
-  __TEXT.__swift5_protos: 0x2c
+  __TEXT.__swift5_fieldmd: 0xa04
+  __TEXT.__swift5_proto: 0x100
+  __TEXT.__swift5_types: 0xc4
+  __TEXT.__swift5_capture: 0x520
+  __TEXT.__swift5_protos: 0x38
+  __TEXT.__swift5_mpenum: 0x24
   __TEXT.__swift5_types2: 0xc
-  __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x2940
-  __TEXT.__eh_frame: 0x14c8
+  __TEXT.__unwind_info: 0x2a28
+  __TEXT.__eh_frame: 0x1548
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x11c0
-  __DATA_CONST.__objc_classlist: 0x2f0
+  __DATA_CONST.__const: 0x11e8
+  __DATA_CONST.__objc_classlist: 0x308
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0xf0
+  __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x21c8
-  __DATA_CONST.__objc_protorefs: 0x70
+  __DATA_CONST.__objc_selrefs: 0x21f8
+  __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0x6d8
-  __AUTH_CONST.__const: 0x2820
-  __AUTH_CONST.__cfstring: 0x4060
-  __AUTH_CONST.__objc_const: 0x86f0
+  __DATA_CONST.__got: 0x6f0
+  __AUTH_CONST.__const: 0x2a60
+  __AUTH_CONST.__cfstring: 0x4140
+  __AUTH_CONST.__objc_const: 0x8988
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1120
-  __AUTH_CONST.__auth_ptr: 0x2f0
-  __AUTH.__objc_data: 0xa60
-  __AUTH.__data: 0x150
+  __AUTH_CONST.__auth_got: 0x1128
+  __AUTH_CONST.__auth_ptr: 0x300
+  __AUTH.__objc_data: 0xb20
+  __AUTH.__data: 0x2d0
   __DATA.__objc_ivar: 0x56c
-  __DATA.__data: 0xc50
-  __DATA.__bss: 0x1f90
+  __DATA.__data: 0xbf0
+  __DATA.__bss: 0x1d30
   __DATA_DIRTY.__objc_data: 0x16d8
-  __DATA_DIRTY.__data: 0xa80
-  __DATA_DIRTY.__bss: 0xd0
+  __DATA_DIRTY.__data: 0xb38
+  __DATA_DIRTY.__bss: 0xe0
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3089
-  Symbols:   3969
+  Functions: 3144
+  Symbols:   4016
   CStrings:  0
 
Symbols:
+ +[HDSQLiteSchemaEntity hasStaticJoinClauses]
+ -[HDDatabaseAssertionManager _lock_releaseBackgroundAccessForFiles:]
+ -[HDSQLiteDatabase truncateWriteAheadLogWithBusyTimeout:contended:error:]
+ -[HDSQLiteQueryDescriptor _uncachedJoinClauseForProperties:predicateJoinClauses:]
+ -[HDXPCProcess isFirstParty]
+ -[HDXPCProcess unitTest_copyProcessWithBundleIdentifier:]
+ GCC_except_table109
+ GCC_except_table110
+ GCC_except_table117
+ GCC_except_table120
+ GCC_except_table44
+ GCC_except_table83
+ GCC_except_table88
+ GCC_except_table90
+ GCC_except_table96
+ _OBJC_METACLASS_$__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __CLASS_METHODS_HDFastPassBackgroundTask
+ __CLASS_METHODS_HDOneShotBackgroundTask
+ __DATA__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __DATA__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A641_ContentProtectionAvailabilityObservation
+ __DATA__TtCC22HealthDaemonFoundation31SQLiteDatabaseConnectionManagerP33_B2576AEC8BE9BB02E063715B6C40AF0F25DatabaseConnectionFlusher
+ __INSTANCE_METHODS__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __IVARS__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __IVARS__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A641_ContentProtectionAvailabilityObservation
+ __IVARS__TtCC22HealthDaemonFoundation31SQLiteDatabaseConnectionManagerP33_B2576AEC8BE9BB02E063715B6C40AF0F25DatabaseConnectionFlusher
+ __METACLASS_DATA__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __METACLASS_DATA__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A641_ContentProtectionAvailabilityObservation
+ __METACLASS_DATA__TtCC22HealthDaemonFoundation31SQLiteDatabaseConnectionManagerP33_B2576AEC8BE9BB02E063715B6C40AF0F25DatabaseConnectionFlusher
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HDContentProtectionObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDContentProtectionObserver
+ __OBJC_$_PROTOCOL_REFS_HDContentProtectionObserver
+ __OBJC_LABEL_PROTOCOL_$_HDContentProtectionObserver
+ __OBJC_PROTOCOL_$_HDContentProtectionObserver
+ __PROTOCOLS__TtC22HealthDaemonFoundationP33_5018826988AE70FF0AC90E49818760A638_ContentProtectionAvailabilityObserver
+ __ZZ25HDSQLiteEntityForPropertyE18propertyOwnerCache
+ __ZZ25HDSQLiteEntityForPropertyE23_propertyOwnerCacheLock
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE15joinClauseCache
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE19joinClauseCacheLock
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE25reportedSaturatedEntities
+ ___52-[HDSQLiteQueryDescriptor _joinClauseForProperties:]_block_invoke
+ ___73-[HDSQLiteDatabase truncateWriteAheadLogWithBusyTimeout:contended:error:]_block_invoke
+ ___block_descriptor_56_ea8_32s40s48s_e15_"NSString"8?0ls32l8s40l8s48l8
+ ___swift_memcpy41_8
+ ___swift_project_boxed_opaque_existential_0
+ _get_enum_tag_for_layout_string 22HealthDaemonFoundation14DataProtectionO
+ _symbolic $s22HealthDaemonFoundation0B14PluginProviderP
+ _symbolic $s22HealthDaemonFoundation27ContentProtectionMonitoringP
+ _symbolic $s22HealthDaemonFoundation28ContentProtectionObservationP
+ _symbolic SS4name______12directoryURL_____10protectiont 10Foundation3URLV 012HealthDaemonA014DataProtectionO
+ _symbolic So26HDContentProtectionManagerCSgXw
+ _symbolic So26HDContentProtectionManagerCSgXwz_Xx
+ _symbolic _____ 22HealthDaemonFoundation14DataProtectionO
+ _symbolic _____ 22HealthDaemonFoundation31SQLiteDatabaseConnectionManagerC0eF7Flusher33_B2576AEC8BE9BB02E063715B6C40AF0FLLC
+ _symbolic _____ 22HealthDaemonFoundation38_ContentProtectionAvailabilityObserver33_5018826988AE70FF0AC90E49818760A6LLC
+ _symbolic _____ 22HealthDaemonFoundation41_ContentProtectionAvailabilityObservation33_5018826988AE70FF0AC90E49818760A6LLC
+ _symbolic _____Sg 22HealthDaemonFoundation31SQLiteDatabaseConnectionManagerC0eF7Flusher33_B2576AEC8BE9BB02E063715B6C40AF0FLLC
+ _symbolic ______p 22HealthDaemonFoundation28ContentProtectionObservationP
+ _symbolic ______p7monitor_t 22HealthDaemonFoundation27ContentProtectionMonitoringP
+ _symbolic _____ySbG 15Synchronization5MutexVAARi_zrlE
+ _symbolic ySbYbc
+ _symbolic yyYbc
+ _type_layout_string 22HealthDaemonFoundation14DataProtectionO
- GCC_except_table105
- GCC_except_table106
- GCC_except_table112
- GCC_except_table113
- GCC_except_table118
- GCC_except_table84
- GCC_except_table87
- GCC_except_table89
- GCC_except_table92
- GCC_except_table95
- _associated conformance So20NSFileProtectionTypeaSHSCSQ
- _associated conformance So20NSFileProtectionTypeas20_SwiftNewtypeWrapperSCSY
- _associated conformance So20NSFileProtectionTypeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _symbolic SS4name______12directoryURL_____18fileProtectionTypet 10Foundation3URLV So20NSFileProtectionTypea
- _symbolic _____ So20NSFileProtectionTypea
```
