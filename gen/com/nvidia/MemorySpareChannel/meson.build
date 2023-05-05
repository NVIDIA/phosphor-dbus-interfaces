# Generated file; do not modify.
generated_sources += custom_target(
    'com/nvidia/MemorySpareChannel__cpp'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/MemorySpareChannel.interface.yaml',  ],
    output: [ 'server.cpp', 'server.hpp', 'client.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/MemorySpareChannel',
    ],
)

