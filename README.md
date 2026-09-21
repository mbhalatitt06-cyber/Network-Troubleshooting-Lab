# Network-Troubleshooting-Lab
A hands-on network troubleshooting lab demonstrating IP configuration, connectivity testing, DNS troubleshooting, DHCP, and network diagnostic commands.

## 📌 Project Overview

This project demonstrates practical network troubleshooting skills using Windows networking tools and commands.

The purpose of this lab is to simulate common IT Support network problems and document a structured troubleshooting process to identify possible causes and verify solutions.

This project was created as part of my ongoing development in IT Support, networking, and cybersecurity.

---

## 🎯 Objectives

The objectives of this lab are to:

- Understand detailed IP configuration
- Check network adapter status
- Troubleshoot DHCP configuration
- Release and renew DHCP network configuration
- Trace network paths
- Interpret basic network diagnostic results
- Document network troubleshooting procedures


---

## 🛠️ Tools Used

- Windows 10/11
- Command Prompt
- `ipconfig /all`
- `netsh interface show interface`
- `tracert`
- `ipconfig /release`
- `ipconfig /renew`

---

## 🔎 Troubleshooting Methodology

I use a structured troubleshooting approach when investigating network problems:

1. Identify the problem
2. Establish a theory of probable cause
3. Test the theory
4. Establish a plan of action
5. Implement the solution
6. Verify full system functionality
7. Document the findings

---

## 🧪 Network Troubleshooting Scenarios

### Scenario 1 — Check Detailed IP Configuration

#### Problem

A technician needs to examine the computer's complete network configuration to identify IP addressing, DHCP, DNS, and gateway information.

#### Command used

`ipconfig /all`

#### Purpose

The `ipconfig /all` command displays detailed network configuration information for the computer's network adapters.

#### Information Checked

- IPv4 configuration
- Subnet mask
- Default gateway
- DHCP information
- DNS configuration
- Network adapter details

---

### Scenario 2 — Check Network Adapter Status

#### Problem

A technician needs to determine whether network interfaces are enabled, connected, or disconnected.

#### Command used

`netsh interface show interface`

#### Purpose

This command displays the administrative state and connection state of available network interfaces.

#### Information Checked

- Administrative state
- Connection state
- Interface type
- Interface name

---

### Scenario 3 — Trace Network Path

#### Problem

A user is experiencing network communication problems and the technician needs to examine the path traffic takes to a destination.

#### Command used

`tracert google.com`

#### Purpose

The `tracert` command identifies the network hops between the local computer and the destination.

It can help an IT Support technician investigate where communication may be experiencing delays or failure.

---

### Scenario 4 — DHCP Troubleshooting

#### Problem

A computer may experience network connectivity problems if it does not have a valid DHCP-assigned network configuration.

#### Commands used

`ipconfig /release`

`ipconfig /renew`

#### Purpose

`ipconfig /release` releases the current DHCP configuration, while `ipconfig /renew` requests a new network configuration from the DHCP server.

#### Troubleshooting Process

1. Release the existing DHCP configuration.
2. Request a new DHCP configuration.
3. Verify that the network adapter receives valid network settings.
4. Confirm that network connectivity is restored.

---

## 📋 Network Troubleshooting Commands

| Command | Purpose |
|---|---|
| `ipconfig /all` | Displays detailed network configuration |
| `netsh interface show interface` | Displays network adapter status |
| `tracert` | Displays the network path to a destination |
| `ipconfig /release` | Releases the current DHCP configuration |
| `ipconfig /renew` | Requests a new DHCP configuration |

---

## 📸 Hands-On Evidence

### 1. Detailed IP Configuration
![IP Configuration](ipconfig-all.png)

### 2. Network Adapter Status
![Network Adapter Status](network-adapter-status.png)

### 3. Network Path Testing
![Traceroute Test](tracert.png)

### 4. DHCP Troubleshooting
![DHCP Troubleshooting](dhcp-renew.png)
---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

- TCP/IP fundamentals
- IPv4 addressing
- Subnetting fundamentals
- Default gateways
- DNS
- DHCP
- Network connectivity testing
- Network path analysis
- Windows command-line tools
- IT troubleshooting methodology
- Technical documentation

---

## 🚀 Future Improvements

I plan to expand this lab with:

- Ping connectivity testing
- DNS troubleshooting using nslookup
- Subnetting exercises
- Static IP configuration
- Network diagrams
- Packet capture analysis
- Wireshark exercises
- Basic network security troubleshooting

---

## 👤 About Me

I am developing my skills in IT Support, networking, and cybersecurity through hands-on labs and practical troubleshooting exercises.

My goal is to apply these skills in a professional IT Support environment while continuing to develop my technical knowledge.
