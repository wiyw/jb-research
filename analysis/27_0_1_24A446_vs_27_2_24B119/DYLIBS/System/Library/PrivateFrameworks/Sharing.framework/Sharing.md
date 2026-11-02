## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

```diff

-2131.10.1.2.11
-  __TEXT.__text: 0x39906c
-  __TEXT.__objc_methlist: 0x1521c
-  __TEXT.__const: 0x25634
-  __TEXT.__cstring: 0x3b535
-  __TEXT.__gcc_except_tab: 0x35f0
-  __TEXT.__oslogstring: 0xc2d3
+2131.21.31.2.5
+  __TEXT.__text: 0x3ac358
+  __TEXT.__objc_methlist: 0x154ac
+  __TEXT.__const: 0x26704
+  __TEXT.__cstring: 0x3bc05
+  __TEXT.__gcc_except_tab: 0x3660
+  __TEXT.__oslogstring: 0xc97b
   __TEXT.__dlopen_cstrs: 0x687
   __TEXT.__ustring: 0xf0
-  __TEXT.__swift5_typeref: 0x97bc
-  __TEXT.__constg_swiftt: 0x81cc
-  __TEXT.__swift5_reflstr: 0x43e2
-  __TEXT.__swift5_fieldmd: 0x7b08
+  __TEXT.__swift5_typeref: 0x9b7e
+  __TEXT.__constg_swiftt: 0x84ec
+  __TEXT.__swift5_reflstr: 0x4a22
+  __TEXT.__swift5_fieldmd: 0x7fe8
   __TEXT.__swift5_builtin: 0x230
-  __TEXT.__swift5_assocty: 0x1280
-  __TEXT.__swift5_capture: 0x32f8
-  __TEXT.__swift5_protos: 0x28
-  __TEXT.__swift5_proto: 0x1f44
-  __TEXT.__swift5_types: 0xa8c
-  __TEXT.__swift_as_entry: 0x4b8
-  __TEXT.__swift_as_ret: 0x498
-  __TEXT.__swift_as_cont: 0xcc8
+  __TEXT.__swift5_assocty: 0x1410
+  __TEXT.__swift5_capture: 0x33e8
+  __TEXT.__swift5_protos: 0x2c
+  __TEXT.__swift5_proto: 0x2030
+  __TEXT.__swift5_types: 0xad0
+  __TEXT.__swift_as_entry: 0x4c8
+  __TEXT.__swift_as_ret: 0x4a8
+  __TEXT.__swift_as_cont: 0xd00
   __TEXT.__swift5_mpenum: 0xd0
-  __TEXT.__unwind_info: 0xf0a0
-  __TEXT.__eh_frame: 0x1033c
+  __TEXT.__unwind_info: 0xf650
+  __TEXT.__eh_frame: 0x10664
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7998
-  __DATA_CONST.__objc_classlist: 0x9d0
+  __DATA_CONST.__const: 0x7b90
+  __DATA_CONST.__objc_classlist: 0x9f0
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x420
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9b98
+  __DATA_CONST.__objc_selrefs: 0x9ca8
   __DATA_CONST.__objc_protorefs: 0x208
   __DATA_CONST.__objc_classrefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x558
   __DATA_CONST.__objc_arraydata: 0x448
-  __DATA_CONST.__got: 0x13f0
-  __AUTH_CONST.__const: 0x1c2e8
-  __AUTH_CONST.__cfstring: 0x137a0
-  __AUTH_CONST.__objc_const: 0x3c840
+  __DATA_CONST.__got: 0x1438
+  __AUTH_CONST.__const: 0x1d188
+  __AUTH_CONST.__cfstring: 0x138c0
+  __AUTH_CONST.__objc_const: 0x3d180
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x660
   __AUTH_CONST.__objc_dictobj: 0x5c8
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x2c08
-  __AUTH_CONST.__auth_ptr: 0x12a8
-  __AUTH.__objc_data: 0x7940
-  __AUTH.__data: 0x4ee0
-  __DATA.__objc_ivar: 0x25b4
-  __DATA.__data: 0xd210
-  __DATA.__bss: 0x3fbd0
+  __AUTH_CONST.__auth_got: 0x2cc8
+  __AUTH_CONST.__auth_ptr: 0x1358
+  __AUTH.__objc_data: 0x3f60
+  __AUTH.__data: 0x3c88
+  __DATA.__objc_ivar: 0x25e8
+  __DATA.__data: 0xd530
+  __DATA.__bss: 0x41470
   __DATA.__common: 0x160
-  __DATA_DIRTY.__objc_data: 0x1080
-  __DATA_DIRTY.__data: 0x300
+  __DATA_DIRTY.__objc_data: 0x4c80
+  __DATA_DIRTY.__data: 0x1940
   __DATA_DIRTY.__bss: 0xc8
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24869
-  Symbols:   20537
+  Functions: 25501
+  Symbols:   20725
   CStrings:  0
 
Symbols:
+ +[SFCollaborationRouteEvent eventName]
+ +[SFCollaborationRouteEvent routeCodeForActivityType:]
+ -[NSURL(Sharing) sf_hasSchemeIn:]
+ -[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]
+ -[SFAutoUnlockManager _releasePairingContextForDevice:]
+ -[SFAutoUnlockManager enableAutoUnlockWithDevice:passcodeRef:]
+ -[SFAutoUnlockManager pairingLAContexts]
+ -[SFAutoUnlockNotificationModel authToken]
+ -[SFAutoUnlockNotificationModel setAuthToken:]
+ -[SFCollaborationPerformer _failIfMetadataLoadFailed]
+ -[SFCollaborationPerformer _isOptionsLoadInFlightForItem:]
+ -[SFCollaborationPerformer _performAfterOptionsCheck]
+ -[SFCollaborationPerformer _stopWaitingForOptionsLoad]
+ -[SFCollaborationPerformer _submitRouteEventIfNeededWithOutcome:error:]
+ -[SFCollaborationPerformer _suppressRouteEvent]
+ -[SFCollaborationPerformer dealloc]
+ -[SFCollaborationPerformer didReportRouteEvent]
+ -[SFCollaborationPerformer isWaitingForOptionsLoad]
+ -[SFCollaborationPerformer observable:didChange:]
+ -[SFCollaborationPerformer performStartTicks]
+ -[SFCollaborationPerformer reportCreationFailureWithError:]
+ -[SFCollaborationPerformer routeItemType]
+ -[SFCollaborationPerformer setDidReportRouteEvent:]
+ -[SFCollaborationPerformer setIsWaitingForOptionsLoad:]
+ -[SFCollaborationPerformer setPerformStartTicks:]
+ -[SFCollaborationPerformer setRouteItemType:]
+ -[SFCollaborationRouteEvent .cxx_destruct]
+ -[SFCollaborationRouteEvent activityType]
+ -[SFCollaborationRouteEvent errorCode]
+ -[SFCollaborationRouteEvent errorDomain]
+ -[SFCollaborationRouteEvent eventPayload]
+ -[SFCollaborationRouteEvent hostAppBundleID]
+ -[SFCollaborationRouteEvent itemType]
+ -[SFCollaborationRouteEvent outcome]
+ -[SFCollaborationRouteEvent setActivityType:]
+ -[SFCollaborationRouteEvent setErrorCode:]
+ -[SFCollaborationRouteEvent setErrorDomain:]
+ -[SFCollaborationRouteEvent setHostAppBundleID:]
+ -[SFCollaborationRouteEvent setItemType:]
+ -[SFCollaborationRouteEvent setOutcome:]
+ -[SFCollaborationRouteEvent setWaitMs:]
+ -[SFCollaborationRouteEvent submitEvent]
+ -[SFCollaborationRouteEvent waitMs]
+ GCC_except_table108
+ GCC_except_table109
+ GCC_except_table118
+ GCC_except_table172
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table180
+ GCC_except_table181
+ GCC_except_table58
+ GCC_except_table61
+ GCC_except_table62
+ GCC_except_table72
+ GCC_except_table75
+ GCC_except_table87
+ GCC_except_table90
+ _OBJC_CLASS_$_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ _OBJC_CLASS_$_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ _OBJC_CLASS_$_SFCollaborationRouteEvent
+ _OBJC_IVAR_$_SFAutoUnlockManager._pairingLAContexts
+ _OBJC_IVAR_$_SFAutoUnlockNotificationModel._authToken
+ _OBJC_IVAR_$_SFCollaborationPerformer._didReportRouteEvent
+ _OBJC_IVAR_$_SFCollaborationPerformer._isWaitingForOptionsLoad
+ _OBJC_IVAR_$_SFCollaborationPerformer._performStartTicks
+ _OBJC_IVAR_$_SFCollaborationPerformer._routeItemType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._activityType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._errorCode
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._errorDomain
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._hostAppBundleID
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._itemType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._outcome
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._waitMs
+ _OBJC_METACLASS_$_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ _OBJC_METACLASS_$_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ _OBJC_METACLASS_$_SFCollaborationRouteEvent
+ _SFIsDeviceHomeAccessory
+ _SFIsDeviceHomeAccessory.onceToken
+ _SFIsDeviceHomeAccessory.result
+ _SFShouldPrintSensitiveData
+ _SFShouldPrintSensitiveData.onceToken
+ _SFShouldPrintSensitiveData.sensitive
+ _SFStringForSensitiveData
+ _SFStringsForSensitiveData
+ __CLASS_METHODS_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ __CLASS_METHODS_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ __CLASS_PROPERTIES_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ __CLASS_PROPERTIES_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ __DATA_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ __DATA_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ __DATA__TtC7Sharing19SFAccessReportStore
+ __INSTANCE_METHODS_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ __INSTANCE_METHODS_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ __IVARS__TtC7Sharing19SFAccessReportStore
+ __METACLASS_DATA_SFAirDropInvocationsFetchTTRInactivityNudgeOptOut
+ __METACLASS_DATA_SFAirDropInvocationsSetTTRInactivityNudgeOptOut
+ __METACLASS_DATA__TtC7Sharing19SFAccessReportStore
+ __OBJC_$_CLASS_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_CLASS_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_VARIABLES_SFCollaborationRouteEvent
+ __OBJC_$_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationPerformer
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationRouteEvent
+ __OBJC_CLASS_RO_$_SFCollaborationRouteEvent
+ __OBJC_METACLASS_RO_$_SFCollaborationRouteEvent
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke_2
+ ___54-[SFCollaborationPerformer _stopWaitingForOptionsLoad]_block_invoke
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_2
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_3
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_4
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_5
+ ___SFIsDeviceHomeAccessory_block_invoke
+ ___SFShouldPrintSensitiveData_block_invoke
+ ___block_descriptor_40_e8_32s_e39_B32?0"_SWCollaborationOption"8Q16^B24ls32l8
+ ___swift__destructor.448Tm
+ ___swift_closure_destructor.1067Tm
+ ___swift_closure_destructor.323Tm
+ ___swift_closure_destructor.663Tm
+ ___unnamed_72
+ __xpc_type_array
+ _associated conformance 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLOSHAASQ
+ _associated conformance 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLOs0D3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLOs0D3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing14SFAccessReportVSHAASQ
+ _associated conformance 7Sharing14SFAccessReportVSLAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV0bcD5ErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 7Sharing15TapToRadarDraftV0bcD5ErrorOSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV11DeviceClassOSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV14ClassificationOSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV15AutoDiagnosticsOSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV15ReproducibilityOSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsVSHAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsVs10SetAlgebraAASQ
+ _associated conformance 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsVs9OptionSetAASY
+ _associated conformance 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsVs9OptionSetAAs0J7Algebra
+ _associated conformance 7Sharing15TapToRadarDraftV9ComponentVSHAASQ
+ _associated conformance 7Sharing19SFClientAccessLevelV10CapabilityOSHAASQ
+ _associated conformance 7Sharing19SFClientAccessLevelV10CapabilityOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 7Sharing20SFAirDropInvocationsO27SetTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA10ParametersAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO27SetTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA10ParametersAaFP_Se
+ _associated conformance 7Sharing20SFAirDropInvocationsO27SetTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA8ResponseAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO27SetTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA8ResponseAaFP_Se
+ _associated conformance 7Sharing20SFAirDropInvocationsO29FetchTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA10ParametersAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO29FetchTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA10ParametersAaFP_Se
+ _associated conformance 7Sharing20SFAirDropInvocationsO29FetchTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA8ResponseAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO29FetchTTRInactivityNudgeOptOutCAA22SFXPCInvocableProtocolAA8ResponseAaFP_Se
+ _associated conformance 7Sharing9URLSchemeVSHAASQ
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAA0eF4TypesADP_s01_cd7BuiltineF0
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAAs0cd23ExtendedGraphemeClusterF0
+ _associated conformance 7Sharing9URLSchemeVs33ExpressibleByUnicodeScalarLiteralAA0efG4TypesADP_s01_cd7BuiltinefG0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAA0efgH4TypesADP_s01_cd7BuiltinefgH0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0cd13UnicodeScalarH0
+ _generic environment 7Sharing21URLParameterEncodableRzl
+ _keypath_set.117Tm
+ _os_variant_has_internal_content
+ _swift_getAtKeyPath
+ _symbolic $s7Sharing21URLParameterEncodableP
+ _symbolic $ss26ExpressibleByStringLiteralP
+ _symbolic $ss33ExpressibleByUnicodeScalarLiteralP
+ _symbolic $ss43ExpressibleByExtendedGraphemeClusterLiteralP
+ _symbolic SDySSShy_____GG 7Sharing14SFAccessReportV
+ _symbolic SaySiG
+ _symbolic Say_____G 7Sharing15TapToRadarDraftV11DeviceClassO
+ _symbolic Say_____G 7Sharing19SFClientAccessLevelV10CapabilityO
+ _symbolic Shy_____G 7Sharing14SFAccessReportV
+ _symbolic _____ 7Sharing12URLParameterV
+ _symbolic _____ 7Sharing14SFAccessReportV
+ _symbolic _____ 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLO
+ _symbolic _____ 7Sharing15TapToRadarDraftV
+ _symbolic _____ 7Sharing15TapToRadarDraftV0bcD5ErrorO
+ _symbolic _____ 7Sharing15TapToRadarDraftV11DeviceClassO
+ _symbolic _____ 7Sharing15TapToRadarDraftV14ClassificationO
+ _symbolic _____ 7Sharing15TapToRadarDraftV15AutoDiagnosticsO
+ _symbolic _____ 7Sharing15TapToRadarDraftV15ReproducibilityO
+ _symbolic _____ 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsV
+ _symbolic _____ 7Sharing15TapToRadarDraftV9ComponentV
+ _symbolic _____ 7Sharing19SFAccessReportStoreC
+ _symbolic _____ 7Sharing19SFClientAccessLevelV10CapabilityO
+ _symbolic _____ 7Sharing20SFAirDropInvocationsO27SetTTRInactivityNudgeOptOutC
+ _symbolic _____ 7Sharing20SFAirDropInvocationsO29FetchTTRInactivityNudgeOptOutC
+ _symbolic _____ 7Sharing9SFAirDropO17SenderDiagnosticsO
+ _symbolic _____ 7Sharing9URLSchemeV
+ _symbolic _____Sg 10Foundation12URLQueryItemV
+ _symbolic _____Sg 7Sharing15TapToRadarDraftV14ClassificationO
+ _symbolic _____Sg 7Sharing15TapToRadarDraftV15ReproducibilityO
+ _symbolic _____Sg 7Sharing15TapToRadarDraftV9ComponentV
+ _symbolic _____ySSSgG 7Sharing12URLParameterV
+ _symbolic _____ySSShy_____GG s18_DictionaryStorageC 7Sharing14SFAccessReportV
+ _symbolic _____ySaySSGG 7Sharing12URLParameterV
+ _symbolic _____ySaySiGG 7Sharing12URLParameterV
+ _symbolic _____ySay_____GG 7Sharing12URLParameterV 10Foundation3URLV
+ _symbolic _____ySay_____GG 7Sharing12URLParameterV AA15TapToRadarDraftV11DeviceClassO
+ _symbolic _____ySbG 7Sharing12URLParameterV
+ _symbolic _____ySdG 7Sharing13SFUserDefaultC
+ _symbolic _____ySdG 7Sharing18AirDropUserDefaultC
+ _symbolic _____ySdSg_____G 7Combine19CurrentValueSubjectC s5NeverO
+ _symbolic _____y_____G 7Sharing12URLParameterV AA15TapToRadarDraftV15AutoDiagnosticsO
+ _symbolic _____y_____G 7Sharing12URLParameterV AA15TapToRadarDraftV22RemoteDeviceSelectionsV
+ _symbolic _____y_____G s11_SetStorageC 7Sharing14SFAccessReportV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing14SFAccessReportV10CodingKeys33_3BDD3C3E45FF7210A0FA925F88A08251LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation12URLQueryItemV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7Sharing19SFClientAccessLevelV10CapabilityO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s4Int8V
+ _symbolic _____y_____SgG 7Sharing12URLParameterV 10Foundation4DateV
+ _symbolic _____y_____SgG 7Sharing12URLParameterV AA15TapToRadarDraftV14ClassificationO
+ _symbolic _____y_____SgG 7Sharing12URLParameterV AA15TapToRadarDraftV15ReproducibilityO
+ _sysctlbyname
+ _type_layout_string 7Sharing14SFAccessReportV
+ _type_layout_string 7Sharing15TapToRadarDraftV22RemoteDeviceSelectionsV
+ _type_layout_string 7Sharing15TapToRadarDraftV9ComponentV
+ _type_layout_string 7Sharing9URLSchemeV
+ _xpc_type_get_name
- GCC_except_table105
- GCC_except_table106
- GCC_except_table112
- GCC_except_table166
- GCC_except_table168
- GCC_except_table170
- GCC_except_table171
- GCC_except_table175
- GCC_except_table178
- GCC_except_table179
- GCC_except_table38
- GCC_except_table40
- GCC_except_table65
- GCC_except_table73
- GCC_except_table81
- GCC_except_table84
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_2
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_3
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_4
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_5
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_6
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke_2
- ___swift__destructor.431Tm
- ___swift_closure_destructor.1003Tm
- ___swift_closure_destructor.254Tm
- ___swift_closure_destructor.599Tm
- ___unnamed_68
- _keypath_set.105Tm
```
