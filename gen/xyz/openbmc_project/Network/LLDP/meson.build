# Generated file; do not modify.
subdir('Settings')
generated_others += custom_target(
    'xyz/openbmc_project/Network/LLDP/Settings__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Network/LLDP/Settings.interface.yaml',  ],
    output: [ 'Settings.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Network/LLDP/Settings',
    ],
)

subdir('TLVs')
generated_others += custom_target(
    'xyz/openbmc_project/Network/LLDP/TLVs__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Network/LLDP/TLVs.interface.yaml',  ],
    output: [ 'TLVs.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Network/LLDP/TLVs',
    ],
)

