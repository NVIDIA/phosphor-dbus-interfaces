# Generated file; do not modify.
subdir('GoldenImageUpdater')
generated_others += custom_target(
    'com/nvidia/BF/GoldenImageUpdater__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/BF/GoldenImageUpdater.interface.yaml',  ],
    output: [ 'GoldenImageUpdater.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/BF/GoldenImageUpdater',
    ],
)

