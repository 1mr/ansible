Preprovision
====

Install common packages.

Requirements
-------------

This role requires ansible 1.4 or higher.

Role Variables
--------------

Dependencies
------------


Example Playbook
----------------

```
---
- hosts: all
  become: True
  roles:
    - { role: gh_1mr.ansible.fail2ban, tags: fail2ban }

```

License
-------

BSD
