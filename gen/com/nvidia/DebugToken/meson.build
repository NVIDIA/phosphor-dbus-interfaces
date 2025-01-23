# Generated file; do not modify.
generated_sources += custom_target(
    'com/nvidia/DebugToken__cpp'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/DebugToken.interface.yaml',  ],
    output: [ 'common.hpp', 'server.cpp', 'server.hpp', 'aserver.hpp', 'client.hpp',  ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/DebugToken',
    ],
)

subdir('ErasePolicy')
generated_others += custom_target(
    'com/nvidia/DebugToken/ErasePolicy__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/DebugToken/ErasePolicy.interface.yaml',  ],
    output: [ 'ErasePolicy.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/DebugToken/ErasePolicy',
    ],
)

