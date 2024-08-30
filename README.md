# ansible_wiki

The playbook installs the deploy wiki.js.

To use it, just set the hosts file in the configuration you want and start the playbook.

The default password from database is "12345", and login is "wiki", but you can change it in the roles/deploy_wiki/tasks
/main.yml file in line 57 and 63

If the error handlers psql occurs, then simply restart the playbook.

The working directory is located on the path /var/wiki
