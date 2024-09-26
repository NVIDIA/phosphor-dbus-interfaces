# Generated file; do not modify.
subdir('NSMRawCommand')
generated_others += custom_target(
    'xyz/openbmc_project/NSM/NSMRawCommand__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/NSM/NSMRawCommand.interface.yaml',  ],
    output: [ 'NSMRawCommand.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/NSM/NSMRawCommand',
    ],
)

subdir('NSMRawCommandStatus')
generated_others += custom_target(
    'xyz/openbmc_project/NSM/NSMRawCommandStatus__markdown'.underscorify(),
    input: [ '../../../../yaml/xyz/openbmc_project/NSM/NSMRawCommandStatus.interface.yaml',  ],
    output: [ 'NSMRawCommandStatus.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'xyz/openbmc_project/NSM/NSMRawCommandStatus',
    ],
)

