**Computer network**:- A collection of computing devices that are corrected in various ways in order to communicate and stored resources.

Usually, the collections between computers in a network are made using physical wire or cables.

However, some connections are wireless using radio, waves or infrared signals.

The generic term node or host refers to any devices on a network.

# Data transfer rate

The speed with which data is moved from  one place on a network to another data transfer rate is a key issue in a computer network.


# Diagram

![[client_server_request_Response.png]]


Computer network have opened up an entire frontier in the world of computing called the client/server model.

**File server**:- A computer that stores and manage files for multiple user on a network.

**Web server**:- A computer dedicated to responding to requests (from the browser client) for web pages.


# Type of networks

**Local area network (LAN)**:- A network that connects a relatively small number of machines in a relatively  geographical area.

various configurations, called topologies have been used to administer lans.

# Ring topology

**A configuration that connects all notes in a closed loop on which message travel in one direction**

# Start topology

**A configuration that centers around one node to which all others are connected and through which all messages are sent**

# Bus topology

**All nodes are connected to a single communication line that carries messages in both directions.**

# Ring Diagram


![[ring_topology.jpeg]]


# Star diagram

![[star_topology_diagram.png]]


# Bus diagram

![[bus-topology.png]]


# Star topology

**Star topology doesn't allow direct communication between devices, a a devices most have to communicate through hub**.

**If one device wants to  send data to other device. 
It has to first send the data to hub and then the hub
Transmit that data to be designated device

- [ ] Best Topology ever for networking of multiple devices over a network.**

**Advantages:- less expensive because each device only need on 1/0 part and needs to be connected with hub with one link. 

Easier to install less amount

**Disadvantages**:- If hub goes down encrypting goes down, none of the devices can work without hub.

# Bus topology

- All devices connected to a single back-bone cable 

- one device is failure, create problem in entire network 

- In bus topology main cable and all the devices are connected to this main cable through drop lines.

- There is a device called tap that connect the dropline to the main cable. since all the data is transmitted.


# Wide area network (WAN)

![[wan.png]]

A  network that connect two or move local area network over a potentially large geographic distance often one particular node on lan is setup to serve as a gateway to handle all communication going between that land and other networks.

Communication between networks is called internetworking the internet, as we knot it today is essentially the ultimate wide-area-networks, spanning the entire globe.


# Metropolian-area-network(MAN)

![[man.png]]

(MAN) The communication infrastructures that have been developed in and around large cities.

**Gateway**:- local area  network connected across a distance to create a wide-area-network.

# Internet backbones connections

**Internet backbone**:- A set of high speed network that carry internet traffic.

These network are provided by companies such as AT & T, GTE and IBM.

# Internet service provider (ISP)

A company that provides other companies or individuals with access to internet.

**Note:- There are various technologies available that you can use to connect a home computers to the internet**

#**A phone modem**:- converts a computer data into a analog audio signal for transfer over a telephone line, and then a model at the destination convert it back again into data.

**A digital subscriber line(DSL)**:- uses regular copper line to transfer digital data to and from the phone company's central office.

**A cabel model**:- use the same line that your cable tv signal come in into transfer the data back one forth.

# Broadband

![[broadband.png]]

A connection in which transfer speed are faster than 128 bit per second.

The speed for downloads  (getting data from the internet to your home computer) may not be the same as uploads (sending data from your home computer to the internet)

# Network devices

**Hub**:- hubs correct computers together in start topology network. due to the design, they increase the chances for colision. hub operate in the physical layer of osi model and have no intelligence. hubs flood incoming packets to all ports all the time.

**Repeater**:- A repeater is an electronic device that receive signal and retransmit it at higher level and/or higher power. or into the other side of an abstruction.  so that the signal can cover long distance without degradation.

**Modem**:- Modem (from modulator demodulator) is a device that runs the digital 1s and 0s of a personal computer into sounds that can be transmitted over the telephone lines and once received to the other side, convert those sounds back into form used by USB, Ethernet, serial or network connection.

Modems are generally classified by the amount of data they can send in given time, normally measured in bits per second, or "bps"

**NIC**:- A network interface card is a computer hardware computer design to allow computer to communicate other a computer network it is both on OSI layer 1 and layer 2 device, as it provide physical access to networking medium and provides a low level address system through the use of mac address.

**Switches**:- Switches provide a central connection between two or more computers on a network, but with some intelligence. they provide traffic control for packets, rather than forwarding data to all the connected ports, a switch forward data only to port on which the destination system is connected.

They used a database of mac address to determine where computers are located and very efficiently send packets only where they need to go.

**Bridge**:- Bridges can be identified by the fact that they operate at the data link layer of OSI model. bridges have intelligence and can "bridge"
two of their port together at very high speed.

They use a database of mac address to determine where computers are located and very efficiently send frames only where they need to go.

The database is created dynamically as computers communication on the network.

**Routers**:- Routers operate at the network layer of the OSI model and efficiently route information between local area networks. since router operate in the third layer, the network layer, they must understand layer 3 addressing, such as TCP/IP.

A router will divide a broadcast domain by not forwarding broadcast on one connected network to another connected networks.

**Wireless Access point**:- A wireless access point (WAP or AP) is a device that allows wireless communication devices to connect to a wireless network using Wifi. Bluetooth or related standards. the WAP usually connect to a weird network (such as computer or printers) and wired devices on the network.

# Hardware component of a network

# Router

![[router.jpg]]

**Device that forward data packet between computer networks. think of them as the 'post office' of the network, directing traffic to ensure it gets where its supposed to go.**


# Switches
![[switch.png]]

**These are like the 'traffic cops' for your network, they connect multiple devices on a Lan and direct the flow of data to the correct destination.**


# Network interface card

![[networkiterface.png]]
**These are hardware components installed in computers that enable them to connect to a computer**

# Software component of a network

**Operating system**:- system like windows, Macos, or Linux have built in network capabilities.

**network driver**:- These are software program that control the network hardware and provide an interface for the operating system to interact with it.

**Networking protocols**:- These are set of rules that given how data is transferred on a network.

# Transmission media

**Guided**

1. Twisted-pair cable
2. coaxial cable
3. Fiber optic cable

**Unguided**

1. Radio waves 
2. microwaves
3. infrared

# Twisted pair cable

![[twisted_pair_cable.png]]


Pair of wires (the forward and return conductors of a single circuit) are twisted together for the purposes of cancelling out Electromagnetic interference (EMI) from other wire pairs and from external sources.


**Advantages**:- cheap, easy to work with
**Disadvantages**:- low data rate, short range


# Coaxial cable

![[coaxial_cable 1.jpg]]

Coaxial cable is a type of copper cable specially built with a metal shield and other components engineered to block signal interference. it is primarily used by cable companies to connect their satellite antena facilities to customer homes and business

**Advantages**

1. Used in high frequency applications
2. improve attenuation and shield effectiveness
3. less Suspectiable to noise an interference compare to twisted pair cable
4. high bandwidth
5. cost of coaxial cable is less

**Disadvantages**

1. Bulky, thick, shift
2. Expensive to install
3. security issue
4. Grounding necessary


# Optical Fiber cable

Optical cable are used to transfer digital data signals in the form of light up to distances of hundreds of miles with higher throughput rates.

two common types of Fiber optics are:
Single mode Fiber(SMF)
Multi-mode Fiber(SMF)

![[Optical-Fiber.png]]

**Advantages**:

Extremely high bandwidth
thinner and light weighted
Resistance to Electromagnetic interference
longer distance
lower security risk

**Disadvantage**
cost
very tragic
difficult to install
Attenuation & dispersion


# Switching

A network consist of many switching devices. in order to connect multiple devices, one solution could be to have a point to point connection in between pair of devices. but this increases the number of connection.

The other solution could be to have a central device to each other and connect every device to each other vice the central device which is generally is known as star topology.

# Types of switching

![[Types-of-switching.png]]

**Circuit switching**

![[circuit_switching.png]]

Circuit switching is generally used in the public network it comes into existence for handling voice traffic in addition to digital data

After the link has been sets in between the sender and the receiver the the information is forwarded continously over the provided link.

A dedicated link/path is established across for the entire duration of conversation.

**Advantage**
1. Guarantee data rate
2. No waiting time at each switch
3. suitable for long continous transmission

**Disadvantage**
1. other nodes cannot use same channel
2. require more bandwidth
3. time required to establish physical link is too long.


**Packet switching**

To improve the efficiency of transferring information over shared communication line, messages are divided into fixed sized, numbered packets.

network devices called routers are used to direct packets between networks.

![[packet_switching.png]]


1. Messages is divided into packets
2. packers are sent over the internet by the most expedient value
3. packets are re-ordered and the re-assembled

**Advantage**

1. Efficient use of network
2. high data transmission
3. no big memory required
4. no dedicated path required
5. suitable for videos/voice cales
6. less usage cost

**Disadvantage**
1. order mismatch
2. transmission delay
3. packet loss
4. implementation cost
5. security issues



**Message switching**

![[message_switching.png]]

Here each message is treated as an independent unit and includes its can destination source address by its own.

Each complete message is then transmitted from one device to another through inter network.
Each intermediate device receive the message and store its until the next device is ready to recieve it. 

For this reason a message switching network is sometimes called as store and forward switching.

**Advantages**

1. More devices share the same channel
1. congestion can be reduced
1. support message length unlimited size.

**Disadvantage**

1. No compatible for voice and video
2. costly as store and forward device are expensive
3. can lead to security issues it hacked
4. not reliable
																	



