# Generated file; do not modify.
subdir('Format')
generated_others += custom_target(
    'com/nvidia/Histogram/Decorator/Format__markdown'.underscorify(),
    input: [ '../../../../../yaml/com/nvidia/Histogram/Decorator/Format.interface.yaml',  ],
    output: [ 'Format.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'com/nvidia/Histogram/Decorator/Format',
    ],
)

subdir('SupportedHistogram')
generated_others += custom_target(
    'com/nvidia/Histogram/Decorator/SupportedHistogram__markdown'.underscorify(),
    input: [ '../../../../../yaml/com/nvidia/Histogram/Decorator/SupportedHistogram.interface.yaml',  ],
    output: [ 'SupportedHistogram.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'com/nvidia/Histogram/Decorator/SupportedHistogram',
    ],
)

