grafana
==========

This playbook is used to install grafana automatically.

Role Variables
--------------

```yaml
grafana_version: GRAFANA_VERSION
```

Dependencies
------------

- pylabs.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: pylabs.grafana
  vars:
    grafana_version: "7.2.1"
```

License
-------

MIT

Author Information
------------------

William Wu <william@pylabs.org>
