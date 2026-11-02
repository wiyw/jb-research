## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Categories`

```diff

-58.0.1.0.0
-  __TEXT.__text: 0xb798
-  __TEXT.__objc_methlist: 0x82c
-  __TEXT.__const: 0xb0
-  __TEXT.__gcc_except_tab: 0x41c
-  __TEXT.__cstring: 0x2e04
-  __TEXT.__oslogstring: 0x676
-  __TEXT.__unwind_info: 0x3b0
+58.1.7.1.0
+  __TEXT.__text: 0xb7bc
+  __TEXT.__objc_methlist: 0x89c
+  __TEXT.__const: 0xb8
+  __TEXT.__gcc_except_tab: 0x3e4
+  __TEXT.__cstring: 0x32d8
+  __TEXT.__oslogstring: 0x6e7
+  __TEXT.__unwind_info: 0x3c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6e8
+  __DATA_CONST.__const: 0x6c0
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x720
+  __DATA_CONST.__objc_selrefs: 0x770
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x28
-  __DATA_CONST.__objc_arraydata: 0xab8
+  __DATA_CONST.__objc_arraydata: 0xc18
   __DATA_CONST.__got: 0x100
-  __AUTH_CONST.__const: 0x140
-  __AUTH_CONST.__cfstring: 0x3780
-  __AUTH_CONST.__objc_const: 0xca0
-  __AUTH_CONST.__objc_arrayobj: 0x990
+  __AUTH_CONST.__const: 0x160
+  __AUTH_CONST.__cfstring: 0x3bc0
+  __AUTH_CONST.__objc_const: 0xcc8
+  __AUTH_CONST.__objc_intobj: 0xc0
+  __AUTH_CONST.__objc_arrayobj: 0x9f0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x50
   __DATA.__objc_ivar: 0x50
   __DATA.__data: 0x1e8
-  __DATA.__bss: 0x60
-  __DATA_DIRTY.__objc_data: 0x230
+  __DATA.__bss: 0x70
+  __DATA_DIRTY.__objc_data: 0x280
   __DATA_DIRTY.__bss: 0x98
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 221
-  Symbols:   526
+  Functions: 228
+  Symbols:   532
   CStrings:  0
 
Symbols:
+ +[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]
+ +[CTCategory _equivalentBundleIDForDestinationScheme:fromBundleID:sourceScheme:]
+ +[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]
+ +[CTCategory _shouldExcludeBundleIdentifierFromCategoryLookup:]
+ +[CTCategory bundleIDForDeviceFamily:fromBundleID:fromDeviceFamily:]
+ +[CTCategory categoryForBundleIdentifiers:platform:targetUserIsU13:origin:withCompletionHandler:]
+ +[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]
+ +[CTCategory currentDeviceFamily]
+ +[CTCategory deviceFamilyForPlatform:]
+ +[CTCategory schemeStringForDeviceFamily:]
+ -[CTCategories bundleIDForDeviceFamily:fromBundleID:fromDeviceFamily:]
+ GCC_except_table100
+ GCC_except_table22
+ GCC_except_table26
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table44
+ GCC_except_table58
+ GCC_except_table59
+ GCC_except_table74
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ ___103+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_2
+ ___105+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:origin:withCompletionHandler:]_block_invoke_3
+ ___33+[CTCategory currentDeviceFamily]_block_invoke
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke
+ ___73+[CTCategory _lookupAppStoreUsing:platform:origin:withCompletionHandler:]_block_invoke_2
+ ___80+[CTCategory _equivalentBundleIDForDestinationScheme:fromBundleID:sourceScheme:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_96_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r56l8r64l8r72l8s40l8s48l8
+ _currentDeviceFamily.deviceFamily
+ _currentDeviceFamily.onceToken
+ _objc_retain_x4
- +[CTCategories currentIOSDevice]
- +[CTCategory itemWith:platform:array:]
- +[CTCategory schemeStringForPlatform:]
- GCC_except_table21
- GCC_except_table24
- GCC_except_table32
- GCC_except_table36
- GCC_except_table40
- GCC_except_table42
- GCC_except_table48
- GCC_except_table54
- GCC_except_table66
- GCC_except_table78
- GCC_except_table95
- ___38+[CTCategory itemWith:platform:array:]_block_invoke
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_2
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_3
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_4
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_5
- ___56+[CTCategory bundleIDForPlatform:fromBundleID:platform:]_block_invoke
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke
- ___66+[CTCategory _lookupAppStoreUsing:platform:withCompletionHandler:]_block_invoke_2
- ___96+[CTCategory _bundleCategoriesLookupResultsForBundleIdentifiers:platform:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_2
- ___98+[CTCategory categoryForBundleIdentifiers:platform:version:targetUserIsU13:withCompletionHandler:]_block_invoke_3
- ___block_descriptor_40_e8_32r_e25_v32?0"NSString"8Q16^B24lr32l8
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
- ___block_descriptor_88_e8_32s40s48bs56r64r72r_e34_v24?0"NSDictionary"8"NSError"16ls32l8r56l8r64l8r72l8s40l8s48l8
```
