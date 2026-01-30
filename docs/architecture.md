# Architecture

## High-level topology

Internet

↑

Wi-Fi (USB adapter)

↑

Linux Server (Router)

↑

Ethernet (LAN)

↑

Access Point / Switch

↑

Clients

## Design decisions

### One interface — one subnet
Each network interface is bound to a single subnet.
Mixing multiple subnets on the same interface was avoided.

### Explicit routing
No interface is allowed to install default routes implicitly.

### External DHCP and DNS
Pi-hole is used as a single source of truth for:
- DHCP
- DNS
