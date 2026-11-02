## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

```diff

-149.104.0.0.0
-  __TEXT.__text: 0x6cf40
-  __TEXT.__objc_methlist: 0x4ccc
-  __TEXT.__const: 0x30c4
-  __TEXT.__cstring: 0x3737
-  __TEXT.__oslogstring: 0x1f2d
-  __TEXT.__gcc_except_tab: 0xd6c
+151.1.11.100.0
+  __TEXT.__text: 0x6f0e8
+  __TEXT.__objc_methlist: 0x4e1c
+  __TEXT.__const: 0x30d4
+  __TEXT.__cstring: 0x3797
+  __TEXT.__oslogstring: 0x23fd
+  __TEXT.__gcc_except_tab: 0xe24
   __TEXT.__dlopen_cstrs: 0xb4
   __TEXT.__swift5_typeref: 0xdf52
   __TEXT.__swift5_capture: 0x47c
-  __TEXT.__swift5_reflstr: 0xe3c
+  __TEXT.__swift5_reflstr: 0xe7c
   __TEXT.__swift5_assocty: 0x290
-  __TEXT.__constg_swiftt: 0xfec
-  __TEXT.__swift5_fieldmd: 0xcbc
+  __TEXT.__constg_swiftt: 0x1004
+  __TEXT.__swift5_fieldmd: 0xce0
   __TEXT.__swift5_builtin: 0x104
   __TEXT.__swift5_proto: 0x194
   __TEXT.__swift5_types: 0xc0

   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x20
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x1cc0
+  __TEXT.__unwind_info: 0x1d68
   __TEXT.__eh_frame: 0x8c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe10
+  __DATA_CONST.__const: 0xeb8
   __DATA_CONST.__objc_classlist: 0x178
-  __DATA_CONST.__objc_catlist: 0x28
+  __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30d8
+  __DATA_CONST.__objc_selrefs: 0x31e0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0xa40
-  __AUTH_CONST.__const: 0x2140
+  __DATA_CONST.__got: 0xa70
+  __AUTH_CONST.__const: 0x2198
   __AUTH_CONST.__cfstring: 0xfe0
-  __AUTH_CONST.__objc_const: 0x69c8
-  __AUTH_CONST.__objc_intobj: 0x570
+  __AUTH_CONST.__objc_const: 0x6a98
+  __AUTH_CONST.__objc_intobj: 0x588
   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__objc_arrayobj: 0x60
-  __AUTH_CONST.__auth_got: 0xf60
+  __AUTH_CONST.__auth_got: 0xf70
   __AUTH_CONST.__auth_ptr: 0x980
-  __AUTH.__objc_data: 0x14b0
+  __AUTH.__objc_data: 0x14d0
   __AUTH.__data: 0x900
-  __DATA.__objc_ivar: 0x38c
-  __DATA.__data: 0x1f08
+  __DATA.__objc_ivar: 0x394
+  __DATA.__data: 0x1f60
   __DATA.__bss: 0x3510
-  __DATA.__common: 0x118
+  __DATA.__common: 0x120
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__bss: 0x90

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3011
-  Symbols:   3210
+  Functions: 3064
+  Symbols:   3253
   CStrings:  0
 
Symbols:
+ +[WTFeedbackProxy sendComposeFeedback:range:finished:compositionSessionType:]
+ +[WTUIActionHostToClient actionForPerformRequestedTool:precomputedData:]
+ -[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]
+ -[NSUndoManager(WTTurnTracking) wt_registerUndoIfPossibleWithTarget:handler:]
+ -[WTFullScreenContainerViewController performRequestedTool:precomputedData:]
+ -[WTMainPopoverViewController adaptivePresentationStyleForPresentationController:traitCollection:]
+ -[WTMainPopoverViewController performRequestedTool:precomputedData:]
+ -[WTSceneHostedInputDashboardViewController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController _reconcileCountsForTurnUndone:]
+ -[WTWritingToolsController _registerUndoTrackingTurnOnUndoManager:]
+ -[WTWritingToolsController _targetCanHostInlineEditing]
+ -[WTWritingToolsController _targetIsWebKitTextInput]
+ -[WTWritingToolsController _targetPrefersLimitedUI]
+ -[WTWritingToolsController canPerformRequestedToolOnCurrentSession]
+ -[WTWritingToolsController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController performRequestedToolOnCurrentSession]
+ -[WTWritingToolsController precomputedData]
+ -[WTWritingToolsController rewriteResultApplied]
+ -[WTWritingToolsController setPrecomputedData:]
+ -[WTWritingToolsController setRewriteResultApplied:]
+ -[WTWritingToolsController setUndoTrackingUnavailable:]
+ -[WTWritingToolsController undoTrackingUnavailable]
+ -[_WTReplaceTextEffect clipsToDestinationRect]
+ -[_WTReplaceTextEffect setClipsToDestinationRect:]
+ -[_WTTextEffectView hasManagedFrame]
+ -[_WTTextEffectView replaceSourceEffect]
+ -[_WTTextEffectView setHasManagedFrame:]
+ -[_WTTextEffectView setReplaceSourceEffect:]
+ GCC_except_table10
+ GCC_except_table125
+ GCC_except_table131
+ GCC_except_table184
+ GCC_except_table187
+ GCC_except_table231
+ GCC_except_table238
+ GCC_except_table240
+ GCC_except_table242
+ GCC_except_table50
+ GCC_except_table76
+ GCC_except_table78
+ GCC_except_table86
+ _NSInternalInconsistencyException
+ _OBJC_CLASS_$_NSUndoManager
+ _OBJC_CLASS_$_WTPrecomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._precomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._rewriteResultApplied
+ _OBJC_IVAR_$_WTWritingToolsController._undoTrackingUnavailable
+ _OBJC_IVAR_$__WTReplaceTextEffect._clipsToDestinationRect
+ _OBJC_IVAR_$__WTTextEffectView._hasManagedFrame
+ _OBJC_IVAR_$__WTTextEffectView._replaceSourceEffect
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUndoManager_$_WTTurnTracking
+ __OBJC_$_CATEGORY_NSUndoManager_$_WTTurnTracking
+ ___48-[WTWritingToolsController beginTextPlaceholder]_block_invoke
+ ___60-[NSUndoManager(WTTurnTracking) wt_registerTurnWithHandler:]_block_invoke
+ ___65-[WTWritingToolsController didBeginWritingToolsSession:contexts:]_block_invoke
+ ___67-[WTWritingToolsController _registerUndoTrackingTurnOnUndoManager:]_block_invoke
+ ___block_descriptor_32_e8_v16?08l
+ ___block_descriptor_40_e8_32bs_e23_v16?0"NSUndoManager"8ls32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0lw56l8s32l8s48l8s40l8
+ _keypath_get.30Tm
+ _keypath_get.32Tm
+ _keypath_get.40Tm
+ _keypath_get.52Tm
+ _keypath_set.33Tm
+ _objc_exception_rethrow
- +[WTFeedbackProxy sendComposeFeedback:range:finished:]
- +[WTFeedbackProxy sendRewriteFeedback:range:finished:]
- GCC_except_table109
- GCC_except_table115
- GCC_except_table152
- GCC_except_table171
- GCC_except_table212
- GCC_except_table219
- GCC_except_table221
- GCC_except_table223
- GCC_except_table34
- GCC_except_table72
- _OBJC_IVAR_$_WTWritingToolsController._precomputedCitationsJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedContentAdvisoriesJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultReplacesExisting
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultText
- _OUTLINED_FUNCTION_4
- ___76-[WTWritingToolsController _presentMainPopoverViewControllerWithCompletion:]_block_invoke_2
- _keypath_get.29Tm
- _keypath_get.31Tm
- _keypath_get.39Tm
- _keypath_get.51Tm
- _keypath_set.32Tm
```
