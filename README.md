## XennisWiki Deployment Script

[![Build Status](https://github.com/Xennis/xenniswiki-deployment-script/actions/workflows/check.yml/badge.svg)](https://github.com/Xennis/xenniswiki-deployment-script/actions/workflows/check.yml)

Ansible playbook to deploy the XennisWiki.

### Deployment

Prerequisite: The host is set, e.g. `/etc/ansible/hosts`

```
[xenniswiki]
example.org
```

Run the playbook
```shell
ansible-playbook xenniswiki.yml
```
