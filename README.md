# Catalog Server

- ip: 107.21.67.188
- domain name: ec2-107-21-67-188.compute-1.amazonaws.com
- port 2200

## Access the server:
`ssh -i grader 107.21.67.188 -p 2200`
Use the domain name to access the website.

## Software Installed

- pip
- flask
- postgresql
- mod_wsgi (for python version 2.7)

## Configuration

- apache html is at default location `/var/www/html/`
- postgresql user named catalog was created
- user named "www-data" was created, granting database access to apache2 process
- system user `grader` created and configured to use ssh key pairs
- system user `grader` added to sudo group

