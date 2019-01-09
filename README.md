# playBookForSQL,Tomcat,httpd
script will install tomcat, mysql ,httpd on the targeted server ,download a sample application and start the application on 2 nodes. it will also make sure to start mysql and httpd on server boot.


Copy the playbook to the targeted system on which Ansible is installed.
and run the below command.

ansible-playbook test.yml --ask-become-pass

The script is currently designed to run on Local host only.

