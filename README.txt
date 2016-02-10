Installing Ansible on Ubuntu:

sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible

ansible-playbook  -c local -i ./hosts install.yml
