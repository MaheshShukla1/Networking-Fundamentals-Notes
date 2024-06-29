# Introduction to Networking 🌐
* Welcome to the Introduction to Networking repository! These notes are designed to provide a beginner-friendly yet comprehensive understanding of networking concepts, from the basics to more advanced topics. Let's dive in! 🚀
  
 ## [Introduction To Networking](https://github.com/MaheshShukla1/Networking-notes-101/wiki/Introduction-to-Networking#network-devices)

 ## [OSI MODEL & TCP/IP MODEL](https://github.com/MaheshShukla1/Networking-notes-101/wiki/OSI-MODEL-AND-TCP-IP-MODEL)

 ## [IP SUBNETTING AND CIDR NOTATION](https://github.com/MaheshShukla1/Networking-notes-101/wiki/IP-Subnetting-CIDR-Notation#ipv6-subnetting)

 ## [Network Address Translation (NAT)](https://github.com/MaheshShukla1/Networking-notes-101/wiki/Network-Address-Translation)

 ## [Internetworking Basics: Protocols, Connectivity, and Future Trends](https://github.com/MaheshShukla1/Networking-notes-101/wiki/Internetworking-Basics:-Protocols,-Connectivity,-and-Future-Trends)

 ## [Networking Fundamentals: TCP vs UDP, Routing, And Wireless Networks](https://github.com/MaheshShukla1/Networking-Fundamentals-Notes/wiki/Networking-Fundamentals:-TCP-vs-UDP,-Routing,-and-Wireless-Networks)

 ## [Network Redundancy and load balancing](https://github.com/MaheshShukla1/Networking-Fundamentals-Notes/wiki/Network-Redundancy-and-load-balancing)

 ## [Firewall & IDS IPS](https://github.com/MaheshShukla1/Networking-Fundamentals-Notes/wiki/Firewall-&-IDS-IPS)


# Comprehensive Guide to VPNs and Wireless Networks

This repository provides a detailed guide to understanding Virtual Private Networks (VPNs) and Wireless Networks, covering their definitions, functionalities, types, security implications, and setup recommendations.

## What is VPN?

A Virtual Private Network (VPN) creates a secure, private connection over a public network like the internet to protect your online activities.

### How does a VPN work?

- **Encryption**: Your data is encrypted to ensure only authorized parties can understand it.
  
- **Secure Tunnel**: Encrypted data travels through a secure tunnel to a VPN server.
  
- **Decryption and Routing**: The VPN server decrypts your data and forwards it to its destination on the internet.
  
- **Anonymity**: To the internet, your data appears to come from the VPN server, masking your real location and identity.

## Types of VPN

- **Remote Access VPN**: Securely connects individual users to a remote network.
  
- **Site-to-Site VPN**: Connects entire networks, commonly used by companies with multiple offices.
  
- **Intranet-based VPN**: Joins multiple remote locations into a single private network.
  
- **Extranet-based VPN**: Connects external parties like customers to a private network.

## Pros of Using a VPN

- **Enhanced Privacy**: Masks your IP address and encrypts your data, protecting you from surveillance.
  
- **Bypass Geographical Restrictions**: Access content not available in your country by connecting to servers elsewhere.
  
- **Secure Public Wi-Fi**: Keeps your data safe on unsecured public networks.
  
- **Avoid Throttling**: Prevents ISPs from slowing down your internet speed based on your activities.

## Cons of Using VPN

- **Speed Impact**: Encryption and routing can sometimes slow down your internet speed.
  
- **Website Blocking**: Some sites detect and block VPN connections.
  
- **Cost**: Quality VPN services often come with a subscription fee.
  
- **Trust in Provider**: You need to trust your VPN provider with your data.

## VPN and Privacy

VPNs are crucial for protecting your online privacy by masking your IP address and encrypting data, making it difficult for anyone to track your online activities.

## Legality of VPNs

In most countries, VPNs are legal and widely used for privacy and security. However, some countries restrict VPN usage due to censorship or monitoring concerns.

## Understanding Wireless Networks

Wireless networks use radio waves to connect devices without physical cables, providing convenience but also introducing security challenges. Protocols manage data transmission rules, ensuring devices know when to send and receive data.

### Vulnerabilities of Wireless Networks

- **Eavesdropping**: Anyone within range can intercept and listen to data transmissions, potentially exposing sensitive information.
  
- **Unauthorized Access**: Weakly protected networks can be accessed by unauthorized users, leading to data theft or network disruption.
  
- **Interferences**: External devices or networks can disrupt wireless signals, impacting network performance.
  
- **Spoofing**: Malicious actors can create fake networks (Evil Twins) to trick users into connecting and steal their data.
  
- **Physical Attacks**: Hardware vulnerabilities like router attacks can compromise network integrity.

### Common Wireless Network Threats

- **Rogue Access Points**: Unauthorized access points create backdoors into secure networks.
  
- **War Driving**: Driving around to discover and exploit unprotected WiFi networks.
  
- **Evil Twin Attacks**: Setting up fake networks to intercept user data.
  
- **Wireless Phishing**: Tricking users into connecting to malicious websites.
  
- **Denial of Service (DoS)**: Overloading networks to disrupt service.
  
- **Man-in-the-Middle Attacks**: Intercepting and altering communication between devices.

### Wireless Encryption Protocols

- **WEP (Wired Equivalent Privacy)**: Basic encryption vulnerable to key cracking.
  
- **WPA (WiFi Protected Access)**: Improved encryption with periodic key changes.
  
- **WPA2 (WiFi Protected Access 2)**: Strong encryption using AES.
  
- **WPA3 (WiFi Protected Access 3)**: Enhanced security against brute-force attacks.

### Secure Wireless Network Setup

- **Choose the Right Router**: Select a router supporting WPA3 and keep firmware updated.
  
- **Change Default Router Password**: Set a strong, unique password to prevent unauthorized access.
  
- **Enable Network Encryption**: Use WPA3 or WPA2 for secure data transmission.
  
- **Create a Strong Network Password**: Protect network access with a strong password.
  
- **Disable Remote Management**: Minimize security risks by disabling remote access unless necessary.
  
- **Set Up a Guest Network**: Separate guest access to protect main network devices.
  
- **Turn on Network Firewalls**: Activate built-in firewalls for added security.
  
- **Turn off WPS**: Disable WiFi Protected Setup to reduce vulnerabilities.
  
- **Wireless Intrusion Prevention System (WIPS)**: Constantly monitor network activity, identify threats, and take preventive measures to maintain network security.

# All In one OSI Model cheat sheet
What is the OSI Reference Model?

The Open Systems Interconnection (OSI) model is a way to represent how devices communicate with one another. It consists of seven layers:

1. Physical
2. Data link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

You receive data from layers 1 through 7 and transmit data in the opposite direction. That’s because every layer of the OSI Model handles a specific job and passes data to and from the layers above and below itself.

Although building computing devices doesn’t require the OSI model, it’s proven helpful in troubleshooting computer networking problems. That’s because the OSI model gives technicians an in-depth method to dissect the network problem to find its root cause. The solution often becomes clear by narrowing it down to a specific model layer.

## OSI Layers

The infographic below summarizes the seven layers of the OSI reference model. If you need a quick refresher, this is the image to [download](https://www.stationx.net/wp-content/uploads/2023/03/The-7-Layer-OSI-Model.jpg).

![The 7-Layer OSI Model](https://www.stationx.net/wp-content/uploads/2023/03/The-7-Layer-OSI-Model.jpg "The 7-Layer OSI Model. Text: No. Layer Function Data unit Hardware Protocols 7 Application Human-computer interaction through applications that access network services Message/data Gateway UPnP, DHCP, DNS, HTTP, HTTPS, NFS, NTP, POP3, SMTP, SNMP, FTP, Telnet, SSH, TFTP, IMAP 6 Presentation Data formatting and encryption/decryption Message/data Gateway redirector TLS, SSL, AFP 5 Session Inter-host communication Message/data Gateway NetBIOS, RPC, SMB, Socks 4 Transport Data transmission TCP: segment; UDP: datagram Gateway TCP, UDP, SCTP 3 Network Path determination and logical addressing Packet, datagram Router, Brouter ARP, IP, NAT, ICMP, IPsec, ICMP (ping) 2 Data Link Physical addressing Frame, cell Switch, bridge, NIC ARP, Ethernet, L2TP, LLDP, MAC, NDP, PPP, PPTP, VTP, VLAN 1 Physical Binary signal transmission over physical media Bit, frame Cables, modem, hub, repeater, NIC, multiplexer Ethernet, IEEE802.11, ISDN, USB, Bluetooth")

The given examples of protocols are for your reference only. For a complete list, check out our [Ports and Protocols Cheat Sheet](https://www.stationx.net/common-ports-cheat-sheet/).

## What Does Each Layer Do

Let’s consider the scenario of receiving an email on your smartphone. How did the email arrive? What has been going on right up to the moment you got the “New Email” notification?

According to the OSI reference model, the following events have transpired:

### Layer 1: The Physical Layer

The virtual world is fascinating, but [the matrix](https://www.stationx.net/movies-for-hackers-to-watch/) requires a physical component. The physical layer of the OSI model is a tangible or intangible medium through which our devices send and receive electronic signals.

Wired **Ethernet** cables are a well-worn example of the physical layer. Still, given the ubiquity of smart devices, we want our illustration in this article to be relevant to the times.

Suppose you’ve connected your phone to a Wi-Fi **access point (AP)**. The AP receives electromagnetic signals of ones and zeros called bits all day, some of which correspond to the email message we’ve mentioned.

The physical layer takes out the portions corresponding to the **preamble**, **start frame delimiter (SFD)**, and the **frame check sequence (FCS)**. It then passes the rest to the data link layer as a frame.

#### Definitions:

- **Ethernet:** the traditional cabling technology for connecting telecommunication devices in a wired network
- **AP: (wireless) access point;** a networking hardware device that allows other Wi-Fi devices to connect to a wired network
- **Preamble:** an indicator of the end of header information used to synchronize a data transmission
- **SFD: start frame delimiter;** a data field in the header of a transmission frame that marks the start of data
- **FCS: frame check sequence;** an error-detecting code added to a frame in a communication protocol

![Physical](https://www.stationx.net/wp-content/uploads/2023/03/1.-Physical.jpg "The Physical Layer")

### Layer 2: The Data Link Layer

The data link layer is usually a **network interface card (NIC)** in a switch or a bridge. Your smartphone contains networking and routing components, so it has no separate NIC. The NIC or networking circuitry reads the source and destination **MAC addresses**, which it expects to map to devices on the **local area network (LAN)**, itself included.

Next, it compares the destination MAC address against the MAC address burned into it. If they match, this layer sends the frame to the network layer as an IP packet. Otherwise, they’re undeliverable and discarded because MAC addresses only make sense within a LAN.

As for the source MAC address, the data link layer keeps it in its memory in case the network layer requires it in a return route. In that scenario, this layer attaches the source MAC address to the data frame as the new destination MAC address.

#### Definitions:

- **NIC: network interface card;** for connecting a computer to a computer network
- **MAC address: media access control address;** a unique identifier assigned to a NIC for use as a network address in communications within a network segment
- **LAN: local area network;** a series of computers connected as a network in a circumscribed location
- **IP: Internet Protocol;** for logical addressing across computer networks

![Data Link](https://www.stationx.net/wp-content/uploads/2023/03/2.-Data-Link.jpg "The Data Link Layer")

### Layer 3: The Network Layer

You can no longer rely on MAC addresses to send data packets across distributed networks larger than a LAN, such as in the broader Internet. The network layer is where we use logical addressing, such as IP addresses, to identify different nodes in large networks.

The network layer, usually a router, picks up an IP packet from the previous layer. Using network layer protocols such as **Address Resolution Protocol (ARP)** and **Network Address Translation (NAT)**, it reads the source and destination IP addresses, saves the source IP address for sending responses, and checks if the destination IP address is your device’s.

If yes, it strips both IP addresses of the packet, and the remainder, which is often a **TCP** segment or a **UDP** datagram, moves upward to the transport layer. If not, the IP packet is lost because the network layer has discarded it.

Your phone is also a router, so it does the above automatically. As an aside, this is also why you can use your phone as a Wi-Fi hotspot.

#### Definitions:

- **ARP: Address Resolution Protocol;** for uncovering the MAC address associated with an IP address
- **NAT: Network Address Translation;** the process of mapping an IP address to another by changing the header of IP packets while in transit via a router
- **TCP: Transmission Control Protocol;** a connection-oriented protocol that helps establish and maintain connections until the applications on both ends have completed data exchange.
- **UDP: User Datagram Protocol;** a connectionless protocol that enables data transfer before reaching an agreement with the receiving party.

![Network](https://www.stationx.net/wp-content/uploads/2023/03/3.-Network.jpg "The Network Layer")

### Layer 4: The Transport Layer

The transport layer is for processing chunks of data called TCP segments and UDP datagrams. The purpose of this layer is to assemble and disassemble these different pieces of incoming data.

The size of a data link frame has an upper limit, such as 1500 bytes for an Ethernet frame, so the payload of a segment/datagram may be a portion of a larger set of data. The transport layer rearranges these portions as appropriate and either joins them to recover the entire body of data received or splits them up before transmission.

In the case of the email reaching your phone, the transport layer pieces together the TCP segments corresponding to various components of your message—sender, recipient, timestamp, subject line, content, attachments—and passes the data on to the session layer.

![Transport](https://www.stationx.net/wp-content/uploads/2023/03/4.-Transport.jpg "The Transport Layer: TCP vs UDP communication")

### Layer 5: The Session Layer

The session layer makes and maintains connections between your local host and remote hosts. Data can travel between your phone’s mail client and the email server if they share an established connection via TCP or UDP.

The data containing your email has reached the session layer, which saves the source and destination port information. It uses the source port number to send data back, such as an acknowledgment receipt or an error message, such as a nonexistent addressee or a full mailbox unable to receive new mail.

Now that the session layer has received the reassembled email data and your mailbox has space, this layer pushes the data forward to the port number of your phone’s email client.

![Session](https://www.stationx.net/wp-content/uploads/2023/03/5.-Session.jpg "The Session Layer: Two computers exchanging data")

![Well-Known Ports](https://www.stationx.net/wp-content/uploads/2023/03/Well-Known-Ports.png "Well-Known Ports: Unencrypted vs Encrypted - Graphic by author")

From our [Ports and Protocols Cheat Sheet](https://www.stationx.net/common-ports-cheat-sheet/)

### Layer 6: The Presentation Layer

The conventional function of the presentation layer is to ensure the correct application receives the data from the previous layer for processing and that the data is in a valid format for viewing. Data encryption and decryption happen at this layer.

Most email services support the POP3S and IMAPS protocols for receiving emails. The TLS/SSL portion of these protocols belongs to the presentation layer. Or, if you use end-to-end encrypted email services such as [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/), this is the layer where your emails stay encrypted until you click each subject line.

Some instructors deem the presentation layer disposable because computer applications have become robust enough to read almost all data types or return relevant error messages. In other words, all data is now machine-readable, even if it outputs gibberish.

![Presentation](https://www.stationx.net/wp-content/uploads/2023/03/6.-Presentation.jpg "The Presentation Layer: Encryption and decryption happen here.")

### Layer 7: The Application Layer

Your phone buzzes. A new notification appears. You’ve got mail. Your email app is working as expected. Is that all to the application layer? For receiving emails, this is it. But for sending emails, no.

This layer is responsible for the features built into the application that make them aware of networks, such as an Application Programming Interface (API). Taking emails as an example, email APIs, such as [Mailchimp](https://mailchimp.com/) or [Constant Contact](https://www.constantcontact.com/), are for sending automated emails, such as payment receipts, password resets, and newsletters.

![Application](https://www.stationx.net/wp-content/uploads/2023/03/7.-Application.jpg "The Application Layer: Receiving an innocuous email... only to be cyberattacked")

## The TCP/IP Reference Model

The TCP/IP model is a model of digital communications which laid the foundation for the modern Internet and most Internet protocols we use today. Since it’s older than the OSI model, it’s more accurate to say the OSI model is an alternative to the TCP/IP model rather than the other way around.

Therefore, a [major point of criticism](https://www.geeksforgeeks.org/critique-of-the-osi-model-and-protocols/) raised against the OSI model was that it emerged too late in the history of the Internet to be a game-changer. Here’s a graphic comparing both models:

![OSI Model vs. TCPIP Model](https://www.stationx.net/wp-content/uploads/2023/03/OSI-Model-vs.-TCPIP-Model.jpg "OSI Model vs. TCP/IP Model")


## What's Included? 📚
* 💻 Basics of Networking: Understand the fundamental principles of networking, including communication protocols, data transmission, and network topologies.

* 🌐 OSI Model Demystified: Dive deep into the OSI (Open Systems Interconnection) model, exploring its seven layers and how they function together to enable network communication.

* 📡 TCP/IP Protocols Explained: Learn about the TCP/IP (Transmission Control Protocol/Internet Protocol) suite, the backbone of the modern internet, including its protocols like HTTP, FTP, DNS, and more.

* 🛠️ Network Devices and Their Functions: Explore the role and functionality of various network devices such as routers, switches, firewalls, and access points in building and managing networks.

* 📋 And Much More!: These notes cover a wide range of topics, including subnetting, IP addressing, network security principles, troubleshooting techniques, and network management concepts.

## 🚀 Getting Started 
* To access these valuable resources:
* 📥 Clone or Download: Clone this repository or download the files to your local machine.
* 📚 Explore and Learn: Dive into the notes and start exploring the world of networking at your own pace.
* 🤝 Share and Collaborate: Feel free to share these notes with others and collaborate on improving them.

## 🤝 Contributions Welcome 
* Contributions and feedback are always welcome! If you find any errors, have additional insights to share, or want to contribute new content, please follow the guidelines outlined in CONTRIBUTING.md.

## 📧 Contact 
* Got questions or suggestions? Reach out to me at shuklamahesh602@gmail.com or through my GitHub profile.

## 💳 Credits
Mahesh Shukla acknowledges any sources or references if applicable for their valuable resources that added in the creation of these notes.

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). You are free to:

- Share: Copy and redistribute the material in any medium or format.
- Adapt: Remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- Attribution: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
