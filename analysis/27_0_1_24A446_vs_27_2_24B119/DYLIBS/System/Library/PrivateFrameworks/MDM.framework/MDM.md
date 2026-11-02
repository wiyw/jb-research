## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

```diff

-113.2.5.0.0
-  __TEXT.__text: 0x55554
-  __TEXT.__objc_methlist: 0x42d4
-  __TEXT.__const: 0x1c2
-  __TEXT.__gcc_except_tab: 0xf08
-  __TEXT.__cstring: 0x532d
-  __TEXT.__oslogstring: 0x70a5
+113.40.20.0.0
+  __TEXT.__text: 0x565fc
+  __TEXT.__objc_methlist: 0x440c
+  __TEXT.__const: 0x1aa
+  __TEXT.__gcc_except_tab: 0xf40
+  __TEXT.__cstring: 0x5484
+  __TEXT.__oslogstring: 0x734f
   __TEXT.__dlopen_cstrs: 0x55
   __TEXT.__swift5_typeref: 0x3c
   __TEXT.__swift5_capture: 0x68
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__unwind_info: 0x12c0
+  __TEXT.__unwind_info: 0x1308
   __TEXT.__eh_frame: 0x178
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1eb8
-  __DATA_CONST.__objc_classlist: 0x1a0
+  __DATA_CONST.__const: 0x1f58
+  __DATA_CONST.__objc_classlist: 0x1a8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xb8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3478
+  __DATA_CONST.__objc_selrefs: 0x3530
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x130
   __DATA_CONST.__objc_arraydata: 0x408
-  __DATA_CONST.__got: 0x1230
+  __DATA_CONST.__got: 0x1208
   __AUTH_CONST.__const: 0x630
-  __AUTH_CONST.__cfstring: 0x4bc0
-  __AUTH_CONST.__objc_const: 0x6c58
+  __AUTH_CONST.__cfstring: 0x4c40
+  __AUTH_CONST.__objc_const: 0x6ec0
   __AUTH_CONST.__objc_arrayobj: 0x8d0
   __AUTH_CONST.__objc_intobj: 0x660
-  __AUTH_CONST.__auth_got: 0x7e0
+  __AUTH_CONST.__auth_got: 0x7e8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x638
-  __DATA.__objc_ivar: 0x2ac
+  __AUTH.__objc_data: 0x688
+  __DATA.__objc_ivar: 0x2d0
   __DATA.__data: 0x7f0
   __DATA.__bss: 0x1c0
   __DATA_DIRTY.__objc_data: 0xa28

   - /System/Library/PrivateFrameworks/DMCTools.framework/DMCTools
   - /System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities
   - /System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity
+  - /System/Library/PrivateFrameworks/DeviceRecovery.framework/DeviceRecovery
   - /System/Library/PrivateFrameworks/EmbeddedDataReset.framework/EmbeddedDataReset
   - /System/Library/PrivateFrameworks/EnhancedLogging.framework/EnhancedLogging
   - /System/Library/PrivateFrameworks/FindMyDevice.framework/FindMyDevice

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1687
-  Symbols:   3409
+  Functions: 1725
+  Symbols:   3457
   CStrings:  0
 
Symbols:
+ +[MDMDeviceRecoveryUtilities setEraseAndUpdateRestricted:completionHandler:]
+ +[MDMDeviceRecoveryUtilities shouldManageEraseAndUpdateRestriction]
+ -[MDMMigrationManager _isDeviceEligibleForMigration]
+ -[MDMMigrationManager _queue_clearConfigFetchRetryState]
+ -[MDMMigrationManager _queue_isConfigFetchPending]
+ -[MDMMigrationManager _queue_retryConfigFetchFromReason:backgroundTask:]
+ -[MDMMigrationManager _queue_scheduleConfigFetchRetry]
+ -[MDMMigrationManager _queue_setConfigFetchPending:]
+ -[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]
+ -[MDMMigrationManager configFetchPending]
+ -[MDMMigrationManager configFetchRetryInterval]
+ -[MDMMigrationManager configFetchRetryTask]
+ -[MDMMigrationManager initWithNetworkMonitor:]
+ -[MDMMigrationManager isFetchingConfig]
+ -[MDMMigrationManager networkMonitor]
+ -[MDMMigrationManager retryInfoPlist]
+ -[MDMMigrationManager setConfigFetchPending:]
+ -[MDMMigrationManager setConfigFetchRetryInterval:]
+ -[MDMMigrationManager setConfigFetchRetryTask:]
+ -[MDMMigrationManager setIsFetchingConfig:]
+ -[MDMMigrationManager setNetworkMonitor:]
+ -[MDMMigrationManager setRetryInfoPlist:]
+ -[MDMMigrationManager setWorkerQueue:]
+ -[MDMMigrationManager workerQueue]
+ -[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]
+ -[MDMServerCore _executionQueueErrorFromTransactionHandlingError:assertion:rmAccountID:enrollmentMode:reauthQueue:]
+ -[MDMServerCore _processAccountDrivenUnauthorizedFromTransaction:rmAccountID:reauthQueue:outHandling:]
+ -[MDMServerCore _processUnauthorizedFromTransaction:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]
+ -[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]
+ -[MDMServerCore _updateDeviceRecoveryEraseAndUpdateRestrictionIsMDMConfigurationValid:]
+ -[MDMServerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ -[MDMServerCore hrnPollTask]
+ -[MDMServerCore memberQueueLastAppliedEraseAndUpdateRestriction]
+ -[MDMServerCore setHrnPollTask:]
+ -[MDMServerCore setMemberQueueLastAppliedEraseAndUpdateRestriction:]
+ -[MDMServerCore setTokenUpdateRetryTask:]
+ -[MDMServerCore tokenUpdateRetryTask]
+ -[MDMServerCore(HRN) _hrnBackgroundPollFromTask:]
+ -[MDMServerCore(HRN) _hrnIsRepeatingPollActiveWithInterval:]
+ -[MDMServerCore(HRN) _hrnMemberQueueSetupRepeatingPoll]
+ -[MDMServerCore(HRN) _hrnPollOrScheduleNextPoll]
+ -[MDMServicerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ GCC_except_table145
+ GCC_except_table165
+ GCC_except_table169
+ GCC_except_table179
+ GCC_except_table183
+ GCC_except_table190
+ GCC_except_table198
+ GCC_except_table2
+ GCC_except_table200
+ GCC_except_table201
+ GCC_except_table214
+ GCC_except_table222
+ GCC_except_table237
+ GCC_except_table242
+ GCC_except_table244
+ GCC_except_table25
+ GCC_except_table264
+ GCC_except_table289
+ GCC_except_table299
+ GCC_except_table312
+ GCC_except_table324
+ GCC_except_table328
+ GCC_except_table339
+ GCC_except_table34
+ GCC_except_table343
+ GCC_except_table359
+ GCC_except_table37
+ GCC_except_table45
+ GCC_except_table50
+ GCC_except_table75
+ GCC_except_table93
+ _DMCMigrationErrorDomain
+ _MDMMigrationConfigFetchRetryInfoFilePath
+ _MDMShouldAllowEscrowCreationForPasscode
+ _OBJC_CLASS_$_DMCDeviceEligibility
+ _OBJC_CLASS_$_DeviceRecoveryController
+ _OBJC_CLASS_$_MDMDeviceRecoveryUtilities
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchPending
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchRetryInterval
+ _OBJC_IVAR_$_MDMMigrationManager._configFetchRetryTask
+ _OBJC_IVAR_$_MDMMigrationManager._isFetchingConfig
+ _OBJC_IVAR_$_MDMMigrationManager._networkMonitor
+ _OBJC_IVAR_$_MDMMigrationManager._retryInfoPlist
+ _OBJC_IVAR_$_MDMMigrationManager._workerQueue
+ _OBJC_IVAR_$_MDMServerCore._hrnPollTask
+ _OBJC_IVAR_$_MDMServerCore._memberQueueLastAppliedEraseAndUpdateRestriction
+ _OBJC_IVAR_$_MDMServerCore._tokenUpdateRetryTask
+ _OBJC_METACLASS_$_MDMDeviceRecoveryUtilities
+ __OBJC_$_CLASS_METHODS_MDMDeviceRecoveryUtilities
+ __OBJC_$_INSTANCE_METHODS_MDMServerCore(HRN)
+ __OBJC_CLASS_RO_$_MDMDeviceRecoveryUtilities
+ __OBJC_METACLASS_RO_$_MDMDeviceRecoveryUtilities
+ ___100-[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]_block_invoke
+ ___100-[MDMServerCore _errorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:outHandling:]_block_invoke_2
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke_2
+ ___131-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:outHandling:]_block_invoke_3
+ ___48-[MDMServerCore(HRN) _hrnPollOrScheduleNextPoll]_block_invoke
+ ___49-[MDMServerCore(HRN) _hrnBackgroundPollFromTask:]_block_invoke
+ ___49-[MDMServerCore(HRN) _hrnBackgroundPollFromTask:]_block_invoke_2
+ ___49-[MDMServerCore(HRN) _hrnBackgroundPollFromTask:]_block_invoke_3
+ ___50-[MDMMigrationManager stopMonitoringDEPServerPush]_block_invoke
+ ___54-[MDMMigrationManager _queue_scheduleConfigFetchRetry]_block_invoke
+ ___55-[MDMServerCore(HRN) _hrnMemberQueueSetupRepeatingPoll]_block_invoke
+ ___55-[MDMServerCore(HRN) _hrnMemberQueueSetupRepeatingPoll]_block_invoke_2
+ ___59-[MDMMigrationManager startMonitoringDEPServerPushIfNeeded]_block_invoke
+ ___59-[MDMMigrationManager startMonitoringDEPServerPushIfNeeded]_block_invoke_2
+ ___64-[MDMServerCore _executionQueueScheduleTokenUpdateRetryIfNeeded]_block_invoke
+ ___64-[MDMServerCore _executionQueueScheduleTokenUpdateRetryIfNeeded]_block_invoke_2
+ ___64-[MDMServerCore _executionQueueScheduleTokenUpdateRetryIfNeeded]_block_invoke_3
+ ___76+[MDMDeviceRecoveryUtilities setEraseAndUpdateRestricted:completionHandler:]_block_invoke
+ ___87-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]_block_invoke
+ ___87-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithCompletionHandler:]_block_invoke_2
+ ___87-[MDMServerCore _updateDeviceRecoveryEraseAndUpdateRestrictionIsMDMConfigurationValid:]_block_invoke
+ ___87-[MDMServerCore _updateDeviceRecoveryEraseAndUpdateRestrictionIsMDMConfigurationValid:]_block_invoke_2
+ ___87-[MDMServerCore _updateDeviceRecoveryEraseAndUpdateRestrictionIsMDMConfigurationValid:]_block_invoke_3
+ ___87-[MDMServerCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]_block_invoke
+ ___block_descriptor_40_e8_32s_e34_v16?0"DMCBackgroundTaskWrapper"8ls32l8
+ ___block_descriptor_41_e8_32bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8
+ ___block_descriptor_41_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s48l8s40l8
+ _kMDMDataKey
+ _kMDMEndpointKey
+ _kMDMMessageTypeDeclarativeManagement
- -[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithRetryCount:completionHandler:]
- -[MDMMigrationManager init]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _areAccountsPresentWithAccountTypeIdentifiers:]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _isDeviceWithoutUserData]
- -[MDMRequestTriggerEnhancedLogCollectionCommand(Handler) _isPasscodePresent]
- -[MDMServerCore _backgroundPollFromTask:]
- -[MDMServerCore _httpErrorFromTransaction:assertion:rmAccountID:enrollmentMode:reauthQueue:]
- -[MDMServerCore _memberQueuePollForHRNFromBackgroundTask:]
- -[MDMServerCore _memberQueuePollOrScheduleNextPollForHRNFromBackgroundTask:]
- -[MDMServerCore _memberQueuePollOrScheduleNextPollForHRN]
- -[MDMServerCore _pollOrScheduleNextPollForHRN]
- -[MDMServerCore _pollingFailed]
- -[MDMServerCore _processAccountDrivenUnauthorizedFromTransaction:rmAccountID:reauthQueue:]
- -[MDMServerCore _processUnauthorizedFromTransaction:authParams:rmAccountID:rmAccountUsername:reauthQueue:]
- -[MDMServerCore _scheduleNextPollWithInterval:]
- -[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]
- -[MDMServerCore pollTask]
- -[MDMServerCore setPollTask:]
- -[MDMUserParser _originator]
- GCC_except_table143
- GCC_except_table163
- GCC_except_table167
- GCC_except_table173
- GCC_except_table177
- GCC_except_table184
- GCC_except_table189
- GCC_except_table192
- GCC_except_table194
- GCC_except_table208
- GCC_except_table211
- GCC_except_table216
- GCC_except_table227
- GCC_except_table232
- GCC_except_table24
- GCC_except_table253
- GCC_except_table287
- GCC_except_table294
- GCC_except_table305
- GCC_except_table31
- GCC_except_table318
- GCC_except_table329
- GCC_except_table333
- GCC_except_table344
- GCC_except_table348
- GCC_except_table36
- GCC_except_table364
- GCC_except_table43
- GCC_except_table48
- GCC_except_table73
- GCC_except_table91
- _ACAccountTypeIdentifierAppleAccount
- _ACAccountTypeIdentifierCalDAV
- _ACAccountTypeIdentifierCardDAV
- _ACAccountTypeIdentifierExchange
- _ACAccountTypeIdentifierGmail
- _ACAccountTypeIdentifierHotmail
- _ACAccountTypeIdentifierIMAP
- _ACAccountTypeIdentifierIMAPMail
- _ACAccountTypeIdentifierIMAPNotes
- _ACAccountTypeIdentifierPOP
- _ACAccountTypeIdentifierYahoo
- _ACAccountTypeIdentifieriTunesStore
- _OBJC_IVAR_$_MDMServerCore._pollTask
- __OBJC_$_INSTANCE_METHODS_MDMServerCore
- ___119-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]_block_invoke
- ___119-[MDMServerCore _triggerRefreshTokenForTransaction:authenticator:authParams:rmAccountID:rmAccountUsername:reauthQueue:]_block_invoke_2
- ___41-[MDMServerCore _backgroundPollFromTask:]_block_invoke
- ___41-[MDMServerCore _backgroundPollFromTask:]_block_invoke_2
- ___41-[MDMServerCore _backgroundPollFromTask:]_block_invoke_3
- ___41-[MDMServerCore _backgroundPollFromTask:]_block_invoke_4
- ___46-[MDMServerCore _pollOrScheduleNextPollForHRN]_block_invoke
- ___47-[MDMServerCore _scheduleNextPollWithInterval:]_block_invoke
- ___57-[MDMServerCore _memberQueuePollOrScheduleNextPollForHRN]_block_invoke
- ___57-[MDMServerCore _memberQueuePollOrScheduleNextPollForHRN]_block_invoke_2
- ___58-[MDMServerCore _memberQueuePollForHRNFromBackgroundTask:]_block_invoke
- ___58-[MDMServerCore _memberQueuePollForHRNFromBackgroundTask:]_block_invoke_2
- ___95-[MDMServerCore _sendCheckInRequestAndHandleErrorForMessageType:requestDict:completionHandler:]_block_invoke_3
- ___98-[MDMMigrationManager _retrieveAndStorePendingCloudConfigurationWithRetryCount:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e34_v24?0"NSError"8"NSDictionary"16ls32l8
- ___block_descriptor_56_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
```
