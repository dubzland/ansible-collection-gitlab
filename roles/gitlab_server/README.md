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

  tasks:
    - name: Schedule GitLab backups
      ansible.builtin.cron:
        name: GitLab application backup
        weekday: "*"
        minute: "0"
        hour: "2"
        user: root
        job: "CRON=1 /opt/gitlab/bin/gitlab-backup create"
        cron_file: gitlab-backup
    - name: Schedule GitLab Registry garbage collection
      ansible.builtin.cron:
        name: GitLab Registry garbage collection
        weekday: "*"
        minute: "0"
        hour: "4"
        user: root
        job: "gitlab-ctl registry-garbage-collect -m"
        cron_file: gitlab-registry-gc
```

## License

GPLv3

## Author

- [Josh Williams](https://codingprime.com)
