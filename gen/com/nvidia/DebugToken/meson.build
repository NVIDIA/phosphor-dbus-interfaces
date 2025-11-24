# Generated file; do not modify.
subdir('Action')
subdir('Aggregation')
subdir('ErasePolicy')
subdir('Status')

sdbusplus_current_path = 'com/nvidia/DebugToken'

generated_sources += custom_target(
    'com/nvidia/DebugToken__cpp'.underscorify(),
    input: ['../../../../yaml/com/nvidia/DebugToken.interface.yaml'],
    output: [
        'common.hpp',
        'server.hpp',
        'server.cpp',
        'aserver.hpp',
        'client.hpp',
    ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'cpp',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/DebugToken',
    ],
    install: should_generate_cpp,
    install_dir: [
        get_option('includedir') / sdbusplus_current_path,
        get_option('includedir') / sdbusplus_current_path,
        false,
        get_option('includedir') / sdbusplus_current_path,
        get_option('includedir') / sdbusplus_current_path,
    ],
    build_by_default: should_generate_cpp,
)

generated_markdown += custom_target(
    'com/nvidia/DebugToken/Action__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/DebugToken/Action.interface.yaml'],
    output: ['Action.md'],
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
        'com/nvidia/DebugToken/Action',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/DebugToken/Aggregation__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/DebugToken/Aggregation.interface.yaml'],
    output: ['Aggregation.md'],
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
        'com/nvidia/DebugToken/Aggregation',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/DebugToken/ErasePolicy__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/DebugToken/ErasePolicy.interface.yaml'],
    output: ['ErasePolicy.md'],
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
        'com/nvidia/DebugToken/ErasePolicy',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/DebugToken/Status__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/DebugToken/Status.interface.yaml'],
    output: ['Status.md'],
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
        'com/nvidia/DebugToken/Status',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

