# Project 1: Active-Directory-and-Domain-Controller-Setup
This project demonstrates the design, deployment, and management of a complete on-premises infrastructure in a simulated enterprise environment. It showcases practical skills in:
- Active Directory Domain Services (ADDS) and domain controller setup
- Organizational Unit (OU) and user management
- Group Policy configuration
- File and Print Server deployment
- DNS, DHCP, and VPN setup
- Delegated user permissions and identity and access management
- Network drive mapping
- PowerShell automation
The project provides hands-on experience with enterprise-grade infrastructure, emphasizing real-world scenarios and best practices for managing users, devices, and services in an on-prem environment.

Key features include:

- Domain Controller Deployment: Installing Active Directory Domain Services and configuring a new forest/domain.

- OU and User Management: Creating parent and child OUs, adding users, and organizing accounts by department.

- Group and Permission Management: Creating security groups and assigning users to manage access to shared resources.

- DNS and DHCP Server Deployment and Management: Configuring DNS zones, DHCP scopes, and managing IP address allocation and name resolution for the network.

- File Server Configuration: Setting up RAID-5 volumes, sharing departmental and private folders, and mapping home and shared drives.
  
- Print Server Deployment and Management: Installing and configuring print servers, deploying printers, and managing access through Group Policy.

- Group Policy Automation: Using GPOs to map network drives, deploy printers, enforce security settings, configure user environments, and apply policies for specific OUs.
  
- PowerShell Automation: Bulk user creation with predefined properties, OU placement, and group membership.

- Troubleshooting Scenarios: Identifying and resolving common issues like login failures, drive mapping errors, printer access problems and permission conflicts.

This project provides a complete, hands-on experience in designing, deploying, and managing an enterprise on-premises infrastructure. It covers the full spectrum of Windows Server administration, including Active Directory and domain controller setup, OU and user management, group and permission configuration, file and print server deployment, DNS and DHCP server management, Group Policy automation, network drive and printer mapping, PowerShell automation, and troubleshooting real-world issues. By completing this project, users gain practical, end-to-end skills in enterprise IT administration, preparing them to confidently manage and support complex Windows Server environments.

# Project 2: Project 2: Exchange Server Deployment and Configuration

# This project demonstrates the deployment, configuration, and validation of Microsoft Exchange Server in an Active Directory based enterprise environment. It builds on the Active Directory and Domain Controller infrastructure by integrating Exchange Server to provide secure internal and external email communication.

# Key features include:

- Exchange Server Preparation: Configuring static IP addressing, server hostname, domain membership, and DNS settings to ensure proper communication with the Domain Controller.

- Prerequisite Configuration: Installing required Windows updates, Exchange prerequisites, and preparing a dedicated storage drive for Exchange databases and logs.

- Exchange Server Installation: Mounting the Exchange Server installation media, running setup with administrative privileges, selecting the Exchange organization name, specifying a custom installation path, and completing the installation process.

- Service Validation: Verifying that all Microsoft Exchange services are running correctly and restarting services if required.

- Web Access Verification: Accessing Exchange Control Panel (ECP) and Outlook Web Access (OWA) to confirm successful deployment and mailbox accessibility.

- Active Directory Integration: Ensuring Exchange Server functionality through proper communication with the Domain Controller for authentication, directory services, and DNS resolution.

This project demonstrates practical experience with enterprise email server deployment, Active Directory integration, DNS configuration, and post-installation verification. It complements the Active Directory project and showcases real-world skills required for system administration, messaging infrastructure management, and enterprise IT support.
