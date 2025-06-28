# MCSA Final Project – Enterprise IT Environment Simulation

This project simulates a real-world enterprise IT environment using Microsoft technologies, designed as part of my MCSA final project. It includes infrastructure for 600 users across 3 departments with realistic access control, group policies, printer management, and server configurations.

## Project Structure

- User Management (Sales, Marketing, HR – 200 users each)
- Group Policy Enforcement (software restrictions, drive access, UI lockdown)
- Printer Configuration (department-specific, time-restricted, priority-based)
- Storage Quotas and File Encryption (5GB/user, sensitive file protection)
- Servers Deployed:
  - Active Directory (with additional DCs)
  - File & Backup Servers
  - DHCP & DNS (with custom pools and domain blocking)
  - Internal Websites
  - WDS & WSUS
  - VPN Server

## Certificate Authority (Windows Server 2025)

Deployed an **Enterprise Certificate Authority** for enhanced security:
- Custom certificate templates for signature, encryption, and authentication
- IPsec integration for secure communication
- Advanced features: CRL, auto-renewal, auditing, RBAC
- Technologies used: ADCS, X.509, PowerShell, GPO

## Key Goals

- Reflect real-world system administration practices
- Apply Microsoft server technologies in a practical environment
- Implement enterprise-level security and access control

## What I Learned

- Designing scalable infrastructure for large organizations
- Enforcing security through GPO and server roles
- Managing digital identity with certificates and IPsec


