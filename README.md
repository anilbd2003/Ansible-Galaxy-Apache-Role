Role Name apache
=========

Install and configure apache with custom document root, Virtual host (config file). 

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

defaults/main.yml     
    http_port: 80

vars/main.yml       
    http_host: domain1.local
    http_conf: domain1.local.conf
    


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - apache
