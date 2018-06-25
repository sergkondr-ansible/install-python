install-python
=========

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
```

License
-------

WTFPL

Author Information
------------------

[Sergey Kondrashov](https://github.com/sergkondr)