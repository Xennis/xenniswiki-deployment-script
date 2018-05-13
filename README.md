## XennisWiki Deployment Script

Ansible playbook to deploy the XennisWiki.

### Deploy XennisWiki

Configure the script

* Copy the file `env_vars/main.yml.sample` to `env_vars/xenniswiki.yml` and configure it (database password, etc.)
* Enter the IP of the server in the `[xenniswiki]` section of the `/etc/ansible/hosts` file

Run the playbook
```sh
ansible-playbook xenniswiki.yml
```
