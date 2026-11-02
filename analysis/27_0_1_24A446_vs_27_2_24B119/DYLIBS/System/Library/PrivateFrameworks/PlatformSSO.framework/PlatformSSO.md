## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

```diff

-643.0.47.0.0
-  __TEXT.__text: 0x5c068
-  __TEXT.__objc_methlist: 0x358c
+643.40.34.0.0
+  __TEXT.__text: 0x5dd74
+  __TEXT.__objc_methlist: 0x37cc
   __TEXT.__const: 0x322
-  __TEXT.__cstring: 0x8296
-  __TEXT.__oslogstring: 0x28f1
-  __TEXT.__gcc_except_tab: 0x1448
+  __TEXT.__cstring: 0x83e6
+  __TEXT.__oslogstring: 0x2c81
+  __TEXT.__gcc_except_tab: 0x1554
   __TEXT.__dlopen_cstrs: 0x162
   __TEXT.__swift5_typeref: 0xd9
   __TEXT.__swift5_capture: 0x14c

   __TEXT.__swift_as_entry: 0x30
   __TEXT.__swift_as_ret: 0x54
   __TEXT.__swift_as_cont: 0x58
-  __TEXT.__unwind_info: 0x15b8
+  __TEXT.__unwind_info: 0x1640
   __TEXT.__eh_frame: 0x628
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xf78
-  __DATA_CONST.__objc_classlist: 0x108
+  __DATA_CONST.__const: 0xfa0
+  __DATA_CONST.__objc_classlist: 0x110
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2400
+  __DATA_CONST.__objc_selrefs: 0x2538
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0xc8
+  __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x440
+  __DATA_CONST.__got: 0x468
   __AUTH_CONST.__const: 0xc80
-  __AUTH_CONST.__cfstring: 0x3a40
-  __AUTH_CONST.__objc_const: 0x8640
+  __AUTH_CONST.__cfstring: 0x3ae0
+  __AUTH_CONST.__objc_const: 0x8948
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x758
+  __AUTH_CONST.__auth_got: 0x760
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xa00
-  __DATA.__objc_ivar: 0x390
+  __AUTH.__objc_data: 0xa50
+  __DATA.__objc_ivar: 0x3bc
   __DATA.__data: 0x600
   __DATA.__bss: 0x340
   __DATA_DIRTY.__objc_data: 0x50

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2146
-  Symbols:   2662
+  Functions: 2206
+  Symbols:   2741
   CStrings:  0
 
Symbols:
+ +[POSoftwareUpdateCredentialPolicy credentialsWanted]
+ +[POSoftwareUpdateCredentialPolicy harvestPassword:forUserId:]
+ -[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]
+ -[POAgentAuthenticationProcess keychainAccess]
+ -[POAgentAuthenticationProcess postAuthenticationNotificationForEvaluationError:]
+ -[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]
+ -[POAgentAuthenticationProcess setKeychainAccess:]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairLock:]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairRequested:]
+ -[POAgentAuthenticationProcess shouldRunConfigurationChangeOnUnlock]
+ -[POAgentAuthenticationProcess userRegistrationRepairLock]
+ -[POAgentAuthenticationProcess userRegistrationRepairRequested]
+ -[POAgentProcess configurationManagerForUserName:]
+ -[POAgentProcess keychainAccess]
+ -[POAgentProcess setKeychainAccess:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ -[POAuthPluginProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POConfigurationManager keychainAccess]
+ -[POConfigurationManager setKeychainAccess:]
+ -[PODaemonConnection resetTempSessionAccountWithCompletion:]
+ -[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]
+ -[PODirectoryServices .cxx_destruct]
+ -[PODirectoryServices init]
+ -[PODirectoryServices keychainAccess]
+ -[PODirectoryServices setKeychainAccess:]
+ -[POProfile additionalHTTPHeaders]
+ -[POProfile alwaysUseLoginUI]
+ -[POProfile setAlwaysUseLoginUI:]
+ -[PORegistrationManager claimDeviceRegistrationStart]
+ -[PORegistrationManager claimRegistrationStartResumingUnfinishedDeviceRegistration:]
+ -[PORegistrationManager claimUserRegistrationStart]
+ -[PORegistrationManager publishRegistrationContext:claim:]
+ -[PORegistrationManager publishRegistrationContextWithState:claim:]
+ -[PORegistrationManager registrationContextLock]
+ -[PORegistrationManager registrationGeneration]
+ -[PORegistrationManager registrationIsInProgress]
+ -[PORegistrationManager registrationStarting]
+ -[PORegistrationManager releaseRegistrationStart:]
+ -[PORegistrationManager setRegistrationContextLock:]
+ -[PORegistrationManager setRegistrationGeneration:]
+ -[PORegistrationManager setRegistrationStarting:]
+ -[PORegistrationManager setUserAuthPluginProcess:]
+ -[PORegistrationManager storeCredentialContext:]
+ -[PORegistrationManager updatePasswordHint]
+ -[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ GCC_except_table104
+ GCC_except_table126
+ GCC_except_table127
+ GCC_except_table133
+ GCC_except_table134
+ GCC_except_table16
+ GCC_except_table185
+ GCC_except_table31
+ GCC_except_table36
+ GCC_except_table57
+ GCC_except_table68
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table71
+ GCC_except_table74
+ GCC_except_table93
+ GCC_except_table95
+ GCC_except_table98
+ _LAErrorDomain
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_CLASS_$_POSoftwareUpdateCredentialPolicy
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._keychainAccess
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairLock
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairRequested
+ _OBJC_IVAR_$_POAgentProcess._keychainAccess
+ _OBJC_IVAR_$_POConfigurationManager._keychainAccess
+ _OBJC_IVAR_$_PODirectoryServices._keychainAccess
+ _OBJC_IVAR_$_POProfile._additionalHTTPHeaders
+ _OBJC_IVAR_$_POProfile._alwaysUseLoginUI
+ _OBJC_IVAR_$_PORegistrationManager._registrationContextLock
+ _OBJC_IVAR_$_PORegistrationManager._registrationGeneration
+ _OBJC_IVAR_$_PORegistrationManager._registrationStarting
+ _OBJC_METACLASS_$_POSoftwareUpdateCredentialPolicy
+ _POExtensionNormalizedTeamIdentifier
+ __OBJC_$_CLASS_METHODS_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_CLASS_PROP_LIST_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_INSTANCE_VARIABLES_PODirectoryServices
+ __OBJC_CLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ __OBJC_METACLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ ___104-[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]_block_invoke
+ ___48-[PORegistrationManager storeCredentialContext:]_block_invoke
+ ___60-[PODaemonConnection resetTempSessionAccountWithCompletion:]_block_invoke
+ ___69-[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke_2
+ ___85-[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48bs_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
+ _kPOErrorDomain
+ _krb5_get_init_creds_opt_set_tkt_life
- -[PORegistrationManager storeCredentialAndUpdatePasswordHint]
- GCC_except_table100
- GCC_except_table110
- GCC_except_table114
- GCC_except_table117
- GCC_except_table122
- GCC_except_table129
- GCC_except_table177
- GCC_except_table30
- GCC_except_table45
- GCC_except_table5
- GCC_except_table73
- GCC_except_table86
- _OBJC_CLASS_$_NSURLRequest
- ___61-[PORegistrationManager storeCredentialAndUpdatePasswordHint]_block_invoke
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke_2
```
