## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1216.2.2.0.0
-  __TEXT.__text: 0x39ae8
-  __TEXT.__auth_stubs: 0xe20
-  __TEXT.__objc_stubs: 0xe80
-  __TEXT.__objc_methlist: 0x66c
-  __TEXT.__const: 0x1e203
-  __TEXT.__cstring: 0x2050
+1219.42.3.0.0
+  __TEXT.__text: 0x3aaec
+  __TEXT.__auth_stubs: 0xe30
+  __TEXT.__objc_stubs: 0xf80
+  __TEXT.__objc_methlist: 0x704
+  __TEXT.__const: 0x1e223
+  __TEXT.__cstring: 0x20ff
+  __TEXT.__oslogstring: 0x6ae2
   __TEXT.__objc_classname: 0x9b
-  __TEXT.__objc_methname: 0x1783
+  __TEXT.__objc_methname: 0x1880
   __TEXT.__objc_methtype: 0x607
-  __TEXT.__oslogstring: 0x66e6
   __TEXT.__gcc_except_tab: 0x270
-  __TEXT.__unwind_info: 0x828
-  __DATA_CONST.__const: 0x6a58
-  __DATA_CONST.__cfstring: 0x1780
+  __TEXT.__unwind_info: 0x838
+  __DATA_CONST.__const: 0x6ab8
+  __DATA_CONST.__cfstring: 0x1860
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x720
-  __DATA_CONST.__got: 0x138
+  __DATA_CONST.__auth_got: 0x728
+  __DATA_CONST.__got: 0x140
   __DATA_CONST.__auth_ptr: 0x40
-  __DATA.__objc_const: 0xb10
-  __DATA.__objc_selrefs: 0x5d0
-  __DATA.__objc_ivar: 0x60
+  __DATA.__objc_const: 0xb68
+  __DATA.__objc_selrefs: 0x5f8
+  __DATA.__objc_ivar: 0x64
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x1b8
-  __DATA.__bss: 0x130
+  __DATA.__bss: 0x140
   __DATA.__common: 0x1c
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1225
-  Symbols:   2799
+  Functions: 1260
+  Symbols:   2838
   CStrings:  0
 
Symbols:
+ -[ACCHWComponentAuthService authenticateBatteryWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateLASWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:updateRegistry:updateUIProperty:logToAnalytics:]
+ -[ACCHWComponentAuthService signRCAMChallenge:completionHandler:]
+ -[ACCHWComponentAuthService signTouchControllerChallenge:completionHandler:componentIndex:]
+ -[ACCHWComponentAuthService signVeridianChallenge:completionHandler:]
+ -[ACCHWComponentAuthServiceParams setSigningHandler:]
+ -[ACCHWComponentAuthServiceParams signingHandler]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(AppleAnchors.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CMS.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CTCompress.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluate.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(CryptoUtils.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(DERUtils.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Certificate.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Chain.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Policy.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/lib/libCoreTrust.a(iCDPAnchors.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/TempContent/Objects/CoreAccessories.build/ACCHWComponentAuthService.build/Objects-normal/arm64e/acc_internal_settings.o
+ GCC_except_table79
+ OBJC_IVAR_$_ACCHWComponentAuthServiceParams._signingHandler
+ _CFDictionaryCreate
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ __createError
+ __oidAppleExtendedKeyUsageSWUpdateSigning
+ _acc_internalSettings_boolForKey
+ _acc_internalSettings_integerForKey
+ _acc_internalSettings_isInternalBuild
+ _kACCInfo_PPIDVersionUID
+ _kCFACCInfo_PPIDVersionUID
+ _kCFErrorUnderlyingErrorKey
+ _objc_msgSend$authenticateBatteryWithChallenge:completionHandler:componentIndex:
+ _objc_msgSend$authenticateLASWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateTouchControllerWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateVeridianWithChallenge:completionHandler:componentIndex:
+ _objc_msgSend$signRCAMChallenge:completionHandler:componentIndex:
+ _objc_msgSend$signVeridianChallenge:completionHandler:componentIndex:
+ _objc_msgSend$verifyModuleCertificate:forModule:forAuthFlags:forIndex:
+ _oidAppleExtendedKeyUsageSWUpdateSigning
+ acc_internalSettings_boolForKey
+ acc_internalSettings_integerForKey
+ acc_internalSettings_isInternalBuild
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(AppleAnchors.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CMS.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CTCompress.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CTEvaluate.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(CryptoUtils.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(DERUtils.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Certificate.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Chain.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(X509Policy.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/lib/libCoreTrust.a(iCDPAnchors.o)
- GCC_except_table70
```
