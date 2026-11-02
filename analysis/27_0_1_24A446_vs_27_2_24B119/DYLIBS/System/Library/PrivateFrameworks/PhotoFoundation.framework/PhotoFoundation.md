## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x23fec
-  __TEXT.__objc_methlist: 0xd04
-  __TEXT.__const: 0x22f8
+916.57.154.0.0
+  __TEXT.__text: 0x24adc
+  __TEXT.__lazy_helpers: 0x150
+  __TEXT.__objc_methlist: 0xea4
+  __TEXT.__const: 0x2300
   __TEXT.__swift5_typeref: 0x87a
   __TEXT.__constg_swiftt: 0x894
   __TEXT.__swift5_builtin: 0x8c
-  __TEXT.__swift5_reflstr: 0x9f9
-  __TEXT.__swift5_fieldmd: 0x854
+  __TEXT.__swift5_reflstr: 0x929
+  __TEXT.__swift5_fieldmd: 0x800
   __TEXT.__swift5_assocty: 0x120
   __TEXT.__swift5_proto: 0x13c
   __TEXT.__swift5_types: 0x90
-  __TEXT.__cstring: 0x125f
+  __TEXT.__cstring: 0x1360
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__oslogstring: 0x863
+  __TEXT.__oslogstring: 0x95f
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_capture: 0x198
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x8
-  __TEXT.__gcc_except_tab: 0xc8
-  __TEXT.__unwind_info: 0xdc0
+  __TEXT.__gcc_except_tab: 0xdc
+  __TEXT.__unwind_info: 0xdf0
   __TEXT.__eh_frame: 0xc48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2e0
-  __DATA_CONST.__objc_classlist: 0xf8
+  __DATA_CONST.__const: 0x310
+  __DATA_CONST.__objc_classlist: 0x108
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8c8
+  __DATA_CONST.__objc_selrefs: 0xa00
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x50
-  __DATA_CONST.__got: 0x418
+  __DATA_CONST.__objc_superrefs: 0x58
+  __DATA_CONST.__got: 0x428
   __AUTH_CONST.__const: 0x1700
-  __AUTH_CONST.__cfstring: 0xdc0
-  __AUTH_CONST.__objc_const: 0x2800
-  __AUTH_CONST.__auth_got: 0xe38
+  __AUTH_CONST.__cfstring: 0xec0
+  __AUTH_CONST.__objc_const: 0x2c38
+  __AUTH_CONST.__lazy_load_got: 0x18
+  __AUTH_CONST.__auth_got: 0xe50
   __AUTH_CONST.__auth_ptr: 0x808
-  __AUTH.__objc_data: 0xb8
-  __AUTH.__data: 0x420
-  __DATA.__objc_ivar: 0x118
-  __DATA.__data: 0xb68
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x154
+  __DATA.__data: 0x92c
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1fc0
+  __DATA.__bss: 0x1fd0
   __DATA.__common: 0x58
-  __DATA_DIRTY.__objc_data: 0x800
-  __DATA_DIRTY.__data: 0x1b0
+  __DATA_DIRTY.__objc_data: 0x8b8
+  __DATA_DIRTY.__data: 0x810
   __DATA_DIRTY.__bss: 0x188
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1494
-  Symbols:   1342
+  Functions: 1531
+  Symbols:   1431
   CStrings:  0
 
Symbols:
+ +[PFStateCaptureHandler stateCaptureDictionariesForAllHandlers]
+ -[PFRadarComponent .cxx_destruct]
+ -[PFRadarComponent description]
+ -[PFRadarComponent identifier]
+ -[PFRadarComponent initWithIdentifier:name:version:]
+ -[PFRadarComponent name]
+ -[PFRadarComponent version]
+ -[PFStateCaptureHandler name]
+ -[PFStateCaptureHandler stateCaptureDictionary]
+ -[PFTapToRadarDraft .cxx_destruct]
+ -[PFTapToRadarDraft attachments]
+ -[PFTapToRadarDraft capturesPerformanceTrace]
+ -[PFTapToRadarDraft classification]
+ -[PFTapToRadarDraft component]
+ -[PFTapToRadarDraft diagnosticExtensionIdentifiers]
+ -[PFTapToRadarDraft diagnosticExtensionParameters]
+ -[PFTapToRadarDraft displayReason]
+ -[PFTapToRadarDraft isUserInitiated]
+ -[PFTapToRadarDraft problemDescription]
+ -[PFTapToRadarDraft processName]
+ -[PFTapToRadarDraft remoteDeviceClasses]
+ -[PFTapToRadarDraft setAttachments:]
+ -[PFTapToRadarDraft setCapturesPerformanceTrace:]
+ -[PFTapToRadarDraft setClassification:]
+ -[PFTapToRadarDraft setComponent:]
+ -[PFTapToRadarDraft setDiagnosticExtensionIdentifiers:]
+ -[PFTapToRadarDraft setDiagnosticExtensionParameters:]
+ -[PFTapToRadarDraft setDisplayReason:]
+ -[PFTapToRadarDraft setProblemDescription:]
+ -[PFTapToRadarDraft setProcessName:]
+ -[PFTapToRadarDraft setRemoteDeviceClasses:]
+ -[PFTapToRadarDraft setTitle:]
+ -[PFTapToRadarDraft setUserInitiated:]
+ -[PFTapToRadarDraft title]
+ GCC_except_table134
+ GCC_except_table197
+ GCC_except_table343
+ GCC_except_table347
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_PFRadarComponent
+ _OBJC_CLASS_$_PFTapToRadarDraft
+ _OBJC_CLASS_$_RadarComponent
+ _OBJC_CLASS_$_RadarComponent$lazyGOT
+ _OBJC_CLASS_$_RadarComponent$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_RadarDraft
+ _OBJC_CLASS_$_RadarDraft$lazyGOT
+ _OBJC_CLASS_$_RadarDraft$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_TapToRadarService
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT$loadHelper_x20
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT$loadHelper_x26
+ _OBJC_IVAR_$_PFRadarComponent._identifier
+ _OBJC_IVAR_$_PFRadarComponent._name
+ _OBJC_IVAR_$_PFRadarComponent._version
+ _OBJC_IVAR_$_PFTapToRadarDraft._attachments
+ _OBJC_IVAR_$_PFTapToRadarDraft._capturesPerformanceTrace
+ _OBJC_IVAR_$_PFTapToRadarDraft._classification
+ _OBJC_IVAR_$_PFTapToRadarDraft._component
+ _OBJC_IVAR_$_PFTapToRadarDraft._diagnosticExtensionIdentifiers
+ _OBJC_IVAR_$_PFTapToRadarDraft._diagnosticExtensionParameters
+ _OBJC_IVAR_$_PFTapToRadarDraft._displayReason
+ _OBJC_IVAR_$_PFTapToRadarDraft._problemDescription
+ _OBJC_IVAR_$_PFTapToRadarDraft._processName
+ _OBJC_IVAR_$_PFTapToRadarDraft._remoteDeviceClasses
+ _OBJC_IVAR_$_PFTapToRadarDraft._title
+ _OBJC_IVAR_$_PFTapToRadarDraft._userInitiated
+ _OBJC_METACLASS_$_PFRadarComponent
+ _OBJC_METACLASS_$_PFTapToRadarDraft
+ _PFHeapBytesAllocated
+ _PFHeapBytesInUse
+ _PFHeapFragmentationRatio
+ _PFTapToRadarCreateDraft
+ _PFTapToRadarErrorDomain
+ _PFTapToRadarGetAuthorizationStatus
+ _PFTapToRadarReportUnavailable
+ __OBJC_$_INSTANCE_METHODS_PFRadarComponent
+ __OBJC_$_INSTANCE_METHODS_PFTapToRadarDraft
+ __OBJC_$_INSTANCE_VARIABLES_PFRadarComponent
+ __OBJC_$_INSTANCE_VARIABLES_PFTapToRadarDraft
+ __OBJC_$_PROP_LIST_PFRadarComponent
+ __OBJC_$_PROP_LIST_PFStateCaptureHandler
+ __OBJC_$_PROP_LIST_PFTapToRadarDraft
+ __OBJC_CLASS_RO_$_PFRadarComponent
+ __OBJC_CLASS_RO_$_PFTapToRadarDraft
+ __OBJC_METACLASS_RO_$_PFRadarComponent
+ __OBJC_METACLASS_RO_$_PFTapToRadarDraft
+ ___PFTapToRadarGetAuthorizationStatus_block_invoke
+ ___block_descriptor_40_e8_32bs_e35_v16?0"TapToRadarServiceSettings"8ls32l8
+ __dyld_lazy_load
+ _lazyLoadFlag$TapToRadarKit
+ _objc_opt_new
+ _objc_setProperty_nonatomic_copy
+ _sAllStateCaptureHandlers
+ _sAllStateCaptureHandlersLock
- +[PFCoalescer arrayCoalescerWithLabel:queue:action:]
- GCC_except_table135
- GCC_except_table196
- GCC_except_table306
- GCC_except_table310
- _PFReduceF
```
