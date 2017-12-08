# Linux Server Configuration

#### Goal given by udacity
You will take a baseline installation of a Linux server and prepare it to host your web applications. You will secure your server from a number of attack vectors, install and configure a database server, and deploy one of your existing web applications onto it.

#### Info
- IP: 52.58.244.247
- SSH PORT: 2200

## Software installed
- apache2: HTTP Server
- finger:	User info lookup program
- flask: Micro web framework written in Python
- git: Version control system
- libapache2-mod-wsgi: Tool to serve flask app with apache
- postgresql:	Database
- sqlalchemy:	The Database Toolkit for Python

## Configurations made
- Created a new user named grader
- Made grader a sudoer
- Updated all installed packages
- Changed SSH port to 2200
- Configured Uncomplicated Firewall to allow incoming connections only from port 2200, 80 and 123
- Configured local timezone to UTC
- Installed Apache to serve Python mod_wsgi application
- Installed and configured PostgreSQL
- Installed git 
- Set up a project

## Third-party resources used
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps142
- https://discussions.udacity.com/t/configuring-utc-time-zone/35776
