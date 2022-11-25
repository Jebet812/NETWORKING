#     NETWORKING
*Networking* is 
## Networking Basics
1. __LAN__: Local Area Network
2. __IP__: Logical address of a device in the network
3. __Router__: Networking device that forwards data packets between "DIFFERENT" computer networks
4. __Switch__: A device within LAN that helps connect devices within the same network
5. __Subnet__: Set of flags that define your LAN
6. __Gateway__: IP address of the router
7. __WAN__: Wide Area Network
8. __NAT__: Network Address Translation is a method of remmaping an IP address while they are in trasit across the traffic routing device
9. __Firewall__: Set of passive rules to protect network from unathorized access
10. __DMZ__: Demilitarized Zone is a subnetwork that contains and exposes a device to an untrusted network such as the internet
11. __Port Forwarding__: Redirects a communication request from one address and port number combination to another while the packets are travessing a network gateway such a router or firewall

## Fundamentals of computer networking

A *network* is a collection of network enabled devices like switches, routers, printers, computers and servers.

### Network Types
They are categorized into one of the following network categories:
1. __*Personal Area Network (PAN)*__: This provides networking needs around an individual. They typically use Bluetooth to communicate as it provides a low-power, short range data sharing capaility. Network starndards associated with PAN are Bluetooth and IEEE 802.15.
2. __*Local Area Network (LAN)*__: It is the most commonly used classification of a network. It provides networking needs around a single location and is usually privately owned hence needing authentication and authorization to access.
3. __*Metropolitant Area Network (MAN)*__: It provides networking capabilities between two different locations in a city/metropolitant area. Typically, it requires a dedicated and secure connection between each LAN joined to the MAN.
4. __*Wide Area Network (WAN)*__: Provides networking capabilities between two different geographical locations locally or worldwide. It links multiple LANs together to create one super network. You can use a virtual private cloud (VPN) to manage connection between different LANs.

### Network Topologies
This describes the physical composition of a network.
1. __*Bus Topology*__: Here each network device is connected to a single network cable. It is the simplest but limitations include;
-    Length of main cable or bus: the longer it takes, the higher the chance of signal dropout.
-    All devices have to be located near each other.
-    Breakage of the bus cable causes failure of the whole network.
2. __*Ring Topology*__: Each network is connected to its neighbor to form a ring. Breakage in the cable ring also affects the performance of the network.
3. __*Mesh Topology*__: It can either be a physical or a logical mesh.
-   *Physical Mesh:* Each network device connects to every other network device in the network.
This increases resilience of a network but has physical overhead of connecting all devices. Few networks today are built as a *full mesh* but most use *partial mesh,* where some machines interconnect but others interconnect through one device.
-   *Logical Mesh:* The perception here is most modern networks are mesh based since each device can communicate with any device on the network. It is primarily made possible through use of network protocols.
4. __*Star Topology*__: It is the most commonly used network topology. Each network connects with the help of a centralized hub or switch. The hub and switches can be linked together to extend and build more extensive networks. It is by far the most robust and scalable.

### Ethernet

It is networking starndard that's synonymus with wire-based LAN networks, and can also be used in MAN and WAN networks.
Ethernet strandard defines a framework of error handling, data transmission and performance handling. It describes how each element in the network interacts.
Ethernet formed basis for IEEE 802.3 Standard which helped unify network and hardware development.
Some of the ethernet networks are:
1. __Fast Ethernet:__ This was developed to support data transmission of upto 100Mbps. It is also reffered to as the 100BASE-TX standard.
2. __Gigabit Ethernet (IEEE 802.3ab):__ It was developed to support faster communication networks that can support services like streaming media. The 1000BASE-T starndard runs 10 times faster than 100BASE-TX standard.
3. __10 Gigabit Ethernet (IEEE 802.3ae):__ It has a data transfer speed of 10 Gbps, which is 10 times faster than Gigabit Ethernet which was made possible only by using fiber optics. 
4. __Terabit Ethernet:__ It offers transfer speed of 200 Gbps and 400 Gbps.

## Network Standards
Network Protocols provides a unified method of communication while Network Starndards govern the hardware and software that uses them. Network starndatd provide a framework that enables the interoperability between devices. It improves the interoperability of different network-enabled devices and provide backward compatiility between product revisions and different vendors.  
__*The 802 Family of Starndards*__ Some of the widely used starndards are can be found on this page https://learn.microsoft.com/en-us/training/modules/network-fundamentals/3-network-infrastructure

## Network Infrastructure
Network starndard-compliant devices makes up structure of a network and depending on network size you might use several devices to build the network's backbone. Examples are repeaters, hubs, switches, ridges, routers.

__*Media Accesss Control (MAC)*__ address is a unique identifier assigned to very network enabled device at the time of manufacture which is used by nearly all devices to deliver data in the network. It sometimes is reffered tp as burned-in address, Ethernet hardware address or a physical addresss.

### Repeater
A two port device that repeats network signals without modifying or interpreting data packets before resending them and doesnt amplify the signal. It instead regeneratyes the data packet at the original strengrh bit-by-bit. It is useful for network devices that are some distance from each other.

### Hub
It acts as a multi-port repearter on a network. It is used to connect more than one device and structure the layout of the network. Hubs contain multiple  ports that act input/output Ethernet connection between network device and hub. It operates in speed of the slowest network device. It doesn't filter or interpret data packets and sends copies of each data packet to all attached devices. </br>

__*Types of Hubs*__
- __Fast Ethernet__: Used for 100Mbps networks and comes as Class I (intoduce a signal delay of upto 140-bit times) and Class II (has a delay of upto 96-bit times)



