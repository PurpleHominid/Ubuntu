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


### Install MariaDB
$ sudo apt-get remove mariadb-server
$ sudo apt-get install software-properties-common
$ sudo apt-key adv --recv-keys --keyserver hkp://keyserver.ubuntu.com:80 0xF1656F24C74CD1D8
$ sudo add-apt-repository "deb [arch=amd64,arm64,ppc64el] http://mariadb.mirror.liquidtelecom.com/repo/10.4/ubuntu $(lsb_release -cs) main"
$ sudo apt update
$ sudo apt -y install mariadb-server mariadb-client


### Set MariaDB root password
$ sudo mysql_secure_installation


### Confirm MariaDB version
$ mysql -u root -p
MariaDB [(none)]> SELECT VERSION();


### Install Java 13
$ sudo add-apt-repository ppa:linuxuprising/java
$ sudo apt update
$ sudo apt install oracle-java13-set-default
