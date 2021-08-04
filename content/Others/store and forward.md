---
title: "store and forward"
---
S1 to S6 have their own storage devices for storing whole messages
Message sent in its entirety from source to switch S1
...S1 stores whole message on its storage device
S1 connects to S3 and forwards whole message to S3
...S3 stores whole message on its storage device
...message is deleted from S1
S3 connects to S5 and forwards whole message to S5
...S1 stores whole message on its storage device
...message is deleted from S3
Process repeated between S5 and S6 where message is stored before
forwarding to destination
The source and destination of the message are not directly connected
Message can be multiplexed with other messages on network Switches
Method is called message switching

---
---
title: " "
--- 
 Advantage of store and forward:

 - more efficient use of bandwidth because the data channels are shared among communication devices
- Network congestion can be reduced as messages can be stored temporarily at message switches
- Priorities may be used to manage network traffic
- Use of broadcast messaging are delivered to multiple destinations makes more efficient use of network bandwidth
- Message can be stored until recipient decides to pick it up
- Process is transparent to applications the use it. 