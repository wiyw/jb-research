## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

```diff

-4636.116.0.0.0
-  __TEXT.__text: 0xb1023c
+4637.1.14.103.0
+  __TEXT.__text: 0xb18b84
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0xbe0c0
-  __TEXT.__const: 0x11370
-  __TEXT.__oslogstring: 0x65862
-  __TEXT.__cstring: 0x85315
-  __TEXT.__gcc_except_tab: 0x18660
+  __TEXT.__objc_methlist: 0xbe6c0
+  __TEXT.__const: 0x11380
+  __TEXT.__oslogstring: 0x660a4
+  __TEXT.__cstring: 0x85b58
+  __TEXT.__gcc_except_tab: 0x18890
   __TEXT.__ustring: 0xd04
   __TEXT.__dlopen_cstrs: 0x373
-  __TEXT.__unwind_info: 0x2e678
+  __TEXT.__unwind_info: 0x2e830
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1d9e8
-  __DATA_CONST.__objc_classlist: 0x5518
+  __DATA_CONST.__const: 0x1dac0
+  __DATA_CONST.__objc_classlist: 0x5540
   __DATA_CONST.__objc_catlist: 0x350
   __DATA_CONST.__objc_nlcatlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x2af0
+  __DATA_CONST.__objc_protolist: 0x2b08
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4eb40
+  __DATA_CONST.__objc_selrefs: 0x4ee30
   __DATA_CONST.__objc_protorefs: 0xd8
-  __DATA_CONST.__objc_superrefs: 0x40a8
+  __DATA_CONST.__objc_superrefs: 0x40c8
   __DATA_CONST.__objc_arraydata: 0x18b8
-  __DATA_CONST.__got: 0xa9a0
-  __AUTH_CONST.__const: 0x10bc8
-  __AUTH_CONST.__cfstring: 0x74ba0
-  __AUTH_CONST.__objc_const: 0x289388
+  __DATA_CONST.__got: 0xaa00
+  __AUTH_CONST.__const: 0x10c68
+  __AUTH_CONST.__cfstring: 0x75020
+  __AUTH_CONST.__objc_const: 0x28b228
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x1740
   __AUTH_CONST.__objc_doubleobj: 0x850
-  __AUTH_CONST.__objc_intobj: 0x2ca0
+  __AUTH_CONST.__objc_intobj: 0x2cb8
   __AUTH_CONST.__objc_dictobj: 0x2f8
-  __AUTH_CONST.__auth_got: 0x2c00
+  __AUTH_CONST.__auth_got: 0x2c10
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xe6f0
-  __DATA.__objc_ivar: 0xfcb8
-  __DATA.__data: 0x21040
-  __DATA.__bss: 0xaa8
+  __AUTH.__objc_data: 0xda70
+  __DATA.__objc_ivar: 0xfd5c
+  __DATA.__data: 0x21160
+  __DATA.__bss: 0x980
   __DATA.__common: 0xa40
-  __DATA_DIRTY.__objc_data: 0x26c00
+  __DATA_DIRTY.__objc_data: 0x27a10
   __DATA_DIRTY.__data: 0x140
-  __DATA_DIRTY.__bss: 0x18c8
+  __DATA_DIRTY.__bss: 0x19e8
   __DATA_DIRTY.__common: 0x40
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

   - /System/Library/PrivateFrameworks/AppRestrictions.framework/AppRestrictions
   - /System/Library/PrivateFrameworks/AppRestrictionsCore.framework/AppRestrictionsCore
   - /System/Library/PrivateFrameworks/AppRestrictionsUI.framework/AppRestrictionsUI
+  - /System/Library/PrivateFrameworks/AppServerSupport.framework/AppServerSupport
   - /System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon
   - /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
   - /System/Library/PrivateFrameworks/AppleKeyStore.framework/AppleKeyStore

   - /usr/lib/libsp.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libutil.dylib
-  Functions: 73615
-  Symbols:   119516
+  Functions: 73776
+  Symbols:   119766
   CStrings:  0
 
Symbols:
+ +[SBApplicationController _appClassForInfo:]
+ +[SBApplicationController _application:canAdoptApplicationInfoInPlace:]
+ +[SBHomeScreenService _validationErrorForStashedLayoutName:]
+ +[SBIconStateArchiver _iconListByAssigningMissingFolderIdentifiers:identifierPrefix:]
+ +[SBIconStateArchiver _iconListsByAssigningMissingFolderIdentifiers:identifierPrefix:]
+ +[SBIconStateArchiver _rootArchiveByAssigningMissingFolderIdentifiers:]
+ +[SBIconStateArchiver modernizedRootArchiveFromITunesRepresentation:]
+ -[FBScene(SBScreenBrightnessHost) sb_screenBrightnessHost]
+ -[SBActionHandler handleClientWorkspaceActions:]
+ -[SBActivationInfoViewController _appendMobileEquipmentInfoForSlot:mobileEquipmentInfoList:]
+ -[SBActivityAmbientViewController _animationSettingsForBackgroundBlurWindDown]
+ -[SBActivityAmbientViewController _removeBackgroundBlurMaterialView]
+ -[SBAppPlatterDragPreview pendingIconViewListLayoutProvider]
+ -[SBAppPlatterDragPreview setPendingIconViewListLayoutProvider:]
+ -[SBAppResizingCoordinator acquireSessionForDisplay:monitoredWindowScene:resizingCornerRadius:]
+ -[SBAppResizingSession initWithWindowSceneManager:displayUniqueId:monitoredWindowScene:resizingCornerRadius:]
+ -[SBAppResizingSession monitoredWindowScene]
+ -[SBAppResizingSession prepareForDisplay]
+ -[SBApplication isUninstallRequestFulfilled]
+ -[SBApplication setUninstallRequestFulfilled:]
+ -[SBApplication(Identity) isFindMyFindingUI]
+ -[SBApplicationSceneUpdateTransaction _shouldRequirePreflightForRequest:]
+ -[SBAssistantIslandStageController _setSceneActivityMode:jetsamPriority:]
+ -[SBContinuitySession _updateSystemGestureWindowFrame]
+ -[SBContinuousExposeAppToAppModifier appLayoutsToEnsureExistForMainTransitionEvent:]
+ -[SBContinuousExposeAppToAppModifier ignoredAppLayout]
+ -[SBContinuousExposeAppToAppModifier setIgnoredAppLayout:]
+ -[SBContinuousExposeAppToAppModifier setShouldOrderToAppLayoutFront:]
+ -[SBContinuousExposeAppToAppModifier shouldOrderToAppLayoutFront]
+ -[SBDashBoardHostableEntityHostingFluidSwitcherViewController _invalidateZStackParticipant]
+ -[SBDashBoardHostableEntityHostingFluidSwitcherViewController _removeBottomEdgeRecognizer]
+ -[SBDeviceApplicationSceneViewController _isDoubleTapTopToZoomEnabled]
+ -[SBDisplayItemLayoutAttributes attributesByZoomingToLargestSizeAllowedBySupportedSizingPolicies:]
+ -[SBFlexibleWindowingAutoLayoutSpace setStageSpanningSplit:]
+ -[SBFlexibleWindowingAutoLayoutSpace stageSpanningSplit]
+ -[SBFluidSwitcherGestureManager gestureRecognizer:shouldReceiveEvent:]
+ -[SBFullScreenToPeekAnimationModifier isLayoutRoleMatchMovedToScene:inAppLayout:]
+ -[SBHomeScreenController _finishFolderOpenAttemptForFolder:]
+ -[SBHomeScreenController iconManager:failedToOpenFolder:]
+ -[SBHomeScreenController iconManager:shouldAvoidPlacingIconOnFirstPage:]
+ -[SBHomeScreenController iconManager:shouldConsiderDefaultLocationAsDesignatedForIconWithIdentifier:]
+ -[SBHomeScreenService replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:]
+ -[SBHomeScreenService simulateCampoEnablementChange]
+ -[SBHomeScreenService swapApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBLockScreenCoordinator _sendStartupTransitionNotesIfNeeded:]
+ -[SBMenuBarViewController _restoreKeyboardFocusToMenuProvidingScene]
+ -[SBMinimizeItemFromSplitResizeWindowingModifier dimmingAlphaForLayoutRole:inAppLayout:]
+ -[SBNotificationCarPlayDestination _cancelPreprocessOnWithdrawForRequest:]
+ -[SBNotificationCarPlayDestination _clearNotificationRequestPendingAnnounceDeactivationIfNecessaryDeactivatingAnnounce:]
+ -[SBNotificationCarPlayDestination _isSiriExcludedForNotificationRequest:]
+ -[SBPIPPegasusContainerAdapter _settleInFlightRotationAnimation]
+ -[SBSceneManager workspace:didReceiveActions:]
+ -[SBScreenBrightnessCoordinator .cxx_destruct]
+ -[SBScreenBrightnessCoordinator _keyForWindowScene:]
+ -[SBScreenBrightnessCoordinator acquireParticipantForObserver:]
+ -[SBScreenBrightnessCoordinator debugHUDForWindowScene:]
+ -[SBScreenBrightnessCoordinator displayClientForWindowScene:]
+ -[SBScreenBrightnessCoordinator init]
+ -[SBScreenBrightnessCoordinator windowSceneDidConnect:]
+ -[SBScreenBrightnessCoordinator windowSceneDidDisconnect:]
+ -[SBScreenBrightnessDebugHUDView .cxx_destruct]
+ -[SBScreenBrightnessDebugHUDView _clearNumberLabel:]
+ -[SBScreenBrightnessDebugHUDView _invalidateLayout]
+ -[SBScreenBrightnessDebugHUDView _numberLabel]
+ -[SBScreenBrightnessDebugHUDView _titleLabelWithString:]
+ -[SBScreenBrightnessDebugHUDView _updateNumberLabel:withDoubleValue:]
+ -[SBScreenBrightnessDebugHUDView _windowSceneBrightnessDidUpdate:]
+ -[SBScreenBrightnessDebugHUDView brightnessDidChange:]
+ -[SBScreenBrightnessDebugHUDView dealloc]
+ -[SBScreenBrightnessDebugHUDView initWithCoordinator:]
+ -[SBScreenBrightnessDebugHUDView invalidate]
+ -[SBScreenBrightnessDebugHUDView sanitizedBrightnessDidChange:]
+ -[SBScreenBrightnessDebugHUDView sizeThatFits:]
+ -[SBScreenBrightnessDebugHUDView updateWindowScene:]
+ -[SBScreenBrightnessDisplayClient .cxx_destruct]
+ -[SBScreenBrightnessDisplayClient _displayDidTurnOn]
+ -[SBScreenBrightnessDisplayClient _displayWillTurnOff]
+ -[SBScreenBrightnessDisplayClient _isBrightnessUnchangedFrom:to:]
+ -[SBScreenBrightnessDisplayClient _newRequestWithBrightness:pendingDisplayOn:]
+ -[SBScreenBrightnessDisplayClient _notifyQueue_readBrightnessFromDisplayForced:]
+ -[SBScreenBrightnessDisplayClient _sanitizedBrightnessLevel:]
+ -[SBScreenBrightnessDisplayClient _updateBrightnessTracking]
+ -[SBScreenBrightnessDisplayClient _updateDisplayWithBrightness:displayClient:]
+ -[SBScreenBrightnessDisplayClient addObserver:]
+ -[SBScreenBrightnessDisplayClient backlightController:didTransitionToBacklightState:source:]
+ -[SBScreenBrightnessDisplayClient backlightController:willTransitionToBacklightState:source:]
+ -[SBScreenBrightnessDisplayClient brightnessControlAvailableUpdate:]
+ -[SBScreenBrightnessDisplayClient brightnessUpdate:]
+ -[SBScreenBrightnessDisplayClient initWithClient:windowScene:]
+ -[SBScreenBrightnessDisplayClient invalidate]
+ -[SBScreenBrightnessDisplayClient notifyQueue]
+ -[SBScreenBrightnessDisplayClient relinquishRequest:]
+ -[SBScreenBrightnessDisplayClient removeObserver:]
+ -[SBScreenBrightnessDisplayClient requestPreferredBrightness:]
+ -[SBScreenBrightnessHostComponent _hostWindowScene]
+ -[SBScreenBrightnessHostComponent _observeHostedScenePolicyHostComponentIfNeeded]
+ -[SBScreenBrightnessHostComponent _updateParticipantForSettings:]
+ -[SBScreenBrightnessHostComponent activateWithSanitizedBrightnessUpdates:]
+ -[SBScreenBrightnessHostComponent brightnessDidChange:]
+ -[SBScreenBrightnessHostComponent deactivate]
+ -[SBScreenBrightnessHostComponent sanitizedBrightnessDidChange:]
+ -[SBScreenBrightnessHostComponent scene:willUpdateSettings:]
+ -[SBScreenBrightnessHostComponent sceneHostingPolicyHostComponentDidUpdateHostWindowScene:]
+ -[SBScreenBrightnessParticipant .cxx_destruct]
+ -[SBScreenBrightnessParticipant _clearBrightnessRequest]
+ -[SBScreenBrightnessParticipant _updateBrightnessRequest]
+ -[SBScreenBrightnessParticipant _updateDisplayClient:]
+ -[SBScreenBrightnessParticipant dealloc]
+ -[SBScreenBrightnessParticipant displayClient:brightnessDidChange:]
+ -[SBScreenBrightnessParticipant displayClient:sanitizedBrightnessDidChange:]
+ -[SBScreenBrightnessParticipant displayClientDidInvalidate:]
+ -[SBScreenBrightnessParticipant initWithObserver:coordinator:]
+ -[SBScreenBrightnessParticipant invalidate]
+ -[SBScreenBrightnessParticipant preferredBrightness]
+ -[SBScreenBrightnessParticipant resignWindowScene]
+ -[SBScreenBrightnessParticipant setPreferredBrightness:]
+ -[SBScreenBrightnessParticipant updateWindowScene:]
+ -[SBScreenBrightnessRequest .cxx_destruct]
+ -[SBScreenBrightnessRequest brightness]
+ -[SBScreenBrightnessRequest delivered]
+ -[SBScreenBrightnessRequest initWithDisplayClient:brightness:pendingDisplayOn:]
+ -[SBScreenBrightnessRequest invalidate]
+ -[SBScreenBrightnessRequest isOverruled]
+ -[SBScreenBrightnessRequest isPendingDisplayOn]
+ -[SBScreenBrightnessRequest overruled]
+ -[SBSecureRenderingViolationHandler _markArchiveAsPurgeableAtURL:]
+ -[SBSplitResizeWindowingModifier dimmingAlphaForLayoutRole:inAppLayout:]
+ -[SBSwitcherController _autoLayoutSpaceForAppLayout:layoutAttributes:]
+ -[SBSwitcherModifier(SharedModifierUtilities) displayItemsChangingSizeFromAppLayout:toAppLayout:fromDisplayItemLayoutAttributesMap:toDisplayItemLayoutAttributesMap:]
+ -[SBTelephonyManager _mobileEquipmentInfoForSlot:]
+ -[SBTransientOverlayViewController _isStatusBarZeroHeightInContainerOrientation]
+ -[SpringBoard _resumeAppReplacementIfNecessary]
+ -[SpringBoard screenBrightnessCoordinator]
+ -[_SBSATimerAndDescriptionRecord dealloc]
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table203
+ GCC_except_table259
+ GCC_except_table263
+ GCC_except_table317
+ GCC_except_table373
+ GCC_except_table405
+ GCC_except_table451
+ GCC_except_table561
+ GCC_except_table571
+ GCC_except_table584
+ _FBSDebugOptionKeyDeveloperToolsOptions
+ _FBSSceneJetsamPriorityDefault
+ _OBJC_CLASS_$_CBDisplayBrightnessClient
+ _OBJC_CLASS_$_OSLaunchdDeveloperToolsOptions
+ _OBJC_CLASS_$_SBScreenBrightnessCoordinator
+ _OBJC_CLASS_$_SBScreenBrightnessDebugHUDView
+ _OBJC_CLASS_$_SBScreenBrightnessDisplayClient
+ _OBJC_CLASS_$_SBScreenBrightnessParticipant
+ _OBJC_CLASS_$_SBScreenBrightnessRequest
+ _OBJC_IVAR_$_SBAccessibilityUIServerUISceneController._presentersByPresentationStyle
+ _OBJC_IVAR_$_SBAppPlatterDragPreview._pendingIconViewListLayoutProvider
+ _OBJC_IVAR_$_SBAppResizingSession._monitoredWindowScene
+ _OBJC_IVAR_$_SBApplication._uninstallRequestFulfilled
+ _OBJC_IVAR_$_SBAssistantIslandStageCoordinator._lastKeybagEffectivelyLocked
+ _OBJC_IVAR_$_SBBackgroundAngelKeepAliveHandler._handleLastGrantedBootstrap
+ _OBJC_IVAR_$_SBContinuityDisplayDelayedUIWindowSceneDelegate._systemEdgeGesturesIgnoreHIDEdgeFlagsAssertion
+ _OBJC_IVAR_$_SBContinuitySession._disableHomeGestureAssertion
+ _OBJC_IVAR_$_SBContinuousExposeAppToAppModifier._ignoredAppLayout
+ _OBJC_IVAR_$_SBContinuousExposeAppToAppModifier._shouldOrderToAppLayoutFront
+ _OBJC_IVAR_$_SBExternalDisplayWindowSceneDelegate._homeScreenController
+ _OBJC_IVAR_$_SBFlexibleWindowingAutoLayoutSpace._stageSpanningSplit
+ _OBJC_IVAR_$_SBFullScreenToPeekAnimationModifier._displayItemLayoutAttributesCalculator
+ _OBJC_IVAR_$_SBFullScreenToPeekAnimationModifier._fromLayoutAttributesMap
+ _OBJC_IVAR_$_SBFullScreenToPeekAnimationModifier._toLayoutAttributesMap
+ _OBJC_IVAR_$_SBLockScreenCoordinator._startupTransitionState
+ _OBJC_IVAR_$_SBPIPPegasusContainerAdapter._inFlightRotation
+ _OBJC_IVAR_$_SBPIPPegasusContainerAdapter._inFlightRotationCompletionHandler
+ _OBJC_IVAR_$_SBPIPPegasusContainerAdapter._inFlightRotationContentViewFrame
+ _OBJC_IVAR_$_SBPIPPegasusContainerAdapter._rotationAnimationGeneration
+ _OBJC_IVAR_$_SBScreenBrightnessCoordinator._client
+ _OBJC_IVAR_$_SBScreenBrightnessCoordinator._displayClientsByDisplayProxyIdentifier
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._participant
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._rawValueLabel
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._sanitizedValueLabel
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._stackView
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._windowScene
+ _OBJC_IVAR_$_SBScreenBrightnessDebugHUDView._windowSceneValueLabel
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._backlightController
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._displayHardwareIdentifier
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_displayClient
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_displayIsOff
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_lastNotifiedBrightness
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_observers
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_registeredForBrightnessUpdates
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._lock_request
+ _OBJC_IVAR_$_SBScreenBrightnessDisplayClient._notifyQueue
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._isActive
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._observingHostedScenePolicyHostComponent
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._participant
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._updatesWithSanitizedBrightness
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._coordinator
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._displayClient
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._invalidated
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._observer
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._preferredBrightness
+ _OBJC_IVAR_$_SBScreenBrightnessParticipant._request
+ _OBJC_IVAR_$_SBScreenBrightnessRequest._brightness
+ _OBJC_IVAR_$_SBScreenBrightnessRequest._lock
+ _OBJC_IVAR_$_SBScreenBrightnessRequest._lock_displayClient
+ _OBJC_IVAR_$_SBScreenBrightnessRequest._lock_state
+ _OBJC_IVAR_$_SpringBoard._screenBrightnessCoordinator
+ _OBJC_METACLASS_$_SBScreenBrightnessCoordinator
+ _OBJC_METACLASS_$_SBScreenBrightnessDebugHUDView
+ _OBJC_METACLASS_$_SBScreenBrightnessDisplayClient
+ _OBJC_METACLASS_$_SBScreenBrightnessParticipant
+ _OBJC_METACLASS_$_SBScreenBrightnessRequest
+ _SBFindingUIAngelBundleIdentifier
+ _SBScreenBrightnessNotSet
+ _SBSiriAppBundleIdentifier
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ _UIScreenBrightnessDidChangeNotification
+ __OBJC_$_CLASS_METHODS_SBChainableModifier(RuntimeProviding|SwitcherModifier|WindowingModifier)
+ __OBJC_$_INSTANCE_METHODS_FBScene(SBVisibilitySceneExtension_ForSceneManager|SafeAreaResolverExtensionDelegate|SBSUIHomeScreenIconStyle|InputUISceneController|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBScreenBrightnessHost|SBProductivityGestureDestination|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
+ __OBJC_$_INSTANCE_METHODS_SBChainableModifier(RuntimeProviding|SwitcherModifier|WindowingModifier)
+ __OBJC_$_INSTANCE_METHODS_SBChainableModifierEvent(SBSwitcherModifierEvent|SBWindowingModifierActivity)
+ __OBJC_$_INSTANCE_METHODS_SBChainableModifierEventResponse(SBSwitcherModifierEventResponse|SBWindowingModifierResponse)
+ __OBJC_$_INSTANCE_METHODS_SBScreenBrightnessCoordinator
+ __OBJC_$_INSTANCE_METHODS_SBScreenBrightnessDebugHUDView
+ __OBJC_$_INSTANCE_METHODS_SBScreenBrightnessDisplayClient
+ __OBJC_$_INSTANCE_METHODS_SBScreenBrightnessParticipant
+ __OBJC_$_INSTANCE_METHODS_SBScreenBrightnessRequest
+ __OBJC_$_INSTANCE_METHODS_SBWindowingModifierActivity(TransitionEvent|GestureEvent|StripChangedModifierActivity)
+ __OBJC_$_INSTANCE_VARIABLES_SBScreenBrightnessCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_SBScreenBrightnessDebugHUDView
+ __OBJC_$_INSTANCE_VARIABLES_SBScreenBrightnessDisplayClient
+ __OBJC_$_INSTANCE_VARIABLES_SBScreenBrightnessParticipant
+ __OBJC_$_INSTANCE_VARIABLES_SBScreenBrightnessRequest
+ __OBJC_$_PROP_LIST_SBScreenBrightnessCoordinator
+ __OBJC_$_PROP_LIST_SBScreenBrightnessDebugHUDView
+ __OBJC_$_PROP_LIST_SBScreenBrightnessDisplayClient
+ __OBJC_$_PROP_LIST_SBScreenBrightnessParticipant
+ __OBJC_$_PROP_LIST_SBScreenBrightnessRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBScreenBrightnessDisplayClientObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBScreenBrightnessObserving
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBScreenBrightnessDisplayClientObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBScreenBrightnessHost
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBScreenBrightnessDisplayClientObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBScreenBrightnessHost
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBScreenBrightnessObserving
+ __OBJC_$_PROTOCOL_REFS_SBScreenBrightnessDisplayClientObserver
+ __OBJC_$_PROTOCOL_REFS_SBScreenBrightnessHost
+ __OBJC_$_PROTOCOL_REFS_SBScreenBrightnessObserving
+ __OBJC_CLASS_PROTOCOLS_$_FBScene(SBVisibilitySceneExtension_ForSceneManager|SafeAreaResolverExtensionDelegate|SBSUIHomeScreenIconStyle|InputUISceneController|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBScreenBrightnessHost|SBProductivityGestureDestination|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
+ __OBJC_CLASS_PROTOCOLS_$_SBScreenBrightnessCoordinator
+ __OBJC_CLASS_PROTOCOLS_$_SBScreenBrightnessDebugHUDView
+ __OBJC_CLASS_PROTOCOLS_$_SBScreenBrightnessDisplayClient
+ __OBJC_CLASS_PROTOCOLS_$_SBScreenBrightnessParticipant
+ __OBJC_CLASS_PROTOCOLS_$_SBScreenBrightnessRequest
+ __OBJC_CLASS_RO_$_SBScreenBrightnessCoordinator
+ __OBJC_CLASS_RO_$_SBScreenBrightnessDebugHUDView
+ __OBJC_CLASS_RO_$_SBScreenBrightnessDisplayClient
+ __OBJC_CLASS_RO_$_SBScreenBrightnessParticipant
+ __OBJC_CLASS_RO_$_SBScreenBrightnessRequest
+ __OBJC_LABEL_PROTOCOL_$_SBScreenBrightnessDisplayClientObserver
+ __OBJC_LABEL_PROTOCOL_$_SBScreenBrightnessHost
+ __OBJC_LABEL_PROTOCOL_$_SBScreenBrightnessObserving
+ __OBJC_METACLASS_RO_$_SBScreenBrightnessCoordinator
+ __OBJC_METACLASS_RO_$_SBScreenBrightnessDebugHUDView
+ __OBJC_METACLASS_RO_$_SBScreenBrightnessDisplayClient
+ __OBJC_METACLASS_RO_$_SBScreenBrightnessParticipant
+ __OBJC_METACLASS_RO_$_SBScreenBrightnessRequest
+ __OBJC_PROTOCOL_$_SBScreenBrightnessDisplayClientObserver
+ __OBJC_PROTOCOL_$_SBScreenBrightnessHost
+ __OBJC_PROTOCOL_$_SBScreenBrightnessObserving
+ __UISceneRenderingEnvironmentBrightnessNotSet
+ ___112-[SBDynamicFlashlightActivityElement contentProviderWillTransitionToSize:inContainerView:transitionCoordinator:]_block_invoke_3
+ ___132-[SBActivityAmbientViewController _animateTransitionToCompactOverlayForItem:transitionType:compactOverlayViewController:completion:]_block_invoke_7
+ ___132-[SBActivityAmbientViewController _animateTransitionToCompactOverlayForItem:transitionType:compactOverlayViewController:completion:]_block_invoke_8
+ ___165-[SBSwitcherModifier(SharedModifierUtilities) displayItemsChangingSizeFromAppLayout:toAppLayout:fromDisplayItemLayoutAttributesMap:toDisplayItemLayoutAttributesMap:]_block_invoke
+ ___46-[SBAssistantController _updateDeferringRules]_block_invoke
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke_2
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke_3
+ ___52-[SBScreenBrightnessDisplayClient _displayDidTurnOn]_block_invoke
+ ___52-[SBScreenBrightnessDisplayClient _displayDidTurnOn]_block_invoke_2
+ ___52-[SBScreenBrightnessDisplayClient brightnessUpdate:]_block_invoke
+ ___60+[SBHomeScreenService _validationErrorForStashedLayoutName:]_block_invoke
+ ___60-[SBScreenBrightnessDisplayClient _updateBrightnessTracking]_block_invoke
+ ___62-[SBContinuousExposeAppToAppModifier didMoveToParentModifier:]_block_invoke
+ ___68-[SBScreenBrightnessDisplayClient brightnessControlAvailableUpdate:]_block_invoke
+ ___73-[SBAssistantIslandStageController _setSceneActivityMode:jetsamPriority:]_block_invoke
+ ___75-[_SBFullScreenAppFloorSwitcherModifier handleSwitcherShortcutActionEvent:]_block_invoke_10
+ ___75-[_SBFullScreenAppFloorSwitcherModifier handleSwitcherShortcutActionEvent:]_block_invoke_9
+ ___79-[SBMainDisplayLayoutStateManager _layoutStateForApplicationTransitionContext:]_block_invoke_36
+ ___79-[SBMainDisplayLayoutStateManager _layoutStateForApplicationTransitionContext:]_block_invoke_37
+ ___79-[SBMainDisplayLayoutStateManager _layoutStateForApplicationTransitionContext:]_block_invoke_38
+ ___79-[SBMainDisplayLayoutStateManager _layoutStateForApplicationTransitionContext:]_block_invoke_39
+ ___83-[SBContinuousExposeRootSwitcherModifier transitionModifierForMainTransitionEvent:]_block_invoke_10
+ ___85+[SBIconStateArchiver _iconListByAssigningMissingFolderIdentifiers:identifierPrefix:]_block_invoke
+ ___86+[SBIconStateArchiver _iconListsByAssigningMissingFolderIdentifiers:identifierPrefix:]_block_invoke
+ ___87-[SBTransientOverlayViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke_3
+ ___96-[SBActivityAmbientViewController _addNewBackgroundBlurMaterialViewWithInitialWeighting:hidden:]_block_invoke
+ ___block_descriptor_35_e33_v16?0"FBSMutableSceneSettings"8l
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40r_e26_v24?0"SBDisplayItem"8q16ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e33_B16?0"FBSDisplayLayoutElement"8ls32l8r40l8
+ ___block_descriptor_49_e8_32s40s_e25_B16?0"SBLayoutElement"8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e43_B16?0"SBFlexibleWindowingAutoLayoutItem"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e25_v28?0"NSString"8i16^B20lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48w_e40_v16?0"<RBSProcessMonitorConfiguring>"8ls32l8s40l8w48l8
+ ___block_descriptor_56_e8_32s40s_e15_v32?08Q16^B24ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s56l8s48l8
+ ___block_descriptor_67_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s64l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e23_B16?0"SBDisplayItem"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48bs56r64r72r_e17_v16?0"NSArray"8lr56l8s32l8s40l8r64l8s48l8r72l8
+ ___block_descriptor_88_e8_32s40s48bs56r64r72r80r_e8_v16?0q8ls32l8s40l8r56l8r64l8r72l8r80l8s48l8
+ __clamp
+ __validationErrorForStashedLayoutName:.invalidCharacters
+ __validationErrorForStashedLayoutName:.onceToken
+ _fsctl
+ _kTCCServiceSiriAccess
- -[SBActivationInfoViewController _processMobileEquipmentInfo:forSlot:]
- -[SBAppResizingCoordinator acquireSessionForDisplay:resizingCornerRadius:]
- -[SBAppResizingSession initWithWindowSceneManager:displayUniqueId:resizingCornerRadius:]
- -[SBAppResizingSession prepareForDisplayWithBounds:]
- -[SBApplicationController _appClassForInfo:]
- -[SBHomeScreenController additionalFloatingDockControllers]
- -[SBHomeScreenController setAdditionalFloatingDockControllers:]
- -[SBMinimizeItemFromSplitResizeWindowingModifier opacityForLayoutRole:inAppLayout:atIndex:]
- -[SBNotificationCarPlayDestination _clearNotificationRequestPendingAnnounceDeactivationIfNecessary]
- -[SBScreenBrightnessHostComponent _applyPreferredBrightness:]
- -[SBScreenBrightnessHostComponent _configureDisplayClientForDisplayConfiguration:]
- -[SBScreenBrightnessHostComponent _flushPendingBrightnessToScene:]
- -[SBScreenBrightnessHostComponent _tearDownDisplayClient]
- -[SBScreenBrightnessHostComponent brightnessUpdate:]
- -[SBScreenBrightnessHostComponent init]
- -[SBScreenBrightnessHostComponent notifyQueue]
- -[SBScreenBrightnessHostComponent scene:didUpdateClientSettings:]
- -[SBScreenBrightnessHostComponent scene:didUpdateSettings:]
- -[SBScreenBrightnessHostComponent setScene:]
- -[SBSplitResizeWindowingModifier opacityForLayoutRole:inAppLayout:atIndex:]
- -[SBSwitcherWindowingSettings setWindowDragRubberBandedTranslationRange:]
- -[SBSwitcherWindowingSettings windowDragRubberBandedTranslationRange]
- GCC_except_table133
- GCC_except_table293
- GCC_except_table321
- GCC_except_table347
- GCC_except_table388
- GCC_except_table396
- GCC_except_table401
- GCC_except_table443
- GCC_except_table557
- GCC_except_table567
- GCC_except_table582
- GCC_except_table94
- _OBJC_IVAR_$_SBAppResizingSession._hostingWindowScene
- _OBJC_IVAR_$_SBFlexibleWindowingWindowDragSwitcherModifier._rubberBandingRange
- _OBJC_IVAR_$_SBHomeScreenController._additionalFloatingDockControllers
- _OBJC_IVAR_$_SBLockScreenCoordinator._isInLostMode
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._displayClient
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._lastNotifiedBrightnessLock
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._lock_lastNotifiedBrightness
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._notifyQueue
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._pendingBrightness
- _OBJC_IVAR_$_SBSwitcherWindowingSettings._windowDragRubberBandedTranslationRange
- _OBJC_IVAR_$_SBTransitionSwitcherModifier._fromAppLayout
- _OBJC_IVAR_$_SBTransitionSwitcherModifier._toAppLayout
- _SBScreenBrightnessSharedCBClient.onceToken
- _SBScreenBrightnessSharedCBClient.sharedClient
- __OBJC_$_CLASS_METHODS_SBChainableModifier(RuntimeProviding|WindowingModifier|SwitcherModifier)
- __OBJC_$_INSTANCE_METHODS_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|InputUISceneController|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SafeAreaResolverExtensionDelegate|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
- __OBJC_$_INSTANCE_METHODS_SBChainableModifier(RuntimeProviding|WindowingModifier|SwitcherModifier)
- __OBJC_$_INSTANCE_METHODS_SBChainableModifierEvent(SBWindowingModifierActivity|SBSwitcherModifierEvent)
- __OBJC_$_INSTANCE_METHODS_SBChainableModifierEventResponse(SBWindowingModifierResponse|SBSwitcherModifierEventResponse)
- __OBJC_$_INSTANCE_METHODS_SBWindowingModifierActivity(TransitionEvent|StripChangedModifierActivity|GestureEvent)
- __OBJC_CLASS_PROTOCOLS_$_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|InputUISceneController|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SafeAreaResolverExtensionDelegate|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
- ___52-[SBScreenBrightnessHostComponent brightnessUpdate:]_block_invoke
- ___60-[SBNotificationCarPlayDestination postNotificationRequest:]_block_invoke
- ___60-[SBNotificationCarPlayDestination postNotificationRequest:]_block_invoke_2
- ___SBScreenBrightnessSharedCBClient_block_invoke
- ___block_descriptor_40_e8_32r_e25_v28?0"NSString"8i16^B20lr32l8
- ___block_descriptor_40_e8_32s_e33_B16?0"FBSDisplayLayoutElement"8ls32l8
- ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls40l8s32l8
- ___block_descriptor_48_e8_32s40w_e40_v16?0"<RBSProcessMonitorConfiguring>"8ls32l8w40l8
- ___block_descriptor_50_e8_32s40w_e8_v12?0B8lw40l8s32l8
- ___block_descriptor_51_e8_32s40w_e5_v8?0lw40l8s32l8
- ___block_descriptor_59_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48r56r64r_e17_v16?0"NSArray"8lr48l8s32l8s40l8r56l8r64l8
- ___block_descriptor_80_e8_32s40s48r56r64r72r_e8_v16?0q8ls32l8s40l8r48l8r56l8r64l8r72l8
- ___block_descriptor_88_e8_32s40bs_e11_v16?0B8B12ls32l8s40l8
```
