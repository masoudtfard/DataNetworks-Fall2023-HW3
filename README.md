# Data Networks Course - HW3 - Fall 2023
## Sharif University of Technology
### MAC Layer

This project includes two simulation-based assignments focusing on wireless network protocols:

1. The Hidden Node Problem:
   - Simulates the hidden node problem in wireless networks using OMNeT++.
   - Explores the effect of RTS/CTS (Request to Send/Clear to Send) mechanism.
   - Requires setting up a network with strategically placed obstacles to create hidden nodes.
   - Compares network performance with and without RTS/CTS, and with obstacles removed.

2. MAC Layer Protocols:
   - Uses WSim, a packet-level network simulator for shared medium networks.
   - Implements and analyzes various Medium Access Control (MAC) protocols:
     a) TDMA (Time Division Multiple Access)
     b) Stabilized ALOHA with backoffs
     c) CSMA (Carrier Sense Multiple Access)
     d) CSMA with contention windows (similar to WiFi 802.11 and Ethernet 802.3)
   - Explores the impact of different parameters on network performance, including:
     - Number of nodes
     - Packet size
     - Retry mechanisms
     - Load distribution (skewed vs. uniform)
   - Requires implementation of key MAC protocol functions and analysis of their performance under various conditions.
