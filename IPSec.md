### IKE
The Internet Key Exchange () protocol is used to establish security associations (SAs) and negotiate cryptographic keys in the IPsec protocol suite. While IKE plays a crucial role in setting up secure communication channels, it does not directly provide authentication services like AH and ESP do.

### ESP
The Encapsulating Security Payload (ESP) protocol provides encryption and authentication services in the IPsec protocol suite. ESP offers confidentiality, data origin authentication, connectionless integrity, anti-replay protection, and limited traffic flow confidentiality for IP packets.

## AH
The Authentication Header (AH) protocol provides authentication services in the IPsec protocol suite. AH ensures data integrity, data origin authentication, and optional anti-replay protection for IP packets.
The Authentication Header (AH) and Encapsulating Security Payload (ESP) protocols both provide authentication services in the IPsec protocol suite. AH provides data integrity, data origin authentication, and an optional anti-replay service, while ESP provides confidentiality, data origin authentication, connectionless integrity, an anti-replay service, and limited traffic flow confidentiality.


### Tunnel Mode - Site to Site
In this mode, IPSec is encapsulated within another protocol, often Layer 2 Tunneling Protocol (L2TP), allowing the secure transmission of data across non-secure or public networks.
This mode is commonly used in Virtual Private Network (VPN) configurations to create a secure tunnel for communication.


### Transport Mode - Internal Netowrk
Transport mode in IPSec is used for end-to-end communication between two hosts, securing the payload of the IP packet but not encapsulating the entire packet within another protocol.
