# waystar-royco-network-/
Enterprise Media Company/
# Waystar Royco — Enterprise Network Design

> Two-site enterprise network for **Tulsa, OK** and **Kansas City, MO**, designed and built in **Cisco Packet Tracer**.
> Goal: a secure, segmented, fully redundant network with **no single point of failure**.

---

## 📋 Project Overview

| Item | Detail |
|---|---|
| **Company** | Waystar Royco (media) |
| **Sites** | Tulsa, OK · Kansas City, MO |
| **Departments per site** | Finance & Accounting · Human Resources · Legal & Compliance |
| **Users** | ~25 per department → ~75 per site |
| **Endpoints** | PCs, laptops, tablets, IP phones, mobile devices, printers |
| **Servers** | Centralized server at each site |
| **Design goal** | No single point of failure, department segmentation, secure Wi-Fi on every floor |
| **Lab platform** | Cisco Packet Tracer |

---

## 🛠️ Technologies

| Area | Technologies |
|---|---|
| **Switching** | VLANs, trunks (802.1Q), SVIs, STP |
| **Redundancy** | HSRP, dual uplinks, redundant links |
| **Routing** | OSPF, static routes |
| **WAN** | Site-to-site link Tulsa ↔ Kansas City |
| **Edge** | NAT, PAT, firewalls (Cisco ASA) |
| **Services** | DHCP, DNS, web server |
| **Wireless** | WLC, lightweight APs, WPA2/WPA3 encryption |
| **Security** | Network segmentation, ACLs, device hardening |

---

## 🗺️ Topology

_Diagram coming in Phase 2._

<!-- ![Topology](diagrams/topology.png) -->

---

## 📁 Repository Structure

```
waystar-royco-network/
├── README.md
├── docs/
│   ├── 01-requirements.md
│   ├── 02-site-survey-kc.md
│   ├── 03-hld.md            # High-Level Design
│   ├── 04-lld.md            # Low-Level Design
│   ├── 05-test-plan.md
│   └── change-log.md
├── diagrams/                # draw.io files + PNG exports
├── ip-plan/                 # IP plan, VLAN table, inventory (Excel)
├── configs/
│   ├── tulsa/               # one config file per device
│   └── kansas-city/
└── packet-tracer/           # .pkt lab file
```

---

## 🚧 Project Status

| Phase | Description | Status |
|---|---|---|
| 0 | Requirements | 🟡 In progress |
| 1 | Site survey (Kansas City) | ⬜ Not started |
| 2 | High-level design | ⬜ Not started |
| 3 | IP addressing + VLAN plan | ⬜ Not started |
| 4 | Wireless design | ⬜ Not started |
| 5 | Security design | ⬜ Not started |
| 6 | Network services | ⬜ Not started |
| 7 | Build (Packet Tracer) | ⬜ Not started |
| 8 | Testing + failover tests | ⬜ Not started |
| 9 | Documentation + handover | ⬜ Not started |

**Legend:** ✅ Done · 🟡 In progress · ⬜ Not started

---

## 👤 Author

**Julio Cesar Zamora Ramirez** — [GitHub](https://github.com/Juliozed)    
