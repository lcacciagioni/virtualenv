Virtaulenv
=========

This role will install virtualenv globally on the designated systems. The virtualenv installed version will be the official supported by the distribution in case.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

You just simply need to include this role in your playbook, no vars needs to be declared.

```
	- hosts: all
		roles:
			 - lcacciagioni.virtualenv
```
License
-------

GPLv3

Author Information
------------------

Leandro David Cacciagioni - < leandro.21.2008@gmail.com >
