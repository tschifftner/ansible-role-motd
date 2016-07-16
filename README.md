# Ansible Role: Install motd

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-motd.svg)](https://travis-ci.org/tschifftner/ansible-role-motd)

Installs motd (message of the day) on Debian/Ubuntu linux servers.

## Requirements

None

## Dependencies

None.

## Installation

```
$ ansible-galaxy install tschifftner.motd
```

## Example Playbook

    - hosts: server
    
      vars:
        message_of_the_day: 'My custom message of the day'

      roles:
        - { role: tschifftner.motd }

## Supported OS
Ansible          | Debian Jessie    | Ubuntu 14.04
:--------------: | :--------------: | :-------------:
2.1              | Yes              | Yes

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)