# Ansible Collection - nicr9.firefox

## Installing This Collection

You can install this collection directly from ansible-galaxy:

```bash
$ ansible-galaxy collection install nicr9.firefox
```

## Installing Firefox

For a basic browser install, all that is needed is to write a playbook that calls the `browser` role:

```
- hosts: all
  collections:
  - nicr9.firefox
  roles:
  - browser
```
