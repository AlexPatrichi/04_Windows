# Network Reliability and Resilience

**University:** Solent University  
**Course:** Network Applications  

## Overview

Organisations depend on reliable and resilient networks to maintain access to essential services, applications and shared resources.

Two important concepts are:

- **Network Reliability:** The ability of a network or service to operate correctly and consistently over time, with minimal failures.
- **Network Resilience:** The ability of a network to withstand disruptions, maintain essential operations where possible, and recover from failures.

Reliability focuses on **preventing or minimising failures**, while resilience focuses on **handling and recovering from disruptions**.

## Common Approaches

Several techniques help organisations improve network reliability and resilience:

- **Redundancy:** Providing alternative components, connections or services if one fails.
- **Fault Tolerance:** Designing systems to continue operating despite certain component failures.
- **Backups:** Maintaining recoverable copies of important data and configurations.
- **Monitoring:** Detecting faults, outages and performance problems.
- **Recovery Planning:** Establishing procedures for restoring services after disruptions.
- **Replication:** Maintaining copies of data across multiple systems to support availability and recovery.

These approaches can **reduce downtime, protect important information and support business continuity.**

## Common Network Risks

Networks and services can experience disruptions caused by:

- **Hardware Failures:** Malfunctioning servers, switches, routers or storage devices.
- **Power Failures:** Loss of electricity affecting network equipment and services.
- **Configuration Errors:** Incorrect settings that cause connectivity problems or service outages.
- **Malware and Ransomware:** Malicious software that can disrupt services or make data inaccessible.
- **Insider Threats:** Accidental or deliberate actions by authorised users that compromise systems or information.
- **Unpatched Systems:** Outdated software containing vulnerabilities that attackers may exploit.
- **Network Connectivity Failures:** Damaged cables, faulty equipment or internet service interruptions.

## Building Reliable Networks

Building a reliable network requires careful planning, appropriate infrastructure, regular maintenance and effective recovery procedures.

Important practices include:

- **Network Design:** Planning network topology, capacity and infrastructure to minimise failures and avoid single points of failure.
- **Redundant Infrastructure:** Using alternative network connections, switches, servers or power supplies to reduce service interruptions.
- **Regular Maintenance:** Keeping operating systems, firmware and network equipment updated and properly configured.
- **Network Monitoring:** Continuously checking network performance, availability and system health to identify problems early.
- **Backup and Disaster Recovery:** Maintaining reliable backups and tested recovery procedures to restore data and services after failures.
- **Security Measures:** Using firewalls, access controls and other protections to reduce the risk of attacks and service disruptions.
- **Documentation:** Maintaining accurate network diagrams, configurations and recovery instructions to support troubleshooting and administration.

A reliable network should be designed not only to minimise failures but also to maintain essential services and recover efficiently when disruptions occur.

## Windows Server and Resilience

Windows Server provides several technologies that can help improve service availability and recovery:

- **Distributed File System (DFS):** DFS Namespaces provides a unified way to access shared folders, while DFS Replication can maintain copies of folder data across multiple servers.
- **Failover Clustering:** Allows supported services and workloads to continue running on another cluster node when a node fails.
- **Windows Server Backup:** Provides backup and recovery capabilities for protecting important data and server configurations.
- **Windows Server Monitoring Tools:** Tools such as Event Viewer and Performance Monitor help administrators detect and investigate problems.

**Important:** Replication and redundancy do not automatically guarantee uninterrupted service. Availability depends on the infrastructure, configuration and recovery procedures.

## Summary

- **Reliability** describes how consistently a network operates without failures.
- **Resilience** describes how effectively a network withstands and recovers from disruptions.
- Redundancy, fault tolerance, backups, monitoring and recovery planning help maintain essential services.
- Windows Server provides technologies that support availability, monitoring and recovery.