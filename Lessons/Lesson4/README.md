### [<- Return](../../)

# Lesson 4

## Lesson 4A

1. Installed all the required libraries

```bash
sudo pip3 install -U setuptools
sudo pip3 install -U django
sudo pip3 install -U djangorestframework
sudo pip3 install -U django-filter
sudo pip3 install -U markdown
sudo pip3 install -U requests
```

2. Had to install MariaDB

3. Starting Django project Stevens.
   1. Create MySQL database

```bash
MariaDB [mysql]> select user, host from mysql.user;
+-------------+-----------+
| User        | Host      |
+-------------+-----------+
| mariadb.sys | localhost |
| mysql       | localhost |
| root        | localhost |
+-------------+-----------+
3 rows in set (0.006 sec)

MariaDB [mysql]> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
+--------------------+
3 rows in set (0.001 sec)

MariaDB [mysql]> create database stevens;
MariaDB [mysql]> grant all privileges on stevens.* to ryan@localhost;
MariaDB [mysql]> quit
Bye
```
