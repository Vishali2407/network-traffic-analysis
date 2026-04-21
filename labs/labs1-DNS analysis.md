# Lab 1 - DNS Traffic Analysis

## Objective
Analyze DNS traffic using Wireshark.

## Environment
- Tool: Wireshark
- IP Address: 192.168.119.128

## Filters Used
dns

## Observations
- Source IP: 192.168.119.128
- Destination IP: 192.168.119.2
- Query Name: play.google.com
- Record Type: type A
- Response IP: 142.251.221.206

## Analysis

A DNS (Domain Name System) query was initiated from the source IP 192.168.119.128 (client) to the destination IP 192.168.119.2 (local DNS server) over UDP (User Datagram Protocol) port 53.

The client requested resolution for the domain "play.google.com" using an A record (IPv4 address lookup). The DNS server responded with the IP address 142.251.221.206.

This indicates a standard DNS query-response process:
- The client sends a query to resolve a domain name
- The DNS server processes the request
- The server returns the corresponding IP address

The destination IP (192.168.119.2) suggests the request was handled by a local gateway or internal DNS resolver rather than a public DNS server.

No abnormal behavior was observed. The traffic follows a normal DNS resolution pattern with a valid request and corresponding response.
## Screenshots
![DNS Screenshot](screenshots/dns-1.png)
![DNS Screenshot](screenshots/dns-2.png)
