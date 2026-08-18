# Cisco Packet Tracer – Networking Fundamentals

## 📌 Project Overview

This project documents my hands-on learning journey with **basic computer networking using Cisco Packet Tracer**.

The goal of this lab was to build a foundation in networking by learning how computers communicate, how network devices are connected, how IPv4 addresses are assigned, and how connectivity can be tested.

This project is part of my ongoing **IT / Networking learning portfolio**.

---

## 🎯 Learning Objectives

By completing this lab, I practiced the following skills:

* Explain what a **PC and laptop** do in simple terms.
* Navigate the **Cisco Packet Tracer workspace**.
* Identify and use basic networking devices.
* Select the appropriate **cable type** for connecting devices.
* Build a simple network topology.
* Configure an **IPv4 address** on a host.
* Test network connectivity using the **ping** command.
* Understand the basic relationship between devices, cables, and IP addresses.

---

## 🛠️ Tools Used

* **Cisco Packet Tracer**
* PC / Laptop
* Ethernet cables
* IPv4 addressing
* Command Prompt
* `ping` command

---

## 🌐 Lab Topology

The basic lab consists of networked end devices connected together and configured with IPv4 addresses.

Example:

```text
+---------+        Ethernet        +---------+
|   PC    | ---------------------- | Laptop  |
+---------+                         +---------+
   IP: 192.168.1.10                   IP: 192.168.1.20
```

The devices are placed in the Packet Tracer workspace and connected using an appropriate Ethernet cable.

---

## 🔧 What I Practiced

### 1. Understanding End Devices

I learned the basic purpose of computers in a network.

A **PC or laptop** can act as a network host. It can send and receive data from other devices using network connections.

---

### 2. Using Cisco Packet Tracer

I practiced navigating the Packet Tracer interface, including:

* Selecting devices
* Placing devices in the workspace
* Connecting devices
* Opening device configuration menus
* Accessing the Command Prompt
* Testing network connectivity

Packet Tracer allowed me to practice networking concepts in a simulated environment without requiring physical networking equipment.

---

### 3. Connecting Devices

I learned that different networking connections may require different cable types.

For this basic lab, I practiced using an Ethernet connection to connect network devices.

This helped me understand that choosing the correct physical connection is an important part of building a network.

---

### 4. Configuring an IPv4 Address

I practiced assigning an IPv4 address to a host.

Example configuration:

```text
IP Address: 192.168.1.10
Subnet Mask: 255.255.255.0
```

Another host can be configured with:

```text
IP Address: 192.168.1.20
Subnet Mask: 255.255.255.0
```

Because both devices are on the same network, they can communicate with each other when the configuration and physical connection are correct.

---

### 5. Testing Connectivity

I used the `ping` command to test whether one device could communicate with another.

Example:

```text
ping 192.168.1.20
```

A successful response indicates that the destination device can be reached.

Example:

```text
Reply from 192.168.1.20: bytes=32 time<1ms TTL=128
```

This introduced me to one of the most basic and useful network troubleshooting commands.

---

## 🧠 Key Concepts Learned

### IP Address

An IP address identifies a device on an IP network.

Example:

```text
192.168.1.10
```

### Subnet Mask

A subnet mask helps determine which portion of an IP address represents the network and which portion represents the host.

Example:

```text
255.255.255.0
```

### Ping

`ping` is a basic network troubleshooting tool used to test connectivity between devices.

Example:

```bash
ping 192.168.1.20
```

### Network Topology

A topology describes how devices are connected within a network.

In this lab, I created a simple topology using end devices and Ethernet connections.

---

## 🔍 Troubleshooting Practice

When connectivity does not work, I learned to check the following:

1. Is the correct cable being used?
2. Are the devices physically connected?
3. Are the network interfaces active?
4. Does each device have a valid IP address?
5. Are the devices on the same network?
6. Is the subnet mask configured correctly?
7. Does `ping` receive a response?

Example troubleshooting process:

```text
Check cable
    ↓
Check interface
    ↓
Check IP address
    ↓
Check subnet mask
    ↓
Run ping
    ↓
Analyze the result
```

---

## 📂 Project Files

```text
.
├── README.md
└── packet-tracer/
    └── basic-network.pkt
```

The `.pkt` file contains the Cisco Packet Tracer network topology and configuration used for this lab.

---

## 📸 Evidence of Learning

Screenshots can be added here to document the work completed in Packet Tracer.

Recommended screenshots:

* Packet Tracer topology
* Device IP configuration
* Command Prompt showing the `ping` command
* Successful ping response

Example:

```text
[Add Packet Tracer screenshot here]
```

---

## 💡 What I Learned

This lab helped me understand that networking is more than simply connecting computers together.

I learned that successful communication requires several components to work together:

```text
Device
   ↓
Network Connection
   ↓
IP Address
   ↓
Network Configuration
   ↓
Connectivity Test
```

The lab also gave me my first practical experience troubleshooting network connectivity instead of only learning networking concepts from theory.

---

## 🚀 Next Steps

My next networking topics will include:

* Understanding subnetting
* Learning about switches
* Learning about routers
* Understanding MAC addresses
* Understanding ARP
* Configuring default gateways
* DHCP
* DNS
* VLANs
* Basic network troubleshooting
* Cisco IOS command-line configuration

---

## 📚 Learning Progress

| Skill                       | Status        |
| --------------------------- | ------------- |
| Understand PCs and laptops  | ✅ Completed   |
| Navigate Packet Tracer      | ✅ Completed   |
| Connect network devices     | ✅ Completed   |
| Select basic cable types    | ✅ Completed   |
| Configure IPv4 addresses    | ✅ Completed   |
| Test connectivity with ping | ✅ Completed   |
| Basic troubleshooting       | 🔄 Practicing |
| Subnetting                  | ⏳ Next        |
| Switch configuration        | ⏳ Next        |
| Router configuration        | ⏳ Next        |

---

## 👨‍💻 About This Portfolio

This repository documents my progress as I develop practical skills in **networking, IT, cybersecurity, and technical troubleshooting**.

I am using hands-on labs and projects to turn networking concepts into practical skills that I can demonstrate through my GitHub portfolio.

> **Learning by doing, documenting the process, and building practical skills one lab at a time.**
