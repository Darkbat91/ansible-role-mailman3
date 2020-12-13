![CI](https://github.com/Darkbat91/ansible-role-mailman3/workflows/CI/badge.svg?branch=main)

# Ansible mailman role
Basic ansible role to enable the full mailman suite

## pattern
All config files are in `/etc/opt/mailman3/`
Django root is `/var/opt/mailman3/web/project/`
All emails are stored in `/var/opt/mailman3/core/`


## Advanced

There are numerous other options within the [defaults/main.yml](./defaults/main.yml) that can change other parts of the behavior of the system

## Changelog
The [changelog](./CHANGELOG.md) is stored externally


## Credit
Original role based on `https://github.com/galaxyproject/ansible-mailman3`