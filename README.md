Role Name
=========

A brief description of the role goes here.

Requirements
------------

This role is created just for centos 7.

Role Variables
--------------

There's no mandatory variable needed. If you need it you can specify where is located the node.js home.

- node_home : Home folder for nodejs.

Dependencies
------------

This role depens on devops_cmp.ansible_nodejs.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: devops_cmp.ansible_nodejs}
```
License
-------

MIT
