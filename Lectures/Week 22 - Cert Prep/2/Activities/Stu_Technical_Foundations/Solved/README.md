# CEH Quiz - Technical Foundations

## questions
- Which of the following packets came from a private network?
  - [ ] `12.27.3.3`
  - [ ] `172.217.12.174`
  - [ ] `66.108.36.233`
  - [x] `192.168.15.98`

- Which DNS record contains administrative contact information?
  - [ ] A Record
  - [ ] AAAA Record
  - [x] SOA
  - [ ] CNAME Record

- Suppose an attacker has infiltrated a LAN, and wants to redirect traffic from another user's machine to her own. The attacker and her target are on the same local network, which sits behind a NAT-ting router and firewall. Which of the following techniques is the attacker most likely to use?
  - [ ] Kerberos Golden Ticket
  - [ ] DNS Spoofing
  - [x] ARP Spoofing
  - [ ] Pass the Hash Attack

- At which layer of the OSI model does a DNS hijacking attack occur?
  - [ ] Layer 4
  - [ ] Layer 6
  - [x] Layer 7
  - [ ] Layer 2

- Which of the following best describes the practice of exposing _only_ the minimum number of ports, services, and applications required?
  - [x] Principle of Least Privilege
  - [ ] Access Control List
  - [ ] Defense in Depth
  - [ ] Deny All By Default

- Which of the following tools would you use to look for evidence of suspicious activity in system log files?
  - [ ] `nc`
  - [ ] `nmap`
  - [x] `grep`
  - [ ] `kismet`

- Which of the following protocols can be exploited by manipulating sequence and acknowledgement numbers?
  - [ ] ARP
  - [x] TCP
  - [ ] UDP
  - [ ] IP

- This protocol allows computers to automatically acquire IP addresses when joining a network.
  - [ ] DNS
  - [ ] RIPv2
  - [ ] DoS
  - [x] DHCP

- Traceroute uses which kind of ICMP packet to determine routing paths?
  - [ ] Type 8
  - [ ] Type 4
  - [x] Type 3
  - [ ] Type 9

- Which attack is most similar to ARP Poisoning?
  - [x] DNS Hijacking
  - [ ] DHCP Flooding
  - [ ] Zone Transfer
  - [ ] Eternal Blue

- Which flag is set on a packet returned from a closed port?
  - [ ] PSH
  - [x] RST
  - [ ] URG
  - [ ] SYN

- Suppose you perform an Nmap scan against a machine behind a firewall that drops all packets to your target. How can Nmap tell that the machine isn't reachable?
  - [ ] It looks for RST flags in the response
  - [x] It waits for a response, but reports the host as unreachable after a timeout
  - [ ] It attempts to ping other hosts with similar IP addresses
  - [ ] It determines if the routing path to the target machine is broken

- Check all tools you might use to perform DNS Enumeration.
  - [x] `dnsrecon`
  - [x] `nslookup`
  - [ ] `aircrack-ng`
  - [x] `dig`

- In which stage of a penetration test does an attacker attempt to gain access to a system?
  - [ ] Maintaining Access
  - [ ] Post-Exploitation
  - [x] Exploitation
  - [ ] Reconnaissance

- Which framework provides guidelines for security assessments?
  - [x] NIST SP 800-115
  - [ ] NIST Open Assessment Guidelines
  - [ ] NIST SP 909
  - [ ] NIST SP 110

- Which of the following is _not_ a section of the OSSTMM?
  - [ ] Defining a security test
  - [ ] Wireless security testing
  - [x] Engagement Negotiations
  - [ ] Human security testing

- Which protocol works at Layer 5 of the OSI model?
  - [x] NetBIOS
  - [ ] UDP
  - [ ] ARP
  - [ ] IP

- Which protocol works at Layer 3 of the OSI model?
  - [ ] DNS
  - [s] IP
  - [ ] TCP
  - [ ] SNMP

- Check all protocols that can be useful for network enumeration.
  - [x] SMB
  - [ ] HTTP
  - [x] SMTP
  - [x] SNMP

- Which two layers of the OSI model are _not_ layers of the TCP/IP model?
  - [ ] Application
  - [x] Presentation
  - [ ] Network
  - [x] Session

- Which of the following is the correct syntax to attempt a Zone Transfer against the domain `foosports.com` using the name server `ns.foosports.com`?
  - [ ] `dig @ns.foosports.com -t axfr `
  - [x] `dig AXFR foosports.com @ns.foosports.com`
  - [ ] `nslookup foosports.com`
  - [ ] `nslookup @ns.foosports.com -t AZFR foosports.com`
  