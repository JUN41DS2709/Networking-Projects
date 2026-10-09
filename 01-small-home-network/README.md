# Project 01: Small Office / Home Network

## Overview

This project demonstrates the construction and testing of a basic home network using Cisco Packet Tracer. A PC and a laptop connect to a wireless router, providing a practical introduction to local network communication and IP addressing.

## Objectives

- Build a basic home network topology.
- Connect a PC to a wireless router using Ethernet.
- Connect a laptop to the wireless network.
- Inspect IP addressing and default gateway settings.
- Test connectivity using ICMP ping.
- Observe packet events using Simulation Mode.

## Network Topology

**Devices used:**
- 1 PC
- 1 laptop
- 1 WRT300N wireless router
- 1 cable modem
- 1 cloud device

## Addressing and Connectivity

The laptop's observed network configuration:

| Setting | Value |
|---|---|
| IPv4 address | `192.168.0.102` |
| Subnet mask | `255.255.255.0` |
| Default gateway | `192.168.0.1` |

The laptop successfully pinged `192.168.0.100`, receiving four replies with 0% packet loss in the recorded test.

## Concepts Practiced

- IPv4 addressing and private IP ranges
- Subnet masks and local subnet communication
- Default gateways
- DHCP and ARP fundamentals
- ICMP Echo Requests and Echo Replies
- Cisco Packet Tracer Simulation Mode

## Validation

- [x] Built the basic network topology
- [x] Inspected laptop IP configuration
- [x] Successfully pinged the PC
- [ ] Inspected ARP and ICMP packet details
- [ ] Tested connectivity to an external destination

## Screenshots

Add screenshots of:
1. The complete network topology
2. The laptop's IP configuration and successful ping
3. Packet events in Simulation Mode

## Lessons Learned

This project introduced basic network addressing and connectivity testing. It highlighted the importance of understanding the difference between local communication and traffic routed through a default gateway.

## Future Improvements

- Investigate ARP resolution and MAC addressing.
- Introduce deliberate configuration errors and troubleshoot them.
- Verify external connectivity in the simulated environment.
- Document findings from packet inspection.

## Tools

- Cisco Packet Tracer
- Command Prompt simulation
