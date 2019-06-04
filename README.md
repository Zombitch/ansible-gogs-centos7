# ansible-gogs-centos7
An ansible playbook that install gogs. 
The easiest way to get gogs installed in your centOS7 server.

## Prerequisites

Ansible software should be installed in centOS7. You can install it with the following command : 

> _sudo yum install ansible_

## What component will be installed
The following software will be installed :

- Apache HTTPD
- MariaDB
- MySQL-Python
- Gogs

## How to install it ?

1. Download gogs.yml and transfer it to your centOS7 server, in /tmp/ directory
2. Run the following command 
>ansible-playbook /tmp/gogs.yml

## Additional information

- By default, root password will be _g0g5_ but you can modify script (gogs.yml) in order to fit your needs
- An empty database will be created; its is name _gogs_
