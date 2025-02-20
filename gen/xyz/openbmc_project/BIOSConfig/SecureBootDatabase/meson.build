# Generated file; do not modify.
subdir('AddSignature')
subdir('Signature')

sdbusplus_current_path = 'xyz/openbmc_project/BIOSConfig/SecureBootDatabase'

generated_markdown += custom_target(
    'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature.interface.yaml',
    ],
    output: ['AddSignature.md'],
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
        'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature.interface.yaml',
    ],
    output: ['Signature.md'],
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
        'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

