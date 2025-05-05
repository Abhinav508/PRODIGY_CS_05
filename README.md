# 🛡️ Python Packet Sniffer with Scapy

This is a simple Python-based packet sniffer using [Scapy](https://scapy.net/). It captures and logs network packets at the IP layer, displaying details such as IP addresses, protocols, ports, and raw payload data.

---

## 📋 Features

- Captures IP packets (IPv4)
- Detects TCP and UDP traffic
- Displays:
  - Source and destination IP addresses
  - Protocol used (TCP/UDP)
  - Source and destination ports
  - Raw payload (first 100 bytes)
- Logs timestamps for each packet
- Graceful exit on `Ctrl+C`

---

## 🧑‍💻 Requirements

- Python 3.x
- [Scapy](https://scapy.readthedocs.io/)

Install dependencies using pip:

```bash
pip install scapy
