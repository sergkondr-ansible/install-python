install-python
=========
[![Build Status](https://travis-ci.com/sergkondr-ansible/install-python.svg?branch=master)](https://travis-ci.com/sergkondr-ansible/install-python)
[![Ansible Role](https://img.shields.io/ansible/role/d/26553.svg)](https://galaxy.ansible.com/sergkondr-ansible/install-python/)

The role install python using `raw` module, so you can use it to prepare host for using Ansible.

Example Playbook
----------------

```
  - name: Ensure python is installed
    hosts: all
    gather_facts: no
    become: yes
    roles:
      - install-python

  - name: Play other roles
    hosts: all
    gather_facts: yes
    become: yes
    roles:
      - other-role
```

License
-------

WTFPL

Author Information
------------------

[Sergey Kondrashov](https://github.com/sergkondr)
