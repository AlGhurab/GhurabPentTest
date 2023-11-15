# NMAP Utilization

## PROTOCOLS
# TCP- Transmission Control Protocol:  Handshakes follow the process of [SYN], [SYN, ACK], [ACK] (Client <-> Server)
# UDP- User Datagram Protocol: No handshake, performance based but no guarantee of packet reaching dest.
# ICMP- Internet Control Message Protocol: Tests connectivitiy
# ARP- Address Resolution Protocol: Maps IPv4 addresses to MAC addresses. ARP tables are preserved

1. arp-scan <IP>/24
2. nmap -sn <IP>/24 (IP+MacAddresses+ICMP+Arp)
3. nmap -sS <IP>/24 (Port scan/SYN-Stealth scan)
4. nmap -sU -T2 <IP>/24 (UDP port scan)
5. nmap --top-ports 100 -T3 <IP>/24 
6. nmap -sV <IP>/24 (Version of service)
7. nmap -p <p1>,<p2>,...<pN> (specific ports)
8. nmap -O <IP>/24 (Operating System ID)
9. nmap -sC (Category Scan)
10. nmap --script <name> <IP> (Vulnerability script)
11. nmap --script <name> -script-args <args>


