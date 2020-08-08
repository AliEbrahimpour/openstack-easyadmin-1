# openstack-easyadmin
Ansible playbooks and roles to automate openstack administrative tasks 

# Instalation
1. install python3-openstacksdk:
   # apt install python3-openstacksdk

add "ansible_python_interpreter=/usr/bin/python3" to group_vars file, or run ansible playbooks like this:
   # ansible-playbook os_identity-domain.yml  -e "ansible_python_interpreter=/usr/bin/python3"
