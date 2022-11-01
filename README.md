Ansible Role Restic
=========

Installs Restic backup utility into /usr/local/bin
https://github.com/restic/restic/releases


Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: ansible-role-restic, restic_version: '0.14.0' }
```
