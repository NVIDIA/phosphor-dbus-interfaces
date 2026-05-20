# Generated file; do not modify.
subdir('ConfigRequester')
subdir('ConfigUpdater')

sdbusplus_current_path = 'com/nvidia/DeviceConfiguration'

generated_markdown += custom_target(
    'com/nvidia/DeviceConfiguration/ConfigRequester__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/DeviceConfiguration/ConfigRequester.interface.yaml',
    ],
    output: ['ConfigRequester.md'],
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
        'com/nvidia/DeviceConfiguration/ConfigRequester',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/DeviceConfiguration/ConfigUpdater__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/DeviceConfiguration/ConfigUpdater.interface.yaml',
    ],
    output: ['ConfigUpdater.md'],
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
        'com/nvidia/DeviceConfiguration/ConfigUpdater',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

