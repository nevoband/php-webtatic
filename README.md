Role Name
=========

Role to install webtatic repo and PHP72.
Copied a bunch of pieces from https://github.com/geerlingguy/ansible-role-php to create a version that is simpler for my particular need.

Requirements
------------


Role Variables
--------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: php-webtatic }

License
-------

MIT
