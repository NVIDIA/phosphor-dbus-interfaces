# Generated file; do not modify.
subdir('Cec')

sdbusplus_current_path = 'com/nvidia/Secureboot'

generated_markdown += custom_target(
    'com/nvidia/Secureboot/Cec__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/Secureboot/Cec.interface.yaml'],
    output: ['Cec.md'],
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
        'com/nvidia/Secureboot/Cec',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

