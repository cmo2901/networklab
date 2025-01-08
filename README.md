# Building a Network with Cisco Packet Tracer

## Objective
For this lab, I took the free Packet Tracer course from Cisco. Using the knowledge gained, I configured a home network.

### Tools Used
Cisco Packet Tracer

### Skills Learned
<p> Networking <br>
Network Configuration <br>
Routing</p>

### Network Setup: Baseline Configuration
<p> To start out, I chose two wireless laptops connected via a wireless connection and four PCs connected to a switch. <br>
The connection from each PC to the switch, as well as from the switch to the router, utilizes a copper straight-through cable.</p>

![basic layout](https://github.com/user-attachments/assets/0266c44b-3bbd-409f-a86e-3b8406945b2d)

<p> Because the laptops on Packet Tracer do not come with wireless NICs already installed, I put one in each laptop:</p>

![wireless NIC laptop](https://github.com/user-attachments/assets/47332f95-51b7-4381-92b5-9a7affdf6841)

### IP Address Configuration
<p> To bring the network online, I started by configuring an IP address on the router:</p>

![ip addresses for routers](https://github.com/user-attachments/assets/d63c5d5c-d9e1-4cc8-85b4-94fefa170cf6)

<p> From here, each device connecting to the router needs an IP address. With DHCP enabled on the router, I allowed each end device to automatically receive an IP address.</p>

![dhcp set on PCs](https://github.com/user-attachments/assets/ff198539-6615-4325-b302-952a8263373a)

![dhcp set on laptops](https://github.com/user-attachments/assets/fc3147bf-adf8-4107-95a7-62146ac6ba37)

### Verifying Connectivity
<p> In order to verify that all endpoints are connected to the network, I sent an ICMP packet from each device to the router:</p>

![verify connectivity](https://github.com/user-attachments/assets/984aed20-1dbb-4d88-93b5-ab946d937d0a)





