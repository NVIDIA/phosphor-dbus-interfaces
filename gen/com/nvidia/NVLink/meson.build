# Generated file; do not modify.
subdir('MNNVLinkTopology')
subdir('MemoryRowRemapping')
subdir('NVLinkDisableFuture')
subdir('NVLinkLED')
subdir('NVLinkMetrics')
subdir('NVLinkRefClock')
subdir('NvLinkTotalCount')
subdir('PortHealthMetrics')

sdbusplus_current_path = 'com/nvidia/NVLink'

generated_markdown += custom_target(
    'com/nvidia/NVLink/MNNVLinkTopology__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/NVLink/MNNVLinkTopology.interface.yaml',
    ],
    output: ['MNNVLinkTopology.md'],
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
        'com/nvidia/NVLink/MNNVLinkTopology',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/MemoryRowRemapping__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/NVLink/MemoryRowRemapping.interface.yaml',
    ],
    output: ['MemoryRowRemapping.md'],
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
        'com/nvidia/NVLink/MemoryRowRemapping',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/NVLinkDisableFuture__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/NVLink/NVLinkDisableFuture.interface.yaml',
    ],
    output: ['NVLinkDisableFuture.md'],
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
        'com/nvidia/NVLink/NVLinkDisableFuture',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/NVLinkLED__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/NVLink/NVLinkLED.interface.yaml'],
    output: ['NVLinkLED.md'],
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
        'com/nvidia/NVLink/NVLinkLED',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/NVLinkMetrics__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/NVLink/NVLinkMetrics.interface.yaml'],
    output: ['NVLinkMetrics.md'],
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
        'com/nvidia/NVLink/NVLinkMetrics',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/NVLinkRefClock__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/NVLink/NVLinkRefClock.interface.yaml'],
    output: ['NVLinkRefClock.md'],
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
        'com/nvidia/NVLink/NVLinkRefClock',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/NvLinkTotalCount__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/NVLink/NvLinkTotalCount.interface.yaml',
    ],
    output: ['NvLinkTotalCount.md'],
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
        'com/nvidia/NVLink/NvLinkTotalCount',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/NVLink/PortHealthMetrics__markdown'.underscorify(),
    input: [
        '../../../../yaml/com/nvidia/NVLink/PortHealthMetrics.interface.yaml',
    ],
    output: ['PortHealthMetrics.md'],
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
        'com/nvidia/NVLink/PortHealthMetrics',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

