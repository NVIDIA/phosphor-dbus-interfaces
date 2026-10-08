# Generated file; do not modify.

sdbusplus_current_path = 'com/nvidia/ConsoleMux'

generated_sources += custom_target(
    'com/nvidia/ConsoleMux__cpp'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/ConsoleMux.errors.yaml',
        '../../../../yaml/com/nvidia/ConsoleMux.interface.yaml',
    ],
    output: [
        'error.cpp',
        'error.hpp',
        'common.hpp',
        'server.hpp',
        'server.cpp',
        'aserver.hpp',
        'client.hpp',
    ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'cpp',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/ConsoleMux',
    ],
    install: should_generate_cpp,
    install_dir: [
        false,
        get_option('includedir') / sdbusplus_current_path,
        get_option('includedir') / sdbusplus_current_path,
        get_option('includedir') / sdbusplus_current_path,
        false,
        get_option('includedir') / sdbusplus_current_path,
        get_option('includedir') / sdbusplus_current_path,
    ],
    build_by_default: should_generate_cpp,
)

