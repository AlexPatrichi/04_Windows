# 01 — Introduction to Windows Server

**University:** Solent University
**Course:** Network Applications 

## Overview

**Windows Server is a network operating system (NOS)** developed by Microsoft to manage and support computer networks within organisations.

Unlike a desktop operating system, which primarily serves an individual user, Windows Server is designed to provide centralised services and resources to multiple users and computers.

Windows Server enables communication, centralised data storage, resource sharing, and collaboration across users and locations.

Understanding Windows Server requires some knowledge of networking, network operating systems, network services, reliability, resilience and security.

## Network Fundamentals

A **computer network** is a collection of interconnected devices that communicate and share information, applications and resources.

Networks allow computers, servers, printers, and other devices to work together, making communication and resource sharing possible within an organisation.

Networks can range from a small Local Area Network (LAN) within an office to global networks connecting multiple geographical locations.

### Network Components
A typical business network includes:
- **Clients:** Computers that request access to resources or services.
- **Servers:** Systems that provide resources or services to clients.
- **Switches:** Devices that connect computers within a local network.
- **Routers:** Devices that forward traffic between different networks.
- **Network Interface Cards (NIC):** Hardware that enables a device to connect to a network.
- **Transmission Media:** Wired or wireless technologies used to transmit data between devices.
- **Protocols:** Rules that define how devices communicate and exchange information.

### How Network Communication Works

For devices to communicate, they must be connected through a network and use compatible communication protocols.

Several technologies make this possible:
- **IP Addressing:** Identifies network interfaces and enables packets to be delivered across IP networks.
- **TCP/IP:** A suite of protocols that supports communication between networked devices.
- **DNS (Domain Name System):** Translates domain names into IP addresses, allowing devices to locate network services.
- **DHCP (Dynamic Host Configuration Protocol):** Automatically provides devices with IP configuration, such as an IP address, subnet mask, default gateway, and DNS server addresses.

The **OSI (Open Systems Interconnection) model** provides a seven-layer conceptual framework for understanding network communication, from physical transmission to application-level services.

### Client–Server Architecture

Many business networks use a **client–server architecture**, where clients request resources or services from centralised servers.

For example, when an employee accesses a shared folder:
1. The client computer connects to the network.
2. It locates the file server using its network address or hostname.
3. The client establishes communication with the server.
4. The server checks the user's identity and applicable access permissions.
5. If access is authorised, the server provides the requested resource.

This architecture allows organisations to manage resources centrally rather than maintaining them separately on every workstation.

### Connection to Windows Server

Windows Server builds upon these networking principles to provide centralised services such as:

- User authentication and directory services.
- DNS and DHCP services.
- File and printer sharing.
- Centralised administration and security management.

**These networking principles form the foundation upon which Windows Server operates.**
