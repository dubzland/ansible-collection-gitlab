# Ansible Collection: Gitlab

[![Gitlab pipeline status (self-hosted)](https://git.dubzland.com/dubzland/ansible-collections/gitlab/badges/main/pipeline.svg)](https://git.dubzland.com/dubzland/ansible-collections/gitlab/pipelines?scope=all&page=1&ref=main)
[![Ansible Galaxy](https://img.shields.io/badge/dynamic/json?style=flat&label=galaxy&prefix=v&url=https://galaxy.ansible.com/api/v3/collections/dubzland/gitlab/&query=highest_version.version)](https://galaxy.ansible.com/ui/repo/published/dubzland/gitlab/)
[![Liberapay patrons](https://img.shields.io/liberapay/patrons/jdubz)](https://liberapay.com/jdubz/donate)
[![Liberapay receiving](https://img.shields.io/liberapay/receives/jdubz)](https://liberapay.com/jdubz/donate)

Installs and configures various components of the Gitlab DevOps platform.

## Ansible version compatibility

This collection has been tested against following ansible-core versions:

- 2.14
- 2.15
- 2.16

Also tested against the current development version of `ansible-core`.

## Included content

### Roles

| Name                                           | Description                                     |
| ---------------------------------------------- | ----------------------------------------------- |
| [dubzland.gitlab.gitlab_common][gitlab_common] | Sets up the GitLab apt repository               |
| [dubzland.gitlab.gitlab_server][gitlab_server] | Install and configure the main GitLab server    |
| [dubzland.gitlab.gitlab_runner][gitlab_runner] | Install and configure the GitLab Runner service |

## Licensing

This collection is primarily licensed and distributed as a whole under the MIT license.

See [LICENSE](https://git.dubzland.com/dubzland/ansible-collections/gitlab/blob/main/LICENSE) for the full text.

## Author

- [Josh Williams](https://codingprime.com)

[gitlab_common]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_common_role.html
[gitlab_server]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_server_role.html
[gitlab_runner]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_runner_role.html
