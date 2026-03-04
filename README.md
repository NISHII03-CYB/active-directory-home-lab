# active-directory-home-lab
# Active Directory Home Lab Implementation & Security Monitoring

## Overview

This project demonstrates the implementation of a simulated enterprise network environment using Active Directory. The lab environment was designed to understand identity management, domain infrastructure, and security monitoring concepts used in real-world enterprise networks.

The lab replicates a small corporate environment consisting of a domain controller, domain-joined workstation, and an attacker machine used to simulate authentication activity. Security logs generated in the environment can be analyzed to understand how SOC analysts monitor authentication events.

---

## Project Objectives

The main objectives of this project were:

- Build an Active Directory home lab environment
- Deploy a Windows Server domain controller
- Configure domain services and DNS
- Create and manage domain users and groups
- Join client machines to the domain
- Generate authentication events
- Analyze Windows Security logs
- Understand how SOC analysts monitor authentication activity

---

## Technologies Used

- VirtualBox
- Windows Server
- Windows 10
- Kali Linux
- Active Directory Domain Services (AD DS)
- DNS
- Windows Security Logs

---

## Lab Architecture

The lab environment simulates a small enterprise network consisting of three systems:

| Machine | Role |
|-------|------|
| Windows Server | Domain Controller |
| Windows 10 | Domain Client |
| Kali Linux | Attacker Machine |

All machines are connected through an internal virtual network.
