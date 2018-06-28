## OSI Model

Layers:

7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Datalink
1. Physical

### Application 

- Network processes to applications
- FTP, Telnet, HTTP
- Use protocols to communicate with other network resources and services

### Presentation

**Data representation/syntax**

- Ensures that data is readable by receiving system
- Structures, negotiation data transfer syntax from application layer
- Provides encryption

### Session

**Interhost Communication**

- Establishment, maintainence, and termination of sessions between applications
- Two application processes on different machines can establish a session
- Security, name recognition, logging

### Transport

**End to End connections**

- Message segmentation (splits message to smaller units)
- Handles transportation issues between hosts
- Ensures data transport reliability

**Flow Control**

- Manage data transmission between hosts

**Session Multiplexing**

- Multiplexing several message streams or session onto one logical link

**Protocols**:

TCP (Transmission Control Protocol)

- TCP 3-way handshake
  - If packet is missing, will be retransmitted

UDP (User Datagram Protocol)

- Does not provide reliability
  - Does not transmit lost packets
- Much more leightweight than TCP

"Postal service (UDP) vs phone call (TCP)

### Network

**Data Delivery**

- Routes data packets

**Layer 3 switches**

- Have router capabilities
- Selects the best path to deliver data
  - OSPF (Open Shortest Path First)
  - BGP (Border Gateway Protocol)
  - IS-IS (Intermediate System-to-intermediate System)
- Not concerned with reliability (leaves it to higher layer protocol)

### Datalink

**Access to Media**

- Defines how data is formatted for transmission
- How access to the network is controlled

**Ethernet**

- MAC address - 48 bits
  - Identifier of a device
- Provides error detection

### Physical

**Binary Transmission**
 
- What state represents 0 or 1
- Defines the electrical, mechanical, procedural, and functional specifications for activating maintaing and deactivating the physical link
- Pins, voltage, specifications vary (copper vs fiber)
- Physical devices and physical cabling

