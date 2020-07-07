[![Build Status](https://travis-ci.com/nl2go/ansible-role-clickhouse-backup.svg?branch=master)](https://travis-ci.com/nl2go/ansible-role-clickhouse-backup)
[![Ansible Galaxy](https://img.shields.io/badge/role-nl2go.clickhouse-backup-blue.svg)](https://galaxy.ansible.com/nl2go/clickhouse-backup/)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/nl2go/ansible-role-clickhouse-backup)](https://github.com/nl2go/ansible-role-clickhouse-backup/releases)

# Ansible Role: Clickhouse backup

An Ansible Role that manages installation and configuration of the [Clickhouse backup tool](https://github.com/AlexAkulov/clickhouse-backup).

## Role Variables

Available variables listed and described along with default values in [defaults/main.yml](defaults/main.yml).

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
         - { role: nl2go.ansible-role-clickhouse-backup }

## Development

Use [docker-molecule](https://github.com/nl2go/docker-molecule) following the instructions to run [Molecule](https://molecule.readthedocs.io/en/stable/)
or install [Molecule](https://molecule.readthedocs.io/en/stable/) locally (not recommended, version conflicts might appear).

Use following to run tests:

    molecule test --all

## Maintainers

- [dirkaholic](https://github.com/dirkaholic)

## License

See the [LICENSE.md](LICENSE.md) file for details.

## Author Information

This role was created in 2020 by [Newsletter2Go GmbH](https://www.newsletter2go.com/).