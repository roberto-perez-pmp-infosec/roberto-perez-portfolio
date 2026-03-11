# Network Traffic Analysis Using Wireshark

## Overview

This project demonstrates packet-level analysis of network traffic using Wireshark to identify anomalies and potential security issues.

## Tools

- Wireshark
- Packet capture files (PCAP)

## Analysis Process

1. Imported PCAP files into Wireshark
2. Filtered traffic by protocol and IP address
3. Identified suspicious communication patterns
4. Examined packet payloads for anomalies

## Key Observations

The analysis revealed:

- Repeated DNS queries from a single host
- Suspicious outbound connections
- Clear text credential transmission

## Security Implications

Unencrypted credentials and abnormal network behavior could indicate compromised systems or insecure application design.

## Recommended Controls

- Enforce TLS encryption
- Monitor DNS traffic patterns
- Implement intrusion detection systems
- Harden endpoint security

## Lessons Learned

Packet-level analysis provides deep visibility into network activity and can uncover threats that are not immediately visible in higher-level logs.
