# ansible-role-selinux

[![Build Status](https://travis-ci.org/linuxhq/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/linuxhq/ansible-role-selinux)

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

GPLv3

## Author Information

This role was created by [Taylor Kimball](http://www.linuxhq.org).
