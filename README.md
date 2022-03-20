## lesson1

### Diagram

```
                          Google.com
                            |
                          Internet
                            |
                          Comcast 
                            |
------------------ + ------ + -------- + -------------
                Laptop     Router     Linux box (IP=192.168.1.63)
                           (DHCP)
```

### Networking

> ```Router
> /etc/hosts
> ipconfig -a
> IP address
> ping
> host
> nslookup
> traceroute

### Linux: chown
```
su
useradd -s /bin/sh -d /home/jvu jvu
cat /etc/passwd /etc/group
mkdir /home/jvu
chown jvu:jvu /home/jvu
(or chgrp jvu /home
ls -l /home

sudo su
```
### Editor
- gedit
- vi
