Ansible: APT Autoupdate Role
============================

Ansible role to activate automated package updates via `apt`.
This role is for Debian and Ubuntu only.

Example Playbook
----------------

Example of how to configure and use the role:

```yaml
- hosts: servers
  become: true
  roles:
    - role: lkiesow.apt_autoupdate
```
