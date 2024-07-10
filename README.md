# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
  
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

# Description

This project demonstrates the deployment of a web application using Vagrant and Linux. The application stack includes:

Nginx: As the web server.
Tomcat: As the application server.
RabbitMQ: For messaging.
Memcache: For caching.

The focus of this project is on the deployment process of the web application. Note that the actual implementation of the web application is not covered in this project.
