## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

```diff

-3901.100.1.2.14
-  __TEXT.__text: 0x150358
+3901.200.71.2.2
+  __TEXT.__text: 0x152754
   __TEXT.__delay_helper: 0x114
-  __TEXT.__objc_methlist: 0x12af4
-  __TEXT.__cstring: 0xa1d6
-  __TEXT.__gcc_except_tab: 0x253a0
-  __TEXT.__const: 0x1ff4
+  __TEXT.__objc_methlist: 0x12b44
+  __TEXT.__cstring: 0xa356
+  __TEXT.__gcc_except_tab: 0x256e4
+  __TEXT.__const: 0x2004
   __TEXT.__ustring: 0x4dc
-  __TEXT.__oslogstring: 0x5ffe
+  __TEXT.__oslogstring: 0x647e
   __TEXT.__dlopen_cstrs: 0x4bf
   __TEXT.__swift5_typeref: 0x1894
   __TEXT.__swift5_reflstr: 0x5a8

   __TEXT.__swift_as_entry: 0x28
   __TEXT.__swift_as_ret: 0x2c
   __TEXT.__swift_as_cont: 0x50
-  __TEXT.__unwind_info: 0xa620
+  __TEXT.__unwind_info: 0xa6a0
   __TEXT.__eh_frame: 0x5e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4a18
-  __DATA_CONST.__objc_classlist: 0x628
+  __DATA_CONST.__const: 0x4a88
+  __DATA_CONST.__objc_classlist: 0x618
   __DATA_CONST.__objc_catlist: 0x108
   __DATA_CONST.__objc_protolist: 0x418
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc2c8
+  __DATA_CONST.__objc_selrefs: 0xc360
   __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0x4b0
-  __DATA_CONST.__objc_arraydata: 0x648
-  __DATA_CONST.__got: 0x1ef0
-  __AUTH_CONST.__const: 0x1c90
+  __DATA_CONST.__objc_superrefs: 0x4a8
+  __DATA_CONST.__objc_arraydata: 0x638
+  __DATA_CONST.__got: 0x1f10
+  __AUTH_CONST.__const: 0x1cd0
   __AUTH_CONST.__cfstring: 0x8f00
-  __AUTH_CONST.__objc_const: 0x1a860
+  __AUTH_CONST.__objc_const: 0x1a788
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x1b0
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__objc_dictobj: 0x5a0
-  __AUTH_CONST.__auth_got: 0x1900
+  __AUTH_CONST.__objc_dictobj: 0x578
+  __AUTH_CONST.__auth_got: 0x18f0
   __AUTH_CONST.__auth_ptr: 0x5a8
-  __AUTH.__objc_data: 0x3588
-  __AUTH.__data: 0x360
-  __DATA.__objc_ivar: 0x114c
-  __DATA.__data: 0x3818
-  __DATA.__bss: 0x1d60
+  __AUTH.__objc_data: 0x34e8
+  __AUTH.__data: 0x358
+  __DATA.__objc_ivar: 0x1154
+  __DATA.__data: 0x3870
+  __DATA.__bss: 0x1d50
   __DATA.__common: 0x2f8
   __DATA_DIRTY.__objc_data: 0xb90
   __DATA_DIRTY.__data: 0x8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6882
-  Symbols:   11672
+  Functions: 6906
+  Symbols:   11676
   CStrings:  0
 
Symbols:
+ +[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]
+ +[MFComposeTypeFactory _recipientAddressLooksLikeHMEAddress:]
+ +[MFComposeTypeFactory _sanitizeRecipientsWithDelegate:]
+ -[MFComposeWebView _composeToolbarUsageDidChange]
+ -[MFComposeWebView _formattingToolbarItem]
+ -[MFComposeWebView _setNeedsComposeToolbarUsageUpdate]
+ -[MFComposeWebView _supportsComposeToolbar]
+ -[MFComposeWebView _updateHingeClosed:]
+ -[MFComposeWebView set_formattingToolbarItem:]
+ -[MFMailComposeController _representStyleSelectorAfterTransition:]
+ -[MFMailComposeController _representStyleSelectorIfPresentationStyleChanged]
+ -[MFMailComposeController _styleSelectorPresentedViewController]
+ -[MFMailComposeController _styleSelectorSizeClassDidChange]
+ -[MFMailComposeController setSizeTransitionCount:]
+ -[MFMailComposeController setStyleSelectorSender:]
+ -[MFMailComposeController sizeTransitionCount]
+ -[MFMailComposeController styleSelectorSender]
+ -[MFMailComposeController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[MFMailRecipients _sanitizeIsReplyAll:sendingEmailAddress:replyAllCCMatcher:]
+ -[MFMailRecipients sanitizeForReplyAllWithSendingEmailAddress:replyAllCCMatcher:]
+ -[MFMailRecipients sanitize]
+ GCC_except_table235
+ GCC_except_table242
+ GCC_except_table253
+ GCC_except_table268
+ GCC_except_table482
+ GCC_except_table486
+ GCC_except_table489
+ GCC_except_table493
+ GCC_except_table496
+ GCC_except_table502
+ GCC_except_table506
+ GCC_except_table511
+ GCC_except_table518
+ GCC_except_table519
+ GCC_except_table527
+ GCC_except_table543
+ GCC_except_table567
+ GCC_except_table569
+ GCC_except_table573
+ GCC_except_table576
+ GCC_except_table582
+ GCC_except_table590
+ GCC_except_table592
+ GCC_except_table594
+ GCC_except_table601
+ GCC_except_table607
+ GCC_except_table610
+ GCC_except_table613
+ GCC_except_table617
+ GCC_except_table622
+ GCC_except_table632
+ GCC_except_table639
+ GCC_except_table654
+ GCC_except_table658
+ GCC_except_table667
+ GCC_except_table675
+ GCC_except_table676
+ GCC_except_table683
+ GCC_except_table698
+ GCC_except_table704
+ GCC_except_table705
+ GCC_except_table706
+ GCC_except_table707
+ GCC_except_table709
+ GCC_except_table710
+ GCC_except_table711
+ GCC_except_table712
+ GCC_except_table713
+ GCC_except_table829
+ GCC_except_table830
+ GCC_except_table833
+ GCC_except_table834
+ GCC_except_table836
+ GCC_except_table838
+ GCC_except_table839
+ GCC_except_table840
+ _EFStringsAreEqual
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_IVAR_$_MFComposeWebView.__formattingToolbarItem
+ _OBJC_IVAR_$_MFComposeWebView._composeToolbarInUse
+ _OBJC_IVAR_$_MFComposeWebView._composeToolbarUsageUpdateScheduled
+ _OBJC_IVAR_$_MFComposeWebView._hingeClosed
+ _OBJC_IVAR_$_MFMailComposeController._sizeTransitionCount
+ _OBJC_IVAR_$_MFMailComposeController._styleSelectorSender
+ ___54-[MFComposeWebView _setNeedsComposeToolbarUsageUpdate]_block_invoke
+ ___66+[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]_block_invoke
+ ___66+[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]_block_invoke_2
+ ___66-[MFMailComposeController _representStyleSelectorAfterTransition:]_block_invoke
+ ___66-[MFMailComposeController _representStyleSelectorAfterTransition:]_block_invoke_2
+ ___66-[MFMailComposeController _representStyleSelectorAfterTransition:]_block_invoke_3
+ ___76-[MFMailComposeController _representStyleSelectorIfPresentationStyleChanged]_block_invoke
+ ___78-[MFMailComposeController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___ECEmailAddressConvertiblePublicDescriptions_block_invoke
+ ___block_descriptor_33_e31_B24?0"NSString"8"NSString"16l
+ ___block_descriptor_40_ea8_32bs_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
+ ___block_descriptor_40_ea8_32w_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8lw32l8
+ ___block_descriptor_48_ea8_32s40s_e26_B16?0"UIViewController"8ls32l8s40l8
+ ___block_descriptor_65_ea8_32s40s48s56w_e5_v8?0lw56l8s32l8s40l8s48l8
- +[MFComposeTypeFactory _sanitizeRecipientsForComposeType:sendingAddress:delegate:]
- +[MFDataDetectors _DDURLifierClass]
- +[MFDataDetectors sharedDetectionController]
- +[MFDataDetectors urlIfyNode:]
- +[MFDataDetectors urlIfyNode:phoneNumberTypes:]
- +[MFDataDetectors urlMatchesForString:]
- +[MFDataDetectors urlMatchesForString:includingTel:]
- -[MFComposeDropPreviewView .cxx_destruct]
- -[MFComposeDropPreviewView finalImage]
- -[MFComposeDropPreviewView imageView]
- -[MFComposeDropPreviewView initWithFrame:]
- -[MFComposeDropPreviewView previewClippingPath]
- -[MFComposeDropPreviewView previewView]
- -[MFComposeDropPreviewView setFinalImage:]
- -[MFComposeDropPreviewView setImageView:]
- -[MFComposeDropPreviewView setPreviewClippingPath:]
- -[MFComposeDropPreviewView setPreviewView:]
- -[MFMailRecipients sanitizeForComposeType:sendingEmailAddress:hideMyEmailAddressProvider:]
- GCC_except_table176
- GCC_except_table177
- GCC_except_table237
- GCC_except_table254
- GCC_except_table255
- GCC_except_table273
- GCC_except_table484
- GCC_except_table490
- GCC_except_table491
- GCC_except_table495
- GCC_except_table500
- GCC_except_table504
- GCC_except_table510
- GCC_except_table513
- GCC_except_table520
- GCC_except_table521
- GCC_except_table529
- GCC_except_table545
- GCC_except_table568
- GCC_except_table570
- GCC_except_table575
- GCC_except_table577
- GCC_except_table584
- GCC_except_table591
- GCC_except_table593
- GCC_except_table598
- GCC_except_table602
- GCC_except_table609
- GCC_except_table611
- GCC_except_table616
- GCC_except_table618
- GCC_except_table623
- GCC_except_table634
- GCC_except_table640
- GCC_except_table646
- GCC_except_table648
- GCC_except_table664
- GCC_except_table668
- GCC_except_table677
- GCC_except_table685
- GCC_except_table693
- GCC_except_table815
- GCC_except_table816
- GCC_except_table819
- GCC_except_table820
- GCC_except_table822
- GCC_except_table824
- GCC_except_table825
- _CGAffineTransformTranslate
- _NSClassFromString
- _OBJC_CLASS_$_MFComposeDropPreviewView
- _OBJC_CLASS_$_MFDataDetectors
- _OBJC_IVAR_$_MFComposeDropPreviewView._finalImage
- _OBJC_IVAR_$_MFComposeDropPreviewView._imageView
- _OBJC_IVAR_$_MFComposeDropPreviewView._previewClippingPath
- _OBJC_IVAR_$_MFComposeDropPreviewView._previewView
- _OBJC_METACLASS_$_MFComposeDropPreviewView
- _OBJC_METACLASS_$_MFDataDetectors
- _UISystemRootDirectory
- __DDURLifierClass._DDURLifierClass
- __DDURLifierClass.inited
- __OBJC_$_CLASS_METHODS_MFDataDetectors
- __OBJC_$_INSTANCE_METHODS_MFComposeDropPreviewView
- __OBJC_$_INSTANCE_VARIABLES_MFComposeDropPreviewView
- __OBJC_$_PROP_LIST_MFComposeDropPreviewView
- __OBJC_CLASS_RO_$_MFComposeDropPreviewView
- __OBJC_CLASS_RO_$_MFDataDetectors
- __OBJC_METACLASS_RO_$_MFComposeDropPreviewView
- __OBJC_METACLASS_RO_$_MFDataDetectors
- ___42-[MFComposeDropPreviewView setFinalImage:]_block_invoke
- ___43-[MFComposeDropPreviewView setPreviewView:]_block_invoke
- ___73-[MFMailComposeController composeRecipientViewDidFinishPickingRecipient:]_block_invoke
- ___82+[MFComposeTypeFactory _sanitizeRecipientsForComposeType:sendingAddress:delegate:]_block_invoke
- ___block_descriptor_40_ea8_32s_e14_"NSArray"8?0ls32l8
- ___block_descriptor_48_ea8_32s40s_e26_v16?0"UIViewController"8ls32l8s40l8
- _sharedDetectionController._DDDetectionControllerClass
- _sharedDetectionController.inited
```
