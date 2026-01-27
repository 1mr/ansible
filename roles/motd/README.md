[![Build Status](https://travis-ci.com/1mr/ansible-role-motd.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-motd)

Motd
====

This role helps to configure motd.

Requirements
------------

This role requires ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: gh_1mr.ansible.motd, tags: motd }

License
-------

MIT
