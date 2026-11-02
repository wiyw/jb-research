## libdyld.dylib

> `/usr/lib/system/libdyld.dylib`

```diff

-27062.0.0.0.0
-  __TEXT.__text: 0x1ce24
+27104.0.0.0.0
+  __TEXT.__text: 0x1da98
   __TEXT.__const: 0x32c
-  __TEXT.__cstring: 0x4d20
+  __TEXT.__cstring: 0x4dd6
   __TEXT.__gcc_except_tab: 0x20
-  __TEXT.__unwind_info: 0xd98
+  __TEXT.__unwind_info: 0xda0
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x1990
   __DATA_CONST.__helper: 0x8

   __AUTH_CONST.__const: 0x17e8
   __AUTH_CONST.__auth_got: 0x1a0
   __AUTH_CONST.__auth_ptr: 0x0
-  __DATA.__data: 0x10
   __DATA.__crash_info: 0x148
+  __DATA.__data: 0x8
   __DATA.__common: 0x11
   __DATA.__bss: 0x18
   __DATA_DIRTY.__common: 0x28

   - /usr/lib/system/libsystem_pthread.dylib
   - /usr/lib/system/libunwind.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 852
-  Symbols:   1078
+  Functions: 854
+  Symbols:   1079
   CStrings:  0
 
Symbols:
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
+ __ZZZ19dyldFrameworkVtablevEUb_EN3$_08__invokeEPvPFvS0_PKvmE
- __ZZ16get_xprr_versionvE19cached_xprr_version
```
