---
title: "Network Interface Card "
--- 
## Network Interface Card:
- Provides access to physical / wireless transmission medium
- Creates the protocol stack (using its electrical components)
- Allows communications between LANs / WANs (using the protocols it has created)
- Provides low level addressing at MAC level
- Works at physical and data level of OSI model / OSI layer 1 and 2

---
## Use in sending and receiving data

- Accepts data from CPU via internal buses
- Converts parallel data stream to linear / serial data stream and vice versa for /transmission / after reception to / from transmission medium
- Data is sent / received in frames
- ---

NIC
- ## When sending:
	- NIC is notified that frame has been created by OS in a buffer
	- NIC accesses  memory directly by DMA(direct memory access)
	- NIC determines address and creates data frame
	- NIC transmits completed frame to transmission medium
	- NIC notifies OS that frame has been sent
---

NIC
- ## When receiving:
	- NIC monitors transmission medium for frames
	- NIC reads frame from transmission medium into buffer using DMA
	- NIC checks frame contents and calculates checksum to verify integrity of data
	- NIC interrupts host OS to indicate that a frame has arrived 
