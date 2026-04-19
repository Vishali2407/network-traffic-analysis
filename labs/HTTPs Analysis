## HTTPS Observation

HTTPS (HyperText Transfer Protocol Secure) traffic was observed between the local machine (192.168.119.128) and external servers over TCP port 443.

A TCP three-way handshake (SYN, SYN-ACK, ACK) was established before encrypted communication began, indicating a successful connection setup.

Following this, a TLS (Transport Layer Security) handshake was observed:
- Client Hello sent by the client
- Server Hello response from the server
- Certificate exchange for authentication
- Key exchange to establish encryption

After the TLS handshake, the traffic became encrypted. Packet payloads were not readable in Wireshark, confirming secure data transmission.

The destination IP corresponds to an external server, likely hosting services for domains such as play.google.com.

This behavior indicates normal secure web communication:
- TCP ensures reliable delivery  
- TLS provides encryption and authentication  
- HTTPS protects data confidentiality  

No anomalies such as certificate errors, failed handshakes, or unusual ports were observed.
