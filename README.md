andrewrothstein.prometheus
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-prometheus.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-prometheus)

Installs [Prometheus](https://prometheus.io).

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
    - andrewrothstein.prometheus
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
