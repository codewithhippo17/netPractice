# VLANs (Virtual Local Area Networks)

**VLANs** separate networks logically, creating "virtual switches" inside a physical switch to improve **security** and limit **broadcast traffic**. Packets are tagged with a **VLAN ID (802.1Q)**, and switches enforce boundaries by discarding packets sent to the wrong VLAN. Ports can be **Access (untagged)** for standard devices, where the switch handles tagging automatically, or **Trunk (tagged)** for connecting switches or VLAN-aware servers, preserving VLAN tags. Servers can participate in multiple VLANs using **virtual interfaces** (e.g., ``eth0.2``, ``eth0.3``) with separate IPs. Basic switches assign VLANs by port, while smart or industrial switches can follow devices via **MAC address** or **user login** to maintain consistent VLAN membership.

![VLANs](../attchements/VlanTags.png)

*VLANs tag packets with a VLAN ID and discard them if the destination is on a different VLAN, isolating devices and controlling communication even on the same physical switch.*

---

[← Back to Main](../README.md) | [Previous: ISP and Router](./isp-and-router.md) | [Next: OSI Model Overview →](./osi-model-overview.md)
