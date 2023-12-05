# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Update keys for S3 credentials (`accesskey` and `secretkey`) (#9)

### Added

- Nginx configuration for the Registry server (#10)

## [1.0.1] - 2023-12-04

### Fixed

- Removed `required_if` references from argument specs (not valid for roles)

## [1.0.0] - 2023-12-03

### Added

- Basic configuration (#2)
- Pages configuration (#3)
- SMTP configuration (#4)
- Object Storage configuration (#5)
- Docker registry configuration (#6)
- Backup configuration (#7)

### Changed

- Limit CI on merges to most recent versions of python/Ansible.

## [0.0.1] - 2023-12-01

### Added

- GitLab server role

[1.0.1]: https://git.dubzland.com/dubzland/ansible-collection-gitlab/-/compare/1.0.0...1.0.1
[1.0.0]: https://git.dubzland.com/dubzland/ansible-collection-gitlab/-/compare/0.0.1...1.0.0
[0.0.1]: https://git.dubzland.com/dubzland/ansible-collection-gitlab/-/tree/0.0.1
