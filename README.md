# ansible-vcenter

This is an Ansible Project for deploying a Ubunut Bionic Server OVA-Template on the VMware vCenter.
The OVA-Image will be donwloaded automatically.

* Deploying Ubuntu Bionic Server on the vCenter

## Required Variables

Path: roles/vcenter/defaults/main.yml

* vcenter_hostname:
* vcenter_datacenter:
* vcenter_cluster:
* vcenter_datastore:
* vcenter_folder:
* vcenter_network:

Path: roles/vcenter/vars/main.yml

* vcenter_username:
* vcenter_password:

for security reasons this file can be encrypted using ansible-vault. then a vault-pass.txt file must be provided oder the password must be specified in the ansible command! 
