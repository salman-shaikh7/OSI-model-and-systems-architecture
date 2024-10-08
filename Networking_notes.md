# Networking Introduction

ISP : Internet Service provider 

![alt text](image.png)

**Purpose of Networking**

![alt text](image-1.png)

**Packetization**
* Breaking down user data into small packets.
* packaging these segment such that they can reassembled across the network.
* Each packet contains two parts 
1.  Data <br>
2.  Overhead required (Metadata) for sucessful delivery and intergration. 

**Advatange of Packetization**
1. Network remains consistant even though different user have different usage pattern like some scrolling twitter and someone watching 4k youtube videos.
2. In case of failure router can manage delivery of packages by themselves without inverventation of support from source/receiver.

Packet Structure

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)
->->->->->->->->->-> <br>
Flow

![alt text](image-5.png)



# Different Networking Layer

1.  physical layer
2.  data link layer
3.  network layer
4.  transport layer
5.  application layer



**Physical Layer**
UTP (Unshielded Twisted Pair) : pairs of insulated copper wires twisted together to reduce electromagnetic interference (EMI) from external sources and crosstalk between the pairs.

![alt text](image-7.png)

![alt text](image-6.png)


**Data Link Layer**

>Ethernet  \
>good fit for 100 meter area \
>Brodcasting every message in the cable then receiver decide to pick it or not.


**Network Layer**

>The network layer is responsible for routing data packets between devices across different networks. 

>It determines the best path for data to travel from the source to the destination.

>Key functions include Routing,Addressing and Packet forwarding 

>IPv4 and IPv6 : how data packets are addressed and routed on the internet.

>ICMP (Internet Control Message Protocol) Used for error messages and operational queries (e.g., ping).


**Transport Layer**

>manages end-to-end communication and controls data flow to ensure that data is delivered accurately and in the correct sequence.

>Key Functions include Segmentation and reassembly of IP packets,Flow control, Connection management, Error detection and correction

>TCP (Transmission Control Protocol): reliable, connection-oriented communication

>UDP (User Datagram Protocol): Becoming popular 

>firewalls may operate at this layer to filter traffic based on port numbers.

**Application Layer**

![alt text](image-8.png)


## Summary Image of Networking Module
![alt text](image-9.png)


**Support Services**
>DHCP Dynamic Host Configuration Protocol. It assign IP address to our machine

>NAPT 

>DNS



![alt text](image-10.png)