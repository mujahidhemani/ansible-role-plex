ansible-role-plex
=========

An Ansible role to install Plex Media Server on CentOS/Red Hat Enterprise Linux

Requirements
------------

CentOS/RHEL 6, 7

Role Variables
--------------

Vars:

- plex_baseurl - Plex repo url
- plex_gpgurl - Plex repo gpgkey url

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mujahidhemani.plex }

License
-------

GPLv3

Author Information
------------------

Author: Mujahid Hemani
