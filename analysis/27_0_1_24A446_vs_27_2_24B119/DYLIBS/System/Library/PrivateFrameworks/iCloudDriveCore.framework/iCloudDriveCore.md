## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/iCloudDriveCore`

```diff

-5168.0.55.0.0
-  __TEXT.__text: 0x308aa0
-  __TEXT.__objc_methlist: 0x1be50
+5168.40.162.0.0
+  __TEXT.__text: 0x30a0cc
+  __TEXT.__objc_methlist: 0x1c204
   __TEXT.__const: 0x4f0
-  __TEXT.__cstring: 0x829d8
-  __TEXT.__oslogstring: 0x3de76
-  __TEXT.__gcc_except_tab: 0x17800
+  __TEXT.__cstring: 0x849ab
+  __TEXT.__oslogstring: 0x3ee7b
+  __TEXT.__gcc_except_tab: 0x17adc
   __TEXT.__ustring: 0x36
-  __TEXT.__unwind_info: 0xa440
+  __TEXT.__unwind_info: 0xa588
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9ed0
-  __DATA_CONST.__objc_classlist: 0xab0
+  __DATA_CONST.__const: 0xa1f8
+  __DATA_CONST.__objc_classlist: 0xad0
   __DATA_CONST.__objc_catlist: 0xd8
-  __DATA_CONST.__objc_protolist: 0x2c0
+  __DATA_CONST.__objc_protolist: 0x2d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf170
+  __DATA_CONST.__objc_selrefs: 0xf310
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x960
+  __DATA_CONST.__objc_superrefs: 0x968
   __DATA_CONST.__objc_arraydata: 0xeb8
-  __DATA_CONST.__got: 0x17c0
-  __AUTH_CONST.__const: 0x2cf8
-  __AUTH_CONST.__cfstring: 0x23640
-  __AUTH_CONST.__objc_const: 0x41a50
+  __DATA_CONST.__got: 0x17b8
+  __AUTH_CONST.__const: 0x2d28
+  __AUTH_CONST.__cfstring: 0x23b20
+  __AUTH_CONST.__objc_const: 0x423a8
   __AUTH_CONST.__objc_intobj: 0xc18
   __AUTH_CONST.__objc_arrayobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH_CONST.__auth_got: 0xda0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x2558
+  __AUTH.__objc_data: 0x2698
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0x2030
-  __DATA.__data: 0x29f0
-  __DATA.__bss: 0x200
+  __DATA.__objc_ivar: 0x2054
+  __DATA.__data: 0x2ab0
+  __DATA.__bss: 0x1f0
   __DATA_DIRTY.__objc_data: 0x4588
   __DATA_DIRTY.__data: 0xd0
   __DATA_DIRTY.__bss: 0x428

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14225
-  Symbols:   18270
+  Functions: 14324
+  Symbols:   18404
   CStrings:  0
 
Symbols:
+ +[BRCClientPrivilegesDescriptor isNonSandboxedForAuditToken:]
+ +[BRCItemID appLibraryForBrainItemIDString:zoneName:zoneAppRetriever:clientZone:]
+ +[BRCItemID appLibraryIDForCrossZoneMovedBrainItemIDString:]
+ +[BRCNotification shouldBlockWithUploadV2Enabled:isIdleOrRejected:]
+ +[BRCPQLInjectionIntegerInListBase _injectionFromValues:]
+ +[BRCPQLInjectionIntegerInListBase columnName]
+ +[BRCPQLInjectionJobStates columnName]
+ +[BRCPQLInjectionRowIDInList columnName]
+ +[BRCPQLInjectionZoneRowIDInList columnName]
+ +[BRCServerChangesApplyUtil_Private itemUndergoingCZMToAnotherZone:si:clientZone:rank:scheduler:zone:session:]
+ +[BRCSyncEngineMigrationManager shouldMigrateToUploadV2]
+ -[BRCAccountSession __getOrCreateServerZone:newlyCreatedDuringInitialSync:]
+ -[BRCAccountSession appLibraryRootNeedsCreationForAppLibraryID:completionHandler:]
+ -[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:newlyCreatedDuringInitialSync:]
+ -[BRCAccountSession quotaHandler]
+ -[BRCAccountSession quotaUV2Handler]
+ -[BRCAccountSession reviveAndSignalFPForRootItemID:zoneName:ownerName:completionHandler:]
+ -[BRCAccountSession zoneAndAppLibraryConsolidationFlagsForItemIDString:zoneName:ownerName:completionHandler:]
+ -[BRCAccountSession zoneAndAppLibraryRootNeedsCreationForZoneName:ownerName:completionHandler:]
+ -[BRCAccountSession zoneHasSyncedDownWithoutError:ownerName:completionHandler:]
+ -[BRCAccountSession zoneNeedsCreation:ownerName:completionHandler:]
+ -[BRCClientDatabaseFacade uv2MigrationPendingLiveItemCount:tombstoneItemCount:]
+ -[BRCClientZone lastSyncDownError]
+ -[BRCClientZone(BRCZoneReset) _rescheduleSuspendedUV2CZMJobsMigratedIntoThisZone]
+ -[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:shareIDsFromDeltaSync:]
+ -[BRCFetchRecordSubResourcesOperation addRecord:fromDeltaSync:]
+ -[BRCItemFetcher localItemBuilder]
+ -[BRCLocalItem _insertUploadV2TombstoneForCrossZoneMove]
+ -[BRCLocalItem cacheUV2MigrationStamp:]
+ -[BRCLocalItem clearUV2MigrationStamp]
+ -[BRCLocalItem clearUploadV2ModifyRedirectPending]
+ -[BRCLocalItem isMigratingToUV2]
+ -[BRCLocalItem markUploadV2ModifyRedirectPending]
+ -[BRCLocalItem syncEngineMarkNeedsSyncingUp]
+ -[BRCLocalItem uv2MigrationNeedsReimport]
+ -[BRCLocalItem uv2MigrationStamp]
+ -[BRCLocalStatInfo _clearProcessingStamp]
+ -[BRCNotification shouldBeBlockedInUploadV2]
+ -[BRCPQLInjectionIntegerInListBase initWithIndexSet:]
+ -[BRCPQLInjectionIntegerInListBase initWithValues:]
+ -[BRCQueryItemInfo _populateShareAttributionFromItem:]
+ -[BRCQueryItemInfo creatorNameComponents]
+ -[BRCQueryItemInfo isCreatedByCurrentUser]
+ -[BRCQueryItemInfo isSharedFolderSubItem]
+ -[BRCQueryItemInfo ownerNameComponents]
+ -[BRCQuotaHandler .cxx_destruct]
+ -[BRCQuotaHandler _fetchedWithinPacerWindow]
+ -[BRCQuotaHandler _registerDailyResolutionTask]
+ -[BRCQuotaHandler _resolveQuotaCategoriesIfPossibleWithCompletion:]
+ -[BRCQuotaHandler _signalResolvedCategoriesForAvailableBytes:]
+ -[BRCQuotaHandler cancel]
+ -[BRCQuotaHandler dealloc]
+ -[BRCQuotaHandler initWithSessionContext:]
+ -[BRCQuotaHandler quotaAvailableForOwner:]
+ -[BRCQuotaHandler scheduleQuotaFetchIfNeededForOwner:]
+ -[BRCReadWriteClientDatabaseFacade hasUV2MigrationRequestedRowsWithError:]
+ -[BRCReadWriteClientDatabaseFacade markUV2MigrationRequestedForRowIDs:retryAt:error:]
+ -[BRCReadWriteClientDatabaseFacade nextUV2MigrationBatchItemsAtTime:limit:itemBuilder:error:]
+ -[BRCReadWriteClientDatabaseFacade stampUV2MigrationChildrenOfParent:error:]
+ -[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:]
+ -[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:fromDeltaSync:error:]
+ -[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]
+ -[BRCServerZone _saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:shareIDsFromDeltaSync:]
+ -[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]
+ -[BRCServerZone _sendApprovedNotificationIfNeededWithShare:fromDeltaSync:]
+ -[BRCServerZone _shouldSendRequestForAccessNotificationFromDeltaSync:]
+ -[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]
+ -[BRCSyncEngineMigrationManager _dispatchModify:]
+ -[BRCSyncEngineMigrationManager _dispatchReimportForFileObjectID:]
+ -[BRCSyncEngineMigrationManager _dropStrandedMigrationRowForFileObjectID:]
+ -[BRCSyncEngineMigrationManager _processPhase2BatchOnWorkloop:task:]
+ -[BRCSyncEngineMigrationManager _runPhase2BatchWithTask:]
+ -[BRCUV2MigrationModifyDispatch .cxx_destruct]
+ -[BRCUV2MigrationModifyDispatch fileObjectID]
+ -[BRCUV2MigrationModifyDispatch initWithFileObjectID:parentIdentifier:]
+ -[BRCUV2MigrationModifyDispatch parentIdentifier]
+ -[BRCUserDefaults getBirdBGSTActivitiesConfigsWithAccountFacade:uploadV2Enabled:]
+ -[BRCUserDefaults quotaCategoryMUpperBound]
+ -[BRCUserDefaults quotaCategoryResolutionBGSystemTaskConfig]
+ -[BRCUserDefaults quotaCategorySUpperBound]
+ -[BRCUserDefaults quotaCategoryXSUpperBound]
+ -[BRCUserDefaults quotaUV2FetchPacerDelay]
+ -[BRCUserDefaults uv2MigrationBoostPendingDeletions]
+ -[BRCUserDefaults uv2MigrationRequestThrottleInterval]
+ -[BRCXPCRegularIPCsClient _fpHasNonUploadedFilesWithCompletion:]
+ -[BRCXPCRegularIPCsClient _getContainersNeedingUploadV1WithFPPendingData:reply:]
+ -[BRCXPCRegularIPCsClient _getContainersNeedingUploadV2WithFPPendingData:reply:]
+ -[BRCXPCRegularIPCsClient _iCloudDriveContainerSet]
+ -[BRCXPCRegularIPCsClient uv2MigrationPendingItemCountWithReply:]
+ -[BRCXPCRegularIPCsClient(FPFSAdditions) _createItemBasedOnTemplate:fields:contents:options:request:additionalItemAttributes:progress:fromModifyRedirect:completionHandler:]
+ -[BRCXPCRegularIPCsClient(FPFSAdditions) validateConnectionDomainWithDomainIdentifier:databaseID:backingStoreIdentity:reply:]
+ -[CKRecordID(BRCItemAdditions) _itemIDWithLibraryRowID:zoneAppRetriever:error:]
+ -[iCDDeleteItemContext clientKey]
+ -[iCDDeleteItemContext initWithZoneName:zoneOwner:itemIDString:serverChangeToken:progress:clientKey:]
+ GCC_except_table114
+ GCC_except_table116
+ GCC_except_table130
+ GCC_except_table139
+ GCC_except_table141
+ GCC_except_table152
+ GCC_except_table168
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table180
+ GCC_except_table185
+ GCC_except_table186
+ GCC_except_table188
+ GCC_except_table195
+ GCC_except_table198
+ GCC_except_table210
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table218
+ GCC_except_table220
+ GCC_except_table223
+ GCC_except_table225
+ GCC_except_table231
+ GCC_except_table233
+ GCC_except_table236
+ GCC_except_table237
+ GCC_except_table243
+ GCC_except_table250
+ GCC_except_table262
+ GCC_except_table263
+ GCC_except_table266
+ GCC_except_table268
+ GCC_except_table272
+ GCC_except_table277
+ GCC_except_table280
+ GCC_except_table286
+ GCC_except_table288
+ GCC_except_table290
+ GCC_except_table292
+ GCC_except_table300
+ GCC_except_table302
+ GCC_except_table305
+ GCC_except_table310
+ GCC_except_table320
+ GCC_except_table324
+ GCC_except_table333
+ GCC_except_table336
+ GCC_except_table339
+ GCC_except_table341
+ GCC_except_table343
+ GCC_except_table346
+ GCC_except_table349
+ GCC_except_table360
+ GCC_except_table364
+ GCC_except_table368
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table380
+ GCC_except_table383
+ GCC_except_table386
+ GCC_except_table392
+ GCC_except_table397
+ GCC_except_table399
+ GCC_except_table405
+ GCC_except_table409
+ GCC_except_table413
+ GCC_except_table418
+ GCC_except_table422
+ GCC_except_table427
+ GCC_except_table439
+ GCC_except_table443
+ GCC_except_table449
+ GCC_except_table451
+ GCC_except_table457
+ GCC_except_table466
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table476
+ GCC_except_table480
+ GCC_except_table482
+ GCC_except_table484
+ GCC_except_table486
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table496
+ GCC_except_table498
+ GCC_except_table499
+ OBJC_IVAR_$_BRCLocalItem._uv2MigrationStamp
+ _BRCInsufficientQuotaLCategory
+ _BRCInsufficientQuotaMCategory
+ _BRCInsufficientQuotaSCategory
+ _BRCInsufficientQuotaXSCategory
+ _OBJC_CLASS_$_BRCPQLInjectionIntegerInListBase
+ _OBJC_CLASS_$_BRCPQLInjectionRowIDInList
+ _OBJC_CLASS_$_BRCPQLInjectionZoneRowIDInList
+ _OBJC_CLASS_$_BRCQuotaHandler
+ _OBJC_CLASS_$_BRCUV2MigrationModifyDispatch
+ _OBJC_IVAR_$_BRCAccountSession._quotaUV2Handler
+ _OBJC_IVAR_$_BRCFetchRecordSubResourcesOperation._shareIDsFromDeltaSync
+ _OBJC_IVAR_$_BRCQueryItemInfo._creatorNameComponents
+ _OBJC_IVAR_$_BRCQueryItemInfo._isCreatedByCurrentUser
+ _OBJC_IVAR_$_BRCQueryItemInfo._isSharedFolderSubItem
+ _OBJC_IVAR_$_BRCQueryItemInfo._ownerNameComponents
+ _OBJC_IVAR_$_BRCQuotaHandler._quotaPacer
+ _OBJC_IVAR_$_BRCQuotaHandler._sessionContext
+ _OBJC_IVAR_$_BRCQuotaHandler._workQueue
+ _OBJC_IVAR_$_BRCSyncEngineMigrationManager._phase2DispatchQueue
+ _OBJC_IVAR_$_BRCUV2MigrationModifyDispatch._fileObjectID
+ _OBJC_IVAR_$_BRCUV2MigrationModifyDispatch._parentIdentifier
+ _OBJC_IVAR_$_iCDDeleteItemContext._clientKey
+ _OBJC_METACLASS_$_BRCPQLInjectionIntegerInListBase
+ _OBJC_METACLASS_$_BRCPQLInjectionRowIDInList
+ _OBJC_METACLASS_$_BRCPQLInjectionZoneRowIDInList
+ _OBJC_METACLASS_$_BRCQuotaHandler
+ _OBJC_METACLASS_$_BRCUV2MigrationModifyDispatch
+ __BRCIsInconclusiveDomainMatchingError
+ __OBJC_$_CLASS_METHODS_BRCPQLInjectionIntegerInListBase
+ __OBJC_$_CLASS_METHODS_BRCPQLInjectionRowIDInList
+ __OBJC_$_CLASS_METHODS_BRCPQLInjectionZoneRowIDInList
+ __OBJC_$_INSTANCE_METHODS_BRCPQLInjectionIntegerInListBase
+ __OBJC_$_INSTANCE_METHODS_BRCQuotaHandler
+ __OBJC_$_INSTANCE_METHODS_BRCUV2MigrationModifyDispatch
+ __OBJC_$_INSTANCE_VARIABLES_BRCQuotaHandler
+ __OBJC_$_INSTANCE_VARIABLES_BRCUV2MigrationModifyDispatch
+ __OBJC_$_PROP_LIST_BRCItemFetcher
+ __OBJC_$_PROP_LIST_BRCQuotaHandler
+ __OBJC_$_PROP_LIST_BRCUV2MigrationModifyDispatch
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BRCQuotaHandling
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BRCUV2MigrationDatabaseWriteProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BRCQuotaHandling
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BRCUV2MigrationDatabaseWriteProtocol
+ __OBJC_$_PROTOCOL_REFS_BRCQuotaHandling
+ __OBJC_$_PROTOCOL_REFS_BRCUV2MigrationDatabaseWriteProtocol
+ __OBJC_CLASS_PROTOCOLS_$_BRCQuotaHandler
+ __OBJC_CLASS_RO_$_BRCPQLInjectionIntegerInListBase
+ __OBJC_CLASS_RO_$_BRCPQLInjectionRowIDInList
+ __OBJC_CLASS_RO_$_BRCPQLInjectionZoneRowIDInList
+ __OBJC_CLASS_RO_$_BRCQuotaHandler
+ __OBJC_CLASS_RO_$_BRCUV2MigrationModifyDispatch
+ __OBJC_LABEL_PROTOCOL_$_BRCQuotaHandling
+ __OBJC_LABEL_PROTOCOL_$_BRCUV2MigrationDatabaseWriteProtocol
+ __OBJC_METACLASS_RO_$_BRCPQLInjectionIntegerInListBase
+ __OBJC_METACLASS_RO_$_BRCPQLInjectionRowIDInList
+ __OBJC_METACLASS_RO_$_BRCPQLInjectionZoneRowIDInList
+ __OBJC_METACLASS_RO_$_BRCQuotaHandler
+ __OBJC_METACLASS_RO_$_BRCUV2MigrationModifyDispatch
+ __OBJC_PROTOCOL_$_BRCQuotaHandling
+ __OBJC_PROTOCOL_$_BRCUV2MigrationDatabaseWriteProtocol
+ ___109-[BRCAccountSession zoneAndAppLibraryConsolidationFlagsForItemIDString:zoneName:ownerName:completionHandler:]_block_invoke
+ ___113-[BRCFSUploader transferStreamOfSyncContext:didBecomeReadyWithMaxRecordsCount:sizeHint:priority:completionBlock:]_block_invoke_2
+ ___117-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]_block_invoke
+ ___117-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]_block_invoke_2
+ ___125-[BRCXPCRegularIPCsClient(FPFSAdditions) validateConnectionDomainWithDomainIdentifier:databaseID:backingStoreIdentity:reply:]_block_invoke
+ ___170-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke
+ ___172-[BRCXPCRegularIPCsClient(FPFSAdditions) _createItemBasedOnTemplate:fields:contents:options:request:additionalItemAttributes:progress:fromModifyRedirect:completionHandler:]_block_invoke
+ ___172-[BRCXPCRegularIPCsClient(FPFSAdditions) _createItemBasedOnTemplate:fields:contents:options:request:additionalItemAttributes:progress:fromModifyRedirect:completionHandler:]_block_invoke_2
+ ___177-[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke
+ ___26-[BRCXPCClient invalidate]_block_invoke
+ ___42-[BRCQuotaHandler initWithSessionContext:]_block_invoke
+ ___44-[BRCBGSystemTaskManager unregisterAllTasks]_block_invoke
+ ___47-[BRCQuotaHandler _registerDailyResolutionTask]_block_invoke
+ ___47-[BRCQuotaHandler _registerDailyResolutionTask]_block_invoke_2
+ ___47-[BRCQuotaHandler _registerDailyResolutionTask]_block_invoke_3
+ ___49-[BRCSyncEngineMigrationManager _dispatchModify:]_block_invoke
+ ___53-[BRCPQLInjectionIntegerInListBase initWithIndexSet:]_block_invoke
+ ___55-[BRCBGSystemTaskManager unregisterTaskWithIdentifier:]_block_invoke
+ ___57-[BRCSyncEngineMigrationManager _runPhase2BatchWithTask:]_block_invoke
+ ___60-[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]_block_invoke
+ ___62-[BRCQuotaHandler _signalResolvedCategoriesForAvailableBytes:]_block_invoke
+ ___64-[BRCXPCRegularIPCsClient _fpHasNonUploadedFilesWithCompletion:]_block_invoke
+ ___65-[BRCXPCRegularIPCsClient uv2MigrationPendingItemCountWithReply:]_block_invoke
+ ___66-[BRCSyncEngineMigrationManager _dispatchReimportForFileObjectID:]_block_invoke
+ ___67-[BRCAccountSession zoneNeedsCreation:ownerName:completionHandler:]_block_invoke
+ ___67-[BRCQuotaHandler _resolveQuotaCategoriesIfPossibleWithCompletion:]_block_invoke
+ ___67-[BRCQuotaHandler _resolveQuotaCategoriesIfPossibleWithCompletion:]_block_invoke_2
+ ___68-[BRCSyncEngineMigrationManager _processPhase2BatchOnWorkloop:task:]_block_invoke
+ ___68-[BRCSyncEngineMigrationManager _processPhase2BatchOnWorkloop:task:]_block_invoke_2
+ ___74-[BRCServerZone _sendApprovedNotificationIfNeededWithShare:fromDeltaSync:]_block_invoke
+ ___74-[BRCSyncEngineMigrationManager _dropStrandedMigrationRowForFileObjectID:]_block_invoke
+ ___75-[BRCAccountSession(BRCDatabaseManager) _registerDynamicDBFunctions:error:]_block_invoke_3
+ ___75-[BRCAccountSession(BRCDatabaseManager) _registerDynamicDBFunctions:error:]_block_invoke_4
+ ___79-[BRCAccountSession zoneHasSyncedDownWithoutError:ownerName:completionHandler:]_block_invoke
+ ___80-[BRCXPCRegularIPCsClient _getContainersNeedingUploadV1WithFPPendingData:reply:]_block_invoke
+ ___80-[BRCXPCRegularIPCsClient _getContainersNeedingUploadV1WithFPPendingData:reply:]_block_invoke_2
+ ___80-[BRCXPCRegularIPCsClient _getContainersNeedingUploadV2WithFPPendingData:reply:]_block_invoke
+ ___81-[BRCUserDefaults getBirdBGSTActivitiesConfigsWithAccountFacade:uploadV2Enabled:]_block_invoke
+ ___82-[BRCAccountSession appLibraryRootNeedsCreationForAppLibraryID:completionHandler:]_block_invoke
+ ___88-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:newlyCreatedDuringInitialSync:]_block_invoke
+ ___88-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:newlyCreatedDuringInitialSync:]_block_invoke_2
+ ___88-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:newlyCreatedDuringInitialSync:]_block_invoke_3
+ ___89-[BRCAccountSession reviveAndSignalFPForRootItemID:zoneName:ownerName:completionHandler:]_block_invoke
+ ___89-[BRCAccountSession reviveAndSignalFPForRootItemID:zoneName:ownerName:completionHandler:]_block_invoke_2
+ ___93-[BRCReadWriteClientDatabaseFacade nextUV2MigrationBatchItemsAtTime:limit:itemBuilder:error:]_block_invoke
+ ___94-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:]_block_invoke
+ ___95-[BRCAccountSession zoneAndAppLibraryRootNeedsCreationForZoneName:ownerName:completionHandler:]_block_invoke
+ ___block_descriptor_114_e8_32s40s48s56s64s72bs80r88r_e5_v8?0ls32l8s40l8s48l8r80l8s56l8s64l8r88l8s72l8
+ ___block_descriptor_121_e8_32s40s48s56s64s72s80s88s96bs_e23_B16?0"PQLConnection"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_137_e8_32s40s48s56s64s72s80s88s96s104r112r_e23_B16?0"PQLConnection"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8r104l8r112l8s88l8s96l8
+ ___block_descriptor_137_e8_32s40s48s56s64s72s80s88s96s104s112bs_e5_v8?0ls32l8s40l8s48l8s56l8s112l8s64l8s72l8s80l8s88l8s96l8s104l8
+ ___block_descriptor_145_e8_32s40s48s56s64s72s80s88bs96r104r112r120r_e5_v8?0ls32l8r96l8s40l8r104l8s48l8s56l8s64l8r112l8s72l8s80l8r120l8s88l8
+ ___block_descriptor_161_e8_32s40s48s56s64s72s80s88s96bs104r112r120r128r136r144r_e42_v16?0"BRCReadWriteClientDatabaseFacade"8ls32l8r104l8r112l8r120l8s40l8r128l8s48l8s56l8s96l8s64l8s72l8s80l8r136l8s88l8r144l8
+ ___block_descriptor_169_e8_32s40s48s56s64s72s80s88s96s104bs112r120r128r136r144r152r_e5_B8?0ls32l8r112l8r120l8r128l8s40l8r136l8s48l8s56l8s104l8s64l8s72l8s80l8s88l8r144l8s96l8r152l8
+ ___block_descriptor_40_e8_32s_e24_v32?0{_NSRange=QQ}8^B24ls32l8
+ ___block_descriptor_48_e8_32s40bs_e33_v16?0"BRCClientDatabaseFacade"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e42_v16?0"BRCReadWriteClientDatabaseFacade"8lw40l8s32l8
+ ___block_descriptor_56_e8_32bs40r48r_e17_v16?0"NSError"8lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32bs40r48r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r_e42_v16?0"BRCReadWriteClientDatabaseFacade"8ls32l8r40l8
+ ___block_descriptor_56_e8_32s40s48w_e17_v16?0"NSError"8lw48l8s32l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48r_e23_B16?0"PQLConnection"8lr48l8s32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e33_B24?0"CKRecordID"8"CKRecord"16ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32bs40r48r56r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr40l8r48l8r56l8s32l8
+ ___block_descriptor_64_e8_32s40s48r_e5_B8?0ls32l8s40l8r48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e42_v16?0"BRCReadWriteClientDatabaseFacade"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56r_e45_B24?0"BRCClientZone"8"NSMutableIndexSet"16ls32l8s40l8s48l8r56l8
+ ___block_descriptor_64_e8_32s40s48s56r_e5_B8?0ls32l8s40l8r56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v24?0Q8"NSError"16lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s_e23_B16?0"PQLConnection"8ls32l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56s64w_e5_v8?0ls32l8w64l8s40l8s48l8s56l8
+ ___block_descriptor_89_e8_32s40s48s56bs64r72r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8r64l8s40l8s48l8r72l8s56l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_98_e8_32s40s48s56s64r72r_e23_B16?0"PQLConnection"8ls32l8r64l8s40l8s48l8s56l8r72l8
+ ___br_update_tables_40_000_cleanup_in_flight_cross_zone_moves_block_invoke
+ _br_update_tables_40_000
- +[BRCClientPrivilegesDescriptor _isNonSandboxedForAuditToken:]
- +[BRCPQLInjectionJobStates _getPQLInjectionFromJobStates:]
- +[BRCServerChangesApplyUtil_Private itemUndergoingCZMToAnotherZone:si:clientZone:rank:scheduler:zone:]
- +[BRCSyncEngineMigrationManager _migrationQueue]
- -[BRCAccountSession hasSyncedDownZoneSinceStartup:ownerName:completionHandler:]
- -[BRCAccountSession(BRCDatabaseManager) clientDBExistsOnDisk]
- -[BRCAccountSession(FPFSAdditions) inflightSyncProgressRegistry]
- -[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:]
- -[BRCFetchRecordSubResourcesOperation addRecord:]
- -[BRCInflightSyncProgressRegistry .cxx_destruct]
- -[BRCInflightSyncProgressRegistry _cancelAndRemoveProgressesMatchingPredicate:]
- -[BRCInflightSyncProgressRegistry cancelProgressesExcludingClientKey:]
- -[BRCInflightSyncProgressRegistry cancelProgressesForClientKey:]
- -[BRCInflightSyncProgressRegistry close]
- -[BRCInflightSyncProgressRegistry createProgressForClientKey:]
- -[BRCInflightSyncProgressRegistry dumpToContext:]
- -[BRCInflightSyncProgressRegistry init]
- -[BRCInflightSyncProgressRegistry unregisterProgress:forClientKey:]
- -[BRCLocalItem _shouldBlockNotifForUploadV2WithDiffs:]
- -[BRCPQLInjectionJobStates initWithJobStates:]
- -[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:]
- -[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:error:]
- -[BRCServerZone _saveEditedShareRecord:error:]
- -[BRCServerZone _saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:]
- -[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]
- -[BRCServerZone _sendApprovedNotificationIfNeededWithShare:]
- -[BRCServerZone _shouldSendNotification]
- -[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]
- -[BRCSyncEngineMigrationManager _cancel]
- -[BRCSyncEngineMigrationManager _isSyncEngineIdleWithDBFacade:]
- -[BRCSyncEngineMigrationManager _markUsageUploadV2SyncEngine:]
- -[BRCSyncEngineMigrationManager _performSyncEngineMigrationCheckWithTask:]
- -[BRCSyncEngineMigrationManager markUsageUploadV2SyncEngineForNewDatabaseIfNeeded]
- -[BRCSyncEngineMigrationManager shouldMigrateToUploadV2]
- -[BRCUserDefaults getBirdBGSTActivitiesConfigsWithAccountFacade:]
- -[BRCXPCClient _auditURL:]
- -[BRCXPCClient _auditedURLFromPath:]
- -[BRCXPCRegularIPCsClient(FPFSAdditions) _cancelObsoleteSyncEngineRequests]
- -[BRCXPCRegularIPCsClient(FPFSAdditions) _createInflightSyncProgress]
- -[BRCXPCRegularIPCsClient(FPFSAdditions) validateConnectionDomainWithDomainIdentifier:databaseID:reply:]
- -[CKRecordID(BRCItemAdditions) _itemIDWithLibraryRowID:zoneAppRetriever:]
- -[iCDDeleteItemContext initWithZoneName:zoneOwner:itemIDString:serverChangeToken:progress:]
- GCC_except_table110
- GCC_except_table115
- GCC_except_table118
- GCC_except_table137
- GCC_except_table140
- GCC_except_table149
- GCC_except_table153
- GCC_except_table172
- GCC_except_table175
- GCC_except_table178
- GCC_except_table181
- GCC_except_table183
- GCC_except_table187
- GCC_except_table189
- GCC_except_table201
- GCC_except_table216
- GCC_except_table219
- GCC_except_table221
- GCC_except_table224
- GCC_except_table226
- GCC_except_table232
- GCC_except_table235
- GCC_except_table239
- GCC_except_table244
- GCC_except_table247
- GCC_except_table249
- GCC_except_table253
- GCC_except_table254
- GCC_except_table256
- GCC_except_table264
- GCC_except_table265
- GCC_except_table269
- GCC_except_table270
- GCC_except_table273
- GCC_except_table278
- GCC_except_table281
- GCC_except_table285
- GCC_except_table287
- GCC_except_table289
- GCC_except_table291
- GCC_except_table299
- GCC_except_table311
- GCC_except_table319
- GCC_except_table322
- GCC_except_table325
- GCC_except_table327
- GCC_except_table329
- GCC_except_table330
- GCC_except_table332
- GCC_except_table335
- GCC_except_table338
- GCC_except_table340
- GCC_except_table345
- GCC_except_table353
- GCC_except_table358
- GCC_except_table365
- GCC_except_table377
- GCC_except_table382
- GCC_except_table385
- GCC_except_table387
- GCC_except_table389
- GCC_except_table395
- GCC_except_table402
- GCC_except_table408
- GCC_except_table411
- GCC_except_table416
- GCC_except_table421
- GCC_except_table424
- GCC_except_table428
- GCC_except_table438
- GCC_except_table440
- GCC_except_table444
- GCC_except_table448
- GCC_except_table461
- GCC_except_table465
- GCC_except_table469
- GCC_except_table471
- GCC_except_table473
- GCC_except_table475
- GCC_except_table477
- GCC_except_table481
- GCC_except_table483
- GCC_except_table485
- GCC_except_table487
- GCC_except_table98
- _BRReadOnlyShareUploadErrorCategory
- _OBJC_CLASS_$_BRCInflightSyncProgressRegistry
- _OBJC_IVAR_$_BRCAccountSession._inflightSyncProgressRegistry
- _OBJC_IVAR_$_BRCInflightSyncProgressRegistry._progressesByClientKey
- _OBJC_IVAR_$_BRCInflightSyncProgressRegistry._queue
- _OBJC_IVAR_$_BRCSyncEngineMigrationManager._registeredBGSystemTask
- _OBJC_IVAR_$_BRCSyncEngineMigrationManager._resumed
- _OBJC_METACLASS_$_BRCInflightSyncProgressRegistry
- _OUTLINED_FUNCTION_29
- __OBJC_$_INSTANCE_METHODS_BRCInflightSyncProgressRegistry
- __OBJC_$_INSTANCE_METHODS_BRCPQLInjectionJobStates
- __OBJC_$_INSTANCE_VARIABLES_BRCInflightSyncProgressRegistry
- __OBJC_CLASS_RO_$_BRCInflightSyncProgressRegistry
- __OBJC_METACLASS_RO_$_BRCInflightSyncProgressRegistry
- ___103-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]_block_invoke
- ___103-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]_block_invoke_2
- ___104-[BRCXPCRegularIPCsClient(FPFSAdditions) validateConnectionDomainWithDomainIdentifier:databaseID:reply:]_block_invoke
- ___143-[BRCXPCRegularIPCsClient(FPFSAdditions) createItemBasedOnTemplate:fields:contents:options:request:additionalItemAttributes:completionHandler:]_block_invoke
- ___143-[BRCXPCRegularIPCsClient(FPFSAdditions) createItemBasedOnTemplate:fields:contents:options:request:additionalItemAttributes:completionHandler:]_block_invoke_2
- ___148-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]_block_invoke
- ___155-[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:]_block_invoke
- ___39-[BRCSyncEngineMigrationManager cancel]_block_invoke
- ___40-[BRCInflightSyncProgressRegistry close]_block_invoke
- ___46-[BRCServerZone _saveEditedShareRecord:error:]_block_invoke
- ___48+[BRCSyncEngineMigrationManager _migrationQueue]_block_invoke
- ___49-[BRCInflightSyncProgressRegistry dumpToContext:]_block_invoke
- ___54-[BRCXPCRegularIPCsClient getContainersNeedingUpload:]_block_invoke_2
- ___58-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:]_block_invoke
- ___58-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:]_block_invoke_2
- ___58-[BRCAccountSession getOrCreateSharedZones:shareAcceptOp:]_block_invoke_3
- ___60-[BRCServerZone _sendApprovedNotificationIfNeededWithShare:]_block_invoke
- ___62-[BRCInflightSyncProgressRegistry createProgressForClientKey:]_block_invoke
- ___63-[BRCSyncEngineMigrationManager _isSyncEngineIdleWithDBFacade:]_block_invoke
- ___64-[BRCInflightSyncProgressRegistry cancelProgressesForClientKey:]_block_invoke
- ___65-[BRCUserDefaults getBirdBGSTActivitiesConfigsWithAccountFacade:]_block_invoke
- ___67-[BRCInflightSyncProgressRegistry unregisterProgress:forClientKey:]_block_invoke
- ___70-[BRCInflightSyncProgressRegistry cancelProgressesExcludingClientKey:]_block_invoke
- ___74-[BRCSyncEngineMigrationManager _performSyncEngineMigrationCheckWithTask:]_block_invoke
- ___74-[BRCSyncEngineMigrationManager _performSyncEngineMigrationCheckWithTask:]_block_invoke_2
- ___79-[BRCAccountSession hasSyncedDownZoneSinceStartup:ownerName:completionHandler:]_block_invoke
- ___79-[BRCInflightSyncProgressRegistry _cancelAndRemoveProgressesMatchingPredicate:]_block_invoke
- ___80-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:]_block_invoke
- ___block_descriptor_113_e8_32s40s48s56s64s72bs80r88r_e5_v8?0ls32l8s40l8s48l8r80l8s56l8s64l8r88l8s72l8
- ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96r104r_e23_B16?0"PQLConnection"8ls32l8s40l8s48l8s56l8s64l8s72l8r96l8r104l8s80l8s88l8
- ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96s104bs_e23_B16?0"PQLConnection"8ls32l8s40l8s48l8s56l8s104l8s64l8s72l8s80l8s88l8s96l8
- ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96s104bs_e5_v8?0ls32l8s40l8s48l8s56l8s104l8s64l8s72l8s80l8s88l8s96l8
- ___block_descriptor_144_e8_32s40s48s56s64s72s80s88bs96r104r112r120r_e5_v8?0ls32l8r96l8s40l8r104l8s48l8s56l8s64l8r112l8s72l8s80l8r120l8s88l8
- ___block_descriptor_160_e8_32s40s48s56s64s72s80s88s96bs104r112r120r128r136r144r_e42_v16?0"BRCReadWriteClientDatabaseFacade"8ls32l8r104l8r112l8r120l8s40l8r128l8s48l8s56l8s96l8s64l8s72l8s80l8r136l8s88l8r144l8
- ___block_descriptor_168_e8_32s40s48s56s64s72s80s88s96s104bs112r120r128r136r144r152r_e5_B8?0ls32l8r112l8r120l8r128l8s40l8r136l8s48l8s56l8s104l8s64l8s72l8s80l8s88l8r144l8s96l8r152l8
- ___block_descriptor_32_e16_B16?0"NSUUID"8l
- ___block_descriptor_40_e8_32s_e16_B16?0"NSUUID"8ls32l8
- ___block_descriptor_72_e8_32s40bs48r56r64r_e17_v16?0"NSError"8lr48l8r56l8r64l8s32l8s40l8
- ___block_descriptor_80_e8_32s40bs48r56r64r72r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr48l8r56l8r64l8s32l8r72l8s40l8
- ___block_descriptor_80_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56bs64r72r_e39_v36?0"BRQueryItem"8Q16B24"NSError"28lr64l8r72l8s32l8s40l8s48l8s56l8
- ___block_descriptor_88_e8_32s40s48s56bs64r72r_e48_v36?0"<NSFileProviderItem>"8Q16B24"NSError"28ls32l8r64l8s40l8s48l8r72l8s56l8
- ___block_descriptor_97_e8_32s40s48s56s64r72r_e23_B16?0"PQLConnection"8ls32l8r64l8s40l8s48l8s56l8r72l8
- __migrationQueue.migrationQueue
- __migrationQueue.onceToken
```
