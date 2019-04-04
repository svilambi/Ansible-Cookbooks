# Ansible-Cookbooks
Ansible Cookbooks are written in yml

# Installation of Ansible
yum install ansible -y

# Add Clients in below location
gedit /etc/ansible/hosts

# format must be as below
[ansible_client]
192.168.2.11 ansible_ssh_user=root ansible_ssh_pass=password

# To check syntax of the yml file below is the command
ansible-playbook first.yml --syntax-check

# To Push to clients below is the command
ansible-playbook first.yml
