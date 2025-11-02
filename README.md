# Urban Mart Network Simulation (Cisco Packet Tracer)

This project was developed as part of my **Computer Networks Lab** to design, configure, and simulate a reliable, scalable, and secure network for **Urban Mart**, consisting of a main site and a branch office connected through WAN using **Cisco Packet Tracer**.

## 🧩 Project Overview
The network includes routers, switches, PCs, printers, and servers configured for end-to-end connectivity and secure inter-departmental communication. VLANs, ACLs, and routing protocols ensure segmentation, control, and redundancy.

## 🎯 Project Objectives
- Design a scalable LAN architecture for both main and branch sites.
- Configure DHCP, DNS, and HTTP servers.
- Implement VLANs for Sales, Inventory, IT, Management, and Guest departments.
- Apply ACLs and port security for network protection.
- Establish inter-site routing using OSPF/RIP.
- Simulate and test connectivity for validation.

## 🖥️ Tools and Technologies
- **Simulation Tool:** Cisco Packet Tracer  
- **Routers:** Cisco 2911  
- **Switches:** Catalyst 2960 & 3650  
- **Protocols:** DHCP, DNS, HTTP, VLANs, OSPF/RIP, ACLs, Port Security  
- **Devices:** PCs, Printers, Servers, and Cloud for WAN simulation

## 🧠 Network Topology
- **Main Site:** Router, Distribution & Access Switches, PCs (pc_0–pc_4), Printers (printer_0–printer_3)
- **Branch Site:** Router, Distribution & Access Switches, PCs (pc_5–pc_8), Printers (printer_4–printer_7)
- **Cloud:** Simulates WAN between main and branch routers

## 🗂️ VLAN Configuration
| VLAN | Department | IP Range | Gateway |
|------|-------------|-----------|----------|
| 10 | Management | 192.168.10.0/24 | 192.168.10.1 |
| 20 | Sales | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Inventory | 192.168.30.0/24 | 192.168.30.1 |
| 40 | IT | 192.168.40.0/24 | 192.168.40.1 |
| 50 | Guest Wi-Fi | 192.168.50.0/24 | 192.168.50.1 |

## 🕒 Project Timeline
- Requirements & Design – 2 days  
- Configuration – 3 days  
- Testing & Validation – 2 days  
- Documentation – 1 day  

## ✅ Outcomes
- Complete two-site network simulation  
- Functional inter-VLAN routing and WAN connectivity  
- Security enforced through ACLs and VLAN segmentation  
- Scalable architecture suitable for real-world deployment  

---

### 📁 File
- `UrbanMart_Network.pkt` — open in Cisco Packet Tracer to explore the simulation.
