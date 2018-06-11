Role Name
=========

A role installing and configuring nginx as a reverse proxy for Radicale on Debian 9. Implements authentication using nginx.

Requirements
------------

TBA

Role Variables
--------------
radicale_proxy_port: port nginx listens on for reverse proxying (default: 443)

radicale_proxy_server_name: server name nginx listens on (default: sub.example.com)

radicale_port: port Radicale service listens on (default: 5232)

radicale_credentials_file: path to credentials file (default: /etc/radicale/users)

radicale_users: dictionary containing credentials on the format { name: <val>, hash: <output of htpasswd -n <val>}. Default value is user{1,2} with password "password".

Dependencies
------------
- https://github.com/hecd/lexicon-letsencrypt.git"

Example Playbook
----------------
TBA


License
-------

GPLv3

Author Information
------------------
TBA

