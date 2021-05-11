# Domain Name System(DNS)

**Domain Name System is a system of devices that helps us find corresponding [IP address](https://github.com/ShubhamJagtap2000/Computer-Networking/blob/main/IP-Addressing-And-NAT.md) of a domain name.**

**Domain Name:** It is a humanly understandable name of any web application hosted on one or more servers, and it helps us connect to them.

**Reasons why we can't have a directory of domain names and their corresponding addresses in our systems:
 
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
    
