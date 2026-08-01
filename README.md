# CCNP Enterprise Labs (GNS3)

A complete collection of **50+ CCNP Enterprise networking labs** built using **GNS3** and **real Cisco virtual platforms**.

These labs are designed with **progressive difficulty**, starting from core enterprise routing and switching concepts and advancing to complex enterprise architectures used in production environments.

The goal of this repository is to provide a practical learning path for:
- CCNP Enterprise (ENCOR)
- Network Engineers
- Infrastructure Engineers
- NOC Engineers
- Network Administrators
- Anyone wanting real-world Cisco Enterprise experience

---

# Repository Objectives

✔ Learn enterprise networking through hands-on labs
✔ Build real-world troubleshooting skills
✔ Understand how enterprise networks are designed
✔ Master Cisco routing and switching technologies
✔ Prepare for CCNP Enterprise certification
✔ Build a professional networking portfolio

---

# Lab Progression

The labs increase in complexity as you progress.

## Foundation
- Static Routing
- VLANs
- Trunking
- STP
- EtherChannel
- ACLs
- DHCP
- NAT

---

## Intermediate
- OSPF
- Multi-Area OSPF
- OSPF Stub Areas
- OSPF NSSA
- OSPF Virtual Links
- EIGRP
- EIGRP Stub
- Route Summarization

---

## Advanced
- BGP
- eBGP
- iBGP
- Route Redistribution
- Policy-Based Routing
- GRE Tunnel
- GRE over IPSec
- VRF Lite

---

## Enterprise Services
- HSRP
- VRRP
- GLBP
- Syslog
- NTP
- SNMP
- AAA
- DHCP Relay

---

## Security
- Standard ACL
- Extended ACL
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- IP Source Guard

---

## Enterprise Design
- Campus Network
- Branch Office
- ISP Connectivity
- WAN Redundancy
- High Availability
- Enterprise Routing
- Enterprise Switching

---

# Repository Structure

```
CCNP-Enterprise-Labs-GNS3/
├── README.md
├── Lab-01
├── Lab-02
├── Lab-03
│
├── ...
│
├── Lab-50
│
└── Images/
```

Every lab contains:
- Objective
- Network Topology
- IP Addressing
- Complete Configuration
- Verification Commands
- Troubleshooting
- Real-World Use Case
- Key Learning

---

# 📋 Complete Lab Index

| # | Lab Name | Category | Key Focus |
|---|----------|----------|-----------|
| Lab-01 | ♦ Static Routing Fundamentals | Foundation | Default & static routes |
| Lab-02 | ♦ VLAN Design & Configuration | Foundation | VLAN creation, port assignment |
| Lab-03 | ♦ 802.1Q Trunking | Foundation | Trunk links, native VLAN |
| Lab-04 | ♦ Spanning Tree Protocol (STP) | Foundation | Root bridge, port states |
| Lab-05 | ♦ EtherChannel (LACP/PAgP) | Foundation | Link aggregation |
| Lab-06 | ♦ Standard & Extended ACLs | Foundation | Traffic filtering |
| Lab-07 | ♦ DHCP Server Configuration | Foundation | Scopes, exclusions, relay |
| Lab-08 | ♦ NAT (Static, Dynamic, PAT) | Foundation | Address translation |
| Lab-09 | ♦ Inter-VLAN Routing (Router-on-a-Stick) | Foundation | Sub-interfaces |
| Lab-10 | ♦ Inter-VLAN Routing (SVI/Layer 3 Switch) | Foundation | SVIs, ip routing |
| Lab-11 | ♦ OSPF Single-Area Fundamentals | Intermediate | Neighbor adjacency, DR/BDR |
| Lab-12 | ♦ OSPF Multi-Area Design | Intermediate | ABR, area types |
| Lab-13 | ♦ OSPF Stub Areas | Intermediate | Stub, totally stubby |
| Lab-14 | ♦ OSPF NSSA | Intermediate | Type 7 LSAs |
| Lab-15 | ♦ OSPF Virtual Links | Intermediate | Area 0 continuity |
| Lab-16 | ♦ OSPF Authentication | Intermediate | MD5, SHA auth |
| Lab-17 | ♦ EIGRP Fundamentals | Intermediate | Neighbor formation, metrics |
| Lab-18 | ♦ EIGRP Stub Routing | Intermediate | Stub types |
| Lab-19 | ♦ EIGRP Route Summarization | Intermediate | Manual summarization |
| Lab-20 | ♦ EIGRP Unequal-Cost Load Balancing | Intermediate | Variance command |
| Lab-21 | ♦ eBGP Peering & Configuration | Advanced | AS numbering, neighbor setup |
| Lab-22 | ♦ iBGP Peering & Full Mesh | Advanced | Split-horizon, route reflectors |
| Lab-23 | ♦ BGP Path Selection | Advanced | Attribute-based best path |
| Lab-24 | ♦ BGP Route Filtering | Advanced | Prefix-lists, route-maps |
| Lab-25 | ♦ Route Redistribution (OSPF ↔ EIGRP) | Advanced | Seed metrics, loop prevention |
| Lab-26 | ♦ Route Redistribution (BGP ↔ IGP) | Advanced | Mutual redistribution |
| Lab-27 | ♦ Policy-Based Routing (PBR) | Advanced | Route-maps, path control |
| Lab-28 | ♦ GRE Tunnel Configuration | Advanced | Tunnel interfaces |
| Lab-29 | ♦ GRE over IPSec VPN | Advanced | Site-to-site encryption |
| Lab-30 | ♦ VRF-Lite Implementation | Advanced | Route isolation |
| Lab-31 | ♦ HSRP Configuration | Enterprise Services | Active/standby gateway |
| Lab-32 | ♦ VRRP Configuration | Enterprise Services | Master/backup gateway |
| Lab-33 | ♦ GLBP Configuration | Enterprise Services | Load-balanced gateway |
| Lab-34 | ♦ Syslog Centralized Logging | Enterprise Services | Log levels, server setup |
| Lab-35 | ♦ NTP Time Synchronization | Enterprise Services | Stratum, authentication |
| Lab-36 | ♦ SNMP Monitoring | Enterprise Services | Traps, community strings |
| Lab-37 | ♦ AAA (TACACS+/RADIUS) | Enterprise Services | Authentication, authorization |
| Lab-38 | ♦ DHCP Relay Across VLANs | Enterprise Services | IP helper-address |
| Lab-39 | ♦ Port Security | Security | MAC limiting, violation modes |
| Lab-40 | ♦ DHCP Snooping | Security | Trusted/untrusted ports |
| Lab-41 | ♦ Dynamic ARP Inspection (DAI) | Security | ARP spoofing prevention |
| Lab-42 | ♦ IP Source Guard | Security | Source address validation |
| Lab-43 | ♦ Rapid-PVST+ Convergence | Security | Fast STP convergence |
| Lab-44 | ♦ Campus Network Design | Enterprise Design | 3-tier architecture |
| Lab-45 | ♦ Branch Office Connectivity | Enterprise Design | Hub-and-spoke WAN |
| Lab-46 | ♦ ISP Multi-Homed Connectivity | Enterprise Design | Dual-ISP failover |
| Lab-47 | ♦ WAN Redundancy & Failover | Enterprise Design | Backup paths |
| Lab-48 | ♦ End-to-End High Availability Design | Enterprise Design | FHRP + routing convergence |
| Lab-49 | ♦ Full Enterprise Routing Integration | Enterprise Design | Multi-protocol environment |
| Lab-50 | ♦ Full Enterprise Switching Integration | Enterprise Design | Campus-wide L2/L3 design |

---

# Technologies Covered

### Routing
- Static Routing
- OSPF
- EIGRP
- BGP
- Route Redistribution

### Switching
- VLAN
- STP
- Rapid STP
- EtherChannel
- Inter-VLAN Routing

### High Availability
- HSRP
- VRRP
- GLBP

### WAN
- GRE Tunnel
- GRE over IPSec
- NAT
- Policy-Based Routing

### Network Services
- DHCP
- DNS
- Syslog
- SNMP
- NTP

### Security
- ACL
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- IP Source Guard

---

# Lab Environment

These labs were developed using:
- GNS3 2.2.55
- Linux (64-bit)
- VMware Workstation
- Cisco IOS / IOS XE virtual platforms

> Cisco IOS images are **not included** in this repository. You must supply your own appropriately licensed images before running the projects.

---

# Intended Audience

This repository is suitable for:
- CCNA graduates
- CCNP students
- Network Engineers
- Infrastructure Engineers
- NOC Engineers
- Anyone interested in enterprise networking

---

# Repository Status

🚧 Work in Progress

This repository is continuously updated with new labs, improvements, and troubleshooting notes.

Current Goal:
✅ 50+ Enterprise Labs

Future additions may include:
- MPLS
- VXLAN EVPN
- SD-WAN Concepts
- Segment Routing
- IPv6 Enterprise
- Automation (Python & Ansible)

---

# Author

**Shailesh Sahani**
Network Engineer
GitHub: https://github.com/ShaileshSahani

---

If this repository helps you in your CCNP journey, consider giving it a ⭐.