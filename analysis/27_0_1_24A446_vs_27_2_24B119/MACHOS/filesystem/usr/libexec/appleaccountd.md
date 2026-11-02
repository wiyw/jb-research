## appleaccountd

> `/usr/libexec/appleaccountd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__objc_classname`
- `__TEXT.__cstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__info_plist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`

```diff

-1067.0.0.0.0
-  __TEXT.__text: 0x3f2e74
-  __TEXT.__auth_stubs: 0x37d0
-  __TEXT.__objc_stubs: 0x4d40
+1069.125.7.0.0
+  __TEXT.__text: 0x3f7e7c
+  __TEXT.__auth_stubs: 0x3800
+  __TEXT.__objc_stubs: 0x4de0
   __TEXT.__objc_methlist: 0xf80
-  __TEXT.__objc_methname: 0x77d5
+  __TEXT.__objc_methname: 0x78b5
   __TEXT.__objc_classname: 0x2e9d
   __TEXT.__cstring: 0x46a9
-  __TEXT.__objc_methtype: 0x2024
+  __TEXT.__objc_methtype: 0x2044
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__const: 0x13350
-  __TEXT.__constg_swiftt: 0xc5f4
-  __TEXT.__swift5_typeref: 0x7993
+  __TEXT.__const: 0x133b0
+  __TEXT.__constg_swiftt: 0xc680
+  __TEXT.__swift5_typeref: 0x79eb
   __TEXT.__swift5_builtin: 0x2bc
   __TEXT.__swift5_reflstr: 0x66d5
-  __TEXT.__swift5_fieldmd: 0x6638
-  __TEXT.__swift5_assocty: 0x950
-  __TEXT.__swift5_proto: 0xc74
-  __TEXT.__swift5_types: 0x638
-  __TEXT.__swift5_capture: 0x65fc
-  __TEXT.__oslogstring: 0x20ccd
+  __TEXT.__swift5_fieldmd: 0x66a0
+  __TEXT.__swift5_assocty: 0x938
+  __TEXT.__swift5_proto: 0xc68
+  __TEXT.__swift5_types: 0x63c
+  __TEXT.__swift5_capture: 0x66a4
+  __TEXT.__oslogstring: 0x212dd
   __TEXT.__swift5_protos: 0x22c
-  __TEXT.__swift_as_entry: 0x674
-  __TEXT.__swift_as_ret: 0x87c
-  __TEXT.__swift_as_cont: 0x11c4
+  __TEXT.__swift_as_entry: 0x680
+  __TEXT.__swift_as_ret: 0x88c
+  __TEXT.__swift_as_cont: 0x11d8
   __TEXT.__swift5_acfuncs: 0xb4
   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__info_plist: 0x7ae
-  __TEXT.__unwind_info: 0x8510
-  __TEXT.__eh_frame: 0x146cc
-  __DATA_CONST.__const: 0x13f60
+  __TEXT.__unwind_info: 0x85a8
+  __TEXT.__eh_frame: 0x14884
+  __DATA_CONST.__const: 0x14048
   __DATA_CONST.__objc_classlist: 0x600
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1a0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xd0
   __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__auth_got: 0x1bf0
-  __DATA_CONST.__got: 0x1580
-  __DATA_CONST.__auth_ptr: 0x1678
-  __DATA.__objc_const: 0x1e0f0
-  __DATA.__objc_selrefs: 0x1720
+  __DATA_CONST.__auth_got: 0x1c08
+  __DATA_CONST.__got: 0x1568
+  __DATA_CONST.__auth_ptr: 0x16a0
+  __DATA.__objc_const: 0x1e170
+  __DATA.__objc_selrefs: 0x1748
   __DATA.__objc_ivar: 0x4
   __DATA.__objc_data: 0x3360
-  __DATA.__data: 0x14300
+  __DATA.__data: 0x144a0
   __DATA.__objc_stublist: 0x68
-  __DATA.__bss: 0x13980
-  __DATA.__common: 0x4b8
+  __DATA.__bss: 0x13800
+  __DATA.__common: 0x4e0
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CloudKit.framework/CloudKit
   - /System/Library/Frameworks/Combine.framework/Combine

   - /System/Library/PrivateFrameworks/StorageContainersPrivate.framework/StorageContainersPrivate
   - /System/Library/PrivateFrameworks/XPCDistributed.framework/XPCDistributed
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10245
-  Symbols:   1815
+  Functions: 10282
+  Symbols:   1818
   CStrings:  0
 
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _$s14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV10auditTokenSo0F8_token_taSgvg
+ _$s20IntelligencePlatform19PersonEntityTagTypeOMn
+ _SecTaskCopySigningIdentifier
+ _SecTaskCreateWithAuditToken
+ _objc_retain_x1
- _$s10Foundation4DateVSLAAMc
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _$sSL2geoiySbx_xtFZTj
- _swift_conformsToProtocol2
```
