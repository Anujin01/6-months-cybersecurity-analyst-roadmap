# IP address (October 28, 2025)

IP address is unique identifier for devices over the network. It tells the network where to send data and receive it. It is assigned DHCP or manually by the user. 
# IP versions

There are 2 versions of IP addresses. IPv4 uses 32-bit format which is old but still in use provide over billions of IP addresses. IPv6 uses 128-bit format allows many more IP address in use as technology expands.
# Public vs Private IP address
There are 2 types of IP addresses where you can use locally inside and visible on the internet. To understand this, we need to talk about NAT (network address translation) a system that translates many private addresses to router making it one public address to send data on the internet. Each device has private IP address locally, when it sends or receives data over the network first go through router and NAT translates it into public IP, when it receives data, it sees the port number and go through NAT’s translation table which records public and private port numbers and IP addresses and find the receiver. 
# Subnetting
Subnetting is a process of dividing large network into smaller to make it easier to manage. 

* 192.161.1.10 – IP address
* 255.255.255.0 – subnet mask
* 192.161.1 – is your networking part shared by everyone in the local network like your neighborhood  
* 10 – is your specific address to find you from the neighborhood 

| Range                             | CIDR           | Typical Use                                 | Example      |
| --------------------------------- | -------------- | ------------------------------------------- | ------------ |
| **10.0.0.0 – 10.255.255.255**     | 10.0.0.0/8     | Large private networks (companies, schools) | 10.10.1.25   |
| **172.16.0.0 – 172.31.255.255**   | 172.16.0.0/12  | Medium private networks                     | 172.20.5.14  |
| **192.168.0.0 – 192.168.255.255** | 192.168.0.0/16 | Small networks (home Wi-Fi, routers)        | 192.168.1.10 |


