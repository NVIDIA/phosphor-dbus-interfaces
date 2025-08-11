# Generated file; do not modify.
subdir('BMCConfigManager')
subdir('GoldenImageUpdater')
subdir('Rshim')

sdbusplus_current_path = 'com/nvidia/BF'

generated_markdown += custom_target(
    'com/nvidia/BF/BMCConfigManager__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/BF/BMCConfigManager.interface.yaml'],
    output: ['BMCConfigManager.md'],
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
        'com/nvidia/BF/BMCConfigManager',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/BF/GoldenImageUpdater__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/BF/GoldenImageUpdater.interface.yaml'],
    output: ['GoldenImageUpdater.md'],
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
        'com/nvidia/BF/GoldenImageUpdater',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/BF/Rshim__markdown'.underscorify(),
    input: ['../../../../yaml/com/nvidia/BF/Rshim.interface.yaml'],
    output: ['Rshim.md'],
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
        'com/nvidia/BF/Rshim',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

