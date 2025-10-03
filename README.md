# network-auto-MIT
This is a college group project work repo .

Core Switch Manual Configuration
enable
configure terminal
vlan 98
 name DHCP_VLAN

interface Ethernet1
 switchport mode access
 switchport access vlan 98
 no shutdown

interface Ethernet2
 switchport mode access
 switchport access vlan 98
 no shutdown

interface Ethernet3
 switchport mode access
 switchport access vlan 98
 no shutdown

write memory

For PC
ip dhcp
show ip