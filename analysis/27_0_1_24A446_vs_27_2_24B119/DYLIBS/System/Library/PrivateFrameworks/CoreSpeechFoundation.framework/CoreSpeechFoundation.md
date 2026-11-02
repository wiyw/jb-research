## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation`

```diff

-3600.70.47.11.1
-  __TEXT.__text: 0xcbfc4
-  __TEXT.__objc_methlist: 0xd9e8
-  __TEXT.__const: 0xfe8
+3605.32.1.0.0
+  __TEXT.__text: 0xcfe90
+  __TEXT.__objc_methlist: 0xdd20
+  __TEXT.__const: 0x1078
   __TEXT.__dlopen_cstrs: 0x24a
   __TEXT.__constg_swiftt: 0x2cc
   __TEXT.__swift5_typeref: 0x1dc
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x30
-  __TEXT.__cstring: 0x1685c
+  __TEXT.__cstring: 0x16dbe
   __TEXT.__swift5_reflstr: 0x278
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_fieldmd: 0x250
   __TEXT.__swift5_proto: 0x74
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x3cec
-  __TEXT.__oslogstring: 0x11a3e
-  __TEXT.__unwind_info: 0x3e08
+  __TEXT.__gcc_except_tab: 0x3e08
+  __TEXT.__oslogstring: 0x120ca
+  __TEXT.__unwind_info: 0x3f08
   __TEXT.__eh_frame: 0x270
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2840
-  __DATA_CONST.__objc_classlist: 0x748
+  __DATA_CONST.__const: 0x2958
+  __DATA_CONST.__objc_classlist: 0x758
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x220
+  __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x7508
+  __DATA_CONST.__objc_selrefs: 0x76d0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x568
+  __DATA_CONST.__objc_superrefs: 0x578
   __DATA_CONST.__objc_arraydata: 0x1c8
-  __DATA_CONST.__got: 0x1038
-  __AUTH_CONST.__const: 0x1ae0
-  __AUTH_CONST.__cfstring: 0x95e0
-  __AUTH_CONST.__objc_const: 0x14e50
+  __DATA_CONST.__got: 0x1048
+  __AUTH_CONST.__const: 0x1b80
+  __AUTH_CONST.__cfstring: 0x9d20
+  __AUTH_CONST.__objc_const: 0x152f0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
-  __AUTH_CONST.__objc_intobj: 0x4b0
+  __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_floatobj: 0x1a0
-  __AUTH_CONST.__auth_got: 0xfc0
+  __AUTH_CONST.__auth_got: 0xfc8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x1c8
-  __DATA.__objc_ivar: 0xd9c
-  __DATA.__data: 0x1a00
-  __DATA.__bss: 0x1580
-  __DATA_DIRTY.__objc_data: 0x47c0
+  __AUTH.__objc_data: 0x218
+  __DATA.__objc_ivar: 0xde4
+  __DATA.__data: 0x1a60
+  __DATA.__bss: 0x1588
+  __DATA_DIRTY.__objc_data: 0x4810
   __DATA_DIRTY.__data: 0x2e8
-  __DATA_DIRTY.__bss: 0x608
+  __DATA_DIRTY.__bss: 0x668
   __DATA_DIRTY.__common: 0x70
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5244
-  Symbols:   9844
+  Functions: 5329
+  Symbols:   9989
   CStrings:  0
 
Symbols:
+ +[CSAudioConsumingStateMonitor sharedInstance]
+ +[CSAudioStartStreamOption getRecordingStartTime:useMachContinuousTime:]
+ +[CSAudioStartStreamOption getRecordingStartTime:useMachContinuousTime:isVoiceTriggered:voiceTriggerInfo:useVoiceTriggerStartTime:]
+ +[CSAudioStreamHoldRequestOption defaultOptionWithTimeout:requestExclaveAudio:]
+ +[CSConfig inputRecordingDurationInSecsAttentive]
+ +[CSFModelConfigDecoder purgeCachedConfigs]
+ +[CSFModelConfigDecoder(Test) cachedConfigPathsForTesting]
+ +[CSUtils allowAttentiveRingBufferSize]
+ +[CSUtils isATVFarFieldVoiceTriggerSupportedLanguageCode:]
+ +[CSUtils isAudioBufferPoolEnabled]
+ +[CSUtils isBargeInDisabled]
+ +[CSUtils isContinuousConversationDisabledInSiriX]
+ +[CSUtils isPerceptionBasedSpeakerChangeDetectionEnabled]
+ +[CSUtils isWaffleIron]
+ +[CSUtils supportEarlyRecordingStartNotification]
+ +[CSUtils(AudioDevice) isCarPlayRecordRoute:]
+ +[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]
+ +[CSUtils(Directory) clearLogFilesInDirectory:matchingPatterns:exceedNumber:]
+ +[CSUtils(Directory) clearLogFilesInDirectorySync:matchingPatterns:exceedNumber:outError:]
+ -[CSAudioConsumingStateMonitor _setAudioConsumingActive:]
+ -[CSAudioConsumingStateMonitor _startMonitoringWithQueue:]
+ -[CSAudioConsumingStateMonitor _stopMonitoring]
+ -[CSAudioConsumingStateMonitor backdateSessionStartBySeconds:]
+ -[CSAudioConsumingStateMonitor init]
+ -[CSAudioConsumingStateMonitor isAudioConsumingSessionActive]
+ -[CSAudioConsumingStateMonitor notifyAudioConsumingSessionDidStart]
+ -[CSAudioConsumingStateMonitor notifyAudioConsumingSessionDidStop]
+ -[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]
+ -[CSAudioProvider _anyPowerMeterLockNeedsBoost12dB]
+ -[CSAudioProvider _clientIdentityQualifiesForPowerMeter:]
+ -[CSAudioProvider _forceReleaseAllPowerMeterLocks]
+ -[CSAudioProvider _forceReleasePowerMeterLockFrom:]
+ -[CSAudioProvider _rewindExclaveCursorForLookbackWithOption:]
+ -[CSAudioProvider _setStreamStateStreamingForTesting]
+ -[CSAudioProvider exfiltratingStreamHolderCountLock]
+ -[CSAudioProvider exfiltratingStreamHolderCount]
+ -[CSAudioProvider hasPowerMeterLock]
+ -[CSAudioProvider isLinwoodEnabledForPowerMeter]
+ -[CSAudioProvider powerMeterLocks]
+ -[CSAudioProvider powerMeterNeedsBoost12dB]
+ -[CSAudioProvider setExfiltratingStreamHolderCount:]
+ -[CSAudioProvider setExfiltratingStreamHolderCountLock:]
+ -[CSAudioProvider setHasPowerMeterLock:]
+ -[CSAudioProvider setIsLinwoodEnabledForPowerMeter:]
+ -[CSAudioProvider setPowerMeterLocks:]
+ -[CSAudioProvider setPowerMeterNeedsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock initWithClientIdentity:needsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock needsBoost12dB]
+ -[CSAudioRecordContext canCreateContinuousConversationProfile]
+ -[CSAudioRecordContext isInitialRequest]
+ -[CSAudioRecordContext isOdeonProxyVoiceTriggered]
+ -[CSAudioRecordContext isPullDownGesture]
+ -[CSAudioSpectralMeter setMovingWindowNormalizationEnabled:]
+ -[CSAudioSpectralMeter setMovingWindowNormalizationTarget:windowSeconds:primeThreshold:]
+ -[CSAudioSpectralMeter setNormalizationEnabled:]
+ -[CSAudioStreamHoldRequestOption initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:]
+ -[CSAudioStreamHoldRequestOption requestExclaveAudio]
+ -[CSAudioStreamHolding initWithName:clientIdentity:requestExclaveAudio:]
+ -[CSAudioStreamHolding requestExclaveAudio]
+ -[CSEventMonitor _removeObserverOnQueue:]
+ -[CSExclaveRecordClient skipProcessingRaiseToSpeakAOE:]
+ -[CSFPreferences spectralMeterNormalizationPrimeThresholdOverride]
+ -[CSFPreferences spectralMeterNormalizationTargetOverride]
+ -[CSFPreferences spectralMeterNormalizationWindowSecondsOverride]
+ GCC_except_table1363
+ GCC_except_table1394
+ GCC_except_table1477
+ GCC_except_table1482
+ GCC_except_table1485
+ GCC_except_table1486
+ GCC_except_table1497
+ GCC_except_table1500
+ GCC_except_table1501
+ GCC_except_table1506
+ GCC_except_table1508
+ GCC_except_table1509
+ GCC_except_table1512
+ GCC_except_table1513
+ GCC_except_table1514
+ GCC_except_table1516
+ GCC_except_table1520
+ GCC_except_table1532
+ GCC_except_table1927
+ GCC_except_table1929
+ GCC_except_table1935
+ GCC_except_table1938
+ GCC_except_table1939
+ GCC_except_table1941
+ GCC_except_table1947
+ GCC_except_table1954
+ GCC_except_table1956
+ GCC_except_table1957
+ GCC_except_table1972
+ GCC_except_table1978
+ GCC_except_table2066
+ GCC_except_table2071
+ GCC_except_table2134
+ GCC_except_table2146
+ GCC_except_table2188
+ GCC_except_table2189
+ GCC_except_table2191
+ GCC_except_table2192
+ GCC_except_table2198
+ GCC_except_table2209
+ GCC_except_table2216
+ GCC_except_table2259
+ GCC_except_table2277
+ GCC_except_table2358
+ GCC_except_table2505
+ GCC_except_table262
+ GCC_except_table2676
+ GCC_except_table2680
+ GCC_except_table274
+ GCC_except_table2759
+ GCC_except_table2770
+ GCC_except_table2772
+ GCC_except_table2777
+ GCC_except_table2779
+ GCC_except_table2792
+ GCC_except_table2799
+ GCC_except_table2801
+ GCC_except_table2819
+ GCC_except_table2840
+ GCC_except_table2891
+ GCC_except_table2944
+ GCC_except_table2946
+ GCC_except_table2947
+ GCC_except_table306
+ GCC_except_table3113
+ GCC_except_table3254
+ GCC_except_table3262
+ GCC_except_table3270
+ GCC_except_table328
+ GCC_except_table3280
+ GCC_except_table3284
+ GCC_except_table3286
+ GCC_except_table3287
+ GCC_except_table329
+ GCC_except_table3323
+ GCC_except_table3329
+ GCC_except_table333
+ GCC_except_table334
+ GCC_except_table339
+ GCC_except_table3390
+ GCC_except_table3394
+ GCC_except_table342
+ GCC_except_table3449
+ GCC_except_table3461
+ GCC_except_table3465
+ GCC_except_table3472
+ GCC_except_table3484
+ GCC_except_table3508
+ GCC_except_table3509
+ GCC_except_table3510
+ GCC_except_table3511
+ GCC_except_table3536
+ GCC_except_table3549
+ GCC_except_table3719
+ GCC_except_table3779
+ GCC_except_table3835
+ GCC_except_table3836
+ GCC_except_table3865
+ GCC_except_table3866
+ GCC_except_table3868
+ GCC_except_table3871
+ GCC_except_table3872
+ GCC_except_table3873
+ GCC_except_table3896
+ GCC_except_table3898
+ GCC_except_table3903
+ GCC_except_table3904
+ GCC_except_table3905
+ GCC_except_table3913
+ GCC_except_table3939
+ GCC_except_table3965
+ GCC_except_table3986
+ GCC_except_table400
+ GCC_except_table4006
+ GCC_except_table4007
+ GCC_except_table4008
+ GCC_except_table4009
+ GCC_except_table401
+ GCC_except_table4019
+ GCC_except_table402
+ GCC_except_table403
+ GCC_except_table404
+ GCC_except_table4110
+ GCC_except_table4111
+ GCC_except_table4120
+ GCC_except_table4122
+ GCC_except_table4124
+ GCC_except_table4125
+ GCC_except_table4128
+ GCC_except_table4129
+ GCC_except_table4132
+ GCC_except_table4133
+ GCC_except_table4134
+ GCC_except_table4135
+ GCC_except_table4136
+ GCC_except_table4137
+ GCC_except_table4138
+ GCC_except_table4139
+ GCC_except_table4140
+ GCC_except_table4143
+ GCC_except_table4144
+ GCC_except_table4150
+ GCC_except_table4151
+ GCC_except_table4153
+ GCC_except_table4155
+ GCC_except_table4156
+ GCC_except_table4158
+ GCC_except_table4159
+ GCC_except_table4162
+ GCC_except_table4163
+ GCC_except_table4166
+ GCC_except_table4167
+ GCC_except_table4168
+ GCC_except_table4170
+ GCC_except_table4171
+ GCC_except_table4172
+ GCC_except_table4174
+ GCC_except_table4175
+ GCC_except_table4178
+ GCC_except_table4179
+ GCC_except_table4180
+ GCC_except_table4208
+ GCC_except_table4258
+ GCC_except_table4262
+ GCC_except_table4322
+ GCC_except_table4324
+ GCC_except_table4326
+ GCC_except_table4352
+ GCC_except_table4354
+ GCC_except_table4358
+ GCC_except_table4359
+ GCC_except_table4360
+ GCC_except_table4361
+ GCC_except_table4373
+ GCC_except_table4382
+ GCC_except_table4384
+ GCC_except_table4385
+ GCC_except_table4386
+ GCC_except_table4387
+ GCC_except_table4388
+ GCC_except_table4389
+ GCC_except_table4390
+ GCC_except_table4392
+ GCC_except_table4394
+ GCC_except_table4395
+ GCC_except_table4396
+ GCC_except_table4397
+ GCC_except_table4398
+ GCC_except_table4401
+ GCC_except_table4403
+ GCC_except_table4404
+ GCC_except_table4406
+ GCC_except_table4408
+ GCC_except_table4410
+ GCC_except_table4412
+ GCC_except_table4419
+ GCC_except_table4432
+ GCC_except_table4433
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4438
+ GCC_except_table4440
+ GCC_except_table4441
+ GCC_except_table4442
+ GCC_except_table4447
+ GCC_except_table4449
+ GCC_except_table4453
+ GCC_except_table4454
+ GCC_except_table4484
+ GCC_except_table4596
+ GCC_except_table4603
+ GCC_except_table4686
+ GCC_except_table4753
+ GCC_except_table4763
+ GCC_except_table4819
+ GCC_except_table4820
+ GCC_except_table4821
+ GCC_except_table4823
+ GCC_except_table4824
+ GCC_except_table4825
+ GCC_except_table4826
+ GCC_except_table4827
+ GCC_except_table4828
+ GCC_except_table4830
+ GCC_except_table4831
+ GCC_except_table4833
+ GCC_except_table4835
+ GCC_except_table4836
+ GCC_except_table4838
+ GCC_except_table4874
+ GCC_except_table4940
+ GCC_except_table4945
+ GCC_except_table4986
+ GCC_except_table5052
+ GCC_except_table509
+ GCC_except_table510
+ GCC_except_table543
+ GCC_except_table580
+ GCC_except_table583
+ GCC_except_table588
+ GCC_except_table606
+ GCC_except_table674
+ GCC_except_table683
+ GCC_except_table685
+ GCC_except_table855
+ GCC_except_table918
+ GCC_except_table926
+ GCC_except_table949
+ GCC_except_table950
+ GCC_except_table954
+ GCC_except_table958
+ GCC_except_table959
+ GCC_except_table960
+ GCC_except_table962
+ GCC_except_table963
+ GCC_except_table964
+ GCC_except_table978
+ _CSAudioPoolCleanup
+ _CSAudioPoolDataWithBytes
+ _CSIsJ265
+ _CSIsJ265.isJ265
+ _CSIsJ265.onceToken
+ _CSSupportsCompanionRuntime
+ _OBJC_CLASS_$_CSAudioConsumingStateMonitor
+ _OBJC_CLASS_$_CSAudioProviderPowerMeterLock
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._audioConsumingActive
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._audioConsumingStartHostTime
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._lock
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSelfTapIOBufferDurationOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSpectralNormalizationPrimeThresholdOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSpectralNormalizationTargetOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSpectralNormalizationWindowSecondsOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._farFieldNormalizationEnabled
+ _OBJC_IVAR_$_CSAudioPowerProvider._spectralNormalizationEnabled
+ _OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCount
+ _OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCountLock
+ _OBJC_IVAR_$_CSAudioProvider._hasPowerMeterLock
+ _OBJC_IVAR_$_CSAudioProvider._isLinwoodEnabledForPowerMeter
+ _OBJC_IVAR_$_CSAudioProvider._powerMeterLocks
+ _OBJC_IVAR_$_CSAudioProvider._powerMeterNeedsBoost12dB
+ _OBJC_IVAR_$_CSAudioProviderPowerMeterLock._needsBoost12dB
+ _OBJC_IVAR_$_CSAudioStreamHoldRequestOption._requestExclaveAudio
+ _OBJC_IVAR_$_CSAudioStreamHolding._requestExclaveAudio
+ _OBJC_METACLASS_$_CSAudioConsumingStateMonitor
+ _OBJC_METACLASS_$_CSAudioProviderPowerMeterLock
+ __CSInternalNumberOverrideForKey
+ __OBJC_$_CLASS_METHODS_CSAudioConsumingStateMonitor
+ __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder(Test)
+ __OBJC_$_INSTANCE_METHODS_CSAudioConsumingStateMonitor
+ __OBJC_$_INSTANCE_METHODS_CSAudioProviderPowerMeterLock
+ __OBJC_$_INSTANCE_VARIABLES_CSAudioConsumingStateMonitor
+ __OBJC_$_INSTANCE_VARIABLES_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROP_LIST_CSAudioConsumingStateMonitor
+ __OBJC_$_PROP_LIST_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSAudioConsumingStateMonitorProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSAudioConsumingStateMonitorProviding
+ __OBJC_$_PROTOCOL_REFS_CSAudioConsumingStateMonitorProviding
+ __OBJC_CLASS_PROTOCOLS_$_CSAudioConsumingStateMonitor
+ __OBJC_CLASS_RO_$_CSAudioConsumingStateMonitor
+ __OBJC_CLASS_RO_$_CSAudioProviderPowerMeterLock
+ __OBJC_LABEL_PROTOCOL_$_CSAudioConsumingStateMonitorProviding
+ __OBJC_METACLASS_RO_$_CSAudioConsumingStateMonitor
+ __OBJC_METACLASS_RO_$_CSAudioProviderPowerMeterLock
+ __OBJC_PROTOCOL_$_CSAudioConsumingStateMonitorProviding
+ __ZN24CSAudioSpectralMeterImpl14_processWindowEPf
+ __ZN24CSAudioSpectralMeterImpl18resetNormalizationEv
+ __ZN24CSAudioSpectralMeterImpl22setNormalizationTargetEf
+ __ZN24CSAudioSpectralMeterImpl23setNormalizationEnabledEb
+ __ZN24CSAudioSpectralMeterImpl29setNormalizationWindowSecondsEf
+ __ZN24CSAudioSpectralMeterImpl30setNormalizationPrimeThresholdEf
+ __ZN24CSAudioSpectralMeterImpl35setMovingWindowNormalizationEnabledEb
+ ___46+[CSAudioConsumingStateMonitor sharedInstance]_block_invoke
+ ___50+[CSUtils isContinuousConversationDisabledInSiriX]_block_invoke
+ ___50-[CSAudioProvider _forceReleaseAllPowerMeterLocks]_block_invoke
+ ___51-[CSAudioProvider _forceReleasePowerMeterLockFrom:]_block_invoke
+ ___57-[CSAudioConsumingStateMonitor _setAudioConsumingActive:]_block_invoke
+ ___58+[CSUtils isATVFarFieldVoiceTriggerSupportedLanguageCode:]_block_invoke
+ ___68-[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]_block_invoke
+ ___77+[CSUtils(Directory) clearLogFilesInDirectory:matchingPatterns:exceedNumber:]_block_invoke
+ ___87+[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]_block_invoke
+ ___87+[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]_block_invoke_2
+ ___CSIsJ265_block_invoke
+ ____ensurePools_block_invoke
+ ___block_descriptor_40_e8_32s_e25_q24?0"NSURL"8"NSURL"16ls32l8
+ ___block_descriptor_42_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_51_e8_32s40s_e5_v8?0ls32l8s40l8
+ __ensurePools.onceToken
+ _isATVFarFieldVoiceTriggerSupportedLanguageCode:.farFieldSupportedLocales
+ _isATVFarFieldVoiceTriggerSupportedLanguageCode:.onceToken
+ _isContinuousConversationDisabledInSiriX.onceToken
+ _kCSDiagnosticReporterAudioConsumingSessionStale
+ _kCSEventMonitorQueueKey
+ _sConfigCache
+ _sConfigCacheLock
+ _sConfigStamp
+ _sLargePool
+ _sSmallPool
+ _stat
- +[CSUtils isSiriDSPTurnedOn]
- +[CSUtils(Directory) clearLogFilesInDirectory:matchingPattern:exceedNumber:]
- GCC_except_table1343
- GCC_except_table1374
- GCC_except_table1453
- GCC_except_table1457
- GCC_except_table1458
- GCC_except_table1459
- GCC_except_table1460
- GCC_except_table1461
- GCC_except_table1462
- GCC_except_table1463
- GCC_except_table1464
- GCC_except_table1465
- GCC_except_table1472
- GCC_except_table1475
- GCC_except_table1476
- GCC_except_table1491
- GCC_except_table1495
- GCC_except_table1507
- GCC_except_table1901
- GCC_except_table1902
- GCC_except_table1903
- GCC_except_table1904
- GCC_except_table1905
- GCC_except_table1909
- GCC_except_table1912
- GCC_except_table1913
- GCC_except_table1915
- GCC_except_table1921
- GCC_except_table1946
- GCC_except_table1952
- GCC_except_table2040
- GCC_except_table2045
- GCC_except_table2105
- GCC_except_table2115
- GCC_except_table2157
- GCC_except_table2158
- GCC_except_table2160
- GCC_except_table2161
- GCC_except_table2167
- GCC_except_table2178
- GCC_except_table2185
- GCC_except_table2228
- GCC_except_table2246
- GCC_except_table2325
- GCC_except_table2435
- GCC_except_table260
- GCC_except_table2626
- GCC_except_table2630
- GCC_except_table2709
- GCC_except_table272
- GCC_except_table2720
- GCC_except_table2722
- GCC_except_table2727
- GCC_except_table2729
- GCC_except_table2742
- GCC_except_table2749
- GCC_except_table2751
- GCC_except_table2769
- GCC_except_table2790
- GCC_except_table2828
- GCC_except_table2885
- GCC_except_table2888
- GCC_except_table302
- GCC_except_table3050
- GCC_except_table3191
- GCC_except_table3199
- GCC_except_table3207
- GCC_except_table3217
- GCC_except_table322
- GCC_except_table3221
- GCC_except_table3223
- GCC_except_table3224
- GCC_except_table324
- GCC_except_table325
- GCC_except_table3260
- GCC_except_table3266
- GCC_except_table327
- GCC_except_table3327
- GCC_except_table3331
- GCC_except_table335
- GCC_except_table3386
- GCC_except_table3398
- GCC_except_table3402
- GCC_except_table3409
- GCC_except_table3418
- GCC_except_table3441
- GCC_except_table3442
- GCC_except_table3443
- GCC_except_table3444
- GCC_except_table3469
- GCC_except_table3482
- GCC_except_table3641
- GCC_except_table3701
- GCC_except_table3715
- GCC_except_table3757
- GCC_except_table3758
- GCC_except_table3787
- GCC_except_table3788
- GCC_except_table3790
- GCC_except_table3794
- GCC_except_table3795
- GCC_except_table3818
- GCC_except_table3820
- GCC_except_table3824
- GCC_except_table3825
- GCC_except_table3826
- GCC_except_table3829
- GCC_except_table3854
- GCC_except_table3880
- GCC_except_table389
- GCC_except_table3901
- GCC_except_table3921
- GCC_except_table3922
- GCC_except_table3923
- GCC_except_table3924
- GCC_except_table393
- GCC_except_table3934
- GCC_except_table394
- GCC_except_table395
- GCC_except_table397
- GCC_except_table4025
- GCC_except_table4026
- GCC_except_table4035
- GCC_except_table4037
- GCC_except_table4038
- GCC_except_table4039
- GCC_except_table4040
- GCC_except_table4043
- GCC_except_table4044
- GCC_except_table4047
- GCC_except_table4048
- GCC_except_table4049
- GCC_except_table4050
- GCC_except_table4051
- GCC_except_table4052
- GCC_except_table4053
- GCC_except_table4054
- GCC_except_table4055
- GCC_except_table4058
- GCC_except_table4059
- GCC_except_table4065
- GCC_except_table4066
- GCC_except_table4068
- GCC_except_table4070
- GCC_except_table4071
- GCC_except_table4073
- GCC_except_table4074
- GCC_except_table4077
- GCC_except_table4078
- GCC_except_table4081
- GCC_except_table4082
- GCC_except_table4083
- GCC_except_table4085
- GCC_except_table4086
- GCC_except_table4087
- GCC_except_table4089
- GCC_except_table4090
- GCC_except_table4092
- GCC_except_table4093
- GCC_except_table4094
- GCC_except_table4095
- GCC_except_table4173
- GCC_except_table4228
- GCC_except_table4229
- GCC_except_table4236
- GCC_except_table4237
- GCC_except_table4238
- GCC_except_table4239
- GCC_except_table4241
- GCC_except_table4242
- GCC_except_table4263
- GCC_except_table4265
- GCC_except_table4266
- GCC_except_table4267
- GCC_except_table4269
- GCC_except_table4270
- GCC_except_table4271
- GCC_except_table4272
- GCC_except_table4273
- GCC_except_table4274
- GCC_except_table4275
- GCC_except_table4276
- GCC_except_table4288
- GCC_except_table4297
- GCC_except_table4299
- GCC_except_table4300
- GCC_except_table4301
- GCC_except_table4302
- GCC_except_table4303
- GCC_except_table4304
- GCC_except_table4305
- GCC_except_table4307
- GCC_except_table4309
- GCC_except_table4310
- GCC_except_table4311
- GCC_except_table4312
- GCC_except_table4316
- GCC_except_table4318
- GCC_except_table4319
- GCC_except_table4325
- GCC_except_table4334
- GCC_except_table4347
- GCC_except_table4353
- GCC_except_table4362
- GCC_except_table4364
- GCC_except_table4368
- GCC_except_table4369
- GCC_except_table4511
- GCC_except_table4518
- GCC_except_table4601
- GCC_except_table4668
- GCC_except_table4678
- GCC_except_table4734
- GCC_except_table4735
- GCC_except_table4736
- GCC_except_table4738
- GCC_except_table4739
- GCC_except_table4740
- GCC_except_table4741
- GCC_except_table4742
- GCC_except_table4743
- GCC_except_table4746
- GCC_except_table4748
- GCC_except_table4750
- GCC_except_table4751
- GCC_except_table4789
- GCC_except_table4855
- GCC_except_table4860
- GCC_except_table4901
- GCC_except_table4967
- GCC_except_table502
- GCC_except_table503
- GCC_except_table536
- GCC_except_table573
- GCC_except_table576
- GCC_except_table581
- GCC_except_table599
- GCC_except_table667
- GCC_except_table671
- GCC_except_table676
- GCC_except_table841
- GCC_except_table911
- GCC_except_table912
- GCC_except_table934
- GCC_except_table935
- GCC_except_table936
- GCC_except_table940
- GCC_except_table944
- GCC_except_table946
- GCC_except_table952
- GCC_except_table956
- GCC_except_table957
- GCC_except_table971
- __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder
- ___76+[CSUtils(Directory) clearLogFilesInDirectory:matchingPattern:exceedNumber:]_block_invoke
- _isAudioStreamProvidingEnabled.result
```
