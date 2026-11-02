## CoreHAP

> `/System/Library/PrivateFrameworks/CoreHAP.framework/CoreHAP`

```diff

-1493.1.5.1.1
-  __TEXT.__text: 0x2add7c
-  __TEXT.__objc_methlist: 0x18cc0
-  __TEXT.__const: 0x1240
+1520.2.7.1.3
+  __TEXT.__text: 0x303ee8
+  __TEXT.__objc_methlist: 0x1c9d8
+  __TEXT.__const: 0x1818
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__constg_swiftt: 0x960
-  __TEXT.__swift5_typeref: 0x3e4
-  __TEXT.__swift5_builtin: 0x50
-  __TEXT.__swift5_reflstr: 0x474
-  __TEXT.__swift5_fieldmd: 0x3f0
-  __TEXT.__swift5_assocty: 0xc0
-  __TEXT.__swift5_proto: 0x50
-  __TEXT.__swift5_types: 0x30
-  __TEXT.__cstring: 0x146d5
-  __TEXT.__oslogstring: 0x4514e
-  __TEXT.__swift5_capture: 0x288
-  __TEXT.__gcc_except_tab: 0x5eb8
-  __TEXT.__unwind_info: 0x77d0
-  __TEXT.__eh_frame: 0x1080
+  __TEXT.__constg_swiftt: 0xc20
+  __TEXT.__swift5_typeref: 0x533
+  __TEXT.__swift5_builtin: 0xdc
+  __TEXT.__swift5_reflstr: 0x851
+  __TEXT.__swift5_fieldmd: 0x6a4
+  __TEXT.__swift5_assocty: 0x138
+  __TEXT.__swift5_proto: 0x78
+  __TEXT.__swift5_types: 0x5c
+  __TEXT.__cstring: 0x17714
+  __TEXT.__oslogstring: 0x4b2bb
+  __TEXT.__swift5_protos: 0x4
+  __TEXT.__swift5_capture: 0x28c
+  __TEXT.__gcc_except_tab: 0x6f8c
+  __TEXT.__unwind_info: 0x87f0
+  __TEXT.__eh_frame: 0x1078
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x59e8
-  __DATA_CONST.__objc_classlist: 0xc20
+  __DATA_CONST.__const: 0x6300
+  __DATA_CONST.__objc_classlist: 0xda0
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x3b0
+  __DATA_CONST.__objc_protolist: 0x3f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8358
-  __DATA_CONST.__objc_protorefs: 0x100
-  __DATA_CONST.__objc_superrefs: 0xa68
+  __DATA_CONST.__objc_selrefs: 0x98f8
+  __DATA_CONST.__objc_protorefs: 0x110
+  __DATA_CONST.__objc_superrefs: 0xbc0
   __DATA_CONST.__objc_arraydata: 0x200
-  __DATA_CONST.__got: 0x1030
-  __AUTH_CONST.__const: 0x14b8
-  __AUTH_CONST.__cfstring: 0x10080
-  __AUTH_CONST.__objc_const: 0x2b2c0
-  __AUTH_CONST.__objc_intobj: 0x738
+  __DATA_CONST.__got: 0x11c8
+  __AUTH_CONST.__const: 0x1738
+  __AUTH_CONST.__cfstring: 0x117a0
+  __AUTH_CONST.__objc_const: 0x32290
+  __AUTH_CONST.__weak_auth_got: 0x10
+  __AUTH_CONST.__objc_intobj: 0x750
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x1340
-  __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x73b8
-  __AUTH.__data: 0xb0
+  __AUTH_CONST.__auth_got: 0x1448
+  __AUTH_CONST.__auth_ptr: 0x258
+  __AUTH.__objc_data: 0x84c0
+  __AUTH.__data: 0x130
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x28
-  __DATA.__objc_ivar: 0x1924
-  __DATA.__data: 0x2da2
+  __DATA.__objc_ivar: 0x1e08
+  __DATA.__data: 0x31b8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xee0
-  __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0xfc8
+  __DATA.__bss: 0x1300
+  __DATA.__common: 0x90
+  __DATA_DIRTY.__objc_data: 0x1108
   __DATA_DIRTY.__data: 0x48
-  __DATA_DIRTY.__bss: 0xa8
+  __DATA_DIRTY.__bss: 0xf0
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9860
-  Symbols:   16522
+  Functions: 11431
+  Symbols:   18803
   CStrings:  0
 
Symbols:
+ +[HAP2AccessoryDeviceIPAddress accessoryDeviceIPAddressWithSerializedData:]
+ +[HAP2AccessoryServerCoordinator(Test) coordinatorForUnitTestsWithBrowser:operationQueue:delegate:]
+ +[HAP2AccessoryServerDiscoveryHAPAccessoryInfo accessoryInfoWithDeviceID:rawDiscoveryInfo:]
+ +[HAP2AccessoryServerIPCacheData dataWithDictionary:deviceID:]
+ +[HAP2AccessoryServerIPCacheData logCategory]
+ +[HAP2SessionKeepAliveConfiguration computeSelectedConfigurationForTransportType:isSleepyEndDevice:supportedMinInterval:supportedMaxInterval:supportedMinRange:]
+ +[HAP2ThreadNetworkUtil _eventQueue]
+ +[HAP2ThreadNetworkUtil _fetchMeshLocalPrefixFromXPC]
+ +[HAP2ThreadNetworkUtil _setSharedThreadClient:]
+ +[HAP2ThreadNetworkUtil forceRefreshMeshLocalPrefix]
+ +[HAP2ThreadNetworkUtil isNetworkLinkManagementEnabled]
+ +[HAP2ThreadNetworkUtil setupEventSubscriptions]
+ +[HAPAVCStreamingControlCommandWrapper parsedFromData:error:]
+ +[HAPAVCStreamingControlRequest parsedFromData:error:]
+ +[HAPAVCStreamingControlResponse parsedFromData:error:]
+ +[HAPAVCStreamingControlStatusWrapper parsedFromData:error:]
+ +[HAPAVCViewerRegistrationOperationWrapper parsedFromData:error:]
+ +[HAPBluetoothMetrics parsedFromData:error:]
+ +[HAPBootReasonsMetrics parsedFromData:error:]
+ +[HAPCHMMetrics parsedFromData:error:]
+ +[HAPConnectionHealthMonitor parsedFromData:error:]
+ +[HAPContributingSensor parsedFromData:error:]
+ +[HAPDefaultWorkQueueFactory sharedFactory]
+ +[HAPErrorCountersMetrics parsedFromData:error:]
+ +[HAPErrorCountersMetricsEntry parsedFromData:error:]
+ +[HAPHKSV3UploadLatencyMetrics parsedFromData:error:]
+ +[HAPMetricEventBluetoothVersionTypeWrapper parsedFromData:error:]
+ +[HAPMetricEventPowerSourcesBitmaskWrapper parsedFromData:error:]
+ +[HAPMetricEventPowerSourcesEnumWrapper parsedFromData:error:]
+ +[HAPMetricEventThreadFirstRestartConnectivityStateWrapper parsedFromData:error:]
+ +[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper parsedFromData:error:]
+ +[HAPMetricEventWiFiVersionTypeWrapper parsedFromData:error:]
+ +[HAPPowerMetrics parsedFromData:error:]
+ +[HAPSaturationMetrics parsedFromData:error:]
+ +[HAPSensorList parsedFromData:error:]
+ +[HAPSessionKeepAliveTransportTypeWrapper parsedFromData:error:]
+ +[HAPStabilityMetrics parsedFromData:error:]
+ +[HAPStabilityMetricsBootReasonTypeWrapper parsedFromData:error:]
+ +[HAPStabilityMetricsHardwareFaultTypeWrapper parsedFromData:error:]
+ +[HAPTLVPreferredWiFiEntry parsedFromData:error:]
+ +[HAPTLVPreferredWiFiList parsedFromData:error:]
+ +[HAPTLVSelectedSessionKeepAliveConfigurationEntry parsedFromData:error:]
+ +[HAPTLVSelectedSessionKeepAliveConfigurationList parsedFromData:error:]
+ +[HAPTLVSupportedSessionKeepAliveConfigurationEntry parsedFromData:error:]
+ +[HAPTLVSupportedSessionKeepAliveConfigurationList parsedFromData:error:]
+ +[HAPThermalMetrics parsedFromData:error:]
+ +[HAPWiFiMetrics parsedFromData:error:]
+ -[HAP2AccessoryAddressLists .cxx_destruct]
+ -[HAP2AccessoryAddressLists cachedPrimary]
+ -[HAP2AccessoryAddressLists cachedSecondary]
+ -[HAP2AccessoryAddressLists description]
+ -[HAP2AccessoryAddressLists initWithPrimary:secondary:]
+ -[HAP2AccessoryAddressLists initWithPrimary:secondary:cachedPrimary:cachedSecondary:]
+ -[HAP2AccessoryAddressLists isEmpty]
+ -[HAP2AccessoryAddressLists primary]
+ -[HAP2AccessoryAddressLists secondary]
+ -[HAP2AccessoryAddressLists setCachedPrimary:]
+ -[HAP2AccessoryAddressLists setCachedSecondary:]
+ -[HAP2AccessoryAddressLists setPrimary:]
+ -[HAP2AccessoryAddressLists setSecondary:]
+ -[HAP2AccessoryAddressResolverPipeline .cxx_destruct]
+ -[HAP2AccessoryAddressResolverPipeline _acquireDNSContextOwnership]
+ -[HAP2AccessoryAddressResolverPipeline _clearAllAddresses]
+ -[HAP2AccessoryAddressResolverPipeline _coapAddressFromGAIResult:outAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _handleGetaddrinfoEvent:error:]
+ -[HAP2AccessoryAddressResolverPipeline _handleGetaddrinfoResults:count:]
+ -[HAP2AccessoryAddressResolverPipeline _handleResolveCallbackWithError:hostname:port:]
+ -[HAP2AccessoryAddressResolverPipeline _recordAddedAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _recordRemovedAddress:]
+ -[HAP2AccessoryAddressResolverPipeline _releaseDNSContextOwnership]
+ -[HAP2AccessoryAddressResolverPipeline _restampWorkingSetWithResolvedPort]
+ -[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]
+ -[HAP2AccessoryAddressResolverPipeline cancel]
+ -[HAP2AccessoryAddressResolverPipeline initWithQueue:updateHandler:errorHandler:]
+ -[HAP2AccessoryAddressResolverPipeline publishedAddresses]
+ -[HAP2AccessoryAddressResolverPipeline startWithServiceName:serviceType:serviceDomain:]
+ -[HAP2AccessoryDNSResolver .cxx_destruct]
+ -[HAP2AccessoryDNSResolver _applyCachedIP:transportType:notifySubscriber:seedAgingClock:]
+ -[HAP2AccessoryDNSResolver _handlePipelineError:]
+ -[HAP2AccessoryDNSResolver _handlePipelineUpdate:]
+ -[HAP2AccessoryDNSResolver _restartPipelineOnQueue]
+ -[HAP2AccessoryDNSResolver _seedCachedIP:transportType:]
+ -[HAP2AccessoryDNSResolver _startPipelineOnQueue]
+ -[HAP2AccessoryDNSResolver _tearDownPipeline]
+ -[HAP2AccessoryDNSResolver _test_setBecameEmptyAt:]
+ -[HAP2AccessoryDNSResolver attachCacheSubscriber:]
+ -[HAP2AccessoryDNSResolver attachDelegate:]
+ -[HAP2AccessoryDNSResolver becameEmptyAt]
+ -[HAP2AccessoryDNSResolver cachedIPDidUpdate:transportType:]
+ -[HAP2AccessoryDNSResolver currentAddresses]
+ -[HAP2AccessoryDNSResolver dealloc]
+ -[HAP2AccessoryDNSResolver deferAgingClockIfRunning]
+ -[HAP2AccessoryDNSResolver detachCacheSubscriber:]
+ -[HAP2AccessoryDNSResolver detachDelegate:]
+ -[HAP2AccessoryDNSResolver deviceID]
+ -[HAP2AccessoryDNSResolver initWithDeviceID:serviceName:managerQueue:pipelineFactory:]
+ -[HAP2AccessoryDNSResolver performHealthCheck]
+ -[HAP2AccessoryDNSResolver serviceName]
+ -[HAP2AccessoryDNSResolver startPipeline]
+ -[HAP2AccessoryDNSResolver stopPipeline]
+ -[HAP2AccessoryDNSResolver updateServiceName:]
+ -[HAP2AccessoryDeviceIPAddress _classifyTransportType:]
+ -[HAP2AccessoryDeviceIPAddress copyWithZone:]
+ -[HAP2AccessoryDeviceIPAddress debugDescription]
+ -[HAP2AccessoryDeviceIPAddress hash]
+ -[HAP2AccessoryDeviceIPAddress isEqual:]
+ -[HAP2AccessoryDeviceIPAddress isIPv6]
+ -[HAP2AccessoryDeviceIPAddress serializedData]
+ -[HAP2AccessoryDeviceIPAddress transportType]
+ -[HAP2AccessoryServer _attachResolverAndForwardToTransport:]
+ -[HAP2AccessoryServer _controllerUnchecked]
+ -[HAP2AccessoryServer _runLostDiscoveryAdvertisementSideEffectsWithWillSleep:]
+ -[HAP2AccessoryServer _runResolverReactiveWorkWithWas:now:connectionState:]
+ -[HAP2AccessoryServer _setHasDiscoveryAdvertisementLockOnly:]
+ -[HAP2AccessoryServer _setHasThreadAdvertisement:]
+ -[HAP2AccessoryServer _setHasWiFiAdvertisement:]
+ -[HAP2AccessoryServer dnsResolver]
+ -[HAP2AccessoryServer hasSeededSinceResolverAttach]
+ -[HAP2AccessoryServer hasThreadAdvertisement]
+ -[HAP2AccessoryServer hasWiFiAdvertisement]
+ -[HAP2AccessoryServer lastObservedHasAdvertisement]
+ -[HAP2AccessoryServer setDnsResolver:]
+ -[HAP2AccessoryServer setHasSeededSinceResolverAttach:]
+ -[HAP2AccessoryServer setHasThreadAdvertisement:]
+ -[HAP2AccessoryServer setHasWiFiAdvertisement:]
+ -[HAP2AccessoryServer setKeepAliveListener:]
+ -[HAP2AccessoryServer setLastObservedHasAdvertisement:]
+ -[HAP2AccessoryServer(Paired) closeSessionWithCompletion:]
+ -[HAP2AccessoryServer(Paired) configureKeepAliveListener:]
+ -[HAP2AccessoryServer(Paired) currentResolverSnapshot]
+ -[HAP2AccessoryServer(Paired) didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServer(Paired) didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServer(Paired) didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:resolver:]
+ -[HAP2AccessoryServer(Paired) pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServer(Paired) pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]
+ -[HAP2AccessoryServer(Paired) restartKeepAliveListener]
+ -[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]
+ -[HAP2AccessoryServer(PairedInternal) _handleProbeCompletion:forKeepAliveTransport:]
+ -[HAP2AccessoryServer(PairedInternal) _haveAllTransportsHitFailureThreshold]
+ -[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]
+ -[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]
+ -[HAP2AccessoryServer(Test) _test_becomePaired]
+ -[HAP2AccessoryServer(Test) _test_hasDiscoveryAdvertisement]
+ -[HAP2AccessoryServer(Test) _test_hasSeededSinceResolverAttach]
+ -[HAP2AccessoryServer(Test) _test_isInternallyPaired]
+ -[HAP2AccessoryServer(Test) _test_lastObservedHasAdvertisement]
+ -[HAP2AccessoryServer(Test) _test_reactiveWorkRecorderBlock]
+ -[HAP2AccessoryServer(Test) _test_setConnectionStateUnreachable]
+ -[HAP2AccessoryServer(Test) _test_setHasSeededSinceResolverAttach:]
+ -[HAP2AccessoryServer(Test) _test_setInternallyPaired:]
+ -[HAP2AccessoryServer(Test) set_test_reactiveWorkRecorderBlock:]
+ -[HAP2AccessoryServer(Unpaired) localPairingIdentityForPairingDriver:error:]
+ -[HAP2AccessoryServer(Unpaired) pairingDriver:saveRemoteECDSAPairingKey:forAccessoryIdentifier:error:]
+ -[HAP2AccessoryServer(Unpaired) pairingDriver:saveRemotePairingIdentity:error:]
+ -[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]
+ -[HAP2AccessoryServerBrowser _buildActiveDeviceIDsSet]
+ -[HAP2AccessoryServerBrowser _cancelPTRRevalidationWindow]
+ -[HAP2AccessoryServerBrowser _fireRevalidationSweep]
+ -[HAP2AccessoryServerBrowser _initializeFromCachedRecord:deviceID:]
+ -[HAP2AccessoryServerBrowser _performAuditPass]
+ -[HAP2AccessoryServerBrowser _reinitializeFromCachedRecordsAfterCoordinatorsStarted]
+ -[HAP2AccessoryServerBrowser _restoreCachedAccessoryServersIfNeeded]
+ -[HAP2AccessoryServerBrowser attachSelfAsCacheSubscriberOnResolver:]
+ -[HAP2AccessoryServerBrowser auditScheduler]
+ -[HAP2AccessoryServerBrowser cachedIPDidUpdate:transportType:forDeviceID:]
+ -[HAP2AccessoryServerBrowser currentPTRs]
+ -[HAP2AccessoryServerBrowser dealloc]
+ -[HAP2AccessoryServerBrowser existingPTRs]
+ -[HAP2AccessoryServerBrowser hasCurrentPTRForDeviceID:]
+ -[HAP2AccessoryServerBrowser hasDiscoveryAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser hasThreadAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser hasWiFiAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser ipCache]
+ -[HAP2AccessoryServerBrowser isInitialCacheRestored]
+ -[HAP2AccessoryServerBrowser localPairingIdentityForDeviceID:error:]
+ -[HAP2AccessoryServerBrowser noteBonjourAdvertisementUpdatedForDeviceID:rawDiscoveryInfo:]
+ -[HAP2AccessoryServerBrowser noteBrowsedPTRAddForDeviceID:serviceName:]
+ -[HAP2AccessoryServerBrowser noteBrowsedPTRRemoveForDeviceID:]
+ -[HAP2AccessoryServerBrowser noteResolverReapedForDeviceID:]
+ -[HAP2AccessoryServerBrowser pendingRevalidationPTRs]
+ -[HAP2AccessoryServerBrowser resolverRegistry]
+ -[HAP2AccessoryServerBrowser revalidationTimer]
+ -[HAP2AccessoryServerBrowser setAuditScheduler:]
+ -[HAP2AccessoryServerBrowser setIPCache:]
+ -[HAP2AccessoryServerBrowser setIpCache:]
+ -[HAP2AccessoryServerBrowser setIsInitialCacheRestored:]
+ -[HAP2AccessoryServerBrowser setPendingRevalidationPTRs:]
+ -[HAP2AccessoryServerBrowser setResolverRegistry:]
+ -[HAP2AccessoryServerBrowser setRevalidationTimer:]
+ -[HAP2AccessoryServerBrowser(Test) _test_auditScheduler]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasDiscoveryAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasThreadAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_hasWiFiAdvertisementForAccessoryWithID:]
+ -[HAP2AccessoryServerBrowser(Test) _test_performAuditPass]
+ -[HAP2AccessoryServerBrowser(Test) _test_restoreCachedAccessoryServersIfNeeded]
+ -[HAP2AccessoryServerBrowser(Test) _test_setLivePairedServers:]
+ -[HAP2AccessoryServerBrowser(Test) _test_setResolverRegistry:]
+ -[HAP2AccessoryServerController _announceReestablishedSessionIfNeeded]
+ -[HAP2AccessoryServerController applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerController checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerController closeSessionWithCompletion:]
+ -[HAP2AccessoryServerController forceSessionExpired]
+ -[HAP2AccessoryServerController hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerController isReadingAttributeDatabase]
+ -[HAP2AccessoryServerController localPairingIdentityForSecureTransport:error:]
+ -[HAP2AccessoryServerController readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerController secureTransport:didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServerController secureTransport:didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServerController secureTransport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerController secureTransport:ecdsaLongTermPublicKeyForPeerWithIdentifier:error:]
+ -[HAP2AccessoryServerController secureTransport:localPairingIdentityForECDSAKeyPairSetupSession:error:]
+ -[HAP2AccessoryServerController secureTransport:pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServerController secureTransport:pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServerController secureTransport:remotePairingIdentityForDeviceID:error:]
+ -[HAP2AccessoryServerController secureTransportCurrentResolverSnapshot:]
+ -[HAP2AccessoryServerController sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerController setUnitTest_useHH2:]
+ -[HAP2AccessoryServerCoordinator _didDiscoverAccessory:fromMDNSEvent:completion:]
+ -[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]
+ -[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]
+ -[HAP2AccessoryServerCoordinator(Test) _test_deliverLoss:]
+ -[HAP2AccessoryServerDiscoveryBonjour lastKnownAccessoryInfoByServiceKey]
+ -[HAP2AccessoryServerEncodingThread _parseCharacteristics:isMultiTransportAccessory:error:]
+ -[HAP2AccessoryServerIPCacheData .cxx_destruct]
+ -[HAP2AccessoryServerIPCacheData cachedPrimaryData]
+ -[HAP2AccessoryServerIPCacheData cachedSecondaryData]
+ -[HAP2AccessoryServerIPCacheData configurationInfo]
+ -[HAP2AccessoryServerIPCacheData deviceID]
+ -[HAP2AccessoryServerIPCacheData dictionaryRepresentation]
+ -[HAP2AccessoryServerIPCacheData initFromDictionary:deviceID:]
+ -[HAP2AccessoryServerIPCacheData initWithDeviceID:cachedPrimaryData:cachedSecondaryData:configurationInfo:]
+ -[HAP2AccessoryServerIPCacheData setCachedPrimaryData:]
+ -[HAP2AccessoryServerIPCacheData setCachedSecondaryData:]
+ -[HAP2AccessoryServerIPCacheData setConfigurationInfo:]
+ -[HAP2AccessoryServerIPCacheData setDeviceID:]
+ -[HAP2AccessoryServerSecureTransportBase applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerSecureTransportBase checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerSecureTransportBase hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerSecureTransportBase lastCompletedMessageID]
+ -[HAP2AccessoryServerSecureTransportBase readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsKeepAlive:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsThreadTransport:]
+ -[HAP2AccessoryServerSecureTransportBase setSupportsWiFiTransport:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didChangeThreadAdvertisement:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didChangeWiFiAdvertisement:]
+ -[HAP2AccessoryServerSecureTransportBase transport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidCompleteOnIPAddress:transportType:]
+ -[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidFailOnIPAddress:transportType:error:]
+ -[HAP2AccessoryServerSecureTransportBase transportCurrentResolverSnapshot:]
+ -[HAP2AccessoryServerSecureTransportPairSetup transport:didReceiveHeartbeatOnTransport:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _claimStateChangeCompletionForGeneration:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _clearECDSAStateForGeneration:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _createSecuritySessionFromECDSASessionForGeneration:]
+ -[HAP2AccessoryServerSecureTransportPairVerify _currentStateChangeGeneration]
+ -[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:generation:]
+ -[HAP2AccessoryServerTransportBase hasQueuedCloseOperation]
+ -[HAP2AccessoryServerTransportBase lastCompletedMessageID]
+ -[HAP2AccessoryServerTransportBase setSupportsKeepAlive:]
+ -[HAP2AccessoryServerTransportBase setSupportsThreadTransport:]
+ -[HAP2AccessoryServerTransportBase setSupportsWiFiTransport:]
+ -[HAP2AccessoryServerTransportBase supportsKeepAlive]
+ -[HAP2AccessoryServerTransportBase supportsThreadTransport]
+ -[HAP2AccessoryServerTransportBase supportsWiFiTransport]
+ -[HAP2AccessoryServerTransportCoAP _applyResolverAddressesOnQueue:]
+ -[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]
+ -[HAP2AccessoryServerTransportCoAP _beginInitialOpenLoggingAddress:transportLabel:]
+ -[HAP2AccessoryServerTransportCoAP _buildSecondaryCoapClientWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _cancelFailoverTimer]
+ -[HAP2AccessoryServerTransportCoAP _cancelResolver]
+ -[HAP2AccessoryServerTransportCoAP _completeRequest:error:path:]
+ -[HAP2AccessoryServerTransportCoAP _createCoapClient]
+ -[HAP2AccessoryServerTransportCoAP _evaluateCacheMissCancelIfNeededWithLivePrimaryCount:]
+ -[HAP2AccessoryServerTransportCoAP _executeCacheMissCancel]
+ -[HAP2AccessoryServerTransportCoAP _failInitialOpenWithError:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolvePrimary:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolveSecondary:]
+ -[HAP2AccessoryServerTransportCoAP _handleInitialResolverComplete]
+ -[HAP2AccessoryServerTransportCoAP _handleLiveResolverUpdate]
+ -[HAP2AccessoryServerTransportCoAP _handleRefreshResolve:isFromPrimaryList:]
+ -[HAP2AccessoryServerTransportCoAP _handleResolve:isFromPrimaryList:]
+ -[HAP2AccessoryServerTransportCoAP _logAddress:index:]
+ -[HAP2AccessoryServerTransportCoAP _maybeFireOffQueueCacheMissCancelForAddresses:]
+ -[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]
+ -[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]
+ -[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]
+ -[HAP2AccessoryServerTransportCoAP _refreshIPAddresses]
+ -[HAP2AccessoryServerTransportCoAP _resetIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP _resetInitialCacheOnlyStopgapState]
+ -[HAP2AccessoryServerTransportCoAP _resolveAddress]
+ -[HAP2AccessoryServerTransportCoAP _resolveFailedWithError:]
+ -[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]
+ -[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]
+ -[HAP2AccessoryServerTransportCoAP _sendMultiTransportRequest:path:]
+ -[HAP2AccessoryServerTransportCoAP _sendRegistrationTLVWithAddressBytes:port:]
+ -[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]
+ -[HAP2AccessoryServerTransportCoAP _setIpAddress:]
+ -[HAP2AccessoryServerTransportCoAP _shouldRegisterEndpoint]
+ -[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]
+ -[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]
+ -[HAP2AccessoryServerTransportCoAP _takeNextPrimaryIPToTry]
+ -[HAP2AccessoryServerTransportCoAP _takeNextSecondaryIPToTry]
+ -[HAP2AccessoryServerTransportCoAP _tearDownInitialCacheGracePeriodTimer]
+ -[HAP2AccessoryServerTransportCoAP addressResolverFactory]
+ -[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP applyResolverAddresses:completion:]
+ -[HAP2AccessoryServerTransportCoAP checkConnectedIPAddressStaleOnTransport:completion:]
+ -[HAP2AccessoryServerTransportCoAP clientDidReceivePing:]
+ -[HAP2AccessoryServerTransportCoAP dataStreamPeerAddressWithCompletion:]
+ -[HAP2AccessoryServerTransportCoAP hasArmedCacheOnlyLatch]
+ -[HAP2AccessoryServerTransportCoAP hasRegisteredEndpoint]
+ -[HAP2AccessoryServerTransportCoAP initialACKTimeout]
+ -[HAP2AccessoryServerTransportCoAP initialCacheGracePeriodTimer]
+ -[HAP2AccessoryServerTransportCoAP initialConnectionAttemptStartedAt]
+ -[HAP2AccessoryServerTransportCoAP lastCompletedMessageID]
+ -[HAP2AccessoryServerTransportCoAP lastMessageID]
+ -[HAP2AccessoryServerTransportCoAP logIPAddresses]
+ -[HAP2AccessoryServerTransportCoAP maxTransmitAttempts]
+ -[HAP2AccessoryServerTransportCoAP primaryEffectiveListIsCacheOnly]
+ -[HAP2AccessoryServerTransportCoAP primaryIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP primaryOpenInFlight]
+ -[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]
+ -[HAP2AccessoryServerTransportCoAP resolveTimeoutTimer]
+ -[HAP2AccessoryServerTransportCoAP resolverRestartTimer]
+ -[HAP2AccessoryServerTransportCoAP secondaryAddressList]
+ -[HAP2AccessoryServerTransportCoAP secondaryCoAPClient]
+ -[HAP2AccessoryServerTransportCoAP secondaryIPsTriedThisSession]
+ -[HAP2AccessoryServerTransportCoAP securedClient]
+ -[HAP2AccessoryServerTransportCoAP sendProbeOnTransport:completion:]
+ -[HAP2AccessoryServerTransportCoAP setAddressResolverFactory:]
+ -[HAP2AccessoryServerTransportCoAP setHasRegisteredEndpoint:]
+ -[HAP2AccessoryServerTransportCoAP setInFlightRacingLogEvent:]
+ -[HAP2AccessoryServerTransportCoAP setInitialCacheGracePeriodTimer:]
+ -[HAP2AccessoryServerTransportCoAP setInitialConnectionAttemptStartedAt:]
+ -[HAP2AccessoryServerTransportCoAP setLastCompletedMessageID:]
+ -[HAP2AccessoryServerTransportCoAP setLastMessageID:]
+ -[HAP2AccessoryServerTransportCoAP setNumOfAddresses:]
+ -[HAP2AccessoryServerTransportCoAP setNumOfAddressesTried:]
+ -[HAP2AccessoryServerTransportCoAP setPrimaryEffectiveListIsCacheOnly:]
+ -[HAP2AccessoryServerTransportCoAP setPrimaryOpenInFlight:]
+ -[HAP2AccessoryServerTransportCoAP setResolveTimeoutTimer:]
+ -[HAP2AccessoryServerTransportCoAP setResolverRestartTimer:]
+ -[HAP2AccessoryServerTransportCoAP setSecondaryCoAPClient:]
+ -[HAP2AccessoryServerTransportCoAP setSecuredClient:]
+ -[HAP2AccessoryServerTransportCoAP setTryingInitialCacheOnly:]
+ -[HAP2AccessoryServerTransportCoAP signalPairVerifyFailureToDelegateWithError:]
+ -[HAP2AccessoryServerTransportCoAP signalPairVerifySuccessToDelegate]
+ -[HAP2AccessoryServerTransportCoAP tryingInitialCacheOnly]
+ -[HAP2BrowserResolverRegistry .cxx_destruct]
+ -[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]
+ -[HAP2BrowserResolverRegistry browser]
+ -[HAP2BrowserResolverRegistry createResolverWithDeviceID:serviceName:]
+ -[HAP2BrowserResolverRegistry initWithName:browser:]
+ -[HAP2BrowserResolverRegistry managerQueue]
+ -[HAP2BrowserResolverRegistry name]
+ -[HAP2BrowserResolverRegistry performAuditPassWithActiveDeviceIDs:]
+ -[HAP2BrowserResolverRegistry pipelineFactory]
+ -[HAP2BrowserResolverRegistry propertyLock]
+ -[HAP2BrowserResolverRegistry removeResolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry resolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry resolversByDeviceID]
+ -[HAP2BrowserResolverRegistry setPipelineFactory:]
+ -[HAP2BrowserResolverRegistry updateCachedAddressesForDeviceID:cachedPrimary:cachedSecondary:]
+ -[HAP2BrowserResolverRegistry(Test) _allDeviceIDs]
+ -[HAP2BrowserResolverRegistry(Test) _managerQueue]
+ -[HAP2BrowserResolverRegistry(Test) _pipelineFactory]
+ -[HAP2BrowserResolverRegistry(Test) _privateResolverForDeviceID:]
+ -[HAP2BrowserResolverRegistry(Test) set_pipelineFactory:]
+ -[HAP2CoAPClient _didDisconnectWithError:]
+ -[HAP2CoAPClient _fireProbeCompletionWithResponse:error:]
+ -[HAP2CoAPClient address]
+ -[HAP2CoAPClient didReceivePingInSession:messageID:]
+ -[HAP2CoAPClient getLocalEndpointWithCompletion:]
+ -[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]
+ -[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]
+ -[HAP2CoAPClient getRTTStatisticsWithCompletion:]
+ -[HAP2CoAPClient sendProbeWithCompletion:]
+ -[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]
+ -[HAP2DefaultAccessoryAddressResolverPipelineFactory createResolverWithServiceName:serviceType:serviceDomain:queue:updateHandler:errorHandler:]
+ -[HAP2SerializedOperationQueue _applyCallerQoSToOperations:]
+ -[HAP2SerializedOperationQueue addConcurrentBlock:qos:]
+ -[HAP2SessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:]
+ -[HAP2SessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAP2SessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAP2SessionKeepAliveConfigurationEntry transportType]
+ -[HAP2SessionKeepAliveListener .cxx_destruct]
+ -[HAP2SessionKeepAliveListener _copyDelegates]
+ -[HAP2SessionKeepAliveListener _handleTimerFireForTransport:]
+ -[HAP2SessionKeepAliveListener addDelegate:]
+ -[HAP2SessionKeepAliveListener dateProvider]
+ -[HAP2SessionKeepAliveListener dealloc]
+ -[HAP2SessionKeepAliveListener delegates]
+ -[HAP2SessionKeepAliveListener didReceiveHeartbeatOnTransport:]
+ -[HAP2SessionKeepAliveListener hasMissedHeartbeatForTransport:]
+ -[HAP2SessionKeepAliveListener initWithConfigurationEntries:workQueue:]
+ -[HAP2SessionKeepAliveListener initWithConfigurationEntries:workQueue:timerProvider:dateProvider:]
+ -[HAP2SessionKeepAliveListener isRunning]
+ -[HAP2SessionKeepAliveListener isTrackingTransport:]
+ -[HAP2SessionKeepAliveListener logIdentifier]
+ -[HAP2SessionKeepAliveListener missCheckTimer]
+ -[HAP2SessionKeepAliveListener removeDelegate:]
+ -[HAP2SessionKeepAliveListener resetHeartbeatTimestamps]
+ -[HAP2SessionKeepAliveListener setDateProvider:]
+ -[HAP2SessionKeepAliveListener setDelegates:]
+ -[HAP2SessionKeepAliveListener setIsRunning:]
+ -[HAP2SessionKeepAliveListener setMissCheckTimer:]
+ -[HAP2SessionKeepAliveListener setTimerProvider:]
+ -[HAP2SessionKeepAliveListener setTransportStates:]
+ -[HAP2SessionKeepAliveListener setWorkQueue:]
+ -[HAP2SessionKeepAliveListener start]
+ -[HAP2SessionKeepAliveListener stop]
+ -[HAP2SessionKeepAliveListener timeSinceLastHeartbeatForTransport:]
+ -[HAP2SessionKeepAliveListener timerDidFire:]
+ -[HAP2SessionKeepAliveListener timerProvider]
+ -[HAP2SessionKeepAliveListener trackedTransportTypes]
+ -[HAP2SessionKeepAliveListener transportStates]
+ -[HAP2SessionKeepAliveListener workQueue]
+ -[HAP2SessionKeepAliveTransportState .cxx_destruct]
+ -[HAP2SessionKeepAliveTransportState hasMissedHeartbeat]
+ -[HAP2SessionKeepAliveTransportState initWithTransportType:maximumInterval:]
+ -[HAP2SessionKeepAliveTransportState lastHeartbeatTime]
+ -[HAP2SessionKeepAliveTransportState maximumInterval]
+ -[HAP2SessionKeepAliveTransportState setHasMissedHeartbeat:]
+ -[HAP2SessionKeepAliveTransportState setLastHeartbeatTime:]
+ -[HAP2SessionKeepAliveTransportState transportType]
+ -[HAPAVCStreamingControlCommandWrapper copyWithZone:]
+ -[HAPAVCStreamingControlCommandWrapper description]
+ -[HAPAVCStreamingControlCommandWrapper initWithValue:]
+ -[HAPAVCStreamingControlCommandWrapper init]
+ -[HAPAVCStreamingControlCommandWrapper isEqual:]
+ -[HAPAVCStreamingControlCommandWrapper parseFromData:error:]
+ -[HAPAVCStreamingControlCommandWrapper serializeWithError:]
+ -[HAPAVCStreamingControlCommandWrapper setValue:]
+ -[HAPAVCStreamingControlCommandWrapper value]
+ -[HAPAVCStreamingControlRequest .cxx_destruct]
+ -[HAPAVCStreamingControlRequest command]
+ -[HAPAVCStreamingControlRequest copyWithZone:]
+ -[HAPAVCStreamingControlRequest description]
+ -[HAPAVCStreamingControlRequest initWithSessionIdentifier:command:]
+ -[HAPAVCStreamingControlRequest init]
+ -[HAPAVCStreamingControlRequest isEqual:]
+ -[HAPAVCStreamingControlRequest parseFromData:error:]
+ -[HAPAVCStreamingControlRequest serializeWithError:]
+ -[HAPAVCStreamingControlRequest sessionIdentifier]
+ -[HAPAVCStreamingControlRequest setCommand:]
+ -[HAPAVCStreamingControlRequest setSessionIdentifier:]
+ -[HAPAVCStreamingControlResponse .cxx_destruct]
+ -[HAPAVCStreamingControlResponse copyWithZone:]
+ -[HAPAVCStreamingControlResponse description]
+ -[HAPAVCStreamingControlResponse initWithSessionIdentifier:status:]
+ -[HAPAVCStreamingControlResponse init]
+ -[HAPAVCStreamingControlResponse isEqual:]
+ -[HAPAVCStreamingControlResponse parseFromData:error:]
+ -[HAPAVCStreamingControlResponse serializeWithError:]
+ -[HAPAVCStreamingControlResponse sessionIdentifier]
+ -[HAPAVCStreamingControlResponse setSessionIdentifier:]
+ -[HAPAVCStreamingControlResponse setStatus:]
+ -[HAPAVCStreamingControlResponse status]
+ -[HAPAVCStreamingControlStatusWrapper copyWithZone:]
+ -[HAPAVCStreamingControlStatusWrapper description]
+ -[HAPAVCStreamingControlStatusWrapper initWithValue:]
+ -[HAPAVCStreamingControlStatusWrapper init]
+ -[HAPAVCStreamingControlStatusWrapper isEqual:]
+ -[HAPAVCStreamingControlStatusWrapper parseFromData:error:]
+ -[HAPAVCStreamingControlStatusWrapper serializeWithError:]
+ -[HAPAVCStreamingControlStatusWrapper setValue:]
+ -[HAPAVCStreamingControlStatusWrapper value]
+ -[HAPAVCViewerRegistrationOperationWrapper copyWithZone:]
+ -[HAPAVCViewerRegistrationOperationWrapper description]
+ -[HAPAVCViewerRegistrationOperationWrapper initWithValue:]
+ -[HAPAVCViewerRegistrationOperationWrapper init]
+ -[HAPAVCViewerRegistrationOperationWrapper isEqual:]
+ -[HAPAVCViewerRegistrationOperationWrapper parseFromData:error:]
+ -[HAPAVCViewerRegistrationOperationWrapper serializeWithError:]
+ -[HAPAVCViewerRegistrationOperationWrapper setValue:]
+ -[HAPAVCViewerRegistrationOperationWrapper value]
+ -[HAPAVCViewerRegistrationRequest initWithSessionIdentifier:viewerParticipantID:viewerNegotiationBlob:operation:]
+ -[HAPAVCViewerRegistrationRequest operation]
+ -[HAPAVCViewerRegistrationRequest setOperation:]
+ -[HAPAccessoryInfo hasAssignedProductPlan]
+ -[HAPAccessoryPairingRequest init]
+ -[HAPAccessoryPairingRequest setShouldAllowECDSAKeyPairSetup:]
+ -[HAPAccessoryPairingRequest shouldAllowECDSAKeyPairSetup]
+ -[HAPAccessoryServer configureKeepAliveListener:]
+ -[HAPAccessoryServer disconnectWithCompletion:]
+ -[HAPAccessoryServer hasThreadAdvertisement]
+ -[HAPAccessoryServer hasWiFiAdvertisement]
+ -[HAPAccessoryServer lastPairSetupWasSpake2]
+ -[HAPAccessoryServer pairSetupLastError]
+ -[HAPAccessoryServer pairSetupM1ToM4Completed]
+ -[HAPAccessoryServer pairSetupM1ToM4DurationMS]
+ -[HAPAccessoryServer pairSetupM1ToM4Error]
+ -[HAPAccessoryServer pairSetupM5ToM6Completed]
+ -[HAPAccessoryServer pairSetupM5ToM6DurationMS]
+ -[HAPAccessoryServer pairSetupM5ToM6Error]
+ -[HAPAccessoryServer pairSetupWorkDurationMS]
+ -[HAPAccessoryServer setHasThreadAdvertisement:]
+ -[HAPAccessoryServer setHasWiFiAdvertisement:]
+ -[HAPAccessoryServer setLastPairSetupWasSpake2:]
+ -[HAPAccessoryServer setPairSetupLastError:]
+ -[HAPAccessoryServer setPairSetupM1ToM4Completed:]
+ -[HAPAccessoryServer setPairSetupM1ToM4DurationMS:]
+ -[HAPAccessoryServer setPairSetupM1ToM4Error:]
+ -[HAPAccessoryServer setPairSetupM5ToM6Completed:]
+ -[HAPAccessoryServer setPairSetupM5ToM6DurationMS:]
+ -[HAPAccessoryServer setPairSetupM5ToM6Error:]
+ -[HAPAccessoryServer setPairSetupWorkDurationMS:]
+ -[HAPAccessoryServer setTokenAuthCompleted:]
+ -[HAPAccessoryServer setTokenAuthDurationMS:]
+ -[HAPAccessoryServer setTokenAuthError:]
+ -[HAPAccessoryServer tokenAuthCompleted]
+ -[HAPAccessoryServer tokenAuthDurationMS]
+ -[HAPAccessoryServer tokenAuthError]
+ -[HAPAccessoryServer workQueueFactory]
+ -[HAPAccessoryServerBrowser hasWiFiAdvertisementForHAP2AccessoryServerIdentifier:]
+ -[HAPAccessoryServerBrowser isThreadAccessoryDiscoveredWithAccessoryServerIdentifier:]
+ -[HAPAccessoryServerBrowserHAP2Adapter hasWiFiAdvertisementForHAP2AccessoryServerIdentifier:]
+ -[HAPAccessoryServerBrowserHAP2Adapter isThreadAccessoryDiscoveredWithAccessoryServerIdentifier:]
+ -[HAPAccessoryServerBrowserHAP2Adapter setIPCache:]
+ -[HAPAccessoryServerHAP2Adapter accessoryServer:didUpdateLocalEndpoints:]
+ -[HAPAccessoryServerHAP2Adapter configureKeepAliveListener:]
+ -[HAPAccessoryServerHAP2Adapter dataStreamPeerAddressWithCompletion:]
+ -[HAPAccessoryServerHAP2Adapter deriveEncryptionForDataStreamWithKeySalt:completionHandler:]
+ -[HAPAccessoryServerHAP2Adapter disconnectWithCompletion:]
+ -[HAPAccessoryServerHAP2Adapter hasThreadAdvertisement]
+ -[HAPAccessoryServerHAP2Adapter hasWiFiAdvertisement]
+ -[HAPAccessoryServerIP disconnectWithCompletion:]
+ -[HAPAccessoryServerIP hasWiFiAdvertisement]
+ -[HAPAccessoryServerIP selfAddress]
+ -[HAPAccessoryServerNFC _captureProxPairSetupPhaseTimingsAsOf:pairSetupReachedM6:phaseError:]
+ -[HAPAccessoryServerNFC _ecdsaKeyPairSetupRefusalError]
+ -[HAPAccessoryServerNFC _finishTokenAuthOnWorkQueueAsOf:completed:error:]
+ -[HAPAccessoryServerNFC _resetProxPairSetupPhaseOutputs]
+ -[HAPAccessoryServerNFC _resetTokenAuthOutputs]
+ -[HAPAccessoryServerNFC finishTokenAuthAsOf:completed:error:]
+ -[HAPAccessoryServerNFC isDenylisted]
+ -[HAPAccessoryServerNFC nfcM4RecvTime]
+ -[HAPAccessoryServerNFC setDenylisted:]
+ -[HAPAccessoryServerNFC setNfcM4RecvTime:]
+ -[HAPAccessoryServerNFC setTokenAuthEndTime:]
+ -[HAPAccessoryServerNFC setTokenAuthStartTime:]
+ -[HAPAccessoryServerNFC tokenAuthEndTime]
+ -[HAPAccessoryServerNFC tokenAuthStartTime]
+ -[HAPBluetoothMetrics .cxx_destruct]
+ -[HAPBluetoothMetrics bluetoothVersion]
+ -[HAPBluetoothMetrics connectionCount]
+ -[HAPBluetoothMetrics connectionErrorCount]
+ -[HAPBluetoothMetrics connectionStatus]
+ -[HAPBluetoothMetrics copyWithZone:]
+ -[HAPBluetoothMetrics description]
+ -[HAPBluetoothMetrics disconnectionCount]
+ -[HAPBluetoothMetrics disconnectionErrorCount]
+ -[HAPBluetoothMetrics hwExceptionCount]
+ -[HAPBluetoothMetrics initWithBluetoothVersion:rssi:txPowerLevel:packetRxCount:packetTxCount:packetRxErrorCount:packetTxErrorCount:overrunCount:connectionStatus:connectionCount:connectionErrorCount:disconnectionCount:disconnectionErrorCount:hwExceptionCount:]
+ -[HAPBluetoothMetrics init]
+ -[HAPBluetoothMetrics isEqual:]
+ -[HAPBluetoothMetrics overrunCount]
+ -[HAPBluetoothMetrics packetRxCount]
+ -[HAPBluetoothMetrics packetRxErrorCount]
+ -[HAPBluetoothMetrics packetTxCount]
+ -[HAPBluetoothMetrics packetTxErrorCount]
+ -[HAPBluetoothMetrics parseFromData:error:]
+ -[HAPBluetoothMetrics rssi]
+ -[HAPBluetoothMetrics serializeWithError:]
+ -[HAPBluetoothMetrics setBluetoothVersion:]
+ -[HAPBluetoothMetrics setConnectionCount:]
+ -[HAPBluetoothMetrics setConnectionErrorCount:]
+ -[HAPBluetoothMetrics setConnectionStatus:]
+ -[HAPBluetoothMetrics setDisconnectionCount:]
+ -[HAPBluetoothMetrics setDisconnectionErrorCount:]
+ -[HAPBluetoothMetrics setHwExceptionCount:]
+ -[HAPBluetoothMetrics setOverrunCount:]
+ -[HAPBluetoothMetrics setPacketRxCount:]
+ -[HAPBluetoothMetrics setPacketRxErrorCount:]
+ -[HAPBluetoothMetrics setPacketTxCount:]
+ -[HAPBluetoothMetrics setPacketTxErrorCount:]
+ -[HAPBluetoothMetrics setRssi:]
+ -[HAPBluetoothMetrics setTxPowerLevel:]
+ -[HAPBluetoothMetrics txPowerLevel]
+ -[HAPBootReasonsMetrics .cxx_destruct]
+ -[HAPBootReasonsMetrics brownOutResetBootCount]
+ -[HAPBootReasonsMetrics connectivityMonitorBootCount]
+ -[HAPBootReasonsMetrics copyWithZone:]
+ -[HAPBootReasonsMetrics description]
+ -[HAPBootReasonsMetrics hardwareFaultBootCount]
+ -[HAPBootReasonsMetrics hardwareWatchdogResetBootCount]
+ -[HAPBootReasonsMetrics heapOverflowBootCount]
+ -[HAPBootReasonsMetrics initWithUnspecifiedBootCount:powerOnBootCount:brownOutResetBootCount:softwareWatchdogResetBootCount:hardwareWatchdogResetBootCount:softwareUpdateCompletedBootCount:softwareResetBootCount:softwareExceptionBootCount:hardwareFaultBootCount:stackOverflowBootCount:heapOverflowBootCount:temperatureLimitBootCount:connectivityMonitorBootCount:]
+ -[HAPBootReasonsMetrics init]
+ -[HAPBootReasonsMetrics isEqual:]
+ -[HAPBootReasonsMetrics parseFromData:error:]
+ -[HAPBootReasonsMetrics powerOnBootCount]
+ -[HAPBootReasonsMetrics serializeWithError:]
+ -[HAPBootReasonsMetrics setBrownOutResetBootCount:]
+ -[HAPBootReasonsMetrics setConnectivityMonitorBootCount:]
+ -[HAPBootReasonsMetrics setHardwareFaultBootCount:]
+ -[HAPBootReasonsMetrics setHardwareWatchdogResetBootCount:]
+ -[HAPBootReasonsMetrics setHeapOverflowBootCount:]
+ -[HAPBootReasonsMetrics setPowerOnBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareExceptionBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareResetBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareUpdateCompletedBootCount:]
+ -[HAPBootReasonsMetrics setSoftwareWatchdogResetBootCount:]
+ -[HAPBootReasonsMetrics setStackOverflowBootCount:]
+ -[HAPBootReasonsMetrics setTemperatureLimitBootCount:]
+ -[HAPBootReasonsMetrics setUnspecifiedBootCount:]
+ -[HAPBootReasonsMetrics softwareExceptionBootCount]
+ -[HAPBootReasonsMetrics softwareResetBootCount]
+ -[HAPBootReasonsMetrics softwareUpdateCompletedBootCount]
+ -[HAPBootReasonsMetrics softwareWatchdogResetBootCount]
+ -[HAPBootReasonsMetrics stackOverflowBootCount]
+ -[HAPBootReasonsMetrics temperatureLimitBootCount]
+ -[HAPBootReasonsMetrics unspecifiedBootCount]
+ -[HAPCHMMetrics .cxx_destruct]
+ -[HAPCHMMetrics chmAccessoryRebootCompleted]
+ -[HAPCHMMetrics chmAccessoryRebootDurationToRecovery]
+ -[HAPCHMMetrics copyWithZone:]
+ -[HAPCHMMetrics description]
+ -[HAPCHMMetrics hapSessionLossCount]
+ -[HAPCHMMetrics initWithWifiTransportLossCount:wifiRecoveryAttemptCount:wifiRestartCount:wifiFirstRestartRecoveryTime:wifiFirstRestartCompleted:wifiFirstRestartConnectivityState:threadTransportLossCount:threadRecoveryAttemptCount:threadRestartCount:threadFirstRestartRecoveryTime:threadFirstRestartCompleted:threadFirstRestartConnectivityState:hapSessionLossCount:chmAccessoryRebootDurationToRecovery:chmAccessoryRebootCompleted:]
+ -[HAPCHMMetrics init]
+ -[HAPCHMMetrics isEqual:]
+ -[HAPCHMMetrics parseFromData:error:]
+ -[HAPCHMMetrics serializeWithError:]
+ -[HAPCHMMetrics setChmAccessoryRebootCompleted:]
+ -[HAPCHMMetrics setChmAccessoryRebootDurationToRecovery:]
+ -[HAPCHMMetrics setHapSessionLossCount:]
+ -[HAPCHMMetrics setThreadFirstRestartCompleted:]
+ -[HAPCHMMetrics setThreadFirstRestartConnectivityState:]
+ -[HAPCHMMetrics setThreadFirstRestartRecoveryTime:]
+ -[HAPCHMMetrics setThreadRecoveryAttemptCount:]
+ -[HAPCHMMetrics setThreadRestartCount:]
+ -[HAPCHMMetrics setThreadTransportLossCount:]
+ -[HAPCHMMetrics setWifiFirstRestartCompleted:]
+ -[HAPCHMMetrics setWifiFirstRestartConnectivityState:]
+ -[HAPCHMMetrics setWifiFirstRestartRecoveryTime:]
+ -[HAPCHMMetrics setWifiRecoveryAttemptCount:]
+ -[HAPCHMMetrics setWifiRestartCount:]
+ -[HAPCHMMetrics setWifiTransportLossCount:]
+ -[HAPCHMMetrics threadFirstRestartCompleted]
+ -[HAPCHMMetrics threadFirstRestartConnectivityState]
+ -[HAPCHMMetrics threadFirstRestartRecoveryTime]
+ -[HAPCHMMetrics threadRecoveryAttemptCount]
+ -[HAPCHMMetrics threadRestartCount]
+ -[HAPCHMMetrics threadTransportLossCount]
+ -[HAPCHMMetrics wifiFirstRestartCompleted]
+ -[HAPCHMMetrics wifiFirstRestartConnectivityState]
+ -[HAPCHMMetrics wifiFirstRestartRecoveryTime]
+ -[HAPCHMMetrics wifiRecoveryAttemptCount]
+ -[HAPCHMMetrics wifiRestartCount]
+ -[HAPCHMMetrics wifiTransportLossCount]
+ -[HAPCharacteristicResponseTuple coapMessageID]
+ -[HAPCharacteristicResponseTuple setCoapMessageID:]
+ -[HAPConnectionHealthMonitor .cxx_destruct]
+ -[HAPConnectionHealthMonitor copyWithZone:]
+ -[HAPConnectionHealthMonitor description]
+ -[HAPConnectionHealthMonitor deviceRebootDelay]
+ -[HAPConnectionHealthMonitor deviceRebootEnable]
+ -[HAPConnectionHealthMonitor initWithDeviceRebootEnable:threadRecoveryConfiguration:wiFiRecoveryConfiguration:recoveryStaggerDelay:deviceRebootDelay:threadPingTestCount:threadPingTestInterval:threadRestartMinInterval:wiFiPingTestCount:wiFiPingTestInterval:wiFiRestartMinInterval:]
+ -[HAPConnectionHealthMonitor init]
+ -[HAPConnectionHealthMonitor isEqual:]
+ -[HAPConnectionHealthMonitor parseFromData:error:]
+ -[HAPConnectionHealthMonitor recoveryStaggerDelay]
+ -[HAPConnectionHealthMonitor serializeWithError:]
+ -[HAPConnectionHealthMonitor setDeviceRebootDelay:]
+ -[HAPConnectionHealthMonitor setDeviceRebootEnable:]
+ -[HAPConnectionHealthMonitor setRecoveryStaggerDelay:]
+ -[HAPConnectionHealthMonitor setThreadPingTestCount:]
+ -[HAPConnectionHealthMonitor setThreadPingTestInterval:]
+ -[HAPConnectionHealthMonitor setThreadRecoveryConfiguration:]
+ -[HAPConnectionHealthMonitor setThreadRestartMinInterval:]
+ -[HAPConnectionHealthMonitor setWiFiPingTestCount:]
+ -[HAPConnectionHealthMonitor setWiFiPingTestInterval:]
+ -[HAPConnectionHealthMonitor setWiFiRecoveryConfiguration:]
+ -[HAPConnectionHealthMonitor setWiFiRestartMinInterval:]
+ -[HAPConnectionHealthMonitor threadPingTestCount]
+ -[HAPConnectionHealthMonitor threadPingTestInterval]
+ -[HAPConnectionHealthMonitor threadRecoveryConfiguration]
+ -[HAPConnectionHealthMonitor threadRestartMinInterval]
+ -[HAPConnectionHealthMonitor wiFiPingTestCount]
+ -[HAPConnectionHealthMonitor wiFiPingTestInterval]
+ -[HAPConnectionHealthMonitor wiFiRecoveryConfiguration]
+ -[HAPConnectionHealthMonitor wiFiRestartMinInterval]
+ -[HAPContributingSensor .cxx_destruct]
+ -[HAPContributingSensor copyWithZone:]
+ -[HAPContributingSensor description]
+ -[HAPContributingSensor initWithSensorUUID:]
+ -[HAPContributingSensor init]
+ -[HAPContributingSensor isEqual:]
+ -[HAPContributingSensor parseFromData:error:]
+ -[HAPContributingSensor sensorUUID]
+ -[HAPContributingSensor serializeWithError:]
+ -[HAPContributingSensor setSensorUUID:]
+ -[HAPCoreUtilsHTTPClient getSelfAddress:maxLength:outLength:]
+ -[HAPDefaultWorkQueueFactory newQueueWithLabel:attributes:]
+ -[HAPDefaultWorkQueueFactory newQueueWithLabel:attributes:target:]
+ -[HAPErrorCountersMetrics .cxx_destruct]
+ -[HAPErrorCountersMetrics copyWithZone:]
+ -[HAPErrorCountersMetrics description]
+ -[HAPErrorCountersMetrics entries]
+ -[HAPErrorCountersMetrics initWithEntries:]
+ -[HAPErrorCountersMetrics init]
+ -[HAPErrorCountersMetrics isEqual:]
+ -[HAPErrorCountersMetrics parseFromData:error:]
+ -[HAPErrorCountersMetrics serializeWithError:]
+ -[HAPErrorCountersMetrics setEntries:]
+ -[HAPErrorCountersMetricsEntry .cxx_destruct]
+ -[HAPErrorCountersMetricsEntry copyWithZone:]
+ -[HAPErrorCountersMetricsEntry count]
+ -[HAPErrorCountersMetricsEntry description]
+ -[HAPErrorCountersMetricsEntry errorID]
+ -[HAPErrorCountersMetricsEntry initWithErrorID:count:]
+ -[HAPErrorCountersMetricsEntry init]
+ -[HAPErrorCountersMetricsEntry isEqual:]
+ -[HAPErrorCountersMetricsEntry parseFromData:error:]
+ -[HAPErrorCountersMetricsEntry serializeWithError:]
+ -[HAPErrorCountersMetricsEntry setCount:]
+ -[HAPErrorCountersMetricsEntry setErrorID:]
+ -[HAPHKSV3UploadLatencyMetrics .cxx_destruct]
+ -[HAPHKSV3UploadLatencyMetrics abandonedRequestCount]
+ -[HAPHKSV3UploadLatencyMetrics audioOnlyFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics authenticationErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics copyWithZone:]
+ -[HAPHKSV3UploadLatencyMetrics description]
+ -[HAPHKSV3UploadLatencyMetrics fragmentFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics fragmentRetriedCount]
+ -[HAPHKSV3UploadLatencyMetrics fragmentSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics initWithFragmentSuccessCount:fragmentFailureCount:fragmentRetriedCount:networkErrorCount:authenticationErrorCount:serverReturnedErrorCount:localErrorCount:playlistFailureCount:latencyCount250ms:latencyCount500ms:latencyCount1000ms:latencyCount2000ms:latencyCount3750ms:latencyCountOver3750ms:sessionSuccessCount:partialSuccessCount:sessionFailureCount:uploadWithoutResidentResponseCount:audioOnlyFailureCount:abandonedRequestCount:]
+ -[HAPHKSV3UploadLatencyMetrics init]
+ -[HAPHKSV3UploadLatencyMetrics isEqual:]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount1000ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount2000ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount250ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount3750ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCount500ms]
+ -[HAPHKSV3UploadLatencyMetrics latencyCountOver3750ms]
+ -[HAPHKSV3UploadLatencyMetrics localErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics networkErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics parseFromData:error:]
+ -[HAPHKSV3UploadLatencyMetrics partialSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics playlistFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics serializeWithError:]
+ -[HAPHKSV3UploadLatencyMetrics serverReturnedErrorCount]
+ -[HAPHKSV3UploadLatencyMetrics sessionFailureCount]
+ -[HAPHKSV3UploadLatencyMetrics sessionSuccessCount]
+ -[HAPHKSV3UploadLatencyMetrics setAbandonedRequestCount:]
+ -[HAPHKSV3UploadLatencyMetrics setAudioOnlyFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setAuthenticationErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentRetriedCount:]
+ -[HAPHKSV3UploadLatencyMetrics setFragmentSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount1000ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount2000ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount250ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount3750ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCount500ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLatencyCountOver3750ms:]
+ -[HAPHKSV3UploadLatencyMetrics setLocalErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setNetworkErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setPartialSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setPlaylistFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setServerReturnedErrorCount:]
+ -[HAPHKSV3UploadLatencyMetrics setSessionFailureCount:]
+ -[HAPHKSV3UploadLatencyMetrics setSessionSuccessCount:]
+ -[HAPHKSV3UploadLatencyMetrics setUploadWithoutResidentResponseCount:]
+ -[HAPHKSV3UploadLatencyMetrics uploadWithoutResidentResponseCount]
+ -[HAPHTTPClient selfAddress]
+ -[HAPKeyBag cachedAccessoryKeyType]
+ -[HAPKeyBag setCachedAccessoryKeyType:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper copyWithZone:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper description]
+ -[HAPMetricEventBluetoothVersionTypeWrapper initWithValue:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper init]
+ -[HAPMetricEventBluetoothVersionTypeWrapper isEqual:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper parseFromData:error:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper serializeWithError:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper setValue:]
+ -[HAPMetricEventBluetoothVersionTypeWrapper value]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper copyWithZone:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper description]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper initWithValue:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper init]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper isEqual:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper parseFromData:error:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper serializeWithError:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper setValue:]
+ -[HAPMetricEventPowerSourcesBitmaskWrapper value]
+ -[HAPMetricEventPowerSourcesEnumWrapper copyWithZone:]
+ -[HAPMetricEventPowerSourcesEnumWrapper description]
+ -[HAPMetricEventPowerSourcesEnumWrapper initWithValue:]
+ -[HAPMetricEventPowerSourcesEnumWrapper init]
+ -[HAPMetricEventPowerSourcesEnumWrapper isEqual:]
+ -[HAPMetricEventPowerSourcesEnumWrapper parseFromData:error:]
+ -[HAPMetricEventPowerSourcesEnumWrapper serializeWithError:]
+ -[HAPMetricEventPowerSourcesEnumWrapper setValue:]
+ -[HAPMetricEventPowerSourcesEnumWrapper value]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper copyWithZone:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper description]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper initWithValue:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper init]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper isEqual:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper parseFromData:error:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper serializeWithError:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper setValue:]
+ -[HAPMetricEventThreadFirstRestartConnectivityStateWrapper value]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper copyWithZone:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper description]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper initWithValue:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper init]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper isEqual:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper parseFromData:error:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper serializeWithError:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper setValue:]
+ -[HAPMetricEventWiFiFirstRestartConnectivityStateWrapper value]
+ -[HAPMetricEventWiFiVersionTypeWrapper copyWithZone:]
+ -[HAPMetricEventWiFiVersionTypeWrapper description]
+ -[HAPMetricEventWiFiVersionTypeWrapper initWithValue:]
+ -[HAPMetricEventWiFiVersionTypeWrapper init]
+ -[HAPMetricEventWiFiVersionTypeWrapper isEqual:]
+ -[HAPMetricEventWiFiVersionTypeWrapper parseFromData:error:]
+ -[HAPMetricEventWiFiVersionTypeWrapper serializeWithError:]
+ -[HAPMetricEventWiFiVersionTypeWrapper setValue:]
+ -[HAPMetricEventWiFiVersionTypeWrapper value]
+ -[HAPNFCReaderSession isConnectedTagPresent]
+ -[HAPPowerMetrics .cxx_destruct]
+ -[HAPPowerMetrics batteryPercentage]
+ -[HAPPowerMetrics copyWithZone:]
+ -[HAPPowerMetrics currentPowerSource]
+ -[HAPPowerMetrics description]
+ -[HAPPowerMetrics durationOnBatteryPower]
+ -[HAPPowerMetrics durationRemainingOnBatteryPower]
+ -[HAPPowerMetrics initWithSupportedPowerSources:currentPowerSource:durationOnBatteryPower:durationRemainingOnBatteryPower:batteryPercentage:]
+ -[HAPPowerMetrics init]
+ -[HAPPowerMetrics isEqual:]
+ -[HAPPowerMetrics parseFromData:error:]
+ -[HAPPowerMetrics serializeWithError:]
+ -[HAPPowerMetrics setBatteryPercentage:]
+ -[HAPPowerMetrics setCurrentPowerSource:]
+ -[HAPPowerMetrics setDurationOnBatteryPower:]
+ -[HAPPowerMetrics setDurationRemainingOnBatteryPower:]
+ -[HAPPowerMetrics setSupportedPowerSources:]
+ -[HAPPowerMetrics supportedPowerSources]
+ -[HAPSaturationMetrics .cxx_destruct]
+ -[HAPSaturationMetrics averageCPUUtilization]
+ -[HAPSaturationMetrics averageSystemMemoryUtilization]
+ -[HAPSaturationMetrics copyWithZone:]
+ -[HAPSaturationMetrics description]
+ -[HAPSaturationMetrics heapHighwaterCount]
+ -[HAPSaturationMetrics heapOverflowCount]
+ -[HAPSaturationMetrics initWithStackHighwaterCount:lastStackHighwaterTaskName:heapHighwaterCount:lastHeapHighwaterTaskName:stackOverflowCount:lastStackOverflowTaskName:heapOverflowCount:lastHeapOverflowTaskName:averageSystemMemoryUtilization:peakSystemMemoryUtilization:systemMemoryPressureCount:processCriticalMemoryCount:lastProcessCriticalMemoryName:averageCPUUtilization:peakCPUUtilization:taskDeadlineMissCount:totalTasksScheduledCount:maxTaskReadyQueueSize:loadAverage:nonVolatileMemoryWriteCount:nonVolatileMemoryReadCount:nonVolatileMemoryWriteErrorCount:nonVolatileMemoryReadErrorCount:nonVolatileMemoryUtilization:]
+ -[HAPSaturationMetrics init]
+ -[HAPSaturationMetrics isEqual:]
+ -[HAPSaturationMetrics lastHeapHighwaterTaskName]
+ -[HAPSaturationMetrics lastHeapOverflowTaskName]
+ -[HAPSaturationMetrics lastProcessCriticalMemoryName]
+ -[HAPSaturationMetrics lastStackHighwaterTaskName]
+ -[HAPSaturationMetrics lastStackOverflowTaskName]
+ -[HAPSaturationMetrics loadAverage]
+ -[HAPSaturationMetrics maxTaskReadyQueueSize]
+ -[HAPSaturationMetrics nonVolatileMemoryReadCount]
+ -[HAPSaturationMetrics nonVolatileMemoryReadErrorCount]
+ -[HAPSaturationMetrics nonVolatileMemoryUtilization]
+ -[HAPSaturationMetrics nonVolatileMemoryWriteCount]
+ -[HAPSaturationMetrics nonVolatileMemoryWriteErrorCount]
+ -[HAPSaturationMetrics parseFromData:error:]
+ -[HAPSaturationMetrics peakCPUUtilization]
+ -[HAPSaturationMetrics peakSystemMemoryUtilization]
+ -[HAPSaturationMetrics processCriticalMemoryCount]
+ -[HAPSaturationMetrics serializeWithError:]
+ -[HAPSaturationMetrics setAverageCPUUtilization:]
+ -[HAPSaturationMetrics setAverageSystemMemoryUtilization:]
+ -[HAPSaturationMetrics setHeapHighwaterCount:]
+ -[HAPSaturationMetrics setHeapOverflowCount:]
+ -[HAPSaturationMetrics setLastHeapHighwaterTaskName:]
+ -[HAPSaturationMetrics setLastHeapOverflowTaskName:]
+ -[HAPSaturationMetrics setLastProcessCriticalMemoryName:]
+ -[HAPSaturationMetrics setLastStackHighwaterTaskName:]
+ -[HAPSaturationMetrics setLastStackOverflowTaskName:]
+ -[HAPSaturationMetrics setLoadAverage:]
+ -[HAPSaturationMetrics setMaxTaskReadyQueueSize:]
+ -[HAPSaturationMetrics setNonVolatileMemoryReadCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryReadErrorCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryUtilization:]
+ -[HAPSaturationMetrics setNonVolatileMemoryWriteCount:]
+ -[HAPSaturationMetrics setNonVolatileMemoryWriteErrorCount:]
+ -[HAPSaturationMetrics setPeakCPUUtilization:]
+ -[HAPSaturationMetrics setPeakSystemMemoryUtilization:]
+ -[HAPSaturationMetrics setProcessCriticalMemoryCount:]
+ -[HAPSaturationMetrics setStackHighwaterCount:]
+ -[HAPSaturationMetrics setStackOverflowCount:]
+ -[HAPSaturationMetrics setSystemMemoryPressureCount:]
+ -[HAPSaturationMetrics setTaskDeadlineMissCount:]
+ -[HAPSaturationMetrics setTotalTasksScheduledCount:]
+ -[HAPSaturationMetrics stackHighwaterCount]
+ -[HAPSaturationMetrics stackOverflowCount]
+ -[HAPSaturationMetrics systemMemoryPressureCount]
+ -[HAPSaturationMetrics taskDeadlineMissCount]
+ -[HAPSaturationMetrics totalTasksScheduledCount]
+ -[HAPSecuritySession deriveEncryptionForDataStreamWithKeySalt:completionHandler:]
+ -[HAPSecuritySession foreignPairVerifySession]
+ -[HAPSecuritySession setForeignPairVerifySession:]
+ -[HAPSensorList .cxx_destruct]
+ -[HAPSensorList contributingSensor]
+ -[HAPSensorList copyWithZone:]
+ -[HAPSensorList description]
+ -[HAPSensorList initWithContributingSensor:]
+ -[HAPSensorList init]
+ -[HAPSensorList isEqual:]
+ -[HAPSensorList parseFromData:error:]
+ -[HAPSensorList serializeWithError:]
+ -[HAPSensorList setContributingSensor:]
+ -[HAPSessionKeepAliveTransportTypeWrapper copyWithZone:]
+ -[HAPSessionKeepAliveTransportTypeWrapper description]
+ -[HAPSessionKeepAliveTransportTypeWrapper initWithValue:]
+ -[HAPSessionKeepAliveTransportTypeWrapper init]
+ -[HAPSessionKeepAliveTransportTypeWrapper isEqual:]
+ -[HAPSessionKeepAliveTransportTypeWrapper parseFromData:error:]
+ -[HAPSessionKeepAliveTransportTypeWrapper serializeWithError:]
+ -[HAPSessionKeepAliveTransportTypeWrapper setValue:]
+ -[HAPSessionKeepAliveTransportTypeWrapper value]
+ -[HAPStabilityMetrics .cxx_destruct]
+ -[HAPStabilityMetrics activeHardwareFaults]
+ -[HAPStabilityMetrics copyWithZone:]
+ -[HAPStabilityMetrics description]
+ -[HAPStabilityMetrics expectedBootCount]
+ -[HAPStabilityMetrics initWithSystemUptime:systemBootCount:expectedBootCount:systemCrashCount:systemHangCount:lastBootReason:activeHardwareFaults:]
+ -[HAPStabilityMetrics init]
+ -[HAPStabilityMetrics isEqual:]
+ -[HAPStabilityMetrics lastBootReason]
+ -[HAPStabilityMetrics parseFromData:error:]
+ -[HAPStabilityMetrics serializeWithError:]
+ -[HAPStabilityMetrics setActiveHardwareFaults:]
+ -[HAPStabilityMetrics setExpectedBootCount:]
+ -[HAPStabilityMetrics setLastBootReason:]
+ -[HAPStabilityMetrics setSystemBootCount:]
+ -[HAPStabilityMetrics setSystemCrashCount:]
+ -[HAPStabilityMetrics setSystemHangCount:]
+ -[HAPStabilityMetrics setSystemUptime:]
+ -[HAPStabilityMetrics systemBootCount]
+ -[HAPStabilityMetrics systemCrashCount]
+ -[HAPStabilityMetrics systemHangCount]
+ -[HAPStabilityMetrics systemUptime]
+ -[HAPStabilityMetricsBootReasonTypeWrapper copyWithZone:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper description]
+ -[HAPStabilityMetricsBootReasonTypeWrapper initWithValue:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper init]
+ -[HAPStabilityMetricsBootReasonTypeWrapper isEqual:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper parseFromData:error:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper serializeWithError:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper setValue:]
+ -[HAPStabilityMetricsBootReasonTypeWrapper value]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper copyWithZone:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper description]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper initWithValue:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper init]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper isEqual:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper parseFromData:error:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper serializeWithError:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper setValue:]
+ -[HAPStabilityMetricsHardwareFaultTypeWrapper value]
+ -[HAPSystemKeychainStore getHH2ControllerECDSAPublicKeyWithIdentifier:allowBackupRestore:]
+ -[HAPSystemKeychainStore getHH2ControllerKeyWithIdentifier:allowBackupRestore:]
+ -[HAPTLVPreferredWiFiEntry .cxx_destruct]
+ -[HAPTLVPreferredWiFiEntry PSK]
+ -[HAPTLVPreferredWiFiEntry SSID]
+ -[HAPTLVPreferredWiFiEntry copyWithZone:]
+ -[HAPTLVPreferredWiFiEntry description]
+ -[HAPTLVPreferredWiFiEntry initWithSSID:securityMode:PSK:]
+ -[HAPTLVPreferredWiFiEntry init]
+ -[HAPTLVPreferredWiFiEntry isEqual:]
+ -[HAPTLVPreferredWiFiEntry parseFromData:error:]
+ -[HAPTLVPreferredWiFiEntry securityMode]
+ -[HAPTLVPreferredWiFiEntry serializeWithError:]
+ -[HAPTLVPreferredWiFiEntry setPSK:]
+ -[HAPTLVPreferredWiFiEntry setSSID:]
+ -[HAPTLVPreferredWiFiEntry setSecurityMode:]
+ -[HAPTLVPreferredWiFiList .cxx_destruct]
+ -[HAPTLVPreferredWiFiList copyWithZone:]
+ -[HAPTLVPreferredWiFiList description]
+ -[HAPTLVPreferredWiFiList initWithPreferredWiFiList:]
+ -[HAPTLVPreferredWiFiList init]
+ -[HAPTLVPreferredWiFiList isEqual:]
+ -[HAPTLVPreferredWiFiList parseFromData:error:]
+ -[HAPTLVPreferredWiFiList preferredWiFiList]
+ -[HAPTLVPreferredWiFiList serializeWithError:]
+ -[HAPTLVPreferredWiFiList setPreferredWiFiList:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry .cxx_destruct]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry copyWithZone:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry description]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry init]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry isEqual:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry parseFromData:error:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry serializeWithError:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setMaximumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setMinimumInterval:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry setTransportType:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationEntry transportType]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList .cxx_destruct]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList copyWithZone:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList description]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList entries]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList initWithEntries:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList init]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList isEqual:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList parseFromData:error:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList serializeWithError:]
+ -[HAPTLVSelectedSessionKeepAliveConfigurationList setEntries:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry .cxx_destruct]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry copyWithZone:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry description]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry initWithTransportType:minimumInterval:maximumInterval:minimumRange:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry init]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry isEqual:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry maximumInterval]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry minimumInterval]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry minimumRange]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry parseFromData:error:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry serializeWithError:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMaximumInterval:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMinimumInterval:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setMinimumRange:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry setTransportType:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationEntry transportType]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList .cxx_destruct]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList copyWithZone:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList description]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList entries]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList initWithEntries:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList init]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList isEqual:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList parseFromData:error:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList serializeWithError:]
+ -[HAPTLVSupportedSessionKeepAliveConfigurationList setEntries:]
+ -[HAPThermalMetrics .cxx_destruct]
+ -[HAPThermalMetrics averageDeviceTemperature]
+ -[HAPThermalMetrics copyWithZone:]
+ -[HAPThermalMetrics description]
+ -[HAPThermalMetrics initWithTemperatureLimitViolationCount:temperatureLimitViolationDuration:minimumDeviceTemperature:maximumDeviceTemperature:averageDeviceTemperature:]
+ -[HAPThermalMetrics init]
+ -[HAPThermalMetrics isEqual:]
+ -[HAPThermalMetrics maximumDeviceTemperature]
+ -[HAPThermalMetrics minimumDeviceTemperature]
+ -[HAPThermalMetrics parseFromData:error:]
+ -[HAPThermalMetrics serializeWithError:]
+ -[HAPThermalMetrics setAverageDeviceTemperature:]
+ -[HAPThermalMetrics setMaximumDeviceTemperature:]
+ -[HAPThermalMetrics setMinimumDeviceTemperature:]
+ -[HAPThermalMetrics setTemperatureLimitViolationCount:]
+ -[HAPThermalMetrics setTemperatureLimitViolationDuration:]
+ -[HAPThermalMetrics temperatureLimitViolationCount]
+ -[HAPThermalMetrics temperatureLimitViolationDuration]
+ -[HAPWebRTCOfferOptions SFrameConfiguration]
+ -[HAPWebRTCOfferOptions initWithSFrameEnabled:SFrameConfiguration:]
+ -[HAPWebRTCOfferOptions setSFrameConfiguration:]
+ -[HAPWiFiMetrics .cxx_destruct]
+ -[HAPWiFiMetrics beaconLostCount]
+ -[HAPWiFiMetrics beaconRxCount]
+ -[HAPWiFiMetrics beaconRxInterval]
+ -[HAPWiFiMetrics bssid]
+ -[HAPWiFiMetrics channelNumber]
+ -[HAPWiFiMetrics connectionStatus]
+ -[HAPWiFiMetrics copyWithZone:]
+ -[HAPWiFiMetrics description]
+ -[HAPWiFiMetrics disconnectionCount]
+ -[HAPWiFiMetrics disconnectionDuration]
+ -[HAPWiFiMetrics gatewayIPv4Address]
+ -[HAPWiFiMetrics gatewayIPv6Address]
+ -[HAPWiFiMetrics gatewayMacAddress]
+ -[HAPWiFiMetrics hwExceptionCount]
+ -[HAPWiFiMetrics initWithGatewayMacAddress:gatewayIPv4Address:gatewayIPv6Address:subnetMask:bssid:wifiVersion:channelNumber:rssi:connectionStatus:disconnectionCount:disconnectionDuration:beaconRxCount:beaconRxInterval:beaconLostCount:ipAddressList:packetMulticastRxCount:packetMulticastRxErrorCount:packetMulticastTxCount:packetMulticastTxErrorCount:packetUnicastRxCount:packetUnicastRxErrorCount:packetUnicastTxCount:packetUnicastTxErrorCount:txPacketCount:txPacketErrorCount:rxPacketCount:rxPacketErrorCount:hwExceptionCount:wifiRestartCount:]
+ -[HAPWiFiMetrics init]
+ -[HAPWiFiMetrics ipAddressList]
+ -[HAPWiFiMetrics isEqual:]
+ -[HAPWiFiMetrics packetMulticastRxCount]
+ -[HAPWiFiMetrics packetMulticastRxErrorCount]
+ -[HAPWiFiMetrics packetMulticastTxCount]
+ -[HAPWiFiMetrics packetMulticastTxErrorCount]
+ -[HAPWiFiMetrics packetUnicastRxCount]
+ -[HAPWiFiMetrics packetUnicastRxErrorCount]
+ -[HAPWiFiMetrics packetUnicastTxCount]
+ -[HAPWiFiMetrics packetUnicastTxErrorCount]
+ -[HAPWiFiMetrics parseFromData:error:]
+ -[HAPWiFiMetrics rssi]
+ -[HAPWiFiMetrics rxPacketCount]
+ -[HAPWiFiMetrics rxPacketErrorCount]
+ -[HAPWiFiMetrics serializeWithError:]
+ -[HAPWiFiMetrics setBeaconLostCount:]
+ -[HAPWiFiMetrics setBeaconRxCount:]
+ -[HAPWiFiMetrics setBeaconRxInterval:]
+ -[HAPWiFiMetrics setBssid:]
+ -[HAPWiFiMetrics setChannelNumber:]
+ -[HAPWiFiMetrics setConnectionStatus:]
+ -[HAPWiFiMetrics setDisconnectionCount:]
+ -[HAPWiFiMetrics setDisconnectionDuration:]
+ -[HAPWiFiMetrics setGatewayIPv4Address:]
+ -[HAPWiFiMetrics setGatewayIPv6Address:]
+ -[HAPWiFiMetrics setGatewayMacAddress:]
+ -[HAPWiFiMetrics setHwExceptionCount:]
+ -[HAPWiFiMetrics setIpAddressList:]
+ -[HAPWiFiMetrics setPacketMulticastRxCount:]
+ -[HAPWiFiMetrics setPacketMulticastRxErrorCount:]
+ -[HAPWiFiMetrics setPacketMulticastTxCount:]
+ -[HAPWiFiMetrics setPacketMulticastTxErrorCount:]
+ -[HAPWiFiMetrics setPacketUnicastRxCount:]
+ -[HAPWiFiMetrics setPacketUnicastRxErrorCount:]
+ -[HAPWiFiMetrics setPacketUnicastTxCount:]
+ -[HAPWiFiMetrics setPacketUnicastTxErrorCount:]
+ -[HAPWiFiMetrics setRssi:]
+ -[HAPWiFiMetrics setRxPacketCount:]
+ -[HAPWiFiMetrics setRxPacketErrorCount:]
+ -[HAPWiFiMetrics setSubnetMask:]
+ -[HAPWiFiMetrics setTxPacketCount:]
+ -[HAPWiFiMetrics setTxPacketErrorCount:]
+ -[HAPWiFiMetrics setWifiRestartCount:]
+ -[HAPWiFiMetrics setWifiVersion:]
+ -[HAPWiFiMetrics subnetMask]
+ -[HAPWiFiMetrics txPacketCount]
+ -[HAPWiFiMetrics txPacketErrorCount]
+ -[HAPWiFiMetrics wifiRestartCount]
+ -[HAPWiFiMetrics wifiVersion]
+ -[NSError(HAPError) containsHAPPortUnreachableError]
+ -[_HAPAccessoryServerBTLE200 _ecdsaKeyPairSetupRefusalError]
+ GCC_except_table10019
+ GCC_except_table10097
+ GCC_except_table10099
+ GCC_except_table10101
+ GCC_except_table10103
+ GCC_except_table10105
+ GCC_except_table10107
+ GCC_except_table10109
+ GCC_except_table10115
+ GCC_except_table10117
+ GCC_except_table10120
+ GCC_except_table10122
+ GCC_except_table10124
+ GCC_except_table10131
+ GCC_except_table10137
+ GCC_except_table10142
+ GCC_except_table10145
+ GCC_except_table10150
+ GCC_except_table10155
+ GCC_except_table10158
+ GCC_except_table10161
+ GCC_except_table10187
+ GCC_except_table10190
+ GCC_except_table10191
+ GCC_except_table10230
+ GCC_except_table10231
+ GCC_except_table10232
+ GCC_except_table10234
+ GCC_except_table10235
+ GCC_except_table10237
+ GCC_except_table10238
+ GCC_except_table10239
+ GCC_except_table10241
+ GCC_except_table10242
+ GCC_except_table10244
+ GCC_except_table10248
+ GCC_except_table10249
+ GCC_except_table10253
+ GCC_except_table10304
+ GCC_except_table10311
+ GCC_except_table10419
+ GCC_except_table10421
+ GCC_except_table10423
+ GCC_except_table10426
+ GCC_except_table10428
+ GCC_except_table10430
+ GCC_except_table10432
+ GCC_except_table10433
+ GCC_except_table10440
+ GCC_except_table10442
+ GCC_except_table10443
+ GCC_except_table1131
+ GCC_except_table1133
+ GCC_except_table1200
+ GCC_except_table1202
+ GCC_except_table1204
+ GCC_except_table1206
+ GCC_except_table1746
+ GCC_except_table1753
+ GCC_except_table1767
+ GCC_except_table1779
+ GCC_except_table1781
+ GCC_except_table1783
+ GCC_except_table1785
+ GCC_except_table18
+ GCC_except_table1915
+ GCC_except_table1919
+ GCC_except_table1921
+ GCC_except_table2123
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table2339
+ GCC_except_table2341
+ GCC_except_table2346
+ GCC_except_table2352
+ GCC_except_table2354
+ GCC_except_table2360
+ GCC_except_table2362
+ GCC_except_table2366
+ GCC_except_table2374
+ GCC_except_table2378
+ GCC_except_table2386
+ GCC_except_table2388
+ GCC_except_table2390
+ GCC_except_table2396
+ GCC_except_table240
+ GCC_except_table2400
+ GCC_except_table241
+ GCC_except_table2423
+ GCC_except_table243
+ GCC_except_table2431
+ GCC_except_table2438
+ GCC_except_table2442
+ GCC_except_table2446
+ GCC_except_table2487
+ GCC_except_table249
+ GCC_except_table251
+ GCC_except_table253
+ GCC_except_table254
+ GCC_except_table257
+ GCC_except_table259
+ GCC_except_table2606
+ GCC_except_table2610
+ GCC_except_table2611
+ GCC_except_table2613
+ GCC_except_table2615
+ GCC_except_table2627
+ GCC_except_table2632
+ GCC_except_table2636
+ GCC_except_table2639
+ GCC_except_table2641
+ GCC_except_table2644
+ GCC_except_table2661
+ GCC_except_table2671
+ GCC_except_table2673
+ GCC_except_table2675
+ GCC_except_table268
+ GCC_except_table2680
+ GCC_except_table2683
+ GCC_except_table2685
+ GCC_except_table2688
+ GCC_except_table2691
+ GCC_except_table2695
+ GCC_except_table2697
+ GCC_except_table2700
+ GCC_except_table2703
+ GCC_except_table2705
+ GCC_except_table2707
+ GCC_except_table2711
+ GCC_except_table2715
+ GCC_except_table272
+ GCC_except_table2734
+ GCC_except_table276
+ GCC_except_table2777
+ GCC_except_table2779
+ GCC_except_table278
+ GCC_except_table2781
+ GCC_except_table2782
+ GCC_except_table2783
+ GCC_except_table2785
+ GCC_except_table2789
+ GCC_except_table2816
+ GCC_except_table2820
+ GCC_except_table2824
+ GCC_except_table2988
+ GCC_except_table2995
+ GCC_except_table2999
+ GCC_except_table3003
+ GCC_except_table3007
+ GCC_except_table3010
+ GCC_except_table3012
+ GCC_except_table3014
+ GCC_except_table3017
+ GCC_except_table3023
+ GCC_except_table3025
+ GCC_except_table3028
+ GCC_except_table3029
+ GCC_except_table3031
+ GCC_except_table3132
+ GCC_except_table3140
+ GCC_except_table3141
+ GCC_except_table3142
+ GCC_except_table3143
+ GCC_except_table3144
+ GCC_except_table3145
+ GCC_except_table3160
+ GCC_except_table3254
+ GCC_except_table3471
+ GCC_except_table3480
+ GCC_except_table3497
+ GCC_except_table3531
+ GCC_except_table3547
+ GCC_except_table3549
+ GCC_except_table3561
+ GCC_except_table3568
+ GCC_except_table3590
+ GCC_except_table3604
+ GCC_except_table3605
+ GCC_except_table3606
+ GCC_except_table3609
+ GCC_except_table3615
+ GCC_except_table3622
+ GCC_except_table3625
+ GCC_except_table3630
+ GCC_except_table3635
+ GCC_except_table3640
+ GCC_except_table3680
+ GCC_except_table3697
+ GCC_except_table3700
+ GCC_except_table3705
+ GCC_except_table3707
+ GCC_except_table3723
+ GCC_except_table3739
+ GCC_except_table3743
+ GCC_except_table3751
+ GCC_except_table3759
+ GCC_except_table3823
+ GCC_except_table3830
+ GCC_except_table3833
+ GCC_except_table3856
+ GCC_except_table41
+ GCC_except_table4104
+ GCC_except_table4179
+ GCC_except_table4186
+ GCC_except_table4190
+ GCC_except_table4192
+ GCC_except_table4194
+ GCC_except_table4196
+ GCC_except_table4200
+ GCC_except_table4203
+ GCC_except_table4209
+ GCC_except_table4220
+ GCC_except_table4223
+ GCC_except_table4230
+ GCC_except_table4233
+ GCC_except_table4236
+ GCC_except_table4243
+ GCC_except_table4253
+ GCC_except_table4256
+ GCC_except_table4267
+ GCC_except_table4268
+ GCC_except_table4270
+ GCC_except_table4272
+ GCC_except_table4275
+ GCC_except_table4279
+ GCC_except_table4281
+ GCC_except_table4284
+ GCC_except_table4287
+ GCC_except_table4301
+ GCC_except_table4305
+ GCC_except_table4309
+ GCC_except_table4313
+ GCC_except_table4331
+ GCC_except_table4350
+ GCC_except_table4373
+ GCC_except_table4379
+ GCC_except_table4387
+ GCC_except_table4389
+ GCC_except_table4392
+ GCC_except_table4394
+ GCC_except_table4396
+ GCC_except_table4403
+ GCC_except_table4404
+ GCC_except_table4405
+ GCC_except_table4406
+ GCC_except_table4407
+ GCC_except_table4409
+ GCC_except_table4410
+ GCC_except_table4411
+ GCC_except_table4412
+ GCC_except_table4498
+ GCC_except_table4499
+ GCC_except_table4500
+ GCC_except_table4501
+ GCC_except_table4502
+ GCC_except_table4503
+ GCC_except_table4504
+ GCC_except_table4505
+ GCC_except_table4506
+ GCC_except_table4507
+ GCC_except_table4508
+ GCC_except_table4509
+ GCC_except_table4510
+ GCC_except_table4511
+ GCC_except_table4512
+ GCC_except_table4551
+ GCC_except_table4578
+ GCC_except_table4669
+ GCC_except_table4671
+ GCC_except_table4673
+ GCC_except_table4708
+ GCC_except_table4719
+ GCC_except_table4740
+ GCC_except_table4748
+ GCC_except_table4759
+ GCC_except_table4773
+ GCC_except_table4776
+ GCC_except_table4781
+ GCC_except_table4789
+ GCC_except_table4795
+ GCC_except_table4797
+ GCC_except_table4799
+ GCC_except_table4810
+ GCC_except_table4843
+ GCC_except_table4846
+ GCC_except_table4847
+ GCC_except_table4853
+ GCC_except_table4855
+ GCC_except_table4861
+ GCC_except_table4862
+ GCC_except_table4867
+ GCC_except_table4868
+ GCC_except_table4874
+ GCC_except_table4883
+ GCC_except_table4884
+ GCC_except_table4885
+ GCC_except_table4886
+ GCC_except_table4887
+ GCC_except_table4888
+ GCC_except_table4889
+ GCC_except_table4895
+ GCC_except_table4902
+ GCC_except_table4906
+ GCC_except_table4907
+ GCC_except_table4921
+ GCC_except_table4937
+ GCC_except_table4954
+ GCC_except_table4955
+ GCC_except_table4957
+ GCC_except_table4958
+ GCC_except_table4961
+ GCC_except_table4962
+ GCC_except_table4977
+ GCC_except_table4992
+ GCC_except_table4999
+ GCC_except_table5019
+ GCC_except_table5029
+ GCC_except_table5031
+ GCC_except_table5097
+ GCC_except_table5101
+ GCC_except_table5102
+ GCC_except_table5104
+ GCC_except_table5106
+ GCC_except_table5109
+ GCC_except_table5112
+ GCC_except_table5115
+ GCC_except_table5118
+ GCC_except_table5121
+ GCC_except_table5124
+ GCC_except_table5127
+ GCC_except_table5130
+ GCC_except_table5135
+ GCC_except_table5148
+ GCC_except_table5153
+ GCC_except_table5157
+ GCC_except_table5159
+ GCC_except_table5162
+ GCC_except_table5174
+ GCC_except_table5182
+ GCC_except_table5186
+ GCC_except_table5192
+ GCC_except_table5193
+ GCC_except_table5196
+ GCC_except_table5197
+ GCC_except_table5215
+ GCC_except_table5217
+ GCC_except_table5219
+ GCC_except_table5220
+ GCC_except_table5223
+ GCC_except_table5229
+ GCC_except_table5232
+ GCC_except_table5234
+ GCC_except_table5241
+ GCC_except_table5243
+ GCC_except_table5245
+ GCC_except_table5248
+ GCC_except_table5259
+ GCC_except_table5270
+ GCC_except_table5272
+ GCC_except_table5283
+ GCC_except_table5285
+ GCC_except_table5287
+ GCC_except_table5293
+ GCC_except_table547
+ GCC_except_table557
+ GCC_except_table5575
+ GCC_except_table5581
+ GCC_except_table5598
+ GCC_except_table5602
+ GCC_except_table5620
+ GCC_except_table5626
+ GCC_except_table5640
+ GCC_except_table5654
+ GCC_except_table5658
+ GCC_except_table571
+ GCC_except_table579
+ GCC_except_table5802
+ GCC_except_table608
+ GCC_except_table615
+ GCC_except_table6260
+ GCC_except_table6269
+ GCC_except_table627
+ GCC_except_table6270
+ GCC_except_table628
+ GCC_except_table6280
+ GCC_except_table630
+ GCC_except_table6322
+ GCC_except_table6325
+ GCC_except_table6326
+ GCC_except_table6327
+ GCC_except_table6328
+ GCC_except_table646
+ GCC_except_table648
+ GCC_except_table6493
+ GCC_except_table6494
+ GCC_except_table6495
+ GCC_except_table6496
+ GCC_except_table6497
+ GCC_except_table6498
+ GCC_except_table6499
+ GCC_except_table6500
+ GCC_except_table6502
+ GCC_except_table652
+ GCC_except_table6523
+ GCC_except_table6534
+ GCC_except_table6536
+ GCC_except_table6541
+ GCC_except_table6544
+ GCC_except_table6547
+ GCC_except_table6551
+ GCC_except_table6555
+ GCC_except_table659
+ GCC_except_table662
+ GCC_except_table696
+ GCC_except_table706
+ GCC_except_table7106
+ GCC_except_table7107
+ GCC_except_table7126
+ GCC_except_table7136
+ GCC_except_table7139
+ GCC_except_table714
+ GCC_except_table7144
+ GCC_except_table7147
+ GCC_except_table7152
+ GCC_except_table741
+ GCC_except_table7421
+ GCC_except_table7425
+ GCC_except_table748
+ GCC_except_table7485
+ GCC_except_table7489
+ GCC_except_table7491
+ GCC_except_table7493
+ GCC_except_table750
+ GCC_except_table756
+ GCC_except_table758
+ GCC_except_table7708
+ GCC_except_table771
+ GCC_except_table7716
+ GCC_except_table7718
+ GCC_except_table7720
+ GCC_except_table7722
+ GCC_except_table7728
+ GCC_except_table7741
+ GCC_except_table7759
+ GCC_except_table7765
+ GCC_except_table7779
+ GCC_except_table7783
+ GCC_except_table7788
+ GCC_except_table779
+ GCC_except_table7790
+ GCC_except_table7794
+ GCC_except_table7796
+ GCC_except_table789
+ GCC_except_table7890
+ GCC_except_table7897
+ GCC_except_table7901
+ GCC_except_table7902
+ GCC_except_table7903
+ GCC_except_table7904
+ GCC_except_table7911
+ GCC_except_table7927
+ GCC_except_table795
+ GCC_except_table7962
+ GCC_except_table7963
+ GCC_except_table7964
+ GCC_except_table798
+ GCC_except_table7984
+ GCC_except_table7996
+ GCC_except_table7999
+ GCC_except_table8004
+ GCC_except_table8006
+ GCC_except_table801
+ GCC_except_table806
+ GCC_except_table810
+ GCC_except_table816
+ GCC_except_table817
+ GCC_except_table822
+ GCC_except_table8244
+ GCC_except_table8257
+ GCC_except_table8262
+ GCC_except_table8265
+ GCC_except_table8266
+ GCC_except_table8268
+ GCC_except_table8269
+ GCC_except_table8271
+ GCC_except_table8301
+ GCC_except_table8323
+ GCC_except_table8327
+ GCC_except_table8336
+ GCC_except_table8340
+ GCC_except_table8344
+ GCC_except_table8348
+ GCC_except_table8352
+ GCC_except_table8360
+ GCC_except_table8362
+ GCC_except_table8364
+ GCC_except_table8390
+ GCC_except_table8401
+ GCC_except_table851
+ GCC_except_table8539
+ GCC_except_table8574
+ GCC_except_table858
+ GCC_except_table8664
+ GCC_except_table8665
+ GCC_except_table8666
+ GCC_except_table8667
+ GCC_except_table8668
+ GCC_except_table8669
+ GCC_except_table867
+ GCC_except_table8670
+ GCC_except_table8735
+ GCC_except_table8748
+ GCC_except_table8749
+ GCC_except_table8754
+ GCC_except_table8755
+ GCC_except_table8774
+ GCC_except_table8780
+ GCC_except_table8782
+ GCC_except_table8784
+ GCC_except_table8794
+ GCC_except_table88
+ GCC_except_table8812
+ GCC_except_table8817
+ GCC_except_table8820
+ GCC_except_table8830
+ GCC_except_table8844
+ GCC_except_table8851
+ GCC_except_table8866
+ GCC_except_table8868
+ GCC_except_table8872
+ GCC_except_table8873
+ GCC_except_table8880
+ GCC_except_table8918
+ GCC_except_table8924
+ GCC_except_table8928
+ GCC_except_table8932
+ GCC_except_table8934
+ GCC_except_table8936
+ GCC_except_table8940
+ GCC_except_table895
+ GCC_except_table9059
+ GCC_except_table9154
+ GCC_except_table9157
+ GCC_except_table9164
+ GCC_except_table9170
+ GCC_except_table9177
+ GCC_except_table9178
+ GCC_except_table918
+ GCC_except_table9195
+ GCC_except_table9199
+ GCC_except_table9200
+ GCC_except_table9201
+ GCC_except_table9250
+ GCC_except_table9251
+ GCC_except_table9253
+ GCC_except_table9256
+ GCC_except_table9283
+ GCC_except_table9284
+ GCC_except_table9289
+ GCC_except_table9309
+ GCC_except_table9327
+ GCC_except_table9328
+ GCC_except_table9329
+ GCC_except_table9334
+ GCC_except_table9335
+ GCC_except_table9337
+ GCC_except_table9339
+ GCC_except_table9340
+ GCC_except_table9342
+ GCC_except_table9343
+ GCC_except_table9347
+ GCC_except_table9348
+ GCC_except_table9350
+ GCC_except_table9360
+ GCC_except_table9362
+ GCC_except_table9367
+ GCC_except_table937
+ GCC_except_table9372
+ GCC_except_table9373
+ GCC_except_table9374
+ GCC_except_table9390
+ GCC_except_table9392
+ GCC_except_table9399
+ GCC_except_table9406
+ GCC_except_table9411
+ GCC_except_table9417
+ GCC_except_table9429
+ GCC_except_table9430
+ GCC_except_table9435
+ GCC_except_table9445
+ GCC_except_table9451
+ GCC_except_table9452
+ GCC_except_table9456
+ GCC_except_table9458
+ GCC_except_table9460
+ GCC_except_table9464
+ GCC_except_table9485
+ GCC_except_table9487
+ GCC_except_table9488
+ GCC_except_table9514
+ GCC_except_table961
+ GCC_except_table965
+ GCC_except_table9679
+ GCC_except_table9742
+ GCC_except_table9774
+ GCC_except_table9777
+ GCC_except_table979
+ GCC_except_table984
+ GCC_except_table9944
+ GCC_except_table9982
+ _DNSServiceRefDeallocate
+ _DNSServiceResolve
+ _DNSServiceSetDispatchQueue
+ _HAP2BonjourResolveReply
+ _HAP2CancelResolverAndReportFailure
+ _HAP2CoAPAddressEqualsAddress
+ _HAP2IPv4MappedIPv6BytesFromIPv4Bytes
+ _HAP2PipelineAddressIdentity
+ _HAP2SelectEffectiveList
+ _HAP2SessionKeepAliveSelectedMaxIntervalKey
+ _HAP2SessionKeepAliveSelectedMinIntervalKey
+ _HAP2TakeNextUntriedIP
+ _HAPAVCStreamingControlCommandAsString
+ _HAPAVCStreamingControlStatusAsString
+ _HAPAVCViewerRegistrationOperationAsString
+ _HAPErrorAlreadyPairedPeerIdentifierKey
+ _HAPMetricEventBluetoothVersionTypeAsString
+ _HAPMetricEventPowerSourcesBitmaskAsString
+ _HAPMetricEventPowerSourcesEnumAsString
+ _HAPMetricEventThreadFirstRestartConnectivityStateAsString
+ _HAPMetricEventWiFiFirstRestartConnectivityStateAsString
+ _HAPMetricEventWiFiVersionTypeAsString
+ _HAPNFCIsReaderProtectionError
+ _HAPSessionKeepAliveTransportTypeAsString
+ _HAPStabilityMetricsBootReasonTypeAsString
+ _HAPStabilityMetricsHardwareFaultTypeAsString
+ _HAPWorkQueueFactoryOrDefault
+ _HTTPClientGetSelfAddress
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_HAP2AccessoryAddressLists
+ _OBJC_CLASS_$_HAP2AccessoryAddressResolverPipeline
+ _OBJC_CLASS_$_HAP2AccessoryDNSResolver
+ _OBJC_CLASS_$_HAP2AccessoryServerIPCacheData
+ _OBJC_CLASS_$_HAP2BrowserResolverRegistry
+ _OBJC_CLASS_$_HAP2CoAPRequestRacingLogEvent
+ _OBJC_CLASS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ _OBJC_CLASS_$_HAP2SessionKeepAliveConfiguration
+ _OBJC_CLASS_$_HAP2SessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAP2SessionKeepAliveListener
+ _OBJC_CLASS_$_HAP2SessionKeepAliveTransportState
+ _OBJC_CLASS_$_HAPAVCStreamingControlCommandWrapper
+ _OBJC_CLASS_$_HAPAVCStreamingControlRequest
+ _OBJC_CLASS_$_HAPAVCStreamingControlResponse
+ _OBJC_CLASS_$_HAPAVCStreamingControlStatusWrapper
+ _OBJC_CLASS_$_HAPAVCViewerRegistrationOperationWrapper
+ _OBJC_CLASS_$_HAPAccessoryCHMMetricsLogEvent
+ _OBJC_CLASS_$_HAPAccessoryCHMRecoveryLogEvent
+ _OBJC_CLASS_$_HAPBluetoothMetrics
+ _OBJC_CLASS_$_HAPBootReasonsMetrics
+ _OBJC_CLASS_$_HAPCHMMetrics
+ _OBJC_CLASS_$_HAPConnectionHealthMonitor
+ _OBJC_CLASS_$_HAPContributingSensor
+ _OBJC_CLASS_$_HAPDefaultWorkQueueFactory
+ _OBJC_CLASS_$_HAPErrorCountersMetrics
+ _OBJC_CLASS_$_HAPErrorCountersMetricsEntry
+ _OBJC_CLASS_$_HAPHKSV3UploadLatencyMetrics
+ _OBJC_CLASS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ _OBJC_CLASS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ _OBJC_CLASS_$_HAPMetricEventPowerSourcesEnumWrapper
+ _OBJC_CLASS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ _OBJC_CLASS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ _OBJC_CLASS_$_HAPMetricEventWiFiVersionTypeWrapper
+ _OBJC_CLASS_$_HAPPowerMetrics
+ _OBJC_CLASS_$_HAPSaturationMetrics
+ _OBJC_CLASS_$_HAPSensorList
+ _OBJC_CLASS_$_HAPSessionKeepAliveTransportTypeWrapper
+ _OBJC_CLASS_$_HAPStabilityMetrics
+ _OBJC_CLASS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ _OBJC_CLASS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ _OBJC_CLASS_$_HAPTLVPreferredWiFiEntry
+ _OBJC_CLASS_$_HAPTLVPreferredWiFiList
+ _OBJC_CLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ _OBJC_CLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ _OBJC_CLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ _OBJC_CLASS_$_HAPThermalMetrics
+ _OBJC_CLASS_$_HAPWiFiMetrics
+ _OBJC_CLASS_$_HMFTimerFactory
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_IVAR_$_HAP2AccessoryAddressLists._cachedPrimary
+ _OBJC_IVAR_$_HAP2AccessoryAddressLists._cachedSecondary
+ _OBJC_IVAR_$_HAP2AccessoryAddressLists._primary
+ _OBJC_IVAR_$_HAP2AccessoryAddressLists._secondary
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._cancelled
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._errorHandler
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._gai
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._queue
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._resolvedHostname
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._resolvedPort
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._retainedContext
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._serviceRef
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._updateHandler
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._workingSet
+ _OBJC_IVAR_$_HAP2AccessoryAddressResolverPipeline._workingSetCounts
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._addresses
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._becameEmptyAt
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._cacheSubscriber
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._cachedPrimaryIP
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._cachedSecondaryIP
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._delegates
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._deviceID
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._immediateRetrySpent
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._managerQueue
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineCancel
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineFactory
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineStarted
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._pipelineTornDown
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._propertyLock
+ _OBJC_IVAR_$_HAP2AccessoryDNSResolver._serviceName
+ _OBJC_IVAR_$_HAP2AccessoryDeviceIPAddress._transportType
+ _OBJC_IVAR_$_HAP2AccessoryServer._consecutiveProbeFailures
+ _OBJC_IVAR_$_HAP2AccessoryServer._dnsResolver
+ _OBJC_IVAR_$_HAP2AccessoryServer._hasSeededSinceResolverAttach
+ _OBJC_IVAR_$_HAP2AccessoryServer._hasThreadAdvertisement
+ _OBJC_IVAR_$_HAP2AccessoryServer._hasWiFiAdvertisement
+ _OBJC_IVAR_$_HAP2AccessoryServer._keepAliveListener
+ _OBJC_IVAR_$_HAP2AccessoryServer._lastObservedHasAdvertisement
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._auditScheduler
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._existingPTRs
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._ipCache
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._isInitialCacheRestored
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._pendingRevalidationPTRs
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._resolverRegistry
+ _OBJC_IVAR_$_HAP2AccessoryServerBrowser._revalidationTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerController._lastAnnouncedSessionNumber
+ _OBJC_IVAR_$_HAP2AccessoryServerController._unitTest_useHH2
+ _OBJC_IVAR_$_HAP2AccessoryServerControllerOperation._coapMessageID
+ _OBJC_IVAR_$_HAP2AccessoryServerDiscoveryBonjour._lastKnownAccessoryInfoByServiceKey
+ _OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._cachedPrimaryData
+ _OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._cachedSecondaryData
+ _OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._configurationInfo
+ _OBJC_IVAR_$_HAP2AccessoryServerIPCacheData._deviceID
+ _OBJC_IVAR_$_HAP2AccessoryServerSecureTransportPairVerify._stateChangeGeneration
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsKeepAlive
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsThreadTransport
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportBase._supportsWiFiTransport
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._activeMessageID
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._addressResolverFactory
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._failoverTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasJustCompletedInitialResolve
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasPublishedAdvertisementState
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._hasRegisteredEndpoint
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._helloRetryCount
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._helloRetryTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._inFlightRacingLogEvent
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialCacheGracePeriodTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialConnectionAttemptStartedAt
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._initialResolveCompleted
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastCompletedMessageID
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastMessageID
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastPublishedHasThreadAdvertisement
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._lastPublishedHasWiFiAdvertisement
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._pendingEndpointRegistration
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._pendingIPRefresh
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryEffectiveListIsCacheOnly
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryIPsTriedThisSession
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._primaryOpenInFlight
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolveTimeoutTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolverCancelBlock
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolverRestartTimer
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryAddressList
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryCoAPClient
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryIPsTriedThisSession
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._secondaryOpenInFlight
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._securedClient
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._sendRequestQoS
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._triedIPsLock
+ _OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._tryingInitialCacheOnly
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._browser
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._managerQueue
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._name
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._pipelineFactory
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._propertyLock
+ _OBJC_IVAR_$_HAP2BrowserResolverRegistry._resolversByDeviceID
+ _OBJC_IVAR_$_HAP2CoAPClient._pendingProbeCompletion
+ _OBJC_IVAR_$_HAP2CoAPClient._pendingProbeMessageID
+ _OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._maximumInterval
+ _OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._minimumInterval
+ _OBJC_IVAR_$_HAP2SessionKeepAliveConfigurationEntry._transportType
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._dateProvider
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._delegateLock
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._delegates
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._isRunning
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._missCheckTimer
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._timerProvider
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._transportStates
+ _OBJC_IVAR_$_HAP2SessionKeepAliveListener._workQueue
+ _OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._hasMissedHeartbeat
+ _OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._lastHeartbeatTime
+ _OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._maximumInterval
+ _OBJC_IVAR_$_HAP2SessionKeepAliveTransportState._transportType
+ _OBJC_IVAR_$_HAPAVCStreamingControlCommandWrapper._value
+ _OBJC_IVAR_$_HAPAVCStreamingControlRequest._command
+ _OBJC_IVAR_$_HAPAVCStreamingControlRequest._sessionIdentifier
+ _OBJC_IVAR_$_HAPAVCStreamingControlResponse._sessionIdentifier
+ _OBJC_IVAR_$_HAPAVCStreamingControlResponse._status
+ _OBJC_IVAR_$_HAPAVCStreamingControlStatusWrapper._value
+ _OBJC_IVAR_$_HAPAVCViewerRegistrationOperationWrapper._value
+ _OBJC_IVAR_$_HAPAVCViewerRegistrationRequest._operation
+ _OBJC_IVAR_$_HAPAccessoryPairingRequest._shouldAllowECDSAKeyPairSetup
+ _OBJC_IVAR_$_HAPAccessoryServer._hasThreadAdvertisement
+ _OBJC_IVAR_$_HAPAccessoryServer._hasWiFiAdvertisement
+ _OBJC_IVAR_$_HAPAccessoryServer._lastPairSetupWasSpake2
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupLastError
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4Completed
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4DurationMS
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM1ToM4Error
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6Completed
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6DurationMS
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupM5ToM6Error
+ _OBJC_IVAR_$_HAPAccessoryServer._pairSetupWorkDurationMS
+ _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthCompleted
+ _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthDurationMS
+ _OBJC_IVAR_$_HAPAccessoryServer._tokenAuthError
+ _OBJC_IVAR_$_HAPAccessoryServer._workQueueFactory
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._denylisted
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._nfcM4RecvTime
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._tokenAuthEndTime
+ _OBJC_IVAR_$_HAPAccessoryServerNFC._tokenAuthStartTime
+ _OBJC_IVAR_$_HAPBluetoothMetrics._bluetoothVersion
+ _OBJC_IVAR_$_HAPBluetoothMetrics._connectionCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._connectionErrorCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._connectionStatus
+ _OBJC_IVAR_$_HAPBluetoothMetrics._disconnectionCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._disconnectionErrorCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._hwExceptionCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._overrunCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._packetRxCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._packetRxErrorCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._packetTxCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._packetTxErrorCount
+ _OBJC_IVAR_$_HAPBluetoothMetrics._rssi
+ _OBJC_IVAR_$_HAPBluetoothMetrics._txPowerLevel
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._brownOutResetBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._connectivityMonitorBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._hardwareFaultBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._hardwareWatchdogResetBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._heapOverflowBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._powerOnBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._softwareExceptionBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._softwareResetBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._softwareUpdateCompletedBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._softwareWatchdogResetBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._stackOverflowBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._temperatureLimitBootCount
+ _OBJC_IVAR_$_HAPBootReasonsMetrics._unspecifiedBootCount
+ _OBJC_IVAR_$_HAPCHMMetrics._chmAccessoryRebootCompleted
+ _OBJC_IVAR_$_HAPCHMMetrics._chmAccessoryRebootDurationToRecovery
+ _OBJC_IVAR_$_HAPCHMMetrics._hapSessionLossCount
+ _OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartCompleted
+ _OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartConnectivityState
+ _OBJC_IVAR_$_HAPCHMMetrics._threadFirstRestartRecoveryTime
+ _OBJC_IVAR_$_HAPCHMMetrics._threadRecoveryAttemptCount
+ _OBJC_IVAR_$_HAPCHMMetrics._threadRestartCount
+ _OBJC_IVAR_$_HAPCHMMetrics._threadTransportLossCount
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartCompleted
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartConnectivityState
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiFirstRestartRecoveryTime
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiRecoveryAttemptCount
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiRestartCount
+ _OBJC_IVAR_$_HAPCHMMetrics._wifiTransportLossCount
+ _OBJC_IVAR_$_HAPCharacteristicResponseTuple._coapMessageID
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._deviceRebootDelay
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._deviceRebootEnable
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._recoveryStaggerDelay
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._threadPingTestCount
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._threadPingTestInterval
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._threadRecoveryConfiguration
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._threadRestartMinInterval
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiPingTestCount
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiPingTestInterval
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiRecoveryConfiguration
+ _OBJC_IVAR_$_HAPConnectionHealthMonitor._wiFiRestartMinInterval
+ _OBJC_IVAR_$_HAPContributingSensor._sensorUUID
+ _OBJC_IVAR_$_HAPErrorCountersMetrics._entries
+ _OBJC_IVAR_$_HAPErrorCountersMetricsEntry._count
+ _OBJC_IVAR_$_HAPErrorCountersMetricsEntry._errorID
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._abandonedRequestCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._audioOnlyFailureCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._authenticationErrorCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentFailureCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentRetriedCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._fragmentSuccessCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount1000ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount2000ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount250ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount3750ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCount500ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._latencyCountOver3750ms
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._localErrorCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._networkErrorCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._partialSuccessCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._playlistFailureCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._serverReturnedErrorCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._sessionFailureCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._sessionSuccessCount
+ _OBJC_IVAR_$_HAPHKSV3UploadLatencyMetrics._uploadWithoutResidentResponseCount
+ _OBJC_IVAR_$_HAPKeyBag._cachedAccessoryKeyType
+ _OBJC_IVAR_$_HAPMetricEventBluetoothVersionTypeWrapper._value
+ _OBJC_IVAR_$_HAPMetricEventPowerSourcesBitmaskWrapper._value
+ _OBJC_IVAR_$_HAPMetricEventPowerSourcesEnumWrapper._value
+ _OBJC_IVAR_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper._value
+ _OBJC_IVAR_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper._value
+ _OBJC_IVAR_$_HAPMetricEventWiFiVersionTypeWrapper._value
+ _OBJC_IVAR_$_HAPPowerMetrics._batteryPercentage
+ _OBJC_IVAR_$_HAPPowerMetrics._currentPowerSource
+ _OBJC_IVAR_$_HAPPowerMetrics._durationOnBatteryPower
+ _OBJC_IVAR_$_HAPPowerMetrics._durationRemainingOnBatteryPower
+ _OBJC_IVAR_$_HAPPowerMetrics._supportedPowerSources
+ _OBJC_IVAR_$_HAPSaturationMetrics._averageCPUUtilization
+ _OBJC_IVAR_$_HAPSaturationMetrics._averageSystemMemoryUtilization
+ _OBJC_IVAR_$_HAPSaturationMetrics._heapHighwaterCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._heapOverflowCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._lastHeapHighwaterTaskName
+ _OBJC_IVAR_$_HAPSaturationMetrics._lastHeapOverflowTaskName
+ _OBJC_IVAR_$_HAPSaturationMetrics._lastProcessCriticalMemoryName
+ _OBJC_IVAR_$_HAPSaturationMetrics._lastStackHighwaterTaskName
+ _OBJC_IVAR_$_HAPSaturationMetrics._lastStackOverflowTaskName
+ _OBJC_IVAR_$_HAPSaturationMetrics._loadAverage
+ _OBJC_IVAR_$_HAPSaturationMetrics._maxTaskReadyQueueSize
+ _OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryReadCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryReadErrorCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryUtilization
+ _OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryWriteCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._nonVolatileMemoryWriteErrorCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._peakCPUUtilization
+ _OBJC_IVAR_$_HAPSaturationMetrics._peakSystemMemoryUtilization
+ _OBJC_IVAR_$_HAPSaturationMetrics._processCriticalMemoryCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._stackHighwaterCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._stackOverflowCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._systemMemoryPressureCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._taskDeadlineMissCount
+ _OBJC_IVAR_$_HAPSaturationMetrics._totalTasksScheduledCount
+ _OBJC_IVAR_$_HAPSecuritySession._foreignPairVerifySession
+ _OBJC_IVAR_$_HAPSensorList._contributingSensor
+ _OBJC_IVAR_$_HAPSessionKeepAliveTransportTypeWrapper._value
+ _OBJC_IVAR_$_HAPStabilityMetrics._activeHardwareFaults
+ _OBJC_IVAR_$_HAPStabilityMetrics._expectedBootCount
+ _OBJC_IVAR_$_HAPStabilityMetrics._lastBootReason
+ _OBJC_IVAR_$_HAPStabilityMetrics._systemBootCount
+ _OBJC_IVAR_$_HAPStabilityMetrics._systemCrashCount
+ _OBJC_IVAR_$_HAPStabilityMetrics._systemHangCount
+ _OBJC_IVAR_$_HAPStabilityMetrics._systemUptime
+ _OBJC_IVAR_$_HAPStabilityMetricsBootReasonTypeWrapper._value
+ _OBJC_IVAR_$_HAPStabilityMetricsHardwareFaultTypeWrapper._value
+ _OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._PSK
+ _OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._SSID
+ _OBJC_IVAR_$_HAPTLVPreferredWiFiEntry._securityMode
+ _OBJC_IVAR_$_HAPTLVPreferredWiFiList._preferredWiFiList
+ _OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._maximumInterval
+ _OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._minimumInterval
+ _OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry._transportType
+ _OBJC_IVAR_$_HAPTLVSelectedSessionKeepAliveConfigurationList._entries
+ _OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._maximumInterval
+ _OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._minimumInterval
+ _OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._minimumRange
+ _OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry._transportType
+ _OBJC_IVAR_$_HAPTLVSupportedSessionKeepAliveConfigurationList._entries
+ _OBJC_IVAR_$_HAPThermalMetrics._averageDeviceTemperature
+ _OBJC_IVAR_$_HAPThermalMetrics._maximumDeviceTemperature
+ _OBJC_IVAR_$_HAPThermalMetrics._minimumDeviceTemperature
+ _OBJC_IVAR_$_HAPThermalMetrics._temperatureLimitViolationCount
+ _OBJC_IVAR_$_HAPThermalMetrics._temperatureLimitViolationDuration
+ _OBJC_IVAR_$_HAPWebRTCOfferOptions._SFrameConfiguration
+ _OBJC_IVAR_$_HAPWiFiMetrics._beaconLostCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._beaconRxCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._beaconRxInterval
+ _OBJC_IVAR_$_HAPWiFiMetrics._bssid
+ _OBJC_IVAR_$_HAPWiFiMetrics._channelNumber
+ _OBJC_IVAR_$_HAPWiFiMetrics._connectionStatus
+ _OBJC_IVAR_$_HAPWiFiMetrics._disconnectionCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._disconnectionDuration
+ _OBJC_IVAR_$_HAPWiFiMetrics._gatewayIPv4Address
+ _OBJC_IVAR_$_HAPWiFiMetrics._gatewayIPv6Address
+ _OBJC_IVAR_$_HAPWiFiMetrics._gatewayMacAddress
+ _OBJC_IVAR_$_HAPWiFiMetrics._hwExceptionCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._ipAddressList
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastRxCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastRxErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastTxCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetMulticastTxErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastRxCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastRxErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastTxCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._packetUnicastTxErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._rssi
+ _OBJC_IVAR_$_HAPWiFiMetrics._rxPacketCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._rxPacketErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._subnetMask
+ _OBJC_IVAR_$_HAPWiFiMetrics._txPacketCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._txPacketErrorCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._wifiRestartCount
+ _OBJC_IVAR_$_HAPWiFiMetrics._wifiVersion
+ _OBJC_METACLASS_$_HAP2AccessoryAddressLists
+ _OBJC_METACLASS_$_HAP2AccessoryAddressResolverPipeline
+ _OBJC_METACLASS_$_HAP2AccessoryDNSResolver
+ _OBJC_METACLASS_$_HAP2AccessoryServerIPCacheData
+ _OBJC_METACLASS_$_HAP2BrowserResolverRegistry
+ _OBJC_METACLASS_$_HAP2CoAPRequestRacingLogEvent
+ _OBJC_METACLASS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveConfiguration
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveListener
+ _OBJC_METACLASS_$_HAP2SessionKeepAliveTransportState
+ _OBJC_METACLASS_$_HAPAVCStreamingControlCommandWrapper
+ _OBJC_METACLASS_$_HAPAVCStreamingControlRequest
+ _OBJC_METACLASS_$_HAPAVCStreamingControlResponse
+ _OBJC_METACLASS_$_HAPAVCStreamingControlStatusWrapper
+ _OBJC_METACLASS_$_HAPAVCViewerRegistrationOperationWrapper
+ _OBJC_METACLASS_$_HAPAccessoryCHMMetricsLogEvent
+ _OBJC_METACLASS_$_HAPAccessoryCHMRecoveryLogEvent
+ _OBJC_METACLASS_$_HAPBluetoothMetrics
+ _OBJC_METACLASS_$_HAPBootReasonsMetrics
+ _OBJC_METACLASS_$_HAPCHMMetrics
+ _OBJC_METACLASS_$_HAPConnectionHealthMonitor
+ _OBJC_METACLASS_$_HAPContributingSensor
+ _OBJC_METACLASS_$_HAPDefaultWorkQueueFactory
+ _OBJC_METACLASS_$_HAPErrorCountersMetrics
+ _OBJC_METACLASS_$_HAPErrorCountersMetricsEntry
+ _OBJC_METACLASS_$_HAPHKSV3UploadLatencyMetrics
+ _OBJC_METACLASS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ _OBJC_METACLASS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ _OBJC_METACLASS_$_HAPMetricEventPowerSourcesEnumWrapper
+ _OBJC_METACLASS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ _OBJC_METACLASS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ _OBJC_METACLASS_$_HAPMetricEventWiFiVersionTypeWrapper
+ _OBJC_METACLASS_$_HAPPowerMetrics
+ _OBJC_METACLASS_$_HAPSaturationMetrics
+ _OBJC_METACLASS_$_HAPSensorList
+ _OBJC_METACLASS_$_HAPSessionKeepAliveTransportTypeWrapper
+ _OBJC_METACLASS_$_HAPStabilityMetrics
+ _OBJC_METACLASS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ _OBJC_METACLASS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ _OBJC_METACLASS_$_HAPTLVPreferredWiFiEntry
+ _OBJC_METACLASS_$_HAPTLVPreferredWiFiList
+ _OBJC_METACLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ _OBJC_METACLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ _OBJC_METACLASS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ _OBJC_METACLASS_$_HAPThermalMetrics
+ _OBJC_METACLASS_$_HAPWiFiMetrics
+ __DATA_HAP2CoAPRequestRacingLogEvent
+ __DATA_HAPAccessoryCHMMetricsLogEvent
+ __DATA_HAPAccessoryCHMRecoveryLogEvent
+ __INSTANCE_METHODS_HAP2CoAPRequestRacingLogEvent
+ __INSTANCE_METHODS_HAPAccessoryCHMMetricsLogEvent
+ __INSTANCE_METHODS_HAPAccessoryCHMRecoveryLogEvent
+ __IVARS_HAP2CoAPRequestRacingLogEvent
+ __IVARS_HAPAccessoryCHMMetricsLogEvent
+ __IVARS_HAPAccessoryCHMRecoveryLogEvent
+ __METACLASS_DATA_HAP2CoAPRequestRacingLogEvent
+ __METACLASS_DATA_HAPAccessoryCHMMetricsLogEvent
+ __METACLASS_DATA_HAPAccessoryCHMRecoveryLogEvent
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryDeviceIPAddress
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerCoordinator(Test)
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerDiscoveryHAPAccessoryInfo
+ __OBJC_$_CLASS_METHODS_HAP2AccessoryServerIPCacheData
+ __OBJC_$_CLASS_METHODS_HAP2SessionKeepAliveConfiguration
+ __OBJC_$_CLASS_METHODS_HAPAVCStreamingControlCommandWrapper
+ __OBJC_$_CLASS_METHODS_HAPAVCStreamingControlRequest
+ __OBJC_$_CLASS_METHODS_HAPAVCStreamingControlResponse
+ __OBJC_$_CLASS_METHODS_HAPAVCStreamingControlStatusWrapper
+ __OBJC_$_CLASS_METHODS_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_$_CLASS_METHODS_HAPBluetoothMetrics
+ __OBJC_$_CLASS_METHODS_HAPBootReasonsMetrics
+ __OBJC_$_CLASS_METHODS_HAPCHMMetrics
+ __OBJC_$_CLASS_METHODS_HAPConnectionHealthMonitor
+ __OBJC_$_CLASS_METHODS_HAPContributingSensor
+ __OBJC_$_CLASS_METHODS_HAPDefaultWorkQueueFactory
+ __OBJC_$_CLASS_METHODS_HAPErrorCountersMetrics
+ __OBJC_$_CLASS_METHODS_HAPErrorCountersMetricsEntry
+ __OBJC_$_CLASS_METHODS_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_CLASS_METHODS_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_CLASS_METHODS_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPPowerMetrics
+ __OBJC_$_CLASS_METHODS_HAPSaturationMetrics
+ __OBJC_$_CLASS_METHODS_HAPSensorList
+ __OBJC_$_CLASS_METHODS_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetrics
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_CLASS_METHODS_HAPTLVPreferredWiFiEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVPreferredWiFiList
+ __OBJC_$_CLASS_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_CLASS_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_CLASS_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_CLASS_METHODS_HAPThermalMetrics
+ __OBJC_$_CLASS_METHODS_HAPWiFiMetrics
+ __OBJC_$_CLASS_PROP_LIST_HAPDefaultWorkQueueFactory
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryAddressLists
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryDNSResolver
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServer(Test|Paired|PairedInternal|Unpaired)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerBrowser(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerCoordinator(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerIPCacheData
+ __OBJC_$_INSTANCE_METHODS_HAP2BrowserResolverRegistry(Test)
+ __OBJC_$_INSTANCE_METHODS_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveListener
+ __OBJC_$_INSTANCE_METHODS_HAP2SessionKeepAliveTransportState
+ __OBJC_$_INSTANCE_METHODS_HAPAVCStreamingControlCommandWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPAVCStreamingControlRequest
+ __OBJC_$_INSTANCE_METHODS_HAPAVCStreamingControlResponse
+ __OBJC_$_INSTANCE_METHODS_HAPAVCStreamingControlStatusWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPBluetoothMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPBootReasonsMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPCHMMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPConnectionHealthMonitor
+ __OBJC_$_INSTANCE_METHODS_HAPContributingSensor
+ __OBJC_$_INSTANCE_METHODS_HAPDefaultWorkQueueFactory
+ __OBJC_$_INSTANCE_METHODS_HAPErrorCountersMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPErrorCountersMetricsEntry
+ __OBJC_$_INSTANCE_METHODS_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPPowerMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPSaturationMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPSensorList
+ __OBJC_$_INSTANCE_METHODS_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_INSTANCE_METHODS_HAPTLVPreferredWiFiEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVPreferredWiFiList
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_METHODS_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_METHODS_HAPThermalMetrics
+ __OBJC_$_INSTANCE_METHODS_HAPWiFiMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryAddressLists
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryDNSResolver
+ __OBJC_$_INSTANCE_VARIABLES_HAP2AccessoryServerIPCacheData
+ __OBJC_$_INSTANCE_VARIABLES_HAP2BrowserResolverRegistry
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveListener
+ __OBJC_$_INSTANCE_VARIABLES_HAP2SessionKeepAliveTransportState
+ __OBJC_$_INSTANCE_VARIABLES_HAPAVCStreamingControlCommandWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPAVCStreamingControlRequest
+ __OBJC_$_INSTANCE_VARIABLES_HAPAVCStreamingControlResponse
+ __OBJC_$_INSTANCE_VARIABLES_HAPAVCStreamingControlStatusWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPBluetoothMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPBootReasonsMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPCHMMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPConnectionHealthMonitor
+ __OBJC_$_INSTANCE_VARIABLES_HAPContributingSensor
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorCountersMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPErrorCountersMetricsEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPPowerMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPSaturationMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPSensorList
+ __OBJC_$_INSTANCE_VARIABLES_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVPreferredWiFiEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVPreferredWiFiList
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_INSTANCE_VARIABLES_HAPThermalMetrics
+ __OBJC_$_INSTANCE_VARIABLES_HAPWiFiMetrics
+ __OBJC_$_PROP_LIST_HAP2AccessoryAddressLists
+ __OBJC_$_PROP_LIST_HAP2AccessoryAddressResolverPipeline
+ __OBJC_$_PROP_LIST_HAP2AccessoryDNSResolver
+ __OBJC_$_PROP_LIST_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROP_LIST_HAP2AccessoryServerIPCacheData
+ __OBJC_$_PROP_LIST_HAP2BrowserResolverRegistry
+ __OBJC_$_PROP_LIST_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROP_LIST_HAP2PairedAccessoryServerPrivate
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveListener
+ __OBJC_$_PROP_LIST_HAP2SessionKeepAliveTransportState
+ __OBJC_$_PROP_LIST_HAPAVCStreamingControlCommandWrapper
+ __OBJC_$_PROP_LIST_HAPAVCStreamingControlRequest
+ __OBJC_$_PROP_LIST_HAPAVCStreamingControlResponse
+ __OBJC_$_PROP_LIST_HAPAVCStreamingControlStatusWrapper
+ __OBJC_$_PROP_LIST_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_$_PROP_LIST_HAPBluetoothMetrics
+ __OBJC_$_PROP_LIST_HAPBootReasonsMetrics
+ __OBJC_$_PROP_LIST_HAPCHMMetrics
+ __OBJC_$_PROP_LIST_HAPConnectionHealthMonitor
+ __OBJC_$_PROP_LIST_HAPContributingSensor
+ __OBJC_$_PROP_LIST_HAPDefaultWorkQueueFactory
+ __OBJC_$_PROP_LIST_HAPErrorCountersMetrics
+ __OBJC_$_PROP_LIST_HAPErrorCountersMetricsEntry
+ __OBJC_$_PROP_LIST_HAPHKSV3UploadLatencyMetrics
+ __OBJC_$_PROP_LIST_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_$_PROP_LIST_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_$_PROP_LIST_HAPNFCReaderSessionProtocol
+ __OBJC_$_PROP_LIST_HAPPowerMetrics
+ __OBJC_$_PROP_LIST_HAPSaturationMetrics
+ __OBJC_$_PROP_LIST_HAPSensorList
+ __OBJC_$_PROP_LIST_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_$_PROP_LIST_HAPStabilityMetrics
+ __OBJC_$_PROP_LIST_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_$_PROP_LIST_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_$_PROP_LIST_HAPTLVPreferredWiFiEntry
+ __OBJC_$_PROP_LIST_HAPTLVPreferredWiFiList
+ __OBJC_$_PROP_LIST_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_$_PROP_LIST_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_$_PROP_LIST_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_$_PROP_LIST_HAPThermalMetrics
+ __OBJC_$_PROP_LIST_HAPWiFiMetrics
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAPNFCReaderSessionProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HAPWorkQueueFactory
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAP2AccessoryServerSecureTransportDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HAP2AccessoryServerTransportDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAPNFCReaderSessionProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HAPWorkQueueFactory
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolver
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverDelegate
+ __OBJC_$_PROTOCOL_REFS_HAP2AccessoryDNSResolverPrivate
+ __OBJC_$_PROTOCOL_REFS_HAPNFCReaderSessionProtocol
+ __OBJC_$_PROTOCOL_REFS_HAPWorkQueueFactory
+ __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryDNSResolver
+ __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryDeviceIPAddress
+ __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryServer(Test|Paired|PairedInternal|Unpaired)
+ __OBJC_CLASS_PROTOCOLS_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_CLASS_PROTOCOLS_$_HAP2SessionKeepAliveListener
+ __OBJC_CLASS_PROTOCOLS_$_HAPAVCStreamingControlCommandWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPAVCStreamingControlRequest
+ __OBJC_CLASS_PROTOCOLS_$_HAPAVCStreamingControlResponse
+ __OBJC_CLASS_PROTOCOLS_$_HAPAVCStreamingControlStatusWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPBluetoothMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPBootReasonsMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPCHMMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPConnectionHealthMonitor
+ __OBJC_CLASS_PROTOCOLS_$_HAPContributingSensor
+ __OBJC_CLASS_PROTOCOLS_$_HAPDefaultWorkQueueFactory
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorCountersMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPErrorCountersMetricsEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPPowerMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPSaturationMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPSensorList
+ __OBJC_CLASS_PROTOCOLS_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVPreferredWiFiEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVPreferredWiFiList
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_PROTOCOLS_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_PROTOCOLS_$_HAPThermalMetrics
+ __OBJC_CLASS_PROTOCOLS_$_HAPWiFiMetrics
+ __OBJC_CLASS_RO_$_HAP2AccessoryAddressLists
+ __OBJC_CLASS_RO_$_HAP2AccessoryAddressResolverPipeline
+ __OBJC_CLASS_RO_$_HAP2AccessoryDNSResolver
+ __OBJC_CLASS_RO_$_HAP2AccessoryServerIPCacheData
+ __OBJC_CLASS_RO_$_HAP2BrowserResolverRegistry
+ __OBJC_CLASS_RO_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveConfiguration
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveListener
+ __OBJC_CLASS_RO_$_HAP2SessionKeepAliveTransportState
+ __OBJC_CLASS_RO_$_HAPAVCStreamingControlCommandWrapper
+ __OBJC_CLASS_RO_$_HAPAVCStreamingControlRequest
+ __OBJC_CLASS_RO_$_HAPAVCStreamingControlResponse
+ __OBJC_CLASS_RO_$_HAPAVCStreamingControlStatusWrapper
+ __OBJC_CLASS_RO_$_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_CLASS_RO_$_HAPBluetoothMetrics
+ __OBJC_CLASS_RO_$_HAPBootReasonsMetrics
+ __OBJC_CLASS_RO_$_HAPCHMMetrics
+ __OBJC_CLASS_RO_$_HAPConnectionHealthMonitor
+ __OBJC_CLASS_RO_$_HAPContributingSensor
+ __OBJC_CLASS_RO_$_HAPDefaultWorkQueueFactory
+ __OBJC_CLASS_RO_$_HAPErrorCountersMetrics
+ __OBJC_CLASS_RO_$_HAPErrorCountersMetricsEntry
+ __OBJC_CLASS_RO_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_CLASS_RO_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_CLASS_RO_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_CLASS_RO_$_HAPPowerMetrics
+ __OBJC_CLASS_RO_$_HAPSaturationMetrics
+ __OBJC_CLASS_RO_$_HAPSensorList
+ __OBJC_CLASS_RO_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_CLASS_RO_$_HAPStabilityMetrics
+ __OBJC_CLASS_RO_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_CLASS_RO_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_CLASS_RO_$_HAPTLVPreferredWiFiEntry
+ __OBJC_CLASS_RO_$_HAPTLVPreferredWiFiList
+ __OBJC_CLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_CLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_CLASS_RO_$_HAPThermalMetrics
+ __OBJC_CLASS_RO_$_HAPWiFiMetrics
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolver
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverDelegate
+ __OBJC_LABEL_PROTOCOL_$_HAP2AccessoryDNSResolverPrivate
+ __OBJC_LABEL_PROTOCOL_$_HAPNFCReaderSessionProtocol
+ __OBJC_LABEL_PROTOCOL_$_HAPWorkQueueFactory
+ __OBJC_METACLASS_RO_$_HAP2AccessoryAddressLists
+ __OBJC_METACLASS_RO_$_HAP2AccessoryAddressResolverPipeline
+ __OBJC_METACLASS_RO_$_HAP2AccessoryDNSResolver
+ __OBJC_METACLASS_RO_$_HAP2AccessoryServerIPCacheData
+ __OBJC_METACLASS_RO_$_HAP2BrowserResolverRegistry
+ __OBJC_METACLASS_RO_$_HAP2DefaultAccessoryAddressResolverPipelineFactory
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveConfiguration
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveListener
+ __OBJC_METACLASS_RO_$_HAP2SessionKeepAliveTransportState
+ __OBJC_METACLASS_RO_$_HAPAVCStreamingControlCommandWrapper
+ __OBJC_METACLASS_RO_$_HAPAVCStreamingControlRequest
+ __OBJC_METACLASS_RO_$_HAPAVCStreamingControlResponse
+ __OBJC_METACLASS_RO_$_HAPAVCStreamingControlStatusWrapper
+ __OBJC_METACLASS_RO_$_HAPAVCViewerRegistrationOperationWrapper
+ __OBJC_METACLASS_RO_$_HAPBluetoothMetrics
+ __OBJC_METACLASS_RO_$_HAPBootReasonsMetrics
+ __OBJC_METACLASS_RO_$_HAPCHMMetrics
+ __OBJC_METACLASS_RO_$_HAPConnectionHealthMonitor
+ __OBJC_METACLASS_RO_$_HAPContributingSensor
+ __OBJC_METACLASS_RO_$_HAPDefaultWorkQueueFactory
+ __OBJC_METACLASS_RO_$_HAPErrorCountersMetrics
+ __OBJC_METACLASS_RO_$_HAPErrorCountersMetricsEntry
+ __OBJC_METACLASS_RO_$_HAPHKSV3UploadLatencyMetrics
+ __OBJC_METACLASS_RO_$_HAPMetricEventBluetoothVersionTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventPowerSourcesBitmaskWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventPowerSourcesEnumWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventThreadFirstRestartConnectivityStateWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventWiFiFirstRestartConnectivityStateWrapper
+ __OBJC_METACLASS_RO_$_HAPMetricEventWiFiVersionTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPPowerMetrics
+ __OBJC_METACLASS_RO_$_HAPSaturationMetrics
+ __OBJC_METACLASS_RO_$_HAPSensorList
+ __OBJC_METACLASS_RO_$_HAPSessionKeepAliveTransportTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPStabilityMetrics
+ __OBJC_METACLASS_RO_$_HAPStabilityMetricsBootReasonTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPStabilityMetricsHardwareFaultTypeWrapper
+ __OBJC_METACLASS_RO_$_HAPTLVPreferredWiFiEntry
+ __OBJC_METACLASS_RO_$_HAPTLVPreferredWiFiList
+ __OBJC_METACLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAPTLVSelectedSessionKeepAliveConfigurationList
+ __OBJC_METACLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationEntry
+ __OBJC_METACLASS_RO_$_HAPTLVSupportedSessionKeepAliveConfigurationList
+ __OBJC_METACLASS_RO_$_HAPThermalMetrics
+ __OBJC_METACLASS_RO_$_HAPWiFiMetrics
+ __OBJC_PROTOCOL_$_HAP2AccessoryAddressResolverPipelineFactory
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolver
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverCacheSubscriber
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverDelegate
+ __OBJC_PROTOCOL_$_HAP2AccessoryDNSResolverPrivate
+ __OBJC_PROTOCOL_$_HAPNFCReaderSessionProtocol
+ __OBJC_PROTOCOL_$_HAPWorkQueueFactory
+ __OBJC_PROTOCOL_REFERENCE_$_HAP2AccessoryDNSResolverPrivate
+ __PROPERTIES_HAP2CoAPRequestRacingLogEvent
+ __PROPERTIES_HAPAccessoryCHMMetricsLogEvent
+ __PROPERTIES_HAPAccessoryCHMRecoveryLogEvent
+ __PROTOCOLS_HAPAccessoryCHMMetricsLogEvent
+ __PROTOCOLS_HAPAccessoryCHMRecoveryLogEvent
+ __ZL10_cacheLock
+ __ZL11_cacheValid
+ __ZL11_eventQueue
+ __ZL11_generation
+ __ZL19_sharedThreadClient
+ __ZL20_eventQueueOnceToken
+ __ZL22_cachedMeshLocalPrefix
+ __ZL22_sharedClientOnceToken
+ __ZL24_lastInstalledNCPHandler
+ __ZL30_lastInstalledPreferredHandler
+ __ZNK6CtrXPC5Event7getNameEv
+ __ZdlPv
+ __ZnwmSt19__type_descriptor_t
+ ___101-[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidFailOnIPAddress:transportType:error:]_block_invoke
+ ___107-[HAP2AccessoryServerTransportCoAP _sendRacingRequest:path:method:messageID:primaryClient:secondaryClient:]_block_invoke
+ ___139-[HAP2AccessoryServerTransportCoAP _executeRacingWithRequest:path:method:messageID:primaryClient:secondaryClient:failoverTimeout:rttStats:]_block_invoke
+ ___143-[HAP2DefaultAccessoryAddressResolverPipelineFactory createResolverWithServiceName:serviceType:serviceDomain:queue:updateHandler:errorHandler:]_block_invoke
+ ___145-[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]_block_invoke
+ ___145-[HAP2AccessoryServer(PairedInternal) keepAliveListener:didMissHeartbeatOnTransport:expectedInterval:timeSinceLastHeartbeat:allTransportsMissed:]_block_invoke_2
+ ___36+[HAP2ThreadNetworkUtil _eventQueue]_block_invoke
+ ___36-[HAP2SessionKeepAliveListener stop]_block_invoke
+ ___37-[HAP2AccessoryServerBrowser ipCache]_block_invoke
+ ___37-[HAP2SessionKeepAliveListener start]_block_invoke
+ ___39-[HAP2AccessoryDNSResolver serviceName]_block_invoke
+ ___40-[HAP2AccessoryDNSResolver stopPipeline]_block_invoke
+ ___41-[HAP2AccessoryDNSResolver becameEmptyAt]_block_invoke
+ ___41-[HAP2AccessoryDNSResolver startPipeline]_block_invoke
+ ___41-[HAP2AccessoryServerBrowser currentPTRs]_block_invoke
+ ___41-[HAP2AccessoryServerBrowser setIPCache:]_block_invoke
+ ___42-[HAP2CoAPClient _didDisconnectWithError:]_block_invoke
+ ___42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke
+ ___42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke_2
+ ___42-[HAP2CoAPClient sendProbeWithCompletion:]_block_invoke_3
+ ___43+[HAPDefaultWorkQueueFactory sharedFactory]_block_invoke
+ ___43-[HAP2AccessoryDNSResolver attachDelegate:]_block_invoke
+ ___43-[HAP2AccessoryDNSResolver detachDelegate:]_block_invoke
+ ___43-[HAP2AccessoryServer hasWiFiAdvertisement]_block_invoke
+ ___44+[HAP2ThreadNetworkUtil _sharedThreadClient]_block_invoke
+ ___44-[HAP2AccessoryDNSResolver currentAddresses]_block_invoke
+ ___44-[HAPNFCReaderSession isConnectedTagPresent]_block_invoke
+ ___45+[HAP2AccessoryServerIPCacheData logCategory]_block_invoke
+ ___45-[HAP2AccessoryServer hasThreadAdvertisement]_block_invoke
+ ___46-[HAP2AccessoryAddressResolverPipeline cancel]_block_invoke
+ ___46-[HAP2AccessoryDNSResolver updateServiceName:]_block_invoke
+ ___46-[HAP2AccessoryDNSResolver updateServiceName:]_block_invoke_2
+ ___47-[HAP2AccessoryServer setHasWiFiAdvertisement:]_block_invoke
+ ___48+[HAP2ThreadNetworkUtil setupEventSubscriptions]_block_invoke
+ ___48-[HAP2AccessoryServer _setHasWiFiAdvertisement:]_block_invoke
+ ___49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke
+ ___49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke_2
+ ___49-[HAP2AccessoryDNSResolver _startPipelineOnQueue]_block_invoke_3
+ ___49-[HAP2AccessoryServer setHasThreadAdvertisement:]_block_invoke
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_2
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_3
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_4
+ ___49-[HAP2CoAPClient getLocalEndpointWithCompletion:]_block_invoke_5
+ ___49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke
+ ___49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke_2
+ ___49-[HAP2CoAPClient getRTTStatisticsWithCompletion:]_block_invoke_3
+ ___49-[HAPAccessoryServerIP disconnectWithCompletion:]_block_invoke
+ ___50-[HAP2AccessoryDNSResolver _handlePipelineUpdate:]_block_invoke
+ ___50-[HAP2AccessoryDNSResolver _handlePipelineUpdate:]_block_invoke_2
+ ___50-[HAP2AccessoryDNSResolver attachCacheSubscriber:]_block_invoke
+ ___50-[HAP2AccessoryDNSResolver detachCacheSubscriber:]_block_invoke
+ ___50-[HAP2AccessoryServer _setHasThreadAdvertisement:]_block_invoke
+ ___50-[HAP2BrowserResolverRegistry(Test) _allDeviceIDs]_block_invoke
+ ___51-[HAP2AccessoryDNSResolver _test_setBecameEmptyAt:]_block_invoke
+ ___51-[HAP2BrowserResolverRegistry resolverForDeviceID:]_block_invoke
+ ___52-[HAP2AccessoryDNSResolver deferAgingClockIfRunning]_block_invoke
+ ___52-[HAP2AccessoryServerBrowser _fireRevalidationSweep]_block_invoke
+ ___52-[HAP2SessionKeepAliveListener isTrackingTransport:]_block_invoke
+ ___53-[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]_block_invoke
+ ___53-[HAP2AccessoryServerTransportCoAP _sendHelloIfReady]_block_invoke_2
+ ___53-[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]_block_invoke
+ ___53-[HAP2CoAPClient getLocalIPv4EndpointWithCompletion:]_block_invoke_2
+ ___53-[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]_block_invoke
+ ___53-[HAP2CoAPClient getLocalIPv6EndpointWithCompletion:]_block_invoke_2
+ ___53-[HAP2SessionKeepAliveListener trackedTransportTypes]_block_invoke
+ ___54-[HAP2AccessoryServerBrowser _buildActiveDeviceIDsSet]_block_invoke
+ ___55-[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]_block_invoke
+ ___55-[HAP2AccessoryServerBrowser _armPTRRevalidationWindow]_block_invoke_2
+ ___55-[HAP2AccessoryServerBrowser hasCurrentPTRForDeviceID:]_block_invoke
+ ___55-[HAP2AccessoryServerTransportCoAP _refreshIPAddresses]_block_invoke
+ ___56-[HAP2SessionKeepAliveListener resetHeartbeatTimestamps]_block_invoke
+ ___57-[HAP2AccessoryServerTransportCoAP clientDidReceivePing:]_block_invoke
+ ___57-[HAP2BrowserResolverRegistry removeResolverForDeviceID:]_block_invoke
+ ___58-[HAP2AccessoryServer(Paired) closeSessionWithCompletion:]_block_invoke
+ ___58-[HAP2AccessoryServer(Paired) configureKeepAliveListener:]_block_invoke
+ ___58-[HAP2AccessoryServerBrowser _cancelPTRRevalidationWindow]_block_invoke
+ ___58-[HAP2AccessoryServerCoordinator(Test) _test_deliverLoss:]_block_invoke
+ ___58-[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]_block_invoke
+ ___58-[HAP2AccessoryServerTransportCoAP _startResolverIfNeeded]_block_invoke_2
+ ___58-[HAPAccessoryServerHAP2Adapter disconnectWithCompletion:]_block_invoke
+ ___59-[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]_block_invoke
+ ___59-[HAP2AccessoryServer(Paired) resolver:didUpdateAddresses:]_block_invoke_2
+ ___59-[HAP2AccessoryServerBrowser initWithCoordinators:storage:]_block_invoke_2
+ ___59-[HAP2AccessoryServerTransportBase hasQueuedCloseOperation]_block_invoke
+ ___59-[HAP2AccessoryServerTransportCoAP _executeCacheMissCancel]_block_invoke
+ ___60-[HAP2AccessoryServerController closeSessionWithCompletion:]_block_invoke
+ ___60-[HAP2SerializedOperationQueue _applyCallerQoSToOperations:]_block_invoke
+ ___61-[HAP2AccessoryServer _setHasDiscoveryAdvertisementLockOnly:]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _sendEndpointRegistration]_block_invoke_2
+ ___61-[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]_block_invoke
+ ___61-[HAP2AccessoryServerTransportCoAP _startResolveTimeoutTimer]_block_invoke_2
+ ___61-[HAP2CoAPClient _ioThreadDidReceivePingInSession:messageID:]_block_invoke
+ ___61-[HAP2CoAPClient _ioThreadDidReceivePongInSession:messageID:]_block_invoke
+ ___61-[HAPAccessoryServerNFC finishTokenAuthAsOf:completed:error:]_block_invoke
+ ___62-[HAP2AccessoryServer(Paired) didReceiveHeartbeatOnTransport:]_block_invoke
+ ___62-[HAP2AccessoryServerBrowser noteBrowsedPTRRemoveForDeviceID:]_block_invoke
+ ___62-[HAP2AccessoryServerTransportCoAP _resolverDidFailWithError:]_block_invoke
+ ___62-[HAP2AccessoryServerTransportCoAP clientDidDisconnect:error:]_block_invoke
+ ___63-[HAP2AccessoryServerController readLocalEndpointsWithHandler:]_block_invoke
+ ___63-[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]_block_invoke
+ ___63-[HAP2AccessoryServerCoordinator(Test) _test_deliverDiscovery:]_block_invoke_2
+ ___63-[HAP2SessionKeepAliveListener didReceiveHeartbeatOnTransport:]_block_invoke
+ ___63-[HAP2SessionKeepAliveListener hasMissedHeartbeatForTransport:]_block_invoke
+ ___64-[HAP2AccessoryServer(Test) _test_setConnectionStateUnreachable]_block_invoke
+ ___65-[HAP2AccessoryServerController sendProbeOnTransport:completion:]_block_invoke
+ ___65-[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]_block_invoke
+ ___65-[HAP2AccessoryServerTransportCoAP _sendWiFiEndpointRegistration]_block_invoke_2
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_2
+ ___66-[HAP2AccessoryServerTransportCoAP readLocalEndpointsWithHandler:]_block_invoke_3
+ ___67-[HAP2BrowserResolverRegistry performAuditPassWithActiveDeviceIDs:]_block_invoke
+ ___67-[HAP2SessionKeepAliveListener timeSinceLastHeartbeatForTransport:]_block_invoke
+ ___68-[HAP2AccessoryServerBrowser _restoreCachedAccessoryServersIfNeeded]_block_invoke
+ ___68-[HAP2AccessoryServerTransportCoAP _resolverDidUpdateWithAddresses:]_block_invoke
+ ___68-[HAP2AccessoryServerTransportCoAP _resolverDidUpdateWithAddresses:]_block_invoke_2
+ ___68-[HAP2AccessoryServerTransportCoAP _sendMultiTransportRequest:path:]_block_invoke
+ ___69-[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]_block_invoke
+ ___69-[HAP2AccessoryAddressResolverPipeline _startGetaddrinfoForHostname:]_block_invoke_2
+ ___69-[HAP2AccessoryServerTransportCoAP signalPairVerifySuccessToDelegate]_block_invoke
+ ___69-[HAPAccessoryServerHAP2Adapter dataStreamPeerAddressWithCompletion:]_block_invoke
+ ___70-[HAP2AccessoryServerController _announceReestablishedSessionIfNeeded]_block_invoke
+ ___70-[HAP2AccessoryServerController secureTransport:didChangeState:error:]_block_invoke_4
+ ___70-[HAP2AccessoryServerTransportCoAP applyResolverAddresses:completion:]_block_invoke
+ ___70-[HAP2BrowserResolverRegistry createResolverWithDeviceID:serviceName:]_block_invoke
+ ___71-[HAP2AccessoryServerBrowser noteBrowsedPTRAddForDeviceID:serviceName:]_block_invoke
+ ___72-[HAP2AccessoryServerSecureTransportBase readLocalEndpointsWithHandler:]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _closeMultiTransportClientWithError:]_block_invoke_2
+ ___72-[HAP2AccessoryServerTransportCoAP _scheduleResolverRestartAfterFailure]_block_invoke
+ ___72-[HAP2AccessoryServerTransportCoAP _scheduleResolverRestartAfterFailure]_block_invoke_2
+ ___72-[HAP2AccessoryServerTransportCoAP dataStreamPeerAddressWithCompletion:]_block_invoke
+ ___73-[HAP2AccessoryServerTransportCoAP _sendProbeOnTransportType:completion:]_block_invoke
+ ___74-[HAP2AccessoryServerBrowser cachedIPDidUpdate:transportType:forDeviceID:]_block_invoke
+ ___74-[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]_block_invoke
+ ___74-[HAP2AccessoryServerSecureTransportBase sendProbeOnTransport:completion:]_block_invoke_2
+ ___74-[HAP2AccessoryServerTransportCoAP _finalizeRequestCompletion:path:error:]_block_invoke
+ ___74-[HAP2AccessoryServerTransportCoAP _openMultiTransportClientWithActivity:]_block_invoke
+ ___75-[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]_block_invoke
+ ___75-[HAP2BrowserResolverRegistry _performAuditPassOnQueueWithActiveDeviceIDs:]_block_invoke_2
+ ___76-[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]_block_invoke
+ ___76-[HAP2AccessoryServerTransportCoAP _armInitialCacheGracePeriodTimerIfNeeded]_block_invoke_2
+ ___76-[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]_block_invoke
+ ___76-[HAP2AccessoryServerTransportCoAP _openPrimaryClientForRefreshWithAddress:]_block_invoke_2
+ ___77-[HAP2AccessoryServerSecureTransportPairVerify _currentStateChangeGeneration]_block_invoke
+ ___78-[HAP2AccessoryServerSecureTransportPairVerify _clearECDSAStateForGeneration:]_block_invoke
+ ___78-[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]_block_invoke
+ ___78-[HAP2AccessoryServerTransportCoAP _openPrimaryClientIteratingWithCompletion:]_block_invoke_2
+ ___78-[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]_block_invoke
+ ___78-[HAP2AccessoryServerTransportCoAP _openSecondaryClientForRefreshWithAddress:]_block_invoke_2
+ ___78-[HAP2AccessoryServerTransportCoAP _sendRegistrationTLVWithAddressBytes:port:]_block_invoke
+ ___79-[HAP2AccessoryServerBrowser(Test) _test_restoreCachedAccessoryServersIfNeeded]_block_invoke
+ ___79-[HAP2AccessoryServerSecureTransportBase transport:didChangeWiFiAdvertisement:]_block_invoke
+ ___79-[HAP2AccessoryServerTransportCoAP signalPairVerifyFailureToDelegateWithError:]_block_invoke
+ ___80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke
+ ___80-[HAP2AccessoryServerCoordinator initializePairedAccessoryServerFromCachedInfo:]_block_invoke_2
+ ___81-[HAP2AccessoryServerCoordinator _didDiscoverAccessory:fromMDNSEvent:completion:]_block_invoke
+ ___81-[HAP2AccessoryServerSecureTransportBase transport:didChangeThreadAdvertisement:]_block_invoke
+ ___81-[HAPSecuritySession deriveEncryptionForDataStreamWithKeySalt:completionHandler:]_block_invoke
+ ___82-[HAP2AccessoryServerTransportCoAP _maybeFireOffQueueCacheMissCancelForAddresses:]_block_invoke
+ ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke
+ ___83-[HAP2AccessoryServer(PairedInternal) keepAliveListenerDidCompleteIPPortPairCheck:]_block_invoke_2
+ ___83-[HAP2AccessoryServerSecureTransportBase transport:didReceiveHeartbeatOnTransport:]_block_invoke
+ ___84-[HAP2AccessoryServer(PairedInternal) _handleProbeCompletion:forKeepAliveTransport:]_block_invoke
+ ___84-[HAP2AccessoryServerBrowser _reinitializeFromCachedRecordsAfterCoordinatorsStarted]_block_invoke
+ ___84-[HAP2AccessoryServerController checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___86-[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:resolver:]_block_invoke
+ ___86-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:generation:]_block_invoke
+ ___86-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:generation:]_block_invoke_2
+ ___86-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:generation:]_block_invoke_3
+ ___87-[HAP2AccessoryServerTransportCoAP checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___87-[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]_block_invoke
+ ___87-[HAP2CoAPClient sendRequestWithMethod:path:payload:messageID:dscpPriority:completion:]_block_invoke_2
+ ___88-[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]_block_invoke
+ ___88-[HAP2AccessoryServerTransportCoAP advanceEndpointAfterPairVerifyFailureWithCompletion:]_block_invoke_2
+ ___89-[HAP2AccessoryDNSResolver _applyCachedIP:transportType:notifySubscriber:seedAgingClock:]_block_invoke
+ ___89-[HAP2AccessoryServerSecureTransportPairVerify _claimStateChangeCompletionForGeneration:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _createDefaultResolverWithUpdateHandler:errorHandler:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]_block_invoke
+ ___89-[HAP2AccessoryServerTransportCoAP _openSecondaryClientIteratingIsThreadOnly:completion:]_block_invoke_2
+ ___90-[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]_block_invoke
+ ___90-[HAP2AccessoryServer(PairedInternal) _closeSessionIfConnectedIPAddressStaleForTransport:]_block_invoke_2
+ ___90-[HAP2AccessoryServerBrowser noteBonjourAdvertisementUpdatedForDeviceID:rawDiscoveryInfo:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]_block_invoke
+ ___90-[HAP2AccessoryServerTransportCoAP _readLocalEndpointForClient:transport:into:completion:]_block_invoke_2
+ ___91-[HAP2AccessoryServerEncodingThread _parseCharacteristics:isMultiTransportAccessory:error:]_block_invoke
+ ___92-[HAPAccessoryServerHAP2Adapter deriveEncryptionForDataStreamWithKeySalt:completionHandler:]_block_invoke
+ ___93-[HAP2AccessoryServerSecureTransportBase checkConnectedIPAddressStaleOnTransport:completion:]_block_invoke
+ ___94-[HAP2BrowserResolverRegistry updateCachedAddressesForDeviceID:cachedPrimary:cachedSecondary:]_block_invoke
+ ___97-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:messageID:dscpPriority:completion:]_block_invoke
+ ___97-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:messageID:dscpPriority:completion:]_block_invoke_2
+ ___97-[HAPAccessoryServerBrowserHAP2Adapter isThreadAccessoryDiscoveredWithAccessoryServerIdentifier:]_block_invoke
+ ___98-[HAPAccessoryServerNFC pairSetupSession:validateAndRollMFiTokenWithUUID:token:completionHandler:]_block_invoke_2
+ ___98-[HAPAccessoryServerNFC pairSetupSession:validateAndRollMFiTokenWithUUID:token:completionHandler:]_block_invoke_3
+ ___99-[HAP2AccessoryServerSecureTransportBase transport:pairVerifyDidCompleteOnIPAddress:transportType:]_block_invoke
+ ___block_descriptor_106_e8_32s40s48s56s64r72r80r88r_e28_v24?0"NSData"8"NSError"16ls32l8r64l8s40l8r72l8r80l8r88l8s48l8s56l8
+ ___block_descriptor_122_e8_32s40s48s56s64s72r80r88r96r104w_e28_v24?0"NSData"8"NSError"16lw104l8r72l8s32l8r80l8r88l8s40l8r96l8s48l8s56l8s64l8
+ ___block_descriptor_123_e8_32s40s48s56s64s72s80r88r96r104r112w_e5_v8?0lw112l8s32l8s40l8s48l8s56l8s64l8r80l8r88l8r96l8r104l8s72l8
+ ___block_descriptor_32_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_40_e28_v32?0"NSOperation"8Q16^B24l
+ ___block_descriptor_40_e65_v24?0{shared_ptr<CtrXPC::Event>=^{Event}^{__shared_weak_count}}8l
+ ___block_descriptor_40_e8_32bs_e41_v32?0"NSData"8"NSString"16"NSError"24ls32l8
+ ___block_descriptor_40_e8_32bs_e49_v28?0B8"HAP2AccessorySessionInfo"12"NSError"20ls32l8
+ ___block_descriptor_40_e8_32s_e31_v28?0"NSData"8S16"NSError"20ls32l8
+ ___block_descriptor_40_e8_32w_e11_v16?0i8i12lw32l8
+ ___block_descriptor_40_e8_32w_e12_v24?0^8Q16lw32l8
+ ___block_descriptor_40_e8_32w_e15_v16?0?<v?q>8lw32l8
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSArray"8lw32l8
+ ___block_descriptor_40_e8_32w_e22_v16?0"NSDictionary"8lw32l8
+ ___block_descriptor_42_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16l
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32bs40w_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16lw40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e28_v32?0"NSOperation"8Q16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32w_e8_v12?0B8lw32l8
+ ___block_descriptor_49_e8_32bs40w_e17_v16?0"NSError"8lw40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_50_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_50_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_50_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_51_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e8_32bs40w48w_e5_v8?0ls32l8w40l8w48l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40r48r_e69_v32?0"HAP2AccessoryServerDiscoveryBonjourBrowseResultTuple"8Q16^B24ls32l8r40l8r48l8
+ ___block_descriptor_56_e8_32s40s48bs_e862_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16ls32l8s48l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e72_"HAP2AccessoryServerIPCacheData"16?0"HAP2AccessoryServerIPCacheData"8ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48w_e20_v20?0B8"NSError"12lw48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s_e72_"HAP2AccessoryServerIPCacheData"16?0"HAP2AccessoryServerIPCacheData"8ls32l8s40l8
+ ___block_descriptor_57_e8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
+ ___block_descriptor_57_e8_32s40s48r_e45_v32?0"HAP2TLVParamServiceSignature"8Q16^B24ls32l8r48l8s40l8
+ ___block_descriptor_57_e8_32s40s48r_e52_v32?0"HAP2TLVParamCharacteristicSignature"8Q16^B24ls32l8r48l8s40l8
+ ___block_descriptor_58_e8_32s40n9_8_8_s0_s8_e5_v8?0l
+ ___block_descriptor_58_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_58_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ ___block_descriptor_59_e8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32bs40r48r56r_e5_v8?0ls32l8r40l8r48l8r56l8
+ ___block_descriptor_64_e8_32bs40r48w_e5_v8?0lw48l8s32l8r40l8
+ ___block_descriptor_64_e8_32bs40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_64_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_64_e8_32s40s48bs_e31_v28?0"NSData"8S16"NSError"20ls32l8s40l8s48l8
+ ___block_descriptor_65_e8_32s40s48bs56w_e20_v20?0B8"NSError"12ls32l8s48l8w56l8s40l8
+ ___block_descriptor_71_e8_32s40s48s_e716_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}IidddIddddCddI[32{?=SdC}]}16ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_74_e8_32s40s48s56s_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_75_e8_32s40s48s56s64w_e22_v16?0"NSDictionary"8lw64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_81_e8_32s40s48r56r64r_e5_v8?0ls32l8s40l8r48l8r56l8r64l8
+ ___block_descriptor_82_e8_32s40s48s56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ ___block_descriptor_83_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_83_e8_32s40s48s56s64s72w_e5_v8?0lw72l8s32l8s40l8s48l8s56l8s64l8
+ ___copy_helper_block_e8_40n9_8_8_s0_s8
+ ___destroy_helper_block_e8_40n7_8_s0_s8
+ ___removeDependencyOnCompletion_block_invoke
+ ___swift_closure_destructor.198Tm
+ __xpc_type_dictionary
+ __xpc_type_string
+ _associated conformance 7CoreHAP17PairSetupTLVErrorOSHAASQ
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs10SetAlgebraSCSQ
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs9OptionSetSCSY
+ _associated conformance So27HAP2CoAPAccessoryTransportsVs9OptionSetSCs0F7Algebra
+ _coapPingHandler
+ _coap_cancel_session_messages
+ _coap_session_send_ping
+ _dispatch_activate
+ _dispatch_assert_queue_not$V2
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dnssd_getaddrinfo_activate
+ _dnssd_getaddrinfo_create
+ _dnssd_getaddrinfo_invalidate
+ _dnssd_getaddrinfo_result_get_address
+ _dnssd_getaddrinfo_result_get_type
+ _dnssd_getaddrinfo_set_event_handler
+ _dnssd_getaddrinfo_set_flags
+ _dnssd_getaddrinfo_set_hostname
+ _dnssd_getaddrinfo_set_interface_index
+ _dnssd_getaddrinfo_set_protocols
+ _dnssd_getaddrinfo_set_queue
+ _dnssd_getaddrinfo_set_result_handler
+ _get_time_now
+ _logCategory._hmf_once_t111
+ _logCategory._hmf_once_t20
+ _logCategory._hmf_once_t216
+ _logCategory._hmf_once_t282
+ _logCategory._hmf_once_t49
+ _logCategory._hmf_once_t8
+ _logCategory._hmf_once_t86
+ _logCategory._hmf_once_t866
+ _logCategory._hmf_once_t938
+ _logCategory._hmf_once_t99
+ _logCategory._hmf_once_v100
+ _logCategory._hmf_once_v112
+ _logCategory._hmf_once_v21
+ _logCategory._hmf_once_v217
+ _logCategory._hmf_once_v283
+ _logCategory._hmf_once_v50
+ _logCategory._hmf_once_v867
+ _logCategory._hmf_once_v87
+ _logCategory._hmf_once_v9
+ _logCategory._hmf_once_v939
+ _os_unfair_lock_lock
+ _record_pending_message
+ _serviceKeyForBrowseResult
+ _sharedFactory.onceToken
+ _sharedFactory.sharedFactory
+ _swift_deallocClassInstance
+ _symbolic $s7CoreHAP39AccessoryMetricsDictionaryRepresentableP
+ _symbolic SS_So8NSObjectCt
+ _symbolic Si
+ _symbolic So11HMMLogEventC
+ _symbolic So7NSErrorCSg
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 7CoreHAP17PairSetupTLVErrorO
+ _symbolic _____ 7CoreHAP25CoAPRequestRacingLogEventC
+ _symbolic _____ 7CoreHAP27AccessoryCHMMetricsLogEventC
+ _symbolic _____ 7CoreHAP28AccessoryCHMRecoveryLogEventC
+ _symbolic _____ So21HAPAccessoryCHMSourceV
+ _symbolic _____ So27HAP2CoAPAccessoryTransportsV
+ _symbolic _____ So27HAP2CoAPRacingTriggerReasonV
+ _symbolic _____ So27HAPAccessoryCHMRecoveryKindV
+ _symbolic _____ So27HAPCHMWiFiConnectivityStateV
+ _symbolic _____ So29HAPCHMThreadConnectivityStateV
+ _symbolic _____ So30HAP2CoAPRacingWinningTransportV
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sg6rolled_______pSg5errorAB9echoTokentSg 10Foundation4DataV s5ErrorP
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _xpc_dictionary_create
+ _xpc_dictionary_get_value
+ _xpc_get_type
+ _xpc_string_get_string_ptr
- -[HAP2AccessoryServer _browserFastSetHasDiscoveryAdvertisement:]
- -[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:]
- -[HAP2AccessoryServer(Unpaired) pairingDriver:didRequestLocalPairingIdentityWithCompletion:]
- -[HAP2AccessoryServer(Unpaired) pairingDriver:didSaveRemoteECDSAPairingKey:forAccessoryIdentifier:completion:]
- -[HAP2AccessoryServer(Unpaired) pairingDriver:didSaveRemotePairingIdentity:completion:]
- -[HAP2AccessoryServerController secureTransport:needsECDSALongTermPublicKeyForPeerWithIdentifier:completion:]
- -[HAP2AccessoryServerController secureTransport:needsLocalPairingIdentityForECDSAKeyPairSetupSession:completion:]
- -[HAP2AccessoryServerController secureTransport:needsLocalPairingIdentityWithCompletion:]
- -[HAP2AccessoryServerController secureTransport:needsRemotePairingIdentityForDeviceID:completion:]
- -[HAP2AccessoryServerCoordinator _didDiscoverAccessory:completion:]
- -[HAP2AccessoryServerSecureTransportPairVerify _createSecuritySessionFromECDSASession]
- -[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]
- -[HAP2AccessoryServerSecureTransportPairVerify setStateChangeCompletion:]
- -[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]
- -[HAPAVCViewerRegistrationRequest initWithSessionIdentifier:viewerParticipantID:viewerNegotiationBlob:]
- -[HAPNFCReaderSession _cancelDiscoveryTimeoutTimer]
- -[HAPNFCReaderSession _startDiscoveryTimeoutTimer]
- -[HAPNFCReaderSession discoveryTimeoutTimer]
- -[HAPNFCReaderSession setDiscoveryTimeoutTimer:]
- -[HAPNFCReaderSession timerDidFire:]
- -[HAPSystemKeychainStore getHH2ControllerECDSAPublicKeyWithIdentifier:]
- -[HAPSystemKeychainStore getHH2ControllerKeyWithIdentifier:]
- -[HAPWebRTCOfferOptions initWithSFrameEnabled:]
- GCC_except_table1059
- GCC_except_table1061
- GCC_except_table1167
- GCC_except_table1172
- GCC_except_table1174
- GCC_except_table1187
- GCC_except_table1199
- GCC_except_table1201
- GCC_except_table1203
- GCC_except_table1205
- GCC_except_table1331
- GCC_except_table1335
- GCC_except_table1337
- GCC_except_table1539
- GCC_except_table16
- GCC_except_table1749
- GCC_except_table1756
- GCC_except_table1762
- GCC_except_table1764
- GCC_except_table1770
- GCC_except_table1772
- GCC_except_table1776
- GCC_except_table1782
- GCC_except_table1784
- GCC_except_table1786
- GCC_except_table1788
- GCC_except_table1793
- GCC_except_table1797
- GCC_except_table1807
- GCC_except_table1815
- GCC_except_table1822
- GCC_except_table1826
- GCC_except_table1830
- GCC_except_table1834
- GCC_except_table1872
- GCC_except_table1991
- GCC_except_table1995
- GCC_except_table1996
- GCC_except_table1998
- GCC_except_table2000
- GCC_except_table2012
- GCC_except_table2017
- GCC_except_table2021
- GCC_except_table2024
- GCC_except_table2026
- GCC_except_table2029
- GCC_except_table2046
- GCC_except_table2056
- GCC_except_table2058
- GCC_except_table2060
- GCC_except_table2065
- GCC_except_table2068
- GCC_except_table2070
- GCC_except_table2073
- GCC_except_table2076
- GCC_except_table2080
- GCC_except_table2082
- GCC_except_table2085
- GCC_except_table2088
- GCC_except_table2090
- GCC_except_table2092
- GCC_except_table2096
- GCC_except_table2100
- GCC_except_table2108
- GCC_except_table2119
- GCC_except_table2152
- GCC_except_table2157
- GCC_except_table2175
- GCC_except_table2176
- GCC_except_table2177
- GCC_except_table2179
- GCC_except_table2180
- GCC_except_table2181
- GCC_except_table2183
- GCC_except_table2184
- GCC_except_table2206
- GCC_except_table2210
- GCC_except_table2218
- GCC_except_table227
- GCC_except_table236
- GCC_except_table239
- GCC_except_table2391
- GCC_except_table2395
- GCC_except_table2399
- GCC_except_table2403
- GCC_except_table2406
- GCC_except_table2413
- GCC_except_table2419
- GCC_except_table242
- GCC_except_table2421
- GCC_except_table2424
- GCC_except_table2425
- GCC_except_table2427
- GCC_except_table244
- GCC_except_table247
- GCC_except_table250
- GCC_except_table252
- GCC_except_table2528
- GCC_except_table2536
- GCC_except_table2537
- GCC_except_table2538
- GCC_except_table2539
- GCC_except_table2540
- GCC_except_table2541
- GCC_except_table2556
- GCC_except_table2570
- GCC_except_table261
- GCC_except_table265
- GCC_except_table2650
- GCC_except_table2662
- GCC_except_table2731
- GCC_except_table2742
- GCC_except_table2756
- GCC_except_table2759
- GCC_except_table2764
- GCC_except_table2772
- GCC_except_table2780
- GCC_except_table2813
- GCC_except_table2819
- GCC_except_table3015
- GCC_except_table3024
- GCC_except_table3041
- GCC_except_table3075
- GCC_except_table3091
- GCC_except_table3093
- GCC_except_table3105
- GCC_except_table3112
- GCC_except_table3134
- GCC_except_table3148
- GCC_except_table3149
- GCC_except_table3150
- GCC_except_table3153
- GCC_except_table3159
- GCC_except_table3166
- GCC_except_table3169
- GCC_except_table3179
- GCC_except_table3184
- GCC_except_table3223
- GCC_except_table3240
- GCC_except_table3243
- GCC_except_table3248
- GCC_except_table3250
- GCC_except_table3280
- GCC_except_table3282
- GCC_except_table3286
- GCC_except_table3294
- GCC_except_table3302
- GCC_except_table3366
- GCC_except_table3373
- GCC_except_table3375
- GCC_except_table3376
- GCC_except_table3399
- GCC_except_table3419
- GCC_except_table3647
- GCC_except_table3714
- GCC_except_table3715
- GCC_except_table3719
- GCC_except_table3722
- GCC_except_table3724
- GCC_except_table3725
- GCC_except_table3727
- GCC_except_table3728
- GCC_except_table3730
- GCC_except_table3747
- GCC_except_table3750
- GCC_except_table3761
- GCC_except_table3762
- GCC_except_table3764
- GCC_except_table3766
- GCC_except_table3769
- GCC_except_table3772
- GCC_except_table3774
- GCC_except_table3777
- GCC_except_table3780
- GCC_except_table3792
- GCC_except_table3794
- GCC_except_table3798
- GCC_except_table3802
- GCC_except_table3806
- GCC_except_table3855
- GCC_except_table3861
- GCC_except_table3865
- GCC_except_table3869
- GCC_except_table3871
- GCC_except_table3874
- GCC_except_table3878
- GCC_except_table3885
- GCC_except_table3886
- GCC_except_table3887
- GCC_except_table39
- GCC_except_table3968
- GCC_except_table3969
- GCC_except_table3970
- GCC_except_table3971
- GCC_except_table3972
- GCC_except_table3973
- GCC_except_table3974
- GCC_except_table3975
- GCC_except_table3976
- GCC_except_table3977
- GCC_except_table3978
- GCC_except_table3979
- GCC_except_table3980
- GCC_except_table3981
- GCC_except_table4020
- GCC_except_table4047
- GCC_except_table4157
- GCC_except_table4164
- GCC_except_table4206
- GCC_except_table4210
- GCC_except_table4213
- GCC_except_table4216
- GCC_except_table4219
- GCC_except_table4239
- GCC_except_table4252
- GCC_except_table4257
- GCC_except_table4261
- GCC_except_table4263
- GCC_except_table4266
- GCC_except_table4277
- GCC_except_table4285
- GCC_except_table4289
- GCC_except_table4295
- GCC_except_table4296
- GCC_except_table4300
- GCC_except_table4320
- GCC_except_table4322
- GCC_except_table4323
- GCC_except_table4326
- GCC_except_table4332
- GCC_except_table4335
- GCC_except_table4337
- GCC_except_table4343
- GCC_except_table4345
- GCC_except_table4348
- GCC_except_table4359
- GCC_except_table4370
- GCC_except_table4372
- GCC_except_table4381
- GCC_except_table4385
- GCC_except_table4391
- GCC_except_table4651
- GCC_except_table4657
- GCC_except_table4674
- GCC_except_table4678
- GCC_except_table4695
- GCC_except_table4701
- GCC_except_table4714
- GCC_except_table4728
- GCC_except_table4732
- GCC_except_table4845
- GCC_except_table521
- GCC_except_table5301
- GCC_except_table5309
- GCC_except_table531
- GCC_except_table5319
- GCC_except_table5361
- GCC_except_table5364
- GCC_except_table5365
- GCC_except_table5366
- GCC_except_table5367
- GCC_except_table545
- GCC_except_table5516
- GCC_except_table5517
- GCC_except_table5518
- GCC_except_table5519
- GCC_except_table5520
- GCC_except_table5521
- GCC_except_table5527
- GCC_except_table5528
- GCC_except_table553
- GCC_except_table5530
- GCC_except_table5537
- GCC_except_table5540
- GCC_except_table5542
- GCC_except_table5547
- GCC_except_table5550
- GCC_except_table5553
- GCC_except_table5557
- GCC_except_table5561
- GCC_except_table582
- GCC_except_table589
- GCC_except_table601
- GCC_except_table602
- GCC_except_table604
- GCC_except_table6047
- GCC_except_table6048
- GCC_except_table6067
- GCC_except_table607
- GCC_except_table6077
- GCC_except_table6080
- GCC_except_table6085
- GCC_except_table6088
- GCC_except_table610
- GCC_except_table620
- GCC_except_table622
- GCC_except_table626
- GCC_except_table6359
- GCC_except_table6363
- GCC_except_table6408
- GCC_except_table6412
- GCC_except_table6414
- GCC_except_table6416
- GCC_except_table6618
- GCC_except_table6624
- GCC_except_table6628
- GCC_except_table6629
- GCC_except_table6630
- GCC_except_table6631
- GCC_except_table6637
- GCC_except_table6653
- GCC_except_table6688
- GCC_except_table6689
- GCC_except_table6690
- GCC_except_table670
- GCC_except_table6710
- GCC_except_table6722
- GCC_except_table6725
- GCC_except_table6730
- GCC_except_table6732
- GCC_except_table6746
- GCC_except_table680
- GCC_except_table688
- GCC_except_table6970
- GCC_except_table6983
- GCC_except_table6988
- GCC_except_table6991
- GCC_except_table6992
- GCC_except_table6994
- GCC_except_table6995
- GCC_except_table6997
- GCC_except_table7027
- GCC_except_table7049
- GCC_except_table7053
- GCC_except_table7057
- GCC_except_table7062
- GCC_except_table7066
- GCC_except_table7070
- GCC_except_table7074
- GCC_except_table7078
- GCC_except_table7086
- GCC_except_table7088
- GCC_except_table7090
- GCC_except_table7129
- GCC_except_table715
- GCC_except_table719
- GCC_except_table722
- GCC_except_table724
- GCC_except_table7251
- GCC_except_table7285
- GCC_except_table730
- GCC_except_table732
- GCC_except_table7375
- GCC_except_table7376
- GCC_except_table7377
- GCC_except_table7378
- GCC_except_table7379
- GCC_except_table7380
- GCC_except_table7381
- GCC_except_table7443
- GCC_except_table7453
- GCC_except_table7454
- GCC_except_table7469
- GCC_except_table7470
- GCC_except_table7478
- GCC_except_table7484
- GCC_except_table749
- GCC_except_table7497
- GCC_except_table7500
- GCC_except_table7501
- GCC_except_table7506
- GCC_except_table7509
- GCC_except_table7516
- GCC_except_table7519
- GCC_except_table753
- GCC_except_table7533
- GCC_except_table7540
- GCC_except_table7546
- GCC_except_table7555
- GCC_except_table7557
- GCC_except_table7561
- GCC_except_table7562
- GCC_except_table7569
- GCC_except_table7593
- GCC_except_table7594
- GCC_except_table7599
- GCC_except_table7603
- GCC_except_table7604
- GCC_except_table7607
- GCC_except_table7613
- GCC_except_table7617
- GCC_except_table7621
- GCC_except_table7623
- GCC_except_table7625
- GCC_except_table7629
- GCC_except_table763
- GCC_except_table764
- GCC_except_table769
- GCC_except_table772
- GCC_except_table7743
- GCC_except_table7780
- GCC_except_table780
- GCC_except_table7837
- GCC_except_table784
- GCC_except_table7840
- GCC_except_table7847
- GCC_except_table7853
- GCC_except_table7860
- GCC_except_table7861
- GCC_except_table7877
- GCC_except_table7881
- GCC_except_table7882
- GCC_except_table7883
- GCC_except_table791
- GCC_except_table7932
- GCC_except_table7933
- GCC_except_table7935
- GCC_except_table7938
- GCC_except_table796
- GCC_except_table7965
- GCC_except_table7966
- GCC_except_table797
- GCC_except_table7971
- GCC_except_table7991
- GCC_except_table8009
- GCC_except_table8010
- GCC_except_table8011
- GCC_except_table8025
- GCC_except_table8026
- GCC_except_table8027
- GCC_except_table8042
- GCC_except_table8045
- GCC_except_table8052
- GCC_except_table8059
- GCC_except_table8064
- GCC_except_table8070
- GCC_except_table8082
- GCC_except_table8083
- GCC_except_table8088
- GCC_except_table8097
- GCC_except_table8103
- GCC_except_table8104
- GCC_except_table8108
- GCC_except_table8110
- GCC_except_table8112
- GCC_except_table8116
- GCC_except_table8137
- GCC_except_table8139
- GCC_except_table8140
- GCC_except_table8166
- GCC_except_table830
- GCC_except_table837
- GCC_except_table838
- GCC_except_table8394
- GCC_except_table8426
- GCC_except_table8429
- GCC_except_table8596
- GCC_except_table86
- GCC_except_table8634
- GCC_except_table8671
- GCC_except_table8760
- GCC_except_table8764
- GCC_except_table8766
- GCC_except_table8768
- GCC_except_table8770
- GCC_except_table8772
- GCC_except_table8775
- GCC_except_table8777
- GCC_except_table8779
- GCC_except_table8781
- GCC_except_table8783
- GCC_except_table8786
- GCC_except_table8790
- GCC_except_table8797
- GCC_except_table8803
- GCC_except_table8816
- GCC_except_table8821
- GCC_except_table8824
- GCC_except_table8853
- GCC_except_table8856
- GCC_except_table889
- GCC_except_table8896
- GCC_except_table8897
- GCC_except_table8898
- GCC_except_table8900
- GCC_except_table8901
- GCC_except_table8903
- GCC_except_table8907
- GCC_except_table8908
- GCC_except_table8919
- GCC_except_table8970
- GCC_except_table8977
- GCC_except_table907
- GCC_except_table9081
- GCC_except_table9085
- GCC_except_table9087
- GCC_except_table9089
- GCC_except_table9092
- GCC_except_table9094
- GCC_except_table9098
- GCC_except_table9099
- GCC_except_table9101
- GCC_except_table9103
- GCC_except_table9108
- GCC_except_table9110
- GCC_except_table9111
- GCC_except_table931
- GCC_except_table935
- GCC_except_table949
- GCC_except_table954
- _OBJC_IVAR_$_HAPNFCReaderSession._discoveryTimeoutTimer
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServer(Paired|PairedInternal|Unpaired)
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerBrowser
- __OBJC_$_INSTANCE_METHODS_HAP2AccessoryServerCoordinator
- __OBJC_CLASS_PROTOCOLS_$_HAP2AccessoryServer(Paired|PairedInternal|Unpaired)
- ___105-[HAP2AccessoryServerSecureTransportPairVerify localPairingIdentityOfECDSAKeyPairSetupSession:withError:]_block_invoke
- ___105-[HAP2AccessoryServerSecureTransportPairVerify localPairingIdentityOfECDSAKeyPairSetupSession:withError:]_block_invoke_2
- ___109-[HAP2AccessoryServerController secureTransport:needsECDSALongTermPublicKeyForPeerWithIdentifier:completion:]_block_invoke
- ___110-[HAP2AccessoryServer(Unpaired) pairingDriver:didSaveRemoteECDSAPairingKey:forAccessoryIdentifier:completion:]_block_invoke
- ___111-[HAP2AccessoryServerSecureTransportPairVerify securitySession:didReceiveLocalPairingIdentityRequestWithError:]_block_invoke
- ___111-[HAP2AccessoryServerSecureTransportPairVerify securitySession:didReceiveLocalPairingIdentityRequestWithError:]_block_invoke_2
- ___113-[HAP2AccessoryServerController secureTransport:needsLocalPairingIdentityForECDSAKeyPairSetupSession:completion:]_block_invoke
- ___117-[HAP2AccessoryServerPairingDriverPairSetupWorkItem pairSetupSession:didReceiveLocalPairingIdentityRequestWithError:]_block_invoke
- ___118-[HAP2AccessoryServerPairingDriverPairSetupWorkItem pairSetupSession:didPairWithPeerIdentifier:ecdsaPairingKey:error:]_block_invoke
- ___124-[HAP2AccessoryServerSecureTransportPairVerify securitySession:didReceiveRequestForPeerPairingIdentityWithIdentifier:error:]_block_invoke
- ___124-[HAP2AccessoryServerSecureTransportPairVerify securitySession:didReceiveRequestForPeerPairingIdentityWithIdentifier:error:]_block_invoke_2
- ___32-[HAP2CoAPClient _didDisconnect]_block_invoke
- ___43-[HAP2AccessoryServer(Paired) closeSession]_block_invoke
- ___45-[HAP2AccessoryServerController closeSession]_block_invoke
- ___64-[HAP2AccessoryServer _browserFastSetHasDiscoveryAdvertisement:]_block_invoke
- ___65-[HAP2AccessoryServerEncodingThread _parseCharacteristics:error:]_block_invoke
- ___67-[HAP2AccessoryServerCoordinator _didDiscoverAccessory:completion:]_block_invoke
- ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke
- ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke_2
- ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke_3
- ___75-[HAP2AccessoryServerSecureTransportPairVerify _handleECDSASessionFailure:]_block_invoke_4
- ___77-[HAP2AccessoryServer(Paired) mergeWithNewlyDiscoveredPairedAccessoryServer:]_block_invoke
- ___77-[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]_block_invoke
- ___77-[HAP2CoAPClient sendRequestWithMethod:path:payload:dscpPriority:completion:]_block_invoke_2
- ___82-[HAP2AccessoryServerSecureTransportPairVerify pairSetupSession:didStopWithError:]_block_invoke_2
- ___82-[HAP2AccessoryServerSecureTransportPairVerify pairSetupSession:didStopWithError:]_block_invoke_3
- ___82-[HAP2AccessoryServerSecureTransportPairVerify pairSetupSession:didStopWithError:]_block_invoke_4
- ___87-[HAP2AccessoryServer(Unpaired) pairingDriver:didSaveRemotePairingIdentity:completion:]_block_invoke
- ___87-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:dscpPriority:completion:]_block_invoke
- ___87-[HAP2CoAPClient _sendRequestWithMethod:path:payload:activity:dscpPriority:completion:]_block_invoke_2
- ___91-[HAP2AccessoryServerSecureTransportPairVerify ecdsaLongTermPublicKeyOfPeerWithIdentifier:]_block_invoke
- ___91-[HAP2AccessoryServerSecureTransportPairVerify ecdsaLongTermPublicKeyOfPeerWithIdentifier:]_block_invoke_2
- ___92-[HAP2AccessoryServer(Unpaired) pairingDriver:didRequestLocalPairingIdentityWithCompletion:]_block_invoke
- ___92-[HAP2AccessoryServerPairingDriverPairSetupWorkItem pairSetupSession:didPairWithPeer:error:]_block_invoke
- ___98-[HAP2AccessoryServerController secureTransport:needsRemotePairingIdentityForDeviceID:completion:]_block_invoke
- ___block_descriptor_48_e693_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16l
- ___block_descriptor_48_e8_32bs40w_e839_v24?0^{coap_context_t=[6S]^{coap_resource_t}^{coap_resource_t}^{coap_async_state_t}Q^{coap_queue_t}^{coap_endpoint_t}^{coap_session_t}^?^?^?^?^?^?^?^?^?^?^v*Q*QIIIII^v}8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16lw40l8s32l8
- ___block_descriptor_48_e8_32r40r_e69_v32?0"HAP2AccessoryServerDiscoveryBonjourBrowseResultTuple"8Q16^B24lr32l8r40l8
- ___block_descriptor_48_e8_32s40bs_e40_v24?0"HAPPairingIdentity"8"NSError"16ls40l8s32l8
- ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
- ___block_descriptor_56_e8_32s40r48r_e28_v24?0"NSData"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40r48r_e40_v24?0"HAPPairingIdentity"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
- ___block_descriptor_56_e8_32s40s48bs_e40_v24?0"HAPECDSAPairingKey"8"NSError"16ls48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s48r_e45_v32?0"HAP2TLVParamServiceSignature"8Q16^B24ls32l8r48l8s40l8
- ___block_descriptor_56_e8_32s40s48r_e52_v32?0"HAP2TLVParamCharacteristicSignature"8Q16^B24ls32l8r48l8s40l8
- ___block_descriptor_57_e8_32s40bs48w_e5_v8?0lw48l8s32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs56w_e20_v20?0B8"NSError"12ls32l8s48l8w56l8s40l8
- ___block_descriptor_69_e8_32s40s48s_e693_v24?0"HAP2CoAPClient"8^{coap_session_t=CCCIII{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{UT_hash_handle=^{UT_hash_table}^v^v^{UT_hash_handle}^{UT_hash_handle}^vII}{coap_addr_tuple_t={coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}{coap_address_t=I(?={sockaddr=CC[14c]}{sockaddr_in=CCS{in_addr=I}[8c]}{sockaddr_in6=CCSI{in6_addr=(?=[16C][8S][4I])}I})}}i{coap_socket_t=iS^{coap_session_t}^{coap_endpoint_t}}^{coap_endpoint_t}^{coap_context_t}^vSCi^{coap_queue_t}Q[8C]Q^{coap_pdu_t}QQQQQ*Q*Q^vI{coap_fixed_point_t=SS}{coap_fixed_point_t=SS}Ii}16ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56r64r_e5_v8?0ls32l8r56l8s40l8r64l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s64r72r_e5_v8?0ls32l8s40l8s48l8r64l8r72l8s56l8
- ___block_descriptor_81_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___swift_closure_destructor.181Tm
- _logCategory._hmf_once_t108
- _logCategory._hmf_once_t13
- _logCategory._hmf_once_t214
- _logCategory._hmf_once_t269
- _logCategory._hmf_once_t47
- _logCategory._hmf_once_t69
- _logCategory._hmf_once_t79
- _logCategory._hmf_once_t83
- _logCategory._hmf_once_t856
- _logCategory._hmf_once_t891
- _logCategory._hmf_once_t98
- _logCategory._hmf_once_v109
- _logCategory._hmf_once_v14
- _logCategory._hmf_once_v215
- _logCategory._hmf_once_v270
- _logCategory._hmf_once_v48
- _logCategory._hmf_once_v70
- _logCategory._hmf_once_v80
- _logCategory._hmf_once_v84
- _logCategory._hmf_once_v857
- _logCategory._hmf_once_v892
- _logCategory._hmf_once_v99
```
