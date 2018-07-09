# Ansible Raspberry Starter

This playbook bootstraps raspbian:

- Install minimal packages (sudo, curl, htop...)
- Install and configure a text editor with [vim](http://www.vim.org/).
- Install and configure a version control system  with [git](https://git-scm.com/).
- Install and configure [oh-my-zs](https://github.com/robbyrussell/oh-my-zsh).
- Install and configure node with [nvm](https://github.com/creationix/nvm).
- Download [Inconsolata font](https://fonts.google.com/specimen/Inconsolata)
- Configure wifi.

Role Variables
--------------

### nvm

- `node_version`:  Node that you want to install 

### oh-my-zsh

- `theme`: Name of the theme you want to use with oh-my-zsh

### wifi

- `ssid`: WIFI network name
- `wep_key0`: WIFI network password

### gitconfig:
  `name`: git username
  `email`: git email

Dependencies
------------

None.

License
-------

MIT