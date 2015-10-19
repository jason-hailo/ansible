# Ansible Playbook 


Installs the following:
* git, cmake, buildessentials, python-dev
* vim-gnome
* Oh-My-Zsh
* vim-go plugin
* YouCompleteMe plugin
* Utilisnips
* Customised .Vimrc for YouCompleteMe and Utilisnips to co-exist
* Docker from official docker repo
* Terminator
* Powerline Fonts - for Oh-My-Zsh agnoster theme

```
git clone https://github.com/dbnegative/ansible.git ~/ansible
cd ~/ansible
ansible-playbook laptop.yml -K
```
