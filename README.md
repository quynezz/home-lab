# Home lab

This repository contains a documentation of my home lab setup, where i demonstrate an ARP spoofing attack using **Ettercap** and trick user to visit a fake website with **Setoolkit**. Futhermore, I will capture the traffic with **Wireshark**, analyze it and defense against such attacks.

## ⚔   Offensive tools uses in the lab

- **Kali Linux** (4 GB RAM, 2 CPU cores, 20 GB disk)
- **Ettercap**: a red team tool for scanning and applying MITM attacks
- **Wireshark**: a network protocol analyzer
- **Setoolkit**: a red team tool for social engineering attacks

## 🛡   Defensive tools uses in the lab

- **Wireshark**: a network protocol analyzer
- **Arpwatch**: a network monitoring tool that tracks Ethernet/IP address pairings
- **Static network configuration**: manually setting IP and MAC addresses to avoid ARP spoofing attacks

## What could improve within the lab

- Use **Snort** or **Suricata** as an IDS/IPS to detect and prevent ARP spoofing attacks
- Implement **Dynamic ARP Inspection (DAI)** on network switches to validate ARP packets
- Use **VPNs** to encrypt traffic and protect against MITM attacks
- Regularly update and patch systems to fix vulnerabilities that could be exploited in ARP spoofing attacks
