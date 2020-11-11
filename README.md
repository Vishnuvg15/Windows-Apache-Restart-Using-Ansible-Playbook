# Windows-Apache-Restart-Using-Ansible-Playbook

This ansible playbook used to Restart Apache Tomcat in Windows Machines and delete the logs.

Need to pass extra IP of remote system as extra variable. 

For example: ansible-playbook your-inventory-name ApacheRestart.yml -e '{"server":"remote-system-ip-address"}'
