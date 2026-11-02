## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

```diff

-751.100.2.0.0
-  __TEXT.__text: 0xd9624
-  __TEXT.__objc_methlist: 0x9f48
-  __TEXT.__cstring: 0x144ac
-  __TEXT.__const: 0x3f68
-  __TEXT.__gcc_except_tab: 0x14c4
-  __TEXT.__oslogstring: 0x242d
-  __TEXT.__swift5_typeref: 0xbd5
-  __TEXT.__swift5_capture: 0x890
-  __TEXT.__swift5_fieldmd: 0xb28
-  __TEXT.__constg_swiftt: 0xd94
-  __TEXT.__swift5_reflstr: 0x91c
-  __TEXT.__swift5_proto: 0x144
-  __TEXT.__swift5_types: 0xb0
+751.200.101.0.0
+  __TEXT.__text: 0xe64d0
+  __TEXT.__objc_methlist: 0xa2d0
+  __TEXT.__cstring: 0x1503c
+  __TEXT.__const: 0x4458
+  __TEXT.__gcc_except_tab: 0x1530
+  __TEXT.__oslogstring: 0x289d
+  __TEXT.__swift5_typeref: 0xccd
+  __TEXT.__swift5_capture: 0x958
+  __TEXT.__swift5_fieldmd: 0xc14
+  __TEXT.__constg_swiftt: 0xf08
+  __TEXT.__swift5_reflstr: 0xabc
+  __TEXT.__swift5_proto: 0x164
+  __TEXT.__swift5_types: 0xb8
   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__swift5_assocty: 0x88
-  __TEXT.__swift5_builtin: 0x50
+  __TEXT.__swift5_assocty: 0x100
+  __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x2ed0
+  __TEXT.__unwind_info: 0x3058
   __TEXT.__eh_frame: 0x960
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x27e8
-  __DATA_CONST.__objc_classlist: 0x2c8
+  __DATA_CONST.__const: 0x2960
+  __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x150
+  __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x44e0
-  __DATA_CONST.__objc_protorefs: 0xe0
-  __DATA_CONST.__objc_superrefs: 0x1f0
+  __DATA_CONST.__objc_selrefs: 0x46d0
+  __DATA_CONST.__objc_protorefs: 0xf0
+  __DATA_CONST.__objc_superrefs: 0x1f8
   __DATA_CONST.__objc_arraydata: 0xb0
-  __DATA_CONST.__got: 0x4d0
-  __AUTH_CONST.__const: 0x2658
-  __AUTH_CONST.__cfstring: 0x60a0
-  __AUTH_CONST.__objc_const: 0x112f8
-  __AUTH_CONST.__objc_intobj: 0x240
+  __DATA_CONST.__got: 0x4f0
+  __AUTH_CONST.__const: 0x2940
+  __AUTH_CONST.__cfstring: 0x6060
+  __AUTH_CONST.__objc_const: 0x11808
+  __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x1140
-  __AUTH_CONST.__auth_ptr: 0x2c0
-  __AUTH.__objc_data: 0x1280
-  __AUTH.__data: 0x538
-  __DATA.__objc_ivar: 0x10f4
-  __DATA.__data: 0x20d8
-  __DATA.__bss: 0x2ea0
+  __AUTH_CONST.__auth_got: 0x11b0
+  __AUTH_CONST.__auth_ptr: 0x3a8
+  __AUTH.__objc_data: 0x50
+  __DATA.__objc_ivar: 0x1124
+  __DATA.__data: 0x6e8
+  __DATA.__bss: 0x32a0
   __DATA.__common: 0x68
-  __DATA_DIRTY.__objc_data: 0x1318
-  __DATA_DIRTY.__data: 0x588
-  __DATA_DIRTY.__bss: 0xc8
+  __DATA_DIRTY.__objc_data: 0x2768
+  __DATA_DIRTY.__data: 0x2660
+  __DATA_DIRTY.__bss: 0xd8
   __DATA_DIRTY.__common: 0x28
   - /System/Library/Frameworks/CFNetwork.framework/CFNetwork
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5746
-  Symbols:   6761
+  Functions: 5948
+  Symbols:   6913
   CStrings:  0
 
Symbols:
+ +[RPNWTXTUtils statusFlagsForEndpoint:]
+ +[RPNWTXTUtils statusFlagsForTXTRecord:]
+ +[RPNWTXTUtils updateStatusFlags:onEndpoint:operation:]
+ +[RPNWTXTUtils updateStatusFlags:onTXTRecord:operation:]
+ -[RPAccessPolicyClient .cxx_destruct]
+ -[RPAccessPolicyClient _activateWithPolicy:forService:completion:]
+ -[RPAccessPolicyClient _invalidate]
+ -[RPAccessPolicyClient _invalidated]
+ -[RPAccessPolicyClient _updateState:]
+ -[RPAccessPolicyClient _xpcActivate:completion:]
+ -[RPAccessPolicyClient _xpcInterrupted]
+ -[RPAccessPolicyClient _xpcInvalidated]
+ -[RPAccessPolicyClient _xpcSetup]
+ -[RPAccessPolicyClient accessPermittedHandler]
+ -[RPAccessPolicyClient accessPolicyUpdatedDevices:]
+ -[RPAccessPolicyClient accessRevokedHandler]
+ -[RPAccessPolicyClient activateWithPolicy:forService:completion:]
+ -[RPAccessPolicyClient devices]
+ -[RPAccessPolicyClient dispatchQueue]
+ -[RPAccessPolicyClient init]
+ -[RPAccessPolicyClient invalidate]
+ -[RPAccessPolicyClient invalidationHandler]
+ -[RPAccessPolicyClient policy]
+ -[RPAccessPolicyClient serviceName]
+ -[RPAccessPolicyClient setAccessPermittedHandler:]
+ -[RPAccessPolicyClient setAccessRevokedHandler:]
+ -[RPAccessPolicyClient setDevices:]
+ -[RPAccessPolicyClient setDispatchQueue:]
+ -[RPAccessPolicyClient setInvalidationHandler:]
+ -[RPAccessPolicyClient setState:]
+ -[RPAccessPolicyClient setXpcConnection:]
+ -[RPAccessPolicyClient state]
+ -[RPAccessPolicyClient xpcConnection]
+ -[RPClient endpointContextForService:trustCircles:completion:]
+ -[RPClient endpointContextForService:trustCircles:parameters:completion:]
+ -[RPClient updateEndpointAttributes:forService:usingContext:completion:]
+ -[RPCompanionLinkDevice updateMultiUserDeviceWithPeer:]
+ -[RPConnection _accountOwnerCheckEnabled]
+ -[RPConnection _identityDaemonGetPairingIdentityFromHomeWithAccessory:completion:]
+ -[RPConnection _isAccountCheckedWithPeerModel:]
+ -[RPConnection _localDeviceClass]
+ -[RPConnection _multiUserDeviceWithIdentifier:]
+ -[RPConnection _peerUpdatedAfterTrustChange:]
+ -[RPConnection _requestIDIsHighVolume:messageIsChatty:]
+ -[RPConnection _sourceVersionFromString:]
+ -[RPConnection accountOwnerCheckApplies]
+ -[RPConnection localAccountUpdated]
+ -[RPConnection multiUserDevices]
+ -[RPConnection setMultiUserDevices:]
+ -[RPConnection verifyIdentityProof:accountAltDSID:]
+ -[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]
+ -[RPSiriSession _triggerInfoRequest]
+ -[RPSiriSession setTriggerDurationMs:]
+ -[RPSiriSession setTriggeredPhrase:]
+ -[RPSiriSession setTwoShotFeedbackDelaySec:]
+ -[RPSiriSession triggerDurationMs]
+ -[RPSiriSession triggeredPhrase]
+ -[RPSiriSession twoShotFeedbackDelaySec]
+ GCC_except_table10
+ GCC_except_table280
+ GCC_except_table291
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table95
+ _OBJC_CLASS_$_NSScanner
+ _OBJC_CLASS_$_RPAccessPolicyClient
+ _OBJC_CLASS_$_RPNWTXTUtils
+ _OBJC_IVAR_$_RPAccessPolicyClient._accessPermittedHandler
+ _OBJC_IVAR_$_RPAccessPolicyClient._accessRevokedHandler
+ _OBJC_IVAR_$_RPAccessPolicyClient._devices
+ _OBJC_IVAR_$_RPAccessPolicyClient._dispatchQueue
+ _OBJC_IVAR_$_RPAccessPolicyClient._invalidationHandler
+ _OBJC_IVAR_$_RPAccessPolicyClient._policy
+ _OBJC_IVAR_$_RPAccessPolicyClient._serviceName
+ _OBJC_IVAR_$_RPAccessPolicyClient._state
+ _OBJC_IVAR_$_RPAccessPolicyClient._xpcConnection
+ _OBJC_IVAR_$_RPConnection._multiUserDevices
+ _OBJC_IVAR_$_RPSiriSession._triggerDurationMs
+ _OBJC_IVAR_$_RPSiriSession._triggeredPhrase
+ _OBJC_IVAR_$_RPSiriSession._twoShotFeedbackDelaySec
+ _OBJC_METACLASS_$_RPAccessPolicyClient
+ _OBJC_METACLASS_$_RPNWTXTUtils
+ _RPLinkIsAccountChecked
+ _RPOptionMultiUserDeviceID
+ _TextToSourceVersion
+ __OBJC_$_CLASS_METHODS_RPNWTXTUtils
+ __OBJC_$_INSTANCE_METHODS_RPAccessPolicyClient
+ __OBJC_$_INSTANCE_VARIABLES_RPAccessPolicyClient
+ __OBJC_$_PROP_LIST_RPAccessPolicyClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RPAccessPolicyXPCClientInterface
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RPAccessPolicyXPCServerInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RPAccessPolicyXPCClientInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RPAccessPolicyXPCServerInterface
+ __OBJC_CLASS_PROTOCOLS_$_RPAccessPolicyClient
+ __OBJC_CLASS_RO_$_RPAccessPolicyClient
+ __OBJC_CLASS_RO_$_RPNWTXTUtils
+ __OBJC_LABEL_PROTOCOL_$_RPAccessPolicyXPCClientInterface
+ __OBJC_LABEL_PROTOCOL_$_RPAccessPolicyXPCServerInterface
+ __OBJC_METACLASS_RO_$_RPAccessPolicyClient
+ __OBJC_METACLASS_RO_$_RPNWTXTUtils
+ __OBJC_PROTOCOL_$_RPAccessPolicyXPCClientInterface
+ __OBJC_PROTOCOL_$_RPAccessPolicyXPCServerInterface
+ __OBJC_PROTOCOL_REFERENCE_$_RPAccessPolicyXPCClientInterface
+ __OBJC_PROTOCOL_REFERENCE_$_RPAccessPolicyXPCServerInterface
+ ___33-[RPAccessPolicyClient _xpcSetup]_block_invoke
+ ___33-[RPAccessPolicyClient _xpcSetup]_block_invoke_2
+ ___34-[RPAccessPolicyClient invalidate]_block_invoke
+ ___40+[RPNWTXTUtils statusFlagsForTXTRecord:]_block_invoke
+ ___48-[RPAccessPolicyClient _xpcActivate:completion:]_block_invoke
+ ___48-[RPAccessPolicyClient _xpcActivate:completion:]_block_invoke_2
+ ___62-[RPClient endpointContextForService:trustCircles:completion:]_block_invoke
+ ___62-[RPClient endpointContextForService:trustCircles:completion:]_block_invoke_2
+ ___65-[RPAccessPolicyClient activateWithPolicy:forService:completion:]_block_invoke
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_2
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke_3
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke_2
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e19_B36?0r*8i16r*20Q28lr32l8
+ ___block_descriptor_49_e8_32s40bs_e27_v24?0"NSSet"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e45_v24?0"NSObject<OS_xpc_object>"8"NSError"16ls48l8s32l8s40l8
+ ___block_descriptor_60_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_65_e8_32s40s48bs56r_e25_v20?0B8"CUPairedPeer"12ls32l8s40l8r56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80r_e23_v20?0B8"RPIdentity"12ls32l8s40l8s48l8s56l8s64l8r80l8s72l8
+ ___swift_closure_destructor.115Tm
+ ___swift_closure_destructor.144Tm
+ ___swift_closure_destructor.156Tm
+ ___swift_closure_destructor.188Tm
+ ___swift_closure_destructor.255Tm
+ __sepBackedIdentityEnabled.enabled
+ __xpc_type_dictionary
+ _associated conformance 7Rapport16RPConnectionCoreC17AccountOwnerCheckOSHAASQ
+ _associated conformance So21RPAccountOwnerSourcesVs10SetAlgebraSCSQ
+ _associated conformance So21RPAccountOwnerSourcesVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So21RPAccountOwnerSourcesVs9OptionSetSCSY
+ _associated conformance So21RPAccountOwnerSourcesVs9OptionSetSCs0E7Algebra
+ _gLogCategory_RPAccessPolicyClient
+ _nw_endpoint_copy_dictionary
+ _nw_endpoint_copy_txt_record
+ _nw_endpoint_create_from_dictionary
+ _nw_endpoint_set_txt_record
+ _nw_parameters_copy_dictionary
+ _nw_txt_record_access_key
+ _nw_txt_record_create_dictionary
+ _nw_txt_record_set_key
+ _swift_bridgeObjectRetain_n
+ _swift_deletedMethodError
+ _swift_retain_x28
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic So10RPIdentityC
+ _symbolic So10RPIdentityCSgIeghg_
+ _symbolic So16CUPairingSessionCSgXw
+ _symbolic So16CUPairingSessionCSgXwz_Xx
+ _symbolic _____ 7Rapport16RPConnectionCoreC17AccountOwnerCheckO
+ _symbolic _____ So21RPAccountOwnerSourcesV
+ _symbolic _____Sg 7Rapport16RPConnectionCoreC17AccountOwnerCheckO
+ _symbolic yySo10RPIdentityCSgYbccSg
+ _type_layout_string So21RPAccountOwnerSourcesV
- -[RPConnection _requestIDLogLevel:chatty:]
- GCC_except_table278
- GCC_except_table39
- GCC_except_table68
- GCC_except_table70
- GCC_except_table91
- _OBJC_IVAR_$_RPConnection._identityVerified
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.143Tm
- ___swift_closure_destructor.175Tm
- ___swift_closure_destructor.242Tm
- ___swift_closure_destructor.250Tm
```
