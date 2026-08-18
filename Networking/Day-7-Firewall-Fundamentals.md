# Day 7 — Firewall Fundamentals

## What is a Firewall?

A firewall is a security mechanism that controls network traffic based on predefined rules.

It can allow or block traffic based on factors such as:
- Source IP address
- Destination IP address
- Port
- Protocol
- Traffic direction

## Inbound vs Outbound Traffic

### Inbound
Traffic coming into a computer or network from another system.

### Outbound
Traffic leaving a computer or network toward another system.

## Firewall Rules

Firewall rules can specify whether particular network traffic should be allowed or blocked.

For example:

TCP + Port 443 + Allow

This can represent allowing HTTPS-related traffic.

## Firewall vs Antivirus

A firewall primarily controls network traffic.

Antivirus or endpoint security focuses on detecting and protecting against malicious software and activity.

## Windows Firewall Practical

I explored Windows Defender Firewall with Advanced Security and observed:

- Inbound Rules
- Outbound Rules
- Firewall profiles
- Network traffic rules

I also used:

netsh advfirewall show allprofiles

to view the firewall profile status.

## Cybersecurity Relevance

Understanding firewalls is important for:

- Network security
- Access control
- Traffic filtering
- Incident investigation
- Reducing unnecessary network exposure

## Key Takeaway

A firewall helps control which network traffic is permitted or blocked according to security rules.
