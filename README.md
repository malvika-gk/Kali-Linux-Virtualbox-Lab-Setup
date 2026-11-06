# Kali Linux and VirtualBox – Cybersecurity Lab Setup

## Overview

This repository documents my hands-on cybersecurity lab setup using Kali Linux and Oracle VirtualBox.

The objective was to configure a Kali Linux virtual machine, establish network connectivity, and prepare a virtual environment for cybersecurity learning and practical exercises.

## Tools Used

- Kali Linux 2026.3
- Oracle VirtualBox
- VirtualBox NAT Network

## Virtual Machine Configuration

- Operating System: Kali Linux
- VM Name: kali-linux-2026.3-virtualbox-amd64
- RAM: 2048 MB
- Network Adapter: Intel PRO/1000 MT Desktop
- Network Mode: NAT Network

## Tasks Completed

- Set up Kali Linux in VirtualBox.
- Configured the virtual network adapter.
- Reviewed NAT Network settings.
- Tested network connectivity using ping.
- Tested DNS resolution.
- Verified connectivity to the virtual network gateway.

## Connectivity Testing

Commands used:

```bash
ping -c 4 8.8.8.8
ping -c 4 10.0.0.1
getent hosts google.com
```

## Screenshots

### 1. Kali Linux Network Connectivity Test
![Network Test](screenshots/Screenshot%20(3).png)

### 2. VirtualBox Adapter Settings
![Adapter Settings](screenshots/Screenshot%20(6).png)

### 3. Kali Linux Desktop
![Kali Linux Desktop](screenshots/WhatsApp%20Image%202026-11-06%20at%209.09.57%20PM.jpeg)

### 4. NAT Network Configuration
![NAT Network](screenshots/3-nat-network-configuration.png)

### 5. VirtualBox Overview
![VirtualBox Overview](screenshots/WhatsApp%20Image%202026-11-06%20at%209.11.59%20PM.jpeg)


## Key Learnings

- Virtual machine configuration.
- Basic Linux networking.
- NAT Network configuration.
- Network connectivity troubleshooting.
- DNS resolution testing.

## Conclusion

This lab helped me understand the fundamentals of setting up a cybersecurity practice environment using Kali Linux and VirtualBox.

This environment will be used for future cybersecurity learning and authorized practical exercises.
