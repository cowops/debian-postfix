Debian-Postfix
==============

Postfix is Wietse Venema's mail server that started life at IBM research as an alternative to the widely-used Sendmail program.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-postfix }

Tasks
-----

  - Install [postfix](http://www.postfix.org/)
  - Install [opendkim](http://www.opendkim.org/)
  

License
-------

BSD