# sysctl

This role helps to configure sysctl.

## Requirements

This role requires ansible 2.5 or higher.

## Role Variables

The variables that can be passed to this role and a brief description about them are as follows:

    sysctl_settings:


## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - { role: gh_1mr.ansible.sysctl, tags: sysctl }

## License

MIT
