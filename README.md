
# Configuration

Replace **eth0** by your LAN interface and **eth1** by WAN interface in
00-firewall script file

# Installation

Copy 00-firewall to /etc/network/if-up.d and restart services
```
sudo cp -fv 00-firewall /etc/network/if-up.d/
sudo service networking restart
```
