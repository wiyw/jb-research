## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

```diff

-449.30.6.14.26
-  __TEXT.__text: 0x77958
-  __TEXT.__objc_methlist: 0xbc0c
-  __TEXT.__const: 0x5b8
+449.31.6.16.29
+  __TEXT.__text: 0x78eac
+  __TEXT.__objc_methlist: 0xbd54
+  __TEXT.__const: 0x5f8
   __TEXT.__gcc_except_tab: 0x15a0
-  __TEXT.__cstring: 0x6ac9
-  __TEXT.__oslogstring: 0x7fa8
+  __TEXT.__cstring: 0x6ca9
+  __TEXT.__oslogstring: 0x81d8
   __TEXT.__dlopen_cstrs: 0x5a
-  __TEXT.__constg_swiftt: 0x148
-  __TEXT.__swift5_typeref: 0x133
-  __TEXT.__swift5_builtin: 0x28
+  __TEXT.__constg_swiftt: 0x168
+  __TEXT.__swift5_typeref: 0x139
+  __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_reflstr: 0x85
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__swift5_proto: 0x40
-  __TEXT.__swift5_types: 0x1c
+  __TEXT.__swift5_proto: 0x44
+  __TEXT.__swift5_types: 0x20
   __TEXT.__swift5_fieldmd: 0xfc
   __TEXT.__swift5_capture: 0x60
   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x8
-  __TEXT.__unwind_info: 0x2760
+  __TEXT.__unwind_info: 0x27d0
   __TEXT.__eh_frame: 0x330
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2190
-  __DATA_CONST.__objc_classlist: 0x450
+  __DATA_CONST.__const: 0x21e0
+  __DATA_CONST.__objc_classlist: 0x458
   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3df8
+  __DATA_CONST.__objc_selrefs: 0x3e80
   __DATA_CONST.__objc_protorefs: 0xc8
-  __DATA_CONST.__objc_superrefs: 0x380
+  __DATA_CONST.__objc_superrefs: 0x388
   __DATA_CONST.__objc_arraydata: 0x18
-  __DATA_CONST.__got: 0x600
-  __AUTH_CONST.__const: 0xbd8
-  __AUTH_CONST.__cfstring: 0x5f00
-  __AUTH_CONST.__objc_const: 0x14370
+  __DATA_CONST.__got: 0x608
+  __AUTH_CONST.__const: 0xbf8
+  __AUTH_CONST.__cfstring: 0x6020
+  __AUTH_CONST.__objc_const: 0x145e0
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x698
-  __AUTH_CONST.__auth_ptr: 0x128
-  __AUTH.__objc_data: 0x98
-  __DATA.__objc_ivar: 0xf14
-  __DATA.__data: 0x15c0
-  __DATA.__bss: 0x800
+  __AUTH_CONST.__auth_ptr: 0x130
+  __AUTH.__objc_data: 0xe8
+  __DATA.__objc_ivar: 0xf34
+  __DATA.__data: 0x15c8
+  __DATA.__bss: 0x880
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x2a98
   __DATA_DIRTY.__data: 0x1a8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 4411
-  Symbols:   7356
+  Functions: 4454
+  Symbols:   7410
   CStrings:  0
 
Symbols:
+ +[SPCommand disableBTCSReflectorWithBeaconUUID:]
+ +[SPCommand enableBTCSReflectorWithBeaconUUID:withOptions:]
+ +[SPFindingSessionEvent supportsSecureCoding]
+ -[SPBTFindingSession didUpdateAccessoryStateCallback]
+ -[SPBTFindingSession setDidUpdateAccessoryStateCallback:]
+ -[SPBTFindingSession startBTCSForBeacon:completion:]
+ -[SPBTFindingSession stopBTCSForBeacon:completion:]
+ -[SPBTFindingSession updateAccessoryEvent:]
+ -[SPBeaconManager submitDeviceEvent:source:timestamp:attachedTo:completion:]
+ -[SPCommand antennaSelectionOption]
+ -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:playSoundOptions:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:antennaSelectionOptions:lockModePasscode:emailUpdates:]
+ -[SPCommand setAntennaSelectionOption:]
+ -[SPFindingSessionEvent .cxx_destruct]
+ -[SPFindingSessionEvent beaconID]
+ -[SPFindingSessionEvent copyWithZone:]
+ -[SPFindingSessionEvent description]
+ -[SPFindingSessionEvent encodeWithCoder:]
+ -[SPFindingSessionEvent event]
+ -[SPFindingSessionEvent initWithBeaconID:event:peripheralID:motionState:]
+ -[SPFindingSessionEvent initWithCoder:]
+ -[SPFindingSessionEvent motionState]
+ -[SPFindingSessionEvent peripheralID]
+ -[SPOwnerSessionLocationFetch callbackQueue]
+ -[SPOwnerSessionLocationFetch queue]
+ _OBJC_CLASS_$_SPFindingSessionEvent
+ _OBJC_IVAR_$_SPBTFindingSession._didUpdateAccessoryStateCallback
+ _OBJC_IVAR_$_SPCommand._antennaSelectionOption
+ _OBJC_IVAR_$_SPFindingSessionEvent._beaconID
+ _OBJC_IVAR_$_SPFindingSessionEvent._event
+ _OBJC_IVAR_$_SPFindingSessionEvent._motionState
+ _OBJC_IVAR_$_SPFindingSessionEvent._peripheralID
+ _OBJC_IVAR_$_SPOwnerSessionLocationFetch._callbackQueue
+ _OBJC_IVAR_$_SPOwnerSessionLocationFetch._queue
+ _OBJC_METACLASS_$_SPFindingSessionEvent
+ _OUTLINED_FUNCTION_4
+ _SPBeaconTaskNameBTChannelSounding
+ _SPBeaconTaskNameDisableBTCSReflector
+ _SPBeaconTaskNameEnableBTCSReflector
+ __OBJC_$_CLASS_METHODS_SPFindingSessionEvent
+ __OBJC_$_CLASS_PROP_LIST_SPFindingSessionEvent
+ __OBJC_$_INSTANCE_METHODS_SPFindingSessionEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPFindingSessionEvent
+ __OBJC_$_PROP_LIST_SPFindingSessionEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPFindingSessionEvent
+ __OBJC_CLASS_RO_$_SPFindingSessionEvent
+ __OBJC_METACLASS_RO_$_SPFindingSessionEvent
+ ___43-[SPBTFindingSession updateAccessoryEvent:]_block_invoke
+ ___51-[SPBTFindingSession stopBTCSForBeacon:completion:]_block_invoke
+ ___51-[SPBTFindingSession stopBTCSForBeacon:completion:]_block_invoke_2
+ ___51-[SPOwnerSessionLocationFetch invalidationHandler:]_block_invoke
+ ___52-[SPBTFindingSession startBTCSForBeacon:completion:]_block_invoke
+ ___52-[SPBTFindingSession startBTCSForBeacon:completion:]_block_invoke_2
+ ___61-[SPOwnerSessionLocationFetch locationForContext:completion:]_block_invoke_2
+ ___72-[SPOwnerSessionLocationFetch unsubscribeLocationUpdatesWithCompletion:]_block_invoke
+ ___76-[SPBeaconManager submitDeviceEvent:source:timestamp:attachedTo:completion:]_block_invoke
+ ___78-[SPOwnerSessionLocationFetch subscribeAndFetchLocationForContext:completion:]_block_invoke_3
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0ls32l8s40l8s48l8w56l8
+ ___block_descriptor_76_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ _symbolic _____ So25SPFindingSessionEventTypeV
- -[SPBeaconManager submitDeviceEvent:source:attachedTo:completion:]
- -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:playSoundOptions:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:lockModePasscode:emailUpdates:]
- GCC_except_table19
- ___66-[SPBeaconManager submitDeviceEvent:source:attachedTo:completion:]_block_invoke
- ___block_descriptor_68_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
```
