# tp1-geoffrey-parrier

## Info

Mail : geoffrey.parrier@ynov.com
github_username : @geoffreyparrier
professor : @aegirops

## VM Config

- Ram: 1GB
- OS: <a href='https://ubuntu.com/download/server'>Ubuntu Server</a>

### Libraires & Programs installed

`nodejs@12
openssh-server
nginx`

## Prerequisites

- <a href='https://www.vagrantup.com'>Vagrant</a>
- <a href='https://www.virtualbox.org/wiki/Download_Old_Builds_6_0'>VirtualBox 6.0</a>
- <a href='https://git-scm.com/book/en/v2/Getting-Started-Installing-Git'>Git</a>
- A shell

## Installation / How to start

1. Clone this repository `https://github.com/YI-B3-Devops/tp1-parrier-geoffrey`.
1. Execute `vagrant up` and wait for the end of the installation and configuration.
1. Your done ! The environment is up and running.

## Usage

### SSH Access

Execute `vagrant ssh`

### View nginx webpage

Go on <a href='http://localhost:8080'>http://localhost:8080</a>

### Stop the Virtual Machine

If you want to stop the virtual machine use `vagrant halt`

## Uninstall

If you need to uninstall this virtual machine use these commands :

3. stop the virtual machine
  3. `vagrant halt`
3. Deleting the vm 
  3. `vagrant destroy`

When he demand say yes in the cmd.
You can delete manually the `.vagrant` folder