## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

```diff

-542.7.0.0.0
-  __TEXT.__text: 0x704bc
-  __TEXT.__objc_methlist: 0x9ac8
-  __TEXT.__const: 0x552
-  __TEXT.__cstring: 0x5a76
-  __TEXT.__oslogstring: 0x36d6
-  __TEXT.__gcc_except_tab: 0x9bc
+552.7.1.0.0
+  __TEXT.__text: 0x70dbc
+  __TEXT.__objc_methlist: 0x9b48
+  __TEXT.__const: 0x562
+  __TEXT.__cstring: 0x5be6
+  __TEXT.__oslogstring: 0x3786
+  __TEXT.__gcc_except_tab: 0x934
   __TEXT.__constg_swiftt: 0x1f8
   __TEXT.__swift5_typeref: 0x13d
   __TEXT.__swift5_builtin: 0x50

   __TEXT.__swift5_proto: 0x18
   __TEXT.__swift5_types: 0x14
   __TEXT.__swift5_fieldmd: 0x7c
-  __TEXT.__unwind_info: 0x1f98
+  __TEXT.__unwind_info: 0x1fa8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1f50
-  __DATA_CONST.__objc_classlist: 0x3f0
+  __DATA_CONST.__objc_classlist: 0x3e8
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x2e8
+  __DATA_CONST.__objc_protolist: 0x2f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x43b8
-  __DATA_CONST.__objc_protorefs: 0x160
-  __DATA_CONST.__objc_superrefs: 0x348
-  __DATA_CONST.__got: 0x880
-  __AUTH_CONST.__const: 0xbc8
-  __AUTH_CONST.__cfstring: 0x5720
-  __AUTH_CONST.__objc_const: 0x215a0
+  __DATA_CONST.__objc_selrefs: 0x4448
+  __DATA_CONST.__objc_protorefs: 0x168
+  __DATA_CONST.__objc_superrefs: 0x350
+  __DATA_CONST.__got: 0x878
+  __AUTH_CONST.__const: 0xbe8
+  __AUTH_CONST.__cfstring: 0x5840
+  __AUTH_CONST.__objc_const: 0x218a0
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x7d0
+  __AUTH_CONST.__auth_got: 0x7b8
   __AUTH_CONST.__auth_ptr: 0x80
-  __AUTH.__objc_data: 0x48
+  __AUTH.__objc_data: 0x98
   __DATA.__objc_ivar: 0xa44
-  __DATA.__data: 0x2050
-  __DATA.__bss: 0x590
+  __DATA.__data: 0x2110
+  __DATA.__bss: 0x5e0
   __DATA.__common: 0x18
-  __DATA_DIRTY.__objc_data: 0x2738
+  __DATA_DIRTY.__objc_data: 0x2698
   __DATA_DIRTY.__data: 0x248
   __DATA_DIRTY.__bss: 0x90
   __DATA_DIRTY.__common: 0x10

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3402
-  Symbols:   6382
+  Functions: 3401
+  Symbols:   6397
   CStrings:  0
 
Symbols:
+ +[CPInterfaceController _setRemoteSupportedSelectorsForTesting:]
+ +[CPListImageRowItemCardElement _setImageSizeForAspectRatioWide:portrait:square:]
+ +[CPListImageRowItemCardElement _setMaximumImageSize:maximumFullHeightImageSize:]
+ +[CPPlaybackItemIdentifier supportsSecureCoding]
+ +[CPTabBarTemplate maximumNumberOfBarButtons]
+ -[CPButton isCollapsible]
+ -[CPButton setCollapsible:]
+ -[CPGridButton initWithTitleVariants:subtitleVariants:image:handler:]
+ -[CPGridButton setSubtitleVariants:]
+ -[CPGridButton subtitleVariants]
+ -[CPGridButton updateSubtitleVariants:]
+ -[CPGridTemplate gridButton:setSubtitleVariants:]
+ -[CPListTemplate _playableItemForMatchingIdentifier:]
+ -[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]
+ -[CPMapTemplate setPanningInterfaceVisible:]
+ -[CPPlaybackConfiguration .cxx_destruct]
+ -[CPPlaybackConfiguration initWithPreferredPresentation:playbackAction:elapsedTime:duration:requiresPlaybackConfirmation:]
+ -[CPPlaybackConfiguration playbackConfirmationBlock]
+ -[CPPlaybackConfiguration requiresPlaybackConfirmation]
+ -[CPPlaybackConfiguration setPlaybackConfirmationBlock:]
+ -[CPPlaybackItemIdentifier .cxx_destruct]
+ -[CPPlaybackItemIdentifier elementIndex]
+ -[CPPlaybackItemIdentifier encodeWithCoder:]
+ -[CPPlaybackItemIdentifier identifier]
+ -[CPPlaybackItemIdentifier initWithCoder:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:elementIndex:]
+ -[CPSessionConfiguration _updateContentStyle:]
+ -[CPTabBarTemplate _clampedBarButtons:]
+ -[CPTemplateApplicationDashboardScene _setFrameRateLimit:]
+ -[CPTemplateApplicationDashboardScene scene:didUpdateFrameRateLimit:]
+ -[CPTemplateApplicationDashboardScene scene:didUpdateMapStyle:]
+ -[CPTemplateApplicationInstrumentClusterScene _setContentStyle:]
+ -[CPTemplateApplicationInstrumentClusterScene _setFrameRateLimit:]
+ -[CPTemplateApplicationInstrumentClusterScene scene:didUpdateFrameRateLimit:]
+ -[CPTemplateApplicationInstrumentClusterScene scene:didUpdateMapStyle:]
+ -[CPTemplateApplicationScene _setContentStyle:]
+ -[CPTemplateApplicationScene _setFrameRateLimit:]
+ -[CPTemplateApplicationScene scene:didUpdateFrameRateLimit:]
+ -[CPTemplateApplicationScene scene:didUpdateMapStyle:]
+ -[CPTrip destinationTimeZoneOffsetMinutesFromGMT]
+ GCC_except_table105
+ GCC_except_table120
+ GCC_except_table123
+ GCC_except_table135
+ _CPBarButtonMaximumImageSize
+ _CPBarButtonSanitizedImage
+ _CRSUIFrameRateLimitUnrestricted
+ _OBJC_CLASS_$_CPPlaybackItemIdentifier
+ _OBJC_CLASS_$_CRSUIApplicationSceneSpecification
+ _OBJC_IVAR_$_CPButton._collapsible
+ _OBJC_IVAR_$_CPGridButton._subtitleVariants
+ _OBJC_IVAR_$_CPMapTemplate._panningInterfaceVisible
+ _OBJC_IVAR_$_CPPlaybackConfiguration._playbackConfirmationBlock
+ _OBJC_IVAR_$_CPPlaybackConfiguration._requiresPlaybackConfirmation
+ _OBJC_IVAR_$_CPPlaybackItemIdentifier._elementIndex
+ _OBJC_IVAR_$_CPPlaybackItemIdentifier._identifier
+ _OBJC_METACLASS_$_CPPlaybackItemIdentifier
+ _OBJC_METACLASS_$_CRSUIApplicationSceneSpecification
+ __OBJC_$_CLASS_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_CLASS_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_VARIABLES_CPPlaybackItemIdentifier
+ __OBJC_$_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CRSUIFrameRateLimitObserving
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CRSUIMapStyleObserving
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CPListClientTemplateDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CRSUIFrameRateLimitObserving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CRSUIMapStyleObserving
+ __OBJC_$_PROTOCOL_REFS_CRSUIFrameRateLimitObserving
+ __OBJC_$_PROTOCOL_REFS_CRSUIMapStyleObserving
+ __OBJC_CLASS_PROTOCOLS_$_CPPlaybackItemIdentifier
+ __OBJC_CLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_LABEL_PROTOCOL_$_CRSUIFrameRateLimitObserving
+ __OBJC_LABEL_PROTOCOL_$_CRSUIMapStyleObserving
+ __OBJC_METACLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_PROTOCOL_$_CRSUIFrameRateLimitObserving
+ __OBJC_PROTOCOL_$_CRSUIMapStyleObserving
+ __OBJC_PROTOCOL_REFERENCE_$_CPPlayableItem
+ ___112-[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]_block_invoke
+ ___36-[CPNavigationManager guidanceState]_block_invoke
+ ___45-[CPNavigationManager routeGuidanceProviding]_block_invoke
+ ___49-[CPGridTemplate gridButton:setSubtitleVariants:]_block_invoke
+ ___49-[CPNavigationManager didUpdateActiveComponents:]_block_invoke_2
+ ___53-[CPTabBarTemplate handleActionForControlIdentifier:]_block_invoke_2
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_10
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_9
+ ___73-[CPGridButton initWithTitleVariants:image:messageConfiguration:handler:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e29_v24?0"NSValue"8"NSValue"16ls32l8
+ ___block_descriptor_40_e8_32s_e41_v32?0"NSValue"8"NSValue"16"NSValue"24ls32l8
+ ___block_descriptor_48_e8_32s40r_e5_v8?0lr40l8s32l8
+ __maximumFullHeightImageSize
+ __maximumImageSizeForAspectRatioPortrait
+ __maximumImageSizeForAspectRatioSquare
+ __maximumImageSizeForAspectRatioWide
- -[CPSessionConfiguration _updateContentStyleWithScene:]
- -[CPTabBarTemplate leadingNavigationBarButtons]
- -[CPTabBarTemplate trailingNavigationBarButtons]
- -[CPTemplateApplicationDashboardScene _frameRateLimit]
- -[CPTemplateApplicationDashboardScene _templateSettings]
- -[CPTemplateApplicationDashboardScene _updateFrameRateLimit]
- -[CPTemplateApplicationDashboardScene frameRateLimitInspector]
- -[CPTemplateApplicationDashboardScene sceneSettingsDiffAction]
- -[CPTemplateApplicationDashboardScene setFrameRateLimitInspector:]
- -[CPTemplateApplicationDashboardScene setSceneSettingsDiffAction:]
- -[CPTemplateApplicationInstrumentClusterScene _frameRateLimit]
- -[CPTemplateApplicationInstrumentClusterScene _mapStyle]
- -[CPTemplateApplicationInstrumentClusterScene _templateSettings]
- -[CPTemplateApplicationInstrumentClusterScene _updateContentStyle]
- -[CPTemplateApplicationInstrumentClusterScene _updateFrameRateLimit]
- -[CPTemplateApplicationInstrumentClusterScene frameRateLimitInspector]
- -[CPTemplateApplicationInstrumentClusterScene mapStyleInspector]
- -[CPTemplateApplicationInstrumentClusterScene sceneSettingsDiffAction]
- -[CPTemplateApplicationInstrumentClusterScene setFrameRateLimitInspector:]
- -[CPTemplateApplicationInstrumentClusterScene setMapStyleInspector:]
- -[CPTemplateApplicationInstrumentClusterScene setSceneSettingsDiffAction:]
- -[CPTemplateApplicationScene _frameRateLimit]
- -[CPTemplateApplicationScene _mapStyle]
- -[CPTemplateApplicationScene _templateSettings]
- -[CPTemplateApplicationScene _updateContentStyle]
- -[CPTemplateApplicationScene _updateFrameRateLimit]
- -[CPTemplateApplicationScene frameRateLimitInspector]
- -[CPTemplateApplicationScene mapStyleInspector]
- -[CPTemplateApplicationScene setFrameRateLimitInspector:]
- -[CPTemplateApplicationScene setMapStyleInspector:]
- -[CPTrip destinationTimeZoneOffsetFromGMT]
- -[CPUIContentStyleDiffInspector observeMapStyleWithBlock:]
- -[CPUIFrameRateLimitDiffInspector observeFrameRateLimitWithBlock:]
- -[CPUIMutableTemplateApplicationSceneSettings frameRateLimit]
- -[CPUIMutableTemplateApplicationSceneSettings mapStyle]
- -[CPUIMutableTemplateApplicationSceneSettings setFrameRateLimit:]
- -[CPUIMutableTemplateApplicationSceneSettings setMapStyle:]
- -[CPUITemplateApplicationSceneSettings frameRateLimit]
- -[CPUITemplateApplicationSceneSettings mapStyle]
- GCC_except_table104
- GCC_except_table132
- GCC_except_table21
- GCC_except_table74
- GCC_except_table85
- _OBJC_CLASS_$_CPUIContentStyleDiffInspector
- _OBJC_CLASS_$_CPUIFrameRateLimitDiffInspector
- _OBJC_CLASS_$_FBSSceneSettingsDiffInspector
- _OBJC_CLASS_$_UIApplicationStarkSceneSpecification
- _OBJC_IVAR_$_CPTemplateApplicationDashboardScene._frameRateLimitInspector
- _OBJC_IVAR_$_CPTemplateApplicationDashboardScene._sceneSettingsDiffAction
- _OBJC_IVAR_$_CPTemplateApplicationInstrumentClusterScene._frameRateLimitInspector
- _OBJC_IVAR_$_CPTemplateApplicationInstrumentClusterScene._mapStyleInspector
- _OBJC_IVAR_$_CPTemplateApplicationInstrumentClusterScene._sceneSettingsDiffAction
- _OBJC_IVAR_$_CPTemplateApplicationScene._frameRateLimitInspector
- _OBJC_IVAR_$_CPTemplateApplicationScene._mapStyleInspector
- _OBJC_METACLASS_$_CPUIContentStyleDiffInspector
- _OBJC_METACLASS_$_CPUIFrameRateLimitDiffInspector
- _OBJC_METACLASS_$_FBSSceneSettingsDiffInspector
- _OBJC_METACLASS_$_UIApplicationStarkSceneSpecification
- __OBJC_$_INSTANCE_METHODS_CPUIContentStyleDiffInspector
- __OBJC_$_INSTANCE_METHODS_CPUIFrameRateLimitDiffInspector
- __OBJC_CLASS_RO_$_CPUIContentStyleDiffInspector
- __OBJC_CLASS_RO_$_CPUIFrameRateLimitDiffInspector
- __OBJC_METACLASS_RO_$_CPUIContentStyleDiffInspector
- __OBJC_METACLASS_RO_$_CPUIFrameRateLimitDiffInspector
- ___42-[CPMapTemplate isPanningInterfaceVisible]_block_invoke
- ___42-[CPMapTemplate isPanningInterfaceVisible]_block_invoke_2
- ___58-[CPUIContentStyleDiffInspector observeMapStyleWithBlock:]_block_invoke
- ___58-[CPUIContentStyleDiffInspector observeMapStyleWithBlock:]_block_invoke_2
- ___64-[CPTemplateApplicationScene initWithSession:connectionOptions:]_block_invoke_2
- ___64-[CPTemplateApplicationScene initWithSession:connectionOptions:]_block_invoke_3
- ___66-[CPUIFrameRateLimitDiffInspector observeFrameRateLimitWithBlock:]_block_invoke
- ___66-[CPUIFrameRateLimitDiffInspector observeFrameRateLimitWithBlock:]_block_invoke_2
- ___81-[CPTemplateApplicationInstrumentClusterScene initWithSession:connectionOptions:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e12_v24?0Q8^v16ls32l8
- ___block_descriptor_48_e8_32s40r_e34_v16?0"<CPMapTemplateProviding>"8lr40l8s32l8
- ___block_descriptor_48_e8_32s40r_e8_v12?0B8lr40l8s32l8
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
```
