## AppleThunderboltSAT

> `/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__got`

```diff

-113.0.0.0.0
-  __TEXT.__cstring: 0x10dcf
+122.0.0.0.1
+  __TEXT.__cstring: 0x10ee6
   __TEXT.__const: 0x50
-  __TEXT_EXEC.__text: 0x24530
-  __TEXT_EXEC.__auth_stubs: 0x570
+  __TEXT_EXEC.__text: 0x24828
+  __TEXT_EXEC.__auth_stubs: 0x590
   __DATA.__data: 0x7f0
-  __DATA.__common: 0x589
+  __DATA.__common: 0x581
   __DATA.__bss: 0x3c
   __DATA_CONST.__mod_init_func: 0x78
   __DATA_CONST.__mod_term_func: 0x78
-  __DATA_CONST.__const: 0x4c18
+  __DATA_CONST.__const: 0x4c30
   __DATA_CONST.__kalloc_type: 0x400
   __DATA_CONST.__kalloc_var: 0x2d0
-  __DATA_CONST.__auth_got: 0x2b8
+  __DATA_CONST.__auth_got: 0x2c8
   __DATA_CONST.__got: 0xe8
-  Functions: 557
-  Symbols:   1117
+  Functions: 559
+  Symbols:   1121
   CStrings:  0
 
Symbols:
+ _IOLockSleepDeadline
+ _IOLockWakeup
+ __Z45AppleThunderboltSATGlobalsEnsureTimeSyncStartv
+ __ZN23AppleThunderboltSATPort10incRxCountEv
+ __ZN34AppleThunderboltSATClientDataQueue21discardStaleAbortWaitEPKc
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_802
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_812
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_876
+ __ZZN29AppleThunderboltSATConnection17newControlCommandEvE21kalloc_type_view_1370
+ __ZZN29AppleThunderboltSATConnection22destroyControlCommandsEvE21kalloc_type_view_1342
- __ZL31getDefaultClientDataQueueLengthv
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_809
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_819
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_883
- __ZZN29AppleThunderboltSATConnection17newControlCommandEvE21kalloc_type_view_1366
- __ZZN29AppleThunderboltSATConnection22destroyControlCommandsEvE21kalloc_type_view_1338
```
