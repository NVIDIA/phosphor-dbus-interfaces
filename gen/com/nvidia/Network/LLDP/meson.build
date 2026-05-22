# Generated file; do not modify.
subdir('Settings')
subdir('TLVs')

sdbusplus_current_path = 'com/nvidia/Network/LLDP'

generated_markdown += custom_target(
    'com/nvidia/Network/LLDP/Settings__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Network/LLDP/Settings.interface.yaml',
    ],
    output: ['Settings.md'],
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
        meson.current_source_dir() / '../../../../../yaml',
        'com/nvidia/Network/LLDP/Settings',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Network/LLDP/TLVs__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Network/LLDP/TLVs.interface.yaml',
    ],
    output: ['TLVs.md'],
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
        meson.current_source_dir() / '../../../../../yaml',
        'com/nvidia/Network/LLDP/TLVs',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

