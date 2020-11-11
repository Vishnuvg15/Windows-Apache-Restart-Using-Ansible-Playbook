# Windows-Apache-Restart-Using-Ansible-Playbook

This ansible playbook used to Restart Apache Tomcat in Windows Machines and delete the logs.

Playbook will first stop the tomcat services, the delete the logs and start tomact services.

Script is used to stop tomcat6 services. Neew to update service name as per your requirements.

Need to pass IP of remote system as extra variable. 

For example: ansible-playbook your-inventory-name ApacheRestart.yml -e '{"server":"remote-system-ip-address"}'
