# CCNA-Configurations
CCNA network configuration projects including VLANs, Routing (RIP, OSPF, Static), ACL, DHCP, etc.
First Project – Basic Switch Configuration
basic-switch-config/
## Basic Switch Configuration

This folder contains the basic switch configuration used to:
- Set hostname
- banner Motd
- line console
- management ip
- Assign passwords
- Enable VLAN 1 IP
- Secure console and VTY lines
- 
### Commands Used:
Switch> enable
Switch# configure terminal
Switch(config)# hostname Switch1
Switch>banner motd
Switch1(config)# enable secret cisco
Switch1(config)# line console 0
Switch1(config-line)# password class
Switch1(config-line)# login
### Network Topology

![Switch Topology](basic-switchconfiguration.png)
