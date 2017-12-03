This repository contains an Ansible playbook to set up my personal Arch Linux
machines.

## Get the repo
```sh
git clone https://github.com/benjaminshafii/ansible-personal.git
cd ansible-personal
git submodule update --recursive --remote
```


## Preflight
sh ./install.sh

## Provision Computer

```sh
ansible-playbook setup.yml --ask-vault-pass
```

## How to execute a specific task

```sh
ansible-playbook setup.yml --tags dotfiles

```

Heavily inspired by
[lrnt's ansible-personal repo](https://github.com/lrnt/ansible-personal)
