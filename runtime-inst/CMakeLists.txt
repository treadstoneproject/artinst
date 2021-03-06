#libart_common_src_file
set(libart_source_file
	atomic.cc.arm \
  barrier.cc \
  base/allocator.cc \
  base/bit_vector.cc \
  base/hex_dump.cc \
  base/logging.cc \
  base/mutex.cc \
  base/scoped_flock.cc \
  base/stringpiece.cc \
  base/stringprintf.cc \
  base/timing_logger.cc \
  base/unix_file/fd_file.cc \
  base/unix_file/mapped_file.cc \
  base/unix_file/null_file.cc \
  base/unix_file/random_access_file_utils.cc \
  base/unix_file/string_file.cc \
  check_jni.cc \
  class_linker.cc \
  common_throws.cc \
  debugger.cc \
  dex_file.cc \
  dex_file_verifier.cc \
  dex_instruction.cc \
  elf_file.cc \
  field_helper.cc \
  gc/allocator/dlmalloc.cc \
  gc/allocator/rosalloc.cc \
  gc/accounting/card_table.cc \
  gc/accounting/heap_bitmap.cc \
  gc/accounting/mod_union_table.cc \
  gc/accounting/remembered_set.cc \
  gc/accounting/space_bitmap.cc \
  gc/collector/concurrent_copying.cc \
  gc/collector/garbage_collector.cc \
  gc/collector/immune_region.cc \
  gc/collector/mark_compact.cc \
  gc/collector/mark_sweep.cc \
  gc/collector/partial_mark_sweep.cc \
  gc/collector/semi_space.cc \
  gc/collector/sticky_mark_sweep.cc \
  gc/gc_cause.cc \
  gc/heap.cc \
  gc/reference_processor.cc \
  gc/reference_queue.cc \
  gc/space/bump_pointer_space.cc \
  gc/space/dlmalloc_space.cc \
  gc/space/image_space.cc \
  gc/space/large_object_space.cc \
  gc/space/malloc_space.cc \
  gc/space/rosalloc_space.cc \
  gc/space/space.cc \
  gc/space/zygote_space.cc \
  hprof/hprof.cc \
  image.cc \
  indirect_reference_table.cc \
  instruction_set.cc \
  instrumentation.cc \
  intern_table.cc \
  interpreter/interpreter.cc \
  interpreter/interpreter_common.cc \
  interpreter/interpreter_switch_impl.cc \
  jdwp/jdwp_event.cc \
  jdwp/jdwp_expand_buf.cc \
  jdwp/jdwp_handler.cc \
  jdwp/jdwp_main.cc \
  jdwp/jdwp_request.cc \
  jdwp/jdwp_socket.cc \
  jdwp/object_registry.cc \
  jni_internal.cc \
  jobject_comparator.cc \
  mem_map.cc \
  memory_region.cc \
  method_helper.cc \
  mirror/art_field.cc \
  mirror/art_method.cc \
  mirror/array.cc \
  mirror/class.cc \
  mirror/dex_cache.cc \
  mirror/object.cc \
  mirror/reference.cc \
  mirror/stack_trace_element.cc \
  mirror/string.cc \
  mirror/throwable.cc \
  monitor.cc \
  native_bridge_art_interface.cc \
  native/dalvik_system_DexFile.cc \
  native/dalvik_system_VMDebug.cc \
  native/dalvik_system_VMRuntime.cc \
  native/dalvik_system_VMStack.cc \
  native/dalvik_system_ZygoteHooks.cc \
  native/java_lang_Class.cc \
  native/java_lang_DexCache.cc \
  native/java_lang_Object.cc \
  native/java_lang_Runtime.cc \
  native/java_lang_String.cc \
  native/java_lang_System.cc \
  native/java_lang_Thread.cc \
  native/java_lang_Throwable.cc \
  native/java_lang_VMClassLoader.cc \
  native/java_lang_ref_FinalizerReference.cc \
  native/java_lang_ref_Reference.cc \
  native/java_lang_reflect_Array.cc \
  native/java_lang_reflect_Constructor.cc \
  native/java_lang_reflect_Field.cc \
  native/java_lang_reflect_Method.cc \
  native/java_lang_reflect_Proxy.cc \
  native/java_util_concurrent_atomic_AtomicLong.cc \
  native/org_apache_harmony_dalvik_ddmc_DdmServer.cc \
  native/org_apache_harmony_dalvik_ddmc_DdmVmInternal.cc \
  native/sun_misc_Unsafe.cc \
  oat.cc \
  oat_file.cc \
  object_lock.cc \
  offsets.cc \
  os_linux.cc \
  parsed_options.cc \
  primitive.cc \
  quick_exception_handler.cc \
  quick/inline_method_analyser.cc \
  reference_table.cc \
  reflection.cc \
  runtime.cc \
  signal_catcher.cc \
  stack.cc \
  thread.cc \
  thread_list.cc \
  thread_pool.cc \
  throw_location.cc \
  trace.cc \
  transaction.cc \
  profiler.cc \
  fault_handler.cc \
  utf.cc \
  utils.cc \
  verifier/dex_gc_map.cc \
  verifier/instruction_flags.cc \
  verifier/method_verifier.cc \
  verifier/reg_type.cc \
  verifier/reg_type_cache.cc \
  verifier/register_line.cc \
  well_known_classes.cc \
  zip_archive.cc \ 
  arch/context.cc \
  arch/memcmp16.cc \
  arch/arm/registers_arm.cc \
  arch/arm64/registers_arm64.cc \
  arch/x86/registers_x86.cc \
  arch/mips/registers_mips.cc \
  entrypoints/entrypoint_utils.cc \
  entrypoints/interpreter/interpreter_entrypoints.cc \
  entrypoints/jni/jni_entrypoints.cc \
  entrypoints/math_entrypoints.cc \
  entrypoints/portable/portable_alloc_entrypoints.cc \
  entrypoints/portable/portable_cast_entrypoints.cc \
  entrypoints/portable/portable_dexcache_entrypoints.cc \
  entrypoints/portable/portable_field_entrypoints.cc \
  entrypoints/portable/portable_fillarray_entrypoints.cc \
  entrypoints/portable/portable_invoke_entrypoints.cc \
  entrypoints/portable/portable_jni_entrypoints.cc \
  entrypoints/portable/portable_lock_entrypoints.cc \
  entrypoints/portable/portable_thread_entrypoints.cc \
  entrypoints/portable/portable_throw_entrypoints.cc \
  entrypoints/portable/portable_trampoline_entrypoints.cc \
  entrypoints/quick/quick_alloc_entrypoints.cc \
  entrypoints/quick/quick_cast_entrypoints.cc \
  entrypoints/quick/quick_deoptimization_entrypoints.cc \
  entrypoints/quick/quick_dexcache_entrypoints.cc \
  entrypoints/quick/quick_field_entrypoints.cc \
  entrypoints/quick/quick_fillarray_entrypoints.cc \
  entrypoints/quick/quick_instrumentation_entrypoints.cc \
  entrypoints/quick/quick_jni_entrypoints.cc \
  entrypoints/quick/quick_lock_entrypoints.cc \
  entrypoints/quick/quick_math_entrypoints.cc \
  entrypoints/quick/quick_thread_entrypoints.cc \
  entrypoints/quick/quick_throw_entrypoints.cc \
  entrypoints/quick/quick_trampoline_entrypoints.cc)

set(libart_source_file_x86_64
  arch/x86_64/context_x86_64.cc \
  arch/x86_64/entrypoints_init_x86_64.cc \
  arch/x86_64/jni_entrypoints_x86_64.S \
  arch/x86_64/memcmp16_x86_64.S \
  arch/x86_64/portable_entrypoints_x86_64.S \
  arch/x86_64/quick_entrypoints_x86_64.S \
  arch/x86_64/thread_x86_64.cc \
  monitor_pool.cc \
  arch/x86/fault_handler_x86.cc)
	

set(libart_source_file_gcc
		interpreter/interpreter_goto_table_impl.cc)


set(libart_source_host_file
  base/logging_linux.cc \
  monitor_linux.cc \
  runtime_linux.cc \
  thread_linux.cc)


set(libart_enum_operator_out_header_source_file
  arch/x86_64/registers_x86_64.h \
  base/allocator.h \
  base/mutex.h \
  base/unix_file/fd_file.h \
  dex_file.h \
  dex_instruction.h \
  gc_root.h \
  gc/collector/gc_type.h \
  gc/collector_type.h \
  gc/space/space.h \
  gc/heap.h \
  indirect_reference_table.h \
  instruction_set.h \
  invoke_type.h \
  jdwp/jdwp.h \
  jdwp/jdwp_constants.h \
  lock_word.h \
  mirror/class.h \
  oat.h \
  quick/inline_method_analyser.h \
  thread.h \
  thread_state.h \
  verifier/method_verifier.h)

#include source file path of library
include_directories()
#library file path.
link_directories()

SET(CMAKE_CXX_COMPILER g++-4.8)

#create library
add_library(libart ${libart_source_file} \
 ${libart_source_file_x86_64} \
 ${libart_source_file_gcc} \
 ${libart_source_host_file} \
 ${bart_enum_operator_out_header_source_file})

target_link_libraries(libart cutils ziparchive-host z utils sigchain ld pthread backtrace_libc++ log nativehelper nativebridge
