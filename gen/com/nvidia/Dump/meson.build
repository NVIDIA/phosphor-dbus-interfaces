# Generated file; do not modify.
subdir('DebugInfo')
generated_others += custom_target(
    'com/nvidia/Dump/DebugInfo__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Dump/DebugInfo.interface.yaml',  ],
    output: [ 'DebugInfo.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Dump/DebugInfo',
    ],
)

subdir('Erase')
generated_others += custom_target(
    'com/nvidia/Dump/Erase__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Dump/Erase.interface.yaml',  ],
    output: [ 'Erase.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Dump/Erase',
    ],
)

subdir('LogInfo')
generated_others += custom_target(
    'com/nvidia/Dump/LogInfo__markdown'.underscorify(),
    input: [ '../../../../yaml/com/nvidia/Dump/LogInfo.interface.yaml',  ],
    output: [ 'LogInfo.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/nvidia/Dump/LogInfo',
    ],
)

