# Generated file; do not modify.
subdir('Binding')
generated_others += custom_target(
    'xyz/openbmc_project/MCTP/Binding__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/MCTP/Binding.interface.yaml',  ],
    output: [ 'Binding.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/MCTP/Binding',
    ],
)

subdir('Endpoint')
generated_others += custom_target(
    'xyz/openbmc_project/MCTP/Endpoint__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/MCTP/Endpoint.interface.yaml',  ],
    output: [ 'Endpoint.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/MCTP/Endpoint',
    ],
)

subdir('UUID')
generated_others += custom_target(
    'xyz/openbmc_project/MCTP/UUID__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/MCTP/UUID.interface.yaml',  ],
    output: [ 'UUID.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/MCTP/UUID',
    ],
)

