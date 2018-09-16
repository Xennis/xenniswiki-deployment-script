## XennisWiki Deployment Script

Ansible playbook to deploy the XennisWiki.

### Deploy XennisWiki

Configure the script

* Enter the IP of the server in the `[xenniswiki]` section of the `/etc/ansible/hosts` file

Run the playbook
```sh
ansible-playbook xenniswiki.yml
```
