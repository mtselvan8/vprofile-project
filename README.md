
# VProfile Project 🚀

## Overview
Multi tier web application deployed locally 
and on AWS Cloud.

## Tech Stack
- 🌐 Web Server: Nginx
- ☕ Application Server: Tomcat
- 🗄️ Database: MySQL
- ⚡ Cache: Memcache
- 📨 Message Queue: RabbitMQ

## Environments
- AWS Cloud using EC2, ELB, S3, 
  Route53, Auto Scaling

## Tools Used
AWS | Maven | Tomcat | 
MySQL | Memcache | RabbitMQ | Nginx

# Prerequisites
#
- JDK 17 
- Maven 3 
- MySQL 8
  
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql

# VProfile Project by Tamil

## URL
🌐 URL: https://vpro.mtsinfotech.xyz

## Screenshots

### EC2 Instances Running
![EC2](screenshots/S_-1.PNG)

### Load Balancer - Active
![Load Balancer](screenshots/S_-2.PNG)

### S3 Bucket
![S3](screenshots/S_-3.PNG)

### Application Login Page
![Login](screenshots/S_-4.PNG)

### Application Dashboard
![Dashboard](screenshots/S_-6.PNG)

### Database & Cache Working
![Cache](screenshots/S_-8.PNG)

### Security groups
![SG](screenshots/S_-9.PNG)
