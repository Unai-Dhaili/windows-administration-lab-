# Windows Infrastructure Lab - Active Directory / DNS / DHCP / GPO / File Services

Personal project focused on strengthening Windows infrastructure and identity management fundamentals through a complete hands-on lab environment based on Active Directory and core Windows Server services.

## Overview
This project documents the deployment, configuration, and validation of a minimal corporate Windows environment, simulating core responsibilities of a Systems Administrator.
It includes domain setup, identity lifecycle, group-based permissions, Group Policy management, file services, and troubleshooting from both server and client perspectives.

## Lab Setup
- **Host OS:** Windows 11 + VMware Workstation Pro  
- **Server:** Windows Server (Desktop Experience)  
- **Client:** Windows 10 domain-joined  
- **Main Services:** AD DS, DNS, DHCP, SMB File Services, Group Policy  
- **Focus Areas:** Identity & access management, policy enforcement, permissions, troubleshooting

## Topics Covered
- Domain Controller deployment & validation (AD DS + DNS)
- DNS forwarders, AD-integrated zones, name resolution tests
- DHCP configuration for domain clients
- OU design and identity lifecycle (users, groups, memberships)
- Group Policy creation, targeting, validation, and troubleshooting (gpupdate, gpresult, Event Viewer)
- SMB file shares with NTFS + Share permissions via security groups
- Operational scenarios: onboarding, offboarding, department changes
- Client-side troubleshooting using standard tools (ipconfig, nslookup, gpupdate)

## Documentation
Full technical report available in **English** and **Spanish**, including configuration steps, validation screenshots, and troubleshooting notes:

 **[Download PDF (English)](https://github.com/user-attachments/files/24351693/Technical.Project_.Windows.Infrastructure.pdf)**
 
 **[Download PDF (Spanish)](https://github.com/user-attachments/files/24351684/Proyecto.Tecnico_.Infraestructura.Windows.pdf)**

# Possible Next Steps
Future extensions may include multi-DC topologies, hybrid identity, and automation, depending on career focus.
