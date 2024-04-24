# Ansible Role: GitLab Runner

Installs and applies base configuration to a GitLab Runner instance.

## Role Variables

## Usage

Install the collection locally, either via `requirements.yml`, or manually:

```bash
ansible-galaxy collection install dubzland.gitlab
```

Then apply the server role using the following playbook:

```yaml
---
- hosts: gitlab-runners

  collections:
    - dubzland.gitlab

  roles:
    - gitlab_runner
```

## License

GPLv3

## Author

- [Josh Williams](https://codingprime.com)
