# Network Services

**University:** Solent University  
**Course:** Network Applications  

## Overview

A **network service** is a function provided by a computer, server or network device that allows other devices and users to access resources, exchange information or perform specific tasks over a network.

Network services are essential to business networks because they support communication, resource sharing, authentication and centralised administration.

A server can host multiple network services, and a network service can also be distributed across multiple servers.

## Common Network Services

The following services are commonly used in business networks:

| Network Service | Description |
|---|---|
| **DNS (Domain Name System)** | Resolves domain names and hostnames into IP addresses, allowing devices to locate network resources. |
| **DHCP (Dynamic Host Configuration Protocol)** | Automatically assigns IP configuration to network devices, including IP addresses, subnet masks, default gateways and DNS servers. |
| **Directory Services** | Store and organise information about users, groups, computers and other network resources. |
| **Authentication Services** | Verify the identity of users and devices before granting access to protected systems. |
| **File Services** | Allow users to store, access and share files across a network. |
| **Print Services** | Enable multiple users and computers to access shared printers. |
| **Web Services** | Deliver websites, web applications and other resources using protocols such as HTTP and HTTPS. |
| **Remote Access Services** | Allow authorised users and administrators to connect to systems and resources remotely. |

## How Network Services Work Together

Network services often depend on one another to provide a complete working environment.

For example, when an employee signs in to a domain-joined Windows computer and accesses a shared folder:

1. **DHCP** may provide the computer with its IP configuration.
2. **DNS** helps the computer locate a domain controller and other network resources.
3. **Active Directory Domain Services (AD DS)** supports domain authentication and provides directory information.
4. **File Services (SMB)** enable communication with the shared folder.
5. **Access permissions** determine whether the employee can read, modify or access the requested files.

This demonstrates how several network services cooperate to provide secure access to organisational resources.

## Network Services in Windows Server

Windows Server can host and manage network services through **server roles and features**.

- **Server Role:** Provides a primary function or service within a network.
- **Server Feature:** Adds functionality or administrative capabilities to the operating system.

### Common Windows Server Roles

- **DNS Server:** Provides DNS name resolution.
- **DHCP Server:** Provides automatic IP configuration.
- **Active Directory Domain Services (AD DS):** Provides directory and domain authentication services.
- **File and Storage Services:** Supports file sharing and storage management.
- **Print and Document Services:** Supports shared printing.
- **Web Server (IIS):** Hosts websites and web applications.

### Common Windows Server Features

- **Group Policy Management:** Provides tools for creating, editing and managing Group Policy Objects (GPOs).
- **Windows Server Backup:** Provides backup and recovery capabilities.
- **BitLocker Drive Encryption:** Protects stored data through volume encryption.
- **Failover Clustering:** Enables multiple servers to work together to improve service availability.
- **.NET Framework Features:** Provides components required by certain applications and server services.

Not every Windows Server installation requires all these roles and features. Administrators install and configure them according to the organisation's requirements.

## Summary

- **Network services** provide the functions that allow users, computers and applications to communicate, access resources and operate across a network.
- Services such as DNS, DHCP, directory services and file sharing form an important part of modern business networks.
- Windows Server provides roles and features that allow administrators to deploy and manage these services according to organisational needs.