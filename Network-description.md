
Network in the US

Switch I-SW-01-22 ports 43-48 VLAN 73 (untagged)

Lenovo RD240 US-01.WARCA.NET Lan1 port 43 member1, Lan2 port 43 member 2, 10.73.1.11/24

IMMI port 45 member 1 - 10.73.1.13

Lenovo RD240 US-02.WARCA.NET Lan 1 port 44 member 1, Lan2 port 44 member2, 10.73.1.21/24

MMI port 45 member 2 - 10.73.1.23

Cisco ASA5515 

Eth0 - Comcast router

Eth2 SWITCH i-sw-01-22 mem1 port 24

Eth3 switch i-sw-01-22 mem2 port 24

MGMT - switch i-sw-01-22 mem1 port 48

Main web-server - warca-web-main - ssh://maint@10.73.1.33

warca DNS server - warca-dns-01 -  ssh://maint@10.73.1.27

warca-gluu-01 - ssh://maint@10.73.1.29

warca-web-01 - ssh://maint@10.73.1.26

