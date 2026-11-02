## lifs

> `/System/Library/Extensions/lifs.kext/lifs`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`

```diff

-974.0.13.0.2
-  __TEXT.__os_log: 0x1f5d
-  __TEXT.__cstring: 0x29fa
-  __TEXT.__const: 0x338
-  __TEXT_EXEC.__text: 0x2099c
+974.40.12.0.0
+  __TEXT.__os_log: 0x1ffc
+  __TEXT.__cstring: 0x2a13
+  __TEXT.__const: 0x348
+  __TEXT_EXEC.__text: 0x20e08
   __TEXT_EXEC.__auth_stubs: 0xfb0
   __DATA.__data: 0x578
   __DATA.__common: 0x138

   __DATA_CONST.__kalloc_type: 0xe40
   __DATA_CONST.__kalloc_var: 0xf0
   __DATA_CONST.__auth_got: 0x7d8
-  __DATA_CONST.__got: 0x80
+  __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 460
-  Symbols:   1244
+  Functions: 463
+  Symbols:   1249
   CStrings:  0
 
Symbols:
+ _lifs_abandon_sync_req
+ _lifs_io_lock_override_owned
+ _lifs_update_attrs_if_needed
+ lifs_abandon_sync_req._os_log_fmt
+ lifs_create_endio_context.kalloc_type_view_1061
+ lifs_destroy_endio_context.kalloc_type_view_1080
+ lifs_fsync_internal.kalloc_type_view_4068
+ lifs_koio_done.kalloc_type_view_2157
+ lifs_mount.kalloc_type_view_669
+ lifs_mount.kalloc_type_view_695
+ lifs_mount.kalloc_type_view_873
+ lifs_mount.kalloc_type_view_923
+ lifs_mount.kalloc_type_view_927
+ lifs_mount.kalloc_type_view_931
+ lifs_reclaim_done.kalloc_type_view_5071
+ lifs_setfsattr_done.kalloc_type_view_3995
+ lifs_submit_io.kalloc_type_view_2139
+ lifs_submit_koio.kalloc_type_view_2179
+ lifs_unmount.kalloc_type_view_1082
+ lifs_unmount_dangling_all.kalloc_type_view_1578
+ lifs_unmount_dangling_all.kalloc_type_view_1599
+ lifs_unmount_dangling_thread.kalloc_type_view_1551
+ lifs_update_attrs_if_needed._os_log_fmt
+ lifs_vnop_readdir.kalloc_type_view_3102
+ lifs_vnop_readdir.kalloc_type_view_3104
+ lifs_vnop_readdir.kalloc_type_view_3199
+ lifs_vnop_readdir.kalloc_type_view_3201
+ lifs_vnop_reclaim.kalloc_type_view_5115
+ lifs_vnop_reclaim.kalloc_type_view_5169
+ lifs_vnop_strategy.kalloc_type_view_2273
+ lifs_vnop_strategy_done.kalloc_type_view_1867
- lifs_create_endio_context.kalloc_type_view_991
- lifs_destroy_endio_context.kalloc_type_view_1010
- lifs_fsync_internal.kalloc_type_view_3952
- lifs_koio_done.kalloc_type_view_2087
- lifs_mount.kalloc_type_view_670
- lifs_mount.kalloc_type_view_697
- lifs_mount.kalloc_type_view_876
- lifs_mount.kalloc_type_view_926
- lifs_mount.kalloc_type_view_930
- lifs_mount.kalloc_type_view_934
- lifs_reclaim_done.kalloc_type_view_4955
- lifs_setfsattr_done.kalloc_type_view_3879
- lifs_submit_io.kalloc_type_view_2069
- lifs_submit_koio.kalloc_type_view_2109
- lifs_unmount.kalloc_type_view_1085
- lifs_unmount_dangling_all.kalloc_type_view_1581
- lifs_unmount_dangling_all.kalloc_type_view_1602
- lifs_unmount_dangling_thread.kalloc_type_view_1554
- lifs_vnop_readdir.kalloc_type_view_3013
- lifs_vnop_readdir.kalloc_type_view_3015
- lifs_vnop_readdir.kalloc_type_view_3110
- lifs_vnop_readdir.kalloc_type_view_3112
- lifs_vnop_reclaim.kalloc_type_view_4999
- lifs_vnop_reclaim.kalloc_type_view_5053
- lifs_vnop_strategy.kalloc_type_view_2203
- lifs_vnop_strategy_done.kalloc_type_view_1797
```
