# Day 6 — NAT, Private/Public IP & Routing

## Private IP Address

A private IP address is used inside a local network.

Common private IPv4 ranges include:

- 10.0.0.0/8
- 172.16.0.0/12
- 192.168.0.0/16

Private IP addresses are not directly routable on the public Internet.

## Public IP Address

A public IP address is used to identify a network/device on the Internet.

It is generally assigned by an Internet Service Provider (ISP).

## NAT

NAT stands for Network Address Translation.

NAT allows devices using private IP addresses to communicate with external networks by translating private addresses to a public address.

Example:

Private IP → Router/NAT → Public IP → Internet

## PAT

PAT (Port Address Translation) allows multiple devices on a private network to share one public IP address by using different port numbers.

This is commonly used in home and small office networks.

## Default Gateway

The default gateway is usually the router that forwards traffic from a local network to other networks.

Example:

Computer → Default Gateway → Internet

## Routing

Routing is the process of determining where network packets should be forwarded to reach their destination.

Routers use routing information to forward packets between different networks.

## Practical Learning

I explored my computer's network configuration and learned how:

- Private IP addresses identify devices inside a local network
- The default gateway connects the local network to other networks
- NAT allows private networks to communicate with the Internet
- Routing determines the path packets take toward their destination

## Cybersecurity Relevance

Understanding NAT and routing is important for:

- Network security
- Firewall configuration
- Network troubleshooting
- Traffic analysis
- Understanding network architecture
- Security monitoring

## Key Takeaway

Private IP addresses are used inside local networks, while NAT and routing help devices communicate with external networks and the Internet.
