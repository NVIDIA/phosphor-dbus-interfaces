# Generated file; do not modify.
subdir('ErrorInjection')
generated_others += custom_target(
    'com/nvidia/ErrorInjection/ErrorInjection__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/ErrorInjection/ErrorInjection.interface.yaml',  ],
    output: [ 'ErrorInjection.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/ErrorInjection/ErrorInjection',
    ],
)

subdir('ErrorInjectionCapability')
generated_others += custom_target(
    'com/nvidia/ErrorInjection/ErrorInjectionCapability__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/ErrorInjection/ErrorInjectionCapability.interface.yaml',  ],
    output: [ 'ErrorInjectionCapability.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/ErrorInjection/ErrorInjectionCapability',
    ],
)

