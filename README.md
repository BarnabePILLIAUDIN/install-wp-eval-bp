# Install WordPress with Ansible

This role has only been testes on ubuntu containers.

## Exemple playbook

```yaml
- name: Install WP with role
  hosts: all
  become: true
  roles:
  - eval-ansible-barnabepilliaudin
```
