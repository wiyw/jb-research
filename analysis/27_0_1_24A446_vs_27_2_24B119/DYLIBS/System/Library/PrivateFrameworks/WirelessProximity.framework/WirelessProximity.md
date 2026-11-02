## WirelessProximity

> `/System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity`

```diff

-2700.51.1.3.0
-  __TEXT.__text: 0x32e2c
-  __TEXT.__objc_methlist: 0x2c0c
+2701.7.1.0.0
+  __TEXT.__text: 0x34400
+  __TEXT.__objc_methlist: 0x2ca4
   __TEXT.__const: 0x380
-  __TEXT.__cstring: 0x3bcb
-  __TEXT.__oslogstring: 0x478f
-  __TEXT.__gcc_except_tab: 0x698
-  __TEXT.__unwind_info: 0x15c8
+  __TEXT.__cstring: 0x3cc9
+  __TEXT.__oslogstring: 0x47db
+  __TEXT.__gcc_except_tab: 0x6d0
+  __TEXT.__unwind_info: 0x1630
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7a8
+  __DATA_CONST.__const: 0x7d0
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1720
+  __DATA_CONST.__objc_selrefs: 0x1790
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xc8
-  __DATA_CONST.__got: 0x1b0
-  __AUTH_CONST.__const: 0x3728
-  __AUTH_CONST.__cfstring: 0x2f80
-  __AUTH_CONST.__objc_const: 0x3198
+  __DATA_CONST.__got: 0x1b8
+  __AUTH_CONST.__const: 0x3828
+  __AUTH_CONST.__cfstring: 0x3120
+  __AUTH_CONST.__objc_const: 0x3288
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x1e0
-  __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x220
+  __AUTH_CONST.__objc_intobj: 0x1f8
+  __AUTH_CONST.__auth_got: 0x3d8
+  __AUTH_CONST.__auth_ptr: 0x0
+  __DATA.__objc_ivar: 0x23c
   __DATA.__data: 0x2a8
-  __DATA.__bss: 0x10
   __DATA_DIRTY.__objc_data: 0x7d0
-  __DATA_DIRTY.__bss: 0x20
+  __DATA_DIRTY.__bss: 0x38
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1969
-  Symbols:   1870
+  Functions: 2006
+  Symbols:   1903
   CStrings:  0
 
Symbols:
+ +[LeAdvertisingMetric getAdvReportDictFromXPC:]
+ +[WPClient isHomeAccessory]
+ -[LeAdvertisingMetric getAdvReportMetricCBv1]
+ -[LeAdvertisingMetric getAdvReportTimestamps]
+ -[LeAdvertisingMetric getAdvReportXPCRepresentation]
+ -[LeAdvertisingMetric setAdvReportTimestamps:]
+ -[LeAdvertisingMetric setDaemonXPCSendAt]
+ -[LeAdvertisingMetric setGapRxAt:]
+ -[LeAdvertisingMetric setHciRxAt:]
+ -[LeAdvertisingMetric setObserverRxAt]
+ -[LeAdvertisingMetric setPreNotifyAt]
+ -[LeAdvertisingMetric setScanMgrRxAt]
+ -[LeAdvertisingMetric setWPDClientAt]
+ GCC_except_table107
+ GCC_except_table114
+ GCC_except_table118
+ GCC_except_table122
+ GCC_except_table126
+ GCC_except_table131
+ GCC_except_table136
+ GCC_except_table141
+ GCC_except_table146
+ GCC_except_table151
+ GCC_except_table155
+ GCC_except_table159
+ GCC_except_table172
+ GCC_except_table178
+ GCC_except_table183
+ GCC_except_table188
+ GCC_except_table193
+ GCC_except_table198
+ GCC_except_table204
+ GCC_except_table209
+ GCC_except_table214
+ GCC_except_table24
+ GCC_except_table47
+ GCC_except_table66
+ GCC_except_table72
+ GCC_except_table78
+ GCC_except_table82
+ GCC_except_table90
+ GCC_except_table94
+ GCC_except_table98
+ _OBJC_IVAR_$_LeAdvertisingMetric.daemonXPCSendAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.gapRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.hciRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.observerRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.preNotifyAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.scanMgrRxAt
+ _OBJC_IVAR_$_LeAdvertisingMetric.wpdClientAt
+ ___45-[LeAdvertisingMetric getAdvReportMetricCBv1]_block_invoke
+ ___47+[LeAdvertisingMetric getAdvReportDictFromXPC:]_block_invoke
+ ___block_descriptor_56_e8_32r_e37_B24?0r*8"NSObject<OS_xpc_object>"16lr32l8
+ ___chkstk_darwin
+ __isHomeAccessory
+ __xpc_type_dictionary
+ _bzero
+ _objc_release_x10
+ _xpc_dictionary_apply
+ _xpc_dictionary_create
+ _xpc_dictionary_get_count
+ _xpc_dictionary_set_uint64
+ _xpc_get_type
+ _xpc_uint64_get_value
- GCC_except_table106
- GCC_except_table113
- GCC_except_table117
- GCC_except_table121
- GCC_except_table125
- GCC_except_table130
- GCC_except_table135
- GCC_except_table140
- GCC_except_table145
- GCC_except_table150
- GCC_except_table154
- GCC_except_table158
- GCC_except_table171
- GCC_except_table177
- GCC_except_table182
- GCC_except_table187
- GCC_except_table192
- GCC_except_table197
- GCC_except_table203
- GCC_except_table208
- GCC_except_table213
- GCC_except_table23
- GCC_except_table41
- GCC_except_table46
- GCC_except_table65
- GCC_except_table71
- GCC_except_table77
- GCC_except_table81
- GCC_except_table89
- GCC_except_table93
- GCC_except_table97
```
