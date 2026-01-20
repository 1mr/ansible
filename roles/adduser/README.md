# adduser

This role helps to manage local users.

## Requirements

This role requires ansible 2.5 or higher.

## Role Variables

`adduser`, default:

```yaml
adduser_user:
  - name: debian
    state: absent
```

Example:

```yaml
    adduser_user:
        - name: alice
        - name: bob
```

## Dependencies

None

## Example Playbook

```yaml
    - hosts: servers
      roles:
         - { role: gh_1mr.ansible.adduser, tags: adduser }
```

## License

MIT
