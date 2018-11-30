## pycharm

[![Build Status](https://travis-ci.org/Oefenweb/ansible-pycharm.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-pycharm) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-pycharm-blue.svg)](https://galaxy.ansible.com/Oefenweb/pycharm)

Set up [PyCharm](https://www.jetbrains.com/pycharm/).

#### Requirements

None

#### Variables

* `pycharm_version` [default: `latest`]: Version to install (e.g. `4.5.5` or `latest`)
* `pycharm_edition` [default: `professional`]: Edition to install (e.g. `community`)
* `pycharm_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - pycharm
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-pycharm/issues)!
