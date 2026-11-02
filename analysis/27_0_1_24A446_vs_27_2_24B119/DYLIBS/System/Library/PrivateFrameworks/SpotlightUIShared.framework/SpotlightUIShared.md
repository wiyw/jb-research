## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

```diff

-236.0.21.105.0
-  __TEXT.__text: 0xe1d08
-  __TEXT.__objc_methlist: 0xf08
-  __TEXT.__const: 0xa25c
-  __TEXT.__cstring: 0x3408
-  __TEXT.__gcc_except_tab: 0x18
-  __TEXT.__oslogstring: 0x1352
-  __TEXT.__ustring: 0x7de
-  __TEXT.__swift5_typeref: 0x3446
-  __TEXT.__swift5_reflstr: 0x1ca8
+250.1.12.200.0
+  __TEXT.__text: 0xe659c
+  __TEXT.__objc_methlist: 0xff0
+  __TEXT.__const: 0xa56c
+  __TEXT.__cstring: 0x3528
+  __TEXT.__gcc_except_tab: 0x28
+  __TEXT.__oslogstring: 0x1602
+  __TEXT.__ustring: 0x7e2
+  __TEXT.__swift5_typeref: 0x3476
+  __TEXT.__swift5_reflstr: 0x1ce8
   __TEXT.__swift5_assocty: 0xb20
-  __TEXT.__constg_swiftt: 0x37fc
-  __TEXT.__swift5_fieldmd: 0x21a4
+  __TEXT.__constg_swiftt: 0x3848
+  __TEXT.__swift5_fieldmd: 0x21f0
   __TEXT.__swift5_proto: 0x7b8
-  __TEXT.__swift5_types: 0x32c
-  __TEXT.__swift_as_entry: 0x5a8
-  __TEXT.__swift_as_ret: 0x50c
-  __TEXT.__swift_as_cont: 0x77c
+  __TEXT.__swift5_types: 0x334
+  __TEXT.__swift_as_entry: 0x664
+  __TEXT.__swift_as_ret: 0x5cc
+  __TEXT.__swift_as_cont: 0x788
   __TEXT.__swift5_protos: 0x9c
   __TEXT.__swift5_capture: 0x718
   __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_mpenum: 0x34
-  __TEXT.__unwind_info: 0x41c8
-  __TEXT.__eh_frame: 0x8c9c
+  __TEXT.__unwind_info: 0x4368
+  __TEXT.__eh_frame: 0x9364
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x658
+  __DATA_CONST.__const: 0x6e0
   __DATA_CONST.__objc_classlist: 0x200
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1608
+  __DATA_CONST.__objc_selrefs: 0x1718
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x1018
-  __AUTH_CONST.__const: 0x6e31
-  __AUTH_CONST.__cfstring: 0x7a0
-  __AUTH_CONST.__objc_const: 0x3ac8
+  __DATA_CONST.__got: 0x10a8
+  __AUTH_CONST.__const: 0x6f91
+  __AUTH_CONST.__cfstring: 0x900
+  __AUTH_CONST.__objc_const: 0x3ae8
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1d30
+  __AUTH_CONST.__auth_got: 0x1d68
   __AUTH_CONST.__auth_ptr: 0x10f8
   __AUTH.__objc_data: 0x1580
-  __AUTH.__data: 0x3828
+  __AUTH.__data: 0x36e8
   __DATA.__objc_ivar: 0x84
-  __DATA.__data: 0x1ce0
+  __DATA.__data: 0x1cb0
   __DATA.__objc_stublist: 0x8
-  __DATA.__bss: 0xe7b0
-  __DATA.__common: 0x1a0
-  __DATA_DIRTY.__objc_data: 0x338
-  __DATA_DIRTY.__data: 0x210
-  __DATA_DIRTY.__bss: 0x870
+  __DATA.__bss: 0xe560
+  __DATA.__common: 0x190
+  __DATA_DIRTY.__objc_data: 0x388
+  __DATA_DIRTY.__data: 0x400
+  __DATA_DIRTY.__bss: 0xb20
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/AppIntents.framework/AppIntents
   - /System/Library/Frameworks/Combine.framework/Combine

   - /System/Library/Frameworks/LinkPresentation.framework/LinkPresentation
   - /System/Library/Frameworks/MapKit.framework/MapKit
   - /System/Library/Frameworks/QuartzCore.framework/QuartzCore
+  - /System/Library/Frameworks/Security.framework/Security
   - /System/Library/Frameworks/SwiftUI.framework/SwiftUI
   - /System/Library/Frameworks/UIKit.framework/UIKit
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5206
-  Symbols:   2268
+  Functions: 5300
+  Symbols:   2327
   CStrings:  0
 
Symbols:
+ +[SUISPasteboardExtractor createIdentifierKey]
+ +[SUISPasteboardExtractor finalizeUniqueIdentifierForAttributeSet:]
+ +[SUISPasteboardExtractor hashStringFromData:]
+ +[SUISPasteboardExtractor hashStringFromRawHash:]
+ +[SUISPasteboardExtractor hashStringFromString:key:]
+ +[SUISPasteboardExtractor identifierKeyQuery]
+ +[SUISPasteboardExtractor identifierKey]
+ +[SUISPasteboardExtractor loadIdentifierKey]
+ +[SUISPasteboardExtractor readIdentifierKeyWithStatus:]
+ +[SUISPasteboardManager carryOverHistoryAttributesTo:from:]
+ +[SUISPasteboardManager indexActionForAttributeSet:generationCount:lastIndexedAttributeSet:lastIndexedGeneration:hasNewlyCachedFiles:]
+ +[SUISPasteboardManager pasteboardIndexingQueue]
+ +[SUIUtilities isSearchFieldAutocorrectAlwaysEnabled]
+ -[SUISPasteboardManager clearPasteboardHistoryIfWipeRequested]
+ -[SUISPasteboardManager deleteCachedFiles:]
+ -[SUISPasteboardManager deleteStalePasteboardItem:]
+ -[SUISPasteboardManager forgetLastIndexedAttributeSet:]
+ -[SUISPasteboardManager historyItemCopiedGeneration]
+ -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]
+ -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]
+ -[SUISPasteboardManager lastIndexedAttributeSet]
+ -[SUISPasteboardManager lastIndexedGeneration]
+ -[SUISPasteboardManager setHistoryItemCopiedGeneration:]
+ -[SUISPasteboardManager setLastIndexedAttributeSet:]
+ -[SUISPasteboardManager setLastIndexedGeneration:]
+ GCC_except_table4
+ _CCHmac
+ _CC_SHA256
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_IVAR_$_SUISPasteboardManager._historyItemCopiedGeneration
+ _OBJC_IVAR_$_SUISPasteboardManager._lastIndexedAttributeSet
+ _OBJC_IVAR_$_SUISPasteboardManager._lastIndexedGeneration
+ _OUTLINED_FUNCTION_1
+ _SUISCorespotlightLog
+ _SUISCorespotlightLog.log
+ _SUISCorespotlightLog.once
+ _SecItemAdd
+ _SecItemCopyMatching
+ _SecRandomCopyBytes
+ __CLASS_METHODS_SUISWindowDisplayPolicy
+ __OBJC_$_CLASS_METHODS_SUISPasteboardExtractor
+ ___109-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]_block_invoke
+ ___48+[SUISPasteboardManager pasteboardIndexingQueue]_block_invoke
+ ___52-[SUICompletionViewController updateCompletionViews]_block_invoke
+ ___55-[SUISPasteboardManager forgetLastIndexedAttributeSet:]_block_invoke
+ ___91-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]_block_invoke
+ ___SUISCorespotlightLog_block_invoke
+ ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_40_e8_32s_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56s_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
+ ___swift_memcpy225_8
+ ___swift_memcpy96_8
+ _get_enum_tag_for_layout_string 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextVIeghn_Sg
+ _kSecAttrAccessGroup
+ _kSecAttrAccessible
+ _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
+ _kSecAttrAccount
+ _kSecAttrService
+ _kSecAttrSynchronizable
+ _kSecClass
+ _kSecClassGenericPassword
+ _kSecRandomDefault
+ _kSecReturnData
+ _kSecUseDataProtectionKeychain
+ _kSecValueData
+ _objc_retain_x4
+ _pasteboardIndexingQueue.onceToken
+ _pasteboardIndexingQueue.queue
+ _sIdentifierKey
+ _swift_getDynamicType
+ _symbolic _____ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic _____Ieghn_ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic _____ytIeghnr_ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic y_____YbScMYccSg 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _type_layout_string 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
- +[SUISPasteboardManager pasteboardExpirationManagerQueue]
- -[SUISPasteboardManager changeCount]
- -[SUISPasteboardManager foundItems]
- -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]
- -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]
- -[SUISPasteboardManager pasteboardHistoryItemWasCopied]
- -[SUISPasteboardManager setChangeCount:]
- -[SUISPasteboardManager setFoundItems:]
- -[SUISPasteboardManager setPasteboardHistoryItemWasCopied:]
- _OBJC_IVAR_$_SUISPasteboardManager._changeCount
- _OBJC_IVAR_$_SUISPasteboardManager._foundItems
- _OBJC_IVAR_$_SUISPasteboardManager._pasteboardHistoryItemWasCopied
- ___57+[SUISPasteboardManager pasteboardExpirationManagerQueue]_block_invoke
- ___64-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]_block_invoke
- ___76-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- ___swift_memcpy193_8
- ___swift_memcpy64_8
- _pasteboardExpirationManagerQueue.onceToken
- _pasteboardExpirationManagerQueue.queue
```
