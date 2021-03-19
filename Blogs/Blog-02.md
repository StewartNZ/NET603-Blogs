# Blog - 02

> ## 02/03/2021

### More Subnetting

Todays class went over more subnetting examples and we were given an example to work through and find the mask, number of subnets and how many hosts each subnet has.

-   Original Network Address: 192.168.0.0/16
-   Take 5 bits for subnetting: CIDR **21**
-   Subnet Mask: 11111111.11111111.11111/000.00000000 **(255.255.248.0)**
-   Number of Subnets: 5 bits of subnetting 2^5 = **32** subnets
-   Number of Hosts per subnet:
    -   Number of bits 16 - 5 = **11** bits
    -   Number of addresses per subnet 2^11 = **2048**
    -   Number of subnets - net address and broadcast address = **2046**
-   First 4 Net and Broadcast Adresses:
    1.  -   192.168.0.0 Net Address
        -   192.168.7.255 Broadcast Address
    2.  -   192.168.8.0 Net Address
        -   192168.15.255 Broadcast Address
    3.  -   192.168.16.0 Net Address
        -   192.168.23.255 Broadcast Address
    4.  -   192.168.24.0 Net Address
        -   192.168.31.255 Broadcast Address
    5.  To get any further addresses:
        -   Net = xxx.xxx.(previous + 8).0
        -   Broadcast = xxx.xxx.(net + 7).255

> ## 04/03/2021

### IPv6 and Introduction to VSphere VM's

This class we covered IPv6 and Hexadecimal. Hexidecimal or just Hex is a more readable version of binary but where every digit represents 4 bits and has the range of 0 to 9 plus A to F to keep it as a single digit. An IPv6 address is made up of 8 sections of 4 Hex digits or 1 Hextet making a total of 128 bits for each address.

The other thing we did in this class was sign into Talos vSphere and have a look around and make a Virtual Machine. We were shown how there are virtual switches you can set up and were shown and example of a router using pfSense.

[Return](https://stewartnz.github.io/NET603-Blogs/)
