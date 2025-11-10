# Deployment-of-web-application-using-Docker

## Launch EC2 Instance (ubuntu)
-- Go to root directory


```shell
sudo -i
```

-- update the instance

```shell
apt update
```
## Prerequisities of the project for frontend ,backend and database

For backend

--Java Development Kit (JDK 17 or higher) installed.

--Maven installed.

--Spring Boot application source code or JAR file.

For frontend

--Install Node.js and npm

For Database

--Install MariaDB

--clone the repository from github
```shell
git clone https://github.com/Rohit-1920/EasyCRUD.git
```



## Database-setup

-- install mysql-client

```shell
apt install mysql-client -y
```
-- login to mysql and connect the database

```shell
mysql -h (endpoint of the database which we have created) -u admin -p
mysql -h database-1.cxaywyasm64g.ap-southeast-2.rds.amazonaws.com -u admin -p
```
enter the root password

create new database and user

```shell
CREATE DATABASE student_db;
GRANT ALL PRIVILEGES ON springbackend.* TO 'username'@'localhost' IDENTIFIED BY 'your_password';
```
replace the username and your_password which you have created

Exit mariaDB
```shell
exit
```
#Backend



