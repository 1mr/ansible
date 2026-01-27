# timezone

[![Build Status](https://travis-ci.com/1mr/ansible-role-timezone.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-timezone)

Configures timezone on Debian servers.

## Requirements

None.

## Role Variables

`timezone` - tz database name (default: America/New_York)

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
         - { role: gh_1mr.ansible.timzeone, tag: timezone }

## License

MIT
