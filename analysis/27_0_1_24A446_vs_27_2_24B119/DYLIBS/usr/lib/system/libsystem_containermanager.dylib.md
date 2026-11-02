## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

```diff

-833.0.8.0.1
-  __TEXT.__text: 0x300b8
+833.40.18.0.1
+  __TEXT.__text: 0x30d74
   __TEXT.__const: 0x434
-  __TEXT.__cstring: 0x3c49
-  __TEXT.__oslogstring: 0x59cf
-  __TEXT.__unwind_info: 0x708
+  __TEXT.__cstring: 0x3d9c
+  __TEXT.__oslogstring: 0x5ca9
+  __TEXT.__unwind_info: 0x718
   __TEXT.__auth_stubs: 0x0
-  __DATA_CONST.__const: 0x1d08
+  __DATA_CONST.__const: 0x1d50
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x220
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/system/libsystem_sandbox.dylib
   - /usr/lib/system/libsystem_trace.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 626
-  Symbols:   1009
+  Functions: 632
+  Symbols:   1017
   CStrings:  0
 
Symbols:
+ ___container_operation_copy_superseded_block_invoke
+ __container_serialize_copy_deserialized_reference
+ _container_frozenset_get_instance_uuid_of_container_at_index
+ _container_get_instance_uuid
+ _container_object_get_instance_uuid
+ _container_object_set_instance_uuid
+ _container_operation_copy_superseded
+ _container_query_set_instance_uuid
+ _mbr_uid_to_uuid
+ _uuid_clear
- __container_serialize_copy_deserialized_reference_v1
- __container_serialize_copy_deserialized_reference_v2
```
