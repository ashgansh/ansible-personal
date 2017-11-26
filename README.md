This repository contains an Ansible playbook to set up my personal Arch Linux
machines.

## Provision Computer

```sh
# first decrypt the secret
ansible-vault decrypt toolbox.zsh
ansible-playbook setup.yml
```

## How to execute a specific task

```sh
ansible-playbook setup.yml --tags dotfiles

```

Heavily inspired by
[lrnt's ansible-personal repo](https://github.com/lrnt/ansible-personal)
