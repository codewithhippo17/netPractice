# TCP vs UDP

## Why use TCP over UDP

You use TCP over UDP when your application requires a reliable communication channel on top of the unreliable underlying network, because unlike UDP which ignores lost or out-of-order data, TCP guarantees that packets arrive and are reassembled in the correct sequence through a system of acknowledgments and sequence numbers

![TCP vs UDP](../attchements/TCP_UDP.png)

---

[← Back to Main](../README.md) | [Previous: Network Packet Anatomy](./network-packet-anatomy.md) | [Next: TCP Connection Lifecycle →](./tcp-connection-lifecycle.md)
