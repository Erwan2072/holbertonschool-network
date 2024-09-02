# Networking Basics

This project aims to help you understand fundamental networking concepts, including the OSI model, types of networks, IP addresses, TCP/UDP protocols, and the use of specific networking commands. You will also learn how to write Bash scripts to automate certain network tasks.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts to anyone, without external help:

### OSI Model
- Understand what the OSI (Open Systems Interconnection) model is.
- Know the 7 layers of the OSI model.
- Understand how these layers are organized and how they interact with each other.

### Types of Networks
- **LAN (Local Area Network)**
  - Typical usage: Local networks (e.g., home, office).
  - Geographical size: Limited.
- **WAN (Wide Area Network)**
  - Typical usage: Wide area networks (e.g., the Internet).
  - Geographical size: Large distances.
- **Internet**
  - Understand what the Internet is and how it connects different networks.

### Addresses and Network Protocols
- **IP Address**
  - Understand what an IP address is and its role.
  - Differentiate between the two types of IP addresses: private and public.
- **Localhost**
  - Understand what "localhost" represents (IP address 127.0.0.1).
- **IPv4 and IPv6**
  - Know why IPv6 was created.
- **Subnet**
  - Understand what a subnet is.

### TCP/UDP Transfer Protocols
- Identify the two main data transfer protocols for IP: **TCP** and **UDP**.
- Main difference between TCP (reliable) and UDP (unreliable).
- Port numbers for common services: **SSH (22)**, **HTTP (80)**, **HTTPS (443)**.

### Networking Tools and Commands
- Use `ping` (ICMP) to check network connectivity.
- Use `netstat` to monitor network connections.
- Write Bash scripts following the project's guidelines.

## Tasks

<details>
<summary><strong>0. OSI model</strong> (click to expand)</summary>

The OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts that make communication possible.

- **Lowest level**: Layer 1, for transmission on physical layers with electrical impulse, light, or radio signals.
- **Highest level**: Layer 7, for application-specific communication like SNMP for emails, HTTP for web browsers, etc.

In this project, we will mainly focus on:
- The Transport layer, especially TCP/UDP.
- The Network layer with IP and ICMP.

**Questions:**
1. What is the OSI model?
2. How is the OSI model organized?

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `0-OSI_model`

</details>

<details>
<summary><strong>1. Types of network</strong> (click to expand)</summary>

LAN connects local devices together, WAN connects LANs together, and WANs operate over the Internet.

**Questions:**
1. What type of network is a computer in local connected to?
2. What type of network could connect an office in one building to another office in a building a few streets away?
3. What network do you use when you browse www.google.com from your smartphone (not connected to the Wifi)?

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `1-types_of_network`

</details>

<details>
<summary><strong>2. MAC and IP address</strong> (click to expand)</summary>

**Questions:**
1. What is a MAC address?
2. What is an IP address?

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `2-MAC_and_IP_address`

</details>

<details>
<summary><strong>3. UDP and TCP</strong> (click to expand)</summary>

Let's fill the empty parts in the diagram above.

**Questions:**
1. Which statement is correct for the TCP box?
2. Which statement is correct for the UDP box?
3. Which statement is correct for the TCP worker?

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `3-UDP_and_TCP`

</details>

<details>
<summary><strong>4. TCP and UDP ports</strong> (click to expand)</summary>

Write a Bash script that displays listening ports.

**Requirements:**
- Show only listening sockets.
- Show the PID and name of the program to which each socket belongs.

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `4-TCP_and_UDP_ports`

</details>

<details>
<summary><strong>5. Is the host on the network</strong> (click to expand)</summary>

Write a Bash script that pings an IP address passed as an argument.

**Requirements:**
- Accepts a string as an argument.
- Displays `Usage: 5-is_the_host_on_the_network {IP_ADDRESS}` if no argument is passed.
- Ping the IP 5 times.

**Repository:**
- GitHub repository: `holbertonschool-network`
- Directory: `basics_0`
- File: `5-is_the_host_on_the_network`

</details>

## General Instructions

- Allowed editors: `vi`, `vim`, `emacs`.
- All your Bash script files must be executable.
- Your Bash scripts must pass `shellcheck` without error.
- The first line of all your Bash scripts should be `#!/usr/bin/env bash`.
- The second line of all your Bash scripts should be a comment explaining what the script is doing.

---

This README provides an overview of your project, with collapsible sections for each task that can be expanded as needed.
