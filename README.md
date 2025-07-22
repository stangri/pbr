# Policy-Based Routing (pbr)

[![OpenWrt](https://img.shields.io/badge/OpenWrt-Compatible-blueviolet)](https://openwrt.org)
[![Web UI](https://img.shields.io/badge/Web_UI-Available-blue)](https://docs.openwrt.melmac.net/pbr/)
[![License](https://img.shields.io/badge/License-GPL--3.0-lightgrey)](https://github.com/stangri/pbr/blob/master/LICENSE)

Flexible rule-based routing framework for OpenWrt.  
Route traffic based on IP, MAC, port, protocol, or domain through WAN, VPNs, or tunnels.

For the current stable release, see the [1.1.8 branch](https://github.com/stangri/pbr/blob/1.1.8/README.md).  
For ongoing development, see the [1.1.9 branch](https://github.com/stangri/pbr/blob/1.1.9/README.md).

## Highlights

- Supports WAN, OpenVPN, WireGuard, and tunnel interfaces
- Create rules by IP, MAC, port, protocol, or domain
- Integrates with dnsmasq, unbound, and smartdns
- Optional LuCI interface for configuration and monitoring
- Resolver health checks and rule-based rollback

**Full documentation:**  
[https://docs.openwrt.melmac.net/pbr/](https://docs.openwrt.melmac.net/pbr/)
