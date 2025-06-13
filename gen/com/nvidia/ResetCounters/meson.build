# Generated file; do not modify.
subdir('ResetCounterMetrics')
subdir('ResetCounterMetricsSupported')

sdbusplus_current_path = 'com/nvidia/ResetCounters'

generated_markdown += custom_target(
    'com/nvidia/ResetCounters/ResetCounterMetrics__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/ResetCounters/ResetCounterMetrics.interface.yaml',
    ],
    output: ['ResetCounterMetrics.md'],
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
        'com/nvidia/ResetCounters/ResetCounterMetrics',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/ResetCounters/ResetCounterMetricsSupported__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/ResetCounters/ResetCounterMetricsSupported.interface.yaml',
    ],
    output: ['ResetCounterMetricsSupported.md'],
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
        'com/nvidia/ResetCounters/ResetCounterMetricsSupported',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

