# Generated file; do not modify.
subdir('FabricManager')

sdbusplus_current_path = 'com/nvidia/State'

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

