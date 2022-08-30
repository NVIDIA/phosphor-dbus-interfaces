# Generated file; do not modify.
subdir('Common')
subdir('Edpp')
generated_others += custom_target(
    'com/nvidia/Edpp__markdown'.underscorify(),
    input: [ '../../../yaml/com/nvidia/Edpp.interface.yaml',  ],
    output: [ 'Edpp.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../yaml',
        'com/nvidia/Edpp',
    ],
)

subdir('MigMode')
generated_others += custom_target(
    'com/nvidia/MigMode__markdown'.underscorify(),
    input: [ '../../../yaml/com/nvidia/MigMode.interface.yaml',  ],
    output: [ 'MigMode.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../yaml',
        'com/nvidia/MigMode',
    ],
)

subdir('NVLink')
