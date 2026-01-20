# ISP and Router (Default Gateway)

The **ISP** provides your connection to the internet and assigns your router a **public IP address**. Inside your network, devices use **private IPs** that cannot be reached directly from the internet.  

The **router**, also called the **default gateway**, forwards traffic that leaves the local network. Local traffic stays within the subnet, but if a destination is remote, the computer sends packets to the router's **MAC address**, letting the router handle the rest.  

Through **NAT (masquerading)**, the router replaces the devices' private IPs with its public IP when sending traffic to the internet. Responses return to the router, which then delivers them to the correct device. Most of the router's configuration is handled by the **ISP**, keeping the process simple for the user.

![Packet Anatomy](../attchements/netBasics.png)

---

[← Back to Main](../README.md) | [Previous: DNS](./dns.md) | [Next: VLANs →](./vlans.md)
