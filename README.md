Virtualhost Manage Script
===========

Bash Script to allow create or delete apache/nginx virtual hosts on Ubuntu on a quick way.

## Installation ##

1. Download the script
2. Move it
        $ mv virtualhost-nginx.sh /usr/bin/virtualhost
3. Apply permission to execute:
        $ chmod +x /usr/bin/virtualhost

## Usage ##

Basic command line syntax:

    $ sudo virtualhost [create | delete] [domain] [optional port host_dir]

### Examples ###

to create a new virtual host:

    $ sudo virtualhost create mysite.dev 1336 /home/user/sites/mysite

to delete a virtual host

    $ sudo virtualhost delete mysite.dev
