# Wireshark-Traffic-Analysis
# Wireshark Traffic Analysis Project

## Overview

This project analyzes live network traffic captured using Wireshark to understand how data moves across a residential network.

## Tools Used

* Wireshark
* Windows 11
* Web browser (Google Chrome)

## Methodology

Network traffic was captured while browsing common websites and performing DNS queries. Filters were applied to isolate DNS, TCP, and HTTPS traffic.

## Analysis

### DNS Traffic

DNS queries were observed when accessing websites. These requests resolve domain names into IP addresses.

### TCP Connections

TCP handshake processes were identified using SYN, SYN-ACK, and ACK packets, demonstrating how connections are established.

### HTTPS Traffic

Encrypted HTTPS traffic was observed. Packet contents were not visible due to encryption, confirming secure communication.

## Key Findings

* DNS traffic reveals browsing activity
* TCP establishes reliable connections
* HTTPS encrypts data payloads for security

## Conclusion

Wireshark analysis provided insight into how network communication occurs at the packet level and demonstrated the importance of encryption and secure communication protocols.
