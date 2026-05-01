# Healthcare Telemedicine Network 🏥

A simulated WAN built in Cisco Packet Tracer connecting a Main Hospital,
Clinic A, Clinic B, and a Central Medical Records Lab.

## 📋 Project Overview
This project simulates a real-world medical network with secure segmentation,
dynamic IP assignment, and inter-site connectivity for healthcare staff and doctors.

## ⚙️ Features
- **VLAN** segmentation — Staff (VLAN 10), Doctors (VLAN 20), Patient Records (VLAN 30)
- **VLSM** subnetting based on host requirements
- **DHCP** — router-based automatic IP assignment for Staff subnet
- **DNS Server** — resolves domain name to internal Web Server
- **Web Server** — hosts an Appointment Booking HTML page
- **NAT** — Static NAT for servers, PAT for users
- **VPN** — Site-to-Site VPN for doctors accessing records remotely
- **Static Routing** — configured across all 4 routers

## 🖧 Network Topology
| Site | Device |
|------|--------|
| Main Hospital | Cisco 2911 Router + 2960 Switch |
| Clinic A | Cisco 2911 Router + 2960 Switch |
| Clinic B | Cisco 2911 Router + 2960 Switch |
| Medical Records Lab | Cisco 2911 Router + 2960 Switch |

## 🛠️ Tools
- Cisco Packet Tracer
- Cisco 2911 Routers
- Cisco 2960-24TT Switches
---

## The Development Team

| Name | GitHub Profile |
| :--- | :--- |
| **Abdulrahman mahmoud** | [@alwakeeeel](https://github.com/alwakeeeel) |
| **Jana Amin** | [@janaadarwish](https://github.com/janaadarwish) |
