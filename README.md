# mantisbt

### Requirements
* [VirtualBox >= 5.2.18](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant >= 2.0.2](https://www.vagrantup.com/downloads.html)


### Usage
##### Create Virtual Machine and Install Docker
```
$ vagrant up -d --provision-with install
```
##### Start MantisBT
```
$ vagrant provision --provision-with start
```
##### Stop MantisBT
```
$ vagrant provision --provision-with stop
```
##### Restart MantisBT
```
$ vagrant provision --provision-with restart
```
##### Destroy MantisBT
```
$ vagrant provision --provision-with destroy
```
##### Shutdown Virtual Machine
```
$ vagrant halt
```
##### Shutdown Virtual Machine and Destroys All Resources 
```
$ vagrant destroy
```
### Installation Options
```
$ firefox http://localhost:8080/admin/install.php
```
```
Type of Database                                        MySQL/MySQLi
Hostname (for Database Server)                          mysql
Username (for Database)                                 mantisbt
Password (for Database)                                 mantisbt
Database name (for Database)                            bugtracker
Admin Username (to create Database if required)         root
Admin Password (to create Database if required)         root
Default Time Zone                                       Sao Paulo
Print SQL Queries instead of Writing to the Database    [ ]
Attempt Installation                                    [Install/Upgrade Database]
```
```
$ firefox http://localhost:8080/
>>> username: administrator
>>> password: root
```
