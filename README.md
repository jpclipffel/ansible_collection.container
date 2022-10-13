# Ansible Collection - jpclipffel.container

Ansible containers management: OCI, CRI, etc.

## Roles

### `config`

* Manages the system-wide container configuration
* Documentation: [link](roles/config/README.md)

> Not suitable for Containerd which uses its own configuration: see role `jpclipffel.container.containerd`

### `containerd`

* Installs and configure `containerd`
* Documentation: [link](roles/containerd/README.md)

### `docker`

* Installs and configure `docker-ce` and `docker-compose`
* Documentation: [link](roles/docker/README.md)
