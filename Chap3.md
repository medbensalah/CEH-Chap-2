# Scanning
______________________________________________

2nd step in the attack lifecycle.\
Make sure the host is available.
 - Scanning IPs
 - Identifying open ports.
 - Identifying services running on default ports
 - Check against DBs.
 - Try to identify the version and show its CVEs otherwise they show all CVEs for the service.
 - Identify ping by 
   - TTL (Time To Live)
     - 128 for Windows.
     - 64 for Linux.
   - TCP windows : more accurate
<br>
<br>
 - Legion : Collection of tools.
 - Nessus
 - Coalis
 - metasploit

### Types of scanning
 - Port scanning
 - Host / network scanning
 - Network scanning

### Tools
 - nmap
   - -o minimum information
   - chneck open posrt and running services
   - change config
   - request cooldown
   - mimic traffic
   - default port : 40125
 - Zenmap : GUI for nmap
 - Hping2 / Hping3
   - CLI for network crafting
   - regular scans
     - ICMP
     - ACK (TCP)
     - UDP
     - scene scans
     - SIN an entire range
     - intercept traffic
   - DoS : SIN Flooding
 - metasploit

### Host discovery techniques
 - ARP :
   - table for IP - MAC address resolution\
   - ARP spoofing.
   - 192.168.  /  172.  /  10.  Non routable IPs. Decided by the DHCP

_______________________________________

## Side notes
 - Port forwarding : from router to specific internal IP\
 - DMZ
 - DHCP not used for servers.
 - RFC 1918
