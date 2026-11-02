## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary`

```diff

-113.2.5.0.0
-  __TEXT.__text: 0x2beb0
-  __TEXT.__objc_methlist: 0x1d1c
-  __TEXT.__const: 0x100
-  __TEXT.__oslogstring: 0x46a2
-  __TEXT.__cstring: 0x278f
-  __TEXT.__gcc_except_tab: 0x880
-  __TEXT.__dlopen_cstrs: 0xae
-  __TEXT.__unwind_info: 0x998
+113.40.20.0.0
+  __TEXT.__text: 0x2d46c
+  __TEXT.__objc_methlist: 0x1da4
+  __TEXT.__const: 0x108
+  __TEXT.__oslogstring: 0x48d6
+  __TEXT.__cstring: 0x28d5
+  __TEXT.__gcc_except_tab: 0x904
+  __TEXT.__dlopen_cstrs: 0x104
+  __TEXT.__unwind_info: 0xa08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x13a8
+  __DATA_CONST.__const: 0x14a0
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d38
+  __DATA_CONST.__objc_selrefs: 0x1db8
   __DATA_CONST.__objc_superrefs: 0x38
-  __DATA_CONST.__objc_arraydata: 0x558
+  __DATA_CONST.__objc_arraydata: 0x588
   __DATA_CONST.__got: 0x4e0
-  __AUTH_CONST.__const: 0x160
-  __AUTH_CONST.__cfstring: 0x1980
-  __AUTH_CONST.__objc_const: 0x2030
-  __AUTH_CONST.__objc_intobj: 0xb28
-  __AUTH_CONST.__objc_arrayobj: 0x4e0
+  __AUTH_CONST.__const: 0x180
+  __AUTH_CONST.__cfstring: 0x1a80
+  __AUTH_CONST.__objc_const: 0x2060
+  __AUTH_CONST.__objc_intobj: 0xb88
+  __AUTH_CONST.__objc_arrayobj: 0x4f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x1a4
-  __DATA.__data: 0x1e0
-  __DATA.__bss: 0x218
+  __DATA.__objc_ivar: 0x1a8
+  __DATA.__bss: 0x230
   __DATA_DIRTY.__objc_data: 0x370
+  __DATA_DIRTY.__data: 0x1e0
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices

   - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 854
-  Symbols:   1491
+  Functions: 878
+  Symbols:   1530
   CStrings:  0
 
Symbols:
+ +[DMCEnrollmentFlowController(Utilities) _createSignInErrorFromError:]
+ -[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]
+ -[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]
+ -[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]
+ -[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]
+ -[DMCEnrollmentFlowController requiredAppID]
+ -[DMCEnrollmentFlowController setRequiredAppID:]
+ -[DMCEnrollmentFlowController(Sequence) _ADxE_ESSO_displayManagementDetailsSteps]
+ -[DMCEnrollmentFlowController(Utilities) _duplicateAccountErrorForConflictingAccounts:]
+ -[DMCEnrollmentFlowController(Utilities) _requiresAppNetworkAccessConsent]
+ -[DMCEnrollmentFlowController(Utilities) _signOutFromAppBundleIDs]
+ GCC_except_table103
+ GCC_except_table107
+ GCC_except_table114
+ GCC_except_table119
+ GCC_except_table127
+ GCC_except_table133
+ GCC_except_table146
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table158
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table179
+ GCC_except_table206
+ GCC_except_table223
+ GCC_except_table226
+ GCC_except_table230
+ GCC_except_table233
+ GCC_except_table24
+ GCC_except_table265
+ GCC_except_table52
+ GCC_except_table65
+ GCC_except_table66
+ GCC_except_table78
+ GCC_except_table83
+ GCC_except_table87
+ _AppleAccountLibraryCore.frameworkLibrary
+ _DMCIsGreenTea
+ _OBJC_IVAR_$_DMCEnrollmentFlowController._requiredAppID
+ ___100-[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]_block_invoke
+ ___100-[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]_block_invoke_2
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_2
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_3
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_4
+ ___66-[DMCEnrollmentFlowController(Utilities) _signOutFromAppBundleIDs]_block_invoke
+ ___87-[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]_block_invoke
+ ___87-[DMCEnrollmentFlowController _ensureAppNetworkAccessWithEnrollmentMethod:essoDetails:]_block_invoke_2
+ ___94-[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]_block_invoke
+ ___94-[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]_block_invoke_2
+ ___AppleAccountLibraryCore_block_invoke
+ ___block_descriptor_48_e8_32s40w_e29_v24?0"NSArray"8"NSError"16lw40l8s32l8
+ ___block_descriptor_48_e8_32w_e17_v16?0"NSError"8lw32l8
+ ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40w_e23_v24?0B8B12"NSError"16lw40l8s32l8
+ ___block_descriptor_74_e8_32s40s48s56w_e5_v8?0ls32l8s40l8s48l8w56l8
+ __signOutFromAppBundleIDs.bundleIDs
+ __signOutFromAppBundleIDs.onceToken
+ _audit_stringAppleAccount
- GCC_except_table100
- GCC_except_table104
- GCC_except_table111
- GCC_except_table116
- GCC_except_table121
- GCC_except_table130
- GCC_except_table137
- GCC_except_table147
- GCC_except_table149
- GCC_except_table151
- GCC_except_table192
- GCC_except_table195
- GCC_except_table198
- GCC_except_table20
- GCC_except_table202
- GCC_except_table219
- GCC_except_table251
- GCC_except_table47
- GCC_except_table63
- GCC_except_table69
- GCC_except_table77
- GCC_except_table8
- GCC_except_table84
```
