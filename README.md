## pycharm

[![CI](https://github.com/Oefenweb/ansible-pycharm/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-pycharm/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-pycharm-blue.svg)](https://galaxy.ansible.com/Oefenweb/pycharm)

Set up [PyCharm](https://www.jetbrains.com/pycharm/).

#### Requirements

None

#### Variables

* `pycharm_version` [default: `2021.3.1`]: Version to install
* `pycharm_edition` [default: `community`]: Edition to install (e.g. `community`)
* `pycharm_install_prefix` [default: `/opt`]: Install prefix
* `pycharm_download_url` [default: `http://download.jetbrains.com/python`]: Download url

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
