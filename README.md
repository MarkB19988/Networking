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

##### Centralized

Centralized networks are a type of network in which many pc's connect to a central server that handles all of the processing power and storage on the network. All of the computers connected to the server are given processing power form the server itself. Computers that are connected to the network normally don't have much processing power on their own, just enought to connect to the network. The main benifit of this is that you can expand the network cheaply as the individual machines don't need much processing power.

##### Cluster

A cluster is a group of computers that are connected together to form a LAN, however unlike a normal network, all of the machines combine their computing power to form a single machine. The most obvious advantage to this is that it increases the complexity of the task that can be assigned to the machines, the more machines you connect, the more complex the task the cluster can complete. Also, if one machine on the network fails or shuts down, the cluster will continue to function, but at a reduced performance.

##### Virtualised

A virtualized network is a network in which the resourses are split up by dividing the networks bandwidth into multiple segments called 'channels' All of the channels act separatly from one another and can be assigned to any device on the network at any time. The main advantage of of a virtual network is that you do not need to spend money of switches or routers as they are not involved in this type of network, all connections are virtual, not physical.

---------------------------

#### Conceptual Models

##### TCP/IP Model


TCP/IP stands for Transmission Control Protocol/Internet Protocol, it is a combination of different protocols that come together in order to connect devices over the internet. It has a total of 4 different 'layers' each with their own responsibilities and tasks.


- Application - This layer is responsible for specifying which protocol is to be used by what application or data.

- Transport - The Transport layer is responsible for creating and maintaining communication between the sender and the reciever. Only two protocols are used in this later. TCP which has a system in place to check if the recipient and recieved the data, and UDP which doenst check if the recipient has got the data.

- Internet - This layer is responsible for segmenting any data sent into packets, these packets are then routed to the recipient using the recipients IP address.

- Network Access - The Network Access layer is responsible for interfacing with your network’s architecture. It is also at this layer that error checking information is applied to sent data so the recipient can check for errors.


##### OSI Model

Application - This layer is similar to the TCP/IP model layer of the same name, it is the layer in which different protocols are assigned to different types of data.

Presentation - This layer is where data is compressed or encrypted. It also makes the data easier to interperate and determine the type of data it is and send it correctly.

Session - This layer is responible for creating connections between different applications. Depending on the application and its requirements, either TCP or UDP is used, similarly to the transport layer of the TCP/IP model.

Transport - This layer is one part of the model that is responsible for the transmision of the data. It is also the layer in which error checks are carried out on the data being sent or recieved.

Network - This layer is the second layer that is directly involved in the sending of data, it is the layer in which the desination address and routing are taken into consideration and the appropriate information is applied to the data being sent. It also validates the address of data being recieved.

Data Link - This layer is responsible for encrypting the data before it is sent to the recipient, it is also the same layer in which recieved data is decrypted back into readable packets for the other layers to process

Physical - The last layer is the one that is responsible for the physical links that send the data, via cables. Information can be conveyed via electrical pulses or even light pulses.

---------------------------

#### Standards and Protocols

##### IEEE Standards

###### IEEE 802.3
IEEE 802.3 refers to the standart of Ethernet connections. This type of physical connection is most often used for LAN connections however can have its place in WAN set-ups. The communication standards for ethernet connections and cables are updated regularly adding aditional features however 802.3 was the first IEEE standard to be implemented. The description of this standard stated that these connections must be at speeds of 10Mbits/s which is equal to 1.25MB/s.

###### IEEE 802.7
IEEE 802.7 is the standards assigned to broadband connections, what is outlined here is thes design and implementation of the connection. It also outlines some methods of testing the connections that should also be followed.

###### IEEE 802.8
IEEE 802.8 refers to the standard of fibre optic connections. It is in the same group as the previous standards and outlines many of the same defining features however is called a standard by itself as it covers a different connection type.

###### IEEE 802.11
IEEE 802.11 refers to the standard of wireless conectivity. The most common connection to follow these standards by far is Wi-Fi, this standard outlines what frequencies are to be used via wireless access points and hubs.

---------------------------

Routed Protocols
Routed Protocols is a protocol where data is routed from one network to another. These protocols use an addressing system that can address a particular network and host. There are different types of routed protocols, but the common being the IP address. The reason for IP being a more valued type of routed protocol is because of the fact that the rest is vanishing due to different issues.

IPv4 has started running out of addresses due to the population of the world and the devices being manufactured, meaning that there is not enough IPv4 addresses. IPv6 is the newer solution where there is a considerable amount of addresses, with more than IPv4. Global Unicast is a routable address that can used in the internet, associated with a single node and can identify that node. The problem with this protocol is mainly unicast flood, where the data packet that is supposed to be sent off to a single destination is sent to all hosts as a broadcast packet, making this protocol a potential security risk.

Link local is a computer address that is only effective for communications within the link or the broadcast domain where the host is connected. They are not unique beyond a single link and routers can’t forward the packets that have a link-local address. A Unique Local Address, or ULA, is an address that is used in IPv6. They are not meant to have data routed outside of their province and not allocated at all by an address registry.

Extended Unique Identifier, also known as EUI, assigns itself a unique 64-Bit IPv6 interface identifier, eliminating the need to manually configure the IP or use DHCP in IPv4 addresses. The problem that arises from using this however, is that privacy loss would be potential concern, with the MAC address of the router being revealed. Auto-configuration is a feature in the IPv6 protocol that allows devices to use the internet without requiring any DHCP support, making it good for applications to require a secure connection without the DHCP server. The problem is that it doesn’t get the configuration needed to be functional on the network, so it needs a DHCPv6 server to get the rest of the configuration.

