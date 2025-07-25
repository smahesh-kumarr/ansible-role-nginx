# Ansible Role: nginx-role

This role installs and configures Nginx on target systems.

## Requirements
None

## Role Variables
No specific variables are required.

## Example Playbook

```yaml
- name: Install Nginx using role
  hosts: all
  roles:
    - nginx-role
