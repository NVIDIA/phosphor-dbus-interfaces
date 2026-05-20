# Generated file; do not modify.
subdir('System')
subdir('TID')

sdbusplus_current_path = 'com/nvidia/PreBootDiag/Config'

generated_markdown += custom_target(
    'com/nvidia/PreBootDiag/Config/System__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/PreBootDiag/Config/System.interface.yaml',
    ],
    output: ['System.md'],
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
        'com/nvidia/PreBootDiag/Config/System',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/PreBootDiag/Config/TID__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/PreBootDiag/Config/TID.interface.yaml',
    ],
    output: ['TID.md'],
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
        'com/nvidia/PreBootDiag/Config/TID',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

