## netstat

> `/usr/sbin/netstat`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-755.0.0.0.0
-  __TEXT.__text: 0x1b288
+757.0.0.0.0
+  __TEXT.__text: 0x1b7a8
   __TEXT.__auth_stubs: 0x4e0
-  __TEXT.__cstring: 0xf2c1
+  __TEXT.__cstring: 0xf9da
   __TEXT.__const: 0x3d8
   __TEXT.__unwind_info: 0x200
   __DATA_CONST.__const: 0x14b8

   __DATA_CONST.__got: 0x38
   __DATA_CONST.__auth_ptr: 0x10
   __DATA.__data: 0xa6c
-  __DATA.__bss: 0xabd8
+  __DATA.__bss: 0xac10
   __DATA.__common: 0x6b0
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 124
-  Symbols:   269
+  Functions: 125
+  Symbols:   272
   CStrings:  0
 
Symbols:
+ _print_ipsec_fastpath
+ ipsec_stats.pfastpath_in
+ ipsec_stats.pfastpath_out
```
