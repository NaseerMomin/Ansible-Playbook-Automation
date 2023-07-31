# Ansible-Playbook-Project

Create Ec2 Instance 4
Name : Ansible-Master (key pair Name Ansible-Master-key)
Name : Server-1       (key pair Name same 3 server Ansible-Master-key)
Name : Server-2       -----
Name : Server-3       -----

# Step 2

To Connect Ansible-Master Ec2 Instance ON Terminal

# Installation of Ansible Command
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt update
$ sudo apt install ansible
$ ansible-inventory --list -y  (option command)
$ sudo nano /etc/ansible/hosts

On Terminal Edit

# Step 3

[servers]
server1 ansible_host=<public ip>
server2 ansible_host=<public ip>

[prdserver]
server3 ansible_host=<public ip>

*Exit

On Terminal
# Step

$ Mkdir Keys (folder create)
$ cd Keys/

