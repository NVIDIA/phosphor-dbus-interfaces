# Generated file; do not modify.
subdir('SecureErase')
generated_others += custom_target(
    'xyz/openbmc_project/Nvme/SecureErase__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Nvme/SecureErase.interface.yaml',  ],
    output: [ 'SecureErase.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Nvme/SecureErase',
    ],
)

subdir('Status')
generated_others += custom_target(
    'xyz/openbmc_project/Nvme/Status__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Nvme/Status.interface.yaml',  ],
    output: [ 'Status.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Nvme/Status',
    ],
)

