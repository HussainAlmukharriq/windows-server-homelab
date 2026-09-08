# Windows Server homelab
Windows Server enterprise homelab documenting Active Directory, DNS, DHCP, Group Policy, access control, networking, and troubleshooting.

## Overview

This project documents my hands-on Windows Server homelab built to develop practical experience with Windows Server administration, Active Directory, networking, Group Policy, and enterprise IT infrastructure.

The environment is virtualized using Proxmox VE and includes a Windows Server 2022 domain controller and a Windows 11 domain-joined workstation.

Rather than only following demonstrations, I use the environment to configure services, test configurations, troubleshoot problems, and better understand how Windows domain environments operate.
## Lab Architecture

![Windows Server Homelab Architecture](images/homelab-architecture.png)

## Lab Environment

| System | Purpose |
|---|---|
| Proxmox VE | Virtualization platform and isolated lab networking |
| Windows Server 2022 | Domain Controller (DC01) |
| Windows 11 | Domain-joined client workstation (WIN11) |
| Active Directory Domain Services | Domain and identity management |
| DNS | Domain name resolution |
| DHCP | Automatic IP address assignment |

## Skills & Technologies

- Windows Server 2022
- Windows 11
- Proxmox VE
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Organizational Units (OUs)
- User and Group Management
- Group Policy
- Security Filtering
- SMB File Sharing
- NTFS Permissions
- Network Drive Mapping
- DHCP Reservations and Exclusions
- Proxmox Virtual Networking and Isolated Lab Networks
- Windows Network Troubleshooting

## Project Documentation

| Project | Documentation |
|---|---|
| [Lab Setup & Virtualization](docs/01%20-%20lab-setup.md) | [View Documentation](docs/01%20-%20lab-setup.md) |
| [Active Directory Domain Services](docs/02%20-%20active-directory.md) | [View Documentation](docs/02%20-%20active-directory.md) |
| [Group Policy Management](docs/03%20-%20group-policy.md) | [View Documentation](docs/03%20-%20group-policy.md) |
| [File Sharing & NTFS Permissions](docs/04%20-%20file-sharing-permissions.md) | [View Documentation](docs/04%20-%20file-sharing-permissions.md) |
| [DHCP Configuration & Management](docs/05%20-%20dhcp.md) | [View Documentation](docs/05%20-%20dhcp.md) |

The documentation includes configuration steps, screenshots, testing, troubleshooting, and lessons learned during the environment's build.

The documentation includes configuration steps, screenshots, testing, troubleshooting, and lessons learned during the environment's build.
