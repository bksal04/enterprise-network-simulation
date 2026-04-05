# Addressing Plan

## Head Office VLANs
- VLAN 10 - Management: 192.168.10.0/24, Gateway 192.168.10.1
- VLAN 20 - HR: 192.168.20.0/24, Gateway 192.168.20.1
- VLAN 30 - Finance: 192.168.30.0/24, Gateway 192.168.30.1
- VLAN 40 - IT: 192.168.40.0/24, Gateway 192.168.40.1
- VLAN 50 - Guest: 192.168.50.0/24, Gateway 192.168.50.1

## Branch Office VLANs
- VLAN 60 - Staff: 192.168.60.0/24, Gateway 192.168.60.1
- VLAN 70 - Guest: 192.168.70.0/24, Gateway 192.168.70.1

## WAN
- HQ Router: 10.0.0.1/30
- Branch Router: 10.0.0.2/30
