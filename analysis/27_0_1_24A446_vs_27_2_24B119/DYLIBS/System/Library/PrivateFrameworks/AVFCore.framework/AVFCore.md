## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

```diff

-2450.77.1.1.0
-  __TEXT.__text: 0x1c9de0
+2475.13.1.1.0
+  __TEXT.__text: 0x1ca874
   __TEXT.__delay_helper: 0x1bc
-  __TEXT.__objc_methlist: 0x1c144
-  __TEXT.__cstring: 0x26f43
-  __TEXT.__gcc_except_tab: 0xa024
+  __TEXT.__objc_methlist: 0x1c2fc
+  __TEXT.__cstring: 0x26f53
+  __TEXT.__gcc_except_tab: 0xa044
   __TEXT.__const: 0x1e48
-  __TEXT.__oslogstring: 0x50d1
+  __TEXT.__oslogstring: 0x5128
   __TEXT.__ustring: 0x18
   __TEXT.__dlopen_cstrs: 0x56
   __TEXT.__swift5_typeref: 0x40d

   __TEXT.__swift5_proto: 0x6c
   __TEXT.__swift5_types: 0x48
   __TEXT.__swift5_capture: 0x60
-  __TEXT.__unwind_info: 0xa520
+  __TEXT.__unwind_info: 0xa580
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5bb8
-  __DATA_CONST.__objc_classlist: 0x1238
+  __DATA_CONST.__const: 0x5be0
+  __DATA_CONST.__objc_classlist: 0x1240
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb5c0
+  __DATA_CONST.__objc_selrefs: 0xb6b8
   __DATA_CONST.__objc_protorefs: 0x60
-  __DATA_CONST.__objc_superrefs: 0xd68
+  __DATA_CONST.__objc_superrefs: 0xd70
   __DATA_CONST.__objc_arraydata: 0x310
   __DATA_CONST.__got: 0x4850
   __AUTH_CONST.__const: 0x1258
-  __AUTH_CONST.__cfstring: 0x1a720
-  __AUTH_CONST.__objc_const: 0x329d8
+  __AUTH_CONST.__cfstring: 0x1a6a0
+  __AUTH_CONST.__objc_const: 0x32bd8
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x360
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x2040
   __AUTH_CONST.__auth_ptr: 0x128
-  __AUTH.__objc_data: 0x8e88
-  __AUTH.__data: 0x1f0
-  __DATA.__objc_ivar: 0x27e0
-  __DATA.__data: 0x183c
+  __AUTH.__objc_data: 0x81e0
+  __AUTH.__data: 0x1e8
+  __DATA.__objc_ivar: 0x27fc
+  __DATA.__data: 0x184c
   __DATA.__crash_info: 0x148
   __DATA.__common: 0x1e0
   __DATA.__bss: 0x1410
-  __DATA_DIRTY.__objc_data: 0x2828
+  __DATA_DIRTY.__objc_data: 0x3520
+  __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__common: 0x1e0
-  __DATA_DIRTY.__bss: 0x1e1
+  __DATA_DIRTY.__bss: 0x1e9
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVRouting.framework/AVRouting
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12084
-  Symbols:   23940
+  Functions: 12122
+  Symbols:   23984
   CStrings:  0
 
Symbols:
+ -[AVActivityProgressClient unfailActivityForTaskID:]
+ -[AVAsset _availableMediaCharacteristicsFromMediaSelectionGroupDictionaries:]
+ -[AVAsset _mediaSelectionGroupDictionariesIncludingExtendedOptions:]
+ -[AVAsset _mediaSelectionGroupForMediaCharacteristic:inMediaSelectionGroupDictionaries:]
+ -[AVAssetDownloadLiveActivity _subtitleForCompleted:failed:]
+ -[AVAssetDownloadLiveActivity _unsafeClientStateForDownload:]
+ -[AVAssetDownloadLiveActivity downloadDidEnterRetry:]
+ -[AVAssetDownloadLiveActivityClientState activityFailed]
+ -[AVAssetDownloadLiveActivityClientState lastPublishedSubtitle]
+ -[AVAssetDownloadLiveActivityClientState lastPublishedTitle]
+ -[AVAssetDownloadLiveActivityClientState setActivityFailed:]
+ -[AVAssetDownloadLiveActivityClientState setLastPublishedSubtitle:]
+ -[AVAssetDownloadLiveActivityClientState setLastPublishedTitle:]
+ -[AVAssetDownloadLiveActivityEntry assetTitle]
+ -[AVAssetDownloadLiveActivityEntry byteProgress]
+ -[AVAssetDownloadLiveActivityEntry dealloc]
+ -[AVAssetDownloadLiveActivityEntry download]
+ -[AVAssetDownloadLiveActivityEntry fractionCompleted]
+ -[AVAssetDownloadLiveActivityEntry initWithDownload:]
+ -[AVAssetDownloadLiveActivityEntry setAssetTitle:]
+ -[AVAssetDownloadLiveActivityEntry setByteProgress:]
+ -[AVAssetDownloadLiveActivityEntry setDownload:]
+ -[AVAssetDownloadLiveActivityEntry setState:]
+ -[AVAssetDownloadLiveActivityEntry state]
+ -[AVAssetDownloadLiveActivityEntry updateToBytesWritten:bytesExpectedToWrite:]
+ -[AVAssetTrackPlan hash]
+ -[AVAssetVideoTrackPlan hash]
+ -[AVAssetWriterInput _readyForMoreMediaDataMayHaveChanged]
+ -[AVAssetWriterInput(SwiftOverlay_Internal) _canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVAssetWriterInput(SwiftOverlay_Internal) _errorForNotReadyForMoreMediaData]
+ -[AVAssetWriterInput(SwiftOverlay_Internal) _invokeWhenReadyForMoreMediaDataUsingBlock:]
+ -[AVAssetWriterInputHelper canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVAssetWriterInputInterPassAnalysisHelper canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVAssetWriterInputNoMorePassesHelper canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVAssetWriterInputUnknownHelper canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVAssetWriterInputWritingHelper canBecomeReadyForMoreMediaDataAndReturnError:]
+ -[AVFigAssetWriterTrack setWeakReferenceToAssetWriterInput:]
+ -[AVFigAssetWriterTrack weakReferenceToAssetWriterInput]
+ -[AVMediaSelection(AVMediaSelection_Local) _initWithAsset:mediaSelectionGroupDictionaries:selectedMediaArray:]
+ -[AVPlannedSegmentConfiguration hash]
+ -[AVPlannedVideoSegmentConfiguration hash]
+ -[AVSampleBufferVideoRenderer _isReadyForMoreMediaDataOnSerialQueue]
+ GCC_except_table101
+ GCC_except_table131
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table160
+ GCC_except_table162
+ GCC_except_table180
+ GCC_except_table225
+ _AVActivityProgressPreserveSubtitleOnFailureKey
+ _AVMediaCharacteristicSignLanguageInterpretationForAccessibility
+ _OBJC_CLASS_$_AVAssetDownloadLiveActivityEntry
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._activityFailed
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._lastPublishedSubtitle
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._lastPublishedTitle
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityEntry._assetTitle
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityEntry._byteProgress
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityEntry._download
+ _OBJC_IVAR_$_AVAssetDownloadLiveActivityEntry._state
+ _OBJC_IVAR_$_AVAssetWriterInputInternal.readyForMoreMediaDataWaiters
+ _OBJC_IVAR_$_AVAssetWriterInputInternal.readyForMoreMediaDataWaitersMutex
+ _OBJC_IVAR_$_AVFigAssetWriterTrack._weakReferenceToAssetWriterInput
+ _OBJC_METACLASS_$_AVAssetDownloadLiveActivityEntry
+ __OBJC_$_INSTANCE_METHODS_AVAssetDownloadLiveActivityEntry
+ __OBJC_$_INSTANCE_VARIABLES_AVAssetDownloadLiveActivityEntry
+ __OBJC_$_PROP_LIST_AVAssetDownloadLiveActivityEntry
+ __OBJC_CLASS_RO_$_AVAssetDownloadLiveActivityEntry
+ __OBJC_METACLASS_RO_$_AVAssetDownloadLiveActivityEntry
+ ___block_descriptor_57_e8_32o40r48r_e5_v8?0ls32l8r40l8r48l8
+ _kFigVideoCompositorProperty_MaximumPendingVideoCompositionRequests
- -[AVAssetDownloadLiveActivity _createDownloadIDForSession:]
- -[AVAssetDownloadLiveActivity _subtitleForCompleted:failed:willRetry:]
- -[AVAssetDownloadLiveActivity _waitForConfig]
- -[AVAssetDownloadLiveActivity errorMayBeRetriedByBackgroundSession:]
- -[AVAssetDownloadLiveActivityClientState setWillRetryDownloadIDs:]
- -[AVAssetDownloadLiveActivityClientState willRetryDownloadIDs]
- -[AVAssetDownloadSession _registerWithLiveActivityManager]
- -[AVAssetDownloadSession cancelFromLiveActivity]
- GCC_except_table100
- GCC_except_table104
- GCC_except_table132
- GCC_except_table154
- GCC_except_table161
- GCC_except_table164
- GCC_except_table172
- GCC_except_table202
- GCC_except_table208
- GCC_except_table220
- GCC_except_table224
- GCC_except_table242
- GCC_except_table97
- _NSURLErrorBackgroundTaskCancelledReasonKey
- _OBJC_IVAR_$_AVAssetDownloadLiveActivity._configLoaded
- _OBJC_IVAR_$_AVAssetDownloadLiveActivity._configLoadedSem
- _OBJC_IVAR_$_AVAssetDownloadLiveActivityClientState._willRetryDownloadIDs
- _kBlockedBundleIdentifiers
- _kCFErrorDomainCFNetwork
```
