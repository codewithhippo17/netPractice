# DNS (Domain Name System)

**DNS (Domain Name System)** maps stable, human-readable **hostnames** to **IP addresses** that may change over time due to **DHCP**. When a device connects, **DHCP** provides both an **IP address** and the **DNS server** address. Communication follows this chain:  
``Hostname → DNS → IP  → ARP → MAC``  
Local **hostnames** are resolved internally, while external domains are forwarded to public DNS servers.

``8.8.8.8`` is a **public DNS server** used when your local **DNS** cannot resolve a domain. Your computer asks its **DNS server** (given by **DHCP**), which forwards the request to ``8.8.8.8``. Google's **DNS** resolves the **hostname** into an **IP address** and sends it back, allowing communication to continue.

---

[← Back to Main](../README.md) | [Previous: Local vs Remote Communication](./local-vs-remote-communication.md) | [Next: ISP and Router →](./isp-and-router.md)
