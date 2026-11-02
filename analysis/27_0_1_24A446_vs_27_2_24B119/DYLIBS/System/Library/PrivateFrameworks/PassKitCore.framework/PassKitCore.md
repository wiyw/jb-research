## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore`

```diff

-1695.1.4.0.0
-  __TEXT.__text: 0x912ac4
-  __TEXT.__objc_methlist: 0x72700
-  __TEXT.__const: 0x2d710
-  __TEXT.__swift5_typeref: 0x8c78
-  __TEXT.__cstring: 0x7334a
-  __TEXT.__constg_swiftt: 0x7554
-  __TEXT.__swift5_reflstr: 0x662d
-  __TEXT.__swift5_fieldmd: 0x7da0
+1696.2.9.0.0
+  __TEXT.__text: 0x91f5dc
+  __TEXT.__objc_methlist: 0x72a68
+  __TEXT.__const: 0x2d790
+  __TEXT.__swift5_typeref: 0x8da0
+  __TEXT.__cstring: 0x74218
+  __TEXT.__constg_swiftt: 0x7588
+  __TEXT.__swift5_reflstr: 0x664d
+  __TEXT.__swift5_fieldmd: 0x7de0
   __TEXT.__swift5_builtin: 0x53c
   __TEXT.__swift5_assocty: 0xe28
-  __TEXT.__swift5_proto: 0x13e8
-  __TEXT.__swift5_types: 0x7f4
-  __TEXT.__swift5_capture: 0x512c
-  __TEXT.__oslogstring: 0x3c1bd
-  __TEXT.__swift_as_entry: 0x1a0
-  __TEXT.__swift_as_ret: 0x1c8
-  __TEXT.__swift_as_cont: 0x3c0
-  __TEXT.__swift5_protos: 0x68
+  __TEXT.__swift5_proto: 0x13f0
+  __TEXT.__swift5_types: 0x7f8
+  __TEXT.__swift5_capture: 0x543c
+  __TEXT.__oslogstring: 0x3cc99
+  __TEXT.__swift_as_entry: 0x198
+  __TEXT.__swift_as_ret: 0x1c0
+  __TEXT.__swift_as_cont: 0x3b4
   __TEXT.__swift5_mpenum: 0x140
+  __TEXT.__swift5_protos: 0x68
   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x6ae8
   __TEXT.__ustring: 0x1e6c
-  __TEXT.__unwind_info: 0x1fdb8
-  __TEXT.__eh_frame: 0x8a30
+  __TEXT.__unwind_info: 0x1fee8
+  __TEXT.__eh_frame: 0x8a08
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x23550
-  __DATA_CONST.__objc_classlist: 0x3e40
+  __DATA_CONST.__const: 0x23898
+  __DATA_CONST.__objc_classlist: 0x3e48
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x5d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x25218
+  __DATA_CONST.__objc_selrefs: 0x25408
   __DATA_CONST.__objc_protorefs: 0x260
-  __DATA_CONST.__objc_superrefs: 0x3150
+  __DATA_CONST.__objc_superrefs: 0x3158
   __DATA_CONST.__objc_arraydata: 0x2810
-  __DATA_CONST.__got: 0x53b8
-  __AUTH_CONST.__const: 0x269a8
-  __AUTH_CONST.__cfstring: 0x79a20
-  __AUTH_CONST.__objc_const: 0xd0310
+  __DATA_CONST.__got: 0x53a0
+  __AUTH_CONST.__const: 0x27248
+  __AUTH_CONST.__cfstring: 0x7a540
+  __AUTH_CONST.__objc_const: 0xd07c0
   __AUTH_CONST.__objc_arrayobj: 0xd20
   __AUTH_CONST.__objc_intobj: 0x11d0
   __AUTH_CONST.__objc_dictobj: 0x15b8
   __AUTH_CONST.__objc_doubleobj: 0x2b0
-  __AUTH_CONST.__auth_got: 0x2fe8
-  __AUTH_CONST.__auth_ptr: 0x1188
-  __AUTH.__objc_data: 0x22598
-  __AUTH.__data: 0x5818
+  __AUTH_CONST.__auth_got: 0x3010
+  __AUTH_CONST.__auth_ptr: 0x1190
+  __AUTH.__objc_data: 0x20b58
+  __AUTH.__data: 0x59a8
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x7314
-  __DATA.__data: 0xa290
-  __DATA.__bss: 0x26758
+  __DATA.__objc_ivar: 0x7348
+  __DATA.__data: 0xa2b0
+  __DATA.__bss: 0x26858
   __DATA.__common: 0xc59
-  __DATA_DIRTY.__objc_ivar: 0x1f40
-  __DATA_DIRTY.__objc_data: 0x5eb0
-  __DATA_DIRTY.__data: 0x180
-  __DATA_DIRTY.__bss: 0x1318
+  __DATA_DIRTY.__objc_ivar: 0x1f58
+  __DATA_DIRTY.__objc_data: 0x7940
+  __DATA_DIRTY.__data: 0x188
+  __DATA_DIRTY.__bss: 0x1348
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 55741
-  Symbols:   79022
+  Functions: 55940
+  Symbols:   79209
   CStrings:  0
 
Symbols:
+ +[PKAnalyticsReporter(AppleCash) billSplitContextWithReceiptRequestType:receiptLength:]
+ +[PKAnalyticsReporter(AppleCash) messagesContextWithIsGroup:groupSize:]
+ +[PKAnalyticsReporter(AppleCash) reportAppleCashEvent:withMessagesContext:billSplitContext:]
+ +[PKCoreSpotlightUtilities _addNormalizedPhoneNumberForPhoneNumber:toAttributeSet:]
+ +[PKCoreSpotlightUtilities _normalizedPhoneNumberDigitsFromPhoneNumber:]
+ +[PKPaymentAuthorizationErrorStateParam paramWithError:requiresExtendedDisplayDuration:]
+ -[PKAddCarKeyPassConfiguration _adoptProvisioningResolvedFieldsFromConfiguration:]
+ -[PKAddCarKeyPassConfiguration _adoptSessionOnlyFieldsFromConfiguration:]
+ -[PKAddCarKeyPassConfiguration reconcileWithPendingConfiguration:]
+ -[PKAppletSubcredentialManagementSession deleteCredential:reason:completionHandler:]
+ -[PKDAManager deleteCredential:reason:completion:]
+ -[PKDAManager deleteCredentials:reason:completion:]
+ -[PKDAManager deleteCredentialsForIdentifiers:reason:completion:]
+ -[PKDAManager deleteCredentialsForReaderIdentifiers:reason:completion:]
+ -[PKExistingCardAuthorizationRequestMessage contentType]
+ -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]
+ -[PKGroupsController groupForPassUniqueID:]
+ -[PKGroupsController isFilteringPassUniqueID:]
+ -[PKInAppPaymentService cacheApplePayButtonTapWithIdentifier:tapDate:]
+ -[PKLocation copyWithZone:]
+ -[PKPassCredentialShare isLocal]
+ -[PKPassLibrary automaticallyPresentedPassForPasses:webDomain:applicationIdentifier:]
+ -[PKPassLibrary deleteKeyMaterialForSubCredentialId:reason:]
+ -[PKPassShare isSameUnderlyingShareAs:ignoringRecipientHandle:]
+ -[PKPaymentApplication(Transit) transitConfirmationStyle]
+ -[PKPaymentAuthorizationErrorStateParam requiresExtendedDisplayDuration]
+ -[PKPaymentAuthorizationErrorStateParam setRequiresExtendedDisplayDuration:]
+ -[PKPaymentAuthorizationStateMachine _handlePeerPaymentAccountChanged]
+ -[PKPaymentAuthorizationStateMachine _resumePeerPaymentUpdates]
+ -[PKPaymentAuthorizationStateMachine hasPausedPeerPaymentUpdates]
+ -[PKPaymentAuthorizationStateMachine setHasPausedPeerPaymentUpdates:]
+ -[PKPaymentButtonAnalytics _lock_payloadForEvent:error:]
+ -[PKPaymentButtonAnalytics _reportPayload:]
+ -[PKPaymentButtonAnalytics didRenderContent]
+ -[PKPaymentButtonAnalytics reportContentRendered]
+ -[PKPaymentOfferConfirmationRecord didProcessEvent:]
+ -[PKPaymentOfferCriteria setSupportsEcomConfirm:]
+ -[PKPaymentOfferCriteria supportsEcomConfirm]
+ -[PKPaymentOffersController _insertEcomConfirmationRecordForTransaction:passUniqueID:]
+ -[PKPaymentOffersController didSuccessfulPaymentWithTransaction:passUniqueID:]
+ -[PKPaymentPassAction isTopUpAction]
+ -[PKPaymentProvisioningController allowsUserGeneratedPass]
+ -[PKPaymentProvisioningController includePrecursorPasses]
+ -[PKPaymentProvisioningController setAllowsUserGeneratedPass:]
+ -[PKPaymentProvisioningController setIncludePrecursorPasses:]
+ -[PKPaymentRemoteCredential supportsExistingCardAuthorization]
+ -[PKPaymentRewrapRequestBase paymentTotalSummaryItemType]
+ -[PKPaymentRewrapRequestBase setPaymentTotalSummaryItemType:]
+ -[PKPaymentService revokeCredentialsWithIdentifiers:reason:completion:]
+ -[PKPaymentService revokeCredentialsWithReaderIdentifiers:reason:completion:]
+ -[PKPaymentSetupFieldPickerItem localizedDescriptionStyle]
+ -[PKPaymentSetupFieldPickerItem localizedDescription]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionStyle]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionTitle]
+ -[PKPaymentSheetApplePayButtonTapAttribution initWithButtonIdentifier:bundleID:tapDate:expirationDate:]
+ -[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]
+ -[PKPaymentWebServiceLocalProxyTargetDevice deleteKeyMaterialForSubCredentialId:reason:]
+ -[PKPaymentWebServiceRemoteProxyTargetDevice deleteKeyMaterialForSubCredentialId:reason:]
+ -[PKPaymentWebServiceTargetDevice deleteKeyMaterialForSubCredentialId:reason:]
+ -[PKPaymentWebServiceTargetDevice revokeCredentialsWithReaderIdentifiers:reason:completion:]
+ -[PKPeerPaymentController analyticsBillSplitContext]
+ -[PKPeerPaymentController analyticsMessagesContext]
+ -[PKPeerPaymentController setAnalyticsBillSplitContext:]
+ -[PKPeerPaymentController setAnalyticsMessagesContext:]
+ -[PKPeerPaymentRequest analyticsBillSplitContext]
+ -[PKPeerPaymentRequest setAnalyticsBillSplitContext:]
+ -[PKPeerPaymentRequiredFieldsPage headerImageStyle]
+ -[PKPeerPaymentRequiredFieldsPage setHeaderImageStyle:]
+ -[PKSearchTransactionResult bankConnectInstitutionID]
+ -[PKSearchTransactionResult bankConnectTransactionUUID]
+ -[PKSearchTransactionResult setBankConnectInstitutionID:]
+ -[PKSearchTransactionResult setBankConnectTransactionUUID:]
+ -[PKSecureElementPass compareProvisioningDatesToPass:newestFirst:]
+ -[PKSharedPassSharesController _activeUserShare]
+ -[PKSharedPassSharesController sharesCreatedByCurrentUser]
+ -[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]
+ GCC_except_table132
+ GCC_except_table146
+ GCC_except_table152
+ GCC_except_table172
+ GCC_except_table178
+ GCC_except_table186
+ GCC_except_table197
+ GCC_except_table207
+ GCC_except_table222
+ GCC_except_table224
+ GCC_except_table228
+ GCC_except_table232
+ GCC_except_table248
+ GCC_except_table253
+ GCC_except_table266
+ GCC_except_table276
+ GCC_except_table290
+ GCC_except_table292
+ GCC_except_table312
+ GCC_except_table314
+ GCC_except_table319
+ GCC_except_table321
+ GCC_except_table340
+ GCC_except_table358
+ GCC_except_table360
+ GCC_except_table367
+ GCC_except_table381
+ GCC_except_table395
+ GCC_except_table435
+ GCC_except_table455
+ GCC_except_table471
+ GCC_except_table482
+ GCC_except_table484
+ GCC_except_table487
+ GCC_except_table53
+ GCC_except_table547
+ GCC_except_table55
+ GCC_except_table555
+ GCC_except_table557
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table578
+ GCC_except_table581
+ GCC_except_table599
+ GCC_except_table893
+ GCC_except_table92
+ GCC_except_table98
+ OBJC_IVAR_$_PKPeerPaymentControllerInternalState.analyticsBillSplitContext
+ OBJC_IVAR_$_PKPeerPaymentControllerInternalState.analyticsMessagesContext
+ _OBJC_CLASS_$_PKPaymentSheetApplePayButtonTapAttribution
+ _OBJC_IVAR_$_PKPaymentAuthorizationErrorStateParam._requiresExtendedDisplayDuration
+ _OBJC_IVAR_$_PKPaymentAuthorizationStateMachine._hasPausedPeerPaymentUpdates
+ _OBJC_IVAR_$_PKPaymentButtonAnalytics._didRenderContent
+ _OBJC_IVAR_$_PKPaymentButtonAnalytics._lock
+ _OBJC_IVAR_$_PKPaymentOfferCriteria._supportsEcomConfirm
+ _OBJC_IVAR_$_PKPaymentProvisioningController._allowsUserGeneratedPass
+ _OBJC_IVAR_$_PKPaymentProvisioningController._includePrecursorPasses
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescription
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescriptionStyle
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionStyle
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionTitle
+ _OBJC_IVAR_$_PKPeerPaymentRequiredFieldsPage._headerImageStyle
+ _OBJC_IVAR_$_PKSearchTransactionResult._bankConnectInstitutionID
+ _OBJC_IVAR_$_PKSearchTransactionResult._bankConnectTransactionUUID
+ _OBJC_METACLASS_$_PKPaymentSheetApplePayButtonTapAttribution
+ _PDCredentialRevocationReasonForPassDeletionReason
+ _PKAcceptedNormalizedPaymentNetworkNames
+ _PKAccessibilityIdentifierCapture
+ _PKAccessibilityIdentifierFeeInterestTransactionsTitle
+ _PKAccessibilityIdentifierFrequentMerchantsTitle
+ _PKAccessibilityIdentifierHighAmountTransactionsTitle
+ _PKAccessibilityIdentifierLoading
+ _PKAccessibilityIdentifierMarkComplete
+ _PKAccessibilityIdentifierObserverBubble
+ _PKAccessibilityIdentifierPrice
+ _PKAccessibilityIdentifierQuantity
+ _PKAccessibilityIdentifierReceiptBubble
+ _PKAccessibilityIdentifierReceiptCameraGuidance
+ _PKAccessibilityIdentifierReceiptCapture
+ _PKAccessibilityIdentifierReceiptChargeDiscount
+ _PKAccessibilityIdentifierReceiptChargeEdit
+ _PKAccessibilityIdentifierReceiptChargeFee
+ _PKAccessibilityIdentifierReceiptChargeTax
+ _PKAccessibilityIdentifierReceiptChargesDetail
+ _PKAccessibilityIdentifierReceiptEditSheet
+ _PKAccessibilityIdentifierReceiptEvenSplit
+ _PKAccessibilityIdentifierReceiptLineItem
+ _PKAccessibilityIdentifierReceiptLineItemModifier
+ _PKAccessibilityIdentifierReceiptLineItemShare
+ _PKAccessibilityIdentifierReceiptModePicker
+ _PKAccessibilityIdentifierReceiptOtherCharges
+ _PKAccessibilityIdentifierReceiptRetake
+ _PKAccessibilityIdentifierReceiptSheet
+ _PKAccessibilityIdentifierReceiptSplitQuantity
+ _PKAccessibilityIdentifierReceiptSubtotal
+ _PKAccessibilityIdentifierReceiptTax
+ _PKAccessibilityIdentifierReceiptTaxEdit
+ _PKAccessibilityIdentifierReceiptTip
+ _PKAccessibilityIdentifierReceiptTip15
+ _PKAccessibilityIdentifierReceiptTip18
+ _PKAccessibilityIdentifierReceiptTip20
+ _PKAccessibilityIdentifierReceiptTip25
+ _PKAccessibilityIdentifierReceiptTipCustom
+ _PKAccessibilityIdentifierReceiptTipNone
+ _PKAccessibilityIdentifierReceiptTipOriginal
+ _PKAccessibilityIdentifierReceiptTotal
+ _PKAccessibilityIdentifierRecurringBubble
+ _PKAccessibilityIdentifierTotalReceived
+ _PKAccessibilityIdentifierTotalRequested
+ _PKAccessibilityIdentifierUnknownBubble
+ _PKAccessibilityIdentifierViewInMessages
+ _PKAddAcceptedNormalizedPaymentNetworkNames
+ _PKAggDKeyApplePayButtonErrorTypeCardArtNotDisplayed
+ _PKAggDKeyApplePayButtonErrorTypeNoEligibleCard
+ _PKAggDKeyApplePayButtonErrorTypePassImageConversionFailed
+ _PKAggDKeyApplePayButtonErrorTypePassLibraryUnavailable
+ _PKAggDKeyApplePayButtonErrorTypePaymentPassLookupFailed
+ _PKAggDKeyApplePayButtonEventTypeContentRendered
+ _PKAnalyticsReportErrorTypeHandoffPaymentFailure
+ _PKAnalyticsReportErrorTypeHandoffUserDismissed
+ _PKAnalyticsReportEventTypeAuthenticationPasscodeStarted
+ _PKAnalyticsReportPaymentApplePayButtonUniqueIdentifier
+ _PKAnalyticsReportPeerPaymentKeyboardTapBillSplitButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapOpenButtonTag
+ _PKCompareDatesPreferringPresent
+ _PKCoreSpotlightCustomKeyNormalizedPhoneNumbers
+ _PKCredentialRevocationReasonCreate
+ _PKCredentialRevocationScenarioAuxiliaryRequirementFailure
+ _PKCredentialRevocationScenarioPassApplicationsRemoved
+ _PKCredentialRevocationScenarioProvisioningFailure
+ _PKCredentialRevocationScenarioProvisioningReplacement
+ _PKCredentialRevocationScenarioServerConsistencyCheck
+ _PKCredentialRevocationScenarioUnspecified
+ _PKExistingCardAuthorizationContentTypeKey
+ _PKHomeAppSharingHost
+ _PKHomeAppURLScheme
+ _PKHomeAppUserLockSettingsHost
+ _PKISO18013_5_Street
+ _PKISO23220_1_PhotoID_ResidentAddressLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentAddressUnicode
+ _PKISO23220_1_PhotoID_ResidentCityUnicode
+ _PKISO23220_1_PhotoID_ResidentState
+ _PKISO23220_1_PhotoID_ResidentStateLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStateUnicode
+ _PKISO23220_1_PhotoID_ResidentStreet
+ _PKISO23220_1_PhotoID_ResidentStreetLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStreetUnicode
+ _PKPassCredentialShareTargetDeviceIsLocal
+ _PKPaymentFieldPickerItemLocalizedDescriptionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionTitleKey
+ _PKPaymentSetupHeaderImageStyleFromString
+ _PKPeerPaymentReceiptMockingEnabled
+ _PKRemoteNetworkPaymentHostAllowGuestCodeScan
+ _PKRemoteNetworkPaymentHostAllowGuestCodeScanKey
+ _PKRemoteNetworkPaymentHostAllowPersonaCodeScan
+ _PKRemoteNetworkPaymentHostAllowPersonaCodeScanKey
+ _PKRemoteNetworkPaymentHostAllowPersonaDisabledPersonalContentCodeScan
+ _PKRemoteNetworkPaymentHostAllowPersonaDisabledPersonalContentCodeScanKey
+ _PKSharingForceTrackKeyNetworkErrorWithoutRequest
+ _PKSharingForceTrackKeyNetworkErrorWithoutRequestKey
+ _PKSharingInvitationFlowIsDeviceTransfer
+ _PKSharingSanitizedRelayURL
+ _PKUserGeneratedPassSupported
+ __DoNotUse_PassDesignerOnly_PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
+ __OBJC_$_CLASS_METHODS_PKPaymentApplication(PKPaymentAuthorizationDataModel|Protobuf|Transit)
+ __OBJC_$_CLASS_PROP_LIST_PKPaymentSheetApplePayButtonTapAttribution
+ __OBJC_$_INSTANCE_METHODS_PKPaymentApplication(PKPaymentAuthorizationDataModel|Protobuf|Transit)
+ __OBJC_$_INSTANCE_METHODS_PKPaymentSheetApplePayButtonTapAttribution
+ __OBJC_CLASS_PROTOCOLS_$_PKPaymentSheetApplePayButtonTapAttribution
+ __OBJC_CLASS_RO_$_PKPaymentSheetApplePayButtonTapAttribution
+ __OBJC_METACLASS_RO_$_PKPaymentSheetApplePayButtonTapAttribution
+ ___188-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]_block_invoke
+ ___48-[PKSharedPassSharesController _activeUserShare]_block_invoke
+ ___50-[PKDAManager deleteCredential:reason:completion:]_block_invoke
+ ___50-[PKDAManager deleteCredential:reason:completion:]_block_invoke_2
+ ___51-[PKDAManager deleteCredentials:reason:completion:]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke_2
+ ___60-[PKPassLibrary deleteKeyMaterialForSubCredentialId:reason:]_block_invoke
+ ___60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke
+ ___60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke_2
+ ___63-[PKPaymentAuthorizationStateMachine _resumePeerPaymentUpdates]_block_invoke
+ ___65-[PKDAManager deleteCredentialsForIdentifiers:reason:completion:]_block_invoke
+ ___65-[PKDAManager deleteCredentialsForIdentifiers:reason:completion:]_block_invoke_2
+ ___65-[PKDAManager deleteCredentialsForIdentifiers:reason:completion:]_block_invoke_3
+ ___70-[PKInAppPaymentService cacheApplePayButtonTapWithIdentifier:tapDate:]_block_invoke
+ ___70-[PKPaymentAuthorizationStateMachine _handlePeerPaymentAccountChanged]_block_invoke
+ ___71-[PKDAManager deleteCredentialsForReaderIdentifiers:reason:completion:]_block_invoke
+ ___71-[PKDAManager deleteCredentialsForReaderIdentifiers:reason:completion:]_block_invoke_2
+ ___71-[PKDAManager deleteCredentialsForReaderIdentifiers:reason:completion:]_block_invoke_3
+ ___71-[PKDAManager deleteCredentialsForReaderIdentifiers:reason:completion:]_block_invoke_4
+ ___71-[PKPaymentService revokeCredentialsWithIdentifiers:reason:completion:]_block_invoke
+ ___77-[PKPaymentService revokeCredentialsWithReaderIdentifiers:reason:completion:]_block_invoke
+ ___78-[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]_block_invoke
+ ___78-[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]_block_invoke_2
+ ___78-[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]_block_invoke_3
+ ___78-[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]_block_invoke_4
+ ___78-[PKPaymentWebService registerDeviceThroughTargetDeviceWithReason:completion:]_block_invoke_5
+ ___89-[PKPaymentWebServiceRemoteProxyTargetDevice deleteKeyMaterialForSubCredentialId:reason:]_block_invoke
+ ___PKCanonicalCredentialTypeForPaymentNetworkName_block_invoke
+ ___PKPaymentNetworkPrioritiesByNormalizedName_block_invoke
+ ____PKPaymentButtonAnalyticsDeviceClass_block_invoke
+ ____PKPaymentButtonAnalyticsOSVersion_block_invoke
+ ___block_descriptor_32_e21_B16?0"PKPassShare"8l
+ ___block_descriptor_40_e8_32s_e30_B16?0"PKTransitCommutePlan"8ls32l8
+ ___block_descriptor_40_e8_32s_e37_B32?0"PKTransitCommutePlan"8Q16^B24ls32l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
+ ___swift__destructor.219Tm
+ ___swift_closure_destructor.150Tm
+ ___swift_closure_destructor.159Tm
+ ___swift_closure_destructor.173Tm
+ ___swift_closure_destructor.252Tm
+ ___swift_closure_destructor.34Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.54Tm
+ ___swift_closure_destructor.68Tm
+ ___swift_closure_destructor.9Tm
+ _associated conformance 11PassKitCore37ProvisioningDeviceTransferContentTypeOSHAASQ
+ _generic environment 11PassKitCore25ProvisioningOperationStepRzl
+ _marketString
+ _symbolic SDySSSo19PKPaymentCredentialCGz_Xx
+ _symbolic SS_So19PKPaymentCredentialCt
+ _symbolic Say______pG 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic SiIegd_
+ _symbolic _____ 11PassKitCore37ProvisioningDeviceTransferContentTypeO
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____GIegn_ s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySS_So19PKPaymentCredentialCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic x4step_______p6runnert 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic y_____ySDySSSo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]
- -[PKPassLibrary automaticallyPresentedPassForPasses:applicationIdentifier:]
- -[PKPaymentAuthorizationStateMachine _handlePeerPaymentAccountChangedNotification:]
- -[PKPaymentAuthorizationStateMachine hasPendingPeerPaymentUpdate]
- -[PKPaymentAuthorizationStateMachine setHasPendingPeerPaymentUpdate:]
- -[PKPaymentButtonAnalytics _recordEvent:]
- -[PKPaymentButtonAnalytics _recordEvent:withError:]
- -[PKPaymentOffersController didSuccessfulPayment]
- -[PKPaymentProvisioningController allowUserGeneratedPassInUnsupportedRegion]
- -[PKPaymentProvisioningController setAllowUserGeneratedPassInUnsupportedRegion:]
- -[PKSecureElementPass isTruthOnServer]
- -[PKStatefulTransferCredential serialNumber]
- -[PKStatefulTransferCredential setSerialNumber:]
- GCC_except_table114
- GCC_except_table117
- GCC_except_table119
- GCC_except_table133
- GCC_except_table134
- GCC_except_table138
- GCC_except_table145
- GCC_except_table147
- GCC_except_table154
- GCC_except_table156
- GCC_except_table161
- GCC_except_table171
- GCC_except_table180
- GCC_except_table181
- GCC_except_table183
- GCC_except_table191
- GCC_except_table192
- GCC_except_table206
- GCC_except_table215
- GCC_except_table223
- GCC_except_table245
- GCC_except_table261
- GCC_except_table262
- GCC_except_table268
- GCC_except_table275
- GCC_except_table279
- GCC_except_table293
- GCC_except_table317
- GCC_except_table318
- GCC_except_table320
- GCC_except_table343
- GCC_except_table352
- GCC_except_table354
- GCC_except_table359
- GCC_except_table370
- GCC_except_table375
- GCC_except_table383
- GCC_except_table429
- GCC_except_table449
- GCC_except_table465
- GCC_except_table473
- GCC_except_table481
- GCC_except_table483
- GCC_except_table486
- GCC_except_table546
- GCC_except_table554
- GCC_except_table556
- GCC_except_table571
- GCC_except_table574
- GCC_except_table577
- GCC_except_table580
- GCC_except_table598
- GCC_except_table64
- GCC_except_table71
- GCC_except_table891
- _OBJC_IVAR_$_PKPaymentAuthorizationStateMachine._hasPendingPeerPaymentUpdate
- _OBJC_IVAR_$_PKPaymentProvisioningController._allowUserGeneratedPassInUnsupportedRegion
- _OBJC_IVAR_$_PKStatefulTransferCredential._serialNumber
- _PKAccessibilityIdentifierReceiptBubblePayButton
- _PKAccessibilityIdentifierReceiptChargeEditInput
- _PKAccessibilityIdentifierReceiptCustomTaxInput
- _PKAccessibilityIdentifierReceiptCustomTipInput
- _PKAccessibilityIdentifierReceiptEditItemName
- _PKAccessibilityIdentifierReceiptEditPrice
- _PKAccessibilityIdentifierReceiptEditQuantityStepper
- _PKAccessibilityIdentifierReceiptEqualSplit
- _PKAccessibilityIdentifierReceiptLineItemSplit
- _PKAccessibilityIdentifierReceiptOtherChargesRow
- _PKAccessibilityIdentifierReceiptSplitPeopleStepper
- _PKAccessibilityIdentifierReceiptSplitQuantityStepper
- _PKAccessibilityIdentifierReceiptTaxRow
- _PKAccessibilityIdentifierReceiptTipPicker
- _PKAccessibilityIdentifierReceiptTipRow
- _PKAnalyticsReportViewedLineItemKey
- _PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
- __OBJC_$_CLASS_METHODS_PKPaymentApplication(PKPaymentAuthorizationDataModel|Protobuf)
- __OBJC_$_INSTANCE_METHODS_PKPaymentApplication(PKPaymentAuthorizationDataModel|Protobuf)
- ___176-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]_block_invoke
- ___43-[PKDAManager deleteCredential:completion:]_block_invoke
- ___43-[PKDAManager deleteCredential:completion:]_block_invoke_2
- ___44-[PKDAManager deleteCredentials:completion:]_block_invoke
- ___51-[PKPaymentProvisioningController _registerDevice:]_block_invoke_4
- ___51-[PKPaymentProvisioningController _registerDevice:]_block_invoke_5
- ___51-[PKPaymentProvisioningController _registerDevice:]_block_invoke_6
- ___53-[PKPassLibrary deleteKeyMaterialForSubCredentialId:]_block_invoke
- ___58-[PKDAManager deleteCredentialsForIdentifiers:completion:]_block_invoke
- ___58-[PKDAManager deleteCredentialsForIdentifiers:completion:]_block_invoke_2
- ___58-[PKDAManager deleteCredentialsForIdentifiers:completion:]_block_invoke_3
- ___64-[PKDAManager deleteCredentialsForReaderIdentifiers:completion:]_block_invoke
- ___64-[PKDAManager deleteCredentialsForReaderIdentifiers:completion:]_block_invoke_2
- ___64-[PKDAManager deleteCredentialsForReaderIdentifiers:completion:]_block_invoke_3
- ___64-[PKDAManager deleteCredentialsForReaderIdentifiers:completion:]_block_invoke_4
- ___64-[PKPaymentService revokeCredentialsWithIdentifiers:completion:]_block_invoke
- ___70-[PKPaymentService revokeCredentialsWithReaderIdentifiers:completion:]_block_invoke
- ___83-[PKPaymentAuthorizationStateMachine _handlePeerPaymentAccountChangedNotification:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8
- ___swift__destructor.176Tm
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.156Tm
- ___swift_closure_destructor.176Tm
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.209Tm
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.29Tm
- _symbolic ScTy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic Scgy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic _____Sg 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV
- _symbolic _____Sg 18AppIntentsServices0bC0O14InterfaceIdiomO
- _symbolic _____ySaySo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- _symbolic y_____ySaySo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
```
