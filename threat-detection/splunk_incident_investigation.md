# SIEM Threat Investigation Using Splunk

## Overview

This project demonstrates how a Security Information and Event Management (SIEM) platform can be used to investigate suspicious activity and identify potential security incidents.

The investigation simulated abnormal network behavior within log data.

## Tools

- Splunk
- Windows event logs
- Firewall logs
- Network traffic logs

## Investigation Process

1. Ingested system and network logs into Splunk
2. Built queries to detect suspicious behavior
3. Investigated unusual login attempts and traffic patterns
4. Correlated events across multiple log sources

## Key Indicators Identified

Indicators of compromise included:

- Multiple failed login attempts from external IP addresses
- Suspicious authentication activity outside normal business hours
- Unusual traffic patterns from internal hosts

## Response Actions

Recommended actions included:

- Locking compromised accounts
- Updating firewall rules
- Enabling multi-factor authentication
- Expanding logging coverage

## Lessons Learned

Centralized logging dramatically improves incident detection capabilities.

SIEM platforms allow analysts to correlate events across multiple systems to identify potential threats more efficiently.
