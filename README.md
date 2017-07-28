[![CircleCI](https://circleci.com/gh/fouadsemaan/ansible-jupyter-supervisord.svg?style=svg)](https://circleci.com/gh/fouadsemaan/ansible-jupyter-supervisord)
fouadsemaan.jupyter-supervisord
=========

Installs a supervisord program specification for a Jupyter notebook

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.supervisord
    - andrewrothstein.jupyter-supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
