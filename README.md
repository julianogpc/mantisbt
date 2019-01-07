# mantisbt

### Requirements
* [VirtualBox >= 5.2.18](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant >= 2.0.2](https://www.vagrantup.com/downloads.html)


### Usage
```
$ vagrant up -d
$ vagrant ssh -c "cd /vagrant/ && docker-compose up -d"
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
