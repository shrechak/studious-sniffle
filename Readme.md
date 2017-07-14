Ansible tutorial
================

#### Prerequisites for Ansible

- [Ansible](http://docs.ansible.com/ansible/intro_installation.html)
- [Vagrant](https://www.vagrantup.com/docs/installation/) - if you want to run your server on a virtual machine

This project also includes a sample Vagrantfile for a Ubuntu 12.04 box

#### Inventory

- Spin up your virtual machines using
	`vagrant up`
	All the ansible commands you run should now have `-i inventory_files/` to point to the appropriate virtual machine you have set up.

- If you would like to run the commands on your local machine instead use `-i "localhost," -c local`


#### Structure of project.

Following [this layout](http://docs.ansible.com/ansible/playbooks_best_practices.html#alternative-directory-layout)

- Basic playbook under `/basics`
- Have defined a basic playbook to install apache server under `/playbooks`

