Role Name
=========
kvm_provision

Requirements
------------
A link to a source of the code:
## https://www.redhat.com/sysadmin/build-lab-quickly
## https://www.redhat.com/sysadmin/build-VM-fast-ansible

Role Variables
--------------
key "--selinux-relabel" is required only for Red Hat-based images or other images that have SELinux enabled, for this purpose "selinux" boolean variable is used

Dependencies
------------
libvirt
qemu-utils (qemu-img)
ansible-galaxy collection install community.libvirt

Example Playbook
----------------
ansible-playbook -K kvm_provision.yaml # -K to initiate a sudo password request
two samples .yaml are applied:
 1. fedora 37 
 2. ubuntu 22.04 (jammy)

 Use **virsh domifaddr <VM name>** to display IP address of VM

License
-------
BSD

Author Information
------------------
matrena.ca