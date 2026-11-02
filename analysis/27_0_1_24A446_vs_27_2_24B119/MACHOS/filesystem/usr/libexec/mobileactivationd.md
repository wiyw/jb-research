## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1145.0.1.0.1
-  __TEXT.__text: 0x34c2ac
-  __TEXT.__auth_stubs: 0x1240
-  __TEXT.__objc_stubs: 0x3240
-  __TEXT.__objc_methlist: 0x112c
+1145.40.5.0.4
+  __TEXT.__text: 0x34ca7c
+  __TEXT.__auth_stubs: 0x12f0
+  __TEXT.__objc_stubs: 0x3260
+  __TEXT.__objc_methlist: 0x113c
   __TEXT.__const: 0x60b63
-  __TEXT.__cstring: 0xeeb1
-  __TEXT.__objc_methname: 0x4044
+  __TEXT.__cstring: 0xf17e
+  __TEXT.__objc_methname: 0x4084
   __TEXT.__oslogstring: 0xf47
   __TEXT.__objc_classname: 0x1a4
   __TEXT.__objc_methtype: 0x1061
-  __TEXT.__gcc_except_tab: 0x1b88
+  __TEXT.__gcc_except_tab: 0x1bcc
   __TEXT.__dlopen_cstrs: 0x294
   __TEXT.__ustring: 0x4
   __TEXT.__info_plist: 0x109
-  __TEXT.__unwind_info: 0x1248
+  __TEXT.__unwind_info: 0x1250
   __TEXT.__eh_frame: 0xa0
-  __DATA_CONST.__const: 0x1c4f8
-  __DATA_CONST.__cfstring: 0xd4e0
+  __DATA_CONST.__const: 0x1c528
+  __DATA_CONST.__cfstring: 0xd6a0
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x48

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_intobj: 0x330
-  __DATA_CONST.__objc_arraydata: 0x600
+  __DATA_CONST.__objc_arraydata: 0x608
   __DATA_CONST.__objc_arrayobj: 0xa8
-  __DATA_CONST.__auth_got: 0x930
-  __DATA_CONST.__got: 0x4b0
+  __DATA_CONST.__auth_got: 0x988
+  __DATA_CONST.__got: 0x4b8
   __DATA_CONST.__auth_ptr: 0x80
-  __DATA.__objc_const: 0x1900
-  __DATA.__objc_selrefs: 0x10c0
-  __DATA.__objc_ivar: 0xfc
+  __DATA.__objc_const: 0x1930
+  __DATA.__objc_selrefs: 0x10c8
+  __DATA.__objc_ivar: 0x100
   __DATA.__objc_data: 0x320
   __DATA.__data: 0x1d58
   __DATA.__bss: 0x568

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/liblockdown.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1660
-  Symbols:   4048
+  Functions: 1666
+  Symbols:   4067
   CStrings:  0
 
Symbols:
+ -[DeviceType is_home_accessory]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/amd/libDER.a(DER_Decode.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(AppleAnchors.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CMS.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluate.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluateBAA.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CryptoUtils.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(DERUtils.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Certificate.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Chain.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Policy.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(iCDPAnchors.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(aks_pack.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(der_utils.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(firebloom_hacks.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(libaks_client.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(libaks_internal.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libaks.a(libaks_ref_key.o)
+ OBJC_IVAR_$_DeviceType._is_home_accessory
+ _DRE_SYSTEM_DATA_MOUNT_PATH
+ _IOPSSetBatteryDateOfFirstUseWithPackDetails
+ _NSPOSIXErrorDomain
+ _OUTLINED_FUNCTION_18
+ _OUTLINED_FUNCTION_21
+ _OUTLINED_FUNCTION_29
+ ___block_descriptor_48_e8_32r40r_e63_B24?0r^{container_object_s=}8r^{container_error_extended_s=}16l
+ ___copy_activation_records_directory_path_for_mount_path_block_invoke
+ _container_error_get_message
+ _container_error_get_path
+ _container_error_get_posix_errno
+ _container_get_identifier
+ _container_get_path
+ _container_paths_context_create
+ _container_paths_context_free
+ _container_paths_context_set_class
+ _container_paths_copy_container_root_path_for_context
+ _container_paths_enumerate_containers_at
+ _copy_activation_records_directory_path_for_mount_path
+ _is_home_accessory
+ _objc_msgSend$is_home_accessory
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/amd/libDER.a(DER_Decode.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(AppleAnchors.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CMS.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluate.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluateBAA.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CryptoUtils.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(DERUtils.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Certificate.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Chain.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Policy.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(iCDPAnchors.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(aks_pack.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(der_utils.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(firebloom_hacks.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(libaks_client.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(libaks_internal.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libaks.a(libaks_ref_key.o)
- _IOPSSetBatteryDateOfFirstUse
- _OUTLINED_FUNCTION_19
- _OUTLINED_FUNCTION_35
- _OUTLINED_FUNCTION_47
```
