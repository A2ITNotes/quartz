---
title: "ARP spoofing "
---
ARP spoofing:
- Address Resolution Protocol spoofing
- To associate MAC address of attacker’s device to IP address of e.g. default gateway
- Occurs when IP address is resolved to a MAC address
- So that traffic is directed to attacker instead of intended host/device
- Data frames may be intercepted and modified traffic movement


prevention of ARP spoofing:

- Use of DHCP server configurations to certify that IP addresses are correctly assigned
- Use of tools to cross-check ARP resolutions to block incorrect ones
- Built into switches/network devices
- Coding the ARP cache in OS to prevent updates. 