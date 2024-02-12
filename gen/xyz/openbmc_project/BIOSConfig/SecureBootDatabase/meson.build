# Generated file; do not modify.
subdir('AddSignature')
generated_others += custom_target(
    'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature.interface.yaml',  ],
    output: [ 'AddSignature.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/AddSignature',
    ],
)

subdir('Signature')
generated_others += custom_target(
    'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature.interface.yaml',  ],
    output: [ 'Signature.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/BIOSConfig/SecureBootDatabase/Signature',
    ],
)

