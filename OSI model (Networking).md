## What is OSI model?
The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. 
It was the first standard model for network communications,adopted by all major computer and telecommunication companies in the early 1980s
The modern Internet is not based on OSI, but on the simpler TCP/IP model. 
However, the OSI 7-layer model is still widely used, as it helps visualize and communicate how networks operate, and helps isolate and troubleshoot networking problems.
OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by ISO as an international standard in 1984.
7. Application Layer
The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and 
present meaningful data to users. A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office 
Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).

6. Presentation Layer
The presentation layer prepares data for the application layer. It defines how two devices should encode, encrypt, and compress data so it is received correctly on the 
other end. The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

5. Session Layer
The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional
while data is being transferred, and closing them when communication ends. The session layer can also set checkpoints during a data transfer—if the session is
interrupted, devices can resume data transfer from the last checkpoint.

4. Transport Layer
The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. It is responsible for reassembling the
segments on the receiving end, turning it back into data that can be used by the session layer. The transport layer carries out flow control, sending data at a
rate that matches the connection speed of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.

3. Network Layer
The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing
packets by discovering the best path across a physical network. The network layer uses network addresses (typically Internet Protocol addresses) to route packets to
a destination node.

2. Data Link Layer
The data link layer establishes and terminates a connection between two physically-connected nodes on a network. It breaks up packets into frames and sends them from
source to destination. This layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols, performs error checking and synchronizes
frames, and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive data.

1. Physical Layer
The physical layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless
technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.

## What is DHCP (Dynamic host configuration Protocol)?
Dynamic Host Configuration Protocol (DHCP) is a network management protocol used to automate the process of configuring devices on IP networks, thus allowing them to
use network services such as DNS, NTP, and any communication protocol based on UDP or TCP. A DHCP server dynamically assigns an IP address and other network
configuration parameters to each device on a network so they can communicate with other IP networks. DHCP is an enhancement of an older protocol called BOOTP.
DHCP is an important part of the DDI solution (DNS-DHCP-IPAM).

## What is Firewall? is it hardware or software?
A Firewall is a network security device that monitors and filters incoming and outgoing network traffic based on an organization’s previously established security
policies. At its most basic, a firewall is essentially the barrier that sits between a private internal network and the public Internet. A firewall’s main purpose
is to allow non-threatening traffic in and to keep dangerous traffic out.
