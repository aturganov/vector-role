Role Name
=========

Download and install Vector
Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

- vector_version

Dependencies
------------

Depend on NGINX installation

Example Playbook
----------------
- name: Add vector role
  hosts: vector-01
  roles: 
    - vector-role

License
-------

BSD

Author Information
------------------

Artem Turganov