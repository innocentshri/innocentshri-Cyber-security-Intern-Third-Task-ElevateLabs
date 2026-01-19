# Task 3 - Networking Basics for Cyber Security

## Objective
To understand basic networking concepts and analyze real network traffic using Wireshark.

## Tools Used
- Wireshark (Primary Tool)

## Concepts Covered
- IP Address
- MAC Address
- TCP and UDP
- DNS
- HTTP vs HTTPS
- Packet Sniffing
- TCP Three-Way Handshake

## Steps Performed 

1. Installed Wireshark.
2. Started live packet capture on the active network interface.
3. Applied protocol filters:
   - 'tcp'
   - 'udp'
   - 'dns'
   - 'http'
4. Observed TCP three-way handshake:
   - SYN
   - SYN-ACK
   - ACK
5. Captured DNS queries and responses.
6. Identified difference between:
   - Plain-text traffic (HTTP)
   - Encrypted traffic (HTTPS)
7. Saved the packet capture as 'capture.pcapng'.

## Observation

1. TCP uses a three-step process to establish a connection, which ensures reliability.
2. UDP sends packets without connection setup, makingit faster but less reliable.
3. DNS translates website names into IP addresses.
4. HTTP traffic is readable, while HTTPS traffic is encrypted.
5. Packet sniffing allows monitoring of network activity for security analysis.

## Final Outcome
I learned how to analyze real network traffic and understand basic protocols using Wireshark.









