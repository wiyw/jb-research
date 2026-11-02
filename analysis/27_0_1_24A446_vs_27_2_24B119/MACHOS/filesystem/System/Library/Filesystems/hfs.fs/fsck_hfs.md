## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-751.0.0.0.0
-  __TEXT.__text: 0x34bbc
+753.42.1.0.0
+  __TEXT.__text: 0x34ddc
   __TEXT.__auth_stubs: 0x7b0
   __TEXT.__const: 0x10b4
-  __TEXT.__cstring: 0x6e74
+  __TEXT.__cstring: 0x6f24
   __TEXT.__unwind_info: 0x540
   __DATA_CONST.__const: 0x370
   __DATA_CONST.__cfstring: 0x40
```
