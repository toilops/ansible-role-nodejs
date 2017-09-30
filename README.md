Ansible Role Nodejs
=========

Ansible role to install and configure epel-release, nodejs and npm.

Requirements
------------

Currently this role only supports Redhat systems. (EL - 6,7)

Example Playbook
----------------

Simply include this role into your playbook:
``` 
    - hosts: servers
      tasks:
        - include_role:
            name: BondAnthony.ansible-role-nodejs
```
License
-------

MIT

Author Information
------------------

Find me on Github [@BondAnthony]((https://github.com/BondAnthony)
