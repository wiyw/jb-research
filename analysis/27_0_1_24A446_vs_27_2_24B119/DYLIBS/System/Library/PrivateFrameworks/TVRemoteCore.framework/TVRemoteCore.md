## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_imageinfo`

```diff

-627.0.28.0.0
-  __TEXT.__text: 0x48670
-  __TEXT.__lazy_helpers: 0x580
-  __TEXT.__objc_methlist: 0x64d0
-  __TEXT.__const: 0x240
-  __TEXT.__oslogstring: 0x6b90
-  __TEXT.__cstring: 0x372c
-  __TEXT.__gcc_except_tab: 0xb14
-  __TEXT.__unwind_info: 0x1210
+627.11.4.0.0
+  __TEXT.__text: 0x50568
+  __TEXT.__lazy_helpers: 0x5d4
+  __TEXT.__objc_methlist: 0x69e0
+  __TEXT.__const: 0x33a
+  __TEXT.__oslogstring: 0x722e
+  __TEXT.__cstring: 0x38e6
+  __TEXT.__gcc_except_tab: 0xbd4
+  __TEXT.__swift5_typeref: 0xbb
+  __TEXT.__constg_swiftt: 0x88
+  __TEXT.__swift5_reflstr: 0x41
+  __TEXT.__swift5_fieldmd: 0x68
+  __TEXT.__swift5_capture: 0x74
+  __TEXT.__swift5_types: 0x8
+  __TEXT.__swift_as_entry: 0x1c
+  __TEXT.__swift_as_ret: 0x2c
+  __TEXT.__swift_as_cont: 0x44
+  __TEXT.__unwind_info: 0x1440
+  __TEXT.__eh_frame: 0x5b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1638
-  __DATA_CONST.__objc_classlist: 0x290
+  __DATA_CONST.__const: 0x1758
+  __DATA_CONST.__objc_classlist: 0x2a0
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0xd8
+  __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3090
+  __DATA_CONST.__objc_selrefs: 0x3390
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x110
-  __DATA_CONST.__got: 0x470
-  __AUTH_CONST.__const: 0x480
-  __AUTH_CONST.__cfstring: 0x4a60
-  __AUTH_CONST.__objc_const: 0x9f88
-  __AUTH_CONST.__lazy_load_got: 0x80
+  __DATA_CONST.__got: 0x518
+  __AUTH_CONST.__const: 0x5b8
+  __AUTH_CONST.__cfstring: 0x4ba0
+  __AUTH_CONST.__objc_const: 0xa4b0
+  __AUTH_CONST.__lazy_load_got: 0x88
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1860
-  __DATA.__objc_ivar: 0x698
-  __DATA.__data: 0xa34
+  __AUTH_CONST.__auth_got: 0x680
+  __AUTH_CONST.__auth_ptr: 0x0
+  __AUTH.__objc_data: 0x1a08
+  __AUTH.__data: 0x50
+  __DATA.__objc_ivar: 0x6ac
+  __DATA.__data: 0xb24
+  __DATA.__common: 0x48
   __DATA_DIRTY.__objc_data: 0x140
-  __DATA_DIRTY.__bss: 0x170
+  __DATA_DIRTY.__bss: 0x180
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth

   - /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
   - /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils
+  - /System/Library/PrivateFrameworks/FindMyDeviceAccessories.framework/FindMyDeviceAccessories
   - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
   - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
   - /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote

   - /System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput
   - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
   - /System/Library/PrivateFrameworks/WatchListKit.framework/WatchListKit
+  - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed
   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2139
-  Symbols:   3704
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 2267
+  Symbols:   3875
   CStrings:  0
 
Symbols:
+ -[TVRCDeviceQuery discoverySources]
+ -[TVRCDeviceQuery init]
+ -[TVRCDeviceQuery setDiscoverySources:]
+ -[TVRCHMHomeObserver _isAtHome]
+ -[TVRCHMHomeObserver homeDidUpdateHomeLocationStatus:]
+ -[TVRCMatchPointDeviceImpl discoverySource]
+ -[TVRCRPCompanionLinkClientWrapper _fetchAndUpdateSiriStatus]
+ -[TVRCRPCompanionLinkClientWrapper _finishInvalidatingWithCompletionHandler:]
+ -[TVRCRPCompanionLinkClientWrapper _resolveFindMyRemoteSupportForDevice:]
+ -[TVRCRPCompanionLinkClientWrapper _setFindMyRemoteSupport:]
+ -[TVRCRPCompanionLinkClientWrapper _startMonitoringSiriStatus]
+ -[TVRCRPCompanionLinkClientWrapper _stopMonitoringSiriStatus]
+ -[TVRCRPCompanionLinkClientWrapper _updateFindMyRemoteSupport]
+ -[TVRCRPCompanionLinkClientWrapper activating]
+ -[TVRCRPCompanionLinkClientWrapper setActivating:]
+ -[TVRCRPCompanionLinkClientWrapper setFindMyRemoteSupport:]
+ -[TVRCRapportDeviceImpl discoverySource]
+ -[TVRCSiriRemoteInfo productID]
+ -[TVRCSiriRemoteInfo setProductID:]
+ -[TVRCXPCClient _beginDeviceQueryWithSources:response:]
+ -[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHandler:]
+ -[TVRCXPCClient beginDeviceQueryWithSources:response:]
+ -[TVRXDevice discoverySource]
+ -[TVRXDeviceQuery _stopSearchForSources:]
+ -[TVRXDeviceQuery addDiscoverySources:]
+ -[TVRXDeviceQuery discoverySources]
+ -[TVRXDeviceQuery removeDiscoverySources:]
+ -[TVRXDeviceQuery setDiscoverySources:]
+ GCC_except_table10
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table104
+ GCC_except_table110
+ GCC_except_table120
+ GCC_except_table125
+ GCC_except_table130
+ GCC_except_table136
+ GCC_except_table147
+ GCC_except_table152
+ GCC_except_table155
+ GCC_except_table157
+ GCC_except_table20
+ GCC_except_table32
+ GCC_except_table37
+ GCC_except_table41
+ GCC_except_table46
+ GCC_except_table49
+ GCC_except_table52
+ GCC_except_table8
+ GCC_except_table86
+ GCC_except_table88
+ GCC_except_table92
+ GCC_except_table94
+ _GestaltGetDeviceClass
+ _HMStringFromHomeLocation
+ _HMStringFromHomeLocation$lazyAuthGOT_IA_ad_0
+ _HMStringFromHomeLocation$lazyLoadStub
+ _OBJC_CLASS_$_TVRCFindMyRemoteInfo
+ _OBJC_CLASS_$_TVRCFindMySupportManager
+ _OBJC_IVAR_$_TVRCDeviceQuery._discoverySources
+ _OBJC_IVAR_$_TVRCRPCompanionLinkClientWrapper._activating
+ _OBJC_IVAR_$_TVRCRPCompanionLinkClientWrapper._findMyRemoteSupport
+ _OBJC_IVAR_$_TVRCSiriRemoteInfo._productID
+ _OBJC_IVAR_$_TVRXDeviceQuery._discoverySources
+ _OBJC_METACLASS_$_TVRCFindMyRemoteInfo
+ _OBJC_METACLASS_$_TVRCFindMySupportManager
+ _TVRCMessageKeyGroupRenderingMode
+ _TVRCRequestIDSurroundGetGroupRenderingMode
+ _TVRCRequestIDSurroundSetGroupRenderingMode
+ __Block_copy
+ __Block_release
+ __CLASS_METHODS_TVRCFindMySupportManager
+ __CLASS_PROPERTIES_TVRCFindMySupportManager
+ __DATA_TVRCFindMyRemoteInfo
+ __DATA_TVRCFindMySupportManager
+ __INSTANCE_METHODS_TVRCFindMyRemoteInfo
+ __INSTANCE_METHODS_TVRCFindMySupportManager
+ __IVARS_TVRCFindMyRemoteInfo
+ __IVARS_TVRCFindMySupportManager
+ __METACLASS_DATA_TVRCFindMyRemoteInfo
+ __METACLASS_DATA_TVRCFindMySupportManager
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_REFS_HMHomeDelegatePrivate
+ __OBJC_LABEL_PROTOCOL_$_HMHomeDelegatePrivate
+ __OBJC_PROTOCOL_$_HMHomeDelegatePrivate
+ __PROPERTIES_TVRCFindMyRemoteInfo
+ __TVRCFindMyLog
+ ___48-[TVRCRPCompanionLinkClientWrapper setDelegate:]_block_invoke
+ ___54-[TVRCXPCClient beginDeviceQueryWithSources:response:]_block_invoke
+ ___55-[TVRCXPCClient _beginDeviceQueryWithSources:response:]_block_invoke
+ ___55-[TVRCXPCClient _beginDeviceQueryWithSources:response:]_block_invoke_2
+ ___61-[TVRCRPCompanionLinkClientWrapper _fetchAndUpdateSiriStatus]_block_invoke
+ ___61-[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHandler:]_block_invoke
+ ___62-[TVRCRPCompanionLinkClientWrapper _startMonitoringSiriStatus]_block_invoke
+ ___73-[TVRCRPCompanionLinkClientWrapper _resolveFindMyRemoteSupportForDevice:]_block_invoke
+ ____TVRCFindMyLog_block_invoke
+ ___block_descriptor_40_e8_32s_e28_q16?0"TVRCSiriRemoteInfo"8ls32l8
+ ___block_descriptor_48_e8_32bs40r_e8_v12?0B8lr40l8s32l8
+ ___block_descriptor_48_e8_32bs40w_e42_v24?0"TVRCFindMyRemoteInfo"8"NSError"16lw40l8s32l8
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
+ ___block_descriptor_56_e8_32bs40w_e5_v8?0lw40l8s32l8
+ ___chkstk_darwin
+ ___swift_allocate_value_buffer
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor
+ ___swift_closure_destructor.10Tm
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_project_value_buffer
+ ___swift_reflection_version
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_TVRemoteCore
+ __swift_stdlib_bridgeErrorToNSError
+ __swift_stdlib_malloc_size
+ __swift_stdlib_reportUnimplementedInitializer
+ _dispatch_assert_queue$V2
+ _malloc_size
+ _memmove
+ _objc_allocWithZone
+ _swift_allocError
+ _swift_allocObject
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain
+ _swift_deallocObject
+ _swift_deletedMethodError
+ _swift_dynamicCast
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _swift_release_x9
+ _swift_retain_x19
+ _swift_retain_x20
+ _swift_retain_x21
+ _swift_retain_x8
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_future_wait_throwing
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
+ _swift_willThrow
+ _symbolic IeAgH_
+ _symbolic IeghH_
+ _symbolic SS
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic ScTy___________pGSg 23FindMyDeviceAccessories22LocalFindableAccessoryV13LiveInterfaceC s5ErrorP
+ _symbolic Si
+ _symbolic So8NSObjectC
+ _symbolic So8NSObjectCSg
+ _symbolic So8NSStringC
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 12TVRemoteCore16FindMyRemoteInfoC
+ _symbolic _____ 12TVRemoteCore20FindMySupportManagerC
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____SgSo7NSErrorCSgIeyByy_ 12TVRemoteCore16FindMyRemoteInfoC
+ _symbolic ______p s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic ytIeAgHr_
- -[TVRCRPCompanionLinkClientWrapper _findMyRemoteSupportForDevice:]
- -[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHander:]
- -[TVRCXPCClient beginDeviceQueryWithResponse:]
- -[TVRXDeviceQuery _stopSearch]
- GCC_except_table103
- GCC_except_table113
- GCC_except_table118
- GCC_except_table123
- GCC_except_table129
- GCC_except_table133
- GCC_except_table145
- GCC_except_table16
- GCC_except_table31
- GCC_except_table35
- GCC_except_table40
- GCC_except_table43
- GCC_except_table79
- GCC_except_table81
- GCC_except_table83
- GCC_except_table85
- GCC_except_table87
- GCC_except_table93
- GCC_except_table95
- ___46-[TVRCXPCClient beginDeviceQueryWithResponse:]_block_invoke
- ___46-[TVRCXPCClient beginDeviceQueryWithResponse:]_block_invoke_2
- ___60-[TVRCXPCClient _startDeviceQueryRetryTimerWithEventHander:]_block_invoke
```
