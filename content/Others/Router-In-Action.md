---
title: "Router In Action"
---
![rout](/Images/routersending.png)
- Each router has a stored lookup table of IP addresses/routes to the next router/network
- Routing table is stored at control plane of router
- Routing table used to choose next router/router to which to send packet
- Static routes B to C to E to G are pre-programmed to show route to destination
- Dynamic routing protocols build up a table of preferred routes between connected routers/networks
B to C to F to G if router E is inefficient/out of action/in heavy demand
- If destination is unknown router B will send packet to next known router/C or
D
- If C/D router does not know destination to H then packet is sent onto next
router/E or F


## 2
 

### Why C doest send to D
Router D may be not responding
Router D may be in heavy demand
Router D may have failed/be offline
There may a policy set up in router C to over-ride the routing tables so that
the packets are not sent to router D
To enforce a QoS for specific services that take precedence over other
packets
Router C may have more than one set of routing protocols because it is
connecting to several different networks at once
Alternative routers may respond quicker/before router D/alternative routes
are available sooner than via router D. 
#Network 