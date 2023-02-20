# Generated file; do not modify.
subdir('CompleteReset')
generated_others += custom_target(
    'com/nvidia/Common/CompleteReset__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Common/CompleteReset.interface.yaml',  ],
    output: [ 'CompleteReset.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Common/CompleteReset',
    ],
)

