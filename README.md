Role Name
=========

Simple Pritunl VPN setup with Ansible.


Requirements
------------

This role expects CentOS 7 operating system.


Role Variables
--------------

All variables are defined under `vars/main.yml`.


Dependencies
------------

Do dependencies.


Example Playbook
----------------

Playbook example:

    - hosts: vpn
      sudo: yes
      roles:
        - { role: include.pritunl }

License
-------

BSD

Author Information
------------------

Francisco Cabrita: <francisco.cabrita@gmail.com>
