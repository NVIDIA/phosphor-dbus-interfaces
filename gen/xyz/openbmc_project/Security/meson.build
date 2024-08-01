# Generated file; do not modify.
subdir('Signing')
generated_others += custom_target(
    'xyz/openbmc_project/Security/Signing__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Security/Signing.interface.yaml',  ],
    output: [ 'Signing.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Security/Signing',
    ],
)

subdir('SigningConfig')
generated_others += custom_target(
    'xyz/openbmc_project/Security/SigningConfig__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Security/SigningConfig.interface.yaml',  ],
    output: [ 'SigningConfig.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Security/SigningConfig',
    ],
)

