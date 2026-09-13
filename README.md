# Ansible Role: adguard_docker

[![Ansible Lint](https://github.com/leberkaslabs/ansible-role-adguard_docker/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-adguard_docker/actions/workflows/ansible-lint.yml)

Setup AdGuard Home with Docker Compose.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.adguard_docker
```

## License

Copyright (c) 2026 Niclas Spreng
