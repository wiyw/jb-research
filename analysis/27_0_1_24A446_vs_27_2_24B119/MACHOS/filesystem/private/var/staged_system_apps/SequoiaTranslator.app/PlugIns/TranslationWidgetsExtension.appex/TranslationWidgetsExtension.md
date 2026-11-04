## TranslationWidgetsExtension

> `/private/var/staged_system_apps/SequoiaTranslator.app/PlugIns/TranslationWidgetsExtension.appex/TranslationWidgetsExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-389.1.1.0.0
-  __TEXT.__text: 0xd818
+396.2.0.0.0
+  __TEXT.__text: 0xd848
   __TEXT.__auth_stubs: 0x1000
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__objc_methlist: 0x20

   __TEXT.__swift5_entry: 0x8
   __TEXT.__unwind_info: 0x4b8
   __TEXT.__eh_frame: 0x4f0
-  __DATA_CONST.__const: 0x7e0
+  __DATA_CONST.__const: 0x800
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x808
-  __DATA_CONST.__got: 0x198
+  __DATA_CONST.__got: 0x1a0
   __DATA_CONST.__auth_ptr: 0x6b8
   __DATA.__objc_const: 0x320
   __DATA.__objc_selrefs: 0x78
   __DATA.__objc_data: 0x128
-  __DATA.__data: 0x780
+  __DATA.__data: 0x788
   __DATA.__bss: 0x2310
   __DATA.__common: 0xb8
   - /System/Library/Frameworks/ActivityKit.framework/ActivityKit

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib

   - /usr/lib/swift/libswiftCoreMIDI.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIntents.dylib
+  - /usr/lib/swift/libswiftMLCompute.dylib
   - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib
   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 384
-  Symbols:   136
+  Symbols:   140
   CStrings:  0
 
Symbols:
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
```
