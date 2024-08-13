# Generated file; do not modify.
subdir('Profile')
generated_others += custom_target(
    'com/nvidia/PowerProfile/Profile__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/PowerProfile/Profile.interface.yaml',  ],
    output: [ 'Profile.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/Profile',
    ],
)

subdir('ProfileInfo')
generated_others += custom_target(
    'com/nvidia/PowerProfile/ProfileInfo__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/PowerProfile/ProfileInfo.interface.yaml',  ],
    output: [ 'ProfileInfo.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/ProfileInfo',
    ],
)

subdir('ProfileInfoAsync')
generated_others += custom_target(
    'com/nvidia/PowerProfile/ProfileInfoAsync__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/PowerProfile/ProfileInfoAsync.interface.yaml',  ],
    output: [ 'ProfileInfoAsync.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/ProfileInfoAsync',
    ],
)

