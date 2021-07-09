pbos.barbican
==============

Ansible role to install and setup Barbican for OpenStack 

Requirements
------------

This role requires Ansible 2.11 or higher.

This role supports:

  - Debian 11 (bullseye)

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: servers
    roles:
      - { role: pbos.barbican, tags: barbican }

Barbican is installed on the node in barbican inventory group:

    [barbican]
    host-1
    host-2
    host-3

License
-------

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

  - Heechul Kim @iOrchard
      - <https://github.com/iorchard>

