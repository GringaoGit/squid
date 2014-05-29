DEBIAN
=====

The configuration used is for transparent proxy

LAN (192.168.9.0/24)=>(eth1 - 192.168.9.1/24) ROUTER (eth0 - 192.168.6.2/30)=>(eth1 - 192.168.6.1/30) PROXY (eth0 - NAT/autoconfig)=> WAN

make iptables rules for your IP configuration
