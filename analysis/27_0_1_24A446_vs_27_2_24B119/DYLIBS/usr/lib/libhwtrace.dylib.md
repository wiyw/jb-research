## libhwtrace.dylib

> `/usr/lib/libhwtrace.dylib`

```diff

-328.2.1.0.0
-  __TEXT.__text: 0x27f5f8
-  __TEXT.__const: 0x176f50
-  __TEXT.__cstring: 0x16f45
-  __TEXT.__oslogstring: 0xaa5
+328.40.36.0.0
+  __TEXT.__text: 0x283480
+  __TEXT.__const: 0x176f80
+  __TEXT.__cstring: 0x17215
+  __TEXT.__oslogstring: 0xac5
   __TEXT.__gcc_except_tab: 0x390
-  __TEXT.__unwind_info: 0x3200
+  __TEXT.__unwind_info: 0x3260
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH.__data: 0x18
   __DATA.__data: 0x70
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xac0
+  __DATA.__bss: 0xab8
   __DATA.__common: 0x178
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4867
-  Symbols:   597
+  Functions: 4924
+  Symbols:   648
   CStrings:  0
 
Symbols:
+ _hwtrace_cluster_options_create
+ _hwtrace_cluster_options_destroy
+ _hwtrace_cluster_options_set_trace_type
+ _hwtrace_cursor_create_from_async_task
+ _hwtrace_cursor_create_from_core
+ _hwtrace_cursor_create_from_thread
+ _hwtrace_cursor_destroy
+ _hwtrace_cursor_previous_pc
+ _hwtrace_cursor_previous_range
+ _hwtrace_cursor_section
+ _hwtrace_isa_create
+ _hwtrace_isa_destroy
+ _hwtrace_live_recording_create_from_session
+ _hwtrace_live_recording_create_with_options
+ _hwtrace_live_recording_destroy
+ _hwtrace_live_recording_options_create
+ _hwtrace_live_recording_options_destroy
+ _hwtrace_live_recording_postprocess_options_create
+ _hwtrace_live_recording_postprocess_options_destroy
+ _hwtrace_live_recording_session_create
+ _hwtrace_live_recording_session_destroy
+ _hwtrace_load_options_create
+ _hwtrace_load_options_destroy
+ _hwtrace_range_cycle_count
+ _hwtrace_range_instruction_count
+ _hwtrace_recording_create_empty
+ _hwtrace_recording_create_from_corefile
+ _hwtrace_recording_create_from_directory
+ _hwtrace_recording_create_from_ktrace
+ _hwtrace_recording_create_from_live_recording
+ _hwtrace_recording_destroy
+ _hwtrace_recording_save_options_add_system
+ _hwtrace_recording_save_options_create
+ _hwtrace_recording_save_options_destroy
+ _hwtrace_section_disasm
+ _hwtrace_section_disassemble
+ _hwtrace_section_load_address
+ _hwtrace_section_module_name
+ _hwtrace_section_name
+ _hwtrace_section_offset_4CoreSymbolication
+ _hwtrace_section_segment_file_address
+ _hwtrace_section_segment_load_address
+ _hwtrace_section_segment_name
+ _hwtrace_section_slide
+ _hwtrace_section_symbol
+ _hwtrace_section_used_iter
+ _hwtrace_section_uuid
+ _hwtrace_task_sections_iter
+ _hwtrace_trace_create_from_directory
+ _hwtrace_trace_create_from_recording
+ _hwtrace_trace_destroy
```
