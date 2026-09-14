# Active Directory Security Lab

## Overview

This project documents the construction of a small Windows-based
Active Directory environment for cybersecurity and system
administration practice.

## Objectives

- Build a Windows Server 2025 domain controller
- Configure Active Directory Domain Services
- Configure DNS
- Create and manage users and security groups
- Implement Group Policy security controls
- Join a Windows 11 client to the domain
- Practice troubleshooting and security monitoring

## Lab Environment

### Domain Controller
- OS: Windows Server 2025
- Role: Domain Controller
- Services: Active Directory Domain Services, DNS
- IPv4: 10.0.2.10
- Domain: homelab.local

### Client
- OS: Windows 11
- Purpose: Domain-joined workstation

## Completed Work

### 1. Windows Server Setup
- Installed Windows Server 2025
- Configured a static IPv4 address
- Configured networking for the lab environment

### 2. Active Directory
- Installed Active Directory Domain Services
- Promoted the server to a domain controller
- Created the `homelab.local` domain

### 3. DNS
- Installed the DNS Server role
- Configured DNS as part of the Active Directory environment

## Current Progress

- [x] Windows Server 2025 installed
- [x] Static IP configured
- [x] AD DS installed
- [x] DNS installed
- [x] Domain controller configured
- [ ] Organizational Units
- [ ] Security groups
- [ ] Test users
- [ ] Group Policy
- [ ] Windows 11 domain join
- [ ] Security monitoring
- [ ] Incident investigations

## Lessons Learned

This section will be updated throughout the project with
troubleshooting experiences, configuration decisions, and
security observations.

## Future Improvements

- Implement centralized security monitoring
- Analyze Windows security events
- Simulate controlled security incidents
- Document incident response procedures
- Incorporate Bad Blood to simulate a real world network
