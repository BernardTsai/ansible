CloudManager
============

The CloudManager role deploys the required ansible infrastructure to execute
ansible playbooks which are capable of managing the lifecycle of virtual
infrastructures (including specific contrail related network resources).

Requirements
------------

The role deploys ansible and the python-contrail-client and requires python3
to be installed. Currently the role has been developed for ubuntu OS.

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

Simple example playbook:

    - hosts: servers
      roles:
         - { role: CloudManager }

License
-------

BSD

Author Information
------------------

Bernard Tsai (email: bernard@tsai.eu)
