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


### Install Python3
$ sudo apt-get update
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt install python3
$ sudo apt-get install python3
$ sudo apt-get upgrade python3
$ sudo apt install python3.7


### Install GCC g++ Compiler
$ sudo apt install g++


### Install build essentials
$ sudo apt install build-essential
