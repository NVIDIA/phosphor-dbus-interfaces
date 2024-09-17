# Generated file; do not modify.
subdir('NSMRawCommand')
generated_others += custom_target(
    'com/nvidia/NSM/NSMRawCommand__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/NSM/NSMRawCommand.interface.yaml',  ],
    output: [ 'NSMRawCommand.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/NSM/NSMRawCommand',
    ],
)

