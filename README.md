## virtualbox

[![Build Status](https://travis-ci.org/orange888/ansible-virtualbox.svg?branch=master)](https://travis-ci.org/orange888/ansible-virtualbox) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtualbox-blue.svg)](https://galaxy.ansible.com/orange888/virtualbox/)

Set up [VirtualBox](https://www.virtualbox.org/) in Debian-like systems.

#### Requirements

None

#### Variables

* `virtualbox_version` [default: `6.0`]: Version to install
* `virtualbox_install`: [default: `[]`]: Additional packages to install (e.g. `dkms`)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - virtualbox
```

#### License

MIT

#### Author Information

Orange888

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-virtualbox/issues)!
