# Generated file; do not modify.
subdir('Responder')
generated_others += custom_target(
    'xyz/openbmc_project/SPDM/Responder__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/SPDM/Responder.interface.yaml',  ],
    output: [ 'Responder.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/SPDM/Responder',
    ],
)

