## Dockerfile for salt-minion on Debian Jessie
* * * 


Usage:

docker run -d e1337h4xx/saltwheezy

Salt-minion will try to reach docker bridge 172.17.0.1

Install salt-master on local machine and make it automatically accept new minions


/etc/salt/master

`auto_accept: True`


**pro tip of the day!**
use iptables to secure your salt-master service

Have fun!
