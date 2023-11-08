# CNS (Oral Question Bank)

**1. What are the different types of cables used in networking, and what connectors are used for each type?**
   - Ethernet cables, like Cat 5e or Cat 6, use RJ-45 connectors.
   - Fiber optic cables use connectors such as SC, LC, or ST.

**2. What is the maximum segment size for twisted pair and fiber optic cables?**
   - Twisted pair cables have a maximum segment size of 100 meters.
   - Fiber optic cables vary in maximum segment size but can extend up to several kilometers.

**3. How many wires and twists are there in UTP (Unshielded Twisted Pair) cables?**
   - UTP typically has 8 wires and 4 twists per inch.

**4. Which cable is commonly used in LANs?**
   - Ethernet cables, such as Cat 5e or Cat 6, are commonly used in LANs.

**5. What is the purpose of a firewall?**
   - A firewall provides network security by filtering and controlling incoming and outgoing traffic, protecting against unauthorized access and threats.

**6. Explain different network topologies, their advantages, disadvantages, and your preference for designing a LAN.**
   - **Star Topology:**
     - Advantages: Scalable, easy to troubleshoot.
     - Disadvantages: Dependent on a central hub or switch.
     - Preference: Preferred for its scalability and ease of troubleshooting.

   - **Bus Topology:**
     - Advantages: Simple, cost-effective.
     - Disadvantages: Single point of failure.

   - **Ring Topology:**
     - Advantages: Redundancy.
     - Disadvantages: Potential data collisions.

   - **Mesh Topology:**
     - Advantages: High redundancy.
     - Disadvantages: Complex to set up and manage.

**7. List the IEEE standards for Ethernet LAN.**
   - IEEE standards for Ethernet LAN include 802.3 (Ethernet), 802.3u (Fast Ethernet), 802.3ab (Gigabit Ethernet), and various others for specific applications.

**8. What factors do you consider when designing a network for 10 PCs?**
   - Factors to consider include bandwidth requirements, scalability for future growth, security measures, cost-effectiveness, and the need for centralized services and data storage.

**9. List the seven layers of the OSI model:**
   1. Physical
   2. Data Link
   3. Network
   4. Transport
   5. Session
   6. Presentation
   7. Application

**10. Explain the working of each layer of the OSI model:**
   - Physical: Handles the physical transmission of data.
   - Data Link: Manages data frames, error detection, and MAC addresses.
   - Network: Routes data packets across networks.
   - Transport: Ensures end-to-end communication, manages flow control, and error recovery.
   - Session: Establishes, maintains, and terminates connections.
   - Presentation: Translates, encrypts, or compresses data for transmission.
   - Application: Provides user interfaces and network services.

**11. Explain the working of each layer of the TCP/IP model:**
   - Application: This interfaces with user applications and network services, such as web browsers, email clients, and file transfer tools.
   - Transport: It ensures end-to-end communication and manages data transfer reliability using protocols like TCP (connection-oriented) and UDP (connectionless).
   - Internet: Responsible for routing data packets across different networks, using IP addresses to determine the best path for data transmission.
   - Link: Manages the physical transmission of data within a local network segment, addressing and framing data for efficient communication between devices on the same network.

**12. Highlight the differences between OSI and TCP/IP models:**
   - OSI has 7 layers; TCP/IP has 4 layers (Application, Transport, Internet, Link).
   - OSI is a theoretical model, while TCP/IP is the basis for the internet.
   - OSI's presentation and session layers are integrated into the TCP/IP Application layer.

**13. List the protocols that operate at each layer of the OSI model:**
   - Physical: Ethernet, USB
   - Data Link: Ethernet, Wi-Fi (802.11)
   - Network: IP, ICMP
   - Transport: TCP, UDP
   - Session: NetBIOS, RPC
   - Presentation: SSL/TLS, JPEG
   - Application: HTTP, SMTP, FTP

**14. List networking devices that function at each layer of the TCP/IP model:**
   - Application: End-user devices (computers, smartphones).
   - Transport: Routers, switches.
   - Internet: Routers, layer 3 switches.
   - Link: Network interface cards (NICs), switches.

**15. What is ATM (Asynchronous Transfer Mode)?**
   - ATM (Asynchronous Transfer Mode) is a high-speed, cell-based switching and multiplexing technology used for data and voice communication.

**16. Define tunneling in networking.**
   - Tunneling in networking is the process of encapsulating one network protocol within another to transmit data securely or across incompatible networks.

**17. Explain what fragmentation is in networking.**
   - Fragmentation in networking refers to the division of data packets into smaller segments to accommodate transmission over networks with lower Maximum Transmission Unit (MTU) sizes.

**18. Describe the two types of transmission technology available.**
   - The two types of transmission technology available are Circuit Switching (dedicated communication path) and Packet Switching (data divided into packets for flexible routing).

**19. What is subnetting, and when should it be used?**
   - Subnetting is the process of dividing a larger IP network into smaller subnetworks; it should be used to manage IP address allocation efficiently.

**20. Explain the difference between communication and transmission.**
   - Communication is the exchange of information between two or more parties, while transmission is the physical or electronic transfer of data from one point to another.

**21. What is a router?**
   - A router is a network device that forwards data packets between computer networks, making decisions based on IP addresses.

**22. Describe the Point-to-Point Protocol (PPP).**
   - PPP is a data link protocol for establishing a direct connection between two devices, often used for internet connections, and providing error detection and authentication.

**23. What is a MAC address, and how many bits is it typically composed of?**
   - A MAC (Media Access Control) address is a hardware address for network interfaces, typically composed of 48 bits.

**24. At which OSI layer does the IP address work, and can you provide an example?**
   - IP addresses work at the network layer (Layer 3) of the OSI model. Example: 192.168.1.1.

**25. How many classes are there in IPV4, and what are the ranges for each class?**
   - There are 5 classes (A, B, C, D, and E). Class A: 1.0.0.0 to 126.0.0.0, Class B: 128.0.0.0 to 191.0.0.0, Class C: 192.0.0.0 to 223.0.0.0.

**26. For each class, indicate the number of networks and hosts.**
   - Class A: 16,777,214 networks and 16,777,214 hosts. Class B: 65,534 networks and 65,534 hosts. Class C: 2,097,150 networks and 254 hosts.

**27. What is the default subnet mask for classes A, B, and C?**
   - Class A: 255.0.0.0, Class B: 255.255.0.0, Class C: 255.255.255.0.

**28. Explain the concepts of physical and logical addresses.**
   - A physical address is a hardware-specific address, like a MAC address. A logical address is a network-specific address, like an IP address, used for routing and communication.

**29. What are the different types of transmission media?**
   - Transmission media include wired (e.g., coaxial cable, fiber optics) and wireless (e.g., radio waves, microwaves) mediums for data communication.

**30. What is a repeater?**
   - A repeater is a network device that amplifies and retransmits signals to extend the range of a network, often used in telecommunication and networking.

**31. What is the purpose of bridges?**
   - Bridges are used to connect and filter traffic between two or more network segments to improve network performance and security.

**32. Define routers.**
   - Routers are devices that connect different networks and determine the best path for data to travel between them, typically used in IP-based networks.

**33. What is a gateway?**
   - A gateway is a device or software that connects two different networks using different protocols, facilitating communication between them.

**34. What is the role of switches?**
   - Switches are network devices that forward data at the data link layer, making decisions based on MAC addresses to connect devices within the same network.

**35. Differentiate between hubs and switches.**
   - Hubs operate at the physical layer and broadcast data to all connected devices, while switches operate at the data link layer and intelligently forward data to specific devices.

**36. Highlight the differences between switches and routers.**
   - Switches operate at the data link layer, directing traffic within a network, while routers operate at the network layer, making decisions for traffic between networks.

**37. Define cutoff switch and store-and-forward switch.**
   - A cutoff switch is a switch that immediately forwards data without storing it, while a store-and-forward switch buffers data before forwarding it.

**38. Explain manageable and unmanageable switches.**
   - Manageable switches allow for configuration and monitoring, while unmanageable switches offer limited or no configuration options and are plug-and-play.

**39. Why do we need web servers?**
   - Web servers are essential for hosting websites and serving web content to users when they request it.

**40. Define broadcast, multicast, and unicast.**
   - Broadcast sends data to all devices on a network, multicast sends data to a select group, and unicast sends data to a specific device.

**41. Explain what FDDI (Fiber Distributed Data Interface) is.**
   - FDDI is a high-speed fiber optic network technology used for reliable data transmission in LANs.

**42. What are Token Ring and Token Bus networks?**
   - Token Ring and Token Bus are older LAN technologies where devices take turns to transmit data using tokens.

**43. List IEEE standards from 802.2 to 802.16.**
   - IEEE standards from 802.2 to 802.16 include Ethernet (802.3), Wi-Fi (802.11), and more.

**44. Differentiate between leased lines and dial-up connections.**
   - Leased lines are dedicated, high-speed connections, while dial-up connections use phone lines and are slower and on-demand.

**45. What is an ISP (Internet Service Provider)?**
   - An ISP is a company that provides internet access and related services to individuals and organizations.

**46. Explain ICMP (Internet Control Message Protocol).**
   - ICMP is a network protocol used for sending error messages and operational information about IP packet delivery.

**47. What are the data units at different layers of the TCP/IP protocol suite?**
   - Data units: At the Link layer, it's frames; Network layer, packets; Transport layer, segments; Application layer, data.

**48. Explain the difference between ARP (Address Resolution Protocol) and RARP (Reverse ARP).**
   - ARP resolves IP to MAC addresses, while RARP resolves MAC to IP addresses.

**49. What is the minimum and maximum length of the header in the TCP segment and IP datagram?**
   - TCP: Minimum 20 bytes, maximum 60 bytes; IP: Minimum 20 bytes, maximum 60 bytes.

**50. Highlight the differences between TFTP (Trivial File Transfer Protocol) and FTP (File Transfer Protocol).**
   - TFTP is simpler, lacks authentication, and uses UDP, while FTP is more feature-rich, includes authentication, and uses TCP.

**51. Describe major types of networks.**
   - Major network types: LAN (Local Area Network), WAN (Wide Area Network), MAN (Metropolitan Area Network), PAN (Personal Area Network), WLAN (Wireless LAN).

