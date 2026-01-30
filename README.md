# Linux Router with Wi-Fi Uplink

This repository is a documentation-based infrastructure case study.

It describes a real-world setup where a Linux server is used as a router:
- Internet uplink via Wi-Fi (USB adapter)
- LAN distribution via Ethernet
- DHCP and DNS handled by Pi-hole
- Configuration survives reboot

No automation scripts are included by design.

## Goals

- Use a Linux server as a network edge device
- Understand packet flow between Wi-Fi and Ethernet
- Build a stable and reboot-safe configuration
- Avoid hidden behavior from network managers

## Documentation

- [Overview](docs/overview.md)
- [Architecture](docs/architecture.md)
- [Implementation](docs/implementation.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Notes](docs/notes.md)
