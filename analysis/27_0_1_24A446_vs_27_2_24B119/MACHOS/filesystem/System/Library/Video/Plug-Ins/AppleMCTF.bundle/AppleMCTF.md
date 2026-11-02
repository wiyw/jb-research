## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-913.43.1.0.0
-  __TEXT.__text: 0x87c38
-  __TEXT.__auth_stubs: 0xd70
+913.64.1.0.0
+  __TEXT.__text: 0x89294
+  __TEXT.__auth_stubs: 0xdc0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x286c9
-  __TEXT.__const: 0x229e8
-  __TEXT.__gcc_except_tab: 0x628
+  __TEXT.__cstring: 0x28dcb
+  __TEXT.__const: 0x22a98
+  __TEXT.__gcc_except_tab: 0x62c
   __TEXT.__objc_methname: 0xb
-  __TEXT.__unwind_info: 0x670
+  __TEXT.__unwind_info: 0x688
   __DATA_CONST.__const: 0x5430
   __DATA_CONST.__cfstring: 0x980
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x6c8
+  __DATA_CONST.__auth_got: 0x6f0
   __DATA_CONST.__got: 0x3c0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA.__objc_selrefs: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 672
-  Symbols:   341
+  Functions: 678
+  Symbols:   346
   CStrings:  0
 
Symbols:
+ _CMBlockBufferAppendBufferReference
+ _CMBlockBufferCreateEmpty
+ _CMBlockBufferCreateWithBufferReference
+ _CMBlockBufferGetDataLength
+ _CMSampleBufferCreateCopyWithNewTiming
```
