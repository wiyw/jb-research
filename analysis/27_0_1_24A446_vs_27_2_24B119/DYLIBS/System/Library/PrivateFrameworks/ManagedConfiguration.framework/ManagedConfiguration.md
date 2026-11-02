## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

```diff

-2483.2.6.0.0
-  __TEXT.__text: 0xf7134
-  __TEXT.__objc_methlist: 0xb33c
-  __TEXT.__const: 0x152c
-  __TEXT.__cstring: 0x186ab
-  __TEXT.__oslogstring: 0x9798
-  __TEXT.__gcc_except_tab: 0x1040
+2483.40.19.0.0
+  __TEXT.__text: 0xf7b38
+  __TEXT.__objc_methlist: 0xb364
+  __TEXT.__const: 0x1584
+  __TEXT.__cstring: 0x1882f
+  __TEXT.__oslogstring: 0x9892
+  __TEXT.__gcc_except_tab: 0x1080
   __TEXT.__dlopen_cstrs: 0xac
   __TEXT.__ustring: 0x50
   __TEXT.__unwind_info: 0x3288

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4e40
+  __DATA_CONST.__const: 0x4e10
   __DATA_CONST.__objc_classlist: 0x3d8
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5e18
+  __DATA_CONST.__objc_selrefs: 0x5e50
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x2d0
   __DATA_CONST.__objc_arraydata: 0xe8
   __DATA_CONST.__got: 0xac0
   __AUTH_CONST.__const: 0x2130
-  __AUTH_CONST.__cfstring: 0x19640
-  __AUTH_CONST.__objc_const: 0xd808
+  __AUTH_CONST.__cfstring: 0x197e0
+  __AUTH_CONST.__objc_const: 0xd850
   __AUTH_CONST.__objc_intobj: 0x4f8
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__auth_got: 0xbf8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x23f0
-  __DATA.__objc_ivar: 0x994
-  __DATA.__data: 0xca0
-  __DATA.__bss: 0xc89
+  __AUTH.__objc_data: 0x2350
+  __DATA.__objc_ivar: 0x99c
+  __DATA.__data: 0xcc8
+  __DATA.__bss: 0xc99
   __DATA.__common: 0x28
-  __DATA_DIRTY.__objc_data: 0x280
+  __DATA_DIRTY.__objc_data: 0x320
   __DATA_DIRTY.__bss: 0x228
   __DATA_DIRTY.__common: 0x68
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/liblockdown.dylib
   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5817
-  Symbols:   9720
+  Functions: 5828
+  Symbols:   9745
   CStrings:  0
 
Symbols:
+ +[MCManifest _fileDataIfPresentAtPath:error:]
+ +[MCManifest installedProfileDataWithIdentifier:error:]
+ +[MCManifest installedSystemProfileDataWithIdentifier:error:]
+ +[MCManifest installedUserProfileDataWithIdentifier:error:]
+ -[MCManifest identifiersOfProfilesWithFilterFlags:error:]
+ -[MCManifest setSystemManifestLoadError:]
+ -[MCManifest setUserManifestLoadError:]
+ -[MCManifest systemManifestLoadError]
+ -[MCManifest userManifestLoadError]
+ -[MCNotifier sendAllowCloudSyncChangedNotification]
+ -[MCProfileConnection _allowCloudSyncDidChange:]
+ -[MCProfileConnection(Misc) isPairingWithHomeDevicesAllowed]
+ GCC_except_table291
+ GCC_except_table374
+ GCC_except_table45
+ GCC_except_table53
+ GCC_except_table93
+ _MCAllowCloudSyncChangedNotification
+ _MCFeaturePairingWithHomeDevicesAllowed
+ _MCGestaltIsHomeAccessory
+ _MCGestaltIsHomeAccessory.isHomeAccessory
+ _MCGestaltIsHomeAccessory.onceToken
+ _MCRemoteManagementTransferProfileAccount
+ _MCSendAllowCloudSyncChangedNotification
+ _MCTakeoverErrorDomain
+ _OBJC_IVAR_$_MCManifest._systemManifestLoadError
+ _OBJC_IVAR_$_MCManifest._userManifestLoadError
+ __OBJC_$_PROP_LIST_MCManifest
+ ___48-[MCProfileConnection _allowCloudSyncDidChange:]_block_invoke
+ ___48-[MCProfileConnection _allowCloudSyncDidChange:]_block_invoke_2
+ ___57-[MCManifest identifiersOfProfilesWithFilterFlags:error:]_block_invoke
+ ___MCGestaltIsHomeAccessory_block_invoke
+ ___MCRemoteManagementTransferProfileAccount_block_invoke
+ ___block_descriptor_64_e8_32s40s48r56r_e20_v20?0B8"NSError"12lr48l8r56l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40r48r56r64r_e5_v8?0lr40l8s32l8r48l8r56l8r64l8
+ ___der_key_state_abs_last_mesa_auth
+ ___der_key_state_abs_last_mesa_unlock
+ ___der_key_state_abs_last_passcode_auth
+ ___der_key_state_abs_last_passcode_unlock
+ ___der_key_state_abs_lock_time
+ _der_key_state_abs_last_mesa_auth
+ _der_key_state_abs_last_mesa_unlock
+ _der_key_state_abs_last_passcode_auth
+ _der_key_state_abs_last_passcode_unlock
+ _der_key_state_abs_lock_time
- -[MCProfileConnection(Profiles) provisiongProfileUUIDsForSignerIdentity:]
- -[MCProfileConnection(Profiles) removeTrustedCodeSigningIdentities:]
- -[MCProfileConnection(Profiles) signerIdentityForBundleID:]
- -[MCProfileConnection(Profiles) syncTrustedCodeSigningIdentitiesWithOutError:]
- -[MCProfileConnection(Profiles) verifiedTrustedCodeSigningIdentities]
- GCC_except_table102
- GCC_except_table116
- GCC_except_table290
- GCC_except_table373
- GCC_except_table43
- GCC_except_table89
- GCC_except_table99
- ___59-[MCProfileConnection(Profiles) signerIdentityForBundleID:]_block_invoke
- ___69-[MCProfileConnection(Profiles) verifiedTrustedCodeSigningIdentities]_block_invoke
- ___73-[MCProfileConnection(Profiles) provisiongProfileUUIDsForSignerIdentity:]_block_invoke
- ___78-[MCProfileConnection(Profiles) syncTrustedCodeSigningIdentitiesWithOutError:]_block_invoke
- ___block_descriptor_40_e8_32r_e27_v24?0"NSSet"8"NSError"16lr32l8
- ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
- ___block_descriptor_48_e8_32s40r_e27_v24?0"NSSet"8"NSError"16ls32l8r40l8
- ___block_descriptor_48_e8_32s40r_e30_v24?0"NSString"8"NSError"16ls32l8r40l8
```
