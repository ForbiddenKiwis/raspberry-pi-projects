# Pi-hole Project

## What is Pi-hole?
Pi-hole is a network-wide ad blocker that acts as a DNS sinkhole, blocking ads and tracking domains for every device on your network.

## Setup
- Device: Raspberry Pi 5
- OS: Raspberry Pi OS (64-bit)
- Installation: curl -sSL https://install.pi-hole.net | bash

## Network Configuration
- Pi-hole set as DCHP server for entire network
- Upstream DNS: Cloadflare (1.1.1.1)
- Blocklist: StevenBlack Unified Host List

## Features Enabled
- Network-wide ad blocking
- DCHP server
- Query logging
- Web dashboard at http://raspberrypi.local/admin

## Results
- Blocks approximately 20-40% of all network traffic
- Covers all devices incluiding phones and smart TVs
