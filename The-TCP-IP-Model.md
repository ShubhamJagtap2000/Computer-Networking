# Understanding the TCP/IP Model

### **Data Flow in TCP/IP:**

![image](https://user-images.githubusercontent.com/63872951/118538356-b28e8380-b76b-11eb-8716-7e5463333f3b.png)

**1. Application Layer:**

- This is 4th layer
- Encodes, compresses and encrypts data
- It initiates sessions
- A session involves signalling to setup and manage communication between two devices
- A browser acts as application layer
- Protocols involved in this layer: HTTP, HTTPS, FTP, TelNet

**2. Transport Layer:**

- This is the 3rd layer
- Here, the port numbers are added to the services
- Protocols used: TCp, UDP

**3. Network Layer:**

- This is 2nd layer
- Handles IP addressing, route and virtual pathing
- IT adds MAC addresses of client and server
- Protocols used: DHCP, ARP, ICMP

**4. Physical Layer:**
 
- First layer
- It converts binary signals to electrical signals for data transfer
- It checks itself for errors e.g. Wi-Fi Adapter
- Protocols used: Ethernet, 802.11, DSL

- After going through all the above layers sequentially, signals from physical layer of sender are received by physical layer(1st layer) of receiver side and processed again.
