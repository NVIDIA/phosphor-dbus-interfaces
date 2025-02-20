# Generated file; do not modify.
subdir('ErrorInjection')
subdir('ErrorInjectionCapability')

sdbusplus_current_path = 'com/nvidia/ErrorInjection'

generated_markdown += custom_target(
    'com/nvidia/ErrorInjection/ErrorInjection__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/ErrorInjection/ErrorInjection.interface.yaml',
    ],
    output: ['ErrorInjection.md'],
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
        'com/nvidia/ErrorInjection/ErrorInjection',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/ErrorInjection/ErrorInjectionCapability__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/ErrorInjection/ErrorInjectionCapability.interface.yaml',
    ],
    output: ['ErrorInjectionCapability.md'],
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
        'com/nvidia/ErrorInjection/ErrorInjectionCapability',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

