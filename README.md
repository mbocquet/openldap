# OpenLDAP

Ansible role to install and configure OpenLDAP server.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this roles as submodule of an existing GIT repository

`git submodule add https://github.com/mbocquet/openldap.git roles/openldap`

## Example Playbook

    - hosts: servers
      roles:
         - openldap


    - hosts: servers
      roles:
         - { role: openldap, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
