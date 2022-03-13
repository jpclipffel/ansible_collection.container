# Ansible Role - jpclipffel.container.containerd

Manages `containerd`.

## Tags

| Tag        | Description                                       |
|------------|---------------------------------------------------|
| `setup`    | Install and configure `containerd`                |
| `teardown` | Removes `containerd` configuration and disable it |
| `remove`   | Same as `teardown` + uninstall `containerd`       |

## Variables

Variables are documented in `defaults/main.yml`.

Important ones:

| Variable                                     | Type   | Default | Required | Description                                                                |
|----------------------------------------------|--------|---------|----------|----------------------------------------------------------------------------|
| `jpclipffel_container_containerd_configonly` | `bool` | `false` | No       | Switch to `true` to only **configure** `containerd` (usefull for MicroK8s) |
