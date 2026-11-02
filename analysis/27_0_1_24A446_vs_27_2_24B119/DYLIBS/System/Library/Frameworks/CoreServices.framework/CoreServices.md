## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

```diff

-1517.0.1.0.0
-  __TEXT.__text: 0x1c7974
+1517.1.12.0.0
+  __TEXT.__text: 0x1cde80
   __TEXT.__delay_helper: 0x1b8
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0xe1fc
-  __TEXT.__const: 0x9b0
-  __TEXT.__cstring: 0x28c90
-  __TEXT.__oslogstring: 0x1667b
-  __TEXT.__gcc_except_tab: 0x29618
+  __TEXT.__objc_methlist: 0xe304
+  __TEXT.__const: 0x9c0
+  __TEXT.__cstring: 0x294e8
+  __TEXT.__oslogstring: 0x16d87
+  __TEXT.__gcc_except_tab: 0x2a294
   __TEXT.__ustring: 0x23c
-  __TEXT.__unwind_info: 0xc630
+  __TEXT.__unwind_info: 0xc798
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7478
+  __DATA_CONST.__const: 0x7588
   __DATA_CONST.__objc_classlist: 0x7b0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6548
+  __DATA_CONST.__objc_selrefs: 0x65f8
   __DATA_CONST.__objc_protorefs: 0x90
   __DATA_CONST.__objc_superrefs: 0x640
   __DATA_CONST.__objc_arraydata: 0x990
   __DATA_CONST.__got: 0xbb8
-  __AUTH_CONST.__const: 0x3bb0
-  __AUTH_CONST.__cfstring: 0x17a60
-  __AUTH_CONST.__objc_const: 0x156e8
+  __AUTH_CONST.__const: 0x3c00
+  __AUTH_CONST.__cfstring: 0x17d60
+  __AUTH_CONST.__objc_const: 0x15750
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__lazy_load_got: 0x10
-  __AUTH_CONST.__objc_intobj: 0x7f8
+  __AUTH_CONST.__objc_intobj: 0x7e0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x150
-  __AUTH_CONST.__auth_got: 0x1968
+  __AUTH_CONST.__auth_got: 0x1970
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x33b8
+  __AUTH.__objc_data: 0x3368
   __AUTH.__data: 0x318
-  __DATA.__objc_ivar: 0xbf0
-  __DATA.__data: 0x15c4
-  __DATA.__bss: 0xf40
+  __DATA.__objc_ivar: 0xbf8
+  __DATA.__data: 0x15bc
+  __DATA.__bss: 0xf18
   __DATA.__common: 0x40
-  __DATA_DIRTY.__objc_data: 0x1928
+  __DATA_DIRTY.__objc_data: 0x1978
   __DATA_DIRTY.__data: 0x58
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0x948
+  __DATA_DIRTY.__bss: 0x970
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 9545
-  Symbols:   14243
+  Functions: 9610
+  Symbols:   14309
   CStrings:  0
 
Symbols:
+ +[LSApplicationIdentity(Conveniences) applicationIdentityForJobLabel:error:]
+ +[LSApplicationRecord(AppReplacement) applicationRecordForPotentiallyReplacedBundleIdentifier:fetchingPlaceholder:error:]
+ +[LSBundleRecord _bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:]
+ +[LSBundleRecord bundleRecordForApplicationIdentifier:error:]
+ -[LSApplicationRecord _LSRecord_resolve_jobLabel]
+ -[LSApplicationRecord initWithJobLabel:error:]
+ -[LSApplicationRecord jobLabelWithContext:tableID:unitID:unitBytes:]
+ -[LSApplicationRecord(MobileInstall) isInstallationHoldActive]
+ -[LSApplicationRestrictionsManager clearCachedValues]
+ -[LSApplicationRestrictionsManager isApplicationRestricted:checkBundleFlags:stateProvider:]
+ -[LSApplicationWorkspace setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]
+ -[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]
+ -[LSApplicationWorkspace setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]
+ -[LSApplicationWorkspace(Migration) migrateApplicationPreferencesFromIdentity:toIdentity:error:]
+ -[LSBundleRecordBuilder appReplacementSourceID]
+ -[LSBundleRecordBuilder launchDLabel]
+ -[LSBundleRecordBuilder setAppReplacementSourceID:]
+ -[LSBundleRecordBuilder shouldBeAlwaysAvailable]
+ -[LSBundleRecordUpdater rollPluginUUIDs]
+ -[LSBundleRecordUpdater setAppReplacementSourceBundleIdentifier:]
+ -[LSBundleRecordUpdater setInstallationHoldActive:]
+ -[LSMarketplacesPreferences migrateBundleIdentifier:toBundleIdentifier:]
+ -[_LSDModifyClient migratePreferencesFromBundleIdentifier:toBundleIdentifier:destinationBundleVersion:completionHandler:]
+ -[_LSDModifyClient setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:reply:]
+ -[_LSDModifyClient setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:reply:]
+ -[_LSDModifyClient setSystemBuildVersion:completionHandler:]
+ GCC_except_table135
+ GCC_except_table155
+ GCC_except_table186
+ GCC_except_table203
+ GCC_except_table209
+ GCC_except_table219
+ GCC_except_table222
+ GCC_except_table225
+ GCC_except_table234
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table247
+ GCC_except_table248
+ GCC_except_table258
+ GCC_except_table259
+ GCC_except_table260
+ GCC_except_table265
+ GCC_except_table268
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table275
+ GCC_except_table282
+ GCC_except_table283
+ GCC_except_table290
+ GCC_except_table293
+ GCC_except_table298
+ GCC_except_table303
+ GCC_except_table304
+ GCC_except_table312
+ GCC_except_table313
+ GCC_except_table315
+ GCC_except_table317
+ GCC_except_table320
+ GCC_except_table329
+ GCC_except_table330
+ GCC_except_table331
+ GCC_except_table344
+ GCC_except_table347
+ GCC_except_table353
+ GCC_except_table364
+ GCC_except_table370
+ GCC_except_table377
+ GCC_except_table380
+ GCC_except_table383
+ GCC_except_table384
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table399
+ GCC_except_table400
+ GCC_except_table401
+ GCC_except_table403
+ GCC_except_table404
+ GCC_except_table405
+ GCC_except_table406
+ GCC_except_table407
+ GCC_except_table408
+ GCC_except_table418
+ GCC_except_table424
+ GCC_except_table429
+ GCC_except_table433
+ GCC_except_table463
+ GCC_except_table481
+ GCC_except_table483
+ GCC_except_table487
+ GCC_except_table488
+ GCC_except_table489
+ GCC_except_table504
+ GCC_except_table524
+ GCC_except_table525
+ GCC_except_table528
+ GCC_except_table531
+ GCC_except_table533
+ GCC_except_table534
+ GCC_except_table544
+ GCC_except_table568
+ _OBJC_IVAR_$_LSBundleRecordBuilder._appReplacementSourceID
+ _OBJC_IVAR_$_LSBundleRecordBuilder._launchDLabel
+ __LSBundleFindWithJobLabel
+ __LSDatabaseSetSeededSystemBuildVersion
+ __LSGetApplicationIdentifierEntitlementKeys
+ __LSGetApplicationIdentifierFromEntitlements
+ __LSServer_LSHandlerPrefMigrateBundleID
+ __LSServer_SetDatabaseSystemBuildVersion
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_ICLBundleRecord_$_LSExtensions
+ __OBJC_$_CLASS_METHODS_LSApplicationRecord(Containers|iTunesMetadata|UniqueIdentifiers|InfoPlistRarities|Localization|AlternateIconsInternal|AlternateIcons|IconServices|Intents|UserActivity|Gaming|AppWrappers|MobileInstall|watchOS|InstallMachineryPrivate|Transitional|Identities|DefaultApps|BUIPrivate|ForRunningBoardOnly|JournalApp|AppReplacement|Redaction|Diagnostic|Enumeration)
+ __OBJC_$_CLASS_METHODS_LSApplicationWorkspace(DeprecatedEnumeration|DefaultApps|Marketplaces|Migration|URLQueries|DeprecatedURLQueries|OpenAdditions|LSURLOverride|PersonaNiceties)
+ __OBJC_$_INSTANCE_METHODS_LSApplicationRecord(Containers|iTunesMetadata|UniqueIdentifiers|InfoPlistRarities|Localization|AlternateIconsInternal|AlternateIcons|IconServices|Intents|UserActivity|Gaming|AppWrappers|MobileInstall|watchOS|InstallMachineryPrivate|Transitional|Identities|DefaultApps|BUIPrivate|ForRunningBoardOnly|JournalApp|AppReplacement|Redaction|Diagnostic|Enumeration)
+ __OBJC_$_INSTANCE_METHODS_LSApplicationWorkspace(DeprecatedEnumeration|DefaultApps|Marketplaces|Migration|URLQueries|DeprecatedURLQueries|OpenAdditions|LSURLOverride|PersonaNiceties)
+ __ZL35appAndPlaceholderUnitsForIdentifierP9LSContextP8NSString
+ __ZN13LSHandlerPref35MigrateRoleHandlersMatchingBundleIDEP11_LSDatabasejj15LSVersionNumber
+ __ZN14LaunchServices16BindingEvaluator18CreateWithJobLabelEP8NSStringb
+ __ZN14LaunchServices16BindingEvaluator31CreateWithApplicationIdentifierEP8NSStringbb
+ __ZN14LaunchServicesL31bbtm2DescriptionFlavorAvailableEv
+ __ZNSt3__116__if_likely_elseB9fqn220106IZNS_6vectorINS_4pairIjhEENS_9allocatorIS3_EEE12emplace_backIJRjS8_EEERS3_DpOT_EUlvE_ZNS7_IJS8_S8_EEES9_SC_EUlvE0_EEvbT_T0_
+ __ZNSt3__16vectorINS_4pairIjhEENS_9allocatorIS2_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS_4pairIjhEENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRjS7_EEEPS2_DpOT_
+ __ZNSt3__19allocatorINS_4pairIjhEEE17allocate_at_leastB9fqn220106Em
+ __ZZ42_LSGetApplicationIdentifierEntitlementKeysE5sOnce
+ __ZZ42_LSGetApplicationIdentifierEntitlementKeysE7sResult
+ ___100-[_LSDModifyClient setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:reply:]_block_invoke
+ ___115-[_LSDModifyClient setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:reply:]_block_invoke
+ ___121-[_LSDModifyClient migratePreferencesFromBundleIdentifier:toBundleIdentifier:destinationBundleVersion:completionHandler:]_block_invoke
+ ___121-[_LSDModifyClient migratePreferencesFromBundleIdentifier:toBundleIdentifier:destinationBundleVersion:completionHandler:]_block_invoke_2
+ ___134-[LSApplicationWorkspace setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]_block_invoke
+ ___134-[LSApplicationWorkspace setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]_block_invoke_2
+ ___149-[LSApplicationWorkspace setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]_block_invoke
+ ___149-[LSApplicationWorkspace setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:]_block_invoke_2
+ ___40-[LSBundleRecordUpdater rollPluginUUIDs]_block_invoke
+ ___46-[LSApplicationRecord initWithJobLabel:error:]_block_invoke
+ ___60-[_LSDModifyClient setSystemBuildVersion:completionHandler:]_block_invoke
+ ___62-[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]_block_invoke
+ ___62-[LSApplicationWorkspace setDatabaseSystemBuildVersion:error:]_block_invoke_2
+ ___88+[LSBundleRecord _bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:]_block_invoke
+ ___96-[LSApplicationWorkspace(Migration) migrateApplicationPreferencesFromIdentity:toIdentity:error:]_block_invoke
+ ___96-[LSApplicationWorkspace(Migration) migrateApplicationPreferencesFromIdentity:toIdentity:error:]_block_invoke_2
+ ____LSGetApplicationIdentifierEntitlementKeys_block_invoke
+ ____ZL24pluginUnitsForBundleDataP9LSContextPK12LSBundleData_block_invoke
+ ____ZL30getReplacementAppForIdentifierP9LSContextP8NSString26LSPlaceholderFetchBehavior_block_invoke
+ ____ZN13LSHandlerPref35MigrateRoleHandlersMatchingBundleIDEP11_LSDatabasejj15LSVersionNumber_block_invoke
+ ___block_descriptor_244_ea8_32r48c40_ZTSN14LaunchServices16BindingEvaluatorE_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20l
+ ___block_descriptor_256_ea8_32s40r48r64c59_ZTSNSt3__18optionalIN14LaunchServices16BindingEvaluatorEEE_e33_B16?0r^{?=IIIIiII[8I]IIIIIIIII}8l
+ ___block_descriptor_32_e392_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20l
+ ___block_descriptor_40_ea8_32s_e392_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20ls32l8
+ ___block_descriptor_40_ea8_32s_e392_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20ls32l8
+ ___block_descriptor_44_e392_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20l
+ ___block_descriptor_48_e8_32s40s_e392_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20ls32l8s40l8
+ ___block_descriptor_48_ea8_32bs_e198_v28?0"NSString"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}IIII}20ls32l8
+ ___block_descriptor_48_ea8_32bs_e389_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20ls32l8
+ ___block_descriptor_48_ea8_32s40s_e35_v16?0"LSMarketplacesPreferences"8ls32l8s40l8
+ ___block_descriptor_52_e8_32s40n6_8_8_s0_e392_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20l
+ ___block_descriptor_56_ea8_32bs40bs_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20ls32l8s40l8
+ ___block_descriptor_56_ea8_32r40r_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20lr32l8r40l8
+ ___block_descriptor_56_ea8_32s40bs_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20ls32l8s40l8
+ ___block_descriptor_579_ea8_32s40r48r56r64r72r_e14_v24?0I8I12*16ls32l8r40l8r48l8r56l8r64l8r72l8
+ ___block_descriptor_644_ea8_32s_e19_v32?0I8r^v12I20*24ls32l8
+ ___block_descriptor_644_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32ls32l8
+ ___block_descriptor_64_ea8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_68_ea8_32s40s48s_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32bs40r48r_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20ls32l8r40l8r48l8
+ ___block_descriptor_72_ea8_32s40s48r_e379_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}12*20ls32l8s40l8r48l8
+ ___block_descriptor_73_ea8_32s40r48r56r_e5_v8?0lr40l8s32l8r48l8r56l8
+ ___block_descriptor_73_ea8_32s40s48s56r64r_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8r56l8r64l8
+ ___block_descriptor_80_e8_32s40s48s56s64n6_8_8_s0_e392_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiIII}20l
+ ___block_descriptor_80_ea8_32s40s48s56s64r72r_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8s56l8r64l8r72l8
+ ___block_descriptor_96_ea8_32s40s48r56r_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8r48l8r56l8
+ ___copy_helper_block_ea8_48c40_ZTSN14LaunchServices16BindingEvaluatorE
+ ___destroy_helper_block_ea8_48c40_ZTSN14LaunchServices16BindingEvaluatorE
+ _kLSCanMigrateApplicationPreferencesEntitlement
+ _kLSCanSetSystemBuildVersionEntitlement
+ _os_variant_has_internal_content
- -[ICLBundleRecord(LSTransitional) ls_associatedPersonasIfAvailable]
- -[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]
- -[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]
- GCC_except_table132
- GCC_except_table158
- GCC_except_table183
- GCC_except_table197
- GCC_except_table204
- GCC_except_table211
- GCC_except_table214
- GCC_except_table217
- GCC_except_table226
- GCC_except_table230
- GCC_except_table235
- GCC_except_table239
- GCC_except_table249
- GCC_except_table251
- GCC_except_table254
- GCC_except_table256
- GCC_except_table264
- GCC_except_table266
- GCC_except_table274
- GCC_except_table277
- GCC_except_table279
- GCC_except_table280
- GCC_except_table286
- GCC_except_table288
- GCC_except_table297
- GCC_except_table299
- GCC_except_table300
- GCC_except_table306
- GCC_except_table311
- GCC_except_table314
- GCC_except_table321
- GCC_except_table322
- GCC_except_table327
- GCC_except_table340
- GCC_except_table343
- GCC_except_table349
- GCC_except_table359
- GCC_except_table361
- GCC_except_table368
- GCC_except_table371
- GCC_except_table374
- GCC_except_table378
- GCC_except_table379
- GCC_except_table381
- GCC_except_table385
- GCC_except_table387
- GCC_except_table389
- GCC_except_table396
- GCC_except_table397
- GCC_except_table412
- GCC_except_table413
- GCC_except_table417
- GCC_except_table451
- GCC_except_table459
- GCC_except_table465
- GCC_except_table469
- GCC_except_table475
- GCC_except_table476
- GCC_except_table480
- GCC_except_table512
- GCC_except_table513
- GCC_except_table516
- GCC_except_table519
- GCC_except_table521
- GCC_except_table522
- GCC_except_table532
- GCC_except_table556
- __LSRegisterExtensionPointClient
- __LSUnregisterExtensionPoint
- __LSUnregisterExtensionPointClient
- __OBJC_$_CLASS_METHODS_LSApplicationRecord(Containers|iTunesMetadata|UniqueIdentifiers|InfoPlistRarities|Localization|AlternateIconsInternal|AlternateIcons|IconServices|Intents|UserActivity|Gaming|AppWrappers|MobileInstall|watchOS|InstallMachineryPrivate|Transitional|Identities|DefaultApps|BUIPrivate|ForRunningBoardOnly|JournalApp|Redaction|Diagnostic|Enumeration)
- __OBJC_$_CLASS_METHODS_LSApplicationWorkspace(DeprecatedEnumeration|DefaultApps|Marketplaces|URLQueries|DeprecatedURLQueries|OpenAdditions|LSURLOverride|PersonaNiceties)
- __OBJC_$_INSTANCE_METHODS_ICLBundleRecord(LSExtensions|LSTransitional)
- __OBJC_$_INSTANCE_METHODS_LSApplicationRecord(Containers|iTunesMetadata|UniqueIdentifiers|InfoPlistRarities|Localization|AlternateIconsInternal|AlternateIcons|IconServices|Intents|UserActivity|Gaming|AppWrappers|MobileInstall|watchOS|InstallMachineryPrivate|Transitional|Identities|DefaultApps|BUIPrivate|ForRunningBoardOnly|JournalApp|Redaction|Diagnostic|Enumeration)
- __OBJC_$_INSTANCE_METHODS_LSApplicationWorkspace(DeprecatedEnumeration|DefaultApps|Marketplaces|URLQueries|DeprecatedURLQueries|OpenAdditions|LSURLOverride|PersonaNiceties)
- __ZN14LaunchServices16BindingEvaluator31CreateWithApplicationIdentifierEP8NSStringb
- ___101-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke
- ___45-[LSBundleRecordUpdater parsePersonas:error:]_block_invoke
- ___67-[ICLBundleRecord(LSTransitional) ls_associatedPersonasIfAvailable]_block_invoke
- ___92-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke_2
- ____LSUnregisterExtensionPointClient_block_invoke
- ____LSUnregisterExtensionPointClient_block_invoke_2
- ___block_descriptor_248_ea8_32s40r48r64c59_ZTSNSt3__18optionalIN14LaunchServices16BindingEvaluatorEEE_e33_B16?0r^{?=IIIIiII[8I]IIIIIIIII}8l
- ___block_descriptor_32_e387_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20l
- ___block_descriptor_40_ea8_32s_e387_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20ls32l8
- ___block_descriptor_40_ea8_32s_e387_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20ls32l8
- ___block_descriptor_415_ea8_32s40r48r56r64r72r_e14_v24?0I8I12*16ls32l8r40l8r48l8r56l8r64l8r72l8
- ___block_descriptor_44_e387_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20l
- ___block_descriptor_48_e8_32s40s_e387_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20ls32l8s40l8
- ___block_descriptor_48_ea8_32bs_e197_v28?0"NSString"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}IIII}20ls32l8
- ___block_descriptor_48_ea8_32bs_e384_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20ls32l8
- ___block_descriptor_52_e8_32s40n6_8_8_s0_e387_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20l
- ___block_descriptor_56_ea8_32bs40bs_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20ls32l8s40l8
- ___block_descriptor_56_ea8_32r40r_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20lr32l8r40l8
- ___block_descriptor_56_ea8_32s40bs_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20ls32l8s40l8
- ___block_descriptor_632_ea8_32s_e19_v32?0I8r^v12I20*24ls32l8
- ___block_descriptor_632_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32ls32l8
- ___block_descriptor_64_ea8_32s40s48bs_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_68_ea8_32s40s48s56bs_e42_v24?0"LSDBExecutionContext"8"NSError"16ls32l8s40l8s48l8s56l8
- ___block_descriptor_68_ea8_32s40s48s_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32bs40r48r_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20ls32l8r40l8r48l8
- ___block_descriptor_72_ea8_32s40s48r_e374_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}12*20ls32l8s40l8r48l8
- ___block_descriptor_80_e8_32s40s48s56s64n6_8_8_s0_e387_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIIiII}20l
- _ls_associatedPersonasIfAvailable.onceToken
- _ls_associatedPersonasIfAvailable.responds
```
