## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

```diff

-792.102.0.0.0
-  __TEXT.__text: 0x66928
+793.1.10.0.0
+  __TEXT.__text: 0x67fec
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa4
-  __TEXT.__objc_methlist: 0x6934
-  __TEXT.__const: 0x8840
-  __TEXT.__cstring: 0x45e7
-  __TEXT.__oslogstring: 0x3d2c
+  __TEXT.__objc_methlist: 0x6a74
+  __TEXT.__cstring: 0x467e
+  __TEXT.__const: 0x8970
+  __TEXT.__oslogstring: 0x3f95
   __TEXT.__gcc_except_tab: 0x6b8
-  __TEXT.__unwind_info: 0x19e0
+  __TEXT.__unwind_info: 0x1a38
   __TEXT.__eh_frame: 0x88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa50
-  __DATA_CONST.__objc_classlist: 0x530
+  __DATA_CONST.__const: 0xa80
+  __DATA_CONST.__objc_classlist: 0x540
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3180
+  __DATA_CONST.__objc_selrefs: 0x3248
   __DATA_CONST.__objc_protorefs: 0x28
-  __DATA_CONST.__objc_superrefs: 0x408
-  __DATA_CONST.__objc_arraydata: 0xb0
-  __DATA_CONST.__got: 0x6b0
-  __AUTH_CONST.__const: 0x11a8
-  __AUTH_CONST.__cfstring: 0x4a00
-  __AUTH_CONST.__objc_const: 0x13f98
-  __AUTH_CONST.__objc_intobj: 0x540
-  __AUTH_CONST.__objc_arrayobj: 0x108
+  __DATA_CONST.__objc_superrefs: 0x410
+  __DATA_CONST.__objc_arraydata: 0xc8
+  __DATA_CONST.__got: 0x6b8
+  __AUTH_CONST.__const: 0x11c8
+  __AUTH_CONST.__cfstring: 0x4a80
+  __AUTH_CONST.__objc_const: 0x141b0
+  __AUTH_CONST.__objc_intobj: 0x588
+  __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0x7f0
+  __AUTH_CONST.__auth_got: 0x808
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0x870
-  __DATA.__objc_ivar: 0x6d0
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x6e0
   __DATA.__data: 0x1cf0
-  __DATA.__bss: 0x698
-  __DATA_DIRTY.__objc_data: 0x2b70
+  __DATA.__bss: 0x640
+  __DATA_DIRTY.__objc_data: 0x33e0
   __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x1c0
+  __DATA_DIRTY.__bss: 0x240
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2599
-  Symbols:   4962
+  Functions: 2640
+  Symbols:   5021
   CStrings:  0
 
Symbols:
+ +[ISSymbol _keyPiecesToVariantOptions]
+ +[ISSymbol _orderedVariantOptions]
+ +[ISSymbol _variantOptionsToKeyPieces]
+ +[ISSymbol variantOptionsForKey:]
+ +[OKLChColor cuspLightnessAtHue:]
+ +[OKLChColor maxChromaAtLightness:hue:]
+ -[ISDefaults isForceHomeAccessoryDeviceEnabled]
+ -[ISDefaults isInteriorDebugContentEnabled]
+ -[ISDeviceInfo isHomeAccessoryDevice]
+ -[ISGenericRecipe allowsDebugBackground]
+ -[ISGenericRecipe debugBackgroundEnabled]
+ -[ISGenericRecipe setAllowsDebugBackground:]
+ -[ISGenericRecipe setDebugBackgroundEnabled:]
+ -[ISHomeAccessoryAppRecipe iconSpecification]
+ -[ISIconConfigurationMarkupParser symbolVariant]
+ -[OKLChColor chroma]
+ -[OKLChColor convertToSRGBRed:green:blue:]
+ -[OKLChColor hue]
+ -[OKLChColor ifColor]
+ -[OKLChColor initFromIFColor:]
+ -[OKLChColor initWithLightness:chroma:hue:]
+ -[OKLChColor initWithSRGBRed:green:blue:]
+ -[OKLChColor lightness]
+ -[OKLChColor setChroma:]
+ -[OKLChColor setHue:]
+ -[OKLChColor setLightness:]
+ -[OKLChColor(FolderAdjustment) adjustForFolder]
+ _OBJC_CLASS_$_ISHomeAccessoryAppRecipe
+ _OBJC_CLASS_$_OKLChColor
+ _OBJC_IVAR_$_ISGenericRecipe._allowsDebugBackground
+ _OBJC_IVAR_$_ISGenericRecipe._debugBackgroundEnabled
+ _OBJC_IVAR_$_OKLChColor._chroma
+ _OBJC_IVAR_$_OKLChColor._hue
+ _OBJC_IVAR_$_OKLChColor._lightness
+ _OBJC_METACLASS_$_ISHomeAccessoryAppRecipe
+ _OBJC_METACLASS_$_OKLChColor
+ __ISSymbolLog
+ __ISSymbolLog.log
+ __ISSymbolLog.onceToken
+ __OBJC_$_CLASS_METHODS_OKLChColor
+ __OBJC_$_INSTANCE_METHODS_ISHomeAccessoryAppRecipe
+ __OBJC_$_INSTANCE_METHODS_OKLChColor(FolderAdjustment)
+ __OBJC_$_INSTANCE_VARIABLES_OKLChColor
+ __OBJC_$_PROP_LIST_OKLChColor
+ __OBJC_CLASS_RO_$_ISHomeAccessoryAppRecipe
+ __OBJC_CLASS_RO_$_OKLChColor
+ __OBJC_METACLASS_RO_$_ISHomeAccessoryAppRecipe
+ __OBJC_METACLASS_RO_$_OKLChColor
+ ___34+[ISSymbol _orderedVariantOptions]_block_invoke
+ ___38+[ISSymbol _keyPiecesToVariantOptions]_block_invoke
+ ___38+[ISSymbol _keyPiecesToVariantOptions]_block_invoke_2
+ ___38+[ISSymbol _variantOptionsToKeyPieces]_block_invoke
+ ____ISSymbolLog_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSNumber"8"NSString"16^B24ls32l8
+ __keyPiecesToVariantOptions.keyPiecesToOptions
+ __keyPiecesToVariantOptions.onceToken
+ __orderedVariantOptions.onceToken
+ __orderedVariantOptions.orderedOptions
+ __variantOptionsToKeyPieces.onceToken
+ __variantOptionsToKeyPieces.optionsToKeyPieces
+ _atan2
+ _cbrt
+ _hypot
+ _kISIconConfigurationKeySymbolVariant
+ _maxChroma
+ _okLabToLinearSRGB
- -[ISGenericRecipe isDebugModeEnabled]
- -[ISGenericRecipe setDebugModeEnabled:]
- _OBJC_IVAR_$_ISGenericRecipe._debugModeEnabled
- ___43+[ISSymbol _generateVariantKeyFromOptions:]_block_invoke
- __generateVariantKeyFromOptions:.onceToken
- __generateVariantKeyFromOptions:.optionsToKeyPieces
- __generateVariantKeyFromOptions:.orderedOptions
```
