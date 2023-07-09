Role Name: apache
=========

Install and configure apache with custom document root, Virtual host (config file). 

Role Variables
--------------

defaults/main.yml     

    http_port: 80

vars/main.yml  

    http_host: domain1.local
    
    http_conf: domain1.local.conf
    

Example Playbook
----------------

    - hosts: node
      roles:
         - apache
