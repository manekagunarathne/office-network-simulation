

# Office Network Simulation

This repository contains a **Packet Tracer simulation** and a detailed **report** of a two-floor office network, demonstrating practical network design and configuration. It showcases VLAN segmentation, router-on-a-stick inter-VLAN routing, DHCP/DNS services, NAT for Internet access, and ACL-based restrictions for guest users.

## Features

* **VLAN Segmentation**

  * VLAN 10: Staff (Low Usage – Sales, Admin, Conference Rooms)
  * VLAN 20: IT Department (Full internal access)
  * VLAN 30: Guest Network (Internet only, restricted internal access)

* **Router-on-a-Stick Configuration**

  * Subinterfaces for each VLAN
  * Inter-VLAN routing for communication between VLANs

* **DHCP and DNS**

  * Router-based DHCP pools
  * DNS server integration for VLANs

* **NAT and Internet Simulation**

  * NAT configuration on the router to enable Internet access
  * ISP router simulation for external connectivity

* **Access Control Lists (ACLs)**

  * Guest VLAN restrictions
  * DHCP and DNS explicitly allowed for isolated VLANs

## Files Included

* `Office_Network_Simulation.pkt` – Cisco Packet Tracer file with full configuration
* `Office_Network_Report.pdf` – Detailed report with network diagrams, device configuration, and test results

## How to Use

1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Review the device configurations, VLANs, and ACLs.
3. Run simulation mode to test connectivity, DHCP, DNS, and Internet access.
4. Explore the report for design details, screenshots, and explanations of the configurations.

## Learning Outcomes

* VLAN creation and management
* Router-on-a-stick inter-VLAN routing
* DHCP and DNS configuration
* NAT setup for Internet access
* ACLs for traffic control and security
* Practical troubleshooting and validation of network connectivity

---

