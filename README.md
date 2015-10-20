# Ansible Playbook 

Tested on Ubuntu 15.04 64bit

Installs the following:

* git, cmake, buildessentials, python-dev
* Oh-My-Zsh
* Vim gnome with vundle, vim-go, YouCompleteMe, Utilisnips
* Customised .Vimrc for YouCompleteMe and Utilisnips to co-exist
* Docker from the official Docker repo
* Terminator
* Powerline Fonts - for Oh-My-Zsh agnoster theme

```
git clone https://github.com/dbnegative/ansible.git ~/ansible
cd ~/ansible
ansible-playbook laptop.yml -K
```

The following tags are available:
* ohmyzsh - Installs Oh My Zsh 
* vim-gnome - Installs Vim for Gnome and plugins (vundle,ycm,utilisnips,vim-go) 
* docker - Installs Docker
* go , golang - Installs Go Lang


