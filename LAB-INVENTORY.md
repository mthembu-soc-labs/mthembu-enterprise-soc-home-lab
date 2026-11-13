# Enterprise SOC Home Lab — Inventory

## 1. Project Environment

| Component | Details |
|---|---|
| Virtualization platform | VMware Workstation Pro 17 |
| Host operating system | Windows 11 |
| Project type | Medium-sized enterprise simulation |
| Project owner | Mcebisi Mthembu |

## 2. Virtual Machine Inventory

| VM Name | Operating System | RAM | CPU | Disk | Purpose |
|---|---|---|---|---|---|
| DC01 | Windows Server 2022 | To document | To document | To document | Active Directory |
| CLIENT01 | Windows 10 Pro | To document | To document | To document | Employee workstation |
| WAZUH01 | Ubuntu Server | To document | To document | To document | SIEM |
| KALI01 | Kali Linux | To document | To document | To document | Security testing |

## 3. Network Configuration

| Device | IP Address | Purpose |
|---|---|---|
| DC01 | To document | Domain Controller |
| WAZUH01 | To document | SIEM |
| CLIENT01 | To document | Windows endpoint |
| KALI01 | To document | Security testing |

## 4. Installed Technologies

- VMware Workstation
- Windows Server 2022
- Windows 10 Pro
- Ubuntu Server
- Kali Linux
- Wazuh
- Nmap
- Wireshark
- Metasploit

## 5. Documentation Status

This inventory will be updated as configurations are completed and verified.

**Rule:** Only verified configurations and actual specifications will be recorded.


---

## 6. Physical Host Inventory

### Physical Host 1 – HOST01

| Component | Specification |
|---|---|
| Manufacturer | Dell |
| Model | Latitude E6530 |
| Operating System | Windows 10 Pro |
| OS Build | 19045 |
| Processor | Intel Core i7-3540M @ 3.00GHz |
| Physical Cores | 2 |
| Logical Processors | 4 |
| Installed RAM | 12 GB |
| Architecture | 64-bit |
| BIOS Version | Dell A22 |
| BIOS Mode | Legacy |
| Virtualization | Enabled |

### Host Responsibilities

This physical computer runs the following virtual machines:

- DC01 – Windows Server 2022
- CLIENT01 – Windows 10 Pro

### Virtualization Environment

- Hypervisor: VMware Workstation Pro 17
- Hardware-assisted virtualization: Enabled

