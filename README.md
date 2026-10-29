# windows-server-active-directory-lab
Windows Server 2022 Active Directory lab using VirtualBox

# Windows Server 2022 – Active Directory Home Lab

## Project Overview

This project demonstrates the setup and administration of a Windows Server 2022 Active Directory environment using Oracle VirtualBox.

The objective was to build a small Windows domain environment, manage users and groups, configure access permissions, and connect a Windows 11 client machine to the domain.

## Lab Environment

| Component | Configuration |
|---|---|
| Virtualisation Platform | Oracle VirtualBox |
| Server Operating System | Windows Server 2022 |
| Client Operating System | Windows 11 |
| Domain Controller | DC01 |
| Directory Service | Active Directory Domain Services |

## Tasks Completed

### 1. Active Directory Installation and Configuration
- Installed Active Directory Domain Services (AD DS).
- Promoted Windows Server 2022 to a Domain Controller.
- Configured the domain environment.

### 2. User and Group Management
- Created user accounts in Active Directory.
- Created security groups.
- Added users to relevant security groups.
- Reset user passwords.
- Unlocked locked user accounts.
- Enabled and disabled user accounts.
- Configured account expiration dates.

### 3. Domain Client Configuration
- Configured a Windows 11 virtual machine.
- Joined the Windows 11 machine to the Active Directory domain.
- Verified the client machine in Active Directory.
- Successfully logged in using a domain user account.

### 4. Shared Folder and Access Permissions
- Created a shared folder on the domain controller.
- Configured folder permissions for the IT Department security group.
- Tested folder access using a domain user account.
- Mapped the shared folder as a network drive on Windows 11.
- Verified access using the assigned user permissions.

## Skills Practised

- Windows Server 2022 Administration
- Active Directory Domain Services (AD DS)
- Domain Controller Configuration
- User and Group Management
- Account Administration and Troubleshooting
- Security Groups and Access Control
- NTFS and Shared Folder Permissions
- Network Drive Mapping
- Windows 11 Domain Integration
- Virtual Machine Management

## Project Outcome

Successfully built and tested a Windows domain environment using VirtualBox. Practised centralised user administration, domain authentication, group-based access control, and shared resource management between a Windows Server and Windows 11 client.

## Tools Used

- Oracle VirtualBox
- Windows Server 2022
- Windows 11
- Active Directory Users and Computers
- Group Policy Management
