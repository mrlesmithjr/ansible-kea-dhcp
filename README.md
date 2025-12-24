# ansible-kea-dhcp

Ansible role to install/configure Kea DHCP

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-kea-dhcp/workflows/Molecule%20Test/badge.svg)

### Travis CI

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-kea-dhcp.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-kea-dhcp)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## SUSE/openSUSE Support

- **SLES 15/16**: Uses native SUSE repositories
- **openSUSE Tumbleweed**: Uses native openSUSE repositories
- **openSUSE Leap**: Not currently supported (Kea not in official repos)

**Note**: The `kea_dhcp_version` variable is not yet supported for SUSE family distributions. The role installs whatever version is available in the native repositories.

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [http://everythingshouldbevirtual.com](http://everythingshouldbevirtual.com)

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
