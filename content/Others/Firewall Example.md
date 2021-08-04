---
title: "Firewall Example "
--- 
![[Pasted image 210428103741.png]]

DMZ in a network:
- Installation of additional (to separate the servers from internal network)
- Installation of demilitarised zone/DMZ
- DMZ can be physical or logical subnetwork
- DMZ external node can only access the services in the DMZ and not the internal LAN
- The services accessible to external users are placed in the DMZ...
  - ...email server and web server and FTP server
- Services for internal use are kept behind internal firewall so not accessible from the internet
- External firewall is the perimeter/front end and allows traffic destined for DMZ to pass
- Internal firewall is configured to allow traffic from DMZ to enter company LAN.

---
---
title: " "
--- 
Benefits Of Two Firewalls

- The extra firewalls means that any attacker that gets past the first firewall would have to get past the second to access the company LAN
- An attacker could not be sure how many other firewalls would be found on the network
- One firewall is an external firewall and one is an internal firewall and could have different security
- The internal firewall security protects the data one LAN segment
- The external firewall security only has to deal with data from the internet
- The internal services are now protected by both firewalls. 