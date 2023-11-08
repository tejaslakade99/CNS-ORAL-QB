# Computer Networks and Security (Oral Question Bank)

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

