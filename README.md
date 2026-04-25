# Enterprise_Network_CCNA

# 🌐 Enterprise Network Design with IPsec VPN

## 📌 Project Overview
This project demonstrates the design and implementation of an enterprise-level network using Cisco Packet Tracer. The network consists of a Head Office (HQ) and a Branch Office connected through a Wide Area Network (WAN).

The primary objective of this project is to establish secure communication between geographically separated networks using an IPsec VPN tunnel.

---

## 🏗️ Network Architecture

- Head Office (HQ)
  - Multilayer Switch (VLAN segmentation)
  - Multiple VLANs (e.g., HR, Finance, IT)
  - Servers (DNS, Email, FTP)

- Branch Office
  - Router and Switch
  - End devices (PCs)

- WAN Cloud
  - Connects HQ and Branch routers

- Security
  - Site-to-Site IPsec VPN for secure communication

---

## 🔧 Technologies Used

- Cisco Packet Tracer
- VLAN (Virtual LAN)
- Inter-VLAN Routing
- Static Routing
- IP Addressing & Subnetting
- IPsec VPN (ISAKMP + IPsec)

---

## 🔐 VPN Implementation

A site-to-site IPsec VPN is configured between the HQ and Branch routers.

### Key Components:
- ISAKMP (Phase 1)
- IPsec Transform Set (Phase 2)
- Crypto Map
- Access Control Lists (ACLs)

### Result:
- Secure, encrypted communication between:
  - HQ LAN (192.168.40.0 / 50.0 / 60.0)
  - Branch LAN (192.168.1.0)

---

## 🧪 Testing & Verification

The network was tested using:

- `ping` command → verifies connectivity
- `show crypto isakmp sa` → confirms VPN (QM_IDLE state)
- `show crypto ipsec sa` → verifies encrypted traffic

✔ Successful communication between HQ and Branch  
✔ VPN tunnel established and active  

---

## 📂 Repository Contents

- `project.pkt` → Cisco Packet Tracer file
- `screenshots/` → Configuration and testing images
- `report/` → Project documentation (optional)

---

## ▶️ How to Run

1. Open the `.pkt` file in Cisco Packet Tracer
2. Verify device configurations
3. Test connectivity:
