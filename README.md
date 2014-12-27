## vagrant-php-ubuntu-utopic

### Creators of [original version](https://github.com/iJackUA/try-yii2)

Created by [Evgeniy Kuzminov](http://stdout.in) and [Anton Logvinenko](http://anton.logvinenko.name/).

## Out of the box

* Ubuntu 14.10 64 bit + bulk of system soft like `mc`, `curl`, etc.
* PHP-FPM 5.5 + modules `intl`, `gd`, `xdebug` etc.
* Nginx 1.6
* MySQL 5.5
* Composer
* Local IP loop on Host machine `/etc/hosts` and Virtual hosts in Nginx already set up too !

## Quick start

### Install

* [Virtualbox 4.3+](https://www.virtualbox.org/) + VirtualBox Extension Pack
* [Vagrant 1.6+](http://www.vagrantup.com/)
additional Vagrant modules (optional, but provide full automation) :
* `vagrant plugin install vagrant-hostsupdater vagrant-vbguest vagrant-cachier`
* [Ansible](http://docs.ansible.com/intro_installation.html)

> You don't need to have Ansible installed on host machine. It will be installed on VM and self-provisioning will be launched. So it is possible to run everything on Windows machine. 

### RUN

* Clone this sources from Git
* Run `vagrant up`.
* It will start VM creation and Provisioning. Could take some time 15-30 min... Drink coffee and get back for complete virtual server ready for play!

#### Differences with original version of box

The box only for develop with PHP. Box doesn't include any DBMS. You can install DBMS manually after `vagrant up`.
