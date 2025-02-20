# Generated file; do not modify.
subdir('IBPort')
subdir('LanError')
subdir('PortMetricsOem1')
subdir('PortMetricsOem2')
subdir('PortMetricsOem3')

sdbusplus_current_path = 'xyz/openbmc_project/Metrics'

generated_markdown += custom_target(
    'xyz/openbmc_project/Metrics/IBPort__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Metrics/IBPort.interface.yaml',
    ],
    output: ['IBPort.md'],
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
        'xyz/openbmc_project/Metrics/IBPort',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Metrics/LanError__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Metrics/LanError.interface.yaml',
    ],
    output: ['LanError.md'],
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
        'xyz/openbmc_project/Metrics/LanError',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Metrics/PortMetricsOem1__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Metrics/PortMetricsOem1.interface.yaml',
    ],
    output: ['PortMetricsOem1.md'],
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
        'xyz/openbmc_project/Metrics/PortMetricsOem1',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Metrics/PortMetricsOem2__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Metrics/PortMetricsOem2.interface.yaml',
    ],
    output: ['PortMetricsOem2.md'],
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
        'xyz/openbmc_project/Metrics/PortMetricsOem2',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'xyz/openbmc_project/Metrics/PortMetricsOem3__markdown'.underscorify(),
    input: [
        '../../../../yaml/xyz/openbmc_project/Metrics/PortMetricsOem3.interface.yaml',
    ],
    output: ['PortMetricsOem3.md'],
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
        'xyz/openbmc_project/Metrics/PortMetricsOem3',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

