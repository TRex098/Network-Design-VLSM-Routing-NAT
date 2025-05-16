# Network-Design-VLSM-Routing-NAT


# 🌐 Computer Networks Project (Cisco Packet Tracer)

This repository contains a full network simulation built using **Cisco Packet Tracer (Instructor Version)**. The project demonstrates advanced networking concepts such as **VLSM**, **dynamic routing (RIP, EIGRP, OSPF)**, **NAT**, **DHCP**, **ACLs**, and **email configuration** across multiple interconnected subnets.

---

## 📁 Project Overview

The network design is based on a given topology layout and customized IP address assignments. It was configured using:

- Variable Length Subnet Masking (VLSM)
- Multi-protocol dynamic routing (RIP, EIGRP, OSPF Areas 1 & 2)
- Inter-protocol redistribution
- NAT implementation on Router20 and Router8
- Centralized DHCP server for all networks
- Access Control Lists (ACLs) for security and traffic restrictions
- Email server with end-to-end mail configuration

---

## ⚙️ Features Implemented

- ✅ VLSM for IP efficiency
- ✅ RIP, EIGRP, OSPF (Areas 1 and 2)
- ✅ Route Redistribution between routing protocols
- ✅ Centralized DHCP for IP management
- ✅ NAT (Network Address Translation) on edge routers
- ✅ ACLs to restrict web access from:
  - One PC in Network A
  - One smartphone in Network E and J
  - All hosts in Network D
- ✅ Mail server for inter-host communication

---

## 📦 Files Included

- `network_topology.pkt`: Cisco Packet Tracer simulation file
- `IP_Addresses.pdf`: Contains assigned IP blocks and host requirements
- `Documentation/`: Folder with subnetting, routing tables, ACL design, and NAT configuration steps
- `README.md`: Project description

---

## 🛠️ Tools Used

- Cisco Packet Tracer (Instructor Version)
- IP subnet calculator
- Basic CLI for Cisco routers/switches

---

## 📧 Email Configuration

All hosts are assigned email addresses and configured to send/receive emails through the mail server in the first block. SMTP/POP3 setup is demonstrated.

---

## 📌 Notes

- Redistribution and DHCP setup tested across all routing blocks.
- NAT configurations successfully allow outside access with defined restrictions.
- ACL logic carefully planned to enforce policy-based filtering.

---

## 📝 License

This project is for academic use. Please contact the author before reusing or distributing.

