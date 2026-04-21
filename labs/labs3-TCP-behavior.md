## TCP Behavior Analysis

TCP (Transmission Control Protocol) traffic shows a standard connection-oriented communication pattern.

A three-way handshake was observed:
- The client (192.168.119.128) initiated the connection with a SYN packet
- The server responded with a SYN-ACK packet
- The client completed the handshake with an ACK packet

This confirms successful session establishment between the client and the destination IP.

After the handshake, data transfer occurred with:
- ACK packets confirming receipt of data
- PSH-ACK packets indicating active data transmission

Sequence numbers and acknowledgment numbers were used to ensure reliable delivery of packets.

The session was properly terminated using FIN-ACK packets, indicating a clean connection closure.

No abnormal behavior such as excessive retransmissions, resets (RST), or failed handshakes was observed, suggesting stable and normal TCP communication.

## Screenshots
![TCP behavior](screenshots/TCP-behavior.png)
