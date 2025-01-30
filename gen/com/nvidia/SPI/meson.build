# Generated file; do not modify.
subdir('SPI')
generated_others += custom_target(
    'com/nvidia/SPI/SPI__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/SPI/SPI.interface.yaml',  ],
    output: [ 'SPI.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/SPI/SPI',
    ],
)

