Role Name
=========

A role for installing KIBANA.

Requirements
------------

For ALL Linux Distro (*.tar.gz)

Role Variables
--------------
You can add your own *.tar.gz files with another version amd add var in ./vars/main.yml
Then change `kb_distr_name: "{{ kibana[xxx] }}"`  in ./defaults/main.yml

Example Playbook
----------------


    - hosts: all
      roles:
         - { role: kibana-role }

License
-------

BSD

Author Information
------------------

@rokovi 
