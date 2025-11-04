# Network-Labs: A Cisco Packet Tracer Portfolio

This repository is a public portfolio of my network simulation projects created using Cisco Packet Tracer. It serves to document my hands-on practice in network design, configuration, and troubleshooting.

## 🚀 About This Repository

Welcome! As I progress in my network engineering studies, I use these labs to build and solidify my understanding of core networking concepts. Each file or folder represents a specific scenario, from basic setup to more complex enterprise-level challenges.

## 🛠️ Tools Used

* **Cisco Packet Tracer:** All labs are created and simulated using this tool. You will need to have Packet Tracer installed on your machine to open the `.pkt` files.

## 🔬 Lab Directory

Here is a list of the labs currently in this repository.

### 1. Basic Subnetting (2 Subnets)

* **File:** `Subnetting Basic Lab 1.pkt`
* **Description:** This lab demonstrates how to subnet a `/24` network (192.168.1.0) into two separate `/25` subnets.
* **Key Concepts:**
    * Subnetting
    * Basic Router & Switch Configuration
    * IP Address assign-ment
    * Inter-Subnet Routing

### 2. Subnetting (3 Subnets)

* **File:** `Subnetting_Lab_2.pkt`
* **Description:** This scenario involves subnetting a `/24` network (192.168.1.0) into three `/26` subnets.
* **Key Concepts:**
    * Subnetting (/26 mask)
    * Multi-Router Topology
    * IP configuration for LANs and a point-to-point (Router-to-Router) link.
    * End-to-end connectivity test.

### 3. DHCP Server Configuration on Router

* **File:** `[Lab_3_DHCP_Server.pkt]`
* **Description:** A lab demonstrating how to configure a Cisco router to act as a DHCP server for a local LAN.
* **Key Concepts:**
    * `ip dhcp excluded-address` (Excluded address range)
    * `ip dhcp pool [name]` (Creating a DHCP pool)
    * `default-router` (Assigning the default gateway)
    * `dns-server` (Assigning a DNS server)
    * Verifying DHCP on the client PC

### 4. Inter-VLAN Routing & DHCP Relay

* **File:** `[Lab_4_DHCP_Relay.pkt]`
* **Description:** A lab demonstrating how to use a centralized router as a DHCP server for multiple VLANs, with a Multilayer Switch acting as the gateway.
* **Key Concepts:**
    * `DHCP Server` (on Router)
    * `Inter-VLAN Routing` (on Multilayer Switch with SVIs)
    * `ip helper-address` (DHCP Relay Agent)
    * `ip dhcp pool` (Multiple pools for different subnets)
    * `ip dhcp excluded-address`

---

## 📖 How to Use

1.  Download or clone this repository.
2.  Ensure you have Cisco Packet Tracer installed.
3.  Open any `.pkt` file to explore the topology, view configurations, and run simulations.

## ✉️ Connect with Me

* **LinkedIn:** `[Emine Kılıç](https://www.linkedin.com/in/emine-kilic/)`
