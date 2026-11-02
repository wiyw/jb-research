## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

```diff

-1347.0.0.0.0
-  __TEXT.__text: 0x1ea8bc
-  __TEXT.__objc_methlist: 0x1ffa8
-  __TEXT.__cstring: 0x12cd4
-  __TEXT.__const: 0x300
-  __TEXT.__gcc_except_tab: 0x3808
-  __TEXT.__oslogstring: 0x22879
+1355.1.0.0.0
+  __TEXT.__text: 0x1eca98
+  __TEXT.__objc_methlist: 0x20140
+  __TEXT.__cstring: 0x12fb4
+  __TEXT.__const: 0x310
+  __TEXT.__gcc_except_tab: 0x3864
+  __TEXT.__oslogstring: 0x22f76
   __TEXT.__dlopen_cstrs: 0x1ba
   __TEXT.__ustring: 0x168
   __TEXT.__constg_swiftt: 0x28

   __TEXT.__swift5_reflstr: 0x17
   __TEXT.__swift5_fieldmd: 0x28
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x7498
+  __TEXT.__unwind_info: 0x7528
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4020
-  __DATA_CONST.__objc_classlist: 0xf78
+  __DATA_CONST.__const: 0x40c0
+  __DATA_CONST.__objc_classlist: 0xf90
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8f00
+  __DATA_CONST.__objc_selrefs: 0x8fd8
   __DATA_CONST.__objc_protorefs: 0x50
-  __DATA_CONST.__objc_superrefs: 0xf20
-  __DATA_CONST.__objc_arraydata: 0x28
+  __DATA_CONST.__objc_superrefs: 0xf30
+  __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x1620
   __AUTH_CONST.__const: 0x720
   __AUTH_CONST.__cfstring: 0xaa00
-  __AUTH_CONST.__objc_const: 0x36f20
-  __AUTH_CONST.__objc_arrayobj: 0x60
-  __AUTH_CONST.__objc_intobj: 0xa8
+  __AUTH_CONST.__objc_const: 0x37290
+  __AUTH_CONST.__objc_arrayobj: 0x48
+  __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x8d90
-  __DATA.__objc_ivar: 0x16b8
+  __AUTH.__objc_data: 0x8b10
+  __DATA.__objc_ivar: 0x16dc
   __DATA.__data: 0x1120
   __DATA.__bss: 0x1a8
-  __DATA_DIRTY.__objc_data: 0xd20
+  __DATA_DIRTY.__objc_data: 0x1090
   __DATA_DIRTY.__bss: 0xa8
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11919
-  Symbols:   18649
+  Functions: 11964
+  Symbols:   18728
   CStrings:  0
 
Symbols:
+ +[NPKPassLibrarySyncState _shouldAddPass:withDeviceIsTinker:supportHealthPass:stateVersion:hasValidSignature:]
+ +[NPKPassSyncState(SyncVersion) minRemoteDevicePassSyncStateVersionSupportForDevice:]
+ +[NPKPassSyncState(SyncVersion) setMinRemoteDevicePassSyncStateVersionSupport:forDevice:]
+ -[NPKCompanionAgentConnection _applyPropertiesToPass:forDevice:]
+ -[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]
+ -[NPKPassLibrarySyncState initWithVersionStates:]
+ -[NPKPassLibrarySyncState uniqueIDsOfPassesSyncedByAlternateMethodWithVersion:]
+ -[NPKPassLibraryVersionState .cxx_destruct]
+ -[NPKPassLibraryVersionState alternateMethodUniqueIDs]
+ -[NPKPassLibraryVersionState initWithSyncState:alternateMethodUniqueIDs:]
+ -[NPKPassLibraryVersionState syncState]
+ -[NPKPassSignatureValidationCache .cxx_destruct]
+ -[NPKPassSignatureValidationCache hasValidSignatureForPass:manifestHash:]
+ -[NPKPassSignatureValidationCache init]
+ -[NPKPassSignatureValidationCache invalidatePassWithUniqueID:]
+ -[NPKPassSignatureValidationCacheEntry .cxx_destruct]
+ -[NPKPassSignatureValidationCacheEntry contentToken]
+ -[NPKPassSignatureValidationCacheEntry hasValidSignature]
+ -[NPKPassSignatureValidationCacheEntry setContentToken:]
+ -[NPKPassSignatureValidationCacheEntry setHasValidSignature:]
+ -[NPKPassSyncEngine initWithRole:syncStateVersion:]
+ -[NPKPassSyncEngine removeOutOfScopeItemsWithUniqueIDs:]
+ -[NPKPassSyncEngine setSyncStateVersion:]
+ -[NPKPassSyncEngine syncStateVersion]
+ -[NPKPassSyncService _remoteDeviceSyncStateVersion]
+ -[NPKPassSyncService _shouldHandleMessageNamed:fromID:]
+ -[NPKPassSyncService associatedPassDataRequested:service:account:fromID:context:]
+ -[NPKPassSyncService catalogChanged:service:account:fromID:context:]
+ -[NPKPassSyncService initWithPassSyncEngineRole:pairedDevice:]
+ -[NPKPassSyncService pairedDevice]
+ -[NPKPassSyncService passSettingsChanged:service:account:fromID:context:]
+ -[NPKPassSyncService passSyncEngine:didUpdateSyncStateVersion:]
+ -[NPKPassSyncService passSyncEngineArchivePath]
+ -[NPKPassSyncService passSyncEngineEncounteredUnexpectedEvent:]
+ -[NPKPassSyncService proposedReconciledState:service:account:fromID:context:]
+ -[NPKPassSyncService reconciledStateAccepted:service:account:fromID:context:]
+ -[NPKPassSyncService reconciledStateUnrecognized:service:account:fromID:context:]
+ -[NPKPassSyncService setPassSyncEngineArchivePath:]
+ -[NPKPassSyncService syncStateChangeProcessed:service:account:fromID:context:]
+ -[NPKPassSyncService syncStateChanged:service:account:fromID:context:]
+ -[NPKPassSyncState passSyncStateByRemovingPassesWithUniqueIDs:]
+ -[NPKPassSyncStateItem isValidForSync]
+ -[NPKPassSyncStateItem syncValidationDescription]
+ GCC_except_table164
+ GCC_except_table166
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table169
+ GCC_except_table234
+ GCC_except_table236
+ _NPKHomeDirectorySubpath
+ _NPKHomeDirectorySubpathForDevice
+ _NPKIDSSenderIdentifierBelongsToDifferentDevice
+ _NPKPassHasValidSignatureForStandaloneSync
+ _NPKPassIsSyncedByAlternateMethodWithStateVersion
+ _NPKPassNeedsSignatureValidationForStandaloneSync
+ _NPKPassSyncEngineArchivePathForDevice
+ _NPKPaymentWebServiceBackgroundContextPathForDevice
+ _NPKPeerPaymentAccountPathForDevice
+ _NPKPeerPaymentWebServiceContextPathForDevice
+ _NPKShouldUseStandaloneSyncForPassWithDeviceAndSignatureValidity
+ _NPKShouldUseStandaloneSyncForPassWithPairedDevice
+ _NPKStorePathForPaymentPassWithUniqueIDForDevice
+ _NPKStorePathForPaymentPassWithUniqueIDInDirectory
+ _NPKValidatePassSignatureForStandaloneSync
+ _OBJC_CLASS_$_NPKPassLibraryVersionState
+ _OBJC_CLASS_$_NPKPassSignatureValidationCache
+ _OBJC_CLASS_$_NPKPassSignatureValidationCacheEntry
+ _OBJC_IVAR_$_NPKPassLibrarySyncState._versionStates
+ _OBJC_IVAR_$_NPKPassLibraryVersionState._alternateMethodUniqueIDs
+ _OBJC_IVAR_$_NPKPassLibraryVersionState._syncState
+ _OBJC_IVAR_$_NPKPassSignatureValidationCache._entriesByUniqueID
+ _OBJC_IVAR_$_NPKPassSignatureValidationCache._lock
+ _OBJC_IVAR_$_NPKPassSignatureValidationCacheEntry._contentToken
+ _OBJC_IVAR_$_NPKPassSignatureValidationCacheEntry._hasValidSignature
+ _OBJC_IVAR_$_NPKPassSyncEngine._syncStateVersion
+ _OBJC_IVAR_$_NPKPassSyncService._pairedDevice
+ _OBJC_IVAR_$_NPKPassSyncService._passSyncEngineArchivePath
+ _OBJC_METACLASS_$_NPKPassLibraryVersionState
+ _OBJC_METACLASS_$_NPKPassSignatureValidationCache
+ _OBJC_METACLASS_$_NPKPassSignatureValidationCacheEntry
+ __NPKFinishDecodingAndLogFailure
+ __OBJC_$_CLASS_PROP_LIST_NPKPassSyncState
+ __OBJC_$_INSTANCE_METHODS_NPKPassLibraryVersionState
+ __OBJC_$_INSTANCE_METHODS_NPKPassSignatureValidationCache
+ __OBJC_$_INSTANCE_METHODS_NPKPassSignatureValidationCacheEntry
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassLibraryVersionState
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassSignatureValidationCache
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassSignatureValidationCacheEntry
+ __OBJC_$_PROP_LIST_NPKPassLibraryVersionState
+ __OBJC_$_PROP_LIST_NPKPassSignatureValidationCacheEntry
+ __OBJC_CLASS_RO_$_NPKPassLibraryVersionState
+ __OBJC_CLASS_RO_$_NPKPassSignatureValidationCache
+ __OBJC_CLASS_RO_$_NPKPassSignatureValidationCacheEntry
+ __OBJC_METACLASS_RO_$_NPKPassLibraryVersionState
+ __OBJC_METACLASS_RO_$_NPKPassSignatureValidationCache
+ __OBJC_METACLASS_RO_$_NPKPassSignatureValidationCacheEntry
+ ___34-[NPKPassSyncState initWithCoder:]_block_invoke
+ ___58-[NPKPassLibrarySyncState initWithStateVersionSyncStates:]_block_invoke
+ ___62-[NPKPassSyncService initWithPassSyncEngineRole:pairedDevice:]_block_invoke
+ ___63-[NPKPassSyncService passSyncEngineEncounteredUnexpectedEvent:]_block_invoke
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke_2
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e43_v32?0"NSNumber"8"NPKPassSyncState"16^B24ls32l8
+ ___block_descriptor_48_e8_32s40s_e39_v32?0"NSNumber"8"NSMutableSet"16^B24ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e23_v16?0"PKPaymentPass"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e23_v24?0B8f12"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_66_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_74_e8_32s40s48s56s64s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e47_v24?0"NPKIDVRemoteDeviceSession"8"NSError"16ls32l8s72l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_98_e8_32s40s48s56s64s72s80r88r_e25_v32?0"NSNumber"8Q16^B24ls32l8r80l8s40l8r88l8s48l8s56l8s64l8s72l8
- +[NPKPassLibrarySyncState _shouldAddPass:withDeviceIsTinker:supportHealthPass:stateVersion:]
- +[NPKPassSyncState(SyncVersion) _currentActiveDevice]
- +[NPKPassSyncState(SyncVersion) _deviceDomainAccessor]
- +[NPKPassSyncState(SyncVersion) minRemoteDevicePassSyncStateVersionSupport]
- +[NPKPassSyncState(SyncVersion) setMinRemoteDevicePassSyncStateVersionSupport:]
- -[NPKCompanionAgentConnection _applyPropertiesToPass:]
- -[NPKPassSyncEngine initWithRole:]
- -[NPKPassSyncService associatedPassDataRequested:]
- -[NPKPassSyncService catalogChanged:]
- -[NPKPassSyncService passSettingsChanged:]
- -[NPKPassSyncService proposedReconciledState:]
- -[NPKPassSyncService reconciledStateAccepted:]
- -[NPKPassSyncService reconciledStateUnrecognized:]
- -[NPKPassSyncService syncStateChangeProcessed:]
- -[NPKPassSyncService syncStateChanged:]
- GCC_except_table157
- GCC_except_table158
- GCC_except_table159
- GCC_except_table160
- GCC_except_table195
- GCC_except_table225
- GCC_except_table227
- _NPKRasterizedPassCachePath
- _NPKShouldUseStandaloneSyncForPass
- _OBJC_IVAR_$_NPKPassLibrarySyncState._syncStates
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke_2
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke_3
- ___49-[NPKPassSyncService initWithPassSyncEngineRole:]_block_invoke
- ___block_descriptor_40_e8_32s_e39_v32?0"NSNumber"8"NSMutableSet"16^B24ls32l8
- ___block_descriptor_56_e8_32s40s48bs_e23_v16?0"PKPaymentPass"8ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s48s_e8_v12?0B8ls32l8s40l8s48l8
- ___block_descriptor_58_e8_32s40s48s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8
- ___block_descriptor_58_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_66_e8_32s40s48s56s_e25_v32?0"NSNumber"8Q16^B24ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e47_v24?0"NPKIDVRemoteDeviceSession"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
```
