# Elastic Artifacts Role

An Ansible role to manage and configure Elasticsearch repositories.

## Features
- Installs and configures Elasticsearch repositories.

## Requirements
- Ansible 2.9 or higher.
- Supported platforms:
  - **Debian-based systems:** Debian, Ubuntu.

## Role Variables
This role supports the following variables for customization:

### Defaults
Located in `playbook.yml`:
```yaml
# Example playbook
---
- name: Install Elasticsearch repositories
  hosts: all
  become: yes
  gather_facts: yes

  roles:
  - artifacts.elastic
```

## Dependencies
None.

## License
MIT

## Author Information
This role was created by Chakib. Contributions and feedback are welcome!