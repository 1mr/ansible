[![Build Status](https://travis-ci.com/1mr/ansible-role-hostname.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-hostname)

Hostname
========

This role helps to set hostname.

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
        - { role: gh_1mr.ansible.hostname, tags: hostname }

License
-------

MIT
