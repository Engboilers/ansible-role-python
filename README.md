# Ansible Role: Python

[![Build Status](https://travis-ci.org/kadaan/ansible-role-python.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-python)

Installs python and global python packages.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    python_versions: []

Python versions you would like to make sure are installed by pyenv.

    python_pip_global_packages: []

Global PIP packages you would like to make sure are installed.

## Dependencies

  - `kadaan.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.python }

## License

Apache 2.0
