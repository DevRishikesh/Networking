# Router vs Switch vs Hub
This comparison helps you understand the difference between **Router**, **Switch**, and **Hub** — three essential network devices.
## Quick Comparison Table
| Feature               | Hub                          | Switch                             | Router                              |
|-----------------------|-------------------------------|-------------------------------------|--------------------------------------|
| OSI Layer             | Layer 1 (Physical)            | Layer 2 (Data Link)                 | Layer 3 (Network)                    |
| Function              | Connects devices in LAN       | Connects devices & manages traffic | Connects different networks (LAN ↔ WAN) |
| Data Forwarding       | Broadcasts to all ports       | Forwards to specific MAC address    | Routes based on IP address           |
| Intelligence          | No                            | Yes (MAC address table)             | Yes (Routing table, NAT, DHCP)       |
| Bandwidth Sharing     | Shared                        | Dedicated per port                  | Dedicated per network path           |
| Collision Domain      | One for all ports             | One per port                        | One per port                         |
| Broadcast Domain      | One                           | One                                 | Each interface = separate domain     |
| Speed & Efficiency    | Lowest                        | High                                | Very High                            |
| Security              | None                          | Basic (segmentation)                | High (firewall, NAT)                 |
| Use Case              | Obsolete                      | LAN communication                   | Internet access, inter-networking    |
## Summary
- **Hub** is a basic, outdated device that blindly sends data to all devices.
- **Switch** is smarter it learns MAC addresses and sends data only where needed.
- **Router** is the smartest it connects different networks (like your LAN to the internet), routes data using IP addresses, and adds security.
