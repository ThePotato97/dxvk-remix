dxvk_shaders = files([
  'shaders/dxvk_blit_frag_1d.frag',
  'shaders/dxvk_blit_frag_2d.frag',
  'shaders/dxvk_blit_frag_3d.frag',

  'shaders/dxvk_clear_buffer_u.comp',
  'shaders/dxvk_clear_buffer_f.comp',
  'shaders/dxvk_clear_image1d_u.comp',
  'shaders/dxvk_clear_image1d_f.comp',
  'shaders/dxvk_clear_image1darr_u.comp',
  'shaders/dxvk_clear_image1darr_f.comp',
  'shaders/dxvk_clear_image2d_u.comp',
  'shaders/dxvk_clear_image2d_f.comp',
  'shaders/dxvk_clear_image2darr_u.comp',
  'shaders/dxvk_clear_image2darr_f.comp',
  'shaders/dxvk_clear_image3d_u.comp',
  'shaders/dxvk_clear_image3d_f.comp',
  
  'shaders/dxvk_copy_buffer_image.comp',
  'shaders/dxvk_copy_color_1d.frag',
  'shaders/dxvk_copy_color_2d.frag',
  'shaders/dxvk_copy_color_ms.frag',
  'shaders/dxvk_copy_depth_1d.frag',
  'shaders/dxvk_copy_depth_2d.frag',
  'shaders/dxvk_copy_depth_ms.frag',
  'shaders/dxvk_copy_depth_stencil_1d.frag',
  'shaders/dxvk_copy_depth_stencil_2d.frag',
  'shaders/dxvk_copy_depth_stencil_ms.frag',

  'shaders/dxvk_fullscreen_geom.geom',
  'shaders/dxvk_fullscreen_vert.vert',
  'shaders/dxvk_fullscreen_layer_vert.vert',

  'shaders/dxvk_pack_d24s8.comp',
  'shaders/dxvk_pack_d32s8.comp',

  'shaders/dxvk_present_frag.frag',
  'shaders/dxvk_present_frag_blit.frag',
  'shaders/dxvk_present_frag_ms.frag',
  'shaders/dxvk_present_frag_ms_amd.frag',
  'shaders/dxvk_present_vert.vert',

  'shaders/dxvk_resolve_frag_d.frag',
  'shaders/dxvk_resolve_frag_ds.frag',
  'shaders/dxvk_resolve_frag_f.frag',
  'shaders/dxvk_resolve_frag_f_amd.frag',
  'shaders/dxvk_resolve_frag_i.frag',
  'shaders/dxvk_resolve_frag_u.frag',
  
  'shaders/dxvk_unpack_d24s8_as_d32s8.comp',
  'shaders/dxvk_unpack_d24s8.comp',
  'shaders/dxvk_unpack_d32s8.comp',
  
  'hud/shaders/hud_line_frag.frag',
  'hud/shaders/hud_line_vert.vert',

  'hud/shaders/hud_text_frag.frag',
  'hud/shaders/hud_text_vert.vert',
])

dxvk_src = files([
  'dxvk_adapter.cpp',
  'dxvk_adapter.h',
  'dxvk_barrier.cpp',
  'dxvk_barrier.h',
  'dxvk_bind_mask.h',
  'dxvk_buffer.cpp',
  'dxvk_buffer.h',
  'dxvk_cmdlist.cpp',
  'dxvk_cmdlist.h',
  'dxvk_compute.cpp',
  'dxvk_compute.h',
  'dxvk_constant_state.h',
  'dxvk_context.cpp',
  'dxvk_context.h',
  'dxvk_context_state.h',
  'dxvk_cs.cpp',
  'dxvk_cs.h',
  'dxvk_data.cpp',
  'dxvk_data.h',
  'dxvk_descriptor.cpp',
  'dxvk_descriptor.h',
  'dxvk_device.cpp',
  'dxvk_device.h',
  'dxvk_device_filter.cpp',
  'dxvk_device_filter.h',
  'dxvk_device_info.h',
  'dxvk_extension_provider.h',
  'dxvk_extensions.cpp',
  'dxvk_extensions.h',
  'dxvk_format.cpp',
  'dxvk_format.h',
  'dxvk_framebuffer.cpp',
  'dxvk_framebuffer.h',
  'dxvk_gpu_event.cpp',
  'dxvk_gpu_event.h',
  'dxvk_gpu_query.cpp',
  'dxvk_gpu_query.h',
  'dxvk_graphics.cpp',
  'dxvk_graphics.h',
  'dxvk_graphics_state.h',
  'dxvk_hash.h',
  'dxvk_image.cpp',
  'dxvk_image.h',
  'dxvk_include.h',
  'dxvk_instance.cpp',
  'dxvk_instance.h',
  'dxvk_lifetime.cpp',
  'dxvk_lifetime.h',
  'dxvk_limits.h',
  'dxvk_memory.cpp',
  'dxvk_memory.h',
  'dxvk_meta_blit.cpp',
  'dxvk_meta_blit.h',
  'dxvk_meta_clear.cpp',
  'dxvk_meta_clear.h',
  'dxvk_meta_copy.cpp',
  'dxvk_meta_copy.h',
  'dxvk_meta_mipgen.cpp',
  'dxvk_meta_mipgen.h',
  'dxvk_meta_pack.cpp',
  'dxvk_meta_pack.h',
  'dxvk_meta_resolve.cpp',
  'dxvk_meta_resolve.h',
  'dxvk_objects.h',
  'dxvk_openvr.cpp',
  'dxvk_openvr.h',
  'dxvk_openxr.cpp',
  'dxvk_openxr.h',
  'dxvk_options.cpp',
  'dxvk_options.h',
  'dxvk_pipecache.cpp',
  'dxvk_pipecache.h',
  'dxvk_pipelayout.cpp',
  'dxvk_pipelayout.h',
  'dxvk_pipemanager.cpp',
  'dxvk_pipemanager.h',
  'dxvk_platform_exts.h',
  'dxvk_queue.cpp',
  'dxvk_queue.h',
  'dxvk_raytracing.cpp',
  'dxvk_raytracing.h',
  'dxvk_recycler.h',
  'dxvk_renderpass.cpp',
  'dxvk_renderpass.h',
  'dxvk_resource.cpp',
  'dxvk_resource.h',
  'dxvk_sampler.cpp',
  'dxvk_sampler.h',
  'dxvk_scoped_annotation.cpp',
  'dxvk_scoped_annotation.h',
  'dxvk_shader.cpp',
  'dxvk_shader.h',
  'dxvk_shader_key.cpp',
  'dxvk_shader_key.h',
  'dxvk_shader_manager.cpp',
  'dxvk_shader_manager.h',
  'dxvk_signal.cpp',
  'dxvk_signal.h',
  'dxvk_spec_const.cpp',
  'dxvk_spec_const.h',
  'dxvk_staging.cpp',
  'dxvk_staging.h',
  'dxvk_state_cache.cpp',
  'dxvk_state_cache.h',
  'dxvk_state_cache_types.h',
  'dxvk_stats.cpp',
  'dxvk_stats.h',
  'dxvk_swapchain_blitter.cpp',
  'dxvk_swapchain_blitter.h',
  'dxvk_unbound.cpp',
  'dxvk_unbound.h',
  'dxvk_util.cpp',
  'dxvk_util.h',

  'rtx_render/rtx_bloom.cpp',
  'rtx_render/rtx_bloom.h',
  'rtx_render/rtx_denoise.cpp',
  'rtx_render/rtx_denoise.h',
  'rtx_render/rtx_denoise_type.h',
  'rtx_render/rtx_dlss.cpp',
  'rtx_render/rtx_dlss.cpp', 
  'rtx_render/rtx_dlss.h',
  'rtx_render/rtx_nis.cpp',
  'rtx_render/rtx_nis.h',
  'rtx_render/rtx_taa.h',
  'rtx_render/rtx_taa.cpp',
  'rtx_render/rtx_pathtracer_gbuffer.cpp',
  'rtx_render/rtx_pathtracer_gbuffer.h',
  'rtx_render/rtx_pathtracer_integrate_direct.cpp',
  'rtx_render/rtx_pathtracer_integrate_direct.h',
  'rtx_render/rtx_pathtracer_integrate_indirect.cpp',
  'rtx_render/rtx_pathtracer_integrate_indirect.h',
  'rtx_render/rtx_postFx.h',
  'rtx_render/rtx_postFx.cpp',
  'rtx_render/rtx_restir_gi_rayquery.cpp',
  'rtx_render/rtx_restir_gi_rayquery.h',
  'rtx_render/rtx_rtxdi_rayquery.cpp',
  'rtx_render/rtx_rtxdi_rayquery.h',
  'rtx_render/rtx_auto_exposure.cpp',
  'rtx_render/rtx_auto_exposure.h',
  'rtx_render/rtx_reflex.cpp',
  'rtx_render/rtx_reflex.h',
  'rtx_render/rtx_tonemapping.cpp',
  'rtx_render/rtx_tonemapping.h',
  'rtx_render/rtx_local_tonemapping.cpp',
  'rtx_render/rtx_local_tonemapping.h',
  'rtx_render/rtx_game_capturer.cpp',
  'rtx_render/rtx_game_capturer.h',
  'rtx_render/rtx_game_capturer_paths.h',
  'rtx_render/rtx_intersection_test_helpers.h',
  'rtx_render/rtx_matrix_helpers.h',
  'rtx_render/rtx.h',
  'rtx_render/rtx_accelmanager.cpp',
  'rtx_render/rtx_accelmanager.h',
  'rtx_render/rtx_asset_exporter.cpp',
  'rtx_render/rtx_asset_exporter.h',
  'rtx_render/rtx_asset_replacer.cpp',
  'rtx_render/rtx_asset_replacer.h',
  'rtx_render/rtx_camera.cpp',
  'rtx_render/rtx_camera.h',
  'rtx_render/rtx_cameramanager.cpp',
  'rtx_render/rtx_cameramanager.h',
  'rtx_render/rtx_composite.cpp',
  'rtx_render/rtx_composite.h',
  'rtx_render/rtx_context.cpp',
  'rtx_render/rtx_context.h',
  'rtx_render/rtx_debug_view.cpp',
  'rtx_render/rtx_debug_view.h',
  'rtx_render/rtx_demodulate.cpp',
  'rtx_render/rtx_demodulate.h',
  'rtx_render/rtx_volume_integrate.cpp',
  'rtx_render/rtx_volume_integrate.h',
  'rtx_render/rtx_volume_filter.cpp',
  'rtx_render/rtx_volume_filter.h',
  'rtx_render/rtx_volume_preintegrate.cpp',
  'rtx_render/rtx_volume_preintegrate.h',
  'rtx_render/rtx_bindlessresourcemanager.cpp',
  'rtx_render/rtx_bindlessresourcemanager.h',
  'rtx_render/rtx_bridgemessagechannel.h',
  'rtx_render/rtx_drawcallcache.cpp',
  'rtx_render/rtx_drawcallcache.h',
  'rtx_render/rtx_geometry_utils.cpp',
  'rtx_render/rtx_geometry_utils.h',
  'rtx_render/rtx_imgui.cpp',
  'rtx_render/rtx_imgui.h',
  'rtx_render/rtx_initializer.cpp',
  'rtx_render/rtx_initializer.h',
  'rtx_render/rtx_instancemanager.cpp',
  'rtx_render/rtx_instancemanager.h',
  'rtx_render/rtx_lightmanager.cpp',
  'rtx_render/rtx_lightmanager.h',
  'rtx_render/rtx_lights.cpp',
  'rtx_render/rtx_lights.h',
  'rtx_render/rtx_materials.cpp',
  'rtx_render/rtx_materials.h',
  'rtx_render/rtx_mod_manager.cpp',
  'rtx_render/rtx_mod_manager.h',
  'rtx_render/rtx_mod_usd.cpp',
  'rtx_render/rtx_mod_usd.h',
  'rtx_render/rtx_nrd_context.cpp',
  'rtx_render/rtx_nrd_context.h',
  'rtx_render/rtx_nrd_settings.cpp',
  'rtx_render/rtx_nrd_settings.h',
  'rtx_render/rtx_opacity_micromap_manager.cpp',
  'rtx_render/rtx_opacity_micromap_manager.h',
  'rtx_render/rtx_options.cpp',
  'rtx_render/rtx_options.h',
  'rtx_render/rtx_option.cpp',
  'rtx_render/rtx_option.h',
  'rtx_render/rtx_rayportalmanager.cpp',
  'rtx_render/rtx_rayportalmanager.h',
  'rtx_render/rtx_resources.cpp',
  'rtx_render/rtx_resources.h',
  'rtx_render/rtx_scenemanager.cpp',
  'rtx_render/rtx_scenemanager.h',
  'rtx_render/rtx_sparserefcountcache.h',
  'rtx_render/rtx_sparseuniquecache.h',
  'rtx_render/rtx_texture.cpp',
  'rtx_render/rtx_texture.h',
  'rtx_render/rtx_texturemanager.cpp',
  'rtx_render/rtx_texturemanager.h',
  'rtx_render/rtx_types.h',
  'rtx_render/rtx_utils.h',
  'rtx_render/rtx_volumemanager.cpp',
  'rtx_render/rtx_volumemanager.h',
  'rtx_render/rtx_image_utils.cpp',
  'rtx_render/rtx_image_utils.h',
  'rtx_render/rtx_io.cpp',
  'rtx_render/rtx_io.h',
  'rtx_render/rtx_semaphore.cpp',
  'rtx_render/rtx_semaphore.h',
  'rtx_render/rtx_asset_datamanager.cpp',
  'rtx_render/rtx_asset_datamanager.h',
  'rtx_render/rtx_asset_data.h',
  'rtx_render/rtx_asset_package.h',

  'rtx_render/rtx_hashing.cpp',
  'rtx_render/rtx_hashing.h',

  'platform/dxvk_win32_exts.cpp',
  
  'hud/dxvk_hud.cpp',
  'hud/dxvk_hud_font.cpp',
  'hud/dxvk_hud_item.cpp',
  'hud/dxvk_hud_renderer.cpp',
  'hud/dxvk_hud.h',
  'hud/dxvk_hud_font.h',
  'hud/dxvk_hud_item.h',
  'hud/dxvk_hud_renderer.h',
  
  'imgui/dxvk_imgui_splash.cpp',
  'imgui/dxvk_imgui_splash.h',
  'imgui/dxvk_imgui_about.cpp',
  'imgui/dxvk_imgui_about.h',
  'imgui/dxvk_imgui.cpp',
  'imgui/dxvk_imgui.h',
  'imgui/imconfig.h',
  'imgui/imgui.cpp',
  'imgui/imgui.h',
  'imgui/imgui_demo.cpp',
  'imgui/imgui_draw.cpp',
  'imgui/imgui_impl_vulkan.cpp',
  'imgui/imgui_impl_vulkan.h',
  'imgui/imgui_impl_win32.cpp',
  'imgui/imgui_impl_win32.h',
  'imgui/imgui_internal.h',
  'imgui/imgui_tables.cpp',
  'imgui/imgui_widgets.cpp',
  'imgui/imstb_rectpack.h',
  'imgui/imstb_textedit.h',
  'imgui/imstb_truetype.h',
])

  dxvk_src += files([

    'rtx_render/rtx_NGXWrapper.cpp',
    'rtx_render/rtx_NGXWrapper.h',
  ])

thread_dep = dependency('threads')

nrd_include_dir = include_directories(join_paths(meson.global_source_root(), 'external/nrd/Include'))
nrd_lib_path = join_paths(meson.global_source_root(), 'external/nrd/Lib/Release')
if get_option('buildtype') == 'debug'  
  nrd_lib_path = join_paths(meson.global_source_root(), 'external/nrd/Lib/Debug')
endif
cc = meson.get_compiler('c')
nrd_lib = cc.find_library('NRD', dirs : nrd_lib_path)
nrd_dep = declare_dependency(
  dependencies : [ nrd_lib ],
  include_directories : nrd_include_dir
)

dlss_include_dir = include_directories(join_paths(meson.global_source_root(), dlss_root_path + '/Include'))
dlss_lib_path = join_paths(meson.global_source_root(), dlss_root_path + '/Lib/Windows_x86_64/x86_64')
cc = meson.get_compiler('c')
dlss_lib_name = 'nvsdk_ngx_s'
if get_option('buildtype') == 'debug'  
  dlss_lib_name = 'nvsdk_ngx_s_dbg'
endif
dlss_lib = cc.find_library(dlss_lib_name, dirs : dlss_lib_path)
dlss_dep = declare_dependency(
  dependencies : [ dlss_lib ],
  include_directories : dlss_include_dir
)

generated_dxvk_shaders = glsl_generator.process(dxvk_shaders)

rtx_shaders_command = [ python_interpreter, shader_compile_script,
    '-glslang', glsl_compiler,
    '-slangc', slang_compiler,
    '-input', '@CURRENT_SOURCE_DIR@/shaders/rtx',
    '-include', '@CURRENT_SOURCE_DIR@/shaders',
    '-include', rtxdi_include_path_string,
    '-output', '@OUTDIR@/rtx_shaders',
    '-parallel' ]

if get_option('buildtype').startswith('debug')
  rtx_shaders_command += [ '-debug' ]
endif

rtx_shaders = custom_target(
  'rtx_shaders',
  build_by_default: true,
  output: ['_built_shaders.txt'],
  command: rtx_shaders_command
)

dxvk_embedded_data_files = files([
  '../../external/fonts/NVIDIASans/NVIDIASansMd.ttf',
  '../../external/fonts/RobotoMono/RobotoMonoRg.ttf'
])

dxvk_generated_embedded_files = embedding_compiler.process(dxvk_embedded_data_files)

dxvk_deps = [ thread_dep, vkcommon_dep, dxvk_extradep, usd_dep, lssUsd_dep, nrd_dep, dlss_dep, tracy_dep, tracy_dep_dynamic, aftermath_dep, nvapi_dep, reflex_dep ]

if enable_rtxio
  dxvk_deps += rtxio_dep
endif

if not dxvk_is_msvc
	ws2_32_dep = declare_dependency(
		dependencies : [ lib_ws2_32 ])
	dxvk_deps += ws2_32_dep
endif

dxvk_lib = static_library('dxvk', dxvk_src, dxvk_version, [generated_dxvk_shaders, rtx_shaders, dxvk_generated_embedded_files],
  link_with           : [ util_lib, spirv_lib ], 
  dependencies        : [ dxvk_deps ],
  include_directories : [ dxvk_include_path, dxvk_shader_include_path, rtxdi_include_path ],
  override_options    : ['cpp_std='+dxvk_cpp_std])

dxvk_dep = declare_dependency(
  link_with           : [ dxvk_lib ],
  include_directories : [ dxvk_include_path ])
