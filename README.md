# Windows Server 2022 & Active Directory Home Lab

# Overview
This project documents a hands-on Windows Server 2022 lab focused on Active Directory administration, domain management, DNS troubleshooting, Group Policy, and access control.

# Lab Environment
- **Server OS:** Windows Server 2022 Standard Evaluation (Desktop Experience)
- **Client OS:** Windows 10 Pro
- **Virtualization:** Oracle VirtualBox
- **Domain:** zackilab.local
- **Tools:** Active Directory Users and Computers, DNS, Group Policy Management, Command Prompt, and Windows file-sharing tools

# Skills Demonstrated

# Active Directory Administration
- Installed Active Directory Domain Services (AD DS).
- Promoted a Windows Server machine to a domain controller.
- Created organizational units (OUs), domain user accounts, and security groups.
- Joined a Windows 10 client to the domain.
- Verified domain authentication using a domain user account.

# DNS & Network Troubleshooting
- Configured static IP addresses for the lab's virtual network.
- Used `ipconfig`, `nslookup`, `ping`, and `whoami` to diagnose and verify connectivity.
- Investigated a DNS resolution issue involving the virtual machine network adapters.
- Corrected the DNS configuration and verified domain name resolution and connectivity.

# Shared Folders & Access Control
- Created a shared folder on the Windows Server.
- Configured share permissions and NTFS security permissions.
- Used security-group membership to control access to shared resources.
- Tested access with a domain user to verify the intended permissions.

# Group Policy
- Created and linked a domain Group Policy Object (GPO).
- Configured an interactive logon policy setting.
- Ran `gpupdate /force` on the client to refresh Group Policy.

# Troubleshooting Process
During testing, domain name resolution initially failed because of DNS configuration on a virtual network adapter. I investigated the adapter settings, corrected the DNS configuration, and verified successful domain resolution and network connectivity. I also tested shared-folder access with and without the relevant security-group membership to confirm that permissions were working as intended.

# Project Evidence
Screenshots and supporting documentation demonstrate the server configuration, Active Directory structure, domain joining, DNS troubleshooting, shared-folder permissions, and Group Policy configuration.

# Purpose
This independent home lab was completed to develop practical skills relevant to entry-level IT support, help desk, and junior systems administration roles.
