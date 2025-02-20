# Generated file; do not modify.
subdir('Signing')
subdir('SigningConfig')

sdbusplus_current_path = 'xyz/openbmc_project/Security'

generated_markdown += custom_target(
    'xyz/openbmc_project/Security/Signing__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Security/Signing.interface.yaml',
    ],
    output: ['Signing.md'],
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
        'xyz/openbmc_project/Security/Signing',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Security/SigningConfig__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Security/SigningConfig.interface.yaml',
    ],
    output: ['SigningConfig.md'],
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
        'xyz/openbmc_project/Security/SigningConfig',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

