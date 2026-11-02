## libquic.dylib

> `/usr/lib/libquic.dylib`

```diff

-6681.2.2.0.0
-  __TEXT.__text: 0xd0200
+6681.42.3.0.0
+  __TEXT.__text: 0xd116c
   __TEXT.__objc_methlist: 0x244
   __TEXT.__const: 0x3b5
-  __TEXT.__cstring: 0x8823
-  __TEXT.__oslogstring: 0x12459
-  __TEXT.__unwind_info: 0xd30
+  __TEXT.__cstring: 0x8907
+  __TEXT.__oslogstring: 0x12684
+  __TEXT.__unwind_info: 0xd18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x25b0
+  __DATA_CONST.__const: 0x25e0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x1e8

   __AUTH_CONST.__const: 0xcd0
   __AUTH_CONST.__cfstring: 0x1320
   __AUTH_CONST.__objc_const: 0xf8
-  __AUTH_CONST.__auth_got: 0xdd8
+  __AUTH_CONST.__auth_got: 0xdd0
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x50
+  __AUTH.__objc_data: 0x28
   __AUTH.__data: 0x118
   __DATA.__objc_ivar: 0xc
   __DATA.__data: 0x6c
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x520
-  __DATA_DIRTY.__data: 0x1c
-  __DATA_DIRTY.__bss: 0x660
+  __DATA_DIRTY.__objc_data: 0x28
+  __DATA_DIRTY.__data: 0x18
+  __DATA_DIRTY.__bss: 0x690
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/Network.framework/Network
   - /System/Library/Frameworks/Security.framework/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1156
-  Symbols:   1660
+  Functions: 1160
+  Symbols:   1663
   CStrings:  0
 
Symbols:
+ ___os_log_helper_1_2_16_8_34_4_0_8_34_4_0_4_0_4_0_4_0_4_0_8_34_8_34_4_0_4_0_4_0_4_0_4_0_4_0
+ __quic_timer_remove
+ _nw_quic_connection_get_path_recovery_timeout
+ _quic_migration_is_ignoring_events
+ _quic_migration_pulse_applies
+ _quic_migration_pulse_fire_now
+ _quic_migration_pulse_stop
+ _quic_migration_record_event
- ___os_log_helper_1_2_14_8_34_4_0_4_0_4_0_4_0_4_0_8_34_8_34_4_0_4_0_4_0_4_0_4_0_4_0
- _nw_protocol_establishment_report_set_quic_stateless_reset_during_path_probe
- _nw_protocol_establishment_report_set_quic_stateless_reset_received
- _quic_migration_report_event
- _quic_timer_remove
```
