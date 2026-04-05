# Testing Results

## Planned Validation
- Verify devices within each VLAN can communicate with their configured gateway
- Verify authorised inter-VLAN traffic succeeds
- Verify unauthorised traffic is blocked by ACLs
- Verify OSPF adjacencies form correctly between HQ and Branch routers
- Verify branch staff can reach approved HQ resources
- Verify guest networks are restricted from internal access

## Evidence to Capture
- Ping tests
- Router `show ip route` output
- Router `show ip ospf neighbor` output
- ACL hit counters or deny tests
