## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/KnowledgeMonitor`

```diff

-477.0.1.0.0
-  __TEXT.__text: 0x2e24c
-  __TEXT.__objc_methlist: 0x3264
-  __TEXT.__const: 0x250
-  __TEXT.__gcc_except_tab: 0x7e4
-  __TEXT.__cstring: 0x3111
-  __TEXT.__oslogstring: 0x28d2
-  __TEXT.__unwind_info: 0xca8
+480.0.0.0.0
+  __TEXT.__text: 0x30458
+  __TEXT.__objc_methlist: 0x3394
+  __TEXT.__const: 0x240
+  __TEXT.__gcc_except_tab: 0x894
+  __TEXT.__cstring: 0x3a2d
+  __TEXT.__oslogstring: 0x2c2f
+  __TEXT.__unwind_info: 0xd18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9e0
-  __DATA_CONST.__objc_classlist: 0x180
+  __DATA_CONST.__const: 0xa80
+  __DATA_CONST.__objc_classlist: 0x190
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x24b0
-  __DATA_CONST.__objc_superrefs: 0x158
-  __DATA_CONST.__objc_arraydata: 0x100
-  __DATA_CONST.__got: 0x648
+  __DATA_CONST.__objc_selrefs: 0x2578
+  __DATA_CONST.__objc_superrefs: 0x168
+  __DATA_CONST.__objc_arraydata: 0x330
+  __DATA_CONST.__got: 0x6b0
   __AUTH_CONST.__const: 0x420
-  __AUTH_CONST.__cfstring: 0x1fe0
-  __AUTH_CONST.__objc_const: 0x50d0
-  __AUTH_CONST.__objc_arrayobj: 0x1c8
+  __AUTH_CONST.__cfstring: 0x2880
+  __AUTH_CONST.__objc_const: 0x53c0
+  __AUTH_CONST.__objc_arrayobj: 0x210
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x38c
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x3b8
   __DATA.__data: 0x548
-  __DATA.__bss: 0x20
+  __DATA.__bss: 0x10
   __DATA_DIRTY.__objc_data: 0xf00
-  __DATA_DIRTY.__bss: 0xb0
+  __DATA_DIRTY.__bss: 0xc0
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/AVRouting

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1249
-  Symbols:   2249
+  Functions: 1293
+  Symbols:   2321
   CStrings:  0
 
Symbols:
+ -[DKApplicationState rawApplication]
+ -[DKApplicationState setRawApplication:]
+ -[_DKApplicationMonitor updateFocalApplication:rawFocalApplication:timestamp:displayType:transitionReason:transaction:]
+ -[_DKApplicationMonitorBase updateBiomeAppInFocusWithStopEventAtTimestamp:reason:transitionReason:]
+ -[_DKExtensionInfo .cxx_destruct]
+ -[_DKExtensionInfo bundleIdentifier]
+ -[_DKExtensionInfo extensionHostID]
+ -[_DKExtensionInfo initWithBundleIdentifier:parentBundleIdentifier:extensionHostID:]
+ -[_DKExtensionInfo parentBundleIdentifier]
+ -[_DKExtensionInfo setBundleIdentifier:]
+ -[_DKExtensionInfo setExtensionHostID:]
+ -[_DKExtensionInfo setParentBundleIdentifier:]
+ -[_DKExtensionUsageMonitor .cxx_destruct]
+ -[_DKExtensionUsageMonitor addProcess:forIdentity:]
+ -[_DKExtensionUsageMonitor dealloc]
+ -[_DKExtensionUsageMonitor extensionInfoForID:]
+ -[_DKExtensionUsageMonitor init]
+ -[_DKExtensionUsageMonitor processMonitor:didUpdateState:forProcess:]
+ -[_DKExtensionUsageMonitor processUpdateHandlerForEpoch:]
+ -[_DKExtensionUsageMonitor removeProcessForIdentity:]
+ -[_DKExtensionUsageMonitor sendBiomeEvent:type:timestamp:]
+ -[_DKExtensionUsageMonitor setSource:]
+ -[_DKExtensionUsageMonitor source]
+ -[_DKExtensionUsageMonitor start]
+ -[_DKExtensionUsageMonitor stop]
+ -[_DKNowPlayingMonitor saveBMEventWithCurrent:outputDevices:artistStoreIdentifier:albumStoreIdentifier:strictMediaType:contentType:excludeFromSuggestions:]
+ GCC_except_table16
+ GCC_except_table44
+ GCC_except_table51
+ GCC_except_table57
+ GCC_except_table62
+ _MRNowPlayingInfoContentTypeBook
+ _MRNowPlayingInfoContentTypeGeneric
+ _MRNowPlayingInfoContentTypeHomeMedia
+ _MRNowPlayingInfoContentTypeMovie
+ _MRNowPlayingInfoContentTypeMusic
+ _MRNowPlayingInfoContentTypePodcast
+ _MRNowPlayingInfoContentTypeRadio
+ _MRNowPlayingInfoContentTypeTVShow
+ _MRNowPlayingInfoMediaTypeAudio
+ _MRNowPlayingInfoMediaTypeVideo
+ _OBJC_CLASS_$_BMAppExtensionUsage
+ _OBJC_CLASS_$__DKExtensionInfo
+ _OBJC_CLASS_$__DKExtensionUsageMonitor
+ _OBJC_IVAR_$_DKApplicationState._rawApplication
+ _OBJC_IVAR_$__DKExtensionInfo._bundleIdentifier
+ _OBJC_IVAR_$__DKExtensionInfo._extensionHostID
+ _OBJC_IVAR_$__DKExtensionInfo._parentBundleIdentifier
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._activeExtensions
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._epoch
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._everVisibleIdentities
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._nonEligibleExtensionsIdentifiers
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._processMonitor
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._source
+ _OBJC_IVAR_$__DKExtensionUsageMonitor._thirdPartyExtensions
+ _OBJC_METACLASS_$__DKExtensionInfo
+ _OBJC_METACLASS_$__DKExtensionUsageMonitor
+ __OBJC_$_INSTANCE_METHODS__DKExtensionInfo
+ __OBJC_$_INSTANCE_METHODS__DKExtensionUsageMonitor
+ __OBJC_$_INSTANCE_VARIABLES__DKExtensionInfo
+ __OBJC_$_INSTANCE_VARIABLES__DKExtensionUsageMonitor
+ __OBJC_$_PROP_LIST__DKExtensionInfo
+ __OBJC_$_PROP_LIST__DKExtensionUsageMonitor
+ __OBJC_CLASS_RO_$__DKExtensionInfo
+ __OBJC_CLASS_RO_$__DKExtensionUsageMonitor
+ __OBJC_METACLASS_RO_$__DKExtensionInfo
+ __OBJC_METACLASS_RO_$__DKExtensionUsageMonitor
+ ___32-[_DKExtensionUsageMonitor stop]_block_invoke
+ ___33-[_DKExtensionUsageMonitor start]_block_invoke
+ ___33-[_DKExtensionUsageMonitor start]_block_invoke_2
+ ___33-[_DKExtensionUsageMonitor start]_block_invoke_3
+ ___57-[_DKExtensionUsageMonitor processUpdateHandlerForEpoch:]_block_invoke
+ ___57-[_DKExtensionUsageMonitor processUpdateHandlerForEpoch:]_block_invoke_2
+ ___block_descriptor_112_e8_32s40s48s56s64r72r80r88r96r104r_e29_v24?0^{__CFDictionary=}8^v16lr64l8s32l8s40l8r72l8r80l8r88l8r96l8r104l8s48l8s56l8
+ ___block_descriptor_120_e8_32s40s48s56r64r72r80r88r96r104r112r_e5_v8?0lr56l8s32l8r64l8r72l8s40l8r80l8r88l8r96l8r104l8r112l8s48l8
+ ___block_descriptor_40_e8_32s_e35_v24?0"NSString"8"NSDictionary"16ls32l8
+ ___block_descriptor_48_e8_32w_e74_v32?0"RBSProcessMonitor"8"RBSProcessHandle"16"RBSProcessStateUpdate"24lw32l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_56_e8_32s40s48r_e40_v16?0"<RBSProcessMonitorConfiguring>"8ls32l8s40l8r48l8
+ ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0ls32l8r48l8s40l8r56l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32r40r48r56r64r72r_e42_v16?0"_DKApplicationMonitorGuardedData"8lr32l8r40l8r48l8r56l8r64l8r72l8
+ _kMRMediaRemoteNowPlayingInfoContentType
+ _kMRMediaRemoteNowPlayingInfoStrictMediaType
- -[_DKApplicationMonitor updateFocalApplication:timestamp:displayType:transitionReason:transaction:]
- -[_DKNowPlayingMonitor saveBMEventWithCurrent:outputDevices:artistStoreIdentifier:albumStoreIdentifier:excludeFromSuggestions:]
- GCC_except_table42
- GCC_except_table49
- GCC_except_table55
- GCC_except_table60
- _OBJC_CLASS_$_NSTimer
- ___block_descriptor_104_e8_32s40s48s56r64r72r80r88r96r_e5_v8?0lr56l8s32l8r64l8r72l8s40l8r80l8r88l8r96l8s48l8
- ___block_descriptor_40_e8_32s_e18_B16?0"NSString"8ls32l8
- ___block_descriptor_40_e8_32w_e17_v16?0"NSTimer"8lw32l8
- ___block_descriptor_72_e8_32r40r48r56r64r_e42_v16?0"_DKApplicationMonitorGuardedData"8lr32l8r40l8r48l8r56l8r64l8
- ___block_descriptor_96_e8_32s40s48s56s64r72r80r88r_e29_v24?0^{__CFDictionary=}8^v16lr64l8s32l8s40l8r72l8r80l8r88l8s48l8s56l8
```
