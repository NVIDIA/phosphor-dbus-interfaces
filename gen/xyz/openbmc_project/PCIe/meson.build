# Generated file; do not modify.
subdir('LTSSMState')
generated_others += custom_target(
    'xyz/openbmc_project/PCIe/LTSSMState__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/PCIe/LTSSMState.interface.yaml',  ],
    output: [ 'LTSSMState.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/PCIe/LTSSMState',
    ],
)

subdir('PCIeECC')
generated_others += custom_target(
    'xyz/openbmc_project/PCIe/PCIeECC__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/PCIe/PCIeECC.interface.yaml',  ],
    output: [ 'PCIeECC.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/PCIe/PCIeECC',
    ],
)

