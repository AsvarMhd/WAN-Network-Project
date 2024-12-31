# WAN Network Configuration Project

## 🚀 Project Overview
This project focuses on configuring a WAN (Wide Area Network) using Cisco Packet Tracer. The network design simulates real-world scenarios involving multiple routers, switches, and end devices, providing practical insights into network topology, routing protocols, and connectivity.

## 🔧 Technologies Used
- **Cisco Packet Tracer**
- **Networking Protocols**: RIP, OSPF
- **Hardware**:
  - 9 Routers
  - 8 Switches
  - 5 End Devices (PCs)

## 🎯 Objectives
- Establish seamless interconnection between multiple LANs through WAN.
- Implement static and dynamic routing.
- Ensure fault tolerance and redundancy.

## 🛠️ Key Features
- **Multiple Routing Protocols**: Configuration of RIP, OSPF.
- **Subnetting**: Effective subnetting to optimize IP allocation.
- **Troubleshooting**: Simulation of network failures and applying troubleshooting techniques.

## 📜 Commands for RIP and OSPF
# RIP Commands
- Router> enable
- Router# configure terminal
- Router(config)# router rip
- Router(config-router)# version 2
- Router(config-router)# network 192.168.1.0
- Router(config-router)# network 10.0.0.0
- Router(config-router)# exit
- Router(config)# exit
- Router# write memory

# OSPF Commands
- Router> enable
- Router# configure terminal
- Router(config)# router ospf 1
- Router(config-router)# network 192.168.1.0 0.0.0.255 area 0
- Router(config-router)# network 10.0.0.0 0.0.0.255 area 0
- Router(config-router)# exit
- Router(config)# exit
- Router# write memory

## 📸 Network Topology
![Annotation 2024-05-11 013920](https://github.com/user-attachments/assets/aa5ef512-5378-457b-aab5-ad2e9d665bd6)

