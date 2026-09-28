Markdown

# Windows Server & Active Directory Enterprise Lab

## Project Overview
This project demonstrates the deployment and configuration of a simulated enterprise network environment using **Windows Server** and **Active Directory Domain Services (AD DS)**. The objective of this lab was to implement centralized identity management, configure organizational units (OUs), establish security groups, and enforce fine-grained access controls using Group Policy Objects (GPOs) and NTFS permissions.

---

## Tools & Technologies Used
* **Operating Systems:** Windows Server 2019/2022, Windows 10/11 Enterprise
* **Directory Services:** Active Directory Domain Services (AD DS)
* **Core Services:** DNS, DHCP, Group Policy Management (GPMC)
* **Virtualization:** VMware Workstation / VirtualBox / Hyper-V

---

## Key Implementation Steps

### 1. Active Directory & Domain Controller Setup
- Installed and promoted **Windows Server** to a Primary Domain Controller (DC).
- Configured **DNS** and **DHCP** server roles to automate network configuration and domain resolution for client workstations.

### 2. Organizational Unit (OU) & User Management
- Designed a structured hierarchy of **Organizational Units (OUs)** representing business departments (e.g., HR, IT, Finance, Sales).
- Created domain user accounts, administrative accounts, and standardized security groups following the **Least Privilege Principle**.

### 3. Permissions & Access Control (NTFS & Share Permissions)
- Created shared folder structures for departmental access.
- Applied **NTFS and Share permissions** to ensure sensitive files were accessible only by authorized security groups.

### 4. Group Policy Objects (GPOs)
- Configured and linked GPOs to enforce security baselines across organizational units.
- Implemented policies for password complexity, account lockout parameters, desktop restrictions, and mapped drive deployments.

---

## Verification & Testing
- Successfully joined Windows client workstations to the domain.
- Verified domain login functionality with non-administrative user accounts.
- Confirmed folder access restrictions and policy enforcement across test workstations.

---

## Skills Demonstrated
* Active Directory Administration & User Provisioning
* Access Control & Least Privilege Model
* System Administration & Security Hardening
* Network Troubleshooting (DNS/DHCP verification)
