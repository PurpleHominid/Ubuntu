# Ubuntu
Common command line instructions


### Add Users
$ adduser username


### Add User to SUDO list
$ usermod -aG sudo username


### Update Packages
$ sudo apt-get update
$ sudo apt autoremove
$ sudo apt-get upgrade
$ sudo apt-get dist-upgrade


### Security Packages Upgrade
$ sudo apt-get install unattended-upgrades -d


### Reboot
$ sudo reboot now


### Reboot (force)
$ sudo reboot -f


### Shutdown (with reboot; -r)
$ sudo shutdown -r now 


### Remote Reboot
$ ssh –t user@server.com ‘sudo reboot’

