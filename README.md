# Ansible Collection: Gitlab

[![Gitlab pipeline][pipeline-badge]][pipeline-url]
[![Gitlab coverage][coverage-badge]][coverage-url]
[![Galaxy Version][galaxy-badge]][galaxy-url]
[![license][license-badge]][license-url]
[![Liberapay patrons][liberapay-patrons-badge]][liberapay-url]
[![Liberapay receiving][liberapay-receives-badge]][liberapay-url]

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

See [LICENSES/MIT.txt](LICENSES/MIT.txt) for the full text.

## Author

- [Josh Williams](https://codingprime.com)

[pipeline-badge]: https://img.shields.io/gitlab/pipeline-status/dubzland%2Fansible-collections%2Fgitlab?gitlab_url=https%3A%2F%2Fgit.dubzland.com&branch=main&style=flat-square&logo=gitlab
[pipeline-url]: https://git.dubzland.com/dubzland/ansible-collections/gitlab/pipelines?scope=all&page=1&ref=main
[coverage-badge]: https://img.shields.io/gitlab/pipeline-coverage/dubzland%2Fansible-collections%2Fgitlab?gitlab_url=https%3A%2F%2Fgit.dubzland.com&branch=main&style=flat-square&logo=gitlab
[coverage-url]: https://git.dubzland.com/dubzland/ansible-collections/gitlab/pipelines?scope=all&page=1&ref=main

[galaxy-badge]: https://img.shields.io/badge/dynamic/json?style=flat-square&label=galaxy&prefix=v&url=https://galaxy.ansible.com/api/v3/collections/dubzland/gitlab/&query=highest_version.version
[galaxy-url]: https://galaxy.ansible.com/ui/repo/published/dubzland/gitlab/
[license-badge]: https://img.shields.io/gitlab/license/dubzland%2Fcontainer-images%2Fci-python?gitlab_url=https%3A%2F%2Fgit.dubzland.com&style=flat-square
[license-url]: https://git.dubzland.com/dubzland/container-images/ci-python/-/blob/main/LICENSE
[liberapay-patrons-badge]: https://img.shields.io/liberapay/patrons/jdubz?style=flat-square&logo=liberapay
[liberapay-receives-badge]: https://img.shields.io/liberapay/receives/jdubz?style=flat-square&logo=liberapay
[liberapay-url]: https://liberapay.com/jdubz/donate
[gitlab_common]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_common_role.html
[gitlab_server]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_server_role.html
[gitlab_runner]: https://docs.dubzland.io/ansible-collections/collections/dubzland/gitlab/gitlab_runner_role.html
