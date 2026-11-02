## libsystem_eligibility.dylib

> `/usr/lib/system/libsystem_eligibility.dylib`

```diff

-446.2.4.0.0
-  __TEXT.__text: 0x4178
+446.42.1.0.0
+  __TEXT.__text: 0x42b8
   __TEXT.__const: 0x760
-  __TEXT.__cstring: 0x57e1
+  __TEXT.__cstring: 0x5821
   __TEXT.__oslogstring: 0x39b
   __TEXT.__unwind_info: 0xc8
   __TEXT.__auth_stubs: 0x0
-  __DATA_CONST.__const: 0xf08
+  __DATA_CONST.__const: 0xf18
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x40
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/system/libsystem_malloc.dylib
   - /usr/lib/system/libsystem_trace.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 28
-  Symbols:   78
+  Functions: 33
+  Symbols:   83
   CStrings:  0
 
Symbols:
+ _eligibility_xpc_create_set_input_message
+ _os_eligibility_bring_up_daemon_4_network_prompt
+ _os_eligibility_reset_all_inputs
+ _os_eligibility_reset_input
+ _os_eligibility_set_input_forced
```
