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

You have to install MySQL + Apache + PHP packages first.
You can use the following ansible scripts to help you install these packages: 

 - [zxcvbnius.ubuntu-server](https://galaxy.ansible.com/zxcvbnius/ubuntu-server/)
 - [zxcvbnius.ubuntu-php](https://galaxy.ansible.com/zxcvbnius/ubuntu-php/)
 - [zxcvbnius.ubuntu-mysql](https://galaxy.ansible.com/zxcvbnius/ubuntu-mysql/)


Example Playbook
----------------

    - hosts: servers
      roles:
         - wordpress

License
-------

MIT
