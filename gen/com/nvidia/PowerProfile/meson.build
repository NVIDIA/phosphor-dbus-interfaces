# Generated file; do not modify.
subdir('Profile')
subdir('ProfileInfo')
subdir('ProfileInfoAsync')

sdbusplus_current_path = 'com/nvidia/PowerProfile'

generated_markdown += custom_target(
    'com/nvidia/PowerProfile/Profile__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerProfile/Profile.interface.yaml',
    ],
    output: ['Profile.md'],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'markdown',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/Profile',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerProfile/ProfileInfo__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerProfile/ProfileInfo.interface.yaml',
    ],
    output: ['ProfileInfo.md'],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'markdown',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/ProfileInfo',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerProfile/ProfileInfoAsync__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerProfile/ProfileInfoAsync.interface.yaml',
    ],
    output: ['ProfileInfoAsync.md'],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'markdown',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/PowerProfile/ProfileInfoAsync',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

