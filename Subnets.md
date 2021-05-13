# Subnets

- Networks are broken down further into what are called as "Subnets"
- These, as their name implies are just sub-networks tat group together devices that can communicate with each other/ You may have seen an IP address before written like **198.162.1.0/24**
- This actually represents the address range for a **/24** subnet
- An IP address is made up of 4 numbers that range from 0-255 and are separated by dots
- These numbers are each called octets because they ultimately made up of 8 bits
- Altogether, IP address contains 8 * 4 = 32 bits
- When we talk about a /24 subnet, it simply means that the first 24 bits(or last 3 octets) are set in stone this section of address are known as Network Addresses
- So, when we have a subnet like, **198.162.1.0/24**, the part 198.162.1.0 is going to be same for all addresses for that subnet with the only difference being the last octet
- As a result, a /24 subnet can have 256 addresses, it can only have 256 hosts
