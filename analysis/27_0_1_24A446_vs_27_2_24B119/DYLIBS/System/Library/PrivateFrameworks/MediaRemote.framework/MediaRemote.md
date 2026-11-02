## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

```diff

-4026.110.4.0.0
-  __TEXT.__text: 0x317a30
-  __TEXT.__objc_methlist: 0x2c818
-  __TEXT.__const: 0x6b0
-  __TEXT.__cstring: 0x2df00
-  __TEXT.__oslogstring: 0xeaed
-  __TEXT.__gcc_except_tab: 0x6368
+4026.210.4.0.0
+  __TEXT.__text: 0x318b64
+  __TEXT.__objc_methlist: 0x2c900
+  __TEXT.__const: 0x700
+  __TEXT.__cstring: 0x2df91
+  __TEXT.__oslogstring: 0xebb9
+  __TEXT.__gcc_except_tab: 0x63d8
   __TEXT.__dlopen_cstrs: 0x777
   __TEXT.__ustring: 0x7b8
-  __TEXT.__unwind_info: 0xbe18
+  __TEXT.__unwind_info: 0xbe20
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xbb58
+  __DATA_CONST.__const: 0xbc18
   __DATA_CONST.__objc_classlist: 0x1210
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x260
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf978
+  __DATA_CONST.__objc_selrefs: 0xfa00
   __DATA_CONST.__objc_protorefs: 0x88
   __DATA_CONST.__objc_superrefs: 0x1038
   __DATA_CONST.__objc_arraydata: 0x260
-  __DATA_CONST.__got: 0x14d0
-  __AUTH_CONST.__const: 0x3440
-  __AUTH_CONST.__cfstring: 0x24a80
-  __AUTH_CONST.__objc_const: 0x47f48
+  __DATA_CONST.__got: 0x14e8
+  __AUTH_CONST.__const: 0x3480
+  __AUTH_CONST.__cfstring: 0x24c60
+  __AUTH_CONST.__objc_const: 0x480b0
+  __AUTH_CONST.__objc_intobj: 0x540
   __AUTH_CONST.__objc_arrayobj: 0x180
-  __AUTH_CONST.__objc_intobj: 0x4f8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xbc0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x8700
-  __DATA.__objc_ivar: 0x33ec
+  __AUTH.__objc_data: 0x5f00
+  __DATA.__objc_ivar: 0x3404
   __DATA.__data: 0x1ca8
   __DATA.__bss: 0x9b8
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x2da0
+  __DATA_DIRTY.__objc_data: 0x55a0
   __DATA_DIRTY.__data: 0x88
   __DATA_DIRTY.__bss: 0x5c8
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 21030
-  Symbols:   30262
+  Functions: 21052
+  Symbols:   30299
   CStrings:  0
 
Symbols:
+ +[MRCBProductInfo isWXDeviceWithModelID:]
+ -[MRAVConcreteOutputDevice supportsDiscoveredIsPlaying]
+ -[MRAVConcreteRoutingDiscoverySession detailsList]
+ -[MRAVDistantOutputDevice supportsDiscoveredIsPlaying]
+ -[MRAVEndpoint supportsDiscoveredIsPlaying]
+ -[MRAVOutputDevice isWXDevice]
+ -[MRAVOutputDevice supportsDiscoveredIsPlaying]
+ -[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]
+ -[MRCompanionLinkClientEvent setStatusFlags:]
+ -[MRCompanionLinkClientEvent statusFlags]
+ -[MRGroupComposition addHomeAccessoryWithModelIdentifier:]
+ -[MRGroupComposition homeAccessoryCount]
+ -[MRGroupComposition setHomeAccessoryCount:]
+ -[MRGroupComposition setSpeakerGroupCount:]
+ -[MRGroupComposition setTvAndSpeakerCount:]
+ -[MRGroupComposition setWalledHomeAccessoryCount:]
+ -[MRGroupComposition speakerGroupCount]
+ -[MRGroupComposition tvAndSpeakerCount]
+ -[MRGroupComposition walledHomeAccessoryCount]
+ -[MRMediaRemoteService requestPushToStartTokenWithCompletion:]
+ -[MRNowPlayingPushTokenManager requestStartToken]
+ -[MRUserSettings remoteSessionStalenessGraceInterval]
+ -[_MRCommandOptionsProtobuf hasRequestDetails]
+ -[_MRCommandOptionsProtobuf requestDetails]
+ -[_MRCommandOptionsProtobuf setRequestDetails:]
+ GCC_except_table222
+ GCC_except_table252
+ GCC_except_table321
+ OBJC_IVAR_$__MRCommandOptionsProtobuf._requestDetails
+ _AVOutputContextPredictedOutputDevicesDidChangeNotification
+ _MRAVOutputDeviceB525ModelID
+ _MRAVOutputDeviceB525ModelIDPrefix
+ _MRAVOutputDeviceJ490ModelID
+ _MRAVOutputDeviceJ491ModelID
+ _MRAVVolumeClientEndpointVolumeCategoryDidChangeNotification
+ _MRRequestDetailsInitiatorCorianderLockScreen
+ _MRRequestDetailsInitiatorNowPlayingPlatter
+ _OBJC_CLASS_$_AVOutputContextPredictedDevicesOptions
+ _OBJC_IVAR_$_MRCompanionLinkClientEvent._statusFlags
+ _OBJC_IVAR_$_MRGroupComposition._homeAccessoryCount
+ _OBJC_IVAR_$_MRGroupComposition._speakerGroupCount
+ _OBJC_IVAR_$_MRGroupComposition._tvAndSpeakerCount
+ _OBJC_IVAR_$_MRGroupComposition._walledHomeAccessoryCount
+ _RPOptionStatusFlags
+ __MRDeviceClassFromMGDeviceClass
+ ___49-[MRNowPlayingPushTokenManager requestStartToken]_block_invoke
+ ___50-[MRAVConcreteRoutingDiscoverySession detailsList]_block_invoke
+ ___53-[MRUserSettings remoteSessionStalenessGraceInterval]_block_invoke
+ ___62-[MRMediaRemoteService requestPushToStartTokenWithCompletion:]_block_invoke
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_2
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_3
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_4
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_5
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_6
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_7
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_8
+ ___75-[MRActiveRoutesObserver _handleActiveSystemEndpointDidRemoveOutputDevice:]_block_invoke_4
+ ___block_descriptor_184_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r176r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8r160l8r168l8r176l8
+ _remoteSessionStalenessGraceInterval.__interval
+ _remoteSessionStalenessGraceInterval.__once
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleEndpointsForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleOutputDevicesForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]
- -[MRAVRoutingDiscoverySessionWrapper _shouldNotify]
- -[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]
- -[MRUserSettings remoteSessionDefaultAssertionInterval]
- GCC_except_table102
- GCC_except_table221
- GCC_except_table250
- GCC_except_table320
- ___50-[MRRapportTransportConnection _registerCallbacks]_block_invoke_3
- ___55-[MRUserSettings remoteSessionDefaultAssertionInterval]_block_invoke
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_2
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_3
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_4
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_5
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_6
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_7
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_8
- ___62-[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]_block_invoke
- ___block_descriptor_160_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8
- _remoteSessionDefaultAssertionInterval.__interval
- _remoteSessionDefaultAssertionInterval.__once
```
