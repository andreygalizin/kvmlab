Role Name
=========
kvm_provision


Requirements
------------
Source of code:
## https://www.redhat.com/sysadmin/build-lab-quickly
## https://www.redhat.com/sysadmin/build-VM-fast-ansible

ansible-galaxy collection install community.libvirt


Role Variables
--------------
key "--selinux-relabel" is required only for Red Hat-based images or other images that have SELinux enabled


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

ansible-playbook -K kvm_provision.yaml # -K to initiate a sudo password request

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
