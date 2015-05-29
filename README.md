drone
=====

Installs and configures Drone

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

- kbrebanov.docker

Example Playbook
----------------

Install Drone
```
- hosts: all
  roles:
    - { role: kbrebanov.drone }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
