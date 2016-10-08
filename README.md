wrboyce.bootstrap
=================

[![Build Status](https://travis-ci.org/wrboyce/ansible-bootstrap.svg)](https://travis-ci.org/wrboyce/ansible-bootstrap)

Bootstrap ansible on Debian/Ubuntu based systems.

Role Variables
--------------

`ansible_deploy_key` holds the authorized ssh key for the ansible user.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: wrboyce.bootstrap
           ansible_deploy_key: "ssh-ed25519 ... user@host"

License
-------

Apache 2.0