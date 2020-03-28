ansible-role-create_user
=========

Create some user

Requirements
------------

None

Role Variables
--------------

user_name - name of user

Dependencies
------------

None

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: ansible-role-create_user, usename: test_user }

License
-------

MIT

Author Information
------------------

tutunak.com
