# Cisco Meraki Centralized WLC on a 3-Tier Campus LAN Architecture

![image](https://github.com/ascotlan/Cisco-Meraki-Centralized-WLC-on-a-3-Tier-Campus-LAN-Architecture/blob/main/topology.png)

## Abstract

Using the Packet tracer software, I successfully implemented a centralized cloud based WLC on a 3-Tier LAN architecture, using the Cisco Meraki server and security appliance. This is a continuation of work done on the project titled as [“DHCP configuration in a 3-Tier Campus LAN Architecture”].(https://github.com/ascotlan/DHCP-configuration-in-a-3-Tier-Campus-LAN-Architecture) After configuring a DHCP pool for the Meraki Security Appliance, I created redundant virtual interfaces at the distribution layer for VLAN 32, for the Meraki appliance. Inter-VLAN routing was enabled and a route for all layer 3 traffic to/from the VLAN 32 virtual interface was also configured using OSPF. A default route to the service provider gateway was manually configured and thus a route to/from the Meraki server was implemented. Once the Meraki security appliance established a management connection to the Meraki server, I successfully configured the appliance via the Meraki dashboard. LAN and WAN connectivity was then achieved for all wireless end hosts on the WLAN implemented on the Meraki Security Appliance.
