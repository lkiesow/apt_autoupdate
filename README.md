Ansible: APT Autoupdate Role
============================

Ansible role to activate automated package updates via `apt`.
This role is for Debian and Ubuntu only.

Role Options
------------

While the defaults set by this role should be reasonable in most cases,
you can control several aspects of this role via ansible variables.
For a list of options and their description, take a look at [the defaults](defaults/main.yml).

Example Playbook
----------------

Example of how to configure and use the role:

```yaml
- hosts: servers
  become: true
  roles:
    - role: lkiesow.apt_autoupdate
```
