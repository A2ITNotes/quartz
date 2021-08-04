---
title: "Static and Dynamic Tables "
--- 
Static Routing  Table:

- Routes are entered into a database are by network administrator
- Entries are fixed
- Defines fixed routes for packets to take from the router
- Used by a routing algorithm to create a ‘forwarding table’ for use when choosing next hop
- Defines route of last resort
- Provides fail-safe if dynamic routing does not provide a route
- Can be used to transfer routing information from one router to another

---
---
title: " "
--- 
Dynamic Routing Table:

- Routing protocols create a table of routing information from real-time logical network changes
- Created automatically by algorithms created by network administrator
- Use a number of different protocols to determine ‘best’ route router to use
- Routing information can be automatically shared with other routers (using same protocol)
- Routing information can be automatically shared with other routers to discover data about remote networks in networks
- Can be used to limit the number of ‘hops’ that a packet can take to its destination
- Routes have a time-to-live after which the database will be updated
- Packets can be forwarded via different routes depending on network conditions
- Packets can be routed around network damage
- Allow as many routes as possible to be kept open.