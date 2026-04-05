# ACL Summary

## Intended Security Policy
- Guest VLANs must not access internal departmental networks
- Finance should be protected from unnecessary access by other departments
- IT should retain administrative access where required
- Branch guest traffic should be limited to internet-bound access only

## Example Policy Logic
- Deny 192.168.50.0/24 to 192.168.10.0/24 through 192.168.40.0/24
- Deny 192.168.70.0/24 to 192.168.60.0/24 and all HQ internal networks
- Permit IT VLAN administrative access where explicitly needed

## Security Value
ACLs provide a practical way to enforce least privilege and prevent unauthorised lateral movement between departments.
