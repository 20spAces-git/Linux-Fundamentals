# Linux Lab 06 - Networking Commands

## Objective

Learn how to identify network information, test connectivity, and perform basic network troubleshooting using Linux networking commands.

---

## Lab Environment

### Platform

- TryHackMe Linux Fundamentals Room
- Linux Terminal

### Commands Used

- ip a
- ping
- nslookup
- traceroute
- netstat
- ss

---

## Procedure

### Step 1 - View Network Interfaces

Command:

ip a

Purpose:

Displays network interfaces, IP addresses, and interface status.

---

### Step 2 - Test Connectivity

Command:

ping google.com

Purpose:

Tests communication between the local system and a remote host.

---

### Step 3 - Perform DNS Lookup

Command:

nslookup google.com

Purpose:

Resolves a domain name into an IP address.

---

### Step 4 - Trace Network Path

Command:

traceroute google.com

Purpose:

Displays the route packets take to reach a destination.

---

### Step 5 - View Active Connections

Command:

netstat -an

Purpose:

Displays active network connections and listening ports.

---

### Step 6 - Review Socket Statistics

Command:

ss

Purpose:

Displays socket and connection information.

---

## Skills Practiced

- Network Troubleshooting
- Connectivity Testing
- DNS Analysis
- Route Analysis
- Connection Monitoring

---

## What I Learned

Linux provides several tools for analyzing network connectivity and troubleshooting communication issues.

These commands help identify:

- IP Addresses
- DNS Information
- Network Paths
- Active Connections

---

## DFIR Relevance

Network analysis helps investigators:

- Identify suspicious connections
- Detect unauthorized communication
- Review active sessions
- Investigate network incidents
- Support forensic investigations

---

## Connections to Previous Repositories

This lab reinforces concepts learned in:

- Network Fundamentals
- Cybersecurity Labs
- Wireshark Basics

---

## Safety Considerations

- Only test systems and networks you are authorized to access.
- Verify commands before execution.
- Follow organizational policies regarding network analysis.

---

## Result

Successfully used Linux networking commands to analyze connectivity, DNS resolution, routing, and active network connections.

Status: Completed ✅


🐧 Commands To Run
ip a

ping google.com

nslookup google.com

traceroute google.com

netstat -an

ss
