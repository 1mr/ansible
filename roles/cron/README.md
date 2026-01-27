# cron

This role helps to configure cron.d files.

## Requirements

This role requires ansible 2.5 or higher.

## Role Variables

* `cron` (default: `[]`)

```yaml
    cron:
      - file: test
        state: present
        record:
          - name: hello
            user: www-data
            minute: "*/5"
            job: echo 'hello'
            state: present
```

## Dependencies

None

## Example Playbook

```yaml
    - hosts: servers
      roles:
         - { role: gh_1mr.ansible.cron, tags: cron }
```

## License

MIT
