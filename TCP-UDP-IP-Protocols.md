# Understanding TCP/IP Protocols

### Protocols working at different layers in [TCP/IP Model](https://github.com/ShubhamJagtap2000/Computer-Networking/blob/main/The-TCP-IP-Model.md) are parts of TCP/IP stack

**TCP protocol works at transport layer and IP protocol works at network layer

**1. Transport Layer**
- TCP: Transmission Control Protocol
- UDP: User Datagram Protocol

| TCP | UDP |
| --- | --- |
| Connection Oriented(establishes connection and sends data packets) | Not Connection Oriented(sends data packets without any connection) |
| Reliable | Not Reliable |
| Slow and Heavy | Fast and Lightweight |

**2. Network Layer**
- DHCP: Dynamic Host Configuration Protocol(allots IP addresses to devices)
- IP: Internet Protocol(Responsible for routing of data packets)

**Other protocols working at Network Layer**
- ARP: Address Resolution Protocol(For mapping the IP anndress to MAC address)
- ICMP: Internet Control Message Protocol(For debugging network stability & deliverability)
