## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__dof_VirtualAu`
- `__TEXT.__dof_Aggregate`
- `__TEXT.__dof_VirtualA0`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-1451.115.30.0.0
-  __TEXT.__text: 0x5477f4
-  __TEXT.__realtime: 0x14ab0
-  __TEXT.__auth_stubs: 0x29b0
-  __TEXT.__objc_stubs: 0x12a0
-  __TEXT.__init_offsets: 0x1048
+1451.212.0.0.0
+  __TEXT.__text: 0x55dec4
+  __TEXT.__realtime: 0x14c88
+  __TEXT.__auth_stubs: 0x2a40
+  __TEXT.__objc_stubs: 0x1280
+  __TEXT.__init_offsets: 0x104c
   __TEXT.__objc_methlist: 0x2c0
-  __TEXT.__const: 0xb4918
-  __TEXT.__cstring: 0x375c2
-  __TEXT.__gcc_except_tab: 0x611d0
+  __TEXT.__const: 0xb4930
+  __TEXT.__cstring: 0x37a3a
+  __TEXT.__gcc_except_tab: 0x661cc
   __TEXT.__swift5_typeref: 0x12b
   __TEXT.__swift5_capture: 0x168
-  __TEXT.__oslogstring: 0x58164
-  __TEXT.__objc_methname: 0xf99
+  __TEXT.__oslogstring: 0x58fb2
+  __TEXT.__objc_methname: 0xf89
   __TEXT.__objc_classname: 0x9d
   __TEXT.__objc_methtype: 0x422
   __TEXT.__constg_swiftt: 0xf8

   __TEXT.__dof_VirtualAu: 0x340
   __TEXT.__dof_Aggregate: 0x5ec
   __TEXT.__dof_VirtualA0: 0x2aa
-  __TEXT.__unwind_info: 0x14a20
+  __TEXT.__unwind_info: 0x15030
   __TEXT.__eh_frame: 0x730
-  __DATA_CONST.__const: 0x294d8
-  __DATA_CONST.__cfstring: 0x2fa0
+  __DATA_CONST.__const: 0x29738
+  __DATA_CONST.__cfstring: 0x2ec0
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
-  __DATA_CONST.__objc_intobj: 0x30
-  __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x14f0
-  __DATA_CONST.__got: 0x530
+  __DATA_CONST.__auth_got: 0x1538
+  __DATA_CONST.__got: 0x540
   __DATA_CONST.__auth_ptr: 0x70
   __DATA.__objc_const: 0x630
-  __DATA.__objc_selrefs: 0x580
+  __DATA.__objc_selrefs: 0x578
   __DATA.__objc_ivar: 0x28
   __DATA.__objc_data: 0x2b8
-  __DATA.__data: 0x5b0
-  __DATA.__bss: 0x25ed0
+  __DATA.__data: 0x5b8
+  __DATA.__bss: 0x269b0
   __DATA.__common: 0x18
   - /AppleInternal/Library/Frameworks/AudioCapture.framework/AudioCapture
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
   - /System/Library/PrivateFrameworks/AudioDSPGraph.framework/AudioDSPGraph
   - /System/Library/PrivateFrameworks/AudioDataAnalysis.framework/AudioDataAnalysis
   - /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12452
-  Symbols:   827
+  Functions: 12546
+  Symbols:   834
   CStrings:  0
 
Symbols:
+ _SCDynamicStoreCopyComputerName
+ _SCPreferencesCreate
+ _SCPreferencesSetCallback
+ _SCPreferencesSetDispatchQueue
+ __ZN5caulk10concurrent7details23lf_read_sync_write_impl10end_mutateEj
+ __ZN5caulk10concurrent7details23lf_read_sync_write_impl12begin_mutateEv
+ __ZN5caulk10concurrent7details23lf_read_sync_write_implC1Ev
+ __ZN5caulk14cf_preferences19interpret_log_levelEPKv
+ __ZN5caulk14cf_preferences7monitor12_add_handlerEPK10__CFStringS4_ONSt3__18functionIFbPKvEEE
+ __ZN5caulk14cf_preferences7monitor8instanceEv
+ __ZN5caulk14cf_preferences8get_boolEPK10__CFStringS3_
+ __ZN5caulk14cf_preferences9get_int64EPK10__CFStringS3_
+ __ZN5caulk7product11_aid_prefixEv
+ __ZNK5caulk10concurrent7details23lf_read_sync_write_impl10end_accessEv
+ __ZNK5caulk10concurrent7details23lf_read_sync_write_impl12begin_accessEv
+ __ZNSt13runtime_errorC2ERKS_
+ __ZNSt3__112system_errorC1EiRKNS_14error_categoryE
+ __ZNSt3__112system_errorD1Ev
+ __ZNSt3__115system_categoryEv
+ __ZTVNSt3__112system_errorE
+ __dispatch_main_q
- _CFPreferencesCopyAppValue
- _CFSetAddValue
- _CFSetApplyFunction
- _CFSetCreateMutable
- _MGCancelNotifications
- _MGGetStringAnswer
- _MGRegisterForUpdates
- _OBJC_CLASS_$_NSConstantArray
- _OBJC_CLASS_$_NSConstantIntegerNumber
- __ZTVN10__cxxabiv121__vmi_class_type_infoE
- ___atomic_load
- ___atomic_store
- __dispatch_source_type_signal
- _kCFTypeSetCallBacks
```
