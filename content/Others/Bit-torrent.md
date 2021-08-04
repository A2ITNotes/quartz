---
title: " Bit-torrent"
--- 
Bit-torrent:

- Multiple servers computers can be used without a central server
- BitTorrent client required on internet-connected computer to implementation
- BitTorrent:
- Provides peer-to-peer file sharing
- Provides web seeding to allow use of HTTP sources
- Can provide (automatic) RSS feeds via ‘c’ (for content distribution)
- Used by social media/microblogs to distribute updates to servers
- Used to stream videos
- Used to transfer large files using minimum bandwidth.
- ---
---
title: " "
--- 
- BitTorrent protocol:  

- Protocol works well over low-bandwidth connections
- BitTorrent descriptor file is used to describe file being distributed
- BitTorrent node set up with use of descriptor file and file to be distributed
- Node becomes seed for download
- Files made available to others for download by connection to seed/other peers
- File being distributed is divided into small segments/pieces
- Segment/piece becomes available to other peers as it is downloaded
- …original seed/source is relieved of load
- Every segment/piece is encrypted/protected by a cryptographic hash that can be used to detect changes to ensure file integrity
- Segments/pieces downloaded in random order/non-sequentially and reordered by BitTorrent client.