# 🏦 Northbridge Savings & Finance – Enterprise Network Security Upgrade

![Project](https://img.shields.io/badge/Project-Academic%20Group%20Project-blue)
![Team](https://img.shields.io/badge/Team-4%20Members-success)
![Module](https://img.shields.io/badge/Module-IE3122-orange)
![Institution](https://img.shields.io/badge/Institution-SLIIT-red)
![Tool](https://img.shields.io/badge/Tool-Cisco%20Packet%20Tracer-blue)

## 📌 Project Information

| Category | Details |
|---|---|
| Project | Northbridge Savings & Finance – Network Security Upgrade |
| Module | IE3122 – Network Security |
| Institution | Sri Lanka Institute of Information Technology (SLIIT) |
| Degree | BSc (Hons) in Information Technology – Cyber Security |
| Project Type | Academic Group Project |
| Team Size | 4 Members |
| Practical Tool | Cisco Packet Tracer |

---
 📖 1. Project Overview

This project focuses on designing and implementing a comprehensive network security upgrade for **Northbridge Savings & Finance**, a fictional mid-sized regional financial institution.

As a four-member IT security consulting team, we analyzed the organization's existing network security weaknesses and proposed a layered security architecture to protect critical banking infrastructure, customer databases, employees, branch networks, and third-party payment integrations.

The existing environment presented several security challenges:

- Flat and unsegmented network architecture.
- Lack of Multi-Factor Authentication (MFA).
- Shared VPN accounts and inadequate remote access security.
- Insufficient network access control.
- Potential ransomware and lateral movement risks.
- Third-party payment integration security concerns.
- Lack of centralized monitoring and intrusion detection.

Our solution combines threat modeling, security control planning, technology evaluation, enterprise network architecture, and practical Cisco Packet Tracer configurations.

## 🎯 2. Project Objectives

- Identify and assess security threats affecting financial infrastructure.
- Develop a risk-based network security strategy.
- Evaluate suitable VPN, AAA, firewall architecture, and IDS/IPS technologies.
- Design a secure multi-zone enterprise network.
- Implement network hardening configurations using Cisco Packet Tracer.
- Demonstrate defense-in-depth and restricted network access.

## 🛠️ 3. Technologies and Tools Evaluated

| Category | Selected Solution | Other Evaluated Technologies |
|---|---|---|
| VPN | Cisco AnyConnect | OpenVPN, WireGuard, IPsec |
| AAA | FreeRADIUS + LDAP | Cisco ISE, Windows NPS, Keycloak |
| Network Architecture | Zone-Based Firewall | DMZ + Dual-Firewall, Micro-Segmentation, Zero Trust |
| IDS/IPS | Suricata | Snort, Cisco Firepower, Zeek |
| Network Simulation | Cisco Packet Tracer | — |

*Note: The selected solutions represent the group's technology evaluation decisions. They should not be interpreted as all being deployed in the Packet Tracer simulation.*

## 👥 4. Team Members and Individual Contributions

This project was completed collaboratively by four members. Each member was responsible for two threat models, four technology proposals, and two individual Packet Tracer configuration tasks.

### 👨‍💻 Member 1 – Repository Owner / Group Leader

**Student ID:** IT24300015

**Threat Modeling**
- T1: Ransomware via Unsegmented Branch Workstation.
- T2: Shared VPN Account Abuse.

**Individual Technology Proposals**
- VPN: OpenVPN.
- AAA: Cisco ISE.
- Architecture: Zone-Based Firewall.
- IDS/IPS: Snort.

**Packet Tracer Configurations**
- VLAN Segmentation and Inter-VLAN ACL on Core Switch.
- SSH Secure Management.

### 👨‍💻 Member 2

**Student Name:** [Insert Member 2 Name]  
**Student ID:** [Insert Student ID]  
**GitHub:** [Insert GitHub Profile URL]

**Threat Modeling**
- T3: Phishing and Credential Theft.
- T4: Third-Party Payment Integration Compromise.

**Individual Technology Proposals**
- VPN: WireGuard.
- AAA: FreeRADIUS + LDAP.
- Architecture: DMZ + Dual-Firewall.
- IDS/IPS: Suricata.

**Packet Tracer Configurations**
- Switch Port Security.
- DHCP Snooping.

### 👨‍💻 Member 3

**Student Name:** [Insert Member 3 Name]  
**Student ID:** [Insert Student ID]  
**GitHub:** [Insert GitHub Profile URL]

**Threat Modeling**
- T5: Unauthorized Database Access.
- T6: Data Loss Due to Untested Backups.

**Individual Technology Proposals**
- VPN: Cisco AnyConnect.
- AAA: Windows NPS.
- Architecture: Micro-Segmentation.
- IDS/IPS: Cisco Firepower.

**Packet Tracer Configurations**
- Inter-VLAN ACL on Firewall.
- DHCP Snooping on Access Switch.

### 👨‍💻 Member 4

**Student Name:** [Insert Member 4 Name]  
**Student ID:** [Insert Student ID]  
**GitHub:** [Insert GitHub Profile URL]

**Threat Modeling**
- T7: Online Banking Portal Attack (SQL Injection / XSS).
- T8: Unmanaged BYOD Endpoint Compromise.

**Individual Technology Proposals**
- VPN: IPsec Site-to-Site.
- AAA: Keycloak.
- Architecture: Zero Trust.
- IDS/IPS: Zeek.

**Packet Tracer Configurations**
- Dynamic ARP Inspection (DAI).
- AAA Local Authentication.

## 🛡️ 5. Combined Layered Security Plan

The team developed a unified security strategy containing 16 broad, multi-purpose security controls.

The controls were designed to address multiple threats while maintaining an efficient security architecture.

**Main security control categories include:**

- Network Segmentation.
- Next-Generation Firewall (NGFW).
- Multi-Factor Authentication (MFA).
- Third-Party Vendor Assessment.
- IDS/IPS.
- Endpoint Security.
- Security Awareness Training.
- Centralized AAA.
- Centralized Security Logging.
- Data Classification.
- Backup and Disaster Recovery.
- Incident Response.

*The complete 16-control mapping and threat relationships are documented in the final project report.*

## 🏗️ 6. Enterprise Network Architecture

The proposed network follows a multi-zone security architecture to reduce unauthorized access and lateral movement.

**Designed network zones:**

1. DMZ – Public-facing services.
2. User Zone – Employee workstations.
3. Server Zone – Application servers.
4. Database Zone – Critical banking databases.
5. Management Zone – Network administration.
6. Branch Zone – Branch office connectivity.
7. Third-Party Zone – External payment integration.

The architecture applies network segmentation, firewall enforcement, controlled communication paths, and defense-in-depth principles.

## ⚙️ 7. Cisco Packet Tracer Implementation

The practical component focused on network hardening, access control, and secure network management.

**Eight individual configuration tasks:**

| No. | Configuration | Responsible Member |
|---|---|---|
| 1 | VLAN Segmentation + Inter-VLAN ACL | Member 1 |
| 2 | SSH Secure Management | Member 1 |
| 3 | Switch Port Security | Member 2 |
| 4 | DHCP Snooping | Member 2 |
| 5 | Inter-VLAN ACL on Firewall | Member 3 |
| 6 | DHCP Snooping on Access Switch | Member 3 |
| 7 | Dynamic ARP Inspection (DAI) | Member 4 |
| 8 | AAA Local Authentication | Member 4 |

**Security objectives demonstrated:**

- Restricting unauthorized inter-VLAN communication.
- Securing network device management.
- Preventing unauthorized device connections.
- Reducing DHCP spoofing risks.
- Mitigating ARP spoofing and related MITM attacks.
- Improving authentication and accountability.

## 📂 8. Repository Structure

```text
Northbridge-Network-Security/
│
├── README.md
│
├── Report/
│   └── Northbridge_Network_Security_Final_Report.pdf
│
├── Packet_Tracer_Files/
│   └── Northbridge_Enterprise_Network_Topology.pkt
│
├── Screenshots/
│   ├── Network_Topology/
│   ├── VLAN_ACL/
│   ├── SSH_Management/
│   ├── Port_Security/
│   ├── DHCP_Snooping/
│   ├── DAI/
│   ├── AAA/
│   └── Verification/
│
└── Documentation/
    ├── Threat_Modeling/
    ├── Technology_Evaluation/
    ├── Security_Architecture/
    └── Layered_Security_Plan/
```

## 📸 9. Project Evidence

Screenshots and verification evidence will be organized into the `Screenshots/` directory.

The evidence will demonstrate:

- Overall network topology.
- VLAN and ACL configuration.
- SSH management configuration.
- Port security configuration.
- DHCP Snooping and DAI.
- AAA authentication.
- Network connectivity and access-control verification.

## 📚 10. Learning Outcomes

Through this collaborative project, we developed practical knowledge and experience in:

- Enterprise Network Security Design.
- Threat Modeling and Risk Assessment.
- Network Segmentation and Access Control.
- Firewall and IDS/IPS Technology Evaluation.
- Authentication, Authorization and Accounting.
- Network Hardening.
- Defense-in-Depth Architecture.
- Cisco Packet Tracer Network Simulation.
- Technical Documentation and Team Collaboration.

## ⚠️ 11. Disclaimer

This project was developed for academic and educational purposes as part of the IE3122 Network Security module at SLIIT.

Northbridge Savings & Finance is a fictional organization used for the assignment scenario. The proposed security architecture and simulated configurations are intended for educational demonstration.

## 🙌 Acknowledgements

We would like to thank our lecturers and team members for their guidance, collaboration, and contributions throughout this project.

---

**Developed as part of the BSc (Hons) in Information Technology – Cyber Security degree programme at the Sri Lanka Institute of Information Technology (SLIIT).**
