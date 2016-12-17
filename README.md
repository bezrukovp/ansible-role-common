# Ansible Role: Common role

The role will setup timezone and install common tools.

Tools:

    - mc
    - vim
    - nano
    - man
    - sudo
    - tzdata
    - python-software-properties
    - software-properties-common
    - htop
    - curl
    - wget


## Role Variables

Available variables are listed below, along with default values:

    common_locale: 'ru_RU.UTF-8'
    common_timezone: 'Europe/Moscow'

## Example Playbook

    - hosts: servers
      roles:
         - { role: bezrukovp.common }

## License

MIT
