## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/CoreSpeech`

```diff

-3600.70.47.11.1
-  __TEXT.__text: 0x14d1ec
+3605.32.1.0.0
+  __TEXT.__text: 0x14c5ec
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_methlist: 0x1508c
-  __TEXT.__const: 0x42c
+  __TEXT.__objc_methlist: 0x14ffc
+  __TEXT.__const: 0x45c
   __TEXT.__dlopen_cstrs: 0x1e0
-  __TEXT.__gcc_except_tab: 0x3230
-  __TEXT.__cstring: 0x28ec2
-  __TEXT.__oslogstring: 0x20308
-  __TEXT.__unwind_info: 0x5010
+  __TEXT.__gcc_except_tab: 0x32e8
+  __TEXT.__cstring: 0x28f4c
+  __TEXT.__oslogstring: 0x2063d
+  __TEXT.__unwind_info: 0x4ff0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4258
+  __DATA_CONST.__const: 0x4330
   __DATA_CONST.__objc_classlist: 0x868
   __DATA_CONST.__objc_catlist: 0x40
-  __DATA_CONST.__objc_protolist: 0x4e8
+  __DATA_CONST.__objc_protolist: 0x4e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xaea8
-  __DATA_CONST.__objc_protorefs: 0xa0
+  __DATA_CONST.__objc_selrefs: 0xaef8
+  __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x6a0
-  __DATA_CONST.__objc_arraydata: 0x3e8
-  __DATA_CONST.__got: 0x1b40
-  __AUTH_CONST.__const: 0x1f60
-  __AUTH_CONST.__cfstring: 0x96c0
-  __AUTH_CONST.__objc_const: 0x21458
+  __DATA_CONST.__objc_arraydata: 0x3f0
+  __DATA_CONST.__got: 0x1b58
+  __AUTH_CONST.__const: 0x1ec0
+  __AUTH_CONST.__cfstring: 0x9640
+  __AUTH_CONST.__objc_const: 0x21588
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__lazy_load_got: 0x8
-  __AUTH_CONST.__objc_intobj: 0x9a8
+  __AUTH_CONST.__objc_intobj: 0x9c0
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__objc_dictobj: 0x3c0
   __AUTH_CONST.__objc_floatobj: 0x4f0
-  __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0xda8
+  __AUTH_CONST.__objc_arrayobj: 0x120
+  __AUTH_CONST.__auth_got: 0xdb0
   __AUTH_CONST.__auth_ptr: 0x0
   __AUTH.__objc_data: 0x3ca0
-  __DATA.__objc_ivar: 0x1998
-  __DATA.__data: 0x3a74
+  __DATA.__objc_ivar: 0x19bc
+  __DATA.__data: 0x3a14
   __DATA.__bss: 0x660
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1770
   __DATA_DIRTY.__data: 0xc0
-  __DATA_DIRTY.__bss: 0x158
+  __DATA_DIRTY.__bss: 0x150
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 8197
+  Functions: 8190
   Symbols:   14246
   CStrings:  0
 
Symbols:
+ -[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:hostTime:]
+ -[CSAttSiriAudioSessionStateClient setTtsEndHostTime:]
+ -[CSAttSiriAudioSessionStateClient ttsEndHostTime]
+ -[CSAttSiriMitigationAssetProvider getMitigationAssetWithCompletion:]
+ -[CSEndpointDelayReporter analytics]
+ -[CSEndpointDelayReporter selfLoggingStream]
+ -[CSEndpointDelayReporter setAnalytics:]
+ -[CSEndpointDelayReporter setSelfLoggingStream:]
+ -[CSSiriAudioActivationInfo myriadElectionIdentity]
+ -[CSSiriSpeechRecorder _playStopAlertWithError:]
+ -[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]
+ -[CSSiriSpeechRecorder electionLedger]
+ -[CSSiriSpeechRecorder setElectionLedger:]
+ -[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]
+ -[CSSpeechController _invalidateRecordSessionActivationState]
+ -[CSSpeechController _noteAudioSessionActivatedForRecord:]
+ -[CSSpeechController _notifyDelegateDidStartRecordingSuccessfully:error:]
+ -[CSSpeechController didActivateAudioSessionForRecord]
+ -[CSSpeechController prefetchedAudioDeviceInfo]
+ -[CSSpeechController setDidActivateAudioSessionForRecord:]
+ -[CSSpeechController setPrefetchedAudioDeviceInfo:]
+ -[CSVoiceIdXPCConnection delegate]
+ -[CSVoiceIdXPCConnection setDelegate:]
+ -[CSVoiceTriggerAPModeSuspendPolicyIOS _isHearstRouted]
+ -[CSVoiceTriggerAPModeSuspendPolicyIOS _isPhoneCallActive]
+ -[CSVoiceTriggerAssetHandlerMac _handleTriggerAssetRefresh]
+ -[CSVoiceTriggerAssetHandlerMac compileAndUpdateDeviceCachesWithAsset:assetType:endpointId:]
+ -[CSVoiceTriggerEnabledPolicyATVExclave _addVoiceTriggerEnabledConditions]
+ -[CSVoiceTriggerEnabledPolicyATVExclave _subscribeEventMonitors]
+ -[CSVoiceTriggerEnabledPolicyATVExclave init]
+ -[CSVoiceTriggerSecondPass requestExclaveAudio]
+ -[CSVoiceTriggerSecondPass setRequestExclaveAudio:]
+ -[CSXPCClient _sendMessageAndReplySync:reply:error:]
+ -[CSXPCClient activateAudioSessionWithReason:dynamicAttribute:bundleID:audioDeviceInfo:error:]
+ GCC_except_table1274
+ GCC_except_table1286
+ GCC_except_table1492
+ GCC_except_table1564
+ GCC_except_table1607
+ GCC_except_table1621
+ GCC_except_table1649
+ GCC_except_table1665
+ GCC_except_table1668
+ GCC_except_table1698
+ GCC_except_table178
+ GCC_except_table1798
+ GCC_except_table1800
+ GCC_except_table1806
+ GCC_except_table1866
+ GCC_except_table1892
+ GCC_except_table1898
+ GCC_except_table1979
+ GCC_except_table1999
+ GCC_except_table202
+ GCC_except_table2115
+ GCC_except_table2264
+ GCC_except_table2294
+ GCC_except_table2297
+ GCC_except_table2300
+ GCC_except_table2305
+ GCC_except_table2317
+ GCC_except_table2322
+ GCC_except_table2325
+ GCC_except_table2417
+ GCC_except_table2423
+ GCC_except_table246
+ GCC_except_table2463
+ GCC_except_table2470
+ GCC_except_table2488
+ GCC_except_table2521
+ GCC_except_table254
+ GCC_except_table2632
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table2703
+ GCC_except_table2734
+ GCC_except_table2759
+ GCC_except_table2770
+ GCC_except_table2804
+ GCC_except_table2805
+ GCC_except_table2808
+ GCC_except_table2812
+ GCC_except_table2815
+ GCC_except_table2818
+ GCC_except_table2819
+ GCC_except_table2822
+ GCC_except_table2823
+ GCC_except_table2832
+ GCC_except_table2838
+ GCC_except_table2840
+ GCC_except_table2841
+ GCC_except_table2911
+ GCC_except_table3181
+ GCC_except_table3260
+ GCC_except_table3299
+ GCC_except_table3335
+ GCC_except_table3338
+ GCC_except_table3341
+ GCC_except_table3372
+ GCC_except_table3432
+ GCC_except_table3605
+ GCC_except_table3631
+ GCC_except_table3659
+ GCC_except_table3694
+ GCC_except_table3695
+ GCC_except_table3697
+ GCC_except_table3699
+ GCC_except_table3715
+ GCC_except_table3717
+ GCC_except_table3719
+ GCC_except_table3721
+ GCC_except_table3723
+ GCC_except_table3725
+ GCC_except_table3727
+ GCC_except_table3738
+ GCC_except_table3741
+ GCC_except_table3747
+ GCC_except_table3749
+ GCC_except_table3758
+ GCC_except_table376
+ GCC_except_table3760
+ GCC_except_table3762
+ GCC_except_table3764
+ GCC_except_table3767
+ GCC_except_table3768
+ GCC_except_table3769
+ GCC_except_table3770
+ GCC_except_table3771
+ GCC_except_table3773
+ GCC_except_table3776
+ GCC_except_table3790
+ GCC_except_table3792
+ GCC_except_table3934
+ GCC_except_table3958
+ GCC_except_table4024
+ GCC_except_table4040
+ GCC_except_table4061
+ GCC_except_table4153
+ GCC_except_table4405
+ GCC_except_table4476
+ GCC_except_table4477
+ GCC_except_table4481
+ GCC_except_table4484
+ GCC_except_table4488
+ GCC_except_table449
+ GCC_except_table4513
+ GCC_except_table4569
+ GCC_except_table4575
+ GCC_except_table4645
+ GCC_except_table4850
+ GCC_except_table4857
+ GCC_except_table4864
+ GCC_except_table4870
+ GCC_except_table4953
+ GCC_except_table5113
+ GCC_except_table5123
+ GCC_except_table5147
+ GCC_except_table5167
+ GCC_except_table5250
+ GCC_except_table5264
+ GCC_except_table5273
+ GCC_except_table5280
+ GCC_except_table5286
+ GCC_except_table5288
+ GCC_except_table5291
+ GCC_except_table5299
+ GCC_except_table5301
+ GCC_except_table5305
+ GCC_except_table5307
+ GCC_except_table5318
+ GCC_except_table5324
+ GCC_except_table5331
+ GCC_except_table5340
+ GCC_except_table5342
+ GCC_except_table5343
+ GCC_except_table5344
+ GCC_except_table5345
+ GCC_except_table5347
+ GCC_except_table5348
+ GCC_except_table5351
+ GCC_except_table5353
+ GCC_except_table5354
+ GCC_except_table5357
+ GCC_except_table5372
+ GCC_except_table5460
+ GCC_except_table5464
+ GCC_except_table547
+ GCC_except_table5518
+ GCC_except_table5548
+ GCC_except_table5551
+ GCC_except_table5641
+ GCC_except_table5655
+ GCC_except_table5662
+ GCC_except_table5674
+ GCC_except_table5678
+ GCC_except_table5688
+ GCC_except_table572
+ GCC_except_table578
+ GCC_except_table579
+ GCC_except_table583
+ GCC_except_table5917
+ GCC_except_table5950
+ GCC_except_table5955
+ GCC_except_table5992
+ GCC_except_table6001
+ GCC_except_table6031
+ GCC_except_table604
+ GCC_except_table605
+ GCC_except_table6105
+ GCC_except_table611
+ GCC_except_table6247
+ GCC_except_table6352
+ GCC_except_table6360
+ GCC_except_table637
+ GCC_except_table6380
+ GCC_except_table6385
+ GCC_except_table6491
+ GCC_except_table6546
+ GCC_except_table6626
+ GCC_except_table6648
+ GCC_except_table6659
+ GCC_except_table6660
+ GCC_except_table6703
+ GCC_except_table6714
+ GCC_except_table6719
+ GCC_except_table6724
+ GCC_except_table6752
+ GCC_except_table6824
+ GCC_except_table6836
+ GCC_except_table6870
+ GCC_except_table6873
+ GCC_except_table690
+ GCC_except_table6908
+ GCC_except_table6955
+ GCC_except_table710
+ GCC_except_table7205
+ GCC_except_table7241
+ GCC_except_table7314
+ GCC_except_table7368
+ GCC_except_table7391
+ GCC_except_table7427
+ GCC_except_table7446
+ GCC_except_table7457
+ GCC_except_table7601
+ GCC_except_table7609
+ GCC_except_table768
+ GCC_except_table772
+ GCC_except_table7725
+ GCC_except_table7726
+ GCC_except_table7727
+ GCC_except_table7728
+ GCC_except_table7729
+ GCC_except_table777
+ GCC_except_table7797
+ GCC_except_table7843
+ GCC_except_table7851
+ GCC_except_table7857
+ GCC_except_table7882
+ GCC_except_table7888
+ GCC_except_table7894
+ GCC_except_table8032
+ GCC_except_table943
+ GCC_except_table955
+ GCC_except_table958
+ _AFIsWaffleiron
+ _CSIsJ265
+ _OBJC_CLASS_$_CSFModelConfigDecoder
+ _OBJC_CLASS_$_CSPickableRouteChangeMonitor
+ _OBJC_CLASS_$_CSVoiceTriggerEnabledPolicyATVExclave
+ _OBJC_CLASS_$_SCDAElectionLedger
+ _OBJC_IVAR_$_CSAttSiriAudioSessionStateClient._ttsEndHostTime
+ _OBJC_IVAR_$_CSEndpointDelayReporter._analytics
+ _OBJC_IVAR_$_CSEndpointDelayReporter._selfLoggingStream
+ _OBJC_IVAR_$_CSSiriAudioActivationInfo._myriadElectionIdentity
+ _OBJC_IVAR_$_CSSiriSpeechRecorder._electionLedgerOverride
+ _OBJC_IVAR_$_CSSiriSpeechRecordingContext._electionIdentity
+ _OBJC_IVAR_$_CSSpeechController._didActivateAudioSessionForRecord
+ _OBJC_IVAR_$_CSSpeechController._prefetchedAudioDeviceInfo
+ _OBJC_IVAR_$_CSVoiceIdXPCConnection._delegate
+ _OBJC_IVAR_$_CSVoiceTriggerSecondPass._requestExclaveAudio
+ _OBJC_METACLASS_$_CSVoiceTriggerEnabledPolicyATVExclave
+ __OBJC_$_INSTANCE_METHODS_CSVoiceTriggerEnabledPolicyATVExclave
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ __OBJC_CLASS_RO_$_CSVoiceTriggerEnabledPolicyATVExclave
+ __OBJC_METACLASS_RO_$_CSVoiceTriggerEnabledPolicyATVExclave
+ ___41-[CSSpeechController releaseAudioSession]_block_invoke_2
+ ___42-[CSSpeechController releaseAudioSession:]_block_invoke_2
+ ___52-[CSXPCClient _sendMessageAndReplySync:reply:error:]_block_invoke
+ ___58-[CSSpeechController _noteAudioSessionActivatedForRecord:]_block_invoke
+ ___59-[CSVoiceTriggerAssetHandlerMac _handleTriggerAssetRefresh]_block_invoke
+ ___69-[CSAttSiriMitigationAssetProvider getMitigationAssetWithCompletion:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke_2
+ ___74-[CSVoiceTriggerEnabledPolicyATVExclave _addVoiceTriggerEnabledConditions]_block_invoke
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke_2
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e32_v20?0B8"SCDAElectionOutcome"12ls32l8
+ ___block_descriptor_40_e8_32bs_e8_v12?0B8ls32l8
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40w_e8_v12?0B8ls32l8w40l8
+ ___block_descriptor_49_e8_32s40w_e8_v12?0B8lw40l8s32l8
+ ___block_descriptor_59_e8_32s40r_e20_v20?0B8"NSError"12ls32l8r40l8
+ ___block_descriptor_64_e8_32s40s48r56w_e29_v24?0"CSAsset"8"NSError"16lw56l8s32l8s40l8r48l8
+ ___block_descriptor_68_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- +[SpeechModelTrainingClient initialize]
- -[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:]
- -[CSVoiceTriggerAPModeSuspendPolicyIOS _isHearstRoutedAndWithNoPhoneCall]
- -[SpeechModelTrainingClient .cxx_destruct]
- -[SpeechModelTrainingClient _serviceProxyWithErrorHandler:]
- -[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]
- -[SpeechModelTrainingClient buildSpeechProfileForLanguage:]
- -[SpeechModelTrainingClient dealloc]
- -[SpeechModelTrainingClient extractBundledOovs:appLmDataFileSandboxExtension:appBundleId:completion:]
- -[SpeechModelTrainingClient generateAudioWithTexts:language:completion:]
- -[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedNbest:recognizedText:correctedText:selectedAlternatives:completion:]
- -[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedTokens:recognizedText:correctedText:selectedAlternatives:completion:]
- -[SpeechModelTrainingClient initWithServiceName:]
- -[SpeechModelTrainingClient init]
- -[SpeechModelTrainingClient invalidate]
- -[SpeechModelTrainingClient trainAllAppLMWithLanguage:]
- -[SpeechModelTrainingClient trainAllAppLMWithLanguage:completion:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:completion:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:completion:]
- -[SpeechModelTrainingClient trainGlobalNNLMwithFidesSessionURL:completion:]
- -[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:]
- -[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:directory:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:fides:activity:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:directory:completion:]
- -[SpeechModelTrainingClient upperCaseString:completion:]
- -[SpeechModelTrainingClient wakeUpWithCompletion:]
- -[SpeechModelTrainingClient xpcExitClean]
- GCC_except_table1272
- GCC_except_table1284
- GCC_except_table1490
- GCC_except_table1562
- GCC_except_table1617
- GCC_except_table1641
- GCC_except_table1661
- GCC_except_table1664
- GCC_except_table1694
- GCC_except_table176
- GCC_except_table1792
- GCC_except_table1794
- GCC_except_table1802
- GCC_except_table1862
- GCC_except_table1888
- GCC_except_table1894
- GCC_except_table1975
- GCC_except_table1995
- GCC_except_table200
- GCC_except_table2111
- GCC_except_table2260
- GCC_except_table2290
- GCC_except_table2293
- GCC_except_table2296
- GCC_except_table2301
- GCC_except_table2313
- GCC_except_table2318
- GCC_except_table2321
- GCC_except_table2413
- GCC_except_table2419
- GCC_except_table244
- GCC_except_table2459
- GCC_except_table2462
- GCC_except_table2484
- GCC_except_table2517
- GCC_except_table252
- GCC_except_table2620
- GCC_except_table265
- GCC_except_table2679
- GCC_except_table268
- GCC_except_table2722
- GCC_except_table2747
- GCC_except_table2758
- GCC_except_table2792
- GCC_except_table2793
- GCC_except_table2794
- GCC_except_table2795
- GCC_except_table2796
- GCC_except_table2800
- GCC_except_table2803
- GCC_except_table2810
- GCC_except_table2811
- GCC_except_table2820
- GCC_except_table2826
- GCC_except_table2828
- GCC_except_table2829
- GCC_except_table2899
- GCC_except_table3165
- GCC_except_table3243
- GCC_except_table3280
- GCC_except_table3291
- GCC_except_table3316
- GCC_except_table3319
- GCC_except_table3350
- GCC_except_table3410
- GCC_except_table3642
- GCC_except_table3668
- GCC_except_table3696
- GCC_except_table3731
- GCC_except_table3733
- GCC_except_table3735
- GCC_except_table374
- GCC_except_table3761
- GCC_except_table3766
- GCC_except_table3783
- GCC_except_table3787
- GCC_except_table3789
- GCC_except_table3794
- GCC_except_table3795
- GCC_except_table3796
- GCC_except_table3798
- GCC_except_table3799
- GCC_except_table3800
- GCC_except_table3803
- GCC_except_table3804
- GCC_except_table3805
- GCC_except_table3806
- GCC_except_table3807
- GCC_except_table3808
- GCC_except_table3809
- GCC_except_table3811
- GCC_except_table3812
- GCC_except_table3820
- GCC_except_table3825
- GCC_except_table3826
- GCC_except_table3827
- GCC_except_table3828
- GCC_except_table3969
- GCC_except_table3993
- GCC_except_table4059
- GCC_except_table4075
- GCC_except_table4096
- GCC_except_table4188
- GCC_except_table4440
- GCC_except_table447
- GCC_except_table4511
- GCC_except_table4512
- GCC_except_table4519
- GCC_except_table4523
- GCC_except_table4548
- GCC_except_table4601
- GCC_except_table4607
- GCC_except_table4677
- GCC_except_table4881
- GCC_except_table4888
- GCC_except_table4895
- GCC_except_table4901
- GCC_except_table4984
- GCC_except_table5144
- GCC_except_table5154
- GCC_except_table5178
- GCC_except_table5198
- GCC_except_table5281
- GCC_except_table5295
- GCC_except_table5304
- GCC_except_table5311
- GCC_except_table5317
- GCC_except_table5322
- GCC_except_table5330
- GCC_except_table5332
- GCC_except_table5362
- GCC_except_table5367
- GCC_except_table5369
- GCC_except_table5371
- GCC_except_table5373
- GCC_except_table5374
- GCC_except_table5375
- GCC_except_table5376
- GCC_except_table5378
- GCC_except_table5379
- GCC_except_table5380
- GCC_except_table5381
- GCC_except_table5382
- GCC_except_table5384
- GCC_except_table5385
- GCC_except_table5386
- GCC_except_table5388
- GCC_except_table5434
- GCC_except_table545
- GCC_except_table5491
- GCC_except_table5495
- GCC_except_table5549
- GCC_except_table5579
- GCC_except_table5582
- GCC_except_table5672
- GCC_except_table5686
- GCC_except_table5693
- GCC_except_table570
- GCC_except_table5705
- GCC_except_table5709
- GCC_except_table5719
- GCC_except_table575
- GCC_except_table576
- GCC_except_table581
- GCC_except_table5948
- GCC_except_table5981
- GCC_except_table5986
- GCC_except_table601
- GCC_except_table602
- GCC_except_table6023
- GCC_except_table6032
- GCC_except_table6062
- GCC_except_table609
- GCC_except_table6130
- GCC_except_table6272
- GCC_except_table635
- GCC_except_table6375
- GCC_except_table6383
- GCC_except_table6403
- GCC_except_table6408
- GCC_except_table6514
- GCC_except_table6569
- GCC_except_table6671
- GCC_except_table6682
- GCC_except_table6683
- GCC_except_table6695
- GCC_except_table6726
- GCC_except_table6737
- GCC_except_table6742
- GCC_except_table6747
- GCC_except_table6775
- GCC_except_table6847
- GCC_except_table688
- GCC_except_table6882
- GCC_except_table6893
- GCC_except_table6919
- GCC_except_table6931
- GCC_except_table6978
- GCC_except_table708
- GCC_except_table7226
- GCC_except_table7262
- GCC_except_table7335
- GCC_except_table7389
- GCC_except_table7412
- GCC_except_table7453
- GCC_except_table7464
- GCC_except_table7608
- GCC_except_table7616
- GCC_except_table764
- GCC_except_table770
- GCC_except_table7732
- GCC_except_table7733
- GCC_except_table7735
- GCC_except_table7736
- GCC_except_table7741
- GCC_except_table775
- GCC_except_table7804
- GCC_except_table7850
- GCC_except_table7858
- GCC_except_table7864
- GCC_except_table7889
- GCC_except_table7895
- GCC_except_table7901
- GCC_except_table8039
- GCC_except_table941
- GCC_except_table953
- GCC_except_table956
- _NSSearchPathForDirectoriesInDomains
- _OBJC_CLASS_$_SpeechModelTrainingClient
- _OBJC_IVAR_$_SpeechModelTrainingClient._smtConnection
- _OBJC_METACLASS_$_SpeechModelTrainingClient
- _SpeechModelTrainingGetInterface
- __OBJC_$_CLASS_METHODS_SpeechModelTrainingClient
- __OBJC_$_INSTANCE_METHODS_SpeechModelTrainingClient
- __OBJC_$_INSTANCE_VARIABLES_SpeechModelTrainingClient
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SpeechModelTrainingProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_SpeechModelTrainingProtocol
- __OBJC_CLASS_RO_$_SpeechModelTrainingClient
- __OBJC_LABEL_PROTOCOL_$_SpeechModelTrainingProtocol
- __OBJC_METACLASS_RO_$_SpeechModelTrainingClient
- __OBJC_PROTOCOL_$_SpeechModelTrainingProtocol
- __OBJC_PROTOCOL_REFERENCE_$_SpeechModelTrainingProtocol
- ___101-[SpeechModelTrainingClient extractBundledOovs:appLmDataFileSandboxExtension:appBundleId:completion:]_block_invoke
- ___101-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]_block_invoke
- ___101-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]_block_invoke_2
- ___102-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:directory:completion:]_block_invoke
- ___122-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:]_block_invoke
- ___133-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:completion:]_block_invoke
- ___137-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:]_block_invoke
- ___148-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:completion:]_block_invoke
- ___175-[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedNbest:recognizedText:correctedText:selectedAlternatives:completion:]_block_invoke
- ___176-[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedTokens:recognizedText:correctedText:selectedAlternatives:completion:]_block_invoke
- ___33-[SpeechModelTrainingClient init]_block_invoke
- ___41-[SpeechModelTrainingClient xpcExitClean]_block_invoke
- ___45-[CSXPCClient sendMessageAndReplySync:error:]_block_invoke
- ___50-[SpeechModelTrainingClient wakeUpWithCompletion:]_block_invoke
- ___55-[SpeechModelTrainingClient trainAllAppLMWithLanguage:]_block_invoke
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke_2
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke_3
- ___58-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]_block_invoke
- ___59-[SpeechModelTrainingClient buildSpeechProfileForLanguage:]_block_invoke
- ___62-[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:]_block_invoke
- ___66-[SpeechModelTrainingClient trainAllAppLMWithLanguage:completion:]_block_invoke
- ___72-[SpeechModelTrainingClient generateAudioWithTexts:language:completion:]_block_invoke
- ___73-[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:completion:]_block_invoke
- ___75-[SpeechModelTrainingClient trainGlobalNNLMwithFidesSessionURL:completion:]_block_invoke
- ___92-[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]_block_invoke
- ___92-[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e30_v24?0"NSString"8"NSError"16ls32l8
- ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
- ___block_descriptor_58_e8_32s40r_e20_v20?0B8"NSError"12ls32l8r40l8
- ___block_descriptor_67_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- _sLog
```
