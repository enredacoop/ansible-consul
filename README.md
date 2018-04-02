# Ansible for Consul

This is an Ansible playbook developed by [ENREDA Cooperativa](http://enreda.coop) for deploying [Consul](http://consulproject.org/). This playbook is originally based on [simple-ansible](https://github.com/infoslack/simple-ansible).


## Before we start

- Requires Ansible 1.6.1 or newer
- Expects Ubuntu 14.04 LTS (64 bit)


## Setup

```
$ git clone https://github.com/enredacoop/ansible-consul.git
$ cd ansible-consul
$ cp hosts.example hosts
$ cp group_vars/all.example group_vars/all
```

- Edit *hosts* and *group_vars/all* to adapt the values to your specific envirnment.


## Use

```
$ ansible-playbook server.yml
```
