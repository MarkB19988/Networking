# Networking

#### Different Types of Network and Standards

##### Peer-based

Peer-based, also called peer to peer or simply P2P networks refers to the process of connecting two or more PCs directly to share data without the need for a separate server. P2P networks allows each connected computer to function as both server and client, as requests can be made by either machine to the other.

If computers are using a P2P connection then they will usually use the same protocols. The most common use for P2P networks is to connect computers that are in close proximity to one another, such as connecting multiple games consoles together to play a game with friends. However it is still possible to create P2P networks over a wide area. P2P networks offer alot of features that may be more complex to set up using other network configurations, such as shared storage. 

P2P networks are relativly basic compared to other network configurations and as so are quite easy to set up and use. Any computer can be connected to a P2P network as they don't require any specialist hardware. Having a P2P network for some tasks can also be faster than setting up a server as in a server based network all of the request traffic goes to one computer and this can slow the network down, however in P2P requests can go to any computer meaning the workload can be shared.

However P2P networks arn't without their flaws. The computers must be manually maintained and kept up to date, there is no central server to ensure this is the case. Ever computer must keep antivirus software up to date and this can only be done manually. If a virus was to infect a machine on a P2P network, it could spell disaster for every single machine on that network as the virus would have free access to every machine that is connected.

##### Client-Server 
Client-Server is a network configuratiuon that includes both a client and a server, this is one of the most common network configurations there is. In a Client-Server network client makes a request for date or a service from the server. For example the request could be for the clients browser to get data from a webserver because the client wants to access a website stored on that server. The server would validate the request and reply to the client with the requested websites data, then would terminate the connection.

In a Client-Server configuration all data and setting and held within the server machine, meaning that any client computer that was not authorized would not be able to access the data stored on the server machine. This can be better when storing data from multiple users as everyones data can be easily separated with each client only having access to their specific data. Furthermore, back-ups are also created and handled by the server machine meaning that the client would not have to worry about backing up the data they store on the server themselves. However this server configuration like any other does have its down side. The biggest flaw is that a server machine can be expensive to buy and to maintain, and experienced personell are usually requried to keep the server running.

##### Cloud

Cloud networking is a network configuration that connects 2 or more sub networkds via a wide are network. cloud networking can be used in many ways, such as sharing computing resources over a great distance. for example you can use the power of many computers over a cloud network to form a kind of super computer for complex math calculations.

The main appeal of cloud computing is that anyone, anywhere, can connect to a cloud network. This means that, for example, people working on a project together can all contribute to that project from separate locations. Cloud networking is not the same as cloud computing, however the two are closely related and do share alot of the same features, benifits and drawbacks.

##### Cluster

A cluster is a group of computers that are connected together to form a LAN, however unlike a normal network, all of the machines combine their computing power to form a single machine. The most obvious advantage to this is that it increases the complexity of the task that can be assigned to the machines, the more machines you connect, the more complex the task the cluster can complete. Also, if one machine on the network fails or shuts down, the cluster will continue to function, but at a reduced performance.

##### Centralized

Centralized networks are a type of network in which many pc's connect to a central server that handles all of the processing power and storage on the network. All of the computers connected to the server are given processing power form the server itself. Computers that are connected to the network normally don't have much processing power on their own, just enought to connect to the network. The main benifit of this is that you can expand the network cheaply as the individual machines don't need much processing power.

##### Virtualised

A virtualized network is a network in which the resourses are split up by dividing the networks bandwidth into multiple segments called 'channels' All of the channels act separatly from one another and can be assigned to any device on the network at any time. The main advantage of of a virtual network is that you do not need to spend money of switches or routers as they are not involved in this type of network, all connections are virtual, not physical.

#### Conceptual Models

##### TCP/IP Model

---------------------------

The Transmission Control Protocol/Internet Protocol model, shortened to TCP/IP is made up of many communication protocol used to connect network devices on the internet and is used as a communications protocol within a private network.

It uses the client/server model of communication where a client is provided a service from another computer in the same network. The model is made up of different protocols and divided into four layers:

Application - The application layer is responsible for providing network services to applications. High-level protocols are included within the application layer, such as Domain Naming System (DNS), Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), etc.
Transport - This layer maintains the end-to-end communications within the network. The communications between the hosts are handled within this layer and flow control, multiplexing and reliability are maintained as well by the layer. Two protocols are used within this layer; TCP, for providing error control and successful delivery of the data, and UDP, though only used for less extensive control features.
Internet - The internet layer, or network layer, packs the data into data packets and routes it to the correct device on the destination network. These packets then form the IP, containing the source and destination address used to transmit the IPs across networks.
Network Access - The lowest layer is known as the Network Access Layer, that combines the data link and physical layers from the OSI model. It provides a means for the data to be delivered to other devices on a network and defines how the network should transmit an IP. This layer has to understand the details of the underlying network before it can format the data being transmitted.


##### OSI Model

Application - The application layer in the OSI model is a means for applications to receive network services, basically communicating the services to them such as file transfers and e-mail. Numerous protocols are used within this layer, such as Hypertext Transfer Protocol for web based languages transferred across the network and mail services by the SMPP protocol for email services.
Presentation - The presentation layer is used for interpreting the data and transformed that the application layer can use it. Many file types are represented by the application and can be converted, encrypted, decrypted or compressed.
Session - The session layer establishes connections between applications and can set up, coordinate and terminate the conversations that happens between them. The protocols used are Transmission Control Protocol (TCP) and User Datagram Protocol (UDP), commonly provided within most applications.
Transport - This layer provides the transferal of data between hosts or end systems and is responsible for error recovery and flow control. TCP and USP protocols, used in the session layer, provide these services through the internet for most applications.
Network - The network layer handles the addressing and routing of data, where it is sent in the correct direction, selecting the appropriate routes and forwarding the data to the transport layer. The protocols that map to the OSI network include the IP protocol from the TCP/IP model, both IPv4 and IPv6, as well as Interwork Packet Exchange (IPX).
Data Link - The data link layer is responsible for encoding the data prior to the transmission and decoding the data back into the bits at the destination, mainly handling the data transfer out of a physical link. The layer divides itself into two sub-layers; Media Access Control, how the computer gains access to the data and the permission to transfer said data, and Logical Link Control, controlling the frame synchronization, flow control and error checking.
Physical - The bottommost layer is the physical layer that conveys the bit stream across the network. This is done via electrical impulse, light or a radio signal. A variety of devices and mediums are covered, through cables, cards and other ports.

