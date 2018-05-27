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

- Application - This layer is similar to the TCP/IP model layer of the same name, it is the layer in which different protocols are assigned to different types of data.

- Presentation - This layer is where data is compressed or encrypted. It also makes the data easier to interperate and determine the type of data it is and send it correctly.

- Session - This layer is responible for creating connections between different applications. Depending on the application and its requirements, either TCP or UDP is used, similarly to the transport layer of the TCP/IP model.

- Transport - This layer is one part of the model that is responsible for the transmision of the data. It is also the layer in which error checks are carried out on the data being sent or recieved.

- Network - This layer is the second layer that is directly involved in the sending of data, it is the layer in which the desination address and routing are taken into consideration and the appropriate information is applied to the data being sent. It also validates the address of data being recieved.

- Data Link - This layer is responsible for encrypting the data before it is sent to the recipient, it is also the same layer in which recieved data is decrypted back into readable packets for the other layers to process

- Physical - The last layer is the one that is responsible for the physical links that send the data, via cables. Information can be conveyed via electrical pulses or even light pulses.

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

#### Routed Protocols

Routed Protocol is a blanket term that is used to describe the different protocols that govern how data is routed from one machine to another. However this term is not often used in practice because the only protocol left in this catagory is IPv4 and IPv6. Other protocols in this catagory encounterd issues at some point during their lifespan that they could not overcome. However this is not to say that IPv4 has not encounterd problems as it has. Its main problem was that it began to run out of addresses it could assign to machines. This is because so many machines were being built that the 4 Billion possible addresses that IPv4 has started to run out. To solve this issue, IPv6 was designed. The principles are the same as IPv4 however the number of possible addresses was drastically increased to over 340 undecillion (2^128).

---------------------------

#### Services and Network Applications

##### HTTP
HTTP stands for Hyper Text Transfer Protocol and is used for the purposes of sending data about websites. HTTP covers everything to do with interperating what the user wants and recieving the data from the web server on what should be displayed on the webpage.

##### FTP
FTP stands for File Transfer Protocol. It is a standard internet protocol for sending and recieving files. FTP relies on a two way connection between a user and a FTP server. FTP allowed the user to upload, edit and dowload files from the server.

##### SSL
SSL stands for Secure Sockets Layer. It is designed to ensure that sesntitive data is sent securely by encrypting it. It is used when entering and sending data such as credit card information or finatial documentation such as tax forms.

##### SMTP
SMTP stands for Simple Mail Transfer Protocol, it is the protocol that is used to send and recieve emails. most modern email services use this protocol.

##### POP3
POP stands for Post Office Protocol. It is a protocol that changes how a user recieves emails. In the most recent version called POP3, the clients email is stored on a server which is then downloaded by the user. after which it can be deleted.

---------------------------

#### The Impact of Networking Topology, Communication and Bandwidth

##### Topologies
Topolgies are the rules by which different networks are designed. Each topology is designed to fill a different role and all have their strenghts and weaknesess. The term 'physical topology' details the design of LANs, using various different cables and connectors to create the layout of the network. Some examples of physical topologies are as follows:

- The star topology is the idea of all of the machines being connected to a single hub or switch at the center of the network, with the various connections comming out of this center hub or switch like a star.

- The mesh topology is the idea of multiple connections between different machines on the network allowing for different routes to be used if one becomes inoperable.

- The bus topology is a simple design, all of the network components are connected in a line.

- The ring topology is the idea of all of the components of the network being aranged into a circle formation. ~Each unit is connected to the two units next to it.

##### Communication
Communication is the process of two or more machines sending and recieving data from one another via a network. The most common form of communication between computers is the act of requesting data from a server. This can range frome requesting web data from a web server to requesting access to your emails from an email server. While connected to the internet, data is being sent to and from your device at all times. In a network it is the router that directs web traffic and data to where it needs to go. Because data is always being send or recieved, there is a constant risk of an attack being launched while the data is in transit or sent with the data itself. For this reason, security measures like firewall are used on most machines connected to the internet in order to help keep the user safe and secure by blocking certain types of data by closing different ports not in use. Due to these security measures, the speed of data transfer can often be reduced as it takes time to carry out these security checks. In some cases the data may not reach its intended recipient at all as the security features falsly flag the data as a threat. While this situation is rare it can happen.

---------------------------

#### Operating Principles

##### Networking devices

###### Hubs
Hubs serve as a central connection point for a network, they manage and route traffic over the local connections. However the data is sent one piece at at time so all users don't get a copy, this slows down the system.

###### Routers
Routers are devices that connect multiple local networks. Packets of data that are sent to the router have an address attached to them, the router knows how to send the data to the address attached and computes the best route for the data to take.

###### Switches
A switch is similar to a hub in that it takes and routes data to the machines connected on a LAN. the differnce being that every machine connected to the switch recieves a copy. This can speed up the LAN but can have security implications.

###### Multilayer Switch
A multilayer switch is a similar to a switch howevwer it operates much more efficiently that a normal switch and therefore increases the speed of the data transfer. 

###### Firewall
A firewall is a piece of software or hardware that determines what data can access a network by opening and closing different ports.

###### HIDS
HIDS stands for host-based intrusion detection system, it is used to detect a threat to a network or a computer. It searches through the data being sent through the network and looks for abnormalities that could be a threat.

###### Repeaters
Repeaters are devices that are used to strengthen a signal that is being sent over a large distance on a physical LAN, this allows the size of LANs to be much larger than if repeaters were not used.

###### Bridges
A bridge is used to get a connection with other networks that use a bridge. The only constraint is that they have to use the same protocols. This is because a bridge uses and internal database to determine what traffic is allowed in and out of the network. If these do not match it can cause connection issues.

###### Access Point
Access points are used to provide users with a connection to a network while they are physically not connected to that network. Wireless access points are the most common, they use Wi-Fi to allow the user(s) to connect to the network remotely.

###### Content Filter
A content filter is a simple concept. It uses a pre determines set of rules that it can compare any incomming data to. This check is used to determine if data is for example spam, or malicious. Email servers commonly use content filters to filter spam emails.

###### Load Balancer
A load balancer is used to spread out the workload over the entire network, by doing this the load balancer is able to prevent certain pathways and connections on a network becoming to busy and effect the speed of the network.

###### Modem
A modem is used to connect networks via existing telephone lines. While this can be convinient for reaching remote areas that may not have modern connections, It has a serious drawback of limited speeds.

###### Packet Shaper
Packet shapers are used to prioritize certain data being sent over a network. It forces lower priority packets such as instant messages to wait to be sent while more important data like security information is s

###### VPN Concentrator
A VPN concentrator is used to allow multiple users on the same network to use the same VPN, it does this by coordinating and organising the traffic on a network between different machines trying to access the VPN


##### Server types

###### Web
A web server stores and sends data on websites over the internet. A user will make a request to the web server for information on how to display the webpage and what information needs to be loaded. The server handles this request and sends a copy of the data to the user. Thousands of request can be handles by a web server at any given time.

###### File
A file server is used to store files and data for users on the network to access. The data stored on this server can range from public data that anyone on the network can have access to. Or private data that only a specific user is able to access.

###### Database
A database server is a type of server that stores data in certain catagories or fields. The data stored on these servers are related to one another so that requests can be made for other information pertaining to a certain subject. For example finding the price of an item at a supermarket, scanning the item will access the database and retrieve data related to that item.

###### Combination
A combination server is a type of server that merges all three of the previous servers in to one, performing all of the above tasks on a single machine.

###### Virtual
A virtualized server is a server that, while can have the funcionality of a physical server, is nothing more that a small machine loaded with specialized software. This software helps the virtual server to perform the tasks needed by a server.

###### Terminal Services
A terminal is a device that provides other computers connected to the devices with a path to another LAN or WAN, the computers to not need to be connect to a router or switch to make the connection.

---------------------------

#### Workstation Hardware

##### Networking Software
Network software defines what is needed to create and maintain a network, regardless of if it is a LAN or WAN. Below are some examples of what is needed in order to create a network.

---- 
EDIT FROM HERE

###### Client Software
A client is a piece of software that works within local and wide area networks. The term basically describes software that functions like an interface between a client’s computer and the server so it technically is located within the client’s PC. Basically, it can be anything that provides services, such as a word processor or a web browser, that makes use of services provided by the server and also provides an interface for the user to interact with these services.

###### Server Software
Server software is a piece of software designed for use in a server, providing power of a use of high end functions. It is used to interact with the infrastructure of the server to ensure maximum performance within the server. The type of usage may vary and the server may be used as a web, application, database, cloud or file server. The primary focus is clear however, which is to use computer resources and capacity.

###### Client Operating System
A client operating system is a computer that doesn’t require networks or external components to properly function and mainly works within the computer. It helps the user perform functions within the computer whenever used, such as browsing the internet. Operating systems must function with a distinct type of hardware. An example of a client operating system is Microsoft Windows, a common operating that comes within a desktop or laptop.

###### Server Operating system
A server operating system is an operating system designed for use on servers, built to serve the requests of client computers in a network. This server is opposite to that of a client operating system but also does function the same way, but the difference is that it enables server roles such as web, mail, file, database, application and print server. The Microsoft Windows Server line-up is a prime example of server operating software and has capabilities required within a client-server architecture.

###### Firewall
A firewall is software that enforces a set of rules that affect the traffic flow from within a network. They are incorporated into a variety of network devices to filter the traffic coming in and out of a firewall, but the main benefit is the security aspect of firewalls as they can prevent any malicious packets of data to flow into the network, mainly a public network. Two types can be used; host-based, which can be installed onto a server and network-based, typically built into the cloud infrastructure.

###### Proxies
A proxy server is a software system that runs on a computer, acting as midway between an endpoint device and another server that the client requests a service from. The proxy exists in the same machine as a firewall server, so that the requests can be forwarded through the firewall. Once a proxy server receives a request for an internet resource, which can be a web page, it runs through a cache of past pages and returns it to the user once found, without having to forward the request to the internet.

-----

#### Design and Implement A Network

##### Network Specification and Design Brief
The network I was asked to design had very specific requirements that had to be met. In terms of design the network had to consist of 2 LANs that were connected together with two routers. The individual LANs had to contain 3 computers, 1 server all connected to a swich that then connected to a router. Somewhere on this WAN there also had to be 1 printer and 1 wireless access point. As all of the devices on these LANs connected to a swich, the design followed the star topology. Below are the IP configurations that were also specified by the client.

###### LAN (a)
Computer IP Addresses:
- 192.168.1.100
- 192.168.1.101
- 192.168.1.102

Server IP Address:
- 192.168.1.10

Router IP Address:
- 192.168.1.1

###### LAN (b)
PC IP Addresses:
- 192.168.10.100
- 192.168.10.101
- 192.168.10.102

Server IP Address:
- 192.168.10.10

Router IP Address:
- 192.168.10.1

##### Concept Diagram
Below is a concept design I made to visualise this network before I implemented it. By doing this I could collect feedback on the design before I started work on implementing it.

![Imgur](https://i.imgur.com/tInbiFE.jpg)







