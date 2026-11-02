## MobileMailUI

> `/System/Library/PrivateFrameworks/MobileMailUI.framework/MobileMailUI`

### Sections with Same Size but Changed Content

- `__TEXT.__ustring`

```diff

-3901.100.1.2.14
-  __TEXT.__text: 0x4ec7c
-  __TEXT.__objc_methlist: 0x5314
-  __TEXT.__gcc_except_tab: 0x9938
-  __TEXT.__cstring: 0x349c
+3901.200.71.2.2
+  __TEXT.__text: 0x4f194
+  __TEXT.__objc_methlist: 0x53b4
+  __TEXT.__gcc_except_tab: 0x9994
+  __TEXT.__const: 0x8504
+  __TEXT.__cstring: 0x348c
   __TEXT.__ustring: 0x318
-  __TEXT.__const: 0x8514
-  __TEXT.__oslogstring: 0x2397
+  __TEXT.__oslogstring: 0x24b7
   __TEXT.__dlopen_cstrs: 0x97
   __TEXT.__swift5_typeref: 0x2a2
   __TEXT.__swift5_capture: 0x128
   __TEXT.__swift5_fieldmd: 0x80
   __TEXT.__constg_swiftt: 0x1c4
-  __TEXT.__swift5_reflstr: 0x3a
+  __TEXT.__swift5_reflstr: 0x41
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_types: 0x14
   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x18
   __TEXT.__swift_as_cont: 0x28
-  __TEXT.__unwind_info: 0x2a80
+  __TEXT.__unwind_info: 0x2ab0
   __TEXT.__eh_frame: 0x1b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1378
+  __DATA_CONST.__const: 0x1370
   __DATA_CONST.__objc_classlist: 0x200
-  __DATA_CONST.__objc_catlist: 0x30
+  __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4250
+  __DATA_CONST.__objc_selrefs: 0x42d0
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0xe8
-  __DATA_CONST.__got: 0xb50
+  __DATA_CONST.__got: 0xb60
   __AUTH_CONST.__const: 0x730
-  __AUTH_CONST.__cfstring: 0x31a0
-  __AUTH_CONST.__objc_const: 0x8028
+  __AUTH_CONST.__cfstring: 0x3160
+  __AUTH_CONST.__objc_const: 0x80e0
   __AUTH_CONST.__objc_intobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x20

   __AUTH_CONST.__auth_ptr: 0x0
   __AUTH.__objc_data: 0xa60
   __AUTH.__data: 0xe8
-  __DATA.__objc_ivar: 0x4dc
+  __DATA.__objc_ivar: 0x4f4
   __DATA.__data: 0x1158
   __DATA.__bss: 0x48
   __DATA.__common: 0x78

   - /System/Library/PrivateFrameworks/EmailCore.framework/EmailCore
   - /System/Library/PrivateFrameworks/EmailDaemon.framework/EmailDaemon
   - /System/Library/PrivateFrameworks/EmailFoundation.framework/EmailFoundation
-  - /System/Library/PrivateFrameworks/MIME.framework/MIME
   - /System/Library/PrivateFrameworks/MailKit.framework/MailKit
   - /System/Library/PrivateFrameworks/MailSupport.framework/MailSupport
   - /System/Library/PrivateFrameworks/MailUI.framework/MailUI

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1767
-  Symbols:   3590
+  Functions: 1781
+  Symbols:   3615
   CStrings:  0
 
Symbols:
+ +[MFMessageDisplayMetrics displayMetricsWithTraitCollection:layoutMargins:safeAreaInsets:hostSystemMinimumLayoutMargins:interfaceOrientation:]
+ -[MFMessageContentView _committedDocumentMatchesContentURL:]
+ -[MFMessageContentView _discardFirstPaintGateState]
+ -[MFMessageContentView _footerHeight]
+ -[MFMessageContentView _handleNavigationFailure:]
+ -[MFMessageContentView _messageSurfaceBackgroundColor]
+ -[MFMessageContentView _readableLayoutMargins]
+ -[MFMessageContentView _setNeedsContentHeightNotification]
+ -[MFMessageContentView _updateFooterViewBackgroundColor]
+ -[MFMessageContentView configuredForSingleMessageDisplay]
+ -[MFMessageContentView setConfiguredForSingleMessageDisplay:]
+ -[MFMessageContentView webView:didFailProvisionalNavigation:withError:]
+ -[MFMessageDisplayMetrics hostSystemMinimumLayoutMargins]
+ -[MFMessageDisplayMetrics setHostSystemMinimumLayoutMargins:]
+ -[MFMessageHeaderView _applyBlockBackgroundColorToBlock:]
+ -[MFMessageHeaderView blockBackgroundColor]
+ -[MFMessageHeaderView setBlockBackgroundColor:]
+ -[MFMessageHeaderViewBlock prefersOwnBackgroundColor]
+ -[MFMessageHeaderViewBlock setPrefersOwnBackgroundColor:]
+ -[MFWebViewLoadingController cancelPendingContent]
+ GCC_except_table100
+ GCC_except_table101
+ GCC_except_table107
+ GCC_except_table121
+ GCC_except_table127
+ GCC_except_table134
+ GCC_except_table135
+ GCC_except_table136
+ GCC_except_table142
+ GCC_except_table145
+ GCC_except_table148
+ GCC_except_table158
+ GCC_except_table164
+ GCC_except_table165
+ GCC_except_table167
+ GCC_except_table178
+ GCC_except_table188
+ GCC_except_table192
+ GCC_except_table201
+ GCC_except_table204
+ GCC_except_table205
+ GCC_except_table208
+ GCC_except_table214
+ GCC_except_table216
+ GCC_except_table218
+ GCC_except_table222
+ GCC_except_table226
+ GCC_except_table230
+ GCC_except_table231
+ GCC_except_table235
+ GCC_except_table236
+ GCC_except_table243
+ GCC_except_table253
+ GCC_except_table255
+ GCC_except_table257
+ GCC_except_table259
+ GCC_except_table269
+ GCC_except_table274
+ GCC_except_table278
+ GCC_except_table281
+ GCC_except_table283
+ GCC_except_table286
+ GCC_except_table287
+ GCC_except_table288
+ GCC_except_table290
+ GCC_except_table291
+ GCC_except_table293
+ GCC_except_table295
+ GCC_except_table369
+ GCC_except_table376
+ GCC_except_table377
+ GCC_except_table378
+ GCC_except_table379
+ GCC_except_table380
+ GCC_except_table382
+ GCC_except_table48
+ GCC_except_table52
+ GCC_except_table61
+ GCC_except_table67
+ GCC_except_table80
+ GCC_except_table87
+ GCC_except_table89
+ GCC_except_table90
+ GCC_except_table92
+ GCC_except_table95
+ _NSURLErrorDomain
+ _OBJC_IVAR_$_MFMessageContentView._committedDocumentURL
+ _OBJC_IVAR_$_MFMessageContentView._configuredForSingleMessageDisplay
+ _OBJC_IVAR_$_MFMessageContentView._contentHeightNotificationNeeded
+ _OBJC_IVAR_$_MFMessageDisplayMetrics._hostSystemMinimumLayoutMargins
+ _OBJC_IVAR_$_MFMessageHeaderView._blockBackgroundColor
+ _OBJC_IVAR_$_MFMessageHeaderViewBlock._prefersOwnBackgroundColor
+ _WKErrorDomain
+ ___58-[MFMessageContentView _setNeedsContentHeightNotification]_block_invoke
- +[MFMessageDisplayMetrics displayMetricsWithTraitCollection:layoutMargins:safeAreaInsets:interfaceOrientation:]
- -[MFWebViewLoadingController clearContent]
- -[NSError(MessageContentView) mf_markupString]
- -[VIPManager allVIPEmailAddressesCriterion]
- -[VIPManager criterionForEmailAddresses:]
- GCC_except_table104
- GCC_except_table109
- GCC_except_table111
- GCC_except_table125
- GCC_except_table131
- GCC_except_table138
- GCC_except_table139
- GCC_except_table140
- GCC_except_table149
- GCC_except_table150
- GCC_except_table155
- GCC_except_table156
- GCC_except_table166
- GCC_except_table168
- GCC_except_table172
- GCC_except_table173
- GCC_except_table175
- GCC_except_table186
- GCC_except_table196
- GCC_except_table200
- GCC_except_table209
- GCC_except_table213
- GCC_except_table221
- GCC_except_table223
- GCC_except_table225
- GCC_except_table228
- GCC_except_table233
- GCC_except_table237
- GCC_except_table240
- GCC_except_table241
- GCC_except_table242
- GCC_except_table246
- GCC_except_table247
- GCC_except_table249
- GCC_except_table254
- GCC_except_table264
- GCC_except_table270
- GCC_except_table277
- GCC_except_table279
- GCC_except_table280
- GCC_except_table356
- GCC_except_table357
- GCC_except_table364
- GCC_except_table365
- GCC_except_table366
- GCC_except_table367
- GCC_except_table370
- GCC_except_table51
- GCC_except_table58
- GCC_except_table64
- GCC_except_table70
- GCC_except_table75
- GCC_except_table76
- GCC_except_table88
- GCC_except_table91
- GCC_except_table93
- GCC_except_table94
- GCC_except_table96
- GCC_except_table99
- _MFMIMEErrorDomain
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSError_$_MessageContentView
- __OBJC_$_CATEGORY_NSError_$_MessageContentView
- __OBJC_$_PROP_LIST_NSError_$_MessageContentView
- _messageForFragment
```
