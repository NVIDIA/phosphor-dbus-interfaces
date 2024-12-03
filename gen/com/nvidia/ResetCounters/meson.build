# Generated file; do not modify.
subdir('ResetCounterMetrics')
generated_others += custom_target(
    'com/nvidia/ResetCounters/ResetCounterMetrics__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/ResetCounters/ResetCounterMetrics.interface.yaml',  ],
    output: [ 'ResetCounterMetrics.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/ResetCounters/ResetCounterMetrics',
    ],
)

