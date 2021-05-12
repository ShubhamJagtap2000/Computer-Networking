# Domain Name System(DNS)

**Domain Name System is a system of devices that helps us find corresponding [IP address](https://github.com/ShubhamJagtap2000/Computer-Networking/blob/main/IP-Addressing-And-NAT.md) of a domain name.**

**Domain Name:** It is a humanly understandable name of any web application hosted on one or more servers, and it helps us connect to them.

**Reasons why we can't have a directory of domain names and their corresponding addresses in our systems:**
 
1. It will be a long list and it will take too much time.
2. IP addresses change.
 
**Why DNS is made up of series of servers and not just one server?**

1. One server cannot store information about so many domain.
2. One server cannot handle millions of incoming requests/second.

**Working of DNS:**

e.g. drive.google.com(.)

1. **Root Name Server:** DNS Server dealing with the root name is called as Root Name Server. It is added automatically. There are 13 Root Name Servers in the world.
2. **Top Level Domain(TLD):** Stored in TLD server. There may be second level server in this domain name. e.g. drive.google.co.in.

**Here,**

  '.' at last denotes Root Name Server\
  '.' after 'co' denotes the Top Level Domain\
  '.' after 'google' denotes the Second Level Domain
  
- notesHow it works?

Browser first searches/checks the address in cache memory(most frequently used). Say, our browser doesn't get this domain name in cache, so it sends a web-request to ISP(Internet Service Provider), we will connect to default DNS server of ISP(also called resolving name server) to connect this server we need its IP.It is always static. Say, we didn't get the IP address in tis cache also, then t starts reading somain name and goes to the Root Name Server(RNS), RNS remembers the IP of the root. It also sees request IP in its cache, say we didn't get it there also. Then it goes to the Top-Level Domain(TLD), '.com' server. let's say it is unable to find the request IP address here as well. Then it looks at the '.google' part and passes its IP to ANS, default DNS goes to ANS, here, 'drive' is subdomain of google so, ANS finally gives the DNS request IP address, default DNS server stores this IP in cache and gives it to OS and to browser get connected to the entered domain name. i.e. https://drive.google.com

- DNS lookup
1. press Windows(Keyboard icon) + R
2. Type cmd and press ENTER
3. Type 'nslookup', space, domain name that you want to see IP address for(e.g. google.com)
4. This will show you the most recent IP address of google

![Screenshot (207)](https://user-images.githubusercontent.com/63872951/117928676-81502680-b319-11eb-8812-df458cad9f17.png)
