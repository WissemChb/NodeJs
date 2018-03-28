Role Name
=========

Nodejs and NPM installation and configuration role.

Requirements
------------

no requirements

Role Variables
--------------

There is 3 vraibles:
  - rpm_base_url: contain RPM url for RedHat systems.
  - deb_base_url:  Contains deb url for Debian systems.
  - version: conatain the version of nodejs package by default is 8.X and can be overrided.

Dependencies
------------

No roles dependancies.

Example Playbook
----------------

This is an example of using this role:

    - hosts: all
      roles:
         - { role: WissemChb.nodejs, version: "_8.x" }

License
-------

BSD


