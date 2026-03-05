# Generated file; do not modify.
subdir('DeviceState')
subdir('FabricManager')
subdir('HardwareWriteProtectedControl')

sdbusplus_current_path = 'com/nvidia/State'

generated_markdown += custom_target(
    'com/nvidia/State/DeviceState__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/State/DeviceState.interface.yaml'],
    output: ['DeviceState.md'],
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
        'com/nvidia/State/DeviceState',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/State/FabricManager__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/State/FabricManager.interface.yaml'],
    output: ['FabricManager.md'],
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
        'com/nvidia/State/FabricManager',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/State/HardwareWriteProtectedControl__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/State/HardwareWriteProtectedControl.interface.yaml',
    ],
    output: ['HardwareWriteProtectedControl.md'],
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
        'com/nvidia/State/HardwareWriteProtectedControl',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

