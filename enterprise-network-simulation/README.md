# Enterprise Network Simulation

## Overview
This project simulates a small multi-site enterprise network in Cisco Packet Tracer. It demonstrates core networking concepts including VLAN segmentation, inter-VLAN routing, dynamic routing with OSPF, ACL-based access control, and secure departmental separation.

## Scenario
The simulated organisation has a Head Office and a Branch Office. Departments are separated into VLANs to improve security and traffic management. Routing between sites is performed dynamically using OSPF.

## Objectives
- Design a multi-site enterprise topology
- Implement VLANs for department separation
- Configure inter-VLAN routing
- Enable OSPF between routers
- Restrict traffic with ACLs
- Document testing and security decisions

## Departments and VLANs
### Head Office
- VLAN 10: Management
- VLAN 20: HR
- VLAN 30: Finance
- VLAN 40: IT
- VLAN 50: Guest

### Branch Office
- VLAN 60: Staff
- VLAN 70: Guest

## Key Features
- Multi-site routing across a WAN link
- Department-level network segmentation
- ACL rules protecting sensitive departments
- Guest network restrictions
- Documentation of addressing, design, and testing

## Repository Contents
- `topology/` contains addressing and topology notes
- `configs/` contains starter router, switch, and ACL configurations
- `docs/` contains design, security, and testing writeups
- `packet-tracer/` is for your final `.pkt` file

## Recommended Evidence to Add
- Packet Tracer topology screenshot
- Successful ping test screenshots
- OSPF adjacency screenshot
- ACL deny test screenshots

## Outcome
This project demonstrates the ability to design and document a structured enterprise network rather than only building a basic connectivity lab.
