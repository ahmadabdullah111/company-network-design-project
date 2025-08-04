# Company Business System Network Design

This repository contains a Packet Tracer project file (`.pkt`) that represents a complete business system network design for a fictional company.

This repository contains a fully functional and professionally structured enterprise network design created using Cisco Packet Tracer. It simulates the networking infrastructure of a medium-sized business organization, including multiple departments, secure segmentation using VLANs, inter-VLAN routing, DHCP automation, and ISP-level internet integration.

The project is ideal for students, networking professionals, and instructors who are looking for real-world simulations of enterprise network topologies.

---

## 🎯 Project Goal

To design a scalable, secure, and efficient enterprise network infrastructure that reflects industry best practices. The network should support:

- Logical and physical segmentation of departments
- Efficient inter-departmental communication
- Scalable IP addressing and subnetting strategies
- Automated address distribution (DHCP)
- Secure and simplified access to external networks (internet)
- Device-specific static IP configuration
- Redundancy and clarity in topology design

---

## 🌐 Real-World Scenario

Imagine a growing company with the following departments:

- ✅ Administration  
- ✅ Human Resources  
- ✅ IT & Support  
- ✅ Finance  
- ✅ Sales  

Each department needs its own isolated subnet (VLAN) but should also be able to securely communicate with other departments when necessary. The network must connect to the Internet through an ISP router and support future expansion with minimal reconfiguration.

---

## 🔧 Tools & Technologies Used

| Category         | Tools / Protocols                            |
|------------------|-----------------------------------------------|
| Simulator        | Cisco Packet Tracer (version 8.2 recommended) |
| Network Layers   | Layer 2 Switching, Layer 3 Routing            |
| Protocols        | VLAN, DHCP, Static Routing, RIP (optional)   |
| Addressing       | Private IP Addressing with CIDR Subnetting    |
| Devices Used     | Routers, Switches, End Devices, Servers       |
| Config Techniques| CLI-Based Configuration on Cisco Devices      |

---

## 🧩 Core Features of the Network Design

- 🔹 **VLAN Configuration**: Each department is isolated into separate VLANs (VLAN 10, 20, 30, etc.).
- 🔹 **Router-on-a-Stick**: A single physical link between router and switch handles inter-VLAN routing using sub-interfaces.
- 🔹 **DHCP Server**: Specific VLANs receive IP addresses dynamically from a centralized DHCP server.
- 🔹 **Static IP Assignment**: Routers, core switches, and servers are assigned fixed IPs for stability.
- 🔹 **ISP Simulation**: Internet access is simulated via a separate ISP router connected to the company’s edge router.
- 🔹 **Proper Subnet Planning**: IPs are allocated based on the number of hosts required per department.
- 🔹 **Logical Topology**: Clean and labeled design for visual clarity and documentation.
- 🔹 **Scalability**: Design supports adding new departments or extending existing ones without overhauling the entire system.

---

## 🗂 File Contents

```plaintext
📁 enterprise-network-design-company-project/
 ┣ 📄 Company Business System Network Design (Project #6).pkt
 ┗ 📄 README.md

## ✍️ Author
Md. Abdullah Talukdar

## 📜 License
This project is for academic or demonstration purposes only.
