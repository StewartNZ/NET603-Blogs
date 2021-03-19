# Blog - 03

> ## 09/03/2021

### DNS

I'll be honest I had a hard time keeping track of what we went over in class, I think it was about how DNS works, VPN's and how these are set up in LAN networks and how they connect out of them.

### Homework Subnetting

190.240.0.0/16

-   Want large subnets at least 1000 hosts each
-   10 bits used for 1024
-   CIDR: **22**
-   Number of hosts: **1022**
-   Subnet Mask: 11111111.11111111.111111/00.00000000 **255.255.252.0**
-   Number of Subnets: **64**

-   First Net Address: **190.240.0.0**
-   First subnet first usable host: **190.240.0.1**
-   First subnet last usable host: **190.240.3.254**
-   First Broadcast address: **190.240.3.255**

-   Second Net Address: **190.240.4.0**
-   Second subnet first usable host: **190.240.4.1**
-   Second subnet last usable host: **190.240.7.254**
-   Second broadcast address: **190.240.7.255**

> ## 11/03/2021

### Top Down Net Design

The top down net design is about designing a network by going down the OSI model starting at the application level or above. More to come. In our group Daniel had set up a pfSense router so I got him to show me what he's done so far which was set up 2 network adapters that connect to WAN and LAN respectively. The WAN adapter connects to the internet while the LAN router is what our other workstations connect through.

[Return](https://stewartnz.github.io/NET603-Blogs/)
