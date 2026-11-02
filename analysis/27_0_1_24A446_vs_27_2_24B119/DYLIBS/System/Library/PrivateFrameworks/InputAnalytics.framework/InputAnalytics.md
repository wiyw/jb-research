## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

```diff

-153.0.0.0.0
-  __TEXT.__text: 0x1fbdc
-  __TEXT.__objc_methlist: 0x26cc
+154.1.8.0.0
+  __TEXT.__text: 0x2037c
+  __TEXT.__objc_methlist: 0x27bc
   __TEXT.__const: 0x32a
-  __TEXT.__gcc_except_tab: 0x390
-  __TEXT.__cstring: 0x61a2
-  __TEXT.__oslogstring: 0x27ac
+  __TEXT.__gcc_except_tab: 0x384
+  __TEXT.__cstring: 0x6602
+  __TEXT.__oslogstring: 0x27fc
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x8b
   __TEXT.__constg_swiftt: 0x4c

   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__unwind_info: 0x980
+  __TEXT.__unwind_info: 0x9c0
   __TEXT.__eh_frame: 0x308
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ff0
-  __DATA_CONST.__objc_classlist: 0x1c0
+  __DATA_CONST.__const: 0x21d8
+  __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1250
+  __DATA_CONST.__objc_selrefs: 0x12a0
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x100
+  __DATA_CONST.__objc_superrefs: 0x108
   __DATA_CONST.__objc_arraydata: 0xea0
-  __DATA_CONST.__got: 0x278
-  __AUTH_CONST.__const: 0x628
-  __AUTH_CONST.__cfstring: 0x9480
-  __AUTH_CONST.__objc_const: 0x4208
-  __AUTH_CONST.__objc_intobj: 0x1260
+  __DATA_CONST.__got: 0x288
+  __AUTH_CONST.__const: 0x648
+  __AUTH_CONST.__cfstring: 0x9b00
+  __AUTH_CONST.__objc_const: 0x4338
+  __AUTH_CONST.__objc_intobj: 0x12a8
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x4a0
+  __AUTH_CONST.__auth_got: 0x4a8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xa70
+  __AUTH.__objc_data: 0xa98
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x230
+  __DATA.__objc_ivar: 0x23c
   __DATA.__data: 0x300
-  __DATA.__bss: 0x138
-  __DATA_DIRTY.__objc_data: 0x730
+  __DATA.__bss: 0x148
+  __DATA_DIRTY.__objc_data: 0x758
   __DATA_DIRTY.__bss: 0xe8
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1046
-  Symbols:   2675
+  Functions: 1067
+  Symbols:   2771
   CStrings:  0
 
Symbols:
+ +[IASAnalyzer shouldSendToBiomeStream]
+ +[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) supportsSecureCoding]
+ -[IASAnalyzer setTestDelegate:]
+ -[IASAnalyzer testDelegate]
+ -[IATextInputActionsAnalytics didMeasureKeyboardLatency:]
+ -[IATextInputActionsAnalytics(TestingSupport) setFlushedActionObserver:]
+ -[IATextInputActionsSessionAction asKeyboardLatency]
+ -[IATextInputActionsSessionKeyboardLatencyAction .cxx_destruct]
+ -[IATextInputActionsSessionKeyboardLatencyAction changedContent]
+ -[IATextInputActionsSessionKeyboardLatencyAction description]
+ -[IATextInputActionsSessionKeyboardLatencyAction inputActionCount]
+ -[IATextInputActionsSessionKeyboardLatencyAction keystrokeLatenciesMsByInputType]
+ -[IATextInputActionsSessionKeyboardLatencyAction setKeystrokeLatenciesMsByInputType:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) encodeWithCoder:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) initFromDictionary:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) initWithCoder:]
+ -[IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding) toDictionary]
+ _CTOSPlatformAll
+ _IAPayloadKeyImageGenerationBlockingSafetyModel
+ _IAPayloadKeyImageGenerationFailureReason
+ _IAPayloadKeyImageGenerationNumInputImages
+ _IAPayloadKeyImageGenerationStyleEnum
+ _IAPayloadValueGenmojiUsageSourceFindAndReplace
+ _IAPayloadValueGenmojiUsageSourcePreGenerated
+ _IAPayloadValueGenmojiUsageTypeDelete
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceAccepted
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceHighlightShown
+ _IAPayloadValueGenmojiUsageTypeFindAndReplaceSuggestionShown
+ _IAPayloadValueGenmojiUsageTypeOther
+ _IAPayloadValueGenmojiUsageTypeShare
+ _IAPayloadValueImageGenerationBlockingSafetyModelMultimodalGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelPixelGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelTextGuardrail
+ _IAPayloadValueImageGenerationBlockingSafetyModelUnspecified
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryAppleProducts
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryBlocklistDrugs
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryCopyright
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryCustomWords
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryDesecration
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryMinor
+ _IAPayloadValueImageGenerationFailureReasonBlocklistCategoryPersonalization
+ _IAPayloadValueImageGenerationFailureReasonExternalGeneratorNetworkFailure
+ _IAPayloadValueImageGenerationFailureReasonExternalGeneratorRateLimited
+ _IAPayloadValueImageGenerationFailureReasonLexiconOrLanguage
+ _IAPayloadValueImageGenerationFailureReasonModelsDownloading
+ _IAPayloadValueImageGenerationFailureReasonPCCErrors
+ _IAPayloadValueImageGenerationFailureReasonPCCNoNodesAvailable
+ _IAPayloadValueImageGenerationFailureReasonSWErrors
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryCSEAI
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryCopyright
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryDrugs
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryHarassment
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryHate
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryIdentityEditing
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryMapsAndFlags
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryNudity
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryOffensive
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryPhotorealism
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryPublicFigure
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryRacy
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategorySelfHarm
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategorySuggestive
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryTerrorism
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryToxic
+ _IAPayloadValueImageGenerationFailureReasonSafetyCategoryViolenceAndGore
+ _IAPayloadValueImageGenerationFailureReasonUnspecified
+ _IAPayloadValueSidecarInteractionModalitySidecar
+ _IASignalSmartRepliesMailFormattingBarIntentDismissed
+ _IASignalSmartRepliesMailFormattingBarIntentEngaged
+ _IASignalSmartRepliesMailFormattingBarIntentShown
+ _IASignalWritingToolsMailFormattingBarActionDismissed
+ _IASignalWritingToolsMailFormattingBarActionEngaged
+ _IASignalWritingToolsMailFormattingBarActionShown
+ _IATextInputActionsKeyboardTypeFloating
+ _IATextInputActionsKeyboardTypeHardware
+ _IATextInputActionsKeyboardTypeLandscape
+ _IATextInputActionsKeyboardTypePortrait
+ _IATextInputActionsKeyboardTypeSplit
+ _IATextInputActionsKeyboardTypeWebSuffix
+ _NSClassFromString
+ _OBJC_CLASS_$_CTCategory
+ _OBJC_CLASS_$_IATextInputActionsSessionKeyboardLatencyAction
+ _OBJC_IVAR_$_IASAnalyzer._testDelegate
+ _OBJC_IVAR_$_IATextInputActionsAnalytics._flushedActionObserver
+ _OBJC_IVAR_$_IATextInputActionsSessionKeyboardLatencyAction._keystrokeLatenciesMsByInputType
+ _OBJC_METACLASS_$_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_$_CLASS_METHODS_IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding)
+ __OBJC_$_INSTANCE_METHODS_IATextInputActionsSessionKeyboardLatencyAction(NSSecureCoding)
+ __OBJC_$_INSTANCE_VARIABLES_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_$_PROP_LIST_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_IXAXPCProtocol
+ __OBJC_CLASS_RO_$_IATextInputActionsSessionKeyboardLatencyAction
+ __OBJC_METACLASS_RO_$_IATextInputActionsSessionKeyboardLatencyAction
+ ___38+[IASAnalyzer shouldSendToBiomeStream]_block_invoke
+ ___57-[IATextInputActionsAnalytics didMeasureKeyboardLatency:]_block_invoke
+ _shouldSendToBiomeStream.isRunningUnderXCTest
+ _shouldSendToBiomeStream.onceToken
- _OBJC_CLASS_$_CTCategories
```
