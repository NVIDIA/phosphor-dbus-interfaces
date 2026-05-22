# Generated file; do not modify.
subdir('Action')
subdir('Blob')

sdbusplus_current_path = 'com/nvidia/Dot'

generated_markdown += custom_target(
    'com/nvidia/Dot/Action__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/Dot/Action.interface.yaml',
    ],
    output: ['Action.md'],
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
        'com/nvidia/Dot/Action',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Dot/Blob__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/Dot/Blob.interface.yaml',
    ],
    output: ['Blob.md'],
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
        'com/nvidia/Dot/Blob',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

