Role Name
=========

Installs Nginx

Role Variables
--------------

server_name is what goes to Nginx server_name

Example Playbook
----------------

How to use role:

    - hosts: servers
      vars:
        - server_name: foo.com
      roles:
        - role: ysz.nginx

License
-------

BSD
