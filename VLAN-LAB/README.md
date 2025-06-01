# VLAN & Subnetting Lab – Cisco Packet Tracer

This project involved the configuration of a fictional small office network using Cisco Packet tracer, focusing on VLAN segmentation, IP subnetting, and inter-VLAN routing through a router-on-a-stick setup.  

---

##  Topology Overview

- **3 VLANs** (HR, IT, Sales)
- **1 Router**, **3 Switches**, and **9 PCs**
- **Router-on-a-Stick** used for inter-VLAN routing
- **/29 subnetting** applied to each VLAN


## Topology 












| VLAN   | VLAN ID | Subnet            | Gateway IP       | 
|--------|---------|-------------------|------------------|
| HR     | 10      | 192.168.1.0/29    | 192.168.1.6      | 
| IT     | 20      | 192.168.1.8/29    | 192.168.1.14     | 
| Sales  | 30      | 192.168.1.16/29   | 192.168.1.22     | 
