# Communications and Network Security

## Elevator pitch
This domain foucuses on communications over the network as obviously stated. Less obviously stated, this include a lot of content on the OSI layers and the protocols that exist within each of them. Are you going to have to know all 65536 TCP and UDP ports? No. Are you going to need to distinguish protocols or technology used in each layer? More than likely.

## Topics

**OSI Layers**

- Application: This is where you interface with the application layer. An FTP program, your browser, etc.
- Presentation: Presents data to the applcation and user in a comprehensible way. Think image formats
- Session: Manages sessions for connections between applications such as Remote Procedure Calls (RPC).
- Transport: Handles Packet Sequencing, flow control and error detection. Encapsulation is in Segments. Think TCP/UDP ports
- Network: Describes routing from one LAN to another. Encapsulation is in Packets. Think IP addresses, Routers
- Data Link: Divided into Media Access Control (MAC) and Logical Link Control (LLC). Encapsulation is in Frames. Think Switches.
- Physical: Cabling, and cabling standards. Encapsulation is in Bits. Think Ethernet, Fiber Optic Cables.

**Network Devices**
- Hubs/Repeaters: Layer 1 device. Receives bits on one port, sends on another.
- Switches: Layer 2 device. Provides traffic isolation associateing the MAC address of each connected device with its port on the switch.
- Bridges: Layer 2 device. A bridge has two ports and two collision domains.
- Routers: Layer 3 device. 

## RFC 1918 (Private Address Spaces)

- Class A: 10.0.0.0 - 10.255.255.255 (10/8 prefix)
- Class B: 172.16.0.0 - 172.31.255.255 (172.16/12 prefix)
- Class C: 192.168.0.0 - 192.168.255.255 (192.168/16 prefix)

## IP Address Classes

## TCP Three Way handshake
- SYN: Connection between a client and server are established
- SYN/ACK: Server receives SYN packet and returns an Acknowledgement receipt to the Client
- ACK: Client receives the SYN/ACK from the server and responses with an ACK packet

## Firewalls
- Packet Filtering: Oldest and most basic firewalls that check the source and destination IP/Port to determine whether to allow or deny passage.
- Circuit Level Gateway: Works at the session layer, verify and keep track of active sessions using minimal resources. Not reliable for inspecting packets for Malware
- Stateful Inspection: Inspects packets; however consume more resources, thus vulnerable to DDoS attacks
- Application level gateways: aka Proxy Firewalls. Connections go through this firewall which perform stateful inspection of packets

## Useful Links

- [Back to the YouTube Video]()
- [Inside Cloud and Security - Domain 4](https://www.youtube.com/watch?v=-b-BbFv7eI8)
- [RFC 1918](https://datatracker.ietf.org/doc/html/rfc1918)
- [Subnetting Basics](https://docs.microsoft.com/en-us/troubleshoot/windows-client/networking/tcpip-addressing-and-subnetting)
- [Common Network Ports](https://web.mit.edu/rhel-doc/4/RH-DOCS/rhel-sg-en-4/ch-ports.html)
- [What are the basic Types of Firewalls](https://www.parallels.com/blogs/ras/types-of-firewalls/)
- [Three Way Handshake](https://www.techopedia.com/definition/10339/three-way-handshake)

