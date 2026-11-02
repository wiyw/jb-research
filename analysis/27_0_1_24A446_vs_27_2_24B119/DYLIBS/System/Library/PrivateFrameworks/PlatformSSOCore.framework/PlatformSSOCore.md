## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

```diff

-643.0.47.0.0
-  __TEXT.__text: 0x97b10
-  __TEXT.__objc_methlist: 0x62d8
-  __TEXT.__const: 0x19ac
-  __TEXT.__cstring: 0xad28
-  __TEXT.__oslogstring: 0x1e67
+643.40.34.0.0
+  __TEXT.__text: 0x99c18
+  __TEXT.__objc_methlist: 0x63b0
+  __TEXT.__const: 0x1a14
+  __TEXT.__cstring: 0xb2a8
+  __TEXT.__oslogstring: 0x2067
+  __TEXT.__ustring: 0x2c
   __TEXT.__gcc_except_tab: 0x6f4
   __TEXT.__dlopen_cstrs: 0xa6
   __TEXT.__swift5_typeref: 0x166

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x1c
   __TEXT.__swift5_types: 0x30
-  __TEXT.__unwind_info: 0x2178
+  __TEXT.__unwind_info: 0x21f0
   __TEXT.__eh_frame: 0x568
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2600
-  __DATA_CONST.__objc_classlist: 0x4d8
+  __DATA_CONST.__const: 0x2630
+  __DATA_CONST.__objc_classlist: 0x4e0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2d10
+  __DATA_CONST.__objc_selrefs: 0x2dd0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x1e8
-  __DATA_CONST.__objc_arraydata: 0x58
-  __DATA_CONST.__got: 0x9b0
-  __AUTH_CONST.__const: 0xc20
-  __AUTH_CONST.__cfstring: 0x7b20
-  __AUTH_CONST.__objc_const: 0x14d28
-  __AUTH_CONST.__objc_intobj: 0x228
+  __DATA_CONST.__objc_superrefs: 0x1f0
+  __DATA_CONST.__objc_arraydata: 0x120
+  __DATA_CONST.__got: 0x9d8
+  __AUTH_CONST.__const: 0xce0
+  __AUTH_CONST.__cfstring: 0x80c0
+  __AUTH_CONST.__objc_const: 0x14e50
+  __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__objc_arrayobj: 0x78
+  __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0xdb8
   __AUTH_CONST.__auth_ptr: 0x1c0
-  __AUTH.__objc_data: 0x35a0
+  __AUTH.__objc_data: 0x35f0
   __AUTH.__data: 0x1a8
-  __DATA.__objc_ivar: 0x654
-  __DATA.__data: 0x1228
-  __DATA.__bss: 0x771
+  __DATA.__objc_ivar: 0x65c
+  __DATA.__data: 0x1250
+  __DATA.__bss: 0x7d1
   __DATA.__common: 0x88
   __DATA_DIRTY.__objc_data: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3850
-  Symbols:   5836
+  Functions: 3894
+  Symbols:   5899
   CStrings:  0
 
Symbols:
+ +[POConstantCoreUtil validatedAdditionalHTTPHeaders:]
+ +[POCoreConfigurationUtil accountDisplayNameForDeviceConfiguration:loginConfiguration:]
+ +[POCoreConfigurationUtil alwaysUseLoginUIOverride]
+ +[POCoreConfigurationUtil shouldUsePlatformSSOLoginUIForDeviceConfiguration:]
+ +[POKeychainAccess isRunningInTestProcess]
+ -[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]
+ -[PODeviceConfiguration additionalHTTPHeaders]
+ -[PODeviceConfiguration alwaysUseLoginUI]
+ -[PODeviceConfiguration requiresPlatformSSOLoginUI]
+ -[PODeviceConfiguration setAdditionalHTTPHeaders:]
+ -[PODeviceConfiguration setAlwaysUseLoginUI:]
+ -[PODeviceConfiguration supportsOpenID]
+ -[POKeychainHelper .cxx_destruct]
+ -[POKeychainHelper init]
+ -[POKeychainHelper keychainAccess]
+ -[POKeychainHelper setKeychainAccess:]
+ -[POTokenHelper findInfoForTokenId:uid:]
+ GCC_except_table128
+ GCC_except_table153
+ GCC_except_table56
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_IVAR_$_PODeviceConfiguration._additionalHTTPHeaders
+ _OBJC_IVAR_$_PODeviceConfiguration._alwaysUseLoginUI
+ _OBJC_IVAR_$_POKeychainHelper._keychainAccess
+ _OBJC_METACLASS_$_POKeychainAccess
+ _POIsReservedHTTPHeaderField.onceToken
+ _POIsReservedHTTPHeaderField.reservedFields
+ _POIsValidHTTPHeaderFieldName.illegalFieldCharacters
+ _POIsValidHTTPHeaderFieldName.onceToken
+ _POIsValidHTTPHeaderFieldValue.illegalValueCharacters
+ _POIsValidHTTPHeaderFieldValue.onceToken
+ _PO_LOG_POConstantCoreUtil
+ _PO_LOG_POConstantCoreUtil.log
+ _PO_LOG_POConstantCoreUtil.once
+ _PO_LOG_POKeychainAccess.log
+ _PO_LOG_POKeychainAccess.once
+ __OBJC_$_CLASS_METHODS_POKeychainAccess
+ __OBJC_$_CLASS_PROP_LIST_POKeychainAccess
+ __OBJC_$_INSTANCE_VARIABLES_POKeychainHelper
+ __OBJC_$_PROP_LIST_POKeychainHelper
+ __OBJC_CLASS_RO_$_POKeychainAccess
+ __OBJC_METACLASS_RO_$_POKeychainAccess
+ ___42+[POKeychainAccess isRunningInTestProcess]_block_invoke
+ ___53+[POConstantCoreUtil validatedAdditionalHTTPHeaders:]_block_invoke
+ ___69-[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]_block_invoke
+ ___POAdditionalHTTPHeadersForDisplay_block_invoke
+ ___POIsReservedHTTPHeaderField_block_invoke
+ ___POIsValidHTTPHeaderFieldName_block_invoke
+ ___POIsValidHTTPHeaderFieldValue_block_invoke
+ ___PO_LOG_POConstantCoreUtil_block_invoke
+ ___PO_LOG_POKeychainAccess_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
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
+ _isRunningInTestProcess.isTest
+ _isRunningInTestProcess.onceToken
+ _kPOErrorDomain
- -[POUserConfiguration newUser]
- GCC_except_table126
- GCC_except_table151
- _OBJC_IVAR_$_POUserConfiguration._newUser
```
