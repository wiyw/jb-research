## UIKit

> `/System/Library/AccessibilityBundles/UIKit.axbundle/UIKit`

```diff

-3048.0.0.0.0
-  __TEXT.__text: 0x15b3b8
-  __TEXT.__objc_methlist: 0xfc24
+3050.3.8.0.0
+  __TEXT.__text: 0x160034
+  __TEXT.__objc_methlist: 0xfde4
   __TEXT.__dlopen_cstrs: 0xb8
-  __TEXT.__const: 0x1c0
-  __TEXT.__gcc_except_tab: 0x35c8
-  __TEXT.__cstring: 0x19451
-  __TEXT.__oslogstring: 0x2712
+  __TEXT.__const: 0x1c8
+  __TEXT.__gcc_except_tab: 0x3608
+  __TEXT.__cstring: 0x19574
+  __TEXT.__oslogstring: 0x2869
   __TEXT.__ustring: 0x78
-  __TEXT.__unwind_info: 0x4308
+  __TEXT.__unwind_info: 0x43a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ee8
-  __DATA_CONST.__objc_classlist: 0x1b70
+  __DATA_CONST.__const: 0x1f58
+  __DATA_CONST.__objc_classlist: 0x1b90
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5d88
+  __DATA_CONST.__objc_selrefs: 0x5e58
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0xa90
+  __DATA_CONST.__objc_superrefs: 0xab0
   __DATA_CONST.__objc_arraydata: 0x160
-  __DATA_CONST.__got: 0xfd8
-  __AUTH_CONST.__const: 0x17c0
-  __AUTH_CONST.__cfstring: 0x1e0e0
-  __AUTH_CONST.__objc_const: 0x20980
+  __DATA_CONST.__got: 0xfe0
+  __AUTH_CONST.__const: 0x17e0
+  __AUTH_CONST.__cfstring: 0x1e1c0
+  __AUTH_CONST.__objc_const: 0x20bc0
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_arrayobj: 0x18

   __AUTH.__objc_data: 0xc80
   __DATA.__objc_ivar: 0x130
   __DATA.__data: 0x6a0
-  __DATA.__bss: 0x408
-  __DATA_DIRTY.__objc_data: 0x105e0
+  __DATA.__bss: 0x400
+  __DATA_DIRTY.__objc_data: 0x10720
   __DATA_DIRTY.__common: 0x8
-  __DATA_DIRTY.__bss: 0x1ea
+  __DATA_DIRTY.__bss: 0x1f2
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5998
-  Symbols:   11930
+  Functions: 6055
+  Symbols:   12012
   CStrings:  0
 
Symbols:
+ +[UIKeyboardModeSwitcherViewAccessibility _accessibilityPerformValidations:]
+ +[UIKeyboardModeSwitcherViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[UIKeyboardModeSwitcherViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[_UINavigationItemProxyAccessibility _accessibilityPerformValidations:]
+ +[_UINavigationItemProxyAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[_UINavigationItemProxyAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[UIAccessibilityElementMockView accessibilitySupportsTextSelection]
+ -[UIApplicationAccessibility _accessibilityElementsForStatusBar:sorted:]
+ -[UIApplicationAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]
+ -[UIApplicationAccessibility _axFirstVisibleAccessibleElementInContainer:]
+ -[UIApplicationAccessibility _axShouldDeferOffscreenFirstFocusForElement:]
+ -[UICollectionViewAccessibility _accessibilityViewChildrenWithOptions:]
+ -[UICollectionViewCellAccessibilityElement accessibilitySupportsTextSelection]
+ -[UIDropShadowViewAccessibility _axCoversWindow]
+ -[UIDropShadowViewAccessibility _axSheetDimmingViewIsModal]
+ -[UIDropShadowViewAccessibility accessibilityViewIsModal]
+ -[UIFocusRingManagerAccessibility _axCircularFocusRingClipForView:]
+ -[UIIndexBarAccessoryViewAccessibility _axLabelForEntry:lowercaseTitle:]
+ -[UIKeyboardModeSwitcherViewAccessibility accessibilityLabel]
+ -[UIKeyboardModeSwitcherViewAccessibility accessibilityTraits]
+ -[UIKeyboardModeSwitcherViewAccessibility isAccessibilityElement]
+ -[UIResponderAccessibility _axFKAArrowKeysAdjustingValue]
+ -[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]
+ -[UIScrollViewAccessibility accessibilityApplyScrollContentOverride:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]
+ -[UISegmentAccessibility accessibilityFrame]
+ -[UITableViewCellAccessibilityElement accessibilitySupportsTextSelection]
+ -[UITextViewAccessibility accessibilitySupportsTextSelection]
+ -[UITransitionViewAccessibility _accessibilityDimmingViewObscuresScreen]
+ -[_AXUITextViewParagraphElement accessibilitySupportsTextSelection]
+ -[_UIButtonBarButtonAccessibility _axHitTestReachesSelfAtPoint:]
+ -[_UIButtonBarButtonAccessibility accessibilityActivationPoint]
+ -[_UIButtonBarButtonAccessibility accessibilityCustomActions]
+ -[_UIContextMenuUIControllerAccessibility _axModalPresentedByMenuActionOwnsFocusForTriggerElement:]
+ -[_UIFloatingBarContainerViewAccessibility _accessibilityUsesDefaultHitTesting]
+ -[_UIInterfaceActionCustomViewRepresentationViewAccessibility accessibilityActivate]
+ -[_UIModernBarButtonAccessibility _accessibilityOwningButtonBarButton]
+ -[_UIModernBarButtonAccessibility accessibilityLabel]
+ -[_UINavigationItemProxyAccessibility initWithDestinationNavigationItem:sourceNavigationItem:]
+ -[_UINavigationItemProxyAccessibility navigationItemUpdatedTitleContent:animated:]
+ -[_UIScenePresentationViewAccessibility _accessibilityHitTest:withEvent:]
+ -[_UITabButtonAccessibility _accessibilityUpdatesOnActivationAfterDelay]
+ GCC_except_table1123
+ GCC_except_table1124
+ GCC_except_table1163
+ GCC_except_table1208
+ GCC_except_table1236
+ GCC_except_table1251
+ GCC_except_table1285
+ GCC_except_table1317
+ GCC_except_table1337
+ GCC_except_table1349
+ GCC_except_table136
+ GCC_except_table1365
+ GCC_except_table1367
+ GCC_except_table1378
+ GCC_except_table1515
+ GCC_except_table1535
+ GCC_except_table1537
+ GCC_except_table1551
+ GCC_except_table1579
+ GCC_except_table1582
+ GCC_except_table1585
+ GCC_except_table1606
+ GCC_except_table1655
+ GCC_except_table1684
+ GCC_except_table1685
+ GCC_except_table171
+ GCC_except_table1781
+ GCC_except_table1792
+ GCC_except_table1804
+ GCC_except_table1808
+ GCC_except_table1811
+ GCC_except_table1813
+ GCC_except_table1820
+ GCC_except_table1842
+ GCC_except_table1871
+ GCC_except_table1874
+ GCC_except_table1923
+ GCC_except_table1929
+ GCC_except_table1949
+ GCC_except_table1963
+ GCC_except_table1974
+ GCC_except_table2021
+ GCC_except_table206
+ GCC_except_table2115
+ GCC_except_table2118
+ GCC_except_table2167
+ GCC_except_table2189
+ GCC_except_table2273
+ GCC_except_table2303
+ GCC_except_table2308
+ GCC_except_table2316
+ GCC_except_table2335
+ GCC_except_table2352
+ GCC_except_table2408
+ GCC_except_table2436
+ GCC_except_table2446
+ GCC_except_table2454
+ GCC_except_table2470
+ GCC_except_table2489
+ GCC_except_table2585
+ GCC_except_table263
+ GCC_except_table2669
+ GCC_except_table2725
+ GCC_except_table2799
+ GCC_except_table2803
+ GCC_except_table2821
+ GCC_except_table2840
+ GCC_except_table2957
+ GCC_except_table2991
+ GCC_except_table3043
+ GCC_except_table3067
+ GCC_except_table3121
+ GCC_except_table3205
+ GCC_except_table3211
+ GCC_except_table3264
+ GCC_except_table3277
+ GCC_except_table3408
+ GCC_except_table3409
+ GCC_except_table3465
+ GCC_except_table3525
+ GCC_except_table3662
+ GCC_except_table3735
+ GCC_except_table3754
+ GCC_except_table3773
+ GCC_except_table3889
+ GCC_except_table3920
+ GCC_except_table3957
+ GCC_except_table3959
+ GCC_except_table3993
+ GCC_except_table3995
+ GCC_except_table4009
+ GCC_except_table4017
+ GCC_except_table403
+ GCC_except_table4031
+ GCC_except_table4032
+ GCC_except_table4058
+ GCC_except_table4063
+ GCC_except_table4093
+ GCC_except_table4113
+ GCC_except_table4118
+ GCC_except_table4126
+ GCC_except_table4128
+ GCC_except_table4144
+ GCC_except_table4158
+ GCC_except_table4197
+ GCC_except_table4215
+ GCC_except_table4221
+ GCC_except_table4233
+ GCC_except_table4255
+ GCC_except_table4262
+ GCC_except_table4401
+ GCC_except_table448
+ GCC_except_table4517
+ GCC_except_table460
+ GCC_except_table4706
+ GCC_except_table4709
+ GCC_except_table4710
+ GCC_except_table4732
+ GCC_except_table4766
+ GCC_except_table4771
+ GCC_except_table4773
+ GCC_except_table4782
+ GCC_except_table4786
+ GCC_except_table4787
+ GCC_except_table4788
+ GCC_except_table4794
+ GCC_except_table4795
+ GCC_except_table4798
+ GCC_except_table4804
+ GCC_except_table4820
+ GCC_except_table4836
+ GCC_except_table4853
+ GCC_except_table4923
+ GCC_except_table4982
+ GCC_except_table499
+ GCC_except_table509
+ GCC_except_table5095
+ GCC_except_table5122
+ GCC_except_table5147
+ GCC_except_table5149
+ GCC_except_table5154
+ GCC_except_table521
+ GCC_except_table5321
+ GCC_except_table5455
+ GCC_except_table5552
+ GCC_except_table558
+ GCC_except_table5648
+ GCC_except_table5676
+ GCC_except_table5721
+ GCC_except_table5741
+ GCC_except_table5847
+ GCC_except_table5853
+ GCC_except_table5868
+ GCC_except_table5884
+ GCC_except_table5905
+ GCC_except_table5917
+ GCC_except_table5934
+ GCC_except_table596
+ GCC_except_table608
+ GCC_except_table616
+ GCC_except_table626
+ GCC_except_table657
+ GCC_except_table664
+ GCC_except_table765
+ GCC_except_table767
+ GCC_except_table774
+ GCC_except_table776
+ GCC_except_table777
+ GCC_except_table779
+ GCC_except_table807
+ GCC_except_table821
+ GCC_except_table843
+ GCC_except_table916
+ _AXDeviceIsViridian
+ _AXIsHostedScene
+ _AXLocalizationForLocale
+ _AXScrollViewTotalPages
+ _OBJC_CLASS_$_UIKeyboardModeSwitcherViewAccessibility
+ _OBJC_CLASS_$__UINavigationItemProxyAccessibility
+ _OBJC_CLASS_$___UIKeyboardModeSwitcherViewAccessibility_super
+ _OBJC_CLASS_$____UINavigationItemProxyAccessibility_super
+ _OBJC_METACLASS_$_UIKeyboardModeSwitcherViewAccessibility
+ _OBJC_METACLASS_$__UINavigationItemProxyAccessibility
+ _OBJC_METACLASS_$___UIKeyboardModeSwitcherViewAccessibility_super
+ _OBJC_METACLASS_$____UINavigationItemProxyAccessibility_super
+ __AXSBrailleScreenInputEnabled
+ __AXTransferNavigationItemAccessibilityLabel
+ __OBJC_$_CLASS_METHODS_UIKeyboardModeSwitcherViewAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS__UINavigationItemProxyAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_$_INSTANCE_METHODS__UINavigationItemProxyAccessibility
+ __OBJC_CLASS_RO_$_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_CLASS_RO_$__UINavigationItemProxyAccessibility
+ __OBJC_CLASS_RO_$___UIKeyboardModeSwitcherViewAccessibility_super
+ __OBJC_CLASS_RO_$____UINavigationItemProxyAccessibility_super
+ __OBJC_METACLASS_RO_$_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_METACLASS_RO_$__UINavigationItemProxyAccessibility
+ __OBJC_METACLASS_RO_$___UIKeyboardModeSwitcherViewAccessibility_super
+ __OBJC_METACLASS_RO_$____UINavigationItemProxyAccessibility_super
+ ___102-[UITableViewAccessibility _accessibilitySortedElementsWithinPreservingFloatingHeader:sortedElements:]_block_invoke_2
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_2
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_3
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_4
+ ___152-[UIKeyboardLayoutStarAccessibility continueFromInternationalActionForTouchUp:withActions:timestamp:interval:didLongPress:prevActions:executionContext:]_block_invoke_2
+ ___71-[UIKeyboardLayoutStarAccessibility _accessibilityCreateElementForKey:]_block_invoke_2
+ ___74-[UIApplicationAccessibility _axFirstVisibleAccessibleElementInContainer:]_block_invoke
+ ___74-[UIApplicationAccessibility _axShouldDeferOffscreenFirstFocusForElement:]_block_invoke
+ ___84-[_UIInterfaceActionCustomViewRepresentationViewAccessibility accessibilityActivate]_block_invoke
+ ___87-[_UINavigationBarTitleControlAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___block_descriptor_40_e16_B16?0"UIView"8lu32l8
+ ___block_descriptor_40_e8_32r_e12_v24?08^B16lr32l8
+ ___block_descriptor_48_e8_32w40w_e15_"NSString"8?0lw32l8w40l8
+ ___os_log_helper_16_3_2_8_65_8_65
+ _accessibilityLocalizedStringForLanguage
+ _axLanguageOverridingAllContainedElements
+ _fmodf
- GCC_except_table1109
- GCC_except_table1117
- GCC_except_table1156
- GCC_except_table1201
- GCC_except_table1229
- GCC_except_table1244
- GCC_except_table1278
- GCC_except_table1308
- GCC_except_table1334
- GCC_except_table135
- GCC_except_table1350
- GCC_except_table1352
- GCC_except_table1363
- GCC_except_table1500
- GCC_except_table1520
- GCC_except_table1522
- GCC_except_table1536
- GCC_except_table1563
- GCC_except_table1566
- GCC_except_table1569
- GCC_except_table1590
- GCC_except_table1639
- GCC_except_table1668
- GCC_except_table1669
- GCC_except_table170
- GCC_except_table1764
- GCC_except_table1775
- GCC_except_table1786
- GCC_except_table1787
- GCC_except_table1791
- GCC_except_table1794
- GCC_except_table1796
- GCC_except_table1825
- GCC_except_table1854
- GCC_except_table1857
- GCC_except_table1906
- GCC_except_table1912
- GCC_except_table1932
- GCC_except_table1946
- GCC_except_table1956
- GCC_except_table2002
- GCC_except_table205
- GCC_except_table2096
- GCC_except_table2099
- GCC_except_table2147
- GCC_except_table2169
- GCC_except_table2253
- GCC_except_table2277
- GCC_except_table2282
- GCC_except_table2290
- GCC_except_table2309
- GCC_except_table2326
- GCC_except_table2382
- GCC_except_table2410
- GCC_except_table2420
- GCC_except_table2427
- GCC_except_table2443
- GCC_except_table2462
- GCC_except_table2555
- GCC_except_table261
- GCC_except_table2639
- GCC_except_table2695
- GCC_except_table2763
- GCC_except_table2767
- GCC_except_table2785
- GCC_except_table2804
- GCC_except_table2921
- GCC_except_table2954
- GCC_except_table3005
- GCC_except_table3028
- GCC_except_table3080
- GCC_except_table3164
- GCC_except_table3170
- GCC_except_table3223
- GCC_except_table3236
- GCC_except_table3365
- GCC_except_table3366
- GCC_except_table3422
- GCC_except_table3482
- GCC_except_table3619
- GCC_except_table3692
- GCC_except_table3711
- GCC_except_table3730
- GCC_except_table3846
- GCC_except_table3877
- GCC_except_table3914
- GCC_except_table3916
- GCC_except_table3949
- GCC_except_table3951
- GCC_except_table3965
- GCC_except_table3973
- GCC_except_table3987
- GCC_except_table3988
- GCC_except_table401
- GCC_except_table4014
- GCC_except_table4019
- GCC_except_table4040
- GCC_except_table4049
- GCC_except_table4069
- GCC_except_table4074
- GCC_except_table4082
- GCC_except_table4100
- GCC_except_table4114
- GCC_except_table4153
- GCC_except_table4171
- GCC_except_table4177
- GCC_except_table4189
- GCC_except_table4211
- GCC_except_table4218
- GCC_except_table4356
- GCC_except_table446
- GCC_except_table4472
- GCC_except_table458
- GCC_except_table4661
- GCC_except_table4664
- GCC_except_table4665
- GCC_except_table4687
- GCC_except_table4721
- GCC_except_table4726
- GCC_except_table4728
- GCC_except_table4737
- GCC_except_table4741
- GCC_except_table4742
- GCC_except_table4743
- GCC_except_table4749
- GCC_except_table4750
- GCC_except_table4753
- GCC_except_table4759
- GCC_except_table4775
- GCC_except_table4790
- GCC_except_table4807
- GCC_except_table4876
- GCC_except_table4934
- GCC_except_table494
- GCC_except_table504
- GCC_except_table5047
- GCC_except_table5058
- GCC_except_table5074
- GCC_except_table5099
- GCC_except_table5101
- GCC_except_table515
- GCC_except_table5273
- GCC_except_table5401
- GCC_except_table5496
- GCC_except_table552
- GCC_except_table5592
- GCC_except_table5620
- GCC_except_table5665
- GCC_except_table5684
- GCC_except_table5790
- GCC_except_table5796
- GCC_except_table5811
- GCC_except_table5827
- GCC_except_table5848
- GCC_except_table5860
- GCC_except_table5877
- GCC_except_table590
- GCC_except_table602
- GCC_except_table604
- GCC_except_table614
- GCC_except_table651
- GCC_except_table658
- GCC_except_table759
- GCC_except_table761
- GCC_except_table762
- GCC_except_table764
- GCC_except_table771
- GCC_except_table773
- GCC_except_table801
- GCC_except_table815
- GCC_except_table837
- GCC_except_table910
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_2
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_3
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_4
```
