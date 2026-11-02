## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

```diff

-821.0.25.0.0
-  __TEXT.__text: 0x172f00
-  __TEXT.__objc_methlist: 0x121fc
-  __TEXT.__cstring: 0x18ff0
+821.1.16.0.0
+  __TEXT.__text: 0x177e20
+  __TEXT.__objc_methlist: 0x1263c
+  __TEXT.__cstring: 0x192b0
   __TEXT.__const: 0x6608
-  __TEXT.__gcc_except_tab: 0x12a0
-  __TEXT.__oslogstring: 0xdebb
+  __TEXT.__gcc_except_tab: 0x12f4
+  __TEXT.__oslogstring: 0xe0eb
   __TEXT.__ustring: 0x18
   __TEXT.__dlopen_cstrs: 0xba
   __TEXT.__swift5_typeref: 0x2062

   __TEXT.__swift_as_ret: 0x1dc
   __TEXT.__swift_as_cont: 0x3f4
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x67d8
-  __TEXT.__eh_frame: 0x5968
+  __TEXT.__unwind_info: 0x6978
+  __TEXT.__eh_frame: 0x59f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x61b0
-  __DATA_CONST.__objc_classlist: 0x810
+  __DATA_CONST.__const: 0x6218
+  __DATA_CONST.__objc_classlist: 0x828
   __DATA_CONST.__objc_catlist: 0x100
   __DATA_CONST.__objc_protolist: 0x230
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8578
+  __DATA_CONST.__objc_selrefs: 0x85a0
   __DATA_CONST.__objc_protorefs: 0x128
-  __DATA_CONST.__objc_superrefs: 0x4f0
+  __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0x280
-  __DATA_CONST.__got: 0x1108
-  __AUTH_CONST.__const: 0x6d08
-  __AUTH_CONST.__cfstring: 0x11640
-  __AUTH_CONST.__objc_const: 0x245c8
+  __DATA_CONST.__got: 0x1118
+  __AUTH_CONST.__const: 0x6d48
+  __AUTH_CONST.__cfstring: 0x11680
+  __AUTH_CONST.__objc_const: 0x24d08
   __AUTH_CONST.__objc_arrayobj: 0x150
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__auth_got: 0x1560
   __AUTH_CONST.__auth_ptr: 0x698
-  __AUTH.__objc_data: 0x2b40
+  __AUTH.__objc_data: 0x2c30
   __AUTH.__data: 0x1088
-  __DATA.__objc_ivar: 0xfb0
-  __DATA.__data: 0x3a60
-  __DATA.__bss: 0x82e0
+  __DATA.__objc_ivar: 0xfd8
+  __DATA.__data: 0x3a58
+  __DATA.__bss: 0x81f0
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x2c40
-  __DATA_DIRTY.__data: 0x748
-  __DATA_DIRTY.__bss: 0xe20
+  __DATA_DIRTY.__data: 0x758
+  __DATA_DIRTY.__bss: 0xf30
   __DATA_DIRTY.__common: 0xb8
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/Combine.framework/Combine

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11229
-  Symbols:   12321
+  Functions: 11358
+  Symbols:   12478
   CStrings:  0
 
Symbols:
+ +[GCFAchievement descriptionForAchievement:achievementDescriptions:]
+ +[GCFAchievement instanceMethodSignatureForSelector:]
+ +[GCFAchievement instancesRespondToSelector:]
+ +[GCFAchievement loadAchievementWithID:forGame:players:complete:]
+ +[GCFAchievement loadAchievementsForGameV2:player:includeUnreported:includeHidden:withCompletionHandler:]
+ +[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]
+ +[GCFAchievement loadAchievementsWithCompletionHandler:]
+ +[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]
+ +[GCFAchievement reportAchievements:withCompletionHandler:]
+ +[GCFAchievement resetAchievementsWithCompletionHandler:]
+ +[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:]
+ +[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:uiFrameworkMethodsRequired:]
+ +[GCFAchievement shouldShowBannerOnReport:reportedAchievements:]
+ +[GCFAchievement shouldShowBannerOnReport:reportedAchievements:uiFrameworkMethodsRequired:]
+ +[GCFAchievement showBannerIsSupported]
+ +[GCFAchievement supportsSecureCoding]
+ +[GCFAchievementDescription _achievementDescriptionFromGame:propertyListDictionary:]
+ +[GCFAchievementDescription _loadLocalAchievementDescriptionsForGame:]
+ +[GCFAchievementDescription instanceMethodSignatureForSelector:]
+ +[GCFAchievementDescription instancesRespondToSelector:]
+ +[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]
+ +[GCFAchievementDescription loadAchievementDescriptionsWithCompletionHandler:]
+ +[GCFAchievementDescription supportsSecureCoding]
+ -[GCFAchievement .cxx_destruct]
+ -[GCFAchievement copyWithZone:]
+ -[GCFAchievement description]
+ -[GCFAchievement encodeWithCoder:]
+ -[GCFAchievement forwardingTargetForSelector:]
+ -[GCFAchievement game]
+ -[GCFAchievement hash]
+ -[GCFAchievement initWithCoder:]
+ -[GCFAchievement initWithIdentifier:]
+ -[GCFAchievement initWithIdentifier:forPlayer:]
+ -[GCFAchievement initWithIdentifier:player:]
+ -[GCFAchievement initWithIdentifier:player:percentComplete:lastReportedDate:]
+ -[GCFAchievement initWithInternalRepresentation:]
+ -[GCFAchievement initWithInternalRepresentation:playerID:]
+ -[GCFAchievement init]
+ -[GCFAchievement internal]
+ -[GCFAchievement isCompleted]
+ -[GCFAchievement isEqual:]
+ -[GCFAchievement methodSignatureForSelector:]
+ -[GCFAchievement playerID]
+ -[GCFAchievement player]
+ -[GCFAchievement reportAchievementWithCompletionHandler:]
+ -[GCFAchievement respondsToSelector:]
+ -[GCFAchievement setGame:]
+ -[GCFAchievement setInternal:]
+ -[GCFAchievement setShowsCompletionBanner:]
+ -[GCFAchievement setValue:forUndefinedKey:]
+ -[GCFAchievement showsCompletionBanner]
+ -[GCFAchievement valueForUndefinedKey:]
+ -[GCFAchievement(GCFAchievementDescription) _achievementDescription]
+ -[GCFAchievementDescription .cxx_destruct]
+ -[GCFAchievementDescription description]
+ -[GCFAchievementDescription encodeWithCoder:]
+ -[GCFAchievementDescription forwardingTargetForSelector:]
+ -[GCFAchievementDescription game]
+ -[GCFAchievementDescription hash]
+ -[GCFAchievementDescription imageNameForIcon]
+ -[GCFAchievementDescription image]
+ -[GCFAchievementDescription initWithCoder:]
+ -[GCFAchievementDescription initWithInternalRepresentation:]
+ -[GCFAchievementDescription init]
+ -[GCFAchievementDescription internal]
+ -[GCFAchievementDescription isEqual:]
+ -[GCFAchievementDescription methodSignatureForSelector:]
+ -[GCFAchievementDescription respondsToSelector:]
+ -[GCFAchievementDescription setImage:]
+ -[GCFAchievementDescription setInternal:]
+ -[GCFAchievementDescription setValue:forUndefinedKey:]
+ -[GCFAchievementDescription valueForUndefinedKey:]
+ -[GCFLocalizedAchievementDescription .cxx_destruct]
+ -[GCFLocalizedAchievementDescription _localizedStringFromKey:]
+ -[GCFLocalizedAchievementDescription achievedDescription]
+ -[GCFLocalizedAchievementDescription game]
+ -[GCFLocalizedAchievementDescription iconImageName]
+ -[GCFLocalizedAchievementDescription imageNameForIcon]
+ -[GCFLocalizedAchievementDescription setGame:]
+ -[GCFLocalizedAchievementDescription setIconImageName:]
+ -[GCFLocalizedAchievementDescription title]
+ -[GCFLocalizedAchievementDescription unachievedDescription]
+ -[GKAchievementChallenge gcfAchievement]
+ -[GKAchievementChallenge setGcfAchievement:]
+ -[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]
+ -[GKMatch pendingPlayerIdentityResolutionGroup]
+ -[GKMatch setPendingPlayerIdentityResolutionGroup:]
+ GCC_except_table160
+ GCC_except_table167
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table175
+ GCC_except_table179
+ GCC_except_table181
+ GCC_except_table188
+ OBJC_IVAR_$_GCFLocalizedAchievementDescription._game
+ OBJC_IVAR_$_GCFLocalizedAchievementDescription._iconImageName
+ _GKOverlayBundleIDs
+ _GKOverlayBundleIDs.onceToken
+ _GKOverlayBundleIDs.sOverlayBundleIDs
+ _OBJC_CLASS_$_GCFAchievement
+ _OBJC_CLASS_$_GCFAchievementDescription
+ _OBJC_CLASS_$_GCFLocalizedAchievementDescription
+ _OBJC_IVAR_$_GCFAchievement._game
+ _OBJC_IVAR_$_GCFAchievement._internal
+ _OBJC_IVAR_$_GCFAchievement._player
+ _OBJC_IVAR_$_GCFAchievement._showsCompletionBanner
+ _OBJC_IVAR_$_GCFAchievementDescription._image
+ _OBJC_IVAR_$_GCFAchievementDescription._internal
+ _OBJC_IVAR_$_GKAchievementChallenge._gcfAchievement
+ _OBJC_IVAR_$_GKAchievementChallenge._publicAchievement
+ _OBJC_IVAR_$_GKMatch._pendingPlayerIdentityResolutionGroup
+ _OBJC_METACLASS_$_GCFAchievement
+ _OBJC_METACLASS_$_GCFAchievementDescription
+ _OBJC_METACLASS_$_GCFLocalizedAchievementDescription
+ __OBJC_$_CLASS_METHODS_GCFAchievement
+ __OBJC_$_CLASS_METHODS_GCFAchievementDescription
+ __OBJC_$_CLASS_PROP_LIST_GCFAchievement
+ __OBJC_$_CLASS_PROP_LIST_GCFAchievementDescription
+ __OBJC_$_INSTANCE_METHODS_GCFAchievement(GCFAchievementDescription)
+ __OBJC_$_INSTANCE_METHODS_GCFAchievementDescription
+ __OBJC_$_INSTANCE_METHODS_GCFLocalizedAchievementDescription
+ __OBJC_$_INSTANCE_VARIABLES_GCFAchievement
+ __OBJC_$_INSTANCE_VARIABLES_GCFAchievementDescription
+ __OBJC_$_INSTANCE_VARIABLES_GCFLocalizedAchievementDescription
+ __OBJC_$_PROP_LIST_GCFAchievement
+ __OBJC_$_PROP_LIST_GCFAchievementDescription
+ __OBJC_$_PROP_LIST_GCFLocalizedAchievementDescription
+ __OBJC_CLASS_PROTOCOLS_$_GCFAchievement
+ __OBJC_CLASS_PROTOCOLS_$_GCFAchievementDescription
+ __OBJC_CLASS_RO_$_GCFAchievement
+ __OBJC_CLASS_RO_$_GCFAchievementDescription
+ __OBJC_CLASS_RO_$_GCFLocalizedAchievementDescription
+ __OBJC_METACLASS_RO_$_GCFAchievement
+ __OBJC_METACLASS_RO_$_GCFAchievementDescription
+ __OBJC_METACLASS_RO_$_GCFLocalizedAchievementDescription
+ ___105+[GCFAchievement loadAchievementsForGameV2:player:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_2
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_3
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_4
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_5
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_2
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_3
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_4
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_5
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_6
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_7
+ ___114+[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:uiFrameworkMethodsRequired:]_block_invoke
+ ___39+[GCFAchievement showBannerIsSupported]_block_invoke
+ ___56+[GCFAchievement loadAchievementsWithCompletionHandler:]_block_invoke
+ ___57+[GCFAchievement resetAchievementsWithCompletionHandler:]_block_invoke
+ ___58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke
+ ___58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke_2
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke_2
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke_3
+ ___70+[GCFAchievementDescription _loadLocalAchievementDescriptionsForGame:]_block_invoke
+ ___78+[GCFAchievementDescription loadAchievementDescriptionsWithCompletionHandler:]_block_invoke
+ ___86+[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]_block_invoke
+ ___86+[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]_block_invoke_2
+ ___GKOverlayBundleIDs_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_49_e8_32s40r_e31_v32?0"GCFAchievement"8Q16^B24ls32l8r40l8
+ _kUnshippedOverlayBundleIDs
- -[GKAchievementChallenge setAchievement:]
- GCC_except_table164
- GCC_except_table168
- GCC_except_table170
- GCC_except_table172
- GCC_except_table176
- GCC_except_table178
- GCC_except_table185
- _OBJC_IVAR_$_GKAchievementChallenge._achievement
```
