panxatony.cs9project
=========

This role is used to implement CloudSystem infrastructure for new customer projects including:

* Creation of Project Group in FreeIPA
* Creation of Project member accounts in FreeIPA
* Creation of OpenStack Project in CloudSystem 9 Foundation
* Add FreeIPA Project member accounts to OpenStack Project
* Upload glance image
* Creation of OpenStack Project Tenant Network and Router
* Creation of OpenStack Project Security Group
* Creation of OpenStack 

Requirements
------------

CS9 Lab environment must be installed using panxatony.cs9lab Ansible playbook.

Role Variables
--------------

t.b.d.

Dependencies
------------

Following infrastructure must be implemented

* CloudSystem 9 must be installed
* CS9 Lab VMs must be deployed
* CloudSystem 9 must use FreeIPA as Directory Server

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: cs9project
      roles:
         - { role: panxatony.cs9project, project_name: dummy }

License
-------

BSD

Author Information
------------------

Lars Hunold
