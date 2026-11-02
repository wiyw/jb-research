## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

```diff

-2215.0.20.0.0
-  __TEXT.__text: 0x264558
-  __TEXT.__objc_methlist: 0x12d9c
-  __TEXT.__const: 0x159a
-  __TEXT.__cstring: 0x3f6e6
-  __TEXT.__oslogstring: 0x5efed
-  __TEXT.__gcc_except_tab: 0xd83c
+2215.42.2.0.0
+  __TEXT.__text: 0x262e88
+  __TEXT.__objc_methlist: 0x12e2c
+  __TEXT.__const: 0x157a
+  __TEXT.__cstring: 0x3fe27
+  __TEXT.__oslogstring: 0x5b60d
+  __TEXT.__gcc_except_tab: 0xd5b4
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__constg_swiftt: 0xf0
   __TEXT.__swift5_typeref: 0x146

   __TEXT.__swift5_assocty: 0x48
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
-  __TEXT.__unwind_info: 0x4888
+  __TEXT.__unwind_info: 0x4900
   __TEXT.__eh_frame: 0x10c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xb8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xaff0
+  __DATA_CONST.__objc_selrefs: 0xb058
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x360
-  __DATA_CONST.__objc_arraydata: 0xf00
+  __DATA_CONST.__objc_arraydata: 0x1028
   __DATA_CONST.__got: 0x12a0
-  __AUTH_CONST.__const: 0x1080
-  __AUTH_CONST.__cfstring: 0x32d00
-  __AUTH_CONST.__objc_const: 0x191a8
-  __AUTH_CONST.__objc_arrayobj: 0x360
+  __AUTH_CONST.__const: 0x10c0
+  __AUTH_CONST.__cfstring: 0x33460
+  __AUTH_CONST.__objc_const: 0x191d8
+  __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_intobj: 0x13c8
   __AUTH_CONST.__objc_dictobj: 0x2d0
   __AUTH_CONST.__auth_got: 0x1238
   __AUTH_CONST.__auth_ptr: 0x2d0
-  __AUTH.__objc_data: 0x918
+  __AUTH.__objc_data: 0x8c8
   __AUTH.__data: 0xc0
-  __DATA.__objc_ivar: 0x1830
-  __DATA.__data: 0x1180
+  __DATA.__objc_ivar: 0x1834
+  __DATA.__data: 0x1170
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x560
-  __DATA_DIRTY.__objc_data: 0x2530
-  __DATA_DIRTY.__data: 0xa8
-  __DATA_DIRTY.__bss: 0x5b0
+  __DATA_DIRTY.__objc_data: 0x2580
+  __DATA_DIRTY.__data: 0xb8
+  __DATA_DIRTY.__bss: 0x5c8
   - /System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices
   - /System/Library/Frameworks/CFNetwork.framework/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7316
-  Symbols:   11496
+  Functions: 7344
+  Symbols:   11526
   CStrings:  0
 
Symbols:
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectoryAtPath:]
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectory]
+ +[MAAutoAssetMigrationManager deleteDirectoryIfEmpty:error:]
+ -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]
+ -[ControlManager maAutoAssetScheduledCleanup]
+ -[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]
+ -[ControlManager setMaAutoAssetScheduledCleanup:]
+ -[DownloadInfo summary]
+ -[MADAutoAssetControlManager _firstAssetTypeForSelectors:]
+ -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVendOrNewerOncePersonalized:fromLocation:]
+ -[MADAutoAssetControlManager _newEntriesBlockForSelectors:]
+ -[MADAutoAssetControlManager _newSelectorsForAtomicEntries:]
+ -[MADAutoAssetControlManager _newSelectorsForSetEntries:]
+ -[MADAutoAssetControlManager formLatestAssetVersionBySelector:]
+ -[MADAutoAssetControlManager hasReachedStartupActivation]
+ -[MADAutoAssetControlManager schedulerReferencesDescriptor:withLatestVersionBySelector:]
+ -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:withLatestVersionBySelector:]
+ GCC_except_table193
+ GCC_except_table199
+ GCC_except_table202
+ GCC_except_table205
+ GCC_except_table305
+ GCC_except_table313
+ GCC_except_table315
+ GCC_except_table317
+ GCC_except_table319
+ GCC_except_table322
+ GCC_except_table336
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table354
+ GCC_except_table358
+ GCC_except_table361
+ GCC_except_table365
+ GCC_except_table371
+ GCC_except_table399
+ GCC_except_table402
+ GCC_except_table432
+ GCC_except_table438
+ GCC_except_table520
+ GCC_except_table522
+ GCC_except_table579
+ GCC_except_table620
+ GCC_except_table622
+ GCC_except_table628
+ GCC_except_table643
+ GCC_except_table672
+ GCC_except_table803
+ GCC_except_table804
+ GCC_except_table806
+ GCC_except_table809
+ _OBJC_IVAR_$_ControlManager._maAutoAssetScheduledCleanup
+ __MADLogDateFormatter
+ __MADLogDateFormatter.dateFormatter
+ __MADLogDateFormatter.onceToken
+ __MADLogSpacedDateFormatter
+ __MADLogSpacedDateFormatter.onceToken
+ __MADLogSpacedDateFormatter.spacedDateFormatter
+ __OBJC_$_CLASS_METHODS_MAAutoAssetMigrationManager
+ ___134-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_2
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_3
+ ___53-[MobileAssetHealthReport scheduleReportWithReports:]_block_invoke_2
+ ____MADLogDateFormatter_block_invoke
+ ____MADLogSpacedDateFormatter_block_invoke
+ ___block_descriptor_32_e8_v16?0q8l
+ ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
+ ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___clearXattrKey_block_invoke
+ ___updateXattrKeyWithDate_block_invoke
+ _clearXattrKey
+ _getDateOnXattrKey
+ _isDownloadErrorNetworkConnectivityError
+ _removexattr
+ _updateXattrKeyWithDate
- -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:logString:]
- -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVend:fromLocation:]
- -[MADAutoAssetControlManager action_RemoveQueuedClient:error:]
- -[MADAutoAssetControlManager action_RouteClientClosed:error:]
- -[MADAutoAssetControlManager schedulerReferencesDescriptor:]
- -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:]
- GCC_except_table152
- GCC_except_table191
- GCC_except_table196
- GCC_except_table200
- GCC_except_table203
- GCC_except_table306
- GCC_except_table314
- GCC_except_table316
- GCC_except_table318
- GCC_except_table320
- GCC_except_table334
- GCC_except_table341
- GCC_except_table345
- GCC_except_table352
- GCC_except_table356
- GCC_except_table359
- GCC_except_table364
- GCC_except_table370
- GCC_except_table373
- GCC_except_table400
- GCC_except_table403
- GCC_except_table433
- GCC_except_table444
- GCC_except_table521
- GCC_except_table523
- GCC_except_table581
- GCC_except_table621
- GCC_except_table623
- GCC_except_table629
- GCC_except_table644
- GCC_except_table673
- GCC_except_table799
- GCC_except_table800
- GCC_except_table801
- GCC_except_table802
- _MAPreferencesIsVerboseLoggingEnabled
- ___106-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:then:]_block_invoke
- ___block_descriptor_32_e20_v24?0Q8"NSError"16l
- ___block_descriptor_41_e8_32s_e19_"NSDictionary"8?0ls32l8
- ___block_descriptor_79_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
```
