# Router-Switch-Topology-Project
A practical network topology project featuring DHCP-enabled router connection to multiple static hosts, wireless access point, and Class C subnet design as part of cyber security learning.
This project demonstrates the foundational networking concepts required in Cyber Security Module 1. The network is built using Cisco Packet Tracer and includes both WAN and LAN infrastructure with static routing, DHCP, and NAT for secure communication with the internet.

The architecture consists of an ISP router connected to a LAN router, which distributes network access to multiple devices via a switch and wireless access point. A private Class C network (192.168.10.0/24) is used for internal devices, while the WAN interface uses a Class B network (172.16.0.0/16) for external connectivity.

Key Objectives:
• Understand how basic enterprise networks are designed
• Configure routers with proper IP addressing
• Enable internal device communication across LAN
• Provide internet access using static routing and NAT
• Verify connectivity using network testing tools (Ping, Commands)

Router Configuration Summary:
• WAN and LAN interfaces configured on routers
• Static route on ISP Router to internal network
• Default route on LAN Router for internet access
• Dynamic NAT (PAT overload) for secure public communication
• ACL defined to permit only internal subnet for NAT
