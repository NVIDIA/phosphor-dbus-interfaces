# Generated file; do not modify.
subdir('BootStatus')
generated_others += custom_target(
    'com/nvidia/RoT/BootStatus__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/RoT/BootStatus.interface.yaml',  ],
    output: [ 'BootStatus.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/RoT/BootStatus',
    ],
)

