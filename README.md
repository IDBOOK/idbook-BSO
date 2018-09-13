# idbook-BSO
BSO Communication Protocol

IDBook will redesign the blockchain communication protocol BSO (Blockchain Security Obscure) to replace most existing public chains, who are using P2P protocols. IDBook will modify the communication between nodes from broadcasting into a transmission with characteristics of network traffic. This is in order to protect against distributed node consensus from the network layer intervention, effectively resisting all kinds of network layer effects including healing attacks, and data leakages during transmission.
One of the defects of the P2P protocol is that it transmits data with naked exposure in the network. There are security vulnerabilities that are easily exploited, packets that are easily inspected, and identities to be stolen. There are also other means to intercept or tamper with data, which leads to influence or control section node communication, and interference with the blockchain consensus process.

BSO is a kind of circuitous security confrontation, that is, protocol characteristics and content encryption are difficult to identify from the transmission traffic, which belongs to the legitimate encryption protocol. Confrontation, another safe design, is a new strong encryption protocol for intermediaries to content identified by analyzing flow application business. But the characteristics of the new protocol itself are clear：
(1) Communication among nodes uses SSL with separate SSL certificates for each node. If a single node is breached, it will not affect the full network of encrypted communication.
(2) Supports a number of authoritative certification institutions, and node owners can apply for or change the certificate.
(3) In the zero-traffic network, others can only see the conventional SSL exchanging process, the real content of the communication cannot be resolved from the packet.
(4) All traffic of nodes and wallets is encrypted, including data synchronization of node blocks, sending transactions and broadcasting messages. All the communication will be disguised as the most common legitimate SSL communication on the Internet
(5) The change is controlled at the communication mechanism level, which will not tamper with the blockchain consensus mechanism, and will follow the technical development of the main line code to carry on the new characteristic update.
With the BSO blockchain communication encryption protocol, IDBook will become the world's leading secure public blockchain.



