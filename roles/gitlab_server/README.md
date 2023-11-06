# Ansible Role: GitLab Server

Installs and applies base configuration to a GitLab Devops server.

## Role Variables

## Usage

Install the collection locally, either via `requirements.yml`, or manually:
```bash
ansible-galaxy collection install dubzland.gitlab
```

Then apply the server role using the following playbook:
```yaml
---
- hosts: gitlab-servers

  collections:
    - dubzland.gitlab

  roles:
    - gitlab_server
```
## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
