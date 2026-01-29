# 🌐 Enterprise Multi-Branch Network Infrastructure
> **Developed by: @KhalidExe & @vd2mi**
> **Academic Project | CIS 326 - Network Administration | IAU**

## 📋 Project Overview
A sophisticated network architecture designed for a corporation with **6 distributed branches**: Store, Warehouse, IT Department, Distribution Center, Factory, and Administration. This project demonstrates a highly scalable infrastructure using Cisco Packet Tracer to simulate real-world environments with both **Logical** and **Physical** implementations.

---

## 🛠️ Technical Highlights & Implementation

### 1. Hybrid Dynamic Routing 🔄
* **Protocols:** Dual implementation using **OSPF** and **RIPv2**.
* **Route Redistribution:** Configured protocol merging on **Router 2** to ensure full reachability across different routing domains.
* **Addressing:** Organized IP allocation with custom subnet masks for global (/8) and internal (/24) operations.

### 2. Network Segmentation & Security 🛡️
* **VLAN Deployment:** Dedicated VLANs for each branch to enhance security and traffic management.
* **VLAN IDs:** Store (100), Warehouse (400), IT (200), Distribution (500), Factory (300), and Admin (10, 20, 30).

### 3. Advanced Services (VoIP & Wireless) 📞
* **VoIP Infrastructure:** Cisco IP Phones configured with dedicated Voice VLANs for inter-branch communication.
* **Centralized Wireless:** Managed via **WLC (Wireless LAN Controller)** with WPA2-PSK security policies.
* **Server Roles:** Deployed centralized **DNS** and **Web Servers** to host internal corporate resources.

---

## 📐 Network Views

### 🔹 Physical Implementation
* **Realistic Simulation:** Fully organized **Physical View** depicting the actual distribution of devices, racks, and structured cabling across all 6 branches.
![Physical View](./Physical_View.png)

### 🔹 Logical Topology
![Logical View](./Logical_View.png)  
*Note: High-level logical representation of the 6-router interconnected network.*

---

## 🧪 Verification & Results
* **Connectivity:** 100% successful **ICMP Ping tests** verified across all branch subnets.
* **Domain Access:** Verified successful access to the corporate internal site via the "IT" domain name.

---
**Main Developers:** @KhalidExe & @vd2mi.
