# Home IT Infrastructure & Technical Support Operations

## Project Overview

This project involved designing, configuring, testing, and troubleshooting a simulated home IT network using Cisco Packet Tracer.

The lab simulates a home environment containing wired computers, a wireless laptop, a printer, and a wireless router. It focuses on foundational IT support operations, network configuration, connectivity verification, fault simulation and troubleshooting.

## Objectives

- Design and configure a simulated home network.
- Configure router LAN and DHCP services.
- Configure Wi-Fi security.
- Connect wired and wireless devices.
- Assign a static IP address to a printer.
- Verify local network connectivity.
- Practice network diagnostic commands.
- Simulate and resolve common network faults.
- Review Windows file sharing, firewall and endpoint security.
- Apply a structured troubleshooting methodology.

## Lab Environment

| Component | Configuration |
|---|---|
| Tool | Cisco Packet Tracer |
| Network | `192.168.10.0/24` |
| Router LAN | `192.168.10.1` |
| DHCP Range | `192.168.10.100–192.168.10.149` |
| Wi-Fi SSID | `HomeNet-202` |
| Wireless Security | WPA2 Personal / AES |
| DNS | `8.8.8.8` |

## Network Devices

| Device | IP Address | Configuration |
|---|---|---|
| Home Router | `192.168.10.1` | LAN Gateway |
| Home-PC | `192.168.10.102` | DHCP |
| Office-PC | `192.168.10.103` | DHCP |
| Home-Laptop | `192.168.10.101` | DHCP / Wi-Fi |
| Home-Printer | `192.168.10.20` | Static IP |

## Tasks Completed

- Home network topology design
- Router LAN configuration
- DHCP configuration
- Wired device connectivity
- Wireless configuration and connection
- Printer static IP configuration
- IP configuration verification
- Local connectivity testing
- Network diagnostics
- IP configuration fault simulation
- Gateway configuration fault simulation
- DHCP failure and recovery simulation
- Network Discovery and File Sharing concepts
- Firewall and endpoint security review
- Wi-Fi troubleshooting
- Structured troubleshooting methodology

## Connectivity Verification

Local connectivity was verified between the home router, Home-Laptop, Office-PC and printer.

Diagnostic commands reviewed:

- `ipconfig`
- `ipconfig /all`
- `ping`
- `tracert`
- `nslookup`
- `netstat -ano` (reviewed conceptually due to Packet Tracer limitations)

## Troubleshooting Exercises

| Fault | Troubleshooting |
|---|---|
| Incorrect IP address | Corrected endpoint addressing |
| Incorrect gateway | Restored correct gateway configuration |
| DHCP failure | Restored DHCP service |
| Wi-Fi connection issues | Reviewed authentication and wireless troubleshooting |
| File-sharing issues | Reviewed discovery, permissions and firewall concepts |

## Limitations

- The WAN was not connected to a functioning ISP.
- External connectivity was not verified.
- External DNS resolution was not verified.
- Packet Tracer does not support the full Windows command set.
- Full Windows file-sharing and firewall workflows were reviewed conceptually.

## Documentation

Detailed technical documentation and project evidence are available in:

- `Documentation/` — Detailed project documentation.
- `Screenshots/` — Configuration, connectivity and troubleshooting evidence.

## Skills Demonstrated

- Basic IT support
- Home network configuration
- IPv4 addressing
- DHCP
- DNS fundamentals
- Default gateway troubleshooting
- Wireless networking
- Network diagnostics
- Connectivity troubleshooting
- Endpoint configuration
- Technical documentation

---

**Project:** Home IT Infrastructure & Technical Support Operations  
**Environment:** Cisco Packet Tracer  
**Focus:** IT Support, Networking and Troubleshooting
