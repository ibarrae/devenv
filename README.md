# devenv

Ansible roles used to provision my local environment.

## Requirements

Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

## Getting Started

 - Install external roles with `ansible-galaxy`

```sh
ansible-galaxy install -r external-roles.yml
```

 - Run the main playbook:

```sh
ansible-playbook setup.yml
```
