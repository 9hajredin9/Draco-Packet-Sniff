# DRACO - Packet Sniffing Tool

**DRACO** is a simple yet powerful packet sniffing tool written in Python using the `scapy` library. It allows you to monitor network traffic in real time and filter specific types of packets based on protocols. The tool is useful for network administrators, security researchers, and anyone interested in monitoring network activity.

## Features

- Supports sniffing various types of network traffic including TCP, UDP, HTTP, HTTPS, ICMP, ARP, and DNS.
- Display detailed information for each packet:
  - Source and destination IP addresses
  - Protocols (TCP, UDP, ICMP, ARP, DNS)
  - Port numbers (TCP/UDP)
  - ARP operations (Request/Reply)
  - DNS queries
- Custom filter expression support for advanced users.

## Requirements

Before using the tool, you need to install the required dependencies.

### 1. Install Python and pip (if not installed)
- Ensure that Python 3 and `pip` (Python package installer) are installed.

### 2. Install the required dependencies
You need to install the `scapy` library to run the script. Use the following command to install it via `pip`:

```bash
pip install scapy
```


If you're using Linux (Ubuntu, for example), you may need to install additional dependencies for packet capture:

```bash 
sudo apt install libpcap-dev
```

Usage :

```bash
git clone https://github.com/your-username/draco-packet-sniffer.git
```
```
cd draco-packet-sniffer
```


Make the Script Executable (Linux/macOS)
If you're using Linux or macOS, make the script executable:

```bash 
chmod +x draco_sniffer.py
```


3. Run the Script
Once you have everything set up, you can run the packet sniffing tool with:

```bash 
python3 draco_sniffer.py
```

License

This project is open-source and licensed under the MIT License. Feel free to contribute, make improvements, or suggest features!
Only for educational purposes !

Author
Made by: Hajra
TikTok: @scriptkidworld
YouTube: ScriptKid Networks
