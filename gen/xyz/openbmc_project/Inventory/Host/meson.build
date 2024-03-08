# Generated file; do not modify.
subdir('BfFruInfo')
generated_others += custom_target(
    'xyz/openbmc_project/Inventory/Host/BfFruInfo__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Inventory/Host/BfFruInfo.interface.yaml',  ],
    output: [ 'BfFruInfo.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Inventory/Host/BfFruInfo',
    ],
)

