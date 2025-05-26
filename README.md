# Hotel-Management-Network-Design
Hotel network design using 3 routers, 3 switches, 8 VLANs, DHCP, OSPF, SSH, and inter-VLAN routing per floor in Cisco Packet Tracer.


# 🏨 Hotel Management Network Design (3-Floor VLAN Architecture)

## 📘 Project Overview
This Cisco Packet Tracer project simulates a **Hotel Management Network** spread across **three floors**, each with its own set of VLANs, **dedicated router**, and switch. The design enables **inter-VLAN communication**, **centralized DHCP**, and **secure remote access** via SSH. **OSPF** is used to connect all routers in a dynamic and scalable routing setup.

## 🧱 Network Design Breakdown

### 🏢 1st Floor – Operations
- **VLAN 80 – Logistics**
- **VLAN 70 – Store**
- **VLAN 60 – Reception**

### 🏢 2nd Floor – Business Departments
- **VLAN 50 – Sales**
- **VLAN 40 – Human Resources**
- **VLAN 30 – Finance**

### 🏢 3rd Floor – Administration & Support
- **VLAN 20 – Admin**
- **VLAN 10 – IT**

Each floor has:
- 1 router (handling inter-VLAN routing for that floor)
- 1 switch (handling VLAN segmentation)

## 🔑 Features Implemented
- ✅ **8 VLANs** across 3 floors
- ✅ **Routing using multiple routers** (one per floor)
- ✅ **OSPF** dynamic routing between routers
- ✅ **DHCP** for automatic IP assignment
- ✅ **SSH** for secure remote device access
- ✅ **IP Addressing and Subnetting** planned for all devices
- ✅ **Full connectivity** – all VLANs can ping each other

## 📁 Files Included
- `Hotel-Network.pkt` – Cisco Packet Tracer file
- `README.md` – This description
- `ip-plan.png` – Screenshot of IP address and subnet mask plan

## 🧪 Testing & Verification
- DHCP confirmed across all VLANs
- Ping tests verified inter-VLAN communication across all floors
- OSPF routing tables successfully populated
- SSH connections tested to routers

## 🚀 Skills Demonstrated
- VLAN design and segmentation
- Multi-router architecture
- OSPF routing configuration
- SSH setup for remote access
- DHCP and IP planning
