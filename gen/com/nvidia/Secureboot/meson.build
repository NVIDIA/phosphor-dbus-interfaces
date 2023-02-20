# Generated file; do not modify.
subdir('Cec')
generated_others += custom_target(
    'com/nvidia/Secureboot/Cec__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Secureboot/Cec.interface.yaml',  ],
    output: [ 'Cec.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Secureboot/Cec',
    ],
)

