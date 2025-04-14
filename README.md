# cybersecurity-homelab-dmz
This home lab was built using Cisco Packet Tracer to simulate a real-world secure network environment, featuring internal, external, and DMZ zones protected by an ASA firewall.


# This home lab simulates a secure enterprise network using Cisco Packet Tracer. It features proper network segmentation, a public-facing DMZ, and firewall rules designed to mirror real-world cybersecurity best practices. This project showcases the design and implementation of network security zones using an ASA firewall, ACLs, DHCP, and basic services.

# Tools Used
Cisco Packet Tracer

Cisco ASA 5506 Firewall

ISR 4321 Router

2960 Switch

PC-PT and Server-PT devices

# Network Architecture

[External PC] → [Router] → [ASA Firewall]
                             ↓         ↓
                        [Inside LAN]   [DMZ Web Server]
Outside Network: 192.168.1.0/24

Inside Network: 10.10.10.0/24

DMZ Network: 172.16.0.0/24

# Test Results
External PC ➔ Internal PC (ping): Blocked (as expected)

External PC ➔ Web Server (HTTP): Allowed

Internal PC ➔ External/DMZ: Allowed (default behavior)

DMZ ➔ Inside: Blocked (by default ASA behavior)

# Inluded
Network Segmentation
DHCP Services
ACL-Based Firewall Rules
DMZ Configuration


## IDS Sensor
A PC labeled "IDS-Sensor" simulates traffic monitoring and represents an intrusion detection system like Snort or Wireshark.

# What I learned
Set up a multi-zone firewall using ASA
Applied access control logic using extended ACLs
Designed and tested a real-world DMZ
Practiced secure subnetting and traffic isolation

Joshua Beaton
Computer Science Graduate | Security+ Certified | Aspiring Security Analystjoshabeaton@gmail.com



