Ansible tlsdate
===============

This is an Ansible role for use with tlsdate - https://github.com/ioerror/tlsdate


Requirements
------------

Works on Debian and Ubuntu.



Example Playbook using tlsdate
-----------------------------------------------

```yml
---
- hosts: servers
  roles:
    - role: ansible-tlsdate
      remove_ntp: yes

```

License
-------

MIT


Feature requests and bug-reports welcome!
-----------------------------------------

https://github.com/david415/ansible-tlsdate/issues
