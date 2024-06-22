TCP (Transmission Control Protocol) handshake involves three key steps:

SYN (Synchronize): The initiating party, usually a client, sends a TCP packet with the SYN (synchronize) flag set to the server. This packet indicates the intention to establish a connection. The client also selects an initial sequence number (ISN) that helps in sequencing data during the connection.

SYN-ACK (Synchronize-Acknowledge): Upon receiving the SYN packet, the server responds with a TCP packet that has both the SYN and ACK (acknowledge) flags set. This packet acknowledges the receipt of the client's SYN packet and signals the server's readiness to establish a connection. The server also selects its own initial sequence number.

ACK (Acknowledge): The client, upon receiving the server's SYN-ACK packet, sends an acknowledgment back to the server. This acknowledgment packet has the ACK flag set, confirming the completion of the three-way handshake. The connection is now established, and both parties can begin exchanging data.
