# Home Lab Setup

## Overview
Built a virtualized home lab environment using Oracle VirtualBox to practice networking, Linux administration, and cybersecurity concepts.

## Virtual Machines
| VM | OS | IP Address | Purpose |
|---|---|---|---|
| Kali Linux | Debian-based | 192.168.1.1 | Security testing & pentesting tools |
| CentOS | RHEL-based | 192.168.1.2 | Enterprise Linux server simulation |
| Windows 10 | Windows | 192.168.1.3 | Windows administration & troubleshooting |
| Ubuntu Server | Ubuntu 26.04 LTS | 192.168.1.4 | Server hosting & services |

## Network Configuration
- Network Type: Internal Network (isolated)
- Subnet: 192.168.1.0/24
- IP Assignment: Static

## Steps Performed
1. Installed and configured four VMs in VirtualBox
2. Set all VMs to Internal Network mode
3. Assigned static IP addresses manually via CLI
4. Verified connectivity between VMs using ping
5. Achieved 0% packet loss across all connections

## Tools Used
- Oracle VirtualBox
- Kali Linux
- CentOS
- Windows 10
- Ubuntu Server 26.04 LTS
- Linux ip command
- Windows netsh command
- Nmap

## Skills Demonstrated
- Virtual machine setup and management
- Network configuration and static IP assignment
- Linux and Windows CLI
- Inter-VM connectivity testing
- Basic network troubleshooting

---
