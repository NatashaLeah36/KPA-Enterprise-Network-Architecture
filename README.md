# Optimized Enterprise Network Architecture for Kenya Ports Authority (KPA)

## Project Overview
The Kenya Ports Authority (KPA) manages critical maritime operations, including cargo handling, shipping logistics, and administrative processes. Efficient and secure communication across all departments is essential for operational excellence. This project presents the design and simulation of a secure, scalable, and highly available enterprise network architecture for KPA. The design follows industry best practices including hierarchical network architecture, VLAN segmentation, Layer 3 switching, OSPF dynamic routing, and high availability mechanisms.

---

## Objectives
- Separate departments using **VLANs**
- Connect devices across VLANs with **Layer 3 routing**
- Use **dynamic routing (OSPF)** for fast communication
- Ensure **high availability** with redundant core switches and HSRP
- Secure the network with **ACLs, port security, and safe device management**
- Simulate the network in **Cisco Packet Tracer**

---

## Key Features
- **Dual Core Switches:** Keep the network running even if one fails
- **Gateway Redundancy (HSRP):** Always have a working default gateway
- **EtherChannel:** Combine multiple links for speed and redundancy
- **VLANs & Segmentation:** Organize and secure traffic
- **Traffic Control (ACLs):** Filter and protect network traffic

---

## Reliability & Security
- **Redundant WAN & links** keep the network online
- **Rapid Spanning Tree (RSTP)** prevents loops
- **Guest VLANs** are isolated
- **Encrypted management (SSH) & centralized authentication (RADIUS)** ensure security

---

## Tools & Technologies
- Cisco Packet Tracer
- Layer 3 Switching & VLANs
- OSPF Routing
- HSRP, EtherChannel, STP/RSTP
- SNMP Monitoring

---

## Future Plans
The network can be further improved with **firewalls, threat detection, cloud monitoring, and automation** for better security and efficiency.
