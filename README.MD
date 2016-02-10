Installing Ansible on Ubuntu:

sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible


Running Ansible playbook:

ansible-playbook  -c local -i ./hosts install.yml

What to Expect:
This ansible playbook has two roles, one for installing oracle-jdk-7 and 
installs Cassandra-2.0.6 using apt-get repo.

This ansible playbook is tested for a single node cassandra node. 
