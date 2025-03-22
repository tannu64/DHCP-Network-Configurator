# DHCP-Network-Configurator

A practical implementation of Dynamic Host Configuration Protocol (DHCP) in a client-server network topology that demonstrates automatic IP address assignment and network configuration management.

## Overview

This project demonstrates a complete DHCP setup in a simulated network environment, showcasing:

- DHCP server configuration for multiple network segments
- Automatic IP address allocation to client devices
- Handling of address conflicts and server failures
- Support for both IPv4 and IPv6 addressing

## Network Topology

The implementation features a multi-client topology with a central DHCP server that manages IP assignment across different network segments.

## Technical Details

- Server Configuration: Cisco IOS commands for DHCP pool setup
- Ports: DHCP uses UDP ports 67 (server) and 68 (client)
- Addressing: Support for up to 254 clients per subnet
- Fault Handling: Documented behavior for server failures and IP conflicts

## Implementation

The project includes CLI commands for configuring:
- Network interfaces and IP addressing
- DHCP address exclusions
- Multiple DHCP pools with custom settings
- DNS server assignments

## Screenshots

The repository includes screenshots of:
- Network topology diagram
- Successful IP address allocation to clients
- Configuration verification

## Key Learnings

- DHCP operation in enterprise networks
- Address pool management
- Network resilience for DHCP failures
- IPv6 support through DHCPv6 