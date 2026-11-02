## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__info_plist`
- `__AUTH_CONST.__auth_ptr`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

-27062.0.0.0.0
-  __TEXT.__text: 0x9eda4
-  __TEXT.__const: 0x1978
-  __TEXT.__cstring: 0x12573
+27104.0.0.0.0
+  __TEXT.__text: 0x9ee60
+  __TEXT.__const: 0x1998
+  __TEXT.__cstring: 0x1263d
   __TEXT.__info_plist: 0x4eb
-  __TEXT.__unwind_info: 0x35b0
-  __DATA_CONST.__const: 0x55f0
-  __AUTH_CONST.__const: 0x2758
+  __TEXT.__unwind_info: 0x35b8
+  __DATA_CONST.__const: 0x5618
+  __AUTH_CONST.__const: 0x2760
   __AUTH_CONST.__auth_ptr: 0x98
   __DATA.__data: 0x1c0
   __DATA.__crash_info: 0x148
   __DATA.__common: 0x8f0
   __DATA.__bss: 0x508
-  __DATA_DIRTY.__data: 0x6c
   __DATA_DIRTY.__all_image_info: 0x170
+  __DATA_DIRTY.__data: 0x64
   __DATA_DIRTY.__common: 0x1160
   __DATA_DIRTY.__bss: 0x1bc0
   __TPRO_CONST.__data: 0xe1
   __TPRO_CONST.__allocator: 0x20000
-  Functions: 3422
-  Symbols:   3669
+  Functions: 3423
+  Symbols:   3667
   CStrings:  0
 
Symbols:
+ __ZN5dyld44APIs28_dyld_with_active_atlas_PRIVEPvPFvS1_PKvmE
+ __ZNK6mach_o5Image19maxAuthRebaseOffsetEv
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
+ __ZNK6mach_o6Policy34enforceAuthRebasesPointWithinImageEv
+ ____ZNK6mach_o5Image19maxAuthRebaseOffsetEv_block_invoke
- _OUTLINED_FUNCTION_38
- _OUTLINED_FUNCTION_41
- _OUTLINED_FUNCTION_42
- _OUTLINED_FUNCTION_44
- _OUTLINED_FUNCTION_45
- _ZNK6mach_o6Header29stringFromOffsetInLoadCommandERKNS0_15LoadCommandInfoEjPNS_5ErrorE
- __ZZ16get_xprr_versionvE19cached_xprr_version
```
