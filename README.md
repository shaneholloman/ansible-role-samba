# Ansible Role: Samba (SMB)

[![CI](https://github.com/shaneholloman/ansible-role-samba/actions/workflows/ci.yml/badge.svg)](https://github.com/shaneholloman/ansible-role-samba/actions/workflows/ci.yml)

Installs Samba client and server for RHEL/CentOS.

## Requirements

Samba requires ports 137, 138, 139, 445 to be open to function properly. For easy firewall configuration, you can use the `shaneholloman.firewall` role.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - shaneholloman.samba

## License

MIT / BSD

## Author Information

This role was created in 2023
