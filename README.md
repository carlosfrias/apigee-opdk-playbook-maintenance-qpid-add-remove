Apigee Maintenance Playbook - Add or Remove a Qpid Node
=======================================================

This playbook provides maintenance assistance for the tasks of 
adding or removing a qpid node. Two playbooks are provided. The first 
playbook called qpid-add.yml will register a qpid node with analytics. 
The second playbook called qpid-remove.yml will de-register a qpid node
with analytics. 


Usage Instructions
==================

These are ansible playbooks and require ansible.

1. Please install and configure ansible as indicated in [opdk-setup-ansible](../apigee-setup-ansible).
1. `ansible-galaxy -f -r requirements.yml`
1. `ansible-playbook -i <inventory file or folder> [qpid-add.yml | qpid-remove.yml]`

