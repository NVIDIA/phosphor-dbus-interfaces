# Generated file; do not modify.
subdir('UpdateTimeout')
subdir('WriteProtection')

sdbusplus_current_path = 'com/nvidia/Software'

generated_markdown += custom_target(
    'com/nvidia/Software/UpdateTimeout__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/Software/UpdateTimeout.interface.yaml'],
    output: ['UpdateTimeout.md'],
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
        'com/nvidia/Software/UpdateTimeout',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Software/WriteProtection__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/Software/WriteProtection.interface.yaml',
    ],
    output: ['WriteProtection.md'],
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
        'com/nvidia/Software/WriteProtection',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

