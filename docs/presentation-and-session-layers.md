# Presentation and Session Layers

## Presentation Layer

The [Presentation Layer](https://www.geeksforgeeks.org/computer-networks/presentation-layer-in-osi-model/) is also called the Translation layer. The data from the application layer is extracted here and manipulated as per the required format to transmit over the network. Protocols used in the Presentation Layer are [TLS/SSL](https://www.geeksforgeeks.org/computer-networks/difference-between-secure-socket-layer-ssl-and-transport-layer-security-tls/) (Transport Layer Security / Secure Sockets Layer).[JPEG, MPEG, GIF](https://www.geeksforgeeks.org/computer-graphics/difference-between-jpeg-and-mpeg/), are standards or formats used for encoding data, which is part of the presentation layer's role.

### Functions of the Presentation Layer
- ****Translation:**** For example, [ASCII to EBCDIC](https://www.geeksforgeeks.org/computer-organization-architecture/difference-between-ascii-and-ebcdic/).
- ****Encryption/ Decryption:**** Data encryption translates the data into another form or code. The encrypted data is known as the ciphertext, and the decrypted data is known as plain text. A key value is used for encrypting as well as decrypting data.
- ****Compression:**** Reduces the number of bits that need to be transmitted on the network.

---

## Session Layer

[Session Layer](https://www.geeksforgeeks.org/computer-networks/session-layer-in-osi-model/) in the OSI Model is responsible for the establishment of connections, management of connections, terminations of sessions between two devices. It also provides authentication and security. Protocols used in the Session Layer are NetBIOS, PPTP.

### Functions of the Session Layer
- ****Session Establishment, Maintenance, and Termination:**** The layer allows the two processes to establish, use, and terminate a connection.
- ****Synchronization:**** This layer allows a process to add checkpoints that are considered synchronization points in the data. These synchronization points help to identify the error so that the data is re-synchronized properly, and ends of the messages are not cut prematurely, and data loss is avoided.
- ****Dialog Controller:**** The session layer allows two systems to start communication with each other in half-duplex or full duplex.

---

[← Back to Main](../README.md) | [Previous: Application Layer](./application-layer.md) | [Next: Network Packet Anatomy →](./network-packet-anatomy.md)
