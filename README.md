mapr_drill
=========

Install apache drill from the MapR repo.

Requirements
------------

Role Variables
--------------

```
drill_version: 0.7.0
```

Dependencies
------------

Example Playbook
----------------

    - hosts: cluster
      roles:
         - { role: mapr_drill, drill_version: 0.7.0 }

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com
