# network-engineering-labs
Hands-on networking, systems administration, troubleshooting, and cloud infrastructure labs
# Lab 01 — Network Fundamentals & Troubleshooting

## Objective

Build and troubleshoot a basic IPv4 network using a Cisco router,
Cisco switch, and two endpoint devices.

## Technologies

- IPv4
- TCP/IP
- Subnetting
- Default Gateway
- ARP
- ICMP
- Ping
- Tracert
- DNS
- DHCP concepts
- Cisco IOS

## Network Topology

Router
|
Switch
|-- PC-01
|-- PC-02

## IP Addressing

| Device | IP Address | Subnet Mask | Gateway |
|---|---|---|---|
| Router | 192.168.10.1 | 255.255.255.0 | N/A |
| PC-01 | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |
| PC-02 | 192.168.10.20 | 255.255.255.0 | 192.168.10.1 |

## Troubleshooting Exercise

PC-02 was intentionally moved to the 192.168.20.0/24 network.

This caused connectivity failure because PC-01 and PC-02
were placed on different IP networks without a routing path.

## Commands Used

ipconfig
ipconfig /all
ping
tracert
nslookup
arp -a
route print

## Skills Demonstrated

- IPv4 configuration
- Network troubleshooting
- Connectivity testing
- Basic Cisco IOS
01-networking-fundamental/ screenshots

<img width="4032" height="3024" alt="03-troubleshooting-ip-mismatch" src="https://github.com/user-attachments/assets/146b31d1-1b82-40b2-b49c-d8f413ac6092" />
<img width="4032" height="3024" alt="02-working-connectivity" src="https://github.com/user-attachments/assets/affe826a-9ca0-4e33-8bd3-abdfd5893b23" />
<img width="4032" height="3024" alt="01-network-topology" src="https://github.com/user-attachments/assets/838b5bbd-c934-4cee-a108-8985de68dd9d" />

