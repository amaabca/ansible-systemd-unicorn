Role Name
=========

Adds systemd configuration for a unicorn process. Does not install unicorn as it assumes the application bears this responsibility.

Requirements
------------

No requirements.

Role Variables
--------------

ansible_systemd_unicorn_app_path: the base application path
ansible_systemd_unicorn_rack_env: either none, development or deployment
ansible_systemd_unicorn_user: the owner of the unicorn process


Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: amaabca.ansible-systemd-unicorn }

License
-------

MIT

Author Information
------------------

https://github.com/amaabca/ansible-systemd-unicorn
