## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication`

```diff

-2319.0.63.0.0
-  __TEXT.__text: 0x34318
-  __TEXT.__objc_methlist: 0x3710
+2319.42.1.0.0
+  __TEXT.__text: 0x3432c
+  __TEXT.__objc_methlist: 0x3728
   __TEXT.__const: 0x314
   __TEXT.__gcc_except_tab: 0xab8
   __TEXT.__cstring: 0x1960

   __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1c10
+  __DATA_CONST.__objc_selrefs: 0x1c20
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x1d8
   __DATA_CONST.__got: 0x600

   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__auth_got: 0x5d8
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x16a0
+  __AUTH.__objc_data: 0x570
   __AUTH.__data: 0x28
   __DATA.__objc_ivar: 0x294
   __DATA.__data: 0xc30
   __DATA.__bss: 0x3f0
-  __DATA_DIRTY.__objc_data: 0x370
-  __DATA_DIRTY.__bss: 0x58
+  __DATA_DIRTY.__objc_data: 0x14a0
+  __DATA_DIRTY.__bss: 0x50
   - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1501
-  Symbols:   2868
+  Functions: 1503
+  Symbols:   2870
   CStrings:  0
 
Symbols:
+ -[LAContext optionDisableAutomaticPasscodeFallback]
+ -[LAContext setOptionDisableAutomaticPasscodeFallback:]
```
