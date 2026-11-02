## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/VoiceShortcuts`

```diff

-5037.111.0.0.0
-  __TEXT.__text: 0x149f94
-  __TEXT.__objc_methlist: 0x568c
-  __TEXT.__const: 0x6918
+5114.0.8.3.0
+  __TEXT.__text: 0x13f328
+  __TEXT.__objc_methlist: 0x5374
+  __TEXT.__const: 0x6c48
   __TEXT.__dlopen_cstrs: 0x1e1
-  __TEXT.__oslogstring: 0xfd79
-  __TEXT.__swift5_typeref: 0x350b
-  __TEXT.__swift5_fieldmd: 0x1834
-  __TEXT.__constg_swiftt: 0x223c
-  __TEXT.__swift5_reflstr: 0x1541
-  __TEXT.__swift5_builtin: 0x140
-  __TEXT.__swift5_assocty: 0x618
-  __TEXT.__swift5_capture: 0x2ee8
-  __TEXT.__cstring: 0xec22
-  __TEXT.__swift5_proto: 0x410
-  __TEXT.__swift5_types: 0x1f8
+  __TEXT.__oslogstring: 0xe94f
+  __TEXT.__swift5_typeref: 0x35a1
+  __TEXT.__swift5_fieldmd: 0x1888
+  __TEXT.__constg_swiftt: 0x22b4
+  __TEXT.__swift5_reflstr: 0x1551
+  __TEXT.__swift5_builtin: 0x154
+  __TEXT.__swift5_assocty: 0x690
+  __TEXT.__swift5_capture: 0x3180
+  __TEXT.__cstring: 0xe2ba
+  __TEXT.__swift5_proto: 0x448
+  __TEXT.__swift5_types: 0x208
   __TEXT.__swift_as_entry: 0x328
-  __TEXT.__swift_as_ret: 0x344
-  __TEXT.__swift_as_cont: 0x79c
+  __TEXT.__swift_as_ret: 0x324
+  __TEXT.__swift_as_cont: 0x750
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__gcc_except_tab: 0x90c
+  __TEXT.__gcc_except_tab: 0x838
   __TEXT.__ustring: 0x44
-  __TEXT.__unwind_info: 0x4f88
-  __TEXT.__eh_frame: 0x8dd8
+  __TEXT.__unwind_info: 0x4e90
+  __TEXT.__eh_frame: 0x8980
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1e68
-  __DATA_CONST.__objc_classlist: 0x310
-  __DATA_CONST.__objc_catlist: 0x110
+  __DATA_CONST.__const: 0x1d10
+  __DATA_CONST.__objc_classlist: 0x320
+  __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4880
+  __DATA_CONST.__objc_selrefs: 0x4478
   __DATA_CONST.__objc_protorefs: 0xd0
-  __DATA_CONST.__objc_superrefs: 0x180
+  __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x1a28
-  __AUTH_CONST.__const: 0xa5d8
-  __AUTH_CONST.__cfstring: 0x3f40
-  __AUTH_CONST.__objc_const: 0xa0d8
+  __DATA_CONST.__got: 0x1888
+  __AUTH_CONST.__const: 0xab88
+  __AUTH_CONST.__cfstring: 0x3e20
+  __AUTH_CONST.__objc_const: 0x9d98
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2110
-  __AUTH_CONST.__auth_ptr: 0xa70
-  __AUTH.__objc_data: 0x8b0
-  __AUTH.__data: 0x1400
-  __DATA.__objc_ivar: 0x394
-  __DATA.__data: 0x2800
-  __DATA.__bss: 0x46c0
-  __DATA.__common: 0x10
-  __DATA_DIRTY.__objc_data: 0x13c0
-  __DATA_DIRTY.__data: 0x2558
+  __AUTH_CONST.__auth_got: 0x20b8
+  __AUTH_CONST.__auth_ptr: 0xa58
+  __AUTH.__objc_data: 0x830
+  __AUTH.__data: 0x11e0
+  __DATA.__objc_ivar: 0x3a4
+  __DATA.__data: 0x2650
+  __DATA.__bss: 0x47a0
+  __DATA.__common: 0x18
+  __DATA_DIRTY.__objc_data: 0x1490
+  __DATA_DIRTY.__data: 0x2a20
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0x2e40
+  __DATA_DIRTY.__bss: 0x3450
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/AppIntents.framework/AppIntents
   - /System/Library/Frameworks/CloudKit.framework/CloudKit

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8058
-  Symbols:   5418
+  Functions: 8053
+  Symbols:   5275
   CStrings:  0
 
Symbols:
+ -[VCCKShortcutSyncService setSyncLogUploadDebouncer:]
+ -[VCCKShortcutSyncService syncLogUploadDebouncer]
+ -[VCCKShortcutSyncService uploadSyncLogsFromDebouncer:]
+ -[WFTriggerEventRunner completeInFlightRunForTestingWithClient:error:cancelled:]
+ -[WFTriggerEventRunner handleFinishedRunForClient:error:cancelled:]
+ -[WFTriggerEventRunner init]
+ -[WFTriggerEventRunner numberOfRunsInFlight]
+ -[WFTriggerEventRunner registerInFlightRunForTestingWithClient:triggerKey:workflowIdentifier:startDate:]
+ -[WFTriggerEventRunner takeInFlightRunForClient:]
+ -[WFTriggerInFlightRun .cxx_destruct]
+ -[WFTriggerInFlightRun client]
+ -[WFTriggerInFlightRun eventInfo]
+ -[WFTriggerInFlightRun initWithClient:triggerKey:workflowIdentifier:eventInfo:runEvent:startDate:]
+ -[WFTriggerInFlightRun runEvent]
+ -[WFTriggerInFlightRun startDate]
+ -[WFTriggerInFlightRun triggerKey]
+ -[WFTriggerInFlightRun workflowIdentifier]
+ -[WFTriggerNotificationScheduler isHiddenTriggerKey:]
+ GCC_except_table1051
+ GCC_except_table1068
+ GCC_except_table1072
+ GCC_except_table1098
+ GCC_except_table1157
+ GCC_except_table1163
+ GCC_except_table1165
+ GCC_except_table1168
+ GCC_except_table1169
+ GCC_except_table1174
+ GCC_except_table1225
+ GCC_except_table1271
+ GCC_except_table1275
+ GCC_except_table1289
+ GCC_except_table1294
+ GCC_except_table1304
+ GCC_except_table1310
+ GCC_except_table1342
+ GCC_except_table1346
+ GCC_except_table1364
+ GCC_except_table1368
+ GCC_except_table1382
+ GCC_except_table1384
+ GCC_except_table1388
+ GCC_except_table1406
+ GCC_except_table1409
+ GCC_except_table1423
+ GCC_except_table231
+ GCC_except_table303
+ GCC_except_table325
+ GCC_except_table389
+ GCC_except_table411
+ GCC_except_table494
+ GCC_except_table575
+ GCC_except_table576
+ GCC_except_table589
+ GCC_except_table600
+ GCC_except_table629
+ GCC_except_table788
+ GCC_except_table89
+ GCC_except_table90
+ GCC_except_table922
+ GCC_except_table948
+ GCC_except_table954
+ GCC_except_table956
+ GCC_except_table974
+ _OBJC_CLASS_$_WFDateComponentsPickerParameter
+ _OBJC_CLASS_$_WFDateComponentsSubstitutableState
+ _OBJC_CLASS_$_WFTriggerInFlightRun
+ _OBJC_IVAR_$_VCCKShortcutSyncService._syncLogUploadDebouncer
+ _OBJC_IVAR_$_WFTriggerEventRunner._inFlightRuns
+ _OBJC_IVAR_$_WFTriggerEventRunner._lock
+ _OBJC_IVAR_$_WFTriggerInFlightRun._client
+ _OBJC_IVAR_$_WFTriggerInFlightRun._eventInfo
+ _OBJC_IVAR_$_WFTriggerInFlightRun._runEvent
+ _OBJC_IVAR_$_WFTriggerInFlightRun._startDate
+ _OBJC_IVAR_$_WFTriggerInFlightRun._triggerKey
+ _OBJC_IVAR_$_WFTriggerInFlightRun._workflowIdentifier
+ _OBJC_METACLASS_$_WFTriggerInFlightRun
+ _OUTLINED_FUNCTION_354
+ _OUTLINED_FUNCTION_355
+ _OUTLINED_FUNCTION_356
+ _OUTLINED_FUNCTION_357
+ _OUTLINED_FUNCTION_358
+ _WFNotificationUserInfoForTriggerKeys
+ _WFRunnerDefaultMaxRunTimeSeconds
+ _WFWorkflowRunOutcomeForRunError
+ __DATA__TtCC14VoiceShortcuts18WFTriggerRegistrar31ResourceAvailabilityEventSource
+ __INSTANCE_METHODS__TtCC14VoiceShortcuts18WFTriggerRegistrar31ResourceAvailabilityEventSource
+ __IVARS__TtCC14VoiceShortcuts18WFTriggerRegistrar31ResourceAvailabilityEventSource
+ __METACLASS_DATA__TtCC14VoiceShortcuts18WFTriggerRegistrar31ResourceAvailabilityEventSource
+ __OBJC_$_INSTANCE_METHODS_WFTriggerInFlightRun
+ __OBJC_$_INSTANCE_VARIABLES_WFTriggerInFlightRun
+ __OBJC_$_PROP_LIST_WFTriggerInFlightRun
+ __OBJC_CLASS_RO_$_WFTriggerInFlightRun
+ __OBJC_METACLASS_RO_$_WFTriggerInFlightRun
+ ___55-[VCCKShortcutSyncService uploadSyncLogsFromDebouncer:]_block_invoke
+ ___block_descriptor_40_e8_32s_e20_v20?0B8"NSError"12ls32l8
+ ___swift_closure_destructor.198Tm
+ _associated conformance 14VoiceShortcuts18WFTriggerRegistrarC31ResourceAvailabilityEventSourceCAA06DaemongH0AA0G0AaFP_AA0iG0
+ _associated conformance 14VoiceShortcuts18WFTriggerRegistrarC42ResourceAvailabilityChangedEventDescriptorVAA06DaemonhI0AA0H0AaFP_AA0jH0
+ _associated conformance 14VoiceShortcuts18WFTriggerRegistrarC42ResourceAvailabilityChangedEventDescriptorVSHAASQ
+ _associated conformance SC11VCErrorCodeLeV10Foundation13CustomNSErrorSCs5Error
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_AC06_ErrorB8Protocol
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_SY
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomF0
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC26_ObjectiveCBridgeableError
+ _associated conformance SC11VCErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC11VCErrorCodeLeV10Foundation26_ObjectiveCBridgeableErrorSCs0F0
+ _associated conformance SC11VCErrorCodeLeVSHSCSQ
+ _associated conformance So11VCErrorCodeV10Foundation06_ErrorB8ProtocolSC01_D4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So11VCErrorCodeV10Foundation06_ErrorB8ProtocolSCSQ
+ _swift_initStaticObject
+ _symbolic SDySo19WFUnifiedTriggerKeyC_____G 11WorkflowKit12WFNewTriggerC
+ _symbolic Say_____G 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic SbIegd_
+ _symbolic _____ 11WorkflowKit31TriggerRegistrationUpdateReasonO
+ _symbolic _____ 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
+ _symbolic _____ 14VoiceShortcuts18WFTriggerRegistrarC31ResourceAvailabilityEventSourceC
+ _symbolic _____ 14VoiceShortcuts18WFTriggerRegistrarC32ResourceAvailabilityChangedEventV
+ _symbolic _____ 14VoiceShortcuts18WFTriggerRegistrarC42ResourceAvailabilityChangedEventDescriptorV
+ _symbolic _____ SC11VCErrorCodeLeV
+ _symbolic _____ So11VCErrorCodeV
+ _symbolic _____Iegd_ s5Int32V
+ _symbolic _____Ieghn_ 14VoiceShortcuts18WFTriggerRegistrarC32ResourceAvailabilityChangedEventV
+ _symbolic _____Iegr_ 11WorkflowKit31TriggerRegistrationUpdateReasonO
+ _symbolic _____Iegr_ s5Int32V
+ _symbolic _____Sg 10Foundation14DateComponentsV
+ _symbolic __________Iegnr_ 14VoiceShortcuts18WFTriggerRegistrarC32ResourceAvailabilityChangedEventV AA05EmptyH0V
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s17_NativeDictionaryV 11WorkflowKit12WFNewTriggerC
+ _symbolic _____ySo19WFUnifiedTriggerKeyC_____G s18_DictionaryStorageC 11WorkflowKit12WFNewTriggerC
+ _symbolic _____y______G 14VoiceShortcuts17DaemonEventStreamV0D6SourceC AA18WFTriggerRegistrarC027ResourceAvailabilityChangedD10DescriptorV
+ _symbolic _____y______GSgXw 14VoiceShortcuts17DaemonEventStreamV0D6SourceC AA18WFTriggerRegistrarC027ResourceAvailabilityChangedD10DescriptorV
+ _symbolic _____y_____y______GG 14VoiceShortcuts14EventDebouncerC AA06DaemonC6StreamV0C6SourceC AA18WFTriggerRegistrarC027ResourceAvailabilityChangedC10DescriptorV
+ _symbolic _____y_____y______GGSgXw 14VoiceShortcuts14EventDebouncerC AA06DaemonC6StreamV0C6SourceC AA18WFTriggerRegistrarC027ResourceAvailabilityChangedC10DescriptorV
+ _type_layout_string 14VoiceShortcuts18WFTriggerRegistrarC42ResourceAvailabilityChangedEventDescriptorV
- +[WFBluetoothTrigger(BiomeContext) stream]
- +[WFTrigger(BiomeContext) unregisterContextSyncClient]
- +[WFWalletTransactionTrigger(BiomeContext) registerContextSyncClient]
- +[WFWalletTransactionTrigger(BiomeContext) unregisterContextSyncClient]
- +[WFWorkoutTrigger(BiomeContext) registerContextSyncClient]
- +[WFWorkoutTrigger(BiomeContext) unregisterContextSyncClient]
- -[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]
- -[VCVoiceShortcutManagerAccessWrapper getConfiguredTriggerForTriggerID:completion:]
- -[VCVoiceShortcutManagerAccessWrapper getConfiguredTriggersForWorkflowID:completion:]
- -[VCVoiceShortcutManagerAccessWrapper getVoiceShortcutsForAppWithBundleIdentifier:completion:]
- -[VCXPCServer triggerManager]
- -[WFAirplaneModeTrigger(BiomeContext) publisherWithScheduler:]
- -[WFAirplaneModeTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFAlarmTrigger(BiomeContext) alarmEventForCurrentAlarmState]
- -[WFAlarmTrigger(BiomeContext) publisherWithScheduler:]
- -[WFAlarmTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFAppInFocusTrigger(BiomeContext) publisherWithScheduler:]
- -[WFAppInFocusTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFBatteryLevelTrigger(BiomeConext) publisherWithScheduler:]
- -[WFBatteryLevelTrigger(BiomeConext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFBluetoothTrigger(BiomeContext) getPreviousStateWithDeviceName:currentStateEvent:completionHandler:]
- -[WFBluetoothTrigger(BiomeContext) publisherWithScheduler:]
- -[WFBluetoothTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFCarPlayConnectionTrigger(BiomeContext) publisherWithScheduler:]
- -[WFCarPlayConnectionTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFExternalDisplayTrigger(BiomeContext) publisherWithScheduler:]
- -[WFExternalDisplayTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFKeyboardTrigger(BiomeContext) publisherWithScheduler:]
- -[WFKeyboardTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFLowPowerModeTrigger(BiomeContext) publisherWithScheduler:]
- -[WFLowPowerModeTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFMultiTaskingArrangementTrigger(BiomeContext) publisherWithScheduler:]
- -[WFMultiTaskingArrangementTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFNFCTrigger(BiomeContext) publisherWithScheduler:]
- -[WFNFCTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFNotificationTrigger(BiomeContext) publisherWithScheduler:]
- -[WFNotificationTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFPlugInTrigger(BiomeContext) publisherWithScheduler:]
- -[WFPlugInTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFScreenshotTrigger(BiomeContext) publisherWithScheduler:]
- -[WFScreenshotTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFSoundRecognitionTrigger(BiomeContext) publisherWithScheduler:]
- -[WFSoundRecognitionTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFStageManagerTrigger(BiomeContext) publisherWithScheduler:]
- -[WFStageManagerTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFTrigger(BiomeContext) hasRemotePublisher]
- -[WFTrigger(BiomeContext) publisherWithScheduler:]
- -[WFTrigger(BiomeContext) remotePublisherWithScheduler:]
- -[WFTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFTriggerEventRunner inProgressEventInfo]
- -[WFTriggerEventRunner inProgressRunEvent]
- -[WFTriggerEventRunner inProgressRunnerClient]
- -[WFTriggerEventRunner inProgressTriggerKey]
- -[WFTriggerEventRunner setInProgressEventInfo:]
- -[WFTriggerEventRunner setInProgressRunEvent:]
- -[WFTriggerEventRunner setInProgressRunnerClient:]
- -[WFTriggerEventRunner setInProgressTriggerKey:]
- -[WFUserFocusActivityTrigger(BiomeContext) publisherWithScheduler:]
- -[WFUserFocusActivityTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFWalletTransactionTrigger(BiomeContext) hasRemotePublisher]
- -[WFWalletTransactionTrigger(BiomeContext) isPassIdentifierValid:]
- -[WFWalletTransactionTrigger(BiomeContext) publisherWithScheduler:]
- -[WFWalletTransactionTrigger(BiomeContext) remotePublisherWithScheduler:]
- -[WFWalletTransactionTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFWalletTransactionTrigger(BiomeContext) transactionIdentifierWithEvent:]
- -[WFWifiTrigger(BiomeContext) publisherWithScheduler:]
- -[WFWifiTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- -[WFWorkoutTrigger(BiomeContext) hasRemotePublisher]
- -[WFWorkoutTrigger(BiomeContext) publisherWithScheduler:]
- -[WFWorkoutTrigger(BiomeContext) remotePublisherWithScheduler:]
- -[WFWorkoutTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]
- GCC_except_table1011
- GCC_except_table1017
- GCC_except_table1019
- GCC_except_table1037
- GCC_except_table1115
- GCC_except_table1132
- GCC_except_table1136
- GCC_except_table1162
- GCC_except_table1224
- GCC_except_table1230
- GCC_except_table1232
- GCC_except_table1235
- GCC_except_table1236
- GCC_except_table1241
- GCC_except_table1293
- GCC_except_table1339
- GCC_except_table1343
- GCC_except_table1357
- GCC_except_table1362
- GCC_except_table1372
- GCC_except_table1378
- GCC_except_table1410
- GCC_except_table1414
- GCC_except_table1432
- GCC_except_table1436
- GCC_except_table1450
- GCC_except_table1452
- GCC_except_table1456
- GCC_except_table1474
- GCC_except_table1477
- GCC_except_table1491
- GCC_except_table228
- GCC_except_table299
- GCC_except_table313
- GCC_except_table334
- GCC_except_table342
- GCC_except_table369
- GCC_except_table391
- GCC_except_table454
- GCC_except_table473
- GCC_except_table556
- GCC_except_table567
- GCC_except_table638
- GCC_except_table639
- GCC_except_table652
- GCC_except_table663
- GCC_except_table692
- GCC_except_table78
- GCC_except_table83
- GCC_except_table851
- GCC_except_table985
- _HealthKitLibrary.sLib
- _HealthKitLibrary.sOnce
- _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
- _OBJC_CLASS_$_BMAccessibilitySoundDetection
- _OBJC_CLASS_$_BMAppInFocus
- _OBJC_CLASS_$_BMCarPlayConnected
- _OBJC_CLASS_$_BMClockAlarm
- _OBJC_CLASS_$_BMContextSyncWalletTransaction
- _OBJC_CLASS_$_BMContextSyncWorkout
- _OBJC_CLASS_$_BMDeviceAirplaneMode
- _OBJC_CLASS_$_BMDeviceBatteryLevel
- _OBJC_CLASS_$_BMDeviceBluetooth
- _OBJC_CLASS_$_BMDeviceLowPowerMode
- _OBJC_CLASS_$_BMDeviceNFCTag
- _OBJC_CLASS_$_BMDevicePluggedIn
- _OBJC_CLASS_$_BMDeviceWiFi
- _OBJC_CLASS_$_BMHealthWorkout
- _OBJC_CLASS_$_BMNotificationDelivery
- _OBJC_CLASS_$_BMPublisherOptions
- _OBJC_CLASS_$_BMScreenshotsScreenshot
- _OBJC_CLASS_$_BMSpringBoardDisplayConnected
- _OBJC_CLASS_$_BMSpringBoardKeyboard
- _OBJC_CLASS_$_BMSpringBoardMultiTaskingArrangement
- _OBJC_CLASS_$_BMUserFocusModeComputed
- _OBJC_CLASS_$_BMWalletTransaction
- _OBJC_CLASS_$_ContextSyncClient
- _OBJC_CLASS_$_WFAXSDSettings
- _OBJC_CLASS_$_WFAirplaneModeTrigger
- _OBJC_CLASS_$_WFAlarmTrigger
- _OBJC_CLASS_$_WFAppInFocusTrigger
- _OBJC_CLASS_$_WFArriveLocationTrigger
- _OBJC_CLASS_$_WFBatteryLevelTrigger
- _OBJC_CLASS_$_WFBluetoothTrigger
- _OBJC_CLASS_$_WFCarPlayConnectionTrigger
- _OBJC_CLASS_$_WFConfiguredTrigger
- _OBJC_CLASS_$_WFConfiguredTriggerRecord
- _OBJC_CLASS_$_WFDateSubstitutableState
- _OBJC_CLASS_$_WFExternalDisplayTrigger
- _OBJC_CLASS_$_WFKeyboardTrigger
- _OBJC_CLASS_$_WFLeaveLocationTrigger
- _OBJC_CLASS_$_WFLocationTrigger
- _OBJC_CLASS_$_WFLowPowerModeTrigger
- _OBJC_CLASS_$_WFMultiTaskingArrangementTrigger
- _OBJC_CLASS_$_WFNFCTrigger
- _OBJC_CLASS_$_WFNotificationTrigger
- _OBJC_CLASS_$_WFPlugInTrigger
- _OBJC_CLASS_$_WFScreenshotTrigger
- _OBJC_CLASS_$_WFSoundRecognitionTrigger
- _OBJC_CLASS_$_WFStageManagerTrigger
- _OBJC_CLASS_$_WFTimeOfDayTrigger
- _OBJC_CLASS_$_WFTriggerManager
- _OBJC_CLASS_$_WFUserFocusActivityTrigger
- _OBJC_CLASS_$_WFWalletTransactionTrigger
- _OBJC_CLASS_$_WFWifiTrigger
- _OBJC_CLASS_$_WFWorkoutTrigger
- _OBJC_IVAR_$_VCXPCServer._triggerManager
- _OBJC_IVAR_$_WFTriggerEventRunner._inProgressEventInfo
- _OBJC_IVAR_$_WFTriggerEventRunner._inProgressRunEvent
- _OBJC_IVAR_$_WFTriggerEventRunner._inProgressRunnerClient
- _OBJC_IVAR_$_WFTriggerEventRunner._inProgressTriggerKey
- _WFAllWalletTransactionMerchantTypes
- _WFSystemNotificationIdentifierIsForTrigger
- _WFTriggerIDsToDisableNotificationUserInfoFromTriggers
- __OBJC_$_CATEGORY_CLASS_METHODS_WFBluetoothTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_CLASS_METHODS_WFTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_CLASS_METHODS_WFWalletTransactionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_CLASS_METHODS_WFWorkoutTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFAirplaneModeTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFAlarmTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFAppInFocusTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFBatteryLevelTrigger_$_BiomeConext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFBluetoothTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFCarPlayConnectionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFExternalDisplayTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFKeyboardTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFLowPowerModeTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFMultiTaskingArrangementTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFNFCTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFNotificationTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFPlugInTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFScreenshotTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFSoundRecognitionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFStageManagerTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFUserFocusActivityTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFWalletTransactionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFWifiTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_INSTANCE_METHODS_WFWorkoutTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFAirplaneModeTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFAlarmTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFAppInFocusTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFBatteryLevelTrigger_$_BiomeConext
- __OBJC_$_CATEGORY_WFBluetoothTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFCarPlayConnectionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFExternalDisplayTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFKeyboardTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFLowPowerModeTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFMultiTaskingArrangementTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFNFCTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFNotificationTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFPlugInTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFScreenshotTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFSoundRecognitionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFStageManagerTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFUserFocusActivityTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFWalletTransactionTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFWifiTrigger_$_BiomeContext
- __OBJC_$_CATEGORY_WFWorkoutTrigger_$_BiomeContext
- ___100-[WFSoundRecognitionTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]_block_invoke
- ___101-[WFWalletTransactionTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]_block_invoke
- ___103-[WFBluetoothTrigger(BiomeContext) getPreviousStateWithDeviceName:currentStateEvent:completionHandler:]_block_invoke
- ___103-[WFBluetoothTrigger(BiomeContext) getPreviousStateWithDeviceName:currentStateEvent:completionHandler:]_block_invoke_2
- ___56-[VCMetricSubmitter numberOfPersonalAutomationsEnabled:]_block_invoke
- ___87-[VCVoiceShortcutManagerAccessWrapper resetAutomationConfirmationStatusWithCompletion:]_block_invoke
- ___93-[WFBluetoothTrigger(BiomeContext) shouldFireInResponseToEvent:triggerIdentifier:completion:]_block_invoke
- ___95-[WFBatteryLevelTrigger(BiomeConext) shouldFireInResponseToEvent:triggerIdentifier:completion:]_block_invoke
- ___95-[WFBatteryLevelTrigger(BiomeConext) shouldFireInResponseToEvent:triggerIdentifier:completion:]_block_invoke_2
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke_2
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke_3
- ___HealthKitLibrary_block_invoke
- ___block_descriptor_32_e23_v16?0"BPSCompletion"8l
- ___block_descriptor_32_e40_v24?0"BPSCompletion"8"<BMBookmark>"16l
- ___block_descriptor_40_e8_32r_e18_16?0"NSString"8lr32l8
- ___block_descriptor_40_e8_32r_e22_v16?0"BMStoreEvent"8lr32l8
- ___block_descriptor_40_e8_32r_e36_v32?0"WFConfiguredTrigger"8Q16^B24lr32l8
- ___block_descriptor_40_e8_32s_e50_v32?0"NSString"8Q16?<v?"NSArray""NSError">24ls32l8
- ___block_descriptor_48_e8_32s40s_e36_v32?0"WFConfiguredTrigger"8Q16^B24ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e27_v16?0"BMDeviceBluetooth"8ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40s48r56r_e22_B16?0"BMStoreEvent"8lr48l8s32l8r56l8s40l8
- ___block_descriptor_67_e8_32s40bs48r56r_e22_v16?0"NSDictionary"8ls40l8r48l8s32l8r56l8
- ___kCFBooleanFalse
- ___swift_closure_destructor.155Tm
- ___swift_project_boxed_opaque_existential_0Tm
- _associated conformance 14VoiceShortcuts22TriggerConversionErrorO10Foundation09LocalizedE0AAs0E0
- _init_HKWorkoutActivityNameForActivityType
- _softLink_HKWorkoutActivityNameForActivityType
- _symbolic SccySo19WFConfiguredTriggerC_So19WFWorkflowReferenceCt______pG s5ErrorP
- _symbolic SccySo19WFConfiguredTriggerC______pG s5ErrorP
- _symbolic So16WFTriggerManagerCSgSg
- _symbolic _____ 14VoiceShortcuts22TriggerConversionErrorO
- _symbolic _____ 19VoiceShortcutClient20ActionParameterValueV
- _symbolic _____Sg 19VoiceShortcutClient16ScheduledTriggerV
- _symbolic _____Sg 19VoiceShortcutClient16TimeOfDayTriggerV
- _symbolic _____Sg 19VoiceShortcutClient21LegacyLocationTriggerV9TimeRangeV
- _symbolic ___________t 19VoiceShortcutClient11TriggerTypeO AA013LegacyCodableD6ActionO
- _symbolic ______p 11WorkflowKit17SchedulingRequestP
- _symbolic _____ySay_____GG 19VoiceShortcutClient0aB17ResponseWithValueO AA16ScheduledTriggerV
- _symbolic _____ySiG s23_ContiguousArrayStorageC
- _symbolic _____y_____G 19VoiceShortcutClient0aB17ResponseWithValueO AA16ScheduledTriggerV
- _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 19VoiceShortcutClient16ScheduledTriggerV
- _symbolic _____y_____SgG 19VoiceShortcutClient0aB17ResponseWithValueO AA16ScheduledTriggerV
- _type_layout_string 14VoiceShortcuts22TriggerConversionErrorO
```
