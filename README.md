# ansible-role-selinux

[![Build Status](https://travis-ci.org/linuxhq/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/linuxhq/ansible-role-selinux)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-selinux-blue.svg?style=flat)](https://galaxy.ansible.com/linuxhq/selinux)
[![License](https://img.shields.io/badge/license-GPLv3-brightgreen.svg?style=flat)](COPYING)

RHEL/CentOS - Security-Enhanced Linux

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    selinux_conf: /etc/selinux/config
    selinux_policy: targeted
    selinux_state: enforcing

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - role: linuxhq.selinux
          selinux_state: disabled

## License

Copyright (C) 2018 Taylor Kimball <tkimball@linuxhq.org>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
