## IP Address

- 32 bit binary number
  - Divided into four octets (8 bits or 1 byte)
- Layer 3 logical address assigned by an administrator
  - MAC Addresses - built into NCI
- Used to identify specific devices on a network
- Connectionaless Protocol (no sessions)
  - TCP is connection oriented (syn -> syn ack -> ack [three way handshake])
- Packets treated independently
  - May take different paths based on LB, Bandwidth, Hopcount
- Best effort delivery
- No data recovery features

## Format Overview

Hierarchical structure to enable routing via Network portion (Network ID) and Host portion (Host ID)
  
- Network Address Portion (Network ID)
  - Identifies a specific network
  - Routers maintain routing tables that contain the network
  - Look at destination of IP address and match to network address
  
- Host Address Portion (Host ID)
  - Identifies a specific endpoint on a network
  - Devices
