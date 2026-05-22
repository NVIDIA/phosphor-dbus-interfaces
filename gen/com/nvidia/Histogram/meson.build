# Generated file; do not modify.
subdir('BucketInfo')
subdir('Decorator')

sdbusplus_current_path = 'com/nvidia/Histogram'

generated_markdown += custom_target(
    'com/nvidia/Histogram/BucketInfo__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/Histogram/BucketInfo.interface.yaml',
    ],
    output: ['BucketInfo.md'],
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
        'com/nvidia/Histogram/BucketInfo',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

