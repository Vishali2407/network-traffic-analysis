## Observations

- Source IP: 192.168.119.128  
- Destination IP: 142.250.71.99  
- Protocols observed: DNS (Domain Name System), TCP (Transmission Control Protocol) 
- Ports used: 53 (DNS), 443 (HTTPS)  
- Traffic type: Outbound communication from local machine to external servers  

## Analysis

The captured traffic shows communication between the local machine (192.168.119.128) and external servers on the internet.

DNS queries were observed where the client requested domain resolution for external domains. The DNS server responded with corresponding public IP addresses.

Following DNS resolution, TCP connections were established with external IP addresses using port 443, indicating encrypted HTTPS communication. The TCP three-way handshake (SYN, SYN-ACK, ACK) confirms successful connection establishment.

The traffic pattern indicates normal external communication:
- DNS used for domain resolution  
- TCP used for reliable connection  
- HTTPS used for secure data transmission  

No immediate anomalies such as repeated failed connections, unusual ports, or suspicious IP addresses were observed.
