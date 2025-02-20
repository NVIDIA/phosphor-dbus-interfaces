# Generated file; do not modify.
subdir('CurrentOperatingConfig')
subdir('RemoteDebug')
subdir('Reset')
subdir('ResetAsync')

sdbusplus_current_path = 'xyz/openbmc_project/Control/Processor'

generated_markdown += custom_target(
    'xyz/openbmc_project/Control/Processor/CurrentOperatingConfig__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/Control/Processor/CurrentOperatingConfig.interface.yaml',
    ],
    output: ['CurrentOperatingConfig.md'],
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
        'xyz/openbmc_project/Control/Processor/CurrentOperatingConfig',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Control/Processor/RemoteDebug__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/Control/Processor/RemoteDebug.interface.yaml',
    ],
    output: ['RemoteDebug.md'],
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
        'xyz/openbmc_project/Control/Processor/RemoteDebug',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Control/Processor/Reset__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/Control/Processor/Reset.interface.yaml',
    ],
    output: ['Reset.md'],
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
        'xyz/openbmc_project/Control/Processor/Reset',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Control/Processor/ResetAsync__markdown'.underscorify(),
    input: [
        '../../../../../yaml/xyz/openbmc_project/Control/Processor/ResetAsync.interface.yaml',
    ],
    output: ['ResetAsync.md'],
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
        'xyz/openbmc_project/Control/Processor/ResetAsync',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

