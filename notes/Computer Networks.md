
## Computer Networks

### High-Yield Topics

- OSI and TCP/IP layers and mapping
- Switching: circuit switching vs packet switching
- TCP vs UDP
- IP addressing basics, subnet masks, routing intuition
- ARP, DNS, DHCP, NAT basics
- Reliable transport, flow control, congestion control
- Error detection basics: parity, checksum, CRC
- Common protocols: HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS
- Devices: hub, switch, router, gateway

### Revision Notes

#### Layer Mapping

| OSI Layer | Main Responsibility |
|---|---|
| Application | End-user network services |
| Presentation | Data representation, translation |
| Session | Session management |
| Transport | End-to-end delivery |
| Network | Logical addressing and routing |
| Data Link | Framing, MAC addressing |
| Physical | Bits on medium |

#### TCP vs UDP

| Feature | TCP | UDP |
|---|---|---|
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable | Best-effort |
| Ordering | Ordered delivery | No guarantee |
| Speed/overhead | Higher overhead | Lower overhead |
| Typical use | Web, file transfer | Streaming, DNS, gaming |

#### Device Comparison

| Device | Layer Focus | Main Role |
|---|---|---|
| Hub | Physical | Broadcast bits |
| Switch | Data Link | Forward frames using MAC |
| Router | Network | Forward packets using IP |
| Gateway | Multiple / translation | Protocol or network translation |

> Common trap: A switch is not a router. Switches typically use MAC addresses, while routers use IP addresses.

#### Memory Tricks

- TCP = reliable and ordered
- UDP = lightweight and fast
- DNS resolves names
- DHCP gives addresses
- ARP maps IP to MAC in local network context

### Practice MCQs

#### MCQ 1

Which layer is responsible for routing packets across networks?

A. Transport layer  
B. Application layer  
C. Network layer  
D. Presentation layer

**Answer:** C  
**Explanation:** Routing and logical addressing belong to the network layer.

#### MCQ 2

Which protocol is typically used to resolve domain names into IP addresses?

A. SMTP  
B. DNS  
C. ARP  
D. FTP

**Answer:** B  
**Explanation:** DNS translates hostnames into IP addresses.

#### MCQ 3

Which statement about TCP is correct?

A. It is connectionless and unreliable  
B. It provides ordered, reliable byte-stream delivery  
C. It works only on local area networks  
D. It does not perform flow control

**Answer:** B  
**Explanation:** TCP establishes a connection and provides reliable transport with ordering.

#### MCQ 4

A switch primarily forwards data based on:

A. Port number  
B. Domain name  
C. MAC address  
D. Process ID

**Answer:** C  
**Explanation:** Ethernet switches make forwarding decisions using MAC addresses.

#### MCQ 5

Which protocol dynamically assigns IP addresses to hosts?

A. DHCP  
B. DNS  
C. HTTP  
D. ARP

**Answer:** A  
**Explanation:** DHCP automates address allocation and related configuration.

#### MCQ 6

Which of the following best fits UDP use?

A. Situation requiring strict in-order guaranteed delivery  
B. File transfer requiring reliability  
C. Latency-sensitive communication where some loss is acceptable  
D. Database transaction commit protocol only

**Answer:** C  
**Explanation:** UDP is often preferred when low latency matters more than perfect reliability.

#### MCQ 7

ARP is used to:

A. Map a domain name to IP address  
B. Map an IP address to a MAC address on a local network  
C. Encrypt packets end to end  
D. Assign CPU time slices

**Answer:** B  
**Explanation:** ARP resolves a local network-layer address to link-layer hardware address.

#### MCQ 8

Which device operates mainly at the network layer?

A. Hub  
B. Router  
C. Repeater  
D. Bridge only at physical layer

**Answer:** B  
**Explanation:** Routers examine IP information to forward packets between networks.

### Summary Sheet

- Memorize layer responsibilities and common protocols.
- Rehearse TCP vs UDP, switch vs router, DNS vs DHCP vs ARP.
- Expect definition, mapping, and scenario-based protocol MCQs.
