# Implementation

## Network interface configuration

The LAN interface is configured manually to:
- prevent automatic gateway assignment
- avoid DNS injection
- remain stable across reboots

## Packet forwarding

IP forwarding is enabled explicitly at the kernel level.

## NAT

Source NAT is applied on the Wi-Fi uplink interface.
Forwarding rules are restricted to LAN ↔ uplink traffic.

## Persistence

Firewall rules are persisted to survive reboots.
