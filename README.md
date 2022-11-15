# ansible-config_docker_containers

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-config_docker_containers-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/config_docker_containers)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-config_docker_containers.svg)](https://github.com/lotusnoir/ansible-config_docker_containers/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-config_docker_containers?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/config_docker_containers)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/config_docker_containers)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/config_docker_containers)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and launch docker containers

## Requirements

- lotusnoir.apps_docker


## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: config_docker_containers
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-config_docker_containers


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

