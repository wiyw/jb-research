## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/HomeKitMatter`

```diff

-1493.1.5.1.1
-  __TEXT.__text: 0x1813cc
-  __TEXT.__objc_methlist: 0xad0c
-  __TEXT.__const: 0x298
+1520.2.7.1.3
+  __TEXT.__text: 0x18d560
+  __TEXT.__objc_methlist: 0xb0cc
+  __TEXT.__const: 0x2c8
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x302c
-  __TEXT.__cstring: 0x6ed0
-  __TEXT.__oslogstring: 0x4f542
+  __TEXT.__gcc_except_tab: 0x3414
+  __TEXT.__cstring: 0x730a
+  __TEXT.__oslogstring: 0x51beb
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0x3160
+  __TEXT.__unwind_info: 0x32f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x48f0
-  __DATA_CONST.__objc_classlist: 0x458
+  __DATA_CONST.__const: 0x4ba8
+  __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7098
+  __DATA_CONST.__objc_selrefs: 0x7360
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x310
-  __DATA_CONST.__objc_arraydata: 0x240
-  __DATA_CONST.__got: 0x9f8
-  __AUTH_CONST.__const: 0x1140
-  __AUTH_CONST.__cfstring: 0x6d20
-  __AUTH_CONST.__objc_const: 0x10238
-  __AUTH_CONST.__objc_intobj: 0x1740
-  __AUTH_CONST.__objc_arrayobj: 0x168
+  __DATA_CONST.__objc_superrefs: 0x318
+  __DATA_CONST.__objc_arraydata: 0x250
+  __DATA_CONST.__got: 0xa48
+  __AUTH_CONST.__const: 0x1200
+  __AUTH_CONST.__cfstring: 0x70a0
+  __AUTH_CONST.__objc_const: 0x106e0
+  __AUTH_CONST.__objc_intobj: 0x1830
+  __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1e50
-  __DATA.__objc_ivar: 0xb64
+  __AUTH.__objc_data: 0x1ea0
+  __DATA.__objc_ivar: 0xbb8
   __DATA.__data: 0xea0
-  __DATA.__bss: 0x478
+  __DATA.__bss: 0x4b8
   __DATA_DIRTY.__objc_data: 0xd20
-  __DATA_DIRTY.__bss: 0xc0
+  __DATA_DIRTY.__bss: 0xb0
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /System/Library/PrivateFrameworks/UARPKit.framework/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4477
-  Symbols:   7338
+  Functions: 4607
+  Symbols:   7533
   CStrings:  0
 
Symbols:
+ +[HMMTRAsyncMutex logCategory]
+ +[HMMTRFeatures disableDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures disableFeatureLockDPSForTests]
+ +[HMMTRFeatures enableDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures enableFeatureLockDPSForTests]
+ +[HMMTRFeatures unsetDemoModeSuppressDPSForTests]
+ +[HMMTRFeatures unsetFeatureLockDPSForTests]
+ +[HMMTRMultiFabricDataStoreQuery v2FabricDataItemPreferenceComparator]
+ +[HMMTRProtocolMap mapTargetAirPurifierState:]
+ -[HMMTRAccessoryServer _deviceStorageDataSourceForCurrentNode]
+ -[HMMTRAccessoryServer _endPairingMode]
+ -[HMMTRAccessoryServer _enqueueResumeFinalizeAttempt]
+ -[HMMTRAccessoryServer _invalidateFinalizeRetry]
+ -[HMMTRAccessoryServer _persistThreadWEDInfoToStorage]
+ -[HMMTRAccessoryServer _readCharacteristicValueFromCacheAfterConfirmingBridgedAccessoryReachabilityWithCharacteristic:responseHandler:]
+ -[HMMTRAccessoryServer _resumeFinalizePairing]
+ -[HMMTRAccessoryServer _scheduleFinalizeRetry]
+ -[HMMTRAccessoryServer connectivityMonitorClusterFactory]
+ -[HMMTRAccessoryServer finalizeRetryAttempt]
+ -[HMMTRAccessoryServer finalizeRetryTimer]
+ -[HMMTRAccessoryServer generalCommissioningClusterFactory]
+ -[HMMTRAccessoryServer networkCommissioningClusterFactory]
+ -[HMMTRAccessoryServer pendingReenumerationCompletionHandlers]
+ -[HMMTRAccessoryServer pendingServiceReenumeration]
+ -[HMMTRAccessoryServer removeClusterIDForCharacteristic:endpointID:]
+ -[HMMTRAccessoryServer removeNode:withPrivilege:fromExistingAclEntries:]
+ -[HMMTRAccessoryServer resumeFinalizeForCommissionedAccessoryWithOnboardingURL:]
+ -[HMMTRAccessoryServer setConnectivityMonitorClusterFactory:]
+ -[HMMTRAccessoryServer setFinalizeRetryAttempt:]
+ -[HMMTRAccessoryServer setFinalizeRetryTimer:]
+ -[HMMTRAccessoryServer setGeneralCommissioningClusterFactory:]
+ -[HMMTRAccessoryServer setNetworkCommissioningClusterFactory:]
+ -[HMMTRAccessoryServer setPendingServiceReenumeration:]
+ -[HMMTRAccessoryServer(Diagnostics) supportsEnhancedMetricsForAccessory:]
+ -[HMMTRAccessoryServer(NetworkRepair) _addThreadNetwork:dataset:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _addWiFiNetworks:networks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _armFailSafeWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _commissioningCompleteWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _connectThreadNetwork:networkID:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _createGeneralCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _createThreadNetworkCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _createWiFiNetworkCommissioningCluster]
+ -[HMMTRAccessoryServer(NetworkRepair) _disarmFailSafeWithCluster:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _extractThreadExtendedPANIDFromNetworksAttribute:]
+ -[HMMTRAccessoryServer(NetworkRepair) _extractWiFiSSIDsFromNetworksAttribute:]
+ -[HMMTRAccessoryServer(NetworkRepair) _findAllNetworkCommissioningEndpoints]
+ -[HMMTRAccessoryServer(NetworkRepair) _findNetworkCommissioningEndpointForInterfaceType:]
+ -[HMMTRAccessoryServer(NetworkRepair) _handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _hasDualNetworkCommissioningClusters]
+ -[HMMTRAccessoryServer(NetworkRepair) _removeWiFiNetwork:ssid:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) _reorderWiFiNetworks:networks:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) hasDualNetworkCommissioningClusters]
+ -[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]
+ -[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]
+ -[HMMTRAccessoryServerBrowser _makeAccessoryServerFactory]
+ -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser discoveredAccessoryServersAsyncMutex]
+ -[HMMTRAccessoryServerBrowser fetchPreferredThreadCredentialsUsingFabricUUID:systemCommissionerFabric:withCompletion:]
+ -[HMMTRAccessoryServerBrowser hasPresentCommissionableNodeMatchingOnboardingURL:]
+ -[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser workQueueFactory]
+ -[HMMTRAccessoryServerFactory workQueueFactory]
+ -[HMMTRAsyncMutex .cxx_destruct]
+ -[HMMTRAsyncMutex initWithQueue:]
+ -[HMMTRAsyncMutex lockWithCompletion:]
+ -[HMMTRAsyncMutex locked]
+ -[HMMTRAsyncMutex pendingCompletions]
+ -[HMMTRAsyncMutex queue]
+ -[HMMTRAsyncMutex setLocked:]
+ -[HMMTRAsyncMutex unlock]
+ -[HMMTRControllerFactory workQueueFactory]
+ -[HMMTRControllerFactoryStorage initWithWorkQueueFactory:]
+ -[HMMTRControllerFactoryStorage workQueueFactory]
+ -[HMMTRDescriptorClusterManager workQueueFactory]
+ -[HMMTRExclusiveServerActionQueue workQueueFactory]
+ -[HMMTRFirmwareUpdateStatus workQueueFactory]
+ -[HMMTRSyncClusterThermostat readAttributePluginCurrentRelativeHumidityWithParams:]
+ -[HMMTRSyncClusterThermostat updatedValuePluginCurrentRelativeHumidityForAttributeReport:responseHandler:]
+ -[HMMTRSyncClusterWindowCovering _targetPositionDictionary:fallingBackToCurrentPositionLift:params:]
+ -[HMMTRSystemCommissionerControllerParams workQueueFactory]
+ -[HMMTRThreadRadioManager eMACAddressOfPairingAccessory]
+ -[HMMTRThreadRadioManager setEMACAddressOfPairingAccessory:]
+ -[HMMTRThreadRadioManager workQueueFactory]
+ GCC_except_table1058
+ GCC_except_table1062
+ GCC_except_table1064
+ GCC_except_table1186
+ GCC_except_table1246
+ GCC_except_table1292
+ GCC_except_table1300
+ GCC_except_table1351
+ GCC_except_table1359
+ GCC_except_table1396
+ GCC_except_table1434
+ GCC_except_table1461
+ GCC_except_table1658
+ GCC_except_table1699
+ GCC_except_table1851
+ GCC_except_table1852
+ GCC_except_table1876
+ GCC_except_table1877
+ GCC_except_table1878
+ GCC_except_table1879
+ GCC_except_table1880
+ GCC_except_table1883
+ GCC_except_table1886
+ GCC_except_table1887
+ GCC_except_table1888
+ GCC_except_table1889
+ GCC_except_table1890
+ GCC_except_table1891
+ GCC_except_table1892
+ GCC_except_table1903
+ GCC_except_table1905
+ GCC_except_table1906
+ GCC_except_table1907
+ GCC_except_table1915
+ GCC_except_table1920
+ GCC_except_table1923
+ GCC_except_table1925
+ GCC_except_table1927
+ GCC_except_table1930
+ GCC_except_table1997
+ GCC_except_table2003
+ GCC_except_table2041
+ GCC_except_table2124
+ GCC_except_table2242
+ GCC_except_table2244
+ GCC_except_table2275
+ GCC_except_table2284
+ GCC_except_table2286
+ GCC_except_table2335
+ GCC_except_table2372
+ GCC_except_table2396
+ GCC_except_table2462
+ GCC_except_table2751
+ GCC_except_table2753
+ GCC_except_table2755
+ GCC_except_table2759
+ GCC_except_table2820
+ GCC_except_table2861
+ GCC_except_table2908
+ GCC_except_table2910
+ GCC_except_table2941
+ GCC_except_table2942
+ GCC_except_table2965
+ GCC_except_table2966
+ GCC_except_table2967
+ GCC_except_table2968
+ GCC_except_table2969
+ GCC_except_table2970
+ GCC_except_table2971
+ GCC_except_table2972
+ GCC_except_table2982
+ GCC_except_table2984
+ GCC_except_table2996
+ GCC_except_table3015
+ GCC_except_table3031
+ GCC_except_table3037
+ GCC_except_table3050
+ GCC_except_table3053
+ GCC_except_table3057
+ GCC_except_table3072
+ GCC_except_table3075
+ GCC_except_table3079
+ GCC_except_table3081
+ GCC_except_table3111
+ GCC_except_table3120
+ GCC_except_table3125
+ GCC_except_table3137
+ GCC_except_table3189
+ GCC_except_table3190
+ GCC_except_table3586
+ GCC_except_table3611
+ GCC_except_table3612
+ GCC_except_table3613
+ GCC_except_table3617
+ GCC_except_table3625
+ GCC_except_table3641
+ GCC_except_table3656
+ GCC_except_table3725
+ GCC_except_table3733
+ GCC_except_table3735
+ GCC_except_table3742
+ GCC_except_table3743
+ GCC_except_table3785
+ GCC_except_table3789
+ GCC_except_table3823
+ GCC_except_table3826
+ GCC_except_table3834
+ GCC_except_table3856
+ GCC_except_table3860
+ GCC_except_table3899
+ GCC_except_table3901
+ GCC_except_table3903
+ GCC_except_table3920
+ GCC_except_table3922
+ GCC_except_table3940
+ GCC_except_table4064
+ GCC_except_table4082
+ GCC_except_table4105
+ GCC_except_table4109
+ GCC_except_table4124
+ GCC_except_table4125
+ GCC_except_table4126
+ GCC_except_table4132
+ GCC_except_table4139
+ GCC_except_table4144
+ GCC_except_table4199
+ GCC_except_table4221
+ GCC_except_table4267
+ GCC_except_table4272
+ GCC_except_table4275
+ GCC_except_table4359
+ GCC_except_table4360
+ GCC_except_table4416
+ GCC_except_table4419
+ GCC_except_table4481
+ GCC_except_table4543
+ GCC_except_table4547
+ GCC_except_table4551
+ GCC_except_table4554
+ GCC_except_table4587
+ GCC_except_table572
+ GCC_except_table576
+ GCC_except_table578
+ GCC_except_table580
+ GCC_except_table753
+ GCC_except_table754
+ GCC_except_table811
+ GCC_except_table812
+ GCC_except_table813
+ GCC_except_table886
+ GCC_except_table928
+ GCC_except_table978
+ GCC_except_table982
+ GCC_except_table984
+ GCC_except_table986
+ GCC_except_table988
+ GCC_except_table992
+ GCC_except_table995
+ _AppleExtensionNeedsAdditionalConfigurationAttribute
+ _HAPWorkQueueFactoryOrDefault
+ _HMErrorDomain
+ _HMMTRAccessoryServerDeferredMatterCommissioningErrorKey
+ _HMMTRAccessoryServerDeferredMatterCommissioningNodeIDKey
+ _HMMTRAccessoryServerDidBeginDeferredMatterCommissioningNotification
+ _HMMTRAccessoryServerDidFailDeferredMatterCommissioningNotification
+ _HMMTRIsSecondPartyProduct
+ _OBJC_CLASS_$_HMHomeManager
+ _OBJC_CLASS_$_HMMTRAsyncMutex
+ _OBJC_CLASS_$_MTRClusterAppleAccessoryConnectivityMonitor
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterAddOrUpdateThreadNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterAddOrUpdateWiFiNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterConnectNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterRemoveNetworkParams
+ _OBJC_CLASS_$_MTRNetworkCommissioningClusterReorderNetworkParams
+ _OBJC_IVAR_$_HMMTRAccessoryServer._connectivityMonitorClusterFactory
+ _OBJC_IVAR_$_HMMTRAccessoryServer._finalizeRetryAttempt
+ _OBJC_IVAR_$_HMMTRAccessoryServer._finalizeRetryTimer
+ _OBJC_IVAR_$_HMMTRAccessoryServer._generalCommissioningClusterFactory
+ _OBJC_IVAR_$_HMMTRAccessoryServer._networkCommissioningClusterFactory
+ _OBJC_IVAR_$_HMMTRAccessoryServer._pendingReenumerationCompletionHandlers
+ _OBJC_IVAR_$_HMMTRAccessoryServer._pendingServiceReenumeration
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._discoveredAccessoryServersAsyncMutex
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._workQueueFactory
+ _OBJC_IVAR_$_HMMTRAccessoryServerFactory._workQueueFactory
+ _OBJC_IVAR_$_HMMTRAsyncMutex._locked
+ _OBJC_IVAR_$_HMMTRAsyncMutex._pendingCompletions
+ _OBJC_IVAR_$_HMMTRAsyncMutex._queue
+ _OBJC_IVAR_$_HMMTRControllerFactory._workQueueFactory
+ _OBJC_IVAR_$_HMMTRControllerFactoryStorage._workQueueFactory
+ _OBJC_IVAR_$_HMMTRDescriptorClusterManager._workQueueFactory
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._workQueueFactory
+ _OBJC_IVAR_$_HMMTRFirmwareUpdateStatus._workQueueFactory
+ _OBJC_IVAR_$_HMMTRSystemCommissionerControllerParams._workQueueFactory
+ _OBJC_IVAR_$_HMMTRThreadRadioManager._eMACAddressOfPairingAccessory
+ _OBJC_IVAR_$_HMMTRThreadRadioManager._workQueueFactory
+ _OBJC_METACLASS_$_HMMTRAsyncMutex
+ __OBJC_$_CLASS_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_METHODS_HMMTRAccessoryServer(HAPAccessory|RemoteAccess|Diagnostics|DiagnosticsInternal|SystemCommissionerPairing|NetworkRepair)
+ __OBJC_$_INSTANCE_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRAsyncMutex
+ __OBJC_$_PROP_LIST_HMMTRAsyncMutex
+ __OBJC_CLASS_RO_$_HMMTRAsyncMutex
+ __OBJC_METACLASS_RO_$_HMMTRAsyncMutex
+ ___118-[HMMTRAccessoryServerBrowser fetchPreferredThreadCredentialsUsingFabricUUID:systemCommissionerFabric:withCompletion:]_block_invoke
+ ___120-[HMMTRAccessoryServer(NetworkRepair) _handleAtCapacityWiFiRepair:deviceSSIDs:preferredNetworks:maxNetworks:completion:]_block_invoke
+ ___139-[HMMTRAccessoryServer scheduleOrExecuteOTAProviderAnnouncement:initiatorType:immediateAnnouncement:endpoint:delayCounter:isUserTriggered:]_block_invoke_2
+ ___177-[HMMTRAccessoryServerBrowser setOperationalFabricData:operationalCertIssuer:storageDataSource:allTargetFabricUUIDs:entityIdentifier:accessoryServerNodeIDs:forTargetFabricUUID:]_block_invoke_2
+ ___25-[HMMTRAsyncMutex unlock]_block_invoke
+ ___30+[HMMTRAsyncMutex logCategory]_block_invoke
+ ___38-[HMMTRAsyncMutex lockWithCompletion:]_block_invoke
+ ___39-[HMMTRAccessoryServer _endPairingMode]_block_invoke
+ ___40-[HMMTRAccessoryServer _finalizePairing]_block_invoke_3
+ ___46-[HMMTRAccessoryServer _resumeFinalizePairing]_block_invoke
+ ___49-[HMMTRAccessoryServer initWithKeystore:browser:]_block_invoke_2
+ ___49-[HMMTRAccessoryServer initWithKeystore:browser:]_block_invoke_3
+ ___53-[HMMTRAccessoryServer _enqueueResumeFinalizeAttempt]_block_invoke
+ ___54-[HMMTRAccessoryServer _persistThreadWEDInfoToStorage]_block_invoke
+ ___70+[HMMTRMultiFabricDataStoreQuery v2FabricDataItemPreferenceComparator]_block_invoke
+ ___73-[HMMTRAccessoryServer(Diagnostics) supportsEnhancedMetricsForAccessory:]_block_invoke
+ ___74-[HMMTRAccessoryServer(NetworkRepair) _armFailSafeWithCluster:completion:]_block_invoke
+ ___74-[HMMTRAccessoryServer(NetworkRepair) _removeWiFiNetwork:ssid:completion:]_block_invoke
+ ___76-[HMMTRAccessoryServer(NetworkRepair) _addThreadNetwork:dataset:completion:]_block_invoke
+ ___76-[HMMTRAccessoryServer(NetworkRepair) _addWiFiNetworks:networks:completion:]_block_invoke
+ ___77-[HMMTRAccessoryServer(NetworkRepair) _disarmFailSafeWithCluster:completion:]_block_invoke
+ ___80-[HMMTRAccessoryServer resumeFinalizeForCommissionedAccessoryWithOnboardingURL:]_block_invoke
+ ___80-[HMMTRAccessoryServer(NetworkRepair) _reorderWiFiNetworks:networks:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) _connectThreadNetwork:networkID:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke
+ ___82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke_2
+ ___82-[HMMTRAccessoryServer(NetworkRepair) repairWiFiNetworkWithCompletion:completion:]_block_invoke_3
+ ___84-[HMMTRAccessoryServer(NetworkRepair) _commissioningCompleteWithCluster:completion:]_block_invoke
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_2
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_3
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_4
+ ___84-[HMMTRAccessoryServer(NetworkRepair) repairThreadNetworkWithCompletion:completion:]_block_invoke_5
+ ___95-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ ___96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ ___96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke_2
+ ___block_descriptor_104_e8_32s40s48s56s64s72bs80bs88w_e17_v16?0"NSError"8lw88l8s72l8s32l8s40l8s48l8s56l8s80l8s64l8
+ ___block_descriptor_32_e111_q24?0"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>"8"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>"16l
+ ___block_descriptor_32_e65_"MTRClusterNetworkCommissioning"24?0"HMMTRAccessoryServer"8Q16l
+ ___block_descriptor_32_e66_"MTRBaseClusterGeneralCommissioning"16?0"HMMTRAccessoryServer"8l
+ ___block_descriptor_32_e88_"MTRClusterAppleAccessoryConnectivityMonitor"24?0"HMMTRAccessoryServer"8"NSNumber"16l
+ ___block_descriptor_40_e8_32bs_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16ls32l8
+ ___block_descriptor_48_e8_32bs40w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16lw40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e80_v24?0"MTRNetworkCommissioningClusterConnectNetworkResponseParams"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e87_v24?0"MTRGeneralCommissioningClusterCommissioningCompleteResponseParams"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32bs40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_56_e8_32bs40r48w_e5_v8?0lw48l8r40l8s32l8
+ ___block_descriptor_56_e8_32s40bs48w_e17_v16?0"NSError"8lw48l8s40l8s32l8
+ ___block_descriptor_57_e8_32s40s48bs_e46_v24?0"HAPThreadNetworkMetadata"8"NSError"16ls32l8s48l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e17_v16?0"NSError"8lw56l8s48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48r56r64w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16lw64l8r48l8r56l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e17_v16?0"NSError"8lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48r56r64r72w_e79_v24?0"MTRNetworkCommissioningClusterNetworkConfigResponseParams"8"NSError"16lw72l8r48l8r56l8s32l8r64l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs72w_e17_v16?0"NSError"8lw72l8s64l8s32l8s40l8s48l8s56l8
+ ___suppressDpsForDemoMode_block_invoke
+ __dispatch_main_q
+ _defaultFeatures._hmf_once_t9
+ _defaultFeatures._hmf_once_v10
+ _isFeatureLockDPSEnabled
+ _isFeatureLockDPSEnabledForTests
+ _isFeatureNetworkLinkManagementEnabled
+ _logCategory._hmf_once_t135
+ _logCategory._hmf_once_t136
+ _logCategory._hmf_once_t1419
+ _logCategory._hmf_once_t180
+ _logCategory._hmf_once_t210
+ _logCategory._hmf_once_t24
+ _logCategory._hmf_once_t32
+ _logCategory._hmf_once_t346
+ _logCategory._hmf_once_t492
+ _logCategory._hmf_once_t50
+ _logCategory._hmf_once_t786
+ _logCategory._hmf_once_v136
+ _logCategory._hmf_once_v137
+ _logCategory._hmf_once_v1420
+ _logCategory._hmf_once_v181
+ _logCategory._hmf_once_v211
+ _logCategory._hmf_once_v25
+ _logCategory._hmf_once_v33
+ _logCategory._hmf_once_v347
+ _logCategory._hmf_once_v493
+ _logCategory._hmf_once_v51
+ _logCategory._hmf_once_v787
+ _secondPartyProducts
+ _suppressDpsForDemoMode
+ _suppressDpsForDemoMode.onceToken
+ _suppressDpsForDemoMode.suppressed
+ _suppressDpsForDemoModeForTests
- +[HMMTRProtocolMap mapTargetAirPuriferState:]
- -[HMMTRAccessoryServer _readCharacteristicValueFromCacheAfterConfirmingBridgedAccessroyReachabilityWithCharacteristic:responseHandler:]
- -[HMMTRAccessoryServer removeNode:withPrivilge:fromExistingAclEntries:]
- -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]
- -[HMMTRProtocolMap isRequiresOptionalMatterAttributeForCharacteristic:]
- GCC_except_table1041
- GCC_except_table1045
- GCC_except_table1047
- GCC_except_table1169
- GCC_except_table1229
- GCC_except_table1275
- GCC_except_table1283
- GCC_except_table1332
- GCC_except_table1340
- GCC_except_table1377
- GCC_except_table1414
- GCC_except_table1441
- GCC_except_table1635
- GCC_except_table1676
- GCC_except_table1828
- GCC_except_table1829
- GCC_except_table1830
- GCC_except_table1833
- GCC_except_table1854
- GCC_except_table1855
- GCC_except_table1857
- GCC_except_table1860
- GCC_except_table1863
- GCC_except_table1864
- GCC_except_table1865
- GCC_except_table1866
- GCC_except_table1867
- GCC_except_table1868
- GCC_except_table1869
- GCC_except_table1934
- GCC_except_table1972
- GCC_except_table2055
- GCC_except_table2168
- GCC_except_table2170
- GCC_except_table2200
- GCC_except_table2208
- GCC_except_table2210
- GCC_except_table2259
- GCC_except_table2296
- GCC_except_table2320
- GCC_except_table2385
- GCC_except_table2662
- GCC_except_table2664
- GCC_except_table2666
- GCC_except_table2670
- GCC_except_table2728
- GCC_except_table2769
- GCC_except_table2815
- GCC_except_table2817
- GCC_except_table2848
- GCC_except_table2849
- GCC_except_table2850
- GCC_except_table2872
- GCC_except_table2873
- GCC_except_table2874
- GCC_except_table2875
- GCC_except_table2876
- GCC_except_table2877
- GCC_except_table2878
- GCC_except_table2879
- GCC_except_table2889
- GCC_except_table2891
- GCC_except_table2902
- GCC_except_table2921
- GCC_except_table2937
- GCC_except_table2956
- GCC_except_table2959
- GCC_except_table2963
- GCC_except_table2978
- GCC_except_table2981
- GCC_except_table2985
- GCC_except_table2987
- GCC_except_table3014
- GCC_except_table3023
- GCC_except_table3028
- GCC_except_table3040
- GCC_except_table3091
- GCC_except_table3092
- GCC_except_table3475
- GCC_except_table3500
- GCC_except_table3501
- GCC_except_table3502
- GCC_except_table3506
- GCC_except_table3511
- GCC_except_table3514
- GCC_except_table3530
- GCC_except_table3545
- GCC_except_table3614
- GCC_except_table3624
- GCC_except_table3631
- GCC_except_table3632
- GCC_except_table3661
- GCC_except_table3668
- GCC_except_table3700
- GCC_except_table3703
- GCC_except_table3711
- GCC_except_table3731
- GCC_except_table3734
- GCC_except_table3772
- GCC_except_table3774
- GCC_except_table3793
- GCC_except_table3795
- GCC_except_table3813
- GCC_except_table3890
- GCC_except_table3937
- GCC_except_table3955
- GCC_except_table3978
- GCC_except_table3982
- GCC_except_table3997
- GCC_except_table3998
- GCC_except_table3999
- GCC_except_table4005
- GCC_except_table4012
- GCC_except_table4072
- GCC_except_table4094
- GCC_except_table4137
- GCC_except_table4142
- GCC_except_table4145
- GCC_except_table4229
- GCC_except_table4230
- GCC_except_table4286
- GCC_except_table4289
- GCC_except_table4351
- GCC_except_table4413
- GCC_except_table4417
- GCC_except_table4421
- GCC_except_table4424
- GCC_except_table4457
- GCC_except_table571
- GCC_except_table575
- GCC_except_table577
- GCC_except_table579
- GCC_except_table739
- GCC_except_table740
- GCC_except_table797
- GCC_except_table798
- GCC_except_table799
- GCC_except_table872
- GCC_except_table914
- GCC_except_table963
- GCC_except_table967
- GCC_except_table969
- GCC_except_table971
- GCC_except_table973
- GCC_except_table977
- __OBJC_$_INSTANCE_METHODS_HMMTRAccessoryServer(HAPAccessory|RemoteAccess|Diagnostics|DiagnosticsInternal|SystemCommissionerPairing)
- __OBJC_$_PROP_LIST_HMMTRAccessoryServer
- ___84-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- _defaultFeatures._hmf_once_t2
- _defaultFeatures._hmf_once_v3
- _dispatch_queue_create_with_target$V2
- _logCategory._hmf_once_t119
- _logCategory._hmf_once_t129
- _logCategory._hmf_once_t1361
- _logCategory._hmf_once_t178
- _logCategory._hmf_once_t18
- _logCategory._hmf_once_t208
- _logCategory._hmf_once_t29
- _logCategory._hmf_once_t345
- _logCategory._hmf_once_t491
- _logCategory._hmf_once_t749
- _logCategory._hmf_once_v120
- _logCategory._hmf_once_v130
- _logCategory._hmf_once_v1362
- _logCategory._hmf_once_v179
- _logCategory._hmf_once_v19
- _logCategory._hmf_once_v209
- _logCategory._hmf_once_v30
- _logCategory._hmf_once_v346
- _logCategory._hmf_once_v492
- _logCategory._hmf_once_v750
```
