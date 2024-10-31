# INSTALASI-DNS-SERVER
Langkah KerjaMasukkan cd 2 dan 3# apt-cdrom add# apt-get update root@smkmanusa:~# apt-get install bind9 dnsutils   masukkan cd 1 dan cd 2 root@smkmanusa:~# nano /etc/bind/named.conf.default-zonesEdit pada baris:zone "smkmanusa.sch.id" {type master;file "/etc/bind/db.manusa";};zone "1.30.172.in-addr.arpa" {type master;file "/etc/bind/db.172";};zone 
