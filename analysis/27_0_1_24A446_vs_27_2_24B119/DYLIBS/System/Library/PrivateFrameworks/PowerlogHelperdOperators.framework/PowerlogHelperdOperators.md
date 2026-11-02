## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

```diff

-3486.2.4.0.0
-  __TEXT.__text: 0x1e6bb8
-  __TEXT.__objc_methlist: 0x111c8
+3486.42.1.0.0
+  __TEXT.__text: 0x1e9064
+  __TEXT.__objc_methlist: 0x11300
   __TEXT.__const: 0x700
-  __TEXT.__cstring: 0x2694b
-  __TEXT.__oslogstring: 0x15b6e
-  __TEXT.__gcc_except_tab: 0x2598
+  __TEXT.__cstring: 0x26c67
+  __TEXT.__oslogstring: 0x15fdd
+  __TEXT.__gcc_except_tab: 0x25a4
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x3c58
+  __TEXT.__unwind_info: 0x3c80
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4580
-  __DATA_CONST.__objc_classlist: 0x3a0
+  __DATA_CONST.__const: 0x45b8
+  __DATA_CONST.__objc_classlist: 0x3a8
   __DATA_CONST.__objc_nlclslist: 0x108
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb208
+  __DATA_CONST.__objc_selrefs: 0xb2d8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x2d8
-  __DATA_CONST.__objc_arraydata: 0x163c8
-  __DATA_CONST.__got: 0xf80
-  __AUTH_CONST.__const: 0x1a40
-  __AUTH_CONST.__cfstring: 0x33f80
-  __AUTH_CONST.__objc_const: 0x168c0
+  __DATA_CONST.__objc_superrefs: 0x2e0
+  __DATA_CONST.__objc_arraydata: 0x16478
+  __DATA_CONST.__got: 0xf88
+  __AUTH_CONST.__const: 0x1a80
+  __AUTH_CONST.__cfstring: 0x34380
+  __AUTH_CONST.__objc_const: 0x16b00
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_intobj: 0x28c8
-  __AUTH_CONST.__objc_dictobj: 0x3ac0
-  __AUTH_CONST.__objc_doubleobj: 0xb90
-  __AUTH_CONST.__objc_arrayobj: 0x2fa0
-  __AUTH_CONST.__auth_got: 0xe00
+  __AUTH_CONST.__objc_intobj: 0x28e0
+  __AUTH_CONST.__objc_dictobj: 0x3b38
+  __AUTH_CONST.__objc_doubleobj: 0xba0
+  __AUTH_CONST.__objc_arrayobj: 0x3060
+  __AUTH_CONST.__auth_got: 0xe08
   __AUTH_CONST.__auth_ptr: 0x0
-  __AUTH.__objc_data: 0xbe0
-  __DATA.__objc_ivar: 0x16c8
+  __AUTH.__objc_data: 0xc08
+  __DATA.__objc_ivar: 0x16ec
   __DATA.__data: 0x580
-  __DATA.__bss: 0x20b8
+  __DATA.__bss: 0x20d8
   __DATA.__common: 0x74
-  __DATA_DIRTY.__objc_data: 0x1860
+  __DATA_DIRTY.__objc_data: 0x1888
   __DATA_DIRTY.__data: 0x10
-  __DATA_DIRTY.__bss: 0x3b8
+  __DATA_DIRTY.__bss: 0x3c0
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8831
-  Symbols:   11942
+  Functions: 8864
+  Symbols:   11993
   CStrings:  0
 
Symbols:
+ +[PLAppTimeService entryAggregateDefinitionDisplayUsage]
+ +[PLUrsaUtilities diagnosticExtensionIDsForProcess:]
+ +[PLUrsaUtilities generateTTRURLWithRadarParams:context:metadataPath:]
+ +[PLUrsaUtilities remoteDiagnosticParamsForProcess:]
+ +[PLUrsaUtilities writeMetadata:toDirectory:]
+ -[PLAggregateSummarizationService getQueryForDisplayAPL:]
+ -[PLAppTimeService aggregateEntryKeyForDisplayUsage]
+ -[PLAppTimeService setAggregateEntryKeyForDisplayUsage:]
+ -[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]
+ -[PLBatteryAgent batteryPackCount]
+ -[PLBatteryAgent setBatteryPackCount:]
+ -[PLCoalitionAgent buildPLEntryDiffForObject:withNewUsage:hasPrevSample:withStartDate:withEndDate:]
+ -[PLCoalitionAgent logOSMetrics:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldLogCoalitionObject:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldProcessCoalitionID:seenCoalitionIDs:]
+ -[PLMetricsFormatterJSON addDisplayAPL:userData:forIndex:]
+ -[PLSleepWakeAgent kaIDMax]
+ -[PLSleepWakeAgent kaIDMin]
+ -[PLSleepWakeAgent setKaIDMax:]
+ -[PLSleepWakeAgent setKaIDMin:]
+ -[PLUrsaViolationContext .cxx_destruct]
+ -[PLUrsaViolationContext init]
+ -[PLUrsaViolationContext internalOnlyRule]
+ -[PLUrsaViolationContext issueType]
+ -[PLUrsaViolationContext mitigationsEnabled]
+ -[PLUrsaViolationContext procName]
+ -[PLUrsaViolationContext ruleID]
+ -[PLUrsaViolationContext setInternalOnlyRule:]
+ -[PLUrsaViolationContext setIssueType:]
+ -[PLUrsaViolationContext setMitigationsEnabled:]
+ -[PLUrsaViolationContext setProcName:]
+ -[PLUrsaViolationContext setRuleID:]
+ -[PLUrsaViolationContext setViolationTime:]
+ -[PLUrsaViolationContext violationTime]
+ GCC_except_table216
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_PLUrsaViolationContext
+ _OBJC_IVAR_$_PLAppTimeService._aggregateEntryKeyForDisplayUsage
+ _OBJC_IVAR_$_PLBatteryAgent._batteryPackCount
+ _OBJC_IVAR_$_PLMetricsFormatterJSON.appDisplayXAPLMapping
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ _OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ _OBJC_IVAR_$_PLUrsaViolationContext._internalOnlyRule
+ _OBJC_IVAR_$_PLUrsaViolationContext._issueType
+ _OBJC_IVAR_$_PLUrsaViolationContext._mitigationsEnabled
+ _OBJC_IVAR_$_PLUrsaViolationContext._procName
+ _OBJC_IVAR_$_PLUrsaViolationContext._ruleID
+ _OBJC_IVAR_$_PLUrsaViolationContext._violationTime
+ _OBJC_METACLASS_$_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_METHODS_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_VARIABLES_PLUrsaViolationContext
+ __OBJC_$_PROP_LIST_PLUrsaViolationContext
+ __OBJC_CLASS_RO_$_PLUrsaViolationContext
+ __OBJC_METACLASS_RO_$_PLUrsaViolationContext
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ ___52+[PLUrsaUtilities remoteDiagnosticParamsForProcess:]_block_invoke
+ ___57-[PLAggregateSummarizationService getQueryForDisplayAPL:]_block_invoke
+ ___83-[PLAppTimeService updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:]_block_invoke
+ ___block_descriptor_41_e8_32s_e17_"NSArray"16?0d8ls32l8
+ _diagnosticExtensionIDsForProcess:.mapping
+ _diagnosticExtensionIDsForProcess:.onceToken
+ _kPLAppTimeServiceAggregateNameDisplayID
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke.classDebugEnabled
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke.defaultOnce
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke_2.classDebugEnabled
+ _kPLAppTimeServiceAggregateNameDisplayID_block_invoke_2.defaultOnce
+ _kPLAppTimeServiceAggregateNameDisplayUsage
+ _normalizedProcessName
+ _remoteDiagnosticParamsForProcess:.mapping
+ _remoteDiagnosticParamsForProcess:.onceToken
+ _updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:.classDebugEnabled
+ _updateScreenOnTimeInDBForBundleId:withTime:withDate:forContext:.defaultOnce
- +[PLUrsaUtilities generateTTRURLWithRadarParams:procName:mitigationsEnabled:violationTime:metadataPath:issueType:]
- -[PLAggregateSummarizationService getQueryForDisplayAPL]
- -[PLCoalitionAgent buildPLEntryDiffForObject:withStartDate:withEndDate:]
- -[PLCoalitionAgent logCoalitionObjectDifference]
- -[PLCoalitionAgent logOSMetrics:]
- -[PLCoalitionAgent shouldLogCoalitionObject:]
- -[PLCoalitionDataObject hasPrevSample]
- -[PLCoalitionDataObject prevCoalResourceUsage]
- -[PLMetricsFormatterJSON addDisplayAPL:userData:]
- GCC_except_table173
- GCC_except_table219
- _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
- _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
- ___48-[PLCoalitionAgent logCoalitionObjectDifference]_block_invoke
- ___56-[PLAggregateSummarizationService getQueryForDisplayAPL]_block_invoke
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke.classDebugEnabled
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke.defaultOnce
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke_2.classDebugEnabled
- _kPLAppTimeServiceAggregateNameHasAudioUsage_block_invoke_2.defaultOnce
- _logCoalitionObjectDifference.classDebugEnabled
- _logCoalitionObjectDifference.defaultOnce
```
