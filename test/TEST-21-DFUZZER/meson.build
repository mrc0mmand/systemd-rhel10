# SPDX-License-Identifier: LGPL-2.1-or-later

integration_tests += [
        integration_test_template + {
                'name' : fs.name(meson.current_source_dir()),
                'timeout' : 3600,
                'priority' : 50,
                'vm' : true,
                'cmdline' : integration_test_template['cmdline'] + ['systemd.log_level=info'],
        },
]
