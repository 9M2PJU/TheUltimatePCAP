# TheUltimatePCAP

What’s in there?
Layer 2 Protocols
ARP (request, reply, gratuitous)
CDP
DTP
LACP
LLDP
LOOP
PPP (PPPoED, LCP, IPCP, IPV6CP)
STP
UDLD
VTP
Layer 4 Protocols that are *not* TCP/UDP
6in4 [Wireshark display filter: ip.proto == 41]
AH v6 (IPv6 extension header number 51, used by OSPFv3)
EIGRP v6/v4
ESP v6/v4 (IPv6 extension header number 50)
GRE v4 (tunneling v6 and v4)
ICMPv6 (RS, RA w/ RDNSS and DNSSL, NS, NA, DAD, MLD with hop-by-hop extension header (number 0), ping, destination unreachables, packet too big, time exceeded)
ICMPv4 (ping, timestamp, destination unreachable, time-to-live exceeded)
IGMP (v1, v3)
OSPFv2 for IPv4 (MD5 authentication)
OSPFv3 for IPv6 (plain & authentication via IPsec authentication header AH)
Upper Layer Protocols based on TCP/UDP
BGP v6/v4 (MD5 authentication)
DHCPv6 (stateful, stateless, prefix delegation)
DHCPv4 (DORA, NAK)
DNS v4/v6 (tons of RRs, UDP, TCP, fragmentation, DNSSEC validation, SERVFAIL, NXDOMAIN, ENDS(0) client subnet, EDNS(0) cookie, mDNS, dynamic update, zone change notification, IXFR, AXFR, TSIG)
HRSP v6/v4
HTTP v6/v4
HTTP-Proxy v4
HTTPS aka TLS v6/v4
IKEv1 v6/v4 (aggressive mode, main mode) [Wireshark display filter: isakmp]
IKEv2 v6 [Wireshark display filter: isakmp]
IMAP v6
IP SLA v4
NetFlow v6
NTP v6/v4 (basic client-server, symmetric, control, authentication w/ md5 and sha-1 and nak, NTS with TLS 1.3)
RIP for IPv4
RIPng for IPv6
RTP v4 (VoIP calls)
SIP v4 (VoIP calls)
SMTP v6/v4 (with and without STARTTLS)
SNMPv2c v6
SSDP v4
SSH v6/v4
Syslog v6/v4
Telnet v6
TFTP v4
WHOIS v6/v4
Miscellaneous
Apple AirPlay v4
IP fragments (sourced by DNS over UDP)
IPv6 fragments (aka fragment header (44), sourced by DNS over UDP)
TCP fragmented segments
Traceroute (aka TTL trick via echo-request & TCP port 25) v6/v4
TLS v6/v4 (1.2, 1.3)
VLAN tagging
VoIP Calls v4
What’s still missing?
The following protocols and packet types are still missing.

Am I missing some more? Please write a comment below! Appreciate it!
4in6
EAPOL
GLBP
IPv6 extension headers: routing (43), destination options (60), mobility (135)
LDAP
MST
PAgP
RADIUS
RMCP+/IPMI
SNMPv3
TACACS+
TCP details & flags
VRRP
Ethernet Jumbo Frames
