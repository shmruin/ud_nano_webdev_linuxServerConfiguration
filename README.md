# Introduction

This project provides linux server environment for previous 'Build an Item Catalog Application' project

# Necessary meetups

i. The IP address and SSH port so your server can be accessed by the reviewer.
 * Public IP: 54.199.232.245
 * SSH port : 2200

ii. The complete URL to your hosted web application.
 * address : [a link](http://ec2-54-199-232-245.ap-northeast-1.compute.amazonaws.com)
 
iii. A summary of software you installed and configuration changes made.
iv. A list of any third-party resources you made use of to complete this project.
 * `Amazon Lightsail` - accessible Ubuntu Linux server
 * Change `ufw settings` - SSH port to 2200, allow HTTP, NTP as required
 * Configure `local timezone` to UTC
 * `ssh-keygen` - key pair to login as `grader` user
 * `Apache2`, `python3 mod_wsgi` for server
 * `PostgreSQL` - Make db by psql
 * `git` - To clone the old git project `ud_nano_webdev_catalogAPI`

# Environment

* `Amazon Lightsail` basic `ubuntu` server
* Requires `Apache2`
* Requires `postgreSQL`

# Path

* All realted files are in `/var/www/FlaskApp`

