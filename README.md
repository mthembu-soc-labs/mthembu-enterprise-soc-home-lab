# Enterprise SOC Home Lab

**Enterprise Security Operations Centre (SOC) Home Lab**

A practical cybersecurity project documenting the design, deployment, configuration, monitoring, testing, and investigation of a simulated enterprise IT environment.

The lab integrates Windows Server, Active Directory, Linux infrastructure, Wazuh SIEM, and security testing tools to develop practical IT and cybersecurity operations skills.

---

## Project Overview

This project simulates the IT infrastructure of a medium-sized enterprise.

The objective is to gain hands-on experience in enterprise infrastructure administration, security monitoring, threat detection, log analysis, security investigations, and incident response.

All configurations, practical exercises, troubleshooting activities, and investigation results are documented throughout the project.

## Lab Infrastructure

| System | Operating System | Primary Role |
|---|---|---|
| DC01 | Windows Server 2022 | Domain Controller |
| CLIENT01 | Windows 10 Pro | Employee Workstation |
| WAZUH01 | Ubuntu Server | SIEM Monitoring Server |
| KALI01 | Kali Linux | Security Testing |
| HOST | Windows 11 | Virtualization Platform |

## Technologies and Tools

- VMware Workstation Pro
- Windows Server 2022
- Windows 10 Pro
- Ubuntu Server
- Kali Linux
- Active Directory Domain Services
- DNS
- Wazuh SIEM
- Wireshark
- Nmap
- PowerShell
- Linux Administration

## Project Objectives

- Design and build a simulated enterprise network.
- Deploy and administer Windows Server infrastructure.
- Configure Active Directory Domain Services.
- Implement centralized security monitoring using Wazuh SIEM.
- Monitor Windows and Linux endpoints.
- Generate and investigate security events.
- Perform authorized security testing.
- Develop incident detection and response procedures.
- Document technical configurations, troubleshooting, and findings.

## Project Documentation

| No. | Documentation Area | Description |
|---|---|---|
| 01 | [Network Infrastructure](01-Network-Infrastructure/) | Network design and configuration |
| 02 | [Windows Server & Active Directory](02-Windows-Server-Active-Directory/) | Domain services and user management |
| 03 | [Linux Server Infrastructure](03-Linux-Server-Infrastructure/) | Ubuntu server configuration |
| 04 | [Wazuh SIEM](04-Wazuh-SIEM/) | SIEM deployment and configuration |
| 05 | [Security Monitoring](05-Security-Monitoring/) | Log analysis and threat detection |
| 06 | [Incident Response](06-Incident-Response/) | Security investigations and response |
| 07 | [Security Testing](07-Security-Testing/) | Authorized security testing |
| 08 | [Screenshots & Evidence](08-Screenshots/) | Practical implementation evidence |
| 09 | [Technical Reports](09-Reports/) | Technical findings and reports |
| 10 | [Lessons Learned](10-Lessons-Learned/) | Challenges and lessons learned |

## Project Progress

This repository is continuously updated as infrastructure is deployed, tested, and documented.

| Project Component | Status |
|---|---|
| Virtual Machine Deployment | Completed |
| Network Infrastructure | In Progress |
| Windows Server & Active Directory | In Progress |
| Linux Server Infrastructure | In Progress |
| Wazuh SIEM | In Progress |
| Security Monitoring | Planned |
| Incident Response | Planned |
| Security Testing | Planned |
| Technical Reporting | In Progress |

## Learning Outcomes

The project aims to demonstrate practical capabilities in:

- Enterprise IT infrastructure administration.
- Active Directory and Windows administration.
- Linux server management.
- SIEM deployment and administration.
- Security event monitoring and log analysis.
- Threat detection and investigation.
- Incident response fundamentals.
- Network security and authorized penetration testing.

## Disclaimer

This is an educational cybersecurity lab. All security testing is performed exclusively on systems owned by me or where explicit authorization has been granted.

No production systems or unauthorized third-party networks are intentionally targeted.

---

*Documenting the journey from infrastructure configuration to practical SOC operations.*
