#How To Run
==========
ansible-playbook vmhardening.yml -K

Role Name
=========

This role 'vmhardening' performs security hardening of the linux vm

Requirements
------------

Preferable Linux types are RedHat, CentOs , Fedora etc


Role Variables
--------------

1. This role has three Tasks defined 
	:-	os configuration updates
	:-	file permissions changes
	:-	ssh configuration updates


2. vars directory contains the details of different variables defined

3. Handlers directory contains the details of restart program that will be called in the tasks 



Dependencies
------------

All tasks are already defined in the sequence. 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: client
      roles:
         - vmhardening

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
