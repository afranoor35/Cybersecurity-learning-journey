# Day 4 — Subnetting & CIDR

## IPv4 Address

An IPv4 address consists of 32 bits divided into four octets.

Example:

192.168.1.10

Each octet contains 8 bits.

8 + 8 + 8 + 8 = 32 bits

## Subnet Mask

A subnet mask separates the network portion from the host portion of an IP address.

Example:

255.255.255.0

This is equivalent to:

/24

## CIDR

CIDR stands for Classless Inter-Domain Routing.

It represents the number of network bits using a slash notation.

Examples:

- /8 → 255.0.0.0
- /16 → 255.255.0.0
- /24 → 255.255.255.0
- /25 → 255.255.255.128
- /26 → 255.255.255.192
- /27 → 255.255.255.224
- /28 → 255.255.255.240

## Network and Host Portions

For:

192.168.1.20/24

- Network bits: 24
- Host bits: 8
- Subnet mask: 255.255.255.0
- Network address: 192.168.1.0

## Cybersecurity Relevance

Subnetting and CIDR are important for understanding:

- Network segmentation
- IP ranges
- Firewall rules
- Network security
- Routing
- Security monitoring
