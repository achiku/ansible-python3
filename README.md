Python3
=======

Install Python3.

Requirements
------------

- None


Role Variables
--------------

```
py3_version: 3.5.1
py3_install_prefix: /usr/local
```


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: python3, py3_version: 3.5.1 }

License
-------

MIT
