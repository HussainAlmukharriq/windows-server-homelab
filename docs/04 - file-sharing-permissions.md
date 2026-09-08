# File Sharing and NTFS Permissions

## Objective

Configure centralized departmental file shares on Windows Server 2022 and control access using Active Directory users, security groups, share permissions, and NTFS permissions.

## File Share Configuration

I created departmental folders on DC01 and shared them across the domain using SMB.

The lab included separate resources for departments such as:

- HR
- IT

This allowed domain users to access shared resources from the Windows 11 workstation while maintaining separation between departments.

## Access Control

Active Directory security groups were used to manage access rather than assigning permissions individually to each user.

Permissions were configured so that users could access resources appropriate to their department while restricting access to resources they were not authorized to use.

This provided experience working with:

- Active Directory security groups
- SMB file sharing
- Share permissions
- NTFS permissions
- Group-based access control

## Network Drive Mapping

I configured Group Policy to automatically map departmental network drives for domain users.

When an authorized user signed in to WIN11, the appropriate shared drive became available in File Explorer.

This demonstrated how Active Directory, Group Policy, and Windows file services can work together to centrally provide resources to users.

## Testing

I tested the configuration using domain accounts from different departments.

Testing included:

- Signing into WIN11 with domain accounts
- Confirming authorized users could access their departmental share
- Verifying permissions were applied through group membership
- Testing network drive mapping
- Confirming departmental resources remained separated

## What I Learned

This portion of the homelab provided hands-on experience with:

- Creating SMB network shares
- Configuring NTFS permissions
- Managing access through Active Directory security groups
- Applying permissions based on organizational roles
- Mapping network drives with Group Policy
- Testing access from a domain-joined workstation
- Understanding the relationship between authentication and resource authorization
