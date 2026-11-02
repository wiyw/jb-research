## libsystem_malloc_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_malloc_debug.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__dof_magmalloc`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH.__data`
- `__AUTH.__v_zone`

```diff

-886.0.8.0.0
-  __TEXT.__text: 0xf0ed4
+886.40.15.0.0
+  __TEXT.__text: 0xf1514
   __TEXT.__const: 0x69f
-  __TEXT.__cstring: 0x30b45
+  __TEXT.__cstring: 0x30e90
   __TEXT.__dof_magmalloc: 0x8c7
-  __TEXT.__unwind_info: 0x8e8
+  __TEXT.__unwind_info: 0x8f0
   __TEXT.__eh_frame: 0x48
   __TEXT.__auth_stubs: 0x790
   __DATA_CONST.__const: 0x908

   - /System/DriverKit/usr/lib/system/libsystem_kernel.dylib
   - /System/DriverKit/usr/lib/system/libsystem_platform.dylib
   - /System/DriverKit/usr/lib/system/libsystem_pthread.dylib
-  Functions: 1215
-  Symbols:   1472
+  Functions: 1216
+  Symbols:   1473
   CStrings:  0
 
Symbols:
+ ___mfm_blocks_hwm
```
