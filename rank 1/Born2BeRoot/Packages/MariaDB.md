# What is?
This is a database. util in various purposes, type how storage of data and application of register
# Install
`sudo` [[apt]] `install mariadb-server`
MariaDB he comes insecure, then you need run `sudo mysql_secure_installation` before install.
## Switch to unix_socket authentication?
No. We have one root account protect.
## Change the root password?
No. We not want change root password.
## Remove anonymous users?
Yes. By default MariaDB  he comes option for access the DB with user without exist for test environment.
## Disallow root login remotely?
Yes. disable option to login with root from remote access. this options block people try brute force. we only can access with root from local access
## Remove test database and access to it?
Yes. this option remove all DB and users test utils.
## Reload privilege tables now?
Yes. Reload table of permissions in MySQL for the definitions.
# Commands
### Create DB
`CREATE DATABASE {database};` this table is from [[WordPress]]
### Get DBs
`SHOW DATABASE;`
### Create User
`CREATE USER '{name}'@'localhost' IDENTIFIED BY '{password}';`
### Give Privileges From user
`GRANT ALL PRIVILEGES ON {database}.* TO '{name}'@'localhost';`
### Update Permissions
`FLUSH PRIVILEGES;`
