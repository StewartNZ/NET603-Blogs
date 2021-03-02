# Blog - 02
> ## 02/03/2021

### More Subnetting

Todays class went over more subnetting examples and we were given an example to work through and find the mask, number of subnets and how many hosts each subnet has.

* Original Network Address: 192.168.0.0/16
* Take 5 bits for subnetting: CIDR __21__
* Subnet Mask: 11111111.11111111.11111/000.00000000 __(255.255.248.0)__
* Number of Subnets: 5 bits of subnetting 2^5 = __32__ subnets
* Number of Hosts per subnet: 
    * Number of bits 16 - 5 = __11__ bits
    * Number of addresses per subnet 2^11 = __2048__
    * Number of subnets - net address and broadcast address = __2046__
* First 4 Net and Broadcast Adresses:
    1. 
        * 192.168.0.0 Net Address
        * 192.168.7.255 Broadcast Address
    2. 
        * 192.168.8.0 Net Address
        * 192168.15.255 Broadcast Address
    3. 
        * 192.168.16.0 Net Address
        * 192.168.23.255 Broadcast Address
    4. 
        * 192.168.24.0 Net Address
        * 192.168.31.255 Broadcast Address
    5. To get any further addresses:
        * Net = xxx.xxx.(previous + 8).0
        * Broadcast = xxx.xxx.(net + 7).255



[Return](https://stewartnz.github.io/NET603-Blogs/)