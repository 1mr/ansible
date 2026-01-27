[![Build Status](https://travis-ci.com/1mr/ansible-role-skel.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-skel)

Skel
====

This role helps to configure user's profile.

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
        - { role: gh_1mr.ansible.skel, tags: skel }

License
-------

MIT
