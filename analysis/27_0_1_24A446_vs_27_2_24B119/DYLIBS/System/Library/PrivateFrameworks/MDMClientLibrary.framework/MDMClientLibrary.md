## MDMClientLibrary

> `/System/Library/PrivateFrameworks/MDMClientLibrary.framework/MDMClientLibrary`

```diff

-113.2.5.0.0
-  __TEXT.__text: 0x1e750
-  __TEXT.__objc_methlist: 0x1db4
+113.40.20.0.0
+  __TEXT.__text: 0x1e938
+  __TEXT.__objc_methlist: 0x1df4
   __TEXT.__const: 0xe1
-  __TEXT.__gcc_except_tab: 0x50c
-  __TEXT.__cstring: 0x2475
-  __TEXT.__oslogstring: 0x30b8
+  __TEXT.__gcc_except_tab: 0x4d8
+  __TEXT.__cstring: 0x245f
+  __TEXT.__oslogstring: 0x313f
   __TEXT.__dlopen_cstrs: 0xb7
   __TEXT.__unwind_info: 0x850
   __TEXT.__objc_stubs: 0x0

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x11b8
+  __DATA_CONST.__const: 0x1178
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13b0
+  __DATA_CONST.__objc_selrefs: 0x13d8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x78
-  __DATA_CONST.__got: 0x3c8
+  __DATA_CONST.__got: 0x3d0
   __AUTH_CONST.__const: 0x3c0
-  __AUTH_CONST.__cfstring: 0x3320
-  __AUTH_CONST.__objc_const: 0x3a10
+  __AUTH_CONST.__cfstring: 0x3380
+  __AUTH_CONST.__objc_const: 0x3a18
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1e0
   __DATA.__objc_ivar: 0x124
-  __DATA.__data: 0x540
   __DATA.__bss: 0x110
-  __DATA_DIRTY.__objc_data: 0x5f0
+  __DATA_DIRTY.__objc_data: 0x7d0
+  __DATA_DIRTY.__data: 0x540
   __DATA_DIRTY.__bss: 0x50
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 685
-  Symbols:   1666
+  Functions: 688
+  Symbols:   1669
   CStrings:  0
 
Symbols:
+ +[MDMCheckInRequest responseFromTransaction:]
+ +[MDMMAIDBearerTokenAuthenticator _createMissingAltDSIDErrorWithAccountID:]
+ -[MDMClientCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ -[MDMCloudConfiguration organizationID]
+ -[MDMCloudConfiguration organizationType]
+ -[MDMConfigurationBase _nameForChannelType:]
+ GCC_except_table108
+ GCC_except_table112
+ GCC_except_table15
+ GCC_except_table23
+ GCC_except_table43
+ GCC_except_table89
+ ___87-[MDMClientCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
+ _kCCOrganizationIDKey
+ _kCCOrganizationTypeKey
+ _kMDMChannelStringDevice
+ _kMDMChannelStringUser
- +[MDMProvisioningProfileTrust manualTrustSignerIdentities:]
- +[MDMProvisioningProfileTrust signerIdentitiesFromProvisioningProfileUUID:]
- GCC_except_table106
- GCC_except_table110
- GCC_except_table17
- GCC_except_table21
- GCC_except_table25
- GCC_except_table27
- GCC_except_table47
- GCC_except_table87
- ___59+[MDMProvisioningProfileTrust manualTrustSignerIdentities:]_block_invoke
- ___75+[MDMProvisioningProfileTrust signerIdentitiesFromProvisioningProfileUUID:]_block_invoke
- ___block_descriptor_40_e8_32bs_e57_v32?0"MDMHTTPTransaction"8"NSDictionary"16"NSError"24ls32l8
- ___block_descriptor_40_e8_32s_e22_v24?0^v8"NSString"16ls32l8
- ___block_descriptor_48_e8_32s40r_e9_B16?0^v8ls32l8r40l8
```
