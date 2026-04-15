# ARP Sniffer Detection Tool

## What it does
Captures and analyzes ARP packets in a network to detect 
suspicious activity like ARP spoofing attacks.

## Technologies Used
- C Language
- Linux Socket Programming
- Network Packet Analysis

## How to Run
1. Clone the repository
2. Compile the code:
   gcc arpsniffer.c -o arpsniffer -lpcap
3. Run with admin permission:
   sudo ./arp_sniffer (your interface name)

## Features
- Captures live ARP packets from the network
- Analyzes source and destination MAC/IP addresses
- Detects suspicious ARP activity
