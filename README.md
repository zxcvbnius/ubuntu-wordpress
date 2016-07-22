Role Name
=========

Quick and easy wordpress installer.

Requirements
------------

Support Ansible 1.2 and above


Role Variables
--------------

In defaults/main.yml, you have to put your database name and mysql account and password for wordpress.

Dependencies
------------

none


Example Playbook
----------------

    - hosts: servers
      roles:
         - wordpress

License
-------

MIT
