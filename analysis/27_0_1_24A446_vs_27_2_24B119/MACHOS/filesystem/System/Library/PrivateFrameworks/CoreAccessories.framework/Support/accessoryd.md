## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__info_plist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1216.2.2.0.0
-  __TEXT.__text: 0x19fdb0
+1219.42.3.0.0
+  __TEXT.__text: 0x1a0db4
   __TEXT.__auth_stubs: 0x1890
-  __TEXT.__objc_stubs: 0x95c0
-  __TEXT.__objc_methlist: 0x6eac
-  __TEXT.__const: 0x2110
+  __TEXT.__objc_stubs: 0x9620
+  __TEXT.__objc_methlist: 0x6edc
+  __TEXT.__const: 0x2120
   __TEXT.__gcc_except_tab: 0x2110
   __TEXT.__objc_classname: 0xfd3
-  __TEXT.__objc_methname: 0xfed6
-  __TEXT.__objc_methtype: 0x324c
-  __TEXT.__cstring: 0xe5f5
-  __TEXT.__oslogstring: 0x390eb
+  __TEXT.__objc_methname: 0xff4a
+  __TEXT.__objc_methtype: 0x3259
+  __TEXT.__cstring: 0xe71b
+  __TEXT.__oslogstring: 0x3949d
   __TEXT.__ustring: 0x232
   __TEXT.__info_plist: 0x54e
-  __TEXT.__unwind_info: 0x4830
-  __DATA_CONST.__const: 0xa2d8
-  __DATA_CONST.__cfstring: 0x73c0
+  __TEXT.__unwind_info: 0x4840
+  __DATA_CONST.__const: 0xa310
+  __DATA_CONST.__cfstring: 0x74a0
   __DATA_CONST.__objc_classlist: 0x318
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x178

   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_intobj: 0x108
   __DATA_CONST.__auth_got: 0xc58
-  __DATA_CONST.__got: 0xef8
+  __DATA_CONST.__got: 0xf10
   __DATA_CONST.__auth_ptr: 0x98
-  __DATA.__objc_const: 0xb080
-  __DATA.__objc_selrefs: 0x33c0
-  __DATA.__objc_ivar: 0x7a0
+  __DATA.__objc_const: 0xb0b0
+  __DATA.__objc_selrefs: 0x33d8
+  __DATA.__objc_ivar: 0x7a4
   __DATA.__objc_data: 0x1ef0
   __DATA.__data: 0x1940
-  __DATA.__bss: 0x1618
+  __DATA.__bss: 0x1628
   __DATA.__common: 0x28
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 8706
-  Symbols:   11697
+  Functions: 8718
+  Symbols:   11717
   CStrings:  0
 
Symbols:
+ -[ACCExternalAccessory EAPPIDVersionUID]
+ -[ACCTransportServer isConnectionEntitled:]
+ -[ACCTransportServer shouldAcceptConnection:]
+ -[NSXPCConnection(Entitlements) hasBooleanEntitlement:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(acc_internal_settings.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-99a82b46828023f8242335e38ab7ad3e.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-8384a129a427130a58837829b535c390.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-149608d2b889e4bb53654e2f81908443.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-e69fdb53fd1f0658925603191da5d672.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-076921ac1196012b7583c4277b58b534.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-37be0b150167e50a2ed6beb99de22ce3.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-f26bacc579a0b438b4edaaf906f6a406.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-62c91a4923ba504f1c6475014d0d62dc.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-c830f56ecc1ccbe834191f52d90c42c5.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-617039433a3c39fa3d34cdbed04f845b.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-fd3867ab21e4c8bde55831e4ecad3d80.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-4c77e5eac4d875a8c809adab7fc0dbff.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-d66ee8de7c729ee1c3e47c0ffab928af.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-9e6c942a78d1f16ee9a9010c4d86bd55.o)
+ OBJC_IVAR_$_ACCExternalAccessory._EAPPIDVersionUID
+ ____genericMFi_appLaunch_setDialogActive_block_invoke
+ ____genericMFi_appLaunch_setDialogActive_block_invoke_2
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ __createError
+ __genericMFi_appLaunch_setDialogActive
+ _acc_internalSettings_boolForKey
+ _kACCExternalAccessoryPPIDVersionUIDKey
+ _kCFACCInfo_PPIDVersionUID
+ _kCFACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
+ _kCFACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
+ _kCFACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
+ _kCFACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
+ _kCFErrorUnderlyingErrorKey
+ _objc_msgSend$EAPPIDVersionUID
+ _objc_msgSend$hasBooleanEntitlement:
+ _objc_msgSend$isConnectionEntitled:
+ acc_internalSettings_boolForKey
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-019ae603d8dc1916f3f174dbee15c627.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-9e7ae0279713610c45dd45353c559a7e.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-3ddfda8a63119859f5b14b3f1b605f6c.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-b63500f7e934b6af4db0708ea018a493.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-80c32cc5c01954b7c782c8d4a2058b8f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-19ad6d8be147053e768386ae23119c7a.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-6ab91b4ee8a78c8edf57750bf9d931d4.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-85618de6e74bd8ca5a62508d02e09c6a.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-f463c0553cb4abcbc5e87cd3c4e2078d.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-21bd53e832b4d5d2c14dc98f2899be5f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-f0c64433c05768d694ca1414363320cd.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-8c74001941e320c1fd60df76badb29da.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-a4e2ec8b55a562dca16e81f81fcd042e.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-4fecf7636e482b76ad79003cfdd0d64e.o)
- _ACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
- _ACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
- _ACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
- _ACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
- ____genericMFi_appLaunch_RequestUserForAppLaunch_block_invoke_2
- ____genericMFi_appLaunch_RequestUserForAppLaunch_block_invoke_3
```
