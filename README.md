## XennisWiki Deployment Script

Ansible playbook to deploy the XennisWiki.

### Deployment

Configure the script

* Python 2 as interpreter is required. For the case Python 3 is the default, set the `ansible_python_interpreter` in the Ansible hosts file to Python 2.

Run the playbook
```sh
ansible-playbook <playbook file>
```
