# Generated file; do not modify.
subdir('Common')
subdir('ComputeHash')
generated_others += custom_target(
    'com/nvidia/ComputeHash__markdown'.underscorify(),
    input: [ '../../../yaml/com/nvidia/ComputeHash.interface.yaml',  ],
    output: [ 'ComputeHash.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../yaml',
        'com/nvidia/ComputeHash',
    ],
)

subdir('Edpp')
generated_others += custom_target(
    'com/nvidia/Edpp__markdown'.underscorify(),
    input: [ '../../../yaml/com/nvidia/Edpp.interface.yaml',  ],
    output: [ 'Edpp.md' ],
    depend_files: sdbusplusplus_depfiles,
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
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../yaml',
        'com/nvidia/MigMode',
    ],
)

subdir('NVLink')
subdir('Protocol')
subdir('Secureboot')
