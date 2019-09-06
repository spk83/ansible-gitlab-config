spk83.gitlab-config
===================

[![Build Status](https://travis-ci.org/spk83/ansible-gitlab-config.svg?branch=master)](https://travis-ci.org/spk83/ansible-gitlab-config)

Configure Gitlab CE with configurations in `gitlab.rb`

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
    - spk83.gitlab-config
```

License
-------

MIT

Author Information
------------------

Vishal Shah <vishal.shah@nyu.edu>
