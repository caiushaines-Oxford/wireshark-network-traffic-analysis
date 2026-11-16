# SOC Investigation 02 — Network Traffic Analysis Using Wireshark

## Overview
This project documents a practical SOC analyst training investigation using Wireshark to capture and analyse network traffic.

The exercise focused on DNS resolution, TCP connection establishment and HTTP requests, with an emphasis on evidence-based security analysis.

## Tools
- Wireshark
- Web browser
- Windows workstation

## Investigation Objectives
- Capture and inspect network packets
- Identify DNS queries and responses
- Analyse the TCP three-way handshake
- Identify HTTP requests
- Assess whether the recorded observations indicate suspicious activity

## Findings
| Area | Observation |
|---|---|
| DNS | AAAA query for example.com |
| DNS response | Observed |
| TCP | SYN, SYN-ACK and ACK identified |
| Destination port | 80 |
| HTTP | Requests observed |
| Security assessment | No confirmed malicious activity |

## Investigation Evidence
### DNS Analysis
![DNS Analysis](screenshots/dns-analysis.png)

### TCP Handshake
![TCP Handshake](screenshots/tcp-handshake.png)

### HTTP Requests
![HTTP Requests](screenshots/http-requests.png)

## Conclusion
The recorded traffic demonstrated DNS resolution, successful TCP connection establishment and HTTP request activity. No confirmed indicators of malicious behaviour were established from the documented observations.

This was a baseline traffic analysis exercise, not an investigation of a confirmed attack.

## Full Report
[Read the SOC Investigation Report](incident-report.md)

## Skills Demonstrated
- Network traffic analysis
- Wireshark packet inspection
- DNS analysis
- TCP and HTTP analysis
- SOC investigation documentation
- Evidence-based security assessment
