Ansible Role: munin-cron(pkg)
================================================================================
Install munin-cron from package(rpm)

- Install munin-cron
- Build and install nginx for WebUI

Requirements
--------------------------------------------------------------------------------
None

Role Variables
--------------------------------------------------------------------------------
These variables are defined in defaults/main.yml file.
```yaml
munin:
  cron:
    enabled: true
    workingdir: /usr/local/src
    conf:
      dbdir:   /var/lib/munin
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-munin-cron-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

