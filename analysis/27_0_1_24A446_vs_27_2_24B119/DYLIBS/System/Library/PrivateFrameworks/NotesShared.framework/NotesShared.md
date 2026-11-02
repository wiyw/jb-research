## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared`

```diff

-3001.2.2.0.0
-  __TEXT.__text: 0x34ab68
+3001.42.1.0.0
+  __TEXT.__text: 0x358f48
   __TEXT.__delay_stubs: 0x240
   __TEXT.__delay_helper: 0x830
-  __TEXT.__objc_methlist: 0x1838c
-  __TEXT.__const: 0xdb68
-  __TEXT.__cstring: 0x193c4
-  __TEXT.__gcc_except_tab: 0xf0e4
-  __TEXT.__oslogstring: 0x1cd19
+  __TEXT.__objc_methlist: 0x1856c
+  __TEXT.__const: 0xdde8
+  __TEXT.__cstring: 0x19614
+  __TEXT.__gcc_except_tab: 0xf1a8
+  __TEXT.__oslogstring: 0x1eb39
   __TEXT.__ustring: 0x39a
-  __TEXT.__swift5_typeref: 0x4348
-  __TEXT.__swift5_fieldmd: 0x2dc8
-  __TEXT.__constg_swiftt: 0x363c
+  __TEXT.__swift5_typeref: 0x4550
+  __TEXT.__swift5_fieldmd: 0x2f8c
+  __TEXT.__constg_swiftt: 0x37d8
   __TEXT.__swift5_builtin: 0x208
-  __TEXT.__swift5_reflstr: 0x2091
+  __TEXT.__swift5_reflstr: 0x2261
   __TEXT.__swift5_assocty: 0x7e0
-  __TEXT.__swift5_protos: 0x54
-  __TEXT.__swift5_proto: 0x988
-  __TEXT.__swift5_types: 0x380
-  __TEXT.__swift5_capture: 0x1d64
-  __TEXT.__swift_as_entry: 0x180
-  __TEXT.__swift_as_ret: 0x1b0
-  __TEXT.__swift_as_cont: 0x3e8
+  __TEXT.__swift5_protos: 0x58
+  __TEXT.__swift5_proto: 0x994
+  __TEXT.__swift5_types: 0x39c
+  __TEXT.__swift5_capture: 0x1e7c
+  __TEXT.__swift_as_entry: 0x188
+  __TEXT.__swift_as_ret: 0x1b8
+  __TEXT.__swift_as_cont: 0x3f4
   __TEXT.__swift5_mpenum: 0x74
-  __TEXT.__unwind_info: 0xf068
-  __TEXT.__eh_frame: 0x8710
+  __TEXT.__unwind_info: 0xf2c0
+  __TEXT.__eh_frame: 0x891c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6568
-  __DATA_CONST.__objc_classlist: 0xa60
+  __DATA_CONST.__const: 0x65a0
+  __DATA_CONST.__objc_classlist: 0xa88
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x238
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xcc30
+  __DATA_CONST.__objc_selrefs: 0xcd10
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x6c0
   __DATA_CONST.__objc_arraydata: 0x228
-  __DATA_CONST.__got: 0x2130
-  __AUTH_CONST.__const: 0xdb08
-  __AUTH_CONST.__cfstring: 0xfa40
-  __AUTH_CONST.__objc_const: 0x223f8
+  __DATA_CONST.__got: 0x2148
+  __AUTH_CONST.__const: 0xdcc8
+  __AUTH_CONST.__cfstring: 0xfc20
+  __AUTH_CONST.__objc_const: 0x229b0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x450
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x2a58
-  __AUTH_CONST.__auth_ptr: 0x14f8
+  __AUTH_CONST.__auth_got: 0x2ac0
+  __AUTH_CONST.__auth_ptr: 0x1520
   __AUTH.__objc_data: 0x2d60
-  __AUTH.__data: 0x1438
+  __AUTH.__data: 0x1700
   __DATA.__objc_ivar: 0xd8c
-  __DATA.__data: 0x4a6c
+  __DATA.__data: 0x4ba4
   __DATA.__objc_stublist: 0x20
-  __DATA.__bss: 0x101a0
-  __DATA.__common: 0x180
-  __DATA_DIRTY.__objc_data: 0x49c8
-  __DATA_DIRTY.__data: 0x1c88
-  __DATA_DIRTY.__bss: 0x29d0
+  __DATA.__bss: 0x10230
+  __DATA.__common: 0x188
+  __DATA_DIRTY.__objc_data: 0x4a68
+  __DATA_DIRTY.__data: 0x1cb8
+  __DATA_DIRTY.__bss: 0x2a40
   __DATA_DIRTY.__common: 0x1f0
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 18547
-  Symbols:   17730
+  Functions: 18726
+  Symbols:   17851
   CStrings:  0
 
Symbols:
+ +[ICAttachment(Management) attachmentsMatchingPredicate:context:]
+ +[ICAttachmentPDFModel pageTextFromPDFAtURL:]
+ +[ICAttachmentPDFModel recognizedTextFromPDFAtURL:suggestedTitle:maxPages:isCancelled:]
+ +[ICBackgroundTranscriptionHelper makeDeferredBackgroundTranscriptionTask]
+ +[ICBackgroundTranscriptionHelper scheduleDeferredBackgroundTranscription]
+ +[ICCloudContext ic_currentPersonaDescription]
+ +[ICCloudContext referenceTargetsLoggingDescriptionForRecord:]
+ +[ICCloudContext shouldDeferPushNotificationWhenReadyToSync:isDisabled:isDisabledInternal:configuredContainerCount:]
+ +[ICInlineAttachment(OrphanRepair) discardOrphanedInlineAttachmentsInContext:]
+ +[ICSearchProfiler signpostIDForOperation:]
+ +[ICTranscriptionBackgroundTask makeTaskRequest]
+ -[ICAccountProxy hasVisibleNotes]
+ -[ICAttachment conversationIdentifier]
+ -[ICAttachment extractedTextContent]
+ -[ICAttachment setConversationIdentifier:]
+ -[ICAttachment(CloudKit) ic_hasAudioMediaOnDiskIncludingSubAttachments]
+ -[ICAttachment(CloudKit) ic_topLevelRecordingAttachment]
+ -[ICAttachmentDrawingModel extractedTextContent]
+ -[ICAttachmentGalleryModel extractedTextContent]
+ -[ICAttachmentImageModel extractedTextContent]
+ -[ICAttachmentInlineDrawingModel extractedTextContent]
+ -[ICAttachmentModel extractedTextContent]
+ -[ICAttachmentPDFModel extractedTextContent]
+ -[ICAttachmentPDFModel supportsOCR]
+ -[ICAttachmentPaperBundleModel extractedTextContent]
+ -[ICCloudContext _prewarmDeferredCommonAssetFetchIfNeededForCloudObject:]
+ -[ICCloudContext deferPushNotificationIfUnableToFetchForSubscriptionID:]
+ -[ICCloudContext needsToFetchForDeferredPushNotification]
+ -[ICCloudContext setNeedsToFetchForDeferredPushNotification:]
+ -[ICCloudContext waitForPendingWorkWithCompletionHandler:]
+ -[ICNote _updateLinksToThisNote]
+ -[ICNote performAfterSave:]
+ -[ICNote setUpdateLinksBackgroundContext:]
+ -[ICNote updateLinksBackgroundContext]
+ -[ICNote updateLinksToThisNoteAfterSave]
+ -[ICNote(AttachmentManagement) titleForParagraphID:]
+ -[ICNoteContainer ic_accessibilityIdentifier]
+ -[ICNoteContext hasVisibleNotes]
+ -[ICNoteContext ic_accessibilityIdentifier]
+ -[ICTranscriptionBackgroundTask handleTaskExpiration]
+ -[ICTranscriptionBackgroundTask runTaskWithCompletion:]
+ -[NSManagedObjectContext(ICInlineAttachmentOrphanRepair) ic_saveRepairingOrphanedInlineAttachmentsWithReason:]
+ -[NoteAttachmentObject(ICLegacyAttachment) setTypeUTI:]
+ GCC_except_table110
+ GCC_except_table139
+ GCC_except_table159
+ GCC_except_table210
+ GCC_except_table261
+ GCC_except_table283
+ GCC_except_table290
+ GCC_except_table306
+ GCC_except_table310
+ GCC_except_table337
+ GCC_except_table364
+ GCC_except_table369
+ GCC_except_table381
+ GCC_except_table400
+ GCC_except_table419
+ GCC_except_table445
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table92
+ _CGBitmapContextCreate
+ _CGBitmapContextCreateImage
+ _CGColorSpaceCreateWithName
+ _CGContextDrawPDFPage
+ _CGContextSetRGBFillColor
+ _CGImageRelease
+ _CGPDFDocumentGetNumberOfPages
+ _CGPDFDocumentGetPage
+ _CGPDFPageGetDrawingTransform
+ _CGPDFPageGetRotationAngle
+ _ICAttachmentMetadataConversationIdentifierKey
+ _ICAttachmentModelNonBlankString
+ _ICNoteUpdateLinksNotification
+ _ICSearchProfilingSignpostLog
+ _ICSearchProfilingSignpostLog.onceToken
+ _ICSearchProfilingSignpostLog.signpostLog
+ _NSManagedObjectContextDidSaveNotification
+ _OBJC_CLASS_$_ICTranscriptionBackgroundTask
+ _OBJC_IVAR_$_ICCloudContext._needsToFetchForDeferredPushNotification
+ _OBJC_IVAR_$_ICNote.updateLinksBackgroundContext
+ _OBJC_METACLASS_$_ICTranscriptionBackgroundTask
+ __DATA__TtC11NotesShared25ExpiringActivityAssertion
+ __DATA__TtC11NotesShared31TranscriptionBackgroundActivity
+ __DATA__TtCC11NotesShared13Transcription14RecordingClaim
+ __DATA__TtCC11NotesShared31TranscriptionBackgroundActivity4Hold
+ __IVARS__TtC11NotesShared25ExpiringActivityAssertion
+ __IVARS__TtC11NotesShared31TranscriptionBackgroundActivity
+ __IVARS__TtCC11NotesShared13Transcription14RecordingClaim
+ __IVARS__TtCC11NotesShared31TranscriptionBackgroundActivity4Hold
+ __METACLASS_DATA__TtC11NotesShared25ExpiringActivityAssertion
+ __METACLASS_DATA__TtC11NotesShared31TranscriptionBackgroundActivity
+ __METACLASS_DATA__TtCC11NotesShared13Transcription14RecordingClaim
+ __METACLASS_DATA__TtCC11NotesShared31TranscriptionBackgroundActivity4Hold
+ __OBJC_$_CATEGORY_NSManagedObjectContext_$_ICInlineAttachmentOrphanRepair
+ __OBJC_$_CLASS_METHODS_ICInlineAttachment(CloudKit|Management|OrphanRepair|ICAttachmentPersistenceAdditions)
+ __OBJC_$_CLASS_METHODS_ICTranscriptionBackgroundTask
+ __OBJC_$_INSTANCE_METHODS_ICInlineAttachment(CloudKit|Management|OrphanRepair|ICAttachmentPersistenceAdditions)
+ __OBJC_$_INSTANCE_METHODS_ICTranscription(NotesShared)
+ __OBJC_$_INSTANCE_METHODS_ICTranscriptionBackgroundTask
+ __OBJC_$_INSTANCE_METHODS_NSManagedObjectContext(ICInlineAttachmentOrphanRepair|Shared)
+ __OBJC_$_PROP_LIST_ICTranscriptionBackgroundTask
+ __OBJC_CLASS_PROTOCOLS_$_ICInlineAttachment(CloudKit|Management|OrphanRepair|ICAttachmentPersistenceAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_ICTranscriptionBackgroundTask
+ __OBJC_CLASS_RO_$_ICTranscriptionBackgroundTask
+ __OBJC_METACLASS_RO_$_ICTranscriptionBackgroundTask
+ ___32-[ICNote _updateLinksToThisNote]_block_invoke
+ ___32-[ICNote _updateLinksToThisNote]_block_invoke_2
+ ___40-[ICNote updateLinksToThisNoteAfterSave]_block_invoke
+ ___40-[ICNote updateLinksToThisNoteAfterSave]_block_invoke_2
+ ___42-[ICAttachment setConversationIdentifier:]_block_invoke
+ ___48-[ICAttachmentGalleryModel extractedTextContent]_block_invoke
+ ___52-[ICNote(AttachmentManagement) titleForParagraphID:]_block_invoke
+ ___53-[ICBackgroundTaskScheduler scheduleTask:completion:]_block_invoke_3
+ ___55-[ICTranscriptionBackgroundTask runTaskWithCompletion:]_block_invoke
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke_2
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke_3
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke_4
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke_5
+ ___58-[ICCloudContext waitForPendingWorkWithCompletionHandler:]_block_invoke_6
+ ___63-[ICCloudContext handleCloudKitNotification:completionHandler:]_block_invoke_6
+ ___78+[ICInlineAttachment(OrphanRepair) discardOrphanedInlineAttachmentsInContext:]_block_invoke
+ ___ICSearchProfilingSignpostLog_block_invoke
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80r88r_e5_v8?0lr80l8s32l8s40l8r88l8s48l8s56l8s72l8s64l8
+ ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
+ ___block_descriptor_65_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_96_e8_32s40s48s56s64bs72r80r_e32_v24?0"CKRecordID"8"NSError"16ls32l8r72l8s40l8r80l8s48l8s64l8s56l8
+ ___swift_memcpy48_8
+ _associated conformance 10Foundation16AttributedStringV11NotesSharedE43TranscriptParagraphAccessibilityInformationV4KindOSHADSQ
+ _kCGColorSpaceSRGB
+ _kICDividerLineHeightBoldText
+ _os_signpost_id_make_with_pointer
+ _swift_retain_x11
+ _symbolic $s11NotesShared28BackgroundExecutionAssertionP
+ _symbolic Iegh_
+ _symbolic SayyyYbcG
+ _symbolic So7NSCacheCy_____yxq__G_____yxq__GG 11NotesShared5CacheC10KeyWrapper33_E2980D92141C1715ABC1100DCD468C78LLC AC05ValueE0AELLC
+ _symbolic _____ 10Foundation16AttributedStringV11NotesSharedE43TranscriptParagraphAccessibilityInformationV
+ _symbolic _____ 10Foundation16AttributedStringV11NotesSharedE43TranscriptParagraphAccessibilityInformationV4KindO
+ _symbolic _____ 11NotesShared13TranscriptionC14RecordingClaimC
+ _symbolic _____ 11NotesShared25ExpiringActivityAssertionC
+ _symbolic _____ 11NotesShared31TranscriptionBackgroundActivityC
+ _symbolic _____ 11NotesShared31TranscriptionBackgroundActivityC4HoldC
+ _symbolic _____ 11NotesShared31TranscriptionBackgroundActivityC5State33_B3D3F430FDD672DD7B42882042ED77DELLV
+ _symbolic _____ s6UInt64V
+ _symbolic _____Sg 11NotesShared13TranscriptionC14RecordingClaimC
+ _symbolic _____Sg 11NotesShared31TranscriptionBackgroundActivityC4HoldC
+ _symbolic _____SgXw 11NotesShared13TranscriptionC
+ _symbolic _____SgXw 11NotesShared31TranscriptionBackgroundActivityC
+ _symbolic _____SgXwz_Xx 11NotesShared13TranscriptionC
+ _symbolic _____XDXMT 11NotesShared13TranscriptionC
+ _symbolic ______pSSYbc 11NotesShared28BackgroundExecutionAssertionP
+ _symbolic ______pSg 11NotesShared28BackgroundExecutionAssertionP
+ _symbolic _____ySDySo17NSManagedObjectIDCSiGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySDySo17NSManagedObjectIDCSiG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____yShySo17NSManagedObjectIDCGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yShySo17NSManagedObjectIDCG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____ySi_____G s18_DictionaryStorageC 10Foundation16AttributedStringV11NotesSharedE43TranscriptParagraphAccessibilityInformationV
+ _symbolic _____ySo17NSManagedObjectIDCSiG s18_DictionaryStorageC
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11NotesShared31TranscriptionBackgroundActivityC5State33_B3D3F430FDD672DD7B42882042ED77DELLV
+ _symbolic _____y_______G 10Foundation16AttributedStringV4RunsV16AttributesSlice1V 11NotesShared16SpeakerAttributeV
+ _symbolic _____y_______G 10Foundation16AttributedStringV4RunsV16AttributesSlice1V 11NotesShared23TranscriptTextAttributeV
+ _symbolic _____y________G 10Foundation16AttributedStringV4RunsV16AttributesSlice1V8IteratorV 11NotesShared16SpeakerAttributeV
+ _symbolic _____y________G 10Foundation16AttributedStringV4RunsV16AttributesSlice1V8IteratorV 11NotesShared23TranscriptTextAttributeV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11NotesShared31TranscriptionBackgroundActivityC5State33_B3D3F430FDD672DD7B42882042ED77DELLV So16os_unfair_lock_sV
+ _symbolic _____yyyYbcG s23_ContiguousArrayStorageC
+ _symbolic yyYbc
+ _symbolic yyc
+ _type_layout_string 10Foundation16AttributedStringV11NotesSharedE43TranscriptParagraphAccessibilityInformationV
+ _type_layout_string 11NotesShared31TranscriptionBackgroundActivityC5State33_B3D3F430FDD672DD7B42882042ED77DELLV
- -[ICCloudContext disableAutomaticallyRetryNetworkFailures]
- -[ICCloudContext setDisableAutomaticallyRetryNetworkFailures:]
- -[ICNote _updateLinksOnMainThreadSelectorDelayer]
- -[ICNote setUpdateLinksSelectorDelayer:]
- -[ICNote titleForParagraphID:]
- -[ICNote updateLinksSelectorDelayer]
- -[ICNote updateLinksWhenPossible]
- -[ICNoteContext startIndexingWithCoreSpotlightDelegateForDescription:coordinator:]
- GCC_except_table158
- GCC_except_table163
- GCC_except_table166
- GCC_except_table178
- GCC_except_table191
- GCC_except_table202
- GCC_except_table211
- GCC_except_table242
- GCC_except_table252
- GCC_except_table271
- GCC_except_table278
- GCC_except_table301
- GCC_except_table331
- GCC_except_table351
- GCC_except_table354
- GCC_except_table387
- GCC_except_table393
- GCC_except_table402
- GCC_except_table405
- GCC_except_table432
- GCC_except_table437
- GCC_except_table442
- _ICInternalSettingsIsCollapsibleSectionsEnabled
- _ICUseCoreDataCoreSpotlightIntegration
- _OBJC_CLASS_$_ICCDCSIReindexer
- _OBJC_CLASS_$_ICCoreDataCoreSpotlightDelegate
- _OBJC_IVAR_$_ICCloudContext._disableAutomaticallyRetryNetworkFailures
- _OBJC_IVAR_$_ICNote.updateLinksSelectorDelayer
- __INSTANCE_METHODS_ICTranscription
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSManagedObjectContext_$_Shared
- __OBJC_$_CATEGORY_NSManagedObjectContext_$_Shared
- __OBJC_$_CLASS_METHODS_ICInlineAttachment(CloudKit|Management|ICAttachmentPersistenceAdditions)
- __OBJC_$_INSTANCE_METHODS_ICInlineAttachment(CloudKit|Management|ICAttachmentPersistenceAdditions)
- __OBJC_$_PROP_LIST_NSManagedObjectContext_$_Shared
- __OBJC_CLASS_PROTOCOLS_$_ICInlineAttachment(CloudKit|Management|ICAttachmentPersistenceAdditions)
- ___30-[ICNote titleForParagraphID:]_block_invoke
- ___49-[ICNote _updateLinksOnMainThreadSelectorDelayer]_block_invoke
- ___block_descriptor_66_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_72_e8_32s40s48bs56r_e38_v32?0"NSString"8"CKContainer"16^B24lr56l8s32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56bs_e32_v24?0"CKRecordID"8"NSError"16ls32l8s40l8s48l8s56l8
- ___swift_closure_destructor.21Tm
- ___swift_closure_destructor.40Tm
- _symbolic So7NSCacheCy_____yxq__xG_____yxq__GG 11NotesShared5CacheC10KeyWrapper33_E2980D92141C1715ABC1100DCD468C78LLC AC05ValueE0AELLC
```
