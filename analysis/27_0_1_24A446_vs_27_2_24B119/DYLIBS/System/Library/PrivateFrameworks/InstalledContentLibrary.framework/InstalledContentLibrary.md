## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

```diff

-1674.2.1.0.0
-  __TEXT.__text: 0xcee84
-  __TEXT.__objc_methlist: 0x5be4
-  __TEXT.__const: 0xdb30
-  __TEXT.__cstring: 0x183ee
+1680.40.14.0.0
+  __TEXT.__text: 0xd3e68
+  __TEXT.__objc_methlist: 0x5ef4
+  __TEXT.__const: 0xdb40
+  __TEXT.__cstring: 0x18cbe
   __TEXT.__gcc_except_tab: 0xde8
   __TEXT.__dlopen_cstrs: 0x111
   __TEXT.__oslogstring: 0x8c1
-  __TEXT.__swift5_typeref: 0x30
-  __TEXT.__unwind_info: 0x19f0
-  __TEXT.__eh_frame: 0x398
+  __TEXT.__swift5_typeref: 0x38
+  __TEXT.__unwind_info: 0x1b20
+  __TEXT.__eh_frame: 0x558
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1000
-  __DATA_CONST.__objc_classlist: 0x228
+  __DATA_CONST.__const: 0x1080
+  __DATA_CONST.__objc_classlist: 0x238
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30c0
+  __DATA_CONST.__objc_selrefs: 0x3208
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0xb10
-  __DATA_CONST.__got: 0x4f0
+  __DATA_CONST.__got: 0x508
   __AUTH_CONST.__const: 0x4d88
-  __AUTH_CONST.__cfstring: 0xd4a0
-  __AUTH_CONST.__objc_const: 0xa7d0
+  __AUTH_CONST.__cfstring: 0xd760
+  __AUTH_CONST.__objc_const: 0xac40
   __AUTH_CONST.__objc_dictobj: 0x1248
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_intobj: 0x180
-  __AUTH_CONST.__auth_got: 0xc10
+  __AUTH_CONST.__auth_got: 0xc70
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x1180
-  __AUTH.__data: 0x78
-  __DATA.__objc_ivar: 0x5cc
-  __DATA.__data: 0xf38
-  __DATA.__bss: 0x2d0
+  __AUTH.__objc_data: 0x1148
+  __AUTH.__data: 0x80
+  __DATA.__objc_ivar: 0x5d4
+  __DATA.__data: 0xf88
+  __DATA.__bss: 0x2e0
   __DATA.__common: 0xaa4
-  __DATA_DIRTY.__objc_data: 0x4b0
-  __DATA_DIRTY.__data: 0x50
+  __DATA_DIRTY.__objc_data: 0x5c8
+  __DATA_DIRTY.__data: 0xb0
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/Security.framework/Security

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 2412
-  Symbols:   3840
+  Functions: 2514
+  Symbols:   3893
   CStrings:  0
 
Symbols:
+ -[ICLBundleRecord appReplacementSourceBundleIdentifier]
+ -[ICLBundleRecord isInstallationHoldActive]
+ -[ICLBundleRecord setAppReplacementSourceBundleIdentifier:]
+ -[ICLBundleRecord setIsInstallationHoldActive:]
+ -[ICLWorkspace getAppLaunchProhibition:forBundleContainerURL:error:]
+ -[ICLWorkspace getAppReplacementState:forBundleContainerURL:error:]
+ -[MIBundle hasAtLeastOneExtensionImplementingExtensionPointIn:error:]
+ -[MIBundleContainer appLaunchProhibitionURL]
+ -[MIBundleContainer appReplacementStateURL]
+ -[MIBundleContainer getAppLaunchProhibition:withError:]
+ -[MIBundleContainer getAppReplacementState:withError:]
+ -[MIBundleContainer removeAppLaunchProhibitionWithError:]
+ -[MIBundleContainer removeAppReplacementStateWithError:]
+ -[MIBundleContainer saveAppLaunchProhibition:withError:]
+ -[MIBundleContainer saveAppReplacementState:withError:]
+ -[MIDataContainer supersedeExistingContainer:error:]
+ -[MIGlobalConfiguration OSBuildVersionWithError:]
+ -[MIMCMContainer setMcmContainer:]
+ -[MIMCMContainer supersedeExistingContainer:error:]
+ GCC_except_table26
+ GCC_except_table37
+ GCC_except_table56
+ _MIAppExtensionPointToExtensionPointIdentifierString
+ _MIAppReplacementMinimumBuildVersion
+ _MIAppReplacementStatusExpectsSourceAppIdentity
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeExtensionEntitlement
+ _MIHasHomeKitEntitlement
+ _MIIsRecordableAppReplacementStatus
+ _MIStringForAppReplacementStatus
+ _OBJC_CLASS_$_MIAppLaunchProhibition
+ _OBJC_CLASS_$_MIAppReplacementState
+ _OBJC_IVAR_$_ICLBundleRecord._appReplacementSourceBundleIdentifier
+ _OBJC_IVAR_$_ICLBundleRecord._isInstallationHoldActive
+ _OBJC_METACLASS_$_MIAppLaunchProhibition
+ _OBJC_METACLASS_$_MIAppReplacementState
+ __CLASS_METHODS_MIAppLaunchProhibition
+ __CLASS_METHODS_MIAppReplacementState
+ __CLASS_PROPERTIES_MIAppLaunchProhibition
+ __CLASS_PROPERTIES_MIAppReplacementState
+ __DATA_MIAppLaunchProhibition
+ __DATA_MIAppReplacementState
+ __INSTANCE_METHODS_MIAppLaunchProhibition
+ __INSTANCE_METHODS_MIAppReplacementState
+ __IVARS_MIAppLaunchProhibition
+ __IVARS_MIAppReplacementState
+ __METACLASS_DATA_MIAppLaunchProhibition
+ __METACLASS_DATA_MIAppReplacementState
+ __PROPERTIES_MIAppLaunchProhibition
+ __PROPERTIES_MIAppReplacementState
+ __PROTOCOLS_MIAppLaunchProhibition
+ __PROTOCOLS_MIAppReplacementState
+ _container_operation_copy_superseded
+ _swift_errorRetain
+ _symbolic ______p s5ErrorP
- GCC_except_table48
- GCC_except_table54
```
