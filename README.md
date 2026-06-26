# Network-Traffic-Analysis-and-Threat-Detection-Using-Wireshark

## Overview

This project demonstrates network traffic analysis and basic threat detection techniques in a controlled virtual lab environment using **Wireshark**, and **Ettercap**. Network traffic generated between a Kali Linux attacker machine and a Windows 11 target machine was captured and analyzed to understand protocol behavior, host discovery, and ARP poisoning within an isolated network.

---

## Objectives

* Configure an isolated virtual network for traffic analysis.
* Capture and inspect live network packets using Wireshark.
* Analyze common network protocols such as ICMP, TCP, and ARP.
* Perform host discovery and demonstrate ARP poisoning using Ettercap.
* Understand packet-level communication and basic threat detection techniques.

---

## Tools & Technologies

* Oracle VirtualBox
* Kali Linux
* Windows 11
* Wireshark
* Ettercap

---

## Lab Environment

| Machine    | IP Address         |
| ---------- | ------------------ |
| Kali Linux | **192.168.56.101** |
| Windows 11 | **192.168.56.1**   |

* Host-Only Network Adapter
* Isolated virtual environment
* Safe testing environment

---

## Methodology

1. Configured Kali Linux and Windows 11 virtual machines using Oracle VirtualBox.
2. Connected both systems using a Host-Only Network Adapter.
3. Verified communication between both machines using the `ping` command.
4. Captured live network traffic using Wireshark.
5. Generated ICMP and TCP traffic using ping and Nmap scans.
6. Applied protocol filters (ICMP, TCP, and ARP) to analyze captured packets.
7. Examined packet details including source and destination IP addresses, protocol information, and TCP communication.
8. Used Ettercap to discover hosts on the network.
9. Demonstrated ARP poisoning within the isolated lab environment and monitored the resulting traffic in Wireshark.
10. Recorded observations and documented the findings.

---

## Features Implemented

* Virtual network configuration
* Live packet capture using Wireshark
* ICMP, TCP, and ARP protocol analysis
* Host discovery using Ettercap
* ARP poisoning demonstration

---

## Key Findings

* Successfully established communication between Kali Linux and Windows 11.
* Captured and analyzed ICMP echo requests and replies.
* Verified ARP request and reply communication.
* Successfully identified hosts using Ettercap.
* Demonstrated ARP poisoning and observed the generated network traffic in Wireshark.
* Conducted all testing within a secure and isolated laboratory environment.

---

## Screenshots

This repository includes screenshots of:

* Kali Linux IP Configuration
* Windows 11 IP Configuration
* Wireshark Live Packet Capture
* Ettercap Host Discovery
* ARP Poisoning Demonstration

---

## Skills Demonstrated

* Network Traffic Analysis
* Threat Detection Fundamentals
* Network Scanning
* Host Discovery
* ARP Poisoning Demonstration
* Wireshark Packet Analysis
* Basic Network Security Investigation

---

## Project Structure

```text
Network-Traffic-Analysis-and-Threat-Detection-Using-Wireshark/
│
├── README.md
├── Network_Traffic_Analysis_and_Threat_Detection_Using_Wireshark.pdf
├── screenshots/
│   ├── kali-ip-config.png
│   ├── windows-ip-config.png
│   ├── wireshark-capture.png
│   ├── ettercap-host-list.png
│   └── arp-poisoning.png
└── packet_captures/
    └── traffic_capture.pcap
```

---

## Learning Outcomes

This project strengthened my understanding of network communication, packet analysis, protocol filtering, host discovery, and ARP poisoning techniques. It also provided practical experience using industry-standard tools such as Wireshark and Ettercap for network monitoring and security analysis.
