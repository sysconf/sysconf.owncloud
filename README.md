# This is a Sysconf repository for the Catapatate OwnCloud system

* Inspired after: http://www.noobslab.com/2015/01/install-owncloud-in-ubuntulinux-mint.html

## Details

* PPA repository provided statically by Sysconf in:
** /etc/apt/sources.list.d/noobslab-ubuntu-apps-utopic.list
** /etc/apt/trusted.gpg.d/noobslab_ubuntu_apps.gpg
* Apache2 is used
* MySQL root password is unchanged (empty?)
* Database used by OwnCloud: MySQL
** user: owncloud
** customized password for MySQL user "owncloud": uuZ8Jav5aegh2Ier
** database: owncloud

## Dependencies

* ```../sysconf.base/``` from ```git@github.com:sysconf/sysconf.base.git``` [```master```]
* ```../sysconf.gitted/``` from ```git@github.com:sysconf/sysconf.gitted.git``` [```master```]
