## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

```diff

-671.0.2.0.1
-  __TEXT.__text: 0x48ecb8
-  __TEXT.__objc_methlist: 0x38eac
+678.0.1.0.0
+  __TEXT.__text: 0x48fc34
+  __TEXT.__objc_methlist: 0x38f3c
   __TEXT.__const: 0x450a
-  __TEXT.__cstring: 0x596b2
-  __TEXT.__oslogstring: 0x3bb49
+  __TEXT.__cstring: 0x59872
+  __TEXT.__oslogstring: 0x3bd49
   __TEXT.__gcc_except_tab: 0xf4a0
   __TEXT.__dlopen_cstrs: 0x1d2
   __TEXT.__ustring: 0x90

   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_protos: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xe640
+  __TEXT.__unwind_info: 0xe678
   __TEXT.__eh_frame: 0x262c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xc0d0
+  __DATA_CONST.__const: 0xc0f8
   __DATA_CONST.__objc_classlist: 0x1f58
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x4d0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x1bf80
+  __DATA_CONST.__objc_selrefs: 0x1c020
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x14f8
   __DATA_CONST.__objc_arraydata: 0x12f0
   __DATA_CONST.__got: 0x39c8
-  __AUTH_CONST.__const: 0x8d58
-  __AUTH_CONST.__cfstring: 0x3b240
-  __AUTH_CONST.__objc_const: 0x83ba0
+  __AUTH_CONST.__const: 0x8d38
+  __AUTH_CONST.__cfstring: 0x3b300
+  __AUTH_CONST.__objc_const: 0x83bf0
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__objc_intobj: 0x3450
+  __AUTH_CONST.__objc_intobj: 0x3468
   __AUTH_CONST.__objc_arrayobj: 0x1098
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x21d8
+  __AUTH_CONST.__auth_got: 0x21e8
   __AUTH_CONST.__auth_ptr: 0x5d8
   __AUTH.__objc_data: 0x4008
   __AUTH.__data: 0x2178
   __DATA.__objc_ivar: 0x4aac
   __DATA.__data: 0x3d18
-  __DATA.__bss: 0x2918
+  __DATA.__bss: 0x2928
   __DATA.__common: 0x128
   __DATA_DIRTY.__objc_data: 0x10088
   __DATA_DIRTY.__data: 0xd28

   - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
   - /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
   - /System/Library/PrivateFrameworks/HeroDataClient.framework/HeroDataClient
+  - /System/Library/PrivateFrameworks/IDS.framework/IDS
   - /System/Library/PrivateFrameworks/IntelligenceFlowContext.framework/IntelligenceFlowContext
   - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared
   - /System/Library/PrivateFrameworks/IntelligencePlatform.framework/IntelligencePlatform

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 25705
-  Symbols:   36750
+  Functions: 25718
+  Symbols:   36769
   CStrings:  0
 
Symbols:
+ +[ATXHeroDataServerHelper anyHeroPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearKnownTypeLOIExcludingGym:isNearFrequentLOI:]
+ +[ATXHeroDataServerHelper canPredictClipsGivenRecentMotionWithContext:]
+ +[ATXHeroDataServerHelper heroAppAndClipPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearFrequentLOI:]
+ +[ATXHeroDataServerHelper heroPoiPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOIExcludingGym:]
+ +[ATXHeroDataServerHelper isNearKnownTypeLocationOfInterest:]
+ +[ATXHeroDataServerHelper isNearKnownTypeLocationOfInterestExcludingGym:]
+ +[_ATXDataStore histogramTypeForString:found:]
+ -[ATXCDNDownloaderTriggerManager _anyHeroPredictionsAreEligible]
+ -[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXStackStateTracker internalStateFromDisk]
+ -[_ATXInspectionClient launchCountForBundleId:inHistogramNamed:reply:]
+ -[_ATXInspectionServer launchCountForBundleId:inHistogramNamed:reply:]
+ _ATXLanguageChangeIsAwaitingRestart
+ _IDSCopyLocalDeviceUniqueID
+ __ATXLanguageChangeObservedTime
+ ___105-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___105-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke_2
+ ___70-[_ATXInspectionClient launchCountForBundleId:inHistogramNamed:reply:]_block_invoke
+ ___block_descriptor_40_e49_v24?0"ATXFaceGalleryConfiguration"8"NSError"16l
+ ___block_descriptor_40_e8_32bs_e49_v24?0"ATXWidgetSmartStackResponse"8"NSError"16ls32l8
+ _clock_gettime_nsec_np
+ _sharedInstance._pasOnceToken1
- -[ATXHeroDataServer heroAppAndClipPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearFrequentLOI:]
- -[ATXHeroDataServer heroPoiPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOIExcludingGym:isNearFrequentLOI:]
- ___block_descriptor_32_e49_v24?0"ATXFaceGalleryConfiguration"8"NSError"16l
```
