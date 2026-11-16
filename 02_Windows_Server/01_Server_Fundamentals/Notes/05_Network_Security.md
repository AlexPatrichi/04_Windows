# Network Security

**University:** Solent University  
**Course:** Network Applications  

## Overview

**Network security** refers to the technologies, policies and practices used to protect networks, systems, services and information against unauthorised access, modification, disclosure and disruption.

Its purpose is to ensure that network resources remain secure, trustworthy and available to authorised users.

## CIA Triad

The **CIA Triad** is a fundamental information security model based on three principles:

| Principle | Description |
|---|---|
| **Confidentiality** | Ensures information is accessible only to authorised users and systems. |
| **Integrity** | Ensures information remains accurate, complete and protected against unauthorised modification. |
| **Availability** | Ensures systems, services and information remain accessible when required. |

These principles guide organisations when designing and implementing network security measures.

## Network Security Controls

Several security controls help protect networks and their resources:

- **Authentication:** Verifies the identity of users, computers and other entities.
- **Authorisation:** Determines which resources or actions an authenticated identity is permitted to access.
- **Access Permissions:** Control access to files, folders, applications and other resources.
- **Firewalls:** Monitor and filter network traffic according to configured security rules.
- **Encryption:** Protects information by converting it into a form that cannot be understood without the appropriate decryption key.
- **Security Policies:** Define and enforce organisational security requirements.
- **Logging and Auditing:** Record security-related events to support monitoring, investigation and accountability.

## Principle of Least Privilege

The **principle of least privilege (PoLP)** means granting users, applications and systems only the permissions necessary to perform their required tasks.

This reduces the risk of unauthorised access, accidental changes and damage caused by compromised accounts.

**Example:**
A Sales employee should have access to the Sales department's shared folders but should not automatically receive access to confidential Finance records.

## Common Network Security Threats

Networks can be exposed to various security threats, including:

- **Malware and Ransomware:** Malicious software designed to damage systems, steal information or make data inaccessible.
- **Phishing:** Deceptive messages intended to trick users into revealing credentials or other sensitive information.
- **Unauthorised Access:** Access to systems or resources without appropriate permission.
- **Denial-of-Service (DoS) Attacks:** Attempts to disrupt the availability of network services.
- **Insider Threats:** Accidental or deliberate actions by authorised individuals that compromise security.
- **Unpatched Vulnerabilities:** Software weaknesses that attackers may exploit when security updates are not applied.

## Secure Network Practices

Organisations can improve network security by following established practices:

- **Strong Authentication:** Use strong passwords and multi-factor authentication (MFA) where supported.
- **Account Protection:** Configure appropriate account lockout or rate-limiting policies to reduce password-guessing attacks.
- **Patch Management:** Regularly update operating systems, applications and network equipment.
- **Least Privilege:** Restrict access according to users' responsibilities.
- **Disable Unnecessary Services:** Reduce the attack surface by removing or disabling unused services and features.
- **Firewall Configuration:** Allow only the network traffic required for legitimate operations.
- **Monitoring and Auditing:** Review security logs and investigate suspicious activity.
- **Backup and Recovery:** Maintain protected backups and test recovery procedures to reduce the impact of incidents.

## Network Security in Windows Server

Windows Server provides technologies that help administrators implement and manage network security:

- **Active Directory Domain Services (AD DS):** Supports centralised identity management and domain authentication.
- **Group Policy:** Enables centralised configuration of security settings for domain users and computers.
- **Windows Defender Firewall:** Controls inbound and outbound network traffic through configurable rules.
- **NTFS Permissions:** Control access to files and folders stored on NTFS volumes.
- **Microsoft Defender Antivirus:** Helps detect and protect against malware.
- **Event Viewer:** Provides access to system and security event logs for troubleshooting and auditing.

These technologies help administrators apply consistent security controls across an organisation.

## Summary

- **Network security** protects network infrastructure, services and information against threats and unauthorised activities.
- The **CIA Triad** defines the three fundamental principles of confidentiality, integrity and availability.
- Authentication, authorisation, permissions, firewalls and encryption are important security controls.
- The **principle of least privilege** reduces security risks by limiting unnecessary access.
- Regular updates, monitoring, secure configurations and recovery planning help maintain a secure network environment.