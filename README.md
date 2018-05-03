Role Name
=========

Installs Nginx

Writes working magento2 configuration to /etc/nginx/sites-available/default as an example

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
        - role: yakovzaytsev.nginx

License
-------

BSD
