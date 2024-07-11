# Generated file; do not modify.
subdir('Set')
generated_others += custom_target(
    'com/nvidia/Async/Set__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Async/Set.interface.yaml',  ],
    output: [ 'Set.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Async/Set',
    ],
)

subdir('Status')
generated_others += custom_target(
    'com/nvidia/Async/Status__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Async/Status.interface.yaml',  ],
    output: [ 'Status.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Async/Status',
    ],
)

