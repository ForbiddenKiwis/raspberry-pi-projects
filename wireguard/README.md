# WireGuard VPN Project

## What is WireGuard?
WireGuard is a modern, fast, and secure VPN protocol that creates
an encrypted tunnel between your device and your home network,
allowing secure access from anywhere in the world.

## Setup
- Device: Raspberry Pi 5
- OS: Raspberry Pi OS (64-bit)
- Installation: PiVPN (pivpn.io)
- Protocol: WireGuard
- Port: 51820 (UDP)

## Network Configuration
- VPN server running on Raspberry Pi 5
- Ethernet connection to router (eth0)
- Integrated with Pi-hole for ad blocking on the go
- DNS routed through Pi-hole for network-wide protection

## Features Enabled
- Encrypted VPN tunnel
- Ad blocking on mobile data via Pi-hole integration
- Secure access to home network remotely
- QR code client configuration

## How It Works
- Connect to WireGuard from anywhere
- All traffic routes through home Pi
- Pi-hole blocks ads even on public WiFi
- Appears as home IP to websites

## Files
- pivpn.sh - PiVPN installer script
