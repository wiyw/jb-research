## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination`

```diff

-842.0.1.0.0
-  __TEXT.__text: 0x6c874
-  __TEXT.__objc_methlist: 0x48b0
+849.40.7.0.2
+  __TEXT.__text: 0x70734
+  __TEXT.__objc_methlist: 0x4c88
   __TEXT.__const: 0x100
-  __TEXT.__cstring: 0x102c0
-  __TEXT.__oslogstring: 0x86c9
-  __TEXT.__gcc_except_tab: 0x1ef8
+  __TEXT.__cstring: 0x10b76
+  __TEXT.__oslogstring: 0x89f4
+  __TEXT.__gcc_except_tab: 0x1f78
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x1a90
+  __TEXT.__unwind_info: 0x1bb8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1e98
-  __DATA_CONST.__objc_classlist: 0x1f8
+  __DATA_CONST.__const: 0x1fd0
+  __DATA_CONST.__objc_classlist: 0x230
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2360
+  __DATA_CONST.__objc_selrefs: 0x2500
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x168
+  __DATA_CONST.__objc_superrefs: 0x1a0
   __DATA_CONST.__objc_arraydata: 0x120
-  __DATA_CONST.__got: 0x4d0
-  __AUTH_CONST.__const: 0x380
-  __AUTH_CONST.__cfstring: 0x6240
-  __AUTH_CONST.__objc_const: 0xcb68
+  __DATA_CONST.__got: 0x530
+  __AUTH_CONST.__const: 0x3e0
+  __AUTH_CONST.__cfstring: 0x6560
+  __AUTH_CONST.__objc_const: 0xd670
   __AUTH_CONST.__objc_intobj: 0x330
   __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__auth_got: 0x608
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x410
-  __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x258
-  __DATA.__data: 0xae8
-  __DATA.__bss: 0xa8
-  __DATA_DIRTY.__objc_data: 0xfa0
-  __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x68
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x278
+  __DATA.__bss: 0xf8
+  __DATA_DIRTY.__objc_data: 0x1540
+  __DATA_DIRTY.__data: 0xb18
+  __DATA_DIRTY.__bss: 0x60
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/ImageIO.framework/ImageIO
   - /System/Library/Frameworks/Security.framework/Security
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers
+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection
   - /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete
   - /System/Library/PrivateFrameworks/IconServices.framework/IconServices
   - /System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary
+  - /System/Library/PrivateFrameworks/ManagedDevice.framework/ManagedDevice
   - /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
   - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices
   - /System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2206
-  Symbols:   3071
+  Functions: 2310
+  Symbols:   3236
   CStrings:  0
 
Symbols:
+ +[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]
+ +[IXAppInstallCoordinator(IXAppReplacement) appReplacementRefusedForAppIdentity:options:error:]
+ +[IXAppInstallCoordinator(IXAppReplacement) getAppReplacementSource:forAppIdentity:options:error:]
+ +[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]
+ +[IXAppInstallCoordinator(IXAppReplacement) performAppReplacementFromAppIdentity:toAppIdentity:options:error:]
+ +[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]
+ +[IXAppInstallCoordinator(IXAppReplacement) resumeInterruptedAppReplacementWithOptions:completion:]
+ +[IXAppInstallCoordinator(IXAppReplacement_Private) resetAppReplacementStateForAppIdentity:options:error:]
+ +[IXAppReplacementOptions supportsSecureCoding]
+ +[IXAppReplacementRefusalOptions supportsSecureCoding]
+ +[IXAppReplacementSourceOptions supportsSecureCoding]
+ +[IXAppReplacementSourceResolver _deviceHasPersonas]
+ +[IXAppReplacementStateResetOptions supportsSecureCoding]
+ +[IXDataReplacementRequest supportsSecureCoding]
+ -[IXAppReplacementOptions copyWithZone:]
+ -[IXAppReplacementOptions encodeWithCoder:]
+ -[IXAppReplacementOptions initForTesting]
+ -[IXAppReplacementOptions initWithCoder:]
+ -[IXAppReplacementOptions isEqual:]
+ -[IXAppReplacementRefusalOptions copyWithZone:]
+ -[IXAppReplacementRefusalOptions encodeWithCoder:]
+ -[IXAppReplacementRefusalOptions initForTesting]
+ -[IXAppReplacementRefusalOptions initWithCoder:]
+ -[IXAppReplacementRefusalOptions isEqual:]
+ -[IXAppReplacementSourceCacheOptions copyWithZone:]
+ -[IXAppReplacementSourceCacheOptions hash]
+ -[IXAppReplacementSourceCacheOptions initForTesting]
+ -[IXAppReplacementSourceCacheOptions isEqual:]
+ -[IXAppReplacementSourceOptions copyWithZone:]
+ -[IXAppReplacementSourceOptions encodeWithCoder:]
+ -[IXAppReplacementSourceOptions initForTesting]
+ -[IXAppReplacementSourceOptions initWithCoder:]
+ -[IXAppReplacementSourceOptions isEqual:]
+ -[IXAppReplacementSourceResolver .cxx_destruct]
+ -[IXAppReplacementSourceResolver _appIsHidden:]
+ -[IXAppReplacementSourceResolver _appIsRestricted:]
+ -[IXAppReplacementSourceResolver _personaForIdentity:record:error:]
+ -[IXAppReplacementSourceResolver _personaForRecord:error:]
+ -[IXAppReplacementSourceResolver identity]
+ -[IXAppReplacementSourceResolver initWithIdentity:managedAppBundleIdentifiers:]
+ -[IXAppReplacementSourceResolver managedAppBundleIdentifiers]
+ -[IXAppReplacementSourceResolver resolveAppReplacementSource:replacementRuledOut:replacementCandidate:error:]
+ -[IXAppReplacementStateResetOptions copyWithZone:]
+ -[IXAppReplacementStateResetOptions encodeWithCoder:]
+ -[IXAppReplacementStateResetOptions initForTesting]
+ -[IXAppReplacementStateResetOptions initWithCoder:]
+ -[IXAppReplacementStateResetOptions isEqual:]
+ -[IXApplicationIdentity hasUnresolvedPersona]
+ -[IXApplicationIdentity initWithLSApplicationIdentity:]
+ -[IXDataReplacementRequest .cxx_destruct]
+ -[IXDataReplacementRequest copyWithZone:]
+ -[IXDataReplacementRequest dataContainerURL]
+ -[IXDataReplacementRequest description]
+ -[IXDataReplacementRequest destinationIdentity]
+ -[IXDataReplacementRequest encodeWithCoder:]
+ -[IXDataReplacementRequest entityType]
+ -[IXDataReplacementRequest hash]
+ -[IXDataReplacementRequest initWithCoder:]
+ -[IXDataReplacementRequest initWithSourceIdentity:destinationIdentity:entityType:dataContainerURL:]
+ -[IXDataReplacementRequest isEqual:]
+ -[IXDataReplacementRequest sourceIdentity]
+ -[IXPlaceholderAttributes alternateDisplayNames]
+ -[IXPlaceholderAttributes pebblePlayBundleMetadata]
+ -[IXPlaceholderAttributes setAlternateDisplayNames:]
+ -[IXPlaceholderAttributes setPebblePlayBundleMetadata:]
+ _IXAppReplacementErrorDomain
+ _IXStringForReplacementEntityType
+ _LSUserApplicationType
+ _MobileInstallationPrepareAppReplacement
+ _MobileInstallationPushReplacementInfo
+ _MobileInstallationSetAppLaunchProhibited
+ _MobileInstallationSetAppReplacementStatus
+ _OBJC_CLASS_$_APApplication
+ _OBJC_CLASS_$_ICLWorkspace
+ _OBJC_CLASS_$_IXAppReplacementOptions
+ _OBJC_CLASS_$_IXAppReplacementRefusalOptions
+ _OBJC_CLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_CLASS_$_IXAppReplacementSourceOptions
+ _OBJC_CLASS_$_IXAppReplacementSourceResolver
+ _OBJC_CLASS_$_IXAppReplacementStateResetOptions
+ _OBJC_CLASS_$_IXDataReplacementRequest
+ _OBJC_CLASS_$_LSBundleRecord
+ _OBJC_CLASS_$_MDFManagedAppMonitor
+ _OBJC_CLASS_$_MIUserManagement
+ _OBJC_IVAR_$_IXAppReplacementSourceResolver._identity
+ _OBJC_IVAR_$_IXAppReplacementSourceResolver._managedAppBundleIdentifiers
+ _OBJC_IVAR_$_IXDataReplacementRequest._dataContainerURL
+ _OBJC_IVAR_$_IXDataReplacementRequest._destinationIdentity
+ _OBJC_IVAR_$_IXDataReplacementRequest._entityType
+ _OBJC_IVAR_$_IXDataReplacementRequest._sourceIdentity
+ _OBJC_IVAR_$_IXPlaceholderAttributes._alternateDisplayNames
+ _OBJC_IVAR_$_IXPlaceholderAttributes._pebblePlayBundleMetadata
+ _OBJC_METACLASS_$_IXAppReplacementOptions
+ _OBJC_METACLASS_$_IXAppReplacementRefusalOptions
+ _OBJC_METACLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_METACLASS_$_IXAppReplacementSourceOptions
+ _OBJC_METACLASS_$_IXAppReplacementSourceResolver
+ _OBJC_METACLASS_$_IXAppReplacementStateResetOptions
+ _OBJC_METACLASS_$_IXDataReplacementRequest
+ __ManagedAppQueue
+ __ManagedAppQueue.onceToken
+ __ManagedAppQueue.queue
+ __OBJC_$_CLASS_METHODS_IXAppInstallCoordinator(IXAppReplacement|IXAppReplacement_Private|IXTesting|IXPersonaBasedMultiUser|IXDiskImageMounter|IXRootContentRegistration|IXSimpleInstaller|IXSimpleInstallerPrivate|IXPersona|IXPersona_Private|IXOSModuleRegistration|IXPersonaConstruction|IXDemoteToPlaceholder|IXDemoteToPlaceholderTesting)
+ __OBJC_$_CLASS_METHODS_IXAppReplacementOptions
+ __OBJC_$_CLASS_METHODS_IXAppReplacementRefusalOptions
+ __OBJC_$_CLASS_METHODS_IXAppReplacementSourceOptions
+ __OBJC_$_CLASS_METHODS_IXAppReplacementSourceResolver
+ __OBJC_$_CLASS_METHODS_IXAppReplacementStateResetOptions
+ __OBJC_$_CLASS_METHODS_IXDataReplacementRequest
+ __OBJC_$_CLASS_PROP_LIST_IXAppReplacementOptions
+ __OBJC_$_CLASS_PROP_LIST_IXAppReplacementRefusalOptions
+ __OBJC_$_CLASS_PROP_LIST_IXAppReplacementSourceOptions
+ __OBJC_$_CLASS_PROP_LIST_IXAppReplacementStateResetOptions
+ __OBJC_$_CLASS_PROP_LIST_IXDataReplacementRequest
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementRefusalOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceCacheOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementStateResetOptions
+ __OBJC_$_INSTANCE_METHODS_IXDataReplacementRequest
+ __OBJC_$_INSTANCE_VARIABLES_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_VARIABLES_IXDataReplacementRequest
+ __OBJC_$_PROP_LIST_IXAppReplacementSourceResolver
+ __OBJC_$_PROP_LIST_IXDataReplacementRequest
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementOptions
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementRefusalOptions
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementSourceOptions
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementStateResetOptions
+ __OBJC_CLASS_PROTOCOLS_$_IXDataReplacementRequest
+ __OBJC_CLASS_RO_$_IXAppReplacementOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementRefusalOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceResolver
+ __OBJC_CLASS_RO_$_IXAppReplacementStateResetOptions
+ __OBJC_CLASS_RO_$_IXDataReplacementRequest
+ __OBJC_METACLASS_RO_$_IXAppReplacementOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementRefusalOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceResolver
+ __OBJC_METACLASS_RO_$_IXAppReplacementStateResetOptions
+ __OBJC_METACLASS_RO_$_IXDataReplacementRequest
+ ___106+[IXAppInstallCoordinator(IXAppReplacement_Private) resetAppReplacementStateForAppIdentity:options:error:]_block_invoke
+ ___110+[IXAppInstallCoordinator(IXAppReplacement) performAppReplacementFromAppIdentity:toAppIdentity:options:error:]_block_invoke
+ ___43-[IXPlaceholderAttributes infoPlistContent]_block_invoke
+ ___82+[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]_block_invoke
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke_2
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke_3
+ ___95+[IXAppInstallCoordinator(IXAppReplacement) appReplacementRefusedForAppIdentity:options:error:]_block_invoke
+ ___98+[IXAppInstallCoordinator(IXAppReplacement) getAppReplacementSource:forAppIdentity:options:error:]_block_invoke
+ ___99+[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]_block_invoke
+ ___99+[IXAppInstallCoordinator(IXAppReplacement) resumeInterruptedAppReplacementWithOptions:completion:]_block_invoke
+ ____ManagedAppQueue_block_invoke
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_40_e8_32s_e28_v16?0"MDFManagedAppEvent"8ls32l8
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
+ ___block_descriptor_48_e5_v8?0l
+ ___block_descriptor_48_e8_32s_e20_v24?0q8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32r40r_e5_v8?0lr32l8r40l8
+ _sManagedAppBundleIdentifiers
+ _sManagedAppSubscription
+ _sReSubscribeCount
- __OBJC_$_CLASS_METHODS_IXAppInstallCoordinator(IXTesting|IXPersonaBasedMultiUser|IXDiskImageMounter|IXRootContentRegistration|IXSimpleInstaller|IXSimpleInstallerPrivate|IXPersona|IXPersona_Private|IXOSModuleRegistration|IXPersonaConstruction|IXDemoteToPlaceholder|IXDemoteToPlaceholderTesting)
```
