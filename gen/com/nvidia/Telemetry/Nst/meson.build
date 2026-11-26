# Generated file; do not modify.
subdir('Actuation')
subdir('Ingress')
subdir('Participant')
subdir('Telemetry')

sdbusplus_current_path = 'com/nvidia/Telemetry/Nst'

generated_markdown += custom_target(
    'com/nvidia/Telemetry/Nst/Actuation__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Telemetry/Nst/Actuation.interface.yaml',
    ],
    output: ['Actuation.md'],
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
        'com/nvidia/Telemetry/Nst/Actuation',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Telemetry/Nst/Ingress__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Telemetry/Nst/Ingress.interface.yaml',
    ],
    output: ['Ingress.md'],
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
        'com/nvidia/Telemetry/Nst/Ingress',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Telemetry/Nst/Participant__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Telemetry/Nst/Participant.interface.yaml',
    ],
    output: ['Participant.md'],
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
        'com/nvidia/Telemetry/Nst/Participant',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/nvidia/Telemetry/Nst/Telemetry__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/nvidia/Telemetry/Nst/Telemetry.interface.yaml',
    ],
    output: ['Telemetry.md'],
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
        'com/nvidia/Telemetry/Nst/Telemetry',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

