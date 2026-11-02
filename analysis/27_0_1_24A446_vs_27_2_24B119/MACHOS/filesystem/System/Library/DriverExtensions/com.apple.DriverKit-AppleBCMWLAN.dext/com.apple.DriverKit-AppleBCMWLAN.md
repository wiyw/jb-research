## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__osclassinfo`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-1580.73.0.0.0
-  __TEXT.__text: 0x2914f8
+1582.9.0.0.0
+  __TEXT.__text: 0x2920c8
   __TEXT.__auth_stubs: 0x25c0
   __TEXT.__init_offsets: 0x1bc
-  __TEXT.__cstring: 0x831be
+  __TEXT.__cstring: 0x83612
   __TEXT.__const: 0x7f168
   __TEXT.__oslogstring: 0x1f27
-  __TEXT.__unwind_info: 0x5fd0
+  __TEXT.__unwind_info: 0x5ff8
   __TEXT.__eh_frame: 0x38
-  __DATA_CONST.__const: 0x21148
+  __DATA_CONST.__const: 0x211c0
   __DATA_CONST.__osclassinfo: 0x388
   __DATA_CONST.__auth_got: 0x12e0
   __DATA_CONST.__got: 0x108

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 14188
-  Symbols:   12064
+  Functions: 14201
+  Symbols:   12073
   CStrings:  0
 
Symbols:
+ __ZN16AppleBCMWLANCore33checkForAdaptive11rFromASRSupportEv
+ __ZN23IO80211SkywalkInterface20postPeerPresenceDoneEP10ether_addrb
+ __ZN24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
+ __ZN30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
+ __ZN30AppleBCMWLANProximityInterface27applyInitialChannelSequenceEPKc
+ __ZThn112_N30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
+ __ZThn128_N30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
+ __ZThn80_N23IO80211SkywalkInterface20postPeerPresenceDoneEP10ether_addrb
+ __ZThn96_N24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
```
