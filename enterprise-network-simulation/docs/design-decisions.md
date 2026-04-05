# Design Decisions

## VLAN Segmentation
Each department was assigned a separate VLAN to reduce broadcast traffic, improve organisation, and support access control.

## OSPF
OSPF was selected instead of only static routing to simulate a more realistic enterprise environment with dynamic route exchange between sites.

## ACLs
ACLs were included to protect sensitive departments and to show policy-based traffic control, especially around guest and finance access.

## Multi-Site Scope
Including a branch office makes the project more realistic and demonstrates routing across a WAN rather than a single isolated LAN.
