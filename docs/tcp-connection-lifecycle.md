# TCP Connection Lifecycle

## TCP Connection Lifecycle Overview

TCP connections follow a well-defined **state diagram** that controls how connections are **established**, **maintained**, and **terminated**. A connection starts with the **three-way handshake**: the client sends a **SYN** to request communication, the server replies with **SYN-ACK** to acknowledge and synchronize, and the client responds with a final **ACK**, after which both sides enter the `ESTABLISHED` state and exchange data as equal peers.

Closing a connection requires cooperation from both ends. One side sends a **FIN** to indicate it has finished sending data, the other acknowledges it and later sends its own **FIN** when ready. After the final acknowledgment, the connection enters the `TIME_WAIT` state, where it remains briefly to ensure any delayed packets from the old connection expire before the port can be reused.

The TCP state diagram also handles edge cases such as **simultaneous opens**, **simultaneous closes**, and abrupt termination using **RST** when a connection is invalid or refused, ensuring reliability even in unusual network conditions.

![TCP State Diagram](../attchements/TCPstateDiagram.png)

## TCP Connection States

A TCP connection transitions through several well-defined states during its lifecycle:

- **CLOSED**  
  The connection is inactive and no data can be sent or received.
- **LISTEN**  
  The server is waiting for an incoming connection request.
- **SYN_SENT**  
  The client has sent a SYN to initiate the three-way handshake.
- **SYN_RECVD**  
  The server has received the SYN and replied with SYN-ACK.
- **ESTABLISHED**  
  The connection is open and data can be exchanged.
- **FIN_WAIT_1**  
  One side initiates connection termination by sending FIN.
- **FIN_WAIT_2**  
  The FIN was acknowledged, waiting for the peer's FIN.
- **CLOSE_WAIT**  
  A FIN was received and acknowledged, waiting to close locally.
- **CLOSING**  
  Both sides have sent FIN and are waiting for final ACKs.
- **TIME_WAIT**  
  The final ACK was sent, waiting to ensure the peer fully closes.
- **RST_ACT**  
  The connection is forcefully terminated using a reset.

---

[← Back to Main](../README.md) | [Previous: TCP vs UDP](./tcp-vs-udp.md) | [Next: Protocols Reference →](./protocols-reference.md)
