# Generated file; do not modify.
subdir('ClearPCIeCounters')
subdir('LTSSMState')
subdir('PCIeClockMode')
subdir('PCIeECC')
subdir('PCIePortConfigurationInfo')
subdir('PCIeTransactionCounter')

sdbusplus_current_path = 'xyz/openbmc_project/PCIe'

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/ClearPCIeCounters__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/PCIe/ClearPCIeCounters.interface.yaml',
    ],
    output: ['ClearPCIeCounters.md'],
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
        'xyz/openbmc_project/PCIe/ClearPCIeCounters',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/LTSSMState__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/PCIe/LTSSMState.interface.yaml',
    ],
    output: ['LTSSMState.md'],
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
        'xyz/openbmc_project/PCIe/LTSSMState',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/PCIeClockMode__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/PCIe/PCIeClockMode.interface.yaml',
    ],
    output: ['PCIeClockMode.md'],
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
        'xyz/openbmc_project/PCIe/PCIeClockMode',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/PCIeECC__markdown'.underscorify(),
    input: ['../../../../yaml/xyz/openbmc_project/PCIe/PCIeECC.interface.yaml'],
    output: ['PCIeECC.md'],
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
        'xyz/openbmc_project/PCIe/PCIeECC',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/PCIePortConfigurationInfo__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/PCIe/PCIePortConfigurationInfo.interface.yaml',
    ],
    output: ['PCIePortConfigurationInfo.md'],
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
        'xyz/openbmc_project/PCIe/PCIePortConfigurationInfo',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/PCIe/PCIeTransactionCounter__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/PCIe/PCIeTransactionCounter.interface.yaml',
    ],
    output: ['PCIeTransactionCounter.md'],
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
        'xyz/openbmc_project/PCIe/PCIeTransactionCounter',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

