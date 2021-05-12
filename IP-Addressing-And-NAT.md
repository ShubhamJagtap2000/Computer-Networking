# IP Addressing and NAT(Network Address Transition)

## Client-Server Model & Data Packets:

- Server is a type of computer which stores data and sends it whenever asked for. 
- All website data is stored in server assigned to that website.
- When you type website name and hit ENTER, your device sends a request to server and in response, the page is sent to your computer.
- This is called Client-Server Model.

**When image loads lowly in case of slow internet connection, is because whenever you request image data, server breaks it  down into small chunks called "Data Packets" and then sends to us, it makes the communication efficient.**

## IP Address:

- When you're connected to a network, a unique number is automatically assigned to your device. It's called the IP address.

**Static IPs:** When you're disconnected from earlier internet, your IP doesn't change when you connect again.

**Dynamic IPs:** Your IP address changes when you connect again.

## IP Address Versions:

**1. IPv4:** 

- IPv4 is the fourth version of the internet protocol. It is one of the core protocols of standards-based internetworking methods on the internet. It is 32 bits long.
- Pattern of IPv4 is A.B.C.D where all A,B,C,D are numbers between 0 and 255.
- As using only IPv4 all the people cannot join a network(more than 4.2 billion), so IPv6 was introduced.

**2. IPv6:** 

-  IPv6 is the most recent version of the Internet protocol that provides an identification and location system for computer networks. IPv6 was created to dominate over the IPv4 address exhaustion.
-  Pattern of IPv6 is A:B:C:D:E:F:G:H where, all A,B,C,D,E,F,G,H are hexadecimal numbers.
-  Old devices don't support IPv6, so NAT is there. So, we deal with a combination of both IPv4 and IPv6.

### **Public IP:**

- It is the IP that identifies your device on Internet.
- Everyone else on internet can have idea about your public IP.

### **Private IP:**

- The Ip that identifies your device on your own personal network. e.g. At home.

 ### IP Address Range:
 
 | Range | Area |
 | --- | --- |
 | 192.168.0.0 to 192.168.255.255 | Home or Office |
 | 172.16.0.0 to 172.31.255.255 | Large MNCs, Colleges |
 | 10.0.0.0 to 10.255.255.255 | Telecomm., Satellites | 
 
**127.0.0.1 is called as 'localhost' or loopback address. IP address of your own machine.**
