*This project has been created as part of the 42 curriculum by codewithhippo17.*

## Description

**netPractice** is a hands-on networking fundamentals project from the 42 curriculum. The goal is to configure small-scale networks and understand how TCP/IP addressing works in practice. Through 10 progressive levels, you'll master essential networking concepts including IP addressing, subnet masks, default gateways, routing, and network segmentation.

This project provides a browser-based training interface where you configure network topologies, assign IP addresses, and set up routing rules. Each level increases in complexity, challenging you to apply networking principles to solve real-world connectivity problems.

By completing this project, you'll gain practical understanding of how data flows through networks, how devices communicate within and across networks, and how network engineers design and troubleshoot IP networks.

---

## Instructions

### Running the Training Interface

1. Download or clone the netPractice training interface (typically provided by 42)
2. Open the `index.html` file in your web browser
3. Navigate through levels 1-10, configuring network settings as required
4. Each level presents a network diagram with configurable fields (IP addresses, subnet masks, routes)

### Exporting Configurations

1. After successfully completing each level, **export** the configuration
2. Save the exported JSON file with the naming format: `levelX.json` (where X = 1 to 10)
3. Place all exported configuration files in the root of your Git repository

### Submission Requirements

- ✅ Complete all 10 levels
- ✅ Export 10 configuration files: `level1.json`, `level2.json`, ..., `level10.json`
- ✅ Place all configuration files at the **repository root**
- ✅ Include this README.md with proper documentation
- ✅ Push everything to your Git repository for evaluation

**Files required at repository root:**
```
level1.json
level2.json
level3.json
level4.json
level5.json
level6.json
level7.json
level8.json
level9.json
level10.json
README.md
```

---

## Resources

### Networking Concepts Studied

This project covers the following core networking concepts:

- **TCP/IP Addressing**: Understanding IPv4 address structure, network and host portions
- **Subnet Mask**: Calculating network boundaries, subnet division, and CIDR notation
- **Default Gateway**: Configuring routers as gateways for inter-network communication
- **Routers**: Routing tables, static routes, and packet forwarding decisions
- **Switches**: Layer 2 switching and local network connectivity
- **OSI Layers**: Focus on Layer 2 (Data Link), Layer 3 (Network), and Layer 4 (Transport)
- **Network Segmentation**: VLANs and logical network separation
- **ARP and DHCP**: Address resolution and dynamic IP configuration
- **DNS**: Domain name resolution
- **NAT**: Network Address Translation for internet connectivity

### Classic References

- [VLANs Video Tutorial](https://www.youtube.com/watch?v=Pm46mFfrK5g&list=PLHh55M_Kq4OCZOAxs2KZyCawhX38YR154&index=2)
- [VLAN Basics - Thomas Krenn](https://www.thomas-krenn.com/en/wiki/VLAN_Basics)
- [OSI Model - GeeksforGeeks](https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/)
- [TCP/IP Part 1 Video](https://www.youtube.com/watch?v=gYmqYHlQWT4&list=PLHh55M_Kq4OCZOAxs2KZyCawhX38YR154&index=7)
- [TCP/IP Part 2 Video](https://www.youtube.com/watch?v=N9DzIK-eeBk&list=PLHh55M_Kq4OCZOAxs2KZyCawhX38YR154&index=8)
- [Subnet Mask Calculator](https://www.calculator.net/ip-subnet-calculator.html)
- [IPv4 Subnetting - Cisco Documentation](https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html)

### AI Usage Disclosure

**AI tools were used in this project for the following purposes:**

used AI tools mainly as helpers to extract *Wisdom* from videos and find the best resources to support my learning. AI also gave a hand in structuring the docs and making explanations a bit clearer, but it wasn’t doing the thinking for me. Everything else solving the network configurations, drawing my own diagrams, asking questions to peers, Googling, reading, and really understanding the concepts was all done by me.
---

## 📖 Documentation

This repository includes comprehensive documentation on networking fundamentals. Explore the topics below to deepen your understanding:

### 🔰 Network Fundamentals

1. **[Physical vs Logical Addressing](./docs/physical-vs-logical-addressing.md)** 🏷️  
   Understanding MAC addresses, IP addresses, and subnet masks

2. **[ARP and DHCP](./docs/arp-and-dhcp.md)** 🔄  
   How devices discover each other and get network configuration

3. **[Local vs Remote Communication](./docs/local-vs-remote-communication.md)** 📡  
   Understanding when traffic stays local or goes through a gateway

4. **[DNS (Domain Name System)](./docs/dns.md)** 🌍  
   How hostnames become IP addresses

5. **[ISP and Router](./docs/isp-and-router.md)** 🔌  
   Default gateway, NAT, and connecting to the internet

6. **[VLANs (Virtual LANs)](./docs/vlans.md)** 🔐  
   Network segmentation and security

### 📦 OSI Model & Packet Anatomy

7. **[OSI Model Overview](./docs/osi-model-overview.md)** 📊  
   How data flows through the 7-layer OSI model

8. **[Application Layer](./docs/application-layer.md)** 💻  
   HTTP, DNS, FTP, and other application protocols

9. **[Presentation and Session Layers](./docs/presentation-and-session-layers.md)** 🔒  
   Data formatting, encryption, and session management

10. **[Network Packet Anatomy](./docs/network-packet-anatomy.md)** 📮  
    Inside look at how packets are structured

### 🚀 Transport Layer Protocols

11. **[TCP vs UDP](./docs/tcp-vs-udp.md)** ⚡  
   Comparing reliable and unreliable transport protocols

12. **[TCP Connection Lifecycle](./docs/tcp-connection-lifecycle.md)** 🔄  
   Three-way handshake, connection states, and termination

13. **[Protocols Reference](./docs/protocols-reference.md)** 📚  
   Complete table of protocols used across OSI layers

---

## 🎯 Quick Reference

| Topic | Key Concepts |
|-------|-------------|
| **Addressing** | MAC addresses, IP addresses, subnet masks |
| **Discovery** | ARP, DHCP, DNS |
| **Routing** | Default gateway, NAT, ISP |
| **Security** | VLANs, network segmentation |
| **OSI Model** | 7 layers of network communication |
| **Protocols** | TCP, UDP, HTTP, FTP, SSH, and more |

---

## 🚀 Getting Started

Start your networking journey by exploring the topics in order, or jump directly to any concept you'd like to learn more about. Each page includes navigation links to help you move through the documentation seamlessly.

Happy Learning! 📖✨
