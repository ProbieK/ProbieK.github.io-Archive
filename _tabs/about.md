---
title: About
icon: fas fa-info-circle
order: 4
---

```
$ whoami
joshua
$ cat /etc/lsb-release
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=32
DISTRIB_CODENAME=Father
DISTRIB_DESCRIPTION="Dad to Kids LTS"
$ ps aux
USER       PID %CPU     %MEM   VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0      0.0   1744  1076 ?       a  00:00   0:00 /init
joshua       9  100.0  100.0  10168  5264 pts/0   b   00:00   0:00 -husband
joshua       9  100.0  100.0  10168  5264 pts/0   C   00:00   0:00 -father
joshua      39  0.0  0.0  10616  3212 pts/0    R+   17:00   0:00 ps aux
$ ifconfig
lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
$ hostname
blog.joshuakroger.com
$ id
uid=1000(joshua) gid=1000(joshua) groups 1000(joshua),22(sudo)
```