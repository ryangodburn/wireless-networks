# CSCI 4482: Wireless Networks

Coursework from **CSCI 4482: Wireless Networks** at the **University of New Haven**, Spring 2025 (third year, spring semester).

- **Author:** Ryan Godburn
- **Tool:** Cisco Packet Tracer 8.2

## Final project: Wireless IoT Home Devices Security

*With Arjun Aravind and Arielle Nash-Rinaldi*

- **`Wireless IOT Home Devices Security.pdf`** (34 pages): a research paper on securing home IoT networks without specialist equipment or training. It covers SSID management, password security, WPA3, network segmentation with VLANs, access control lists, MAC filtering, secure web administration, firmware updates, and a framework for putting the practices in place.
- **`Final Project.pkt`**: the paper's Packet Tracer model of a secured smart home. A Cisco 1941 router does router-on-a-stick inter-VLAN routing for three VLANs (trusted devices on 10, IoT on 20, guests on 30), each with its own access point and SSID. ACLs on the router stop IoT and guest devices from reaching the trusted network, and guests from reaching the IoT devices. The IoT side includes a smart lock, a thermostat and a security camera.

## Labs

| File | Topology and topics |
| --- | --- |
| `Lab 1 - Ryan Godburn.pkt` | Six Cisco 1841 routers running RIP, with two wireless access points serving laptops and smartphones alongside wired PCs. |
| `Lab_2_Godburn.pkt` | Two routers running RIP, a home wireless router and two access points connecting laptops, PCs and a smartphone across several subnets. |
| `Lab_3_Godburn.pkt` | Wireless security: a Linksys router with a hidden SSID, MAC address filtering and a pre-shared key, with a "Hacker" PC placed on the outside network. |
| `Lab_5_Godburn.pkt` | Controller-based Wi-Fi: a Cisco 3504 wireless LAN controller managing a lightweight access point, with a 3560 multilayer switch relaying DHCP requests (`ip helper-address`) to a server. |

## Opening the files

Open the `.pkt` files with Cisco Packet Tracer 8.2 or later (free through Cisco Networking Academy).

---

*Archived coursework, shared as part of my portfolio. If you're taking this course now, please follow your instructor's academic integrity policy.*
