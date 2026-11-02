## NTKUltraBezel

> `/System/Library/PrivateFrameworks/NTKUltraBezel.framework/NTKUltraBezel`

```diff

-2483.523.0.4.0
-  __TEXT.__text: 0x120bc
-  __TEXT.__objc_methlist: 0xefc
-  __TEXT.__const: 0x552
-  __TEXT.__cstring: 0xab8
-  __TEXT.__oslogstring: 0x121
-  __TEXT.__gcc_except_tab: 0xac
+2483.560.1.0.0
+  __TEXT.__text: 0x1606c
+  __TEXT.__objc_methlist: 0x11a4
+  __TEXT.__const: 0x6a2
+  __TEXT.__cstring: 0xba8
+  __TEXT.__oslogstring: 0x248
+  __TEXT.__gcc_except_tab: 0x2c8
   __TEXT.__swift5_typeref: 0x8d
   __TEXT.__constg_swiftt: 0x44
   __TEXT.__swift5_reflstr: 0x58

   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x10
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x480
+  __TEXT.__unwind_info: 0x520
   __TEXT.__eh_frame: 0x128
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x258
+  __DATA_CONST.__const: 0x280
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc38
+  __DATA_CONST.__objc_selrefs: 0xe48
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_arraydata: 0x38
-  __DATA_CONST.__got: 0x208
+  __DATA_CONST.__got: 0x218
   __AUTH_CONST.__const: 0x2ad
-  __AUTH_CONST.__cfstring: 0x9e0
-  __AUTH_CONST.__objc_const: 0x1a10
+  __AUTH_CONST.__cfstring: 0xb40
+  __AUTH_CONST.__objc_const: 0x1e10
   __AUTH_CONST.__objc_floatobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__objc_intobj: 0x48
+  __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x660
+  __AUTH_CONST.__auth_got: 0x680
   __AUTH_CONST.__auth_ptr: 0x90
   __AUTH.__objc_data: 0x3f0
   __AUTH.__data: 0xa0
-  __DATA.__objc_ivar: 0x178
+  __DATA.__objc_ivar: 0x1cc
   __DATA.__data: 0x450
-  __DATA.__bss: 0x3f0
+  __DATA.__bss: 0x460
   - /System/Library/Frameworks/ClockKit.framework/ClockKit
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 423
-  Symbols:   838
+  Functions: 490
+  Symbols:   945
   CStrings:  0
 
Symbols:
+ +[CLKFont(NTKFoghornFaceAdditions) _foghornCaseSensitiveFontDescriptor]
+ +[CLKFont(NTKFoghornFaceAdditions) foghornReadinessBezelLabelFontOfSize:]
+ +[NTKFoghornPreferences readinessDemoModeScore]
+ +[NTKFoghornPreferences readinessDemoMode]
+ -[NTKFoghornFaceBezelView _drawReadinessBezelInContext:tritiumProgress:alpha:]
+ -[NTKFoghornFaceBezelView _readinessBaseLabelAllocatedWidth]
+ -[NTKFoghornFaceBezelView _readinessDeemphasizedBaseColor]
+ -[NTKFoghornFaceBezelView _readinessLabelColor]
+ -[NTKFoghornFaceBezelView _updateBaseLabelAllocatedWidthForStyle:]
+ -[NTKFoghornFaceBezelView _updateBaseLabelForReadinessBezel]
+ -[NTKFoghornFaceBezelView readinessDataState]
+ -[NTKFoghornFaceBezelView readinessEmphasizedTickColor]
+ -[NTKFoghornFaceBezelView readinessGoForItColor]
+ -[NTKFoghornFaceBezelView readinessGoForItDotColor]
+ -[NTKFoghornFaceBezelView readinessGoForItInactiveColor]
+ -[NTKFoghornFaceBezelView readinessLevel]
+ -[NTKFoghornFaceBezelView readinessLocalizedSummary]
+ -[NTKFoghornFaceBezelView readinessMonochrome]
+ -[NTKFoghornFaceBezelView readinessNegativeColor]
+ -[NTKFoghornFaceBezelView readinessPaceColor]
+ -[NTKFoghornFaceBezelView readinessPaceDotColor]
+ -[NTKFoghornFaceBezelView readinessPaceInactiveColor]
+ -[NTKFoghornFaceBezelView readinessPositiveColor]
+ -[NTKFoghornFaceBezelView readinessReadyColor]
+ -[NTKFoghornFaceBezelView readinessReadyDotColor]
+ -[NTKFoghornFaceBezelView readinessReadyInactiveColor]
+ -[NTKFoghornFaceBezelView readinessRecoverColor]
+ -[NTKFoghornFaceBezelView readinessRecoverDotColor]
+ -[NTKFoghornFaceBezelView readinessRecoverInactiveColor]
+ -[NTKFoghornFaceBezelView readinessScoreIsAvailable]
+ -[NTKFoghornFaceBezelView setReadinessDataState:]
+ -[NTKFoghornFaceBezelView setReadinessEmphasizedTickColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessLevel:]
+ -[NTKFoghornFaceBezelView setReadinessLocalizedSummary:]
+ -[NTKFoghornFaceBezelView setReadinessMonochrome:]
+ -[NTKFoghornFaceBezelView setReadinessNegativeColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessPositiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessScoreIsAvailable:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:forBezelStyle:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:forPrimaryColor:strictlyMonochrome:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:fromPalette:toPalette:fraction:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:useMulticolor:bezelStyle:primaryColor:strictlyMonochrome:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsWithPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMulticolorsInPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) _setReadinessMulticolorsInPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) setColorsFromUseMulticolor:fromBezelStyle:fromPrimaryColor:fromStrictlyMonochrome:toUseMulticolor:toBezelStyle:toPrimaryColor:toStrictlyMonochrome:fraction:]
+ -[NTKFoghornFaceBezelView(UIColor) setColorsUseMulticolor:bezelStyle:primaryColor:strictlyMonochrome:]
+ GCC_except_table10
+ GCC_except_table14
+ GCC_except_table15
+ GCC_except_table26
+ _CGContextSetLineJoin
+ _CGRectGetMinX
+ _CGRectGetWidth
+ _NTKFoghornReadinessLocalizedString
+ _NTKFoghornReadinessLocalizedStringForState
+ _NTKFoghornReadinessSnapshotLevel
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._baseLabelMaxWidthConstraint
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessDataState
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessEmphasizedTickColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessLevel
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessLocalizedSummary
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessMonochrome
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessNegativeColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPositiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessScoreIsAvailable
+ _UIFontFeatureSelectorIdentifierKey
+ _UIFontFeatureTypeIdentifierKey
+ ___71+[CLKFont(NTKFoghornFaceAdditions) _foghornCaseSensitiveFontDescriptor]_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___copy_constructor_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208_s216_s224_s232_s248_s256_s264_s272_s280_s288_s296_s304_s312_s320_s328_s336_s344_s352_s360
+ ___move_assignment_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ __foghornCaseSensitiveFontDescriptor.fontDescriptor
+ __foghornCaseSensitiveFontDescriptor.onceToken
+ __foghornPreferences.__readinessDemoMode
+ __foghornPreferences.__readinessDemoModeScore
+ __readinessBandEndFraction
+ __readinessBandMaxLevel
+ __readinessBandMinLevel
+ __readinessBandStartFraction
+ __readinessColorByScalingAlpha
+ __readinessDeemphasizedColors
+ _objc_release_x1
- -[NTKFoghornFaceBezelView(UIColor) _setColorsFromPrimaryColor:strictlyMonochrome:]
- -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMultiColors]
```
