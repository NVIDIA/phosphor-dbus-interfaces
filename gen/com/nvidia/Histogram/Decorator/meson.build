# Generated file; do not modify.
subdir('Format')
subdir('SupportedHistogram')

sdbusplus_current_path = 'com/nvidia/Histogram/Decorator'

generated_markdown += custom_target(
    'com/nvidia/Histogram/Decorator/Format__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Histogram/Decorator/Format.interface.yaml',
    ],
    output: ['Format.md'],
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
        'com/nvidia/Histogram/Decorator/Format',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Histogram/Decorator/SupportedHistogram__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Histogram/Decorator/SupportedHistogram.interface.yaml',
    ],
    output: ['SupportedHistogram.md'],
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
        'com/nvidia/Histogram/Decorator/SupportedHistogram',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

