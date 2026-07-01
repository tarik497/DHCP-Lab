# Cisco Packet Tracer – DHCP Configuration Labs

Two hands-on Cisco Packet Tracer labs demonstrating DHCP server configuration on Cisco IOS, from basic to multi-network setups.

## Labs

| Lab | Description | Link |
|---|---|---|
| **Lab 1** | DHCP server on a Cisco 2911 router serving two separate networks (`223.0.0.0/24` and `100.0.0.0/8`) via two DHCP pools. | [lab1/](./lab1) |
| **Lab 2** | Similar setup with different addressing (`192.168.1.0/24` and `128.1.0.0/16`), documented CCNA-style with full verification steps. | [lab2/](./lab2) |

Each lab folder includes:
- `DHCP.pkt` / `DHCP2.pkt` — the Packet Tracer project file
- `configs/` — full `show running-config` output from the router
- `screenshots/` — topology diagram, DHCP assignment, and ping test results
- `README.md` — full write-up: objectives, topology, configuration, verification

## Skills Demonstrated
- Cisco IOS router configuration
- DHCP pool creation across multiple networks
- IPv4 addressing and subnetting
- Network verification and troubleshooting

## Author
**Tarek Hamraoui**
