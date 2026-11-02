## iTunesCloud

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud`

```diff

-4026.110.1.0.0
-  __TEXT.__text: 0x3c9cac
-  __TEXT.__objc_methlist: 0x187cc
+4026.210.1.0.0
+  __TEXT.__text: 0x3ccaf0
+  __TEXT.__objc_methlist: 0x18a24
   __TEXT.__const: 0x225e8
   __TEXT.__dlopen_cstrs: 0x4cf
-  __TEXT.__gcc_except_tab: 0x2b50
-  __TEXT.__cstring: 0x17a42
-  __TEXT.__oslogstring: 0x22336
+  __TEXT.__gcc_except_tab: 0x2b88
+  __TEXT.__cstring: 0x17c74
+  __TEXT.__oslogstring: 0x2268e
   __TEXT.__ustring: 0x8e
-  __TEXT.__unwind_info: 0x6b10
+  __TEXT.__unwind_info: 0x6b90
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7448
+  __DATA_CONST.__const: 0x74e0
   __DATA_CONST.__objc_classlist: 0xdd0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x300
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa570
+  __DATA_CONST.__objc_selrefs: 0xa6a8
   __DATA_CONST.__objc_protorefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0xc00
   __DATA_CONST.__objc_arraydata: 0x498
-  __DATA_CONST.__got: 0x1088
-  __AUTH_CONST.__const: 0x18638
-  __AUTH_CONST.__cfstring: 0x18a80
-  __AUTH_CONST.__objc_const: 0x31728
+  __DATA_CONST.__got: 0x1098
+  __AUTH_CONST.__const: 0x18658
+  __AUTH_CONST.__cfstring: 0x18ba0
+  __AUTH_CONST.__objc_const: 0x31ad0
   __AUTH_CONST.__objc_intobj: 0x480
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x258
   __AUTH_CONST.__auth_got: 0xa68
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x5640
-  __DATA.__objc_ivar: 0x24a8
-  __DATA.__data: 0x3198
-  __DATA.__bss: 0x540
+  __AUTH.__objc_data: 0x230
+  __DATA.__objc_ivar: 0x24e8
+  __DATA.__data: 0x30c8
+  __DATA.__bss: 0x550
   __DATA.__common: 0xb88
-  __DATA_DIRTY.__objc_data: 0x33e0
-  __DATA_DIRTY.__data: 0x108
+  __DATA_DIRTY.__objc_data: 0x87f0
+  __DATA_DIRTY.__data: 0x1d0
   __DATA_DIRTY.__bss: 0x398
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 10164
-  Symbols:   17844
+  Functions: 10213
+  Symbols:   17919
   CStrings:  0
 
Symbols:
+ +[ICCloudAPNSChannelPushMessage dateFromISO8601Timestamp:defaultFetchStartSeconds:]
+ +[ICCloudAPNSChannelPushMessage messageWithAPSIncomingMessage:defaultFetchStartSeconds:]
+ +[ICCloudEntityUpdate allUpdatesPaused]
+ +[ICCloudEntityUpdate pushReceivedUpdateWithMessages:]
+ +[ICCloudEntityUpdateRegistrationToken supportsSecureCoding]
+ +[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]
+ -[ICCloudAPNSChannelPushMessage hash]
+ -[ICCloudAPNSChannelPushMessage isEqual:]
+ -[ICCloudAPNSChannelRegistrationConfiguration initWithChannelID:entityType:storeID:reason:expectedReleaseDate:lastProcessedGoLiveTimestamp:registrationToken:]
+ -[ICCloudAPNSChannelRegistrationConfiguration lastProcessedGoLiveTimestamp]
+ -[ICCloudAPNSChannelRegistrationConfiguration registrationToken]
+ -[ICCloudChannelRegistrationAvailability _updateCloudChannelConfigurationUsingBag:source:]
+ -[ICCloudChannelRegistrationAvailability maxAllowedCloudChannelRegistrations]
+ -[ICCloudChannelRegistrationAvailability registrationFetchEndOffsetSeconds]
+ -[ICCloudChannelRegistrationAvailability registrationFetchStartOffsetSeconds]
+ -[ICCloudClientAPNSChannelManager _computeChannelStatesForResync]
+ -[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]
+ -[ICCloudClientAPNSChannelManager _dispatchUpdate:toRegistrationsForChannelIDs:]
+ -[ICCloudClientAPNSChannelManager _postCloudChannelRegistrationConfigurationChanged:]
+ -[ICCloudClientAPNSChannelManager _resumeUpdates]
+ -[ICCloudClientAPNSChannelManager _serverSetupDidComplete]
+ -[ICCloudClientAPNSChannelManager _xpcRegisterChannelState:completion:]
+ -[ICCloudClientAPNSChannelManager _xpcUnregisterToken:completion:]
+ -[ICCloudClientAPNSChannelManager cloudChannelSubscriptionsConfigurationChanged:]
+ -[ICCloudClientAPNSChannelManager invalidateAllRegistrations]
+ -[ICCloudClientAPNSChannelManager monitoredChannelsWereUpdatedWithMessagesByChannelID:completion:]
+ -[ICCloudClientAPNSChannelManager unregisterAllUpdates]
+ -[ICCloudEntityUpdate initWithType:pushMessages:error:channelIDs:unsubscribeReason:resubscribeReason:]
+ -[ICCloudEntityUpdate pushMessages]
+ -[ICCloudEntityUpdateRegistrationToken _UUID]
+ -[ICCloudEntityUpdateRegistrationToken _initWithUUID:]
+ -[ICCloudEntityUpdateRegistrationToken encodeWithCoder:]
+ -[ICCloudEntityUpdateRegistrationToken initWithCoder:]
+ -[ICCloudServiceStatusMonitor initWithUserIdentity:]
+ -[ICDefaults setShouldTreatCloudChannelRegistrationAsDisabled:]
+ -[ICDefaults shouldTreatCloudChannelRegistrationAsDisabled]
+ -[ICInAppMessageConfiguration syncEnabled]
+ -[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]
+ -[ICLibraryAuthServiceClientTokenProvider _handleAccountAuthenticationDidFinishNotification]
+ -[ICLibraryAuthServiceClientTokenProvider _shouldIncrementFailureCountForError:]
+ -[ICLibraryAuthServiceClientTokenProvider _updateEntriesForExternalAccountsChanges:]
+ -[ICLibraryAuthServiceClientTokenStatus allowRecoveryRefresh]
+ -[ICLibraryAuthServiceClientTokenStatus failureCount]
+ -[ICLibraryAuthServiceClientTokenStatus setAllowRecoveryRefresh:]
+ -[ICLibraryAuthServiceClientTokenStatus setFailureCount:]
+ -[ICMusicLibraryAuthTokenStatus failureCount]
+ -[ICMusicLibraryAuthTokenStatus setFailureCount:]
+ -[ICMusicSubscriptionStatusCache lastKnownSubscriptionStatusResponseForUserIdentity:]
+ -[ICURLBag musicChannelSubscriptionsMaxAllowedRegistrations]
+ -[_ICCloudAPNSChannelRegistrationState initWithChannelID:entityType:storeID:reasons:expectedReleaseDate:registrationToken:lastProcessedGoLiveTimestamp:]
+ -[_ICCloudAPNSChannelRegistrationState lastProcessedGoLiveTimestamp]
+ -[_ICCloudAPNSChannelRegistrationState registrationToken]
+ -[_ICCloudUpdateRegistration initWithConfiguration:handler:token:]
+ -[_ICCloudUpdateRegistration lastProcessedGoLiveTimestamp]
+ -[_ICCloudUpdateRegistration setLastProcessedGoLiveTimestamp:]
+ -[_ICCloudUpdateRegistration token]
+ GCC_except_table1036
+ GCC_except_table1044
+ GCC_except_table1132
+ GCC_except_table1158
+ GCC_except_table1210
+ GCC_except_table1214
+ GCC_except_table1216
+ GCC_except_table1218
+ GCC_except_table1290
+ GCC_except_table138
+ GCC_except_table1384
+ GCC_except_table1583
+ GCC_except_table1596
+ GCC_except_table1854
+ GCC_except_table2038
+ GCC_except_table2067
+ GCC_except_table2082
+ GCC_except_table2122
+ GCC_except_table2234
+ GCC_except_table2249
+ GCC_except_table2298
+ GCC_except_table2300
+ GCC_except_table2306
+ GCC_except_table2313
+ GCC_except_table2341
+ GCC_except_table2356
+ GCC_except_table2361
+ GCC_except_table2363
+ GCC_except_table2368
+ GCC_except_table2371
+ GCC_except_table2384
+ GCC_except_table2461
+ GCC_except_table2470
+ GCC_except_table2473
+ GCC_except_table2476
+ GCC_except_table2479
+ GCC_except_table2481
+ GCC_except_table2492
+ GCC_except_table2494
+ GCC_except_table25
+ GCC_except_table2511
+ GCC_except_table2550
+ GCC_except_table257
+ GCC_except_table2581
+ GCC_except_table2583
+ GCC_except_table2585
+ GCC_except_table2587
+ GCC_except_table260
+ GCC_except_table278
+ GCC_except_table2941
+ GCC_except_table2986
+ GCC_except_table3134
+ GCC_except_table3151
+ GCC_except_table3161
+ GCC_except_table3185
+ GCC_except_table3195
+ GCC_except_table3293
+ GCC_except_table34
+ GCC_except_table3572
+ GCC_except_table3576
+ GCC_except_table3579
+ GCC_except_table3594
+ GCC_except_table3624
+ GCC_except_table3664
+ GCC_except_table3678
+ GCC_except_table3791
+ GCC_except_table3951
+ GCC_except_table4116
+ GCC_except_table4158
+ GCC_except_table4258
+ GCC_except_table4268
+ GCC_except_table4272
+ GCC_except_table4274
+ GCC_except_table4278
+ GCC_except_table4289
+ GCC_except_table4304
+ GCC_except_table4307
+ GCC_except_table4486
+ GCC_except_table4538
+ GCC_except_table4542
+ GCC_except_table4545
+ GCC_except_table4550
+ GCC_except_table4614
+ GCC_except_table4656
+ GCC_except_table4660
+ GCC_except_table4662
+ GCC_except_table4730
+ GCC_except_table480
+ GCC_except_table4807
+ GCC_except_table485
+ GCC_except_table4895
+ GCC_except_table4978
+ GCC_except_table5047
+ GCC_except_table5128
+ GCC_except_table5288
+ GCC_except_table5545
+ GCC_except_table5650
+ GCC_except_table5698
+ GCC_except_table5722
+ GCC_except_table5763
+ GCC_except_table5764
+ GCC_except_table5837
+ GCC_except_table5855
+ GCC_except_table6115
+ GCC_except_table6131
+ GCC_except_table6142
+ GCC_except_table6143
+ GCC_except_table6144
+ GCC_except_table6145
+ GCC_except_table6146
+ GCC_except_table6151
+ GCC_except_table6156
+ GCC_except_table6161
+ GCC_except_table6172
+ GCC_except_table6187
+ GCC_except_table6189
+ GCC_except_table6195
+ GCC_except_table6204
+ GCC_except_table6214
+ GCC_except_table6248
+ GCC_except_table6280
+ GCC_except_table6293
+ GCC_except_table6300
+ GCC_except_table6301
+ GCC_except_table6361
+ GCC_except_table6364
+ GCC_except_table6406
+ GCC_except_table6412
+ GCC_except_table6415
+ GCC_except_table6418
+ GCC_except_table6421
+ GCC_except_table6424
+ GCC_except_table6427
+ GCC_except_table6430
+ GCC_except_table6433
+ GCC_except_table6436
+ GCC_except_table6439
+ GCC_except_table6442
+ GCC_except_table6543
+ GCC_except_table6759
+ GCC_except_table6766
+ GCC_except_table6940
+ GCC_except_table6944
+ GCC_except_table6946
+ GCC_except_table6973
+ GCC_except_table7019
+ GCC_except_table7193
+ GCC_except_table7325
+ GCC_except_table7445
+ GCC_except_table7457
+ GCC_except_table7480
+ GCC_except_table7558
+ GCC_except_table7573
+ GCC_except_table7596
+ GCC_except_table7607
+ GCC_except_table7651
+ GCC_except_table7652
+ GCC_except_table7653
+ GCC_except_table7654
+ GCC_except_table7655
+ GCC_except_table767
+ GCC_except_table7696
+ GCC_except_table7714
+ GCC_except_table7766
+ GCC_except_table7769
+ GCC_except_table7778
+ GCC_except_table7785
+ GCC_except_table779
+ GCC_except_table7832
+ GCC_except_table7938
+ GCC_except_table7971
+ GCC_except_table8029
+ GCC_except_table8030
+ GCC_except_table8043
+ GCC_except_table821
+ GCC_except_table8466
+ GCC_except_table8470
+ GCC_except_table8474
+ GCC_except_table8496
+ GCC_except_table8503
+ GCC_except_table8519
+ GCC_except_table8554
+ GCC_except_table8557
+ GCC_except_table8628
+ GCC_except_table8673
+ GCC_except_table8721
+ GCC_except_table8750
+ GCC_except_table8755
+ GCC_except_table8757
+ GCC_except_table8759
+ GCC_except_table8791
+ GCC_except_table8923
+ GCC_except_table8931
+ GCC_except_table8936
+ GCC_except_table8951
+ GCC_except_table8959
+ GCC_except_table9003
+ GCC_except_table9152
+ GCC_except_table9158
+ GCC_except_table9196
+ GCC_except_table9199
+ GCC_except_table9206
+ GCC_except_table9209
+ GCC_except_table935
+ GCC_except_table944
+ GCC_except_table9456
+ GCC_except_table9466
+ GCC_except_table9524
+ GCC_except_table9611
+ GCC_except_table9616
+ GCC_except_table9856
+ _ICCloudChannelRegistrationConfigurationChangedNotification
+ _ICCloudChannelRegistrationEndOffsetSecondsKey
+ _ICCloudChannelRegistrationFetchEndOffsetSeconds
+ _ICCloudChannelRegistrationFetchStartOffsetSeconds
+ _ICCloudChannelRegistrationMaxAllowedSubscriptions
+ _ICCloudChannelRegistrationMaxSubscriptionsKey
+ _ICCloudChannelRegistrationStartOffsetSecondsKey
+ _ICURLBagKeyCloudChannelRegistrationMaxAllowedSubscription
+ _OBJC_IVAR_$_ICCloudAPNSChannelRegistrationConfiguration._lastProcessedGoLiveTimestamp
+ _OBJC_IVAR_$_ICCloudAPNSChannelRegistrationConfiguration._registrationToken
+ _OBJC_IVAR_$_ICCloudChannelRegistrationAvailability._maxAllowedRegistrations
+ _OBJC_IVAR_$_ICCloudChannelRegistrationAvailability._registrationFetchEndOffsetSeconds
+ _OBJC_IVAR_$_ICCloudChannelRegistrationAvailability._registrationFetchStartOffsetSeconds
+ _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._deliveryQueue
+ _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._isInvalidating
+ _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._pauseUpdates
+ _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._registrationsByChannel
+ _OBJC_IVAR_$_ICCloudEntityUpdate._pushMessages
+ _OBJC_IVAR_$_ICCloudServiceStatusMonitor._userIdentity
+ _OBJC_IVAR_$_ICLibraryAuthServiceClientTokenStatus._allowRecoveryRefresh
+ _OBJC_IVAR_$_ICLibraryAuthServiceClientTokenStatus._failureCount
+ _OBJC_IVAR_$_ICMusicLibraryAuthTokenStatus._failureCount
+ _OBJC_IVAR_$__ICCloudAPNSChannelRegistrationState._lastProcessedGoLiveTimestamp
+ _OBJC_IVAR_$__ICCloudAPNSChannelRegistrationState._registrationToken
+ _OBJC_IVAR_$__ICCloudUpdateRegistration._lastProcessedGoLiveTimestamp
+ _OBJC_IVAR_$__ICCloudUpdateRegistration._token
+ __ContentTypeForPayloadValue.sContentTypeDict
+ __ICLogCategoryAPNSChannel
+ __ISO8601DateFormatterWithFractionalSeconds.sFormatter
+ __ISO8601DateFormatterWithFractionalSeconds.sOnceToken
+ __OBJC_$_CLASS_PROP_LIST_ICCloudEntityUpdateRegistrationToken
+ __OBJC_$_PROP_LIST_ICCloudEntityUpdateRegistrationToken
+ ___58-[ICCloudClientAPNSChannelManager _serverSetupDidComplete]_block_invoke
+ ___61-[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]_block_invoke
+ ___61-[ICInAppMessageManager _performSyncIfEnabledWithCompletion:]_block_invoke_2
+ ___66-[ICCloudClientAPNSChannelManager _xpcUnregisterToken:completion:]_block_invoke
+ ___71-[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]_block_invoke
+ ___71-[ICCloudClientAPNSChannelManager _deliverMessages:forChannelID:group:]_block_invoke_2
+ ___71-[ICCloudClientAPNSChannelManager _xpcRegisterChannelState:completion:]_block_invoke
+ ___80-[ICCloudClientAPNSChannelManager _dispatchUpdate:toRegistrationsForChannelIDs:]_block_invoke
+ ___84-[ICLibraryAuthServiceClientTokenProvider _updateEntriesForExternalAccountsChanges:]_block_invoke
+ ___84-[ICLibraryAuthServiceClientTokenProvider _updateEntriesForExternalAccountsChanges:]_block_invoke_2
+ ___85+[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
+ ___85-[ICMusicSubscriptionStatusCache lastKnownSubscriptionStatusResponseForUserIdentity:]_block_invoke
+ ____ISO8601DateFormatterWithFractionalSeconds_block_invoke
+ ___block_descriptor_48_e8_32r40r_e64_v32?0"NSNumber"8"ICLibraryAuthServiceClientTokenStatus"16^B24lr32l8r40l8
+ ___block_descriptor_48_e8_32s40bs_e49_v24?0"ICInAppMessageConfiguration"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e58_v24?0"ICCloudEntityUpdateRegistrationToken"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40r_e15_v32?0816^B24ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e64_v32?0"NSNumber"8"ICLibraryAuthServiceClientTokenStatus"16^B24ls32l8s40l8
+ ___block_descriptor_49_e8_32s40r_e64_v32?0"NSNumber"8"ICLibraryAuthServiceClientTokenStatus"16^B24ls32l8r40l8
+ ___block_descriptor_80_e8_32s40s48s56bs64bs_e58_v24?0"ICCloudEntityUpdateRegistrationToken"8"NSError"16ls32l8s40l8s56l8s48l8s64l8
+ __handleAccountAuthenticationDidFinishNotification
- +[ICCloudAPNSChannelPushMessage dateFromISO8601Timestamp:]
- +[ICCloudAPNSChannelPushMessage messageWithAPSIncomingMessage:]
- -[ICCloudChannelRegistrationAvailability _commitAvailability:source:]
- -[ICCloudClient unregisterUpdatesForChannelID:reason:]
- -[ICCloudClientAPNSChannelManager _snapshotChannelStatesForResync]
- -[ICCloudClientAPNSChannelManager _xpcUpdateReasonsWithState:completion:]
- -[ICCloudClientAPNSChannelManager handleCloudServerSetupCompleted]
- -[ICCloudClientAPNSChannelManager monitoredEntityWasUpdatedWithMessage:]
- -[ICCloudClientAPNSChannelManager unregisterUpdatesForChannelID:reason:]
- -[ICCloudEntityUpdate initWithType:pushMessage:error:channelIDs:unsubscribeReason:resubscribeReason:]
- -[ICCloudEntityUpdateRegistrationToken _initInternal]
- -[ICCloudServiceStatusMonitor requestUserTokenForDeveloperToken:completionHandler:]
- -[ICLibraryAuthServiceClientTokenProvider _shouldStopBackgroundRefreshForError:]
- -[ICLibraryAuthServiceClientTokenProvider _updateEntriesForAccountsChanges]
- -[ICMusicLibraryAuthTokenStatus setShouldExcludeFromBackgroundRefresh:]
- -[_ICCloudUpdateRegistration initWithConfiguration:handler:]
- GCC_except_table1021
- GCC_except_table1029
- GCC_except_table1117
- GCC_except_table1143
- GCC_except_table1195
- GCC_except_table1199
- GCC_except_table1201
- GCC_except_table1203
- GCC_except_table1275
- GCC_except_table134
- GCC_except_table1370
- GCC_except_table1569
- GCC_except_table1582
- GCC_except_table1840
- GCC_except_table2024
- GCC_except_table2053
- GCC_except_table2068
- GCC_except_table2108
- GCC_except_table2220
- GCC_except_table2235
- GCC_except_table2284
- GCC_except_table2286
- GCC_except_table2292
- GCC_except_table2299
- GCC_except_table2327
- GCC_except_table2342
- GCC_except_table2347
- GCC_except_table2349
- GCC_except_table2354
- GCC_except_table2357
- GCC_except_table2370
- GCC_except_table2447
- GCC_except_table2456
- GCC_except_table2459
- GCC_except_table2462
- GCC_except_table2465
- GCC_except_table2467
- GCC_except_table247
- GCC_except_table2478
- GCC_except_table2480
- GCC_except_table2497
- GCC_except_table250
- GCC_except_table2536
- GCC_except_table2567
- GCC_except_table2569
- GCC_except_table2571
- GCC_except_table2573
- GCC_except_table265
- GCC_except_table2923
- GCC_except_table2968
- GCC_except_table30
- GCC_except_table3115
- GCC_except_table3132
- GCC_except_table3142
- GCC_except_table3166
- GCC_except_table3176
- GCC_except_table3274
- GCC_except_table3553
- GCC_except_table3557
- GCC_except_table3560
- GCC_except_table3575
- GCC_except_table3586
- GCC_except_table3645
- GCC_except_table3659
- GCC_except_table3772
- GCC_except_table3932
- GCC_except_table4097
- GCC_except_table4139
- GCC_except_table4239
- GCC_except_table4247
- GCC_except_table4249
- GCC_except_table4251
- GCC_except_table4253
- GCC_except_table4255
- GCC_except_table4259
- GCC_except_table4288
- GCC_except_table4467
- GCC_except_table4519
- GCC_except_table4523
- GCC_except_table4526
- GCC_except_table4531
- GCC_except_table4595
- GCC_except_table4637
- GCC_except_table4641
- GCC_except_table4643
- GCC_except_table467
- GCC_except_table4710
- GCC_except_table472
- GCC_except_table4787
- GCC_except_table4875
- GCC_except_table4958
- GCC_except_table5026
- GCC_except_table5107
- GCC_except_table5267
- GCC_except_table5524
- GCC_except_table5629
- GCC_except_table5677
- GCC_except_table5701
- GCC_except_table5742
- GCC_except_table5743
- GCC_except_table5816
- GCC_except_table5834
- GCC_except_table6094
- GCC_except_table6101
- GCC_except_table6109
- GCC_except_table6120
- GCC_except_table6121
- GCC_except_table6122
- GCC_except_table6124
- GCC_except_table6129
- GCC_except_table6134
- GCC_except_table6139
- GCC_except_table6150
- GCC_except_table6165
- GCC_except_table6167
- GCC_except_table6173
- GCC_except_table6182
- GCC_except_table6191
- GCC_except_table6225
- GCC_except_table6257
- GCC_except_table6270
- GCC_except_table6277
- GCC_except_table6278
- GCC_except_table6338
- GCC_except_table6341
- GCC_except_table6355
- GCC_except_table6383
- GCC_except_table6389
- GCC_except_table6392
- GCC_except_table6395
- GCC_except_table6398
- GCC_except_table6404
- GCC_except_table6407
- GCC_except_table6410
- GCC_except_table6413
- GCC_except_table6416
- GCC_except_table6419
- GCC_except_table6520
- GCC_except_table6734
- GCC_except_table6741
- GCC_except_table6915
- GCC_except_table6919
- GCC_except_table6921
- GCC_except_table6948
- GCC_except_table6994
- GCC_except_table7167
- GCC_except_table7299
- GCC_except_table7419
- GCC_except_table7431
- GCC_except_table7454
- GCC_except_table7532
- GCC_except_table754
- GCC_except_table7547
- GCC_except_table7570
- GCC_except_table7581
- GCC_except_table7625
- GCC_except_table7626
- GCC_except_table7627
- GCC_except_table7628
- GCC_except_table7629
- GCC_except_table766
- GCC_except_table7670
- GCC_except_table7688
- GCC_except_table7740
- GCC_except_table7743
- GCC_except_table7752
- GCC_except_table7759
- GCC_except_table7806
- GCC_except_table7896
- GCC_except_table7929
- GCC_except_table7987
- GCC_except_table7988
- GCC_except_table8001
- GCC_except_table808
- GCC_except_table8423
- GCC_except_table8427
- GCC_except_table8431
- GCC_except_table8453
- GCC_except_table8460
- GCC_except_table8471
- GCC_except_table8476
- GCC_except_table8511
- GCC_except_table8585
- GCC_except_table8630
- GCC_except_table8678
- GCC_except_table8707
- GCC_except_table8712
- GCC_except_table8714
- GCC_except_table8716
- GCC_except_table8748
- GCC_except_table8880
- GCC_except_table8888
- GCC_except_table8893
- GCC_except_table8908
- GCC_except_table8916
- GCC_except_table8960
- GCC_except_table9109
- GCC_except_table9113
- GCC_except_table9115
- GCC_except_table9153
- GCC_except_table9163
- GCC_except_table9166
- GCC_except_table920
- GCC_except_table929
- GCC_except_table9407
- GCC_except_table9417
- GCC_except_table9475
- GCC_except_table9562
- GCC_except_table9567
- GCC_except_table9807
- _ICCloudChannelRegistrationAvailabilityDidChangeNotification
- _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._listenerEndpointProvider
- _OBJC_IVAR_$_ICCloudClientAPNSChannelManager._tokensByChannelAndReason
- __ContentTypeForPayloadValue.__contentTypeDict
- ___52-[ICInAppMessageManager _performSyncWithCompletion:]_block_invoke_2
- ___62-[ICCloudClientAPNSChannelManager unregisterUpdatesForTokens:]_block_invoke
- ___64-[ICCloudClientAPNSChannelManager channelRegistrationsDisabled:]_block_invoke
- ___66-[ICCloudClientAPNSChannelManager handleCloudServerSetupCompleted]_block_invoke
- ___72-[ICCloudClientAPNSChannelManager monitoredEntityWasUpdatedWithMessage:]_block_invoke
- ___72-[ICCloudClientAPNSChannelManager unregisterUpdatesForChannelID:reason:]_block_invoke
- ___73-[ICCloudClientAPNSChannelManager _xpcUpdateReasonsWithState:completion:]_block_invoke
- ___75-[ICLibraryAuthServiceClientTokenProvider _updateEntriesForAccountsChanges]_block_invoke
- ___75-[ICLibraryAuthServiceClientTokenProvider _updateEntriesForAccountsChanges]_block_invoke_2
- ___83-[ICCloudClientAPNSChannelManager _tearDownAllRegistrationsWithError:notifyDaemon:]_block_invoke_2
- ___85-[ICCloudServiceStatusMonitor revokeMusicKitUserTokensForAccountDSID:withCompletion:]_block_invoke
- ___block_descriptor_41_e8_32r_e64_v32?0"NSNumber"8"ICLibraryAuthServiceClientTokenStatus"16^B24lr32l8
- ___block_descriptor_56_e8_32s40r48r_e64_v32?0"NSNumber"8"ICLibraryAuthServiceClientTokenStatus"16^B24lr40l8r48l8s32l8
- ___block_descriptor_57_e8_32s40bs48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
- ___block_descriptor_98_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s80l8s72l8
```
