# Generated file; do not modify.
subdir('AdminPowerProfile')
subdir('CurrentPowerProfile')
subdir('PowerProfile')
subdir('PowerSmoothing')
subdir('ProfileActionAsync')

sdbusplus_current_path = 'com/nvidia/PowerSmoothing'

generated_markdown += custom_target(
    'com/nvidia/PowerSmoothing/AdminPowerProfile__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerSmoothing/AdminPowerProfile.interface.yaml',
    ],
    output: ['AdminPowerProfile.md'],
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
        'com/nvidia/PowerSmoothing/AdminPowerProfile',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerSmoothing/CurrentPowerProfile__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerSmoothing/CurrentPowerProfile.interface.yaml',
    ],
    output: ['CurrentPowerProfile.md'],
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
        'com/nvidia/PowerSmoothing/CurrentPowerProfile',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerSmoothing/PowerProfile__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerSmoothing/PowerProfile.interface.yaml',
    ],
    output: ['PowerProfile.md'],
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
        'com/nvidia/PowerSmoothing/PowerProfile',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerSmoothing/PowerSmoothing__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerSmoothing/PowerSmoothing.interface.yaml',
    ],
    output: ['PowerSmoothing.md'],
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
        'com/nvidia/PowerSmoothing/PowerSmoothing',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PowerSmoothing/ProfileActionAsync__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/PowerSmoothing/ProfileActionAsync.interface.yaml',
    ],
    output: ['ProfileActionAsync.md'],
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
        'com/nvidia/PowerSmoothing/ProfileActionAsync',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

