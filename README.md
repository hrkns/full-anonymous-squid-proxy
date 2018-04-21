Setup a full anonymous proxy. Install squid in your OS (only tested on UNIX) and replace the existing squid.conf (make a backup first) with the one provided in this project. Then restart the service.

In order to set an authentication process create an user and a password:

- Execute the command `sudo htpasswd -c /etc/squid3/passwords username_you_like` an provide a password to the username that you set
