# Generated file; do not modify.
subdir('Nst')

sdbusplus_current_path = 'com/nvidia/Telemetry'

generated_markdown += custom_target(
    'com/nvidia/Telemetry/Nst__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/Telemetry/Nst.interface.yaml',
    ],
    output: ['Nst.md'],
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
        'com/nvidia/Telemetry/Nst',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

