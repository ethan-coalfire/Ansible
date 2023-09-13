# Ansible

## How to use

- Make a copy of coalfire-template.yml and name it to your vm name (eg. ethan-rapid7-vm.yml)
- remove any roles that you don't need.
- change the hostname variable to whatever you want your vm called
- set the remote_user to your username on your template
- run: ```ansible-playbook -i <your vm ip>, <your playbook name>``` (e.g. ```ansible-playbook -i 172.16.34.128, coalfire-template.yml```) 