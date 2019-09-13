Ansible Role: vSphere-Graphite
=========

Launches vSphere-Graphite docker container with persistent configuration

Configuration file is stored in /var/vsphere-graphite/config on the docker host and should reload itself when changes are made without needing to restart the container.

Requirements
------------

Docker

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: josephrpalmer.vsphere-graphite
         become:yes

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by Joseph Ryan-Palmer
