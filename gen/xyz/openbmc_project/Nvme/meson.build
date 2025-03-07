# Generated file; do not modify.
subdir('Operation')
generated_others += custom_target(
    'xyz/openbmc_project/Nvme/Operation__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Nvme/Operation.interface.yaml',  ],
    output: [ 'Operation.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Nvme/Operation',
    ],
)

subdir('SecureErase')
generated_others += custom_target(
    'xyz/openbmc_project/Nvme/SecureErase__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/Nvme/SecureErase.interface.yaml',  ],
    output: [ 'SecureErase.md' ],
    depend_files: sdbusplusplus_depfiles,
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
    input: [ '../../../../yaml/xyz/openbmc_project/Nvme/Status.errors.yaml', '../../../../yaml/xyz/openbmc_project/Nvme/Status.interface.yaml',  ],
    output: [ 'Status.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/Nvme/Status',
    ],
)

