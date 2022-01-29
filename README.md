# Ansible-Change-Dns
Changing DNS with Ansible
This version currently supported for:
	1- Ubuntu 18.04 and later
	2- Ubuntu 16.04 and erlier

# Ansible Playbook Command
ansible-playbook change-dns.yml -i <inventory_file> --extra-vars "dns1= dns2="


# Example 1 For Ubuntu 18.04:
ansible-playbook change-dns.yml -l <ubuntu_hostname> -u <user_name> -kK --extra-vars "dns1=8.8.8.8 dns2=1.1.1.1"


# Example 1 For Ubuntu 16.04:
ansible-playbook change-dns.yml -l <ubuntu_hostname> -u <user_name> -kK --extra-vars "server1=8.8.8.8 server2=1.1.1.1"


