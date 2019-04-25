[![Build Status](https://travis-ci.org/kleinstuff/ansible-role-newrelic-phpagent.png)](https://travis-ci.org/kleinstuff/ansible-role-newrelic-phpagent)

kleinstuff.ansible_role_newrelic_phpagent
=========

Install NewRelic PHP Agent on RHEL/CentOS
Currently supports:
* CentOS/RHEL 7

Requirements
------------

No extra requirements needed.

Role Variables
--------------

role_newrelic_licence: REQUIRED
role_newrelic_appname: REQUIRED


Dependencies
------------

No deps.

Example Playbook
----------------

```
    - hosts: servers
      roles:
        - { role: kleinstuff.ansible_role_newrelic_phpagent }
      vars:
        - role_newrelic_licence: "XXXXXXX"
        - role_newrelic_appname: "XXXXXXX"
```
License
-------

GPL

Author Information
------------------

If you want to suggest changes or request new features, please feel free to create a issue or send a pull request.
