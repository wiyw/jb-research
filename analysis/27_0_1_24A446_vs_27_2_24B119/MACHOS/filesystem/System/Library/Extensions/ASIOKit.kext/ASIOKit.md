## ASIOKit

> `/System/Library/Extensions/ASIOKit.kext/ASIOKit`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__got`

```diff

-27.0.28.0.0
-  __TEXT.__cstring: 0x261
-  __TEXT.__const: 0x8580
-  __TEXT_EXEC.__text: 0x347e0
-  __TEXT_EXEC.__auth_stubs: 0x210
+27.2.9.0.0
+  __TEXT.__cstring: 0xd2
+  __TEXT.__const: 0x91d0
+  __TEXT_EXEC.__text: 0x50b48
+  __TEXT_EXEC.__auth_stubs: 0x1f0
   __DATA.__data: 0x158
   __DATA.__common: 0x60
   __DATA_CONST.__mod_init_func: 0x10
   __DATA_CONST.__mod_term_func: 0x10
-  __DATA_CONST.__const: 0x2bd8
+  __DATA_CONST.__const: 0x34c0
   __DATA_CONST.__kalloc_type: 0x80
-  __DATA_CONST.__auth_got: 0x108
+  __DATA_CONST.__auth_got: 0xf8
   __DATA_CONST.__got: 0x58
-  Functions: 98
-  Symbols:   352
+  Functions: 97
+  Symbols:   349
   CStrings:  0
 
Symbols:
+ __ZN7ASIOKit8teardownEv
- __ZN7ASIOKit16DqycVGt64ff4YTONEP11_baaOptions
- __ZN7ASIOKit16kKcutC1yTbOdNEHiEP11_baaOptions
- __ZN7OSArray12withCapacityEj
- __ZN8OSString11withCStringEPKc
```
