# Blog - 01
> ## 23/02/2021 - 25/02/2021
### Introduction and Subnetting

I have previously studied CSA502, NET502 and OSA501 at NMIT.
I also have experience in calculating and converting Binary.

On thursday we learned about subnetting and how it effects subnet masks, the IP adress and broadcast address for that subnet.
The specific example we studied was having the subnets be 26 bits meaning the binary seperation is 11000000.10101000.00000001.00|000000 (192.168.1.0) where the last 6 bits are different IP addresses in the subnet except for when they are 000000 making them broadcast addresses. The subnet mask for 26 places would be 255.255.255.192

This configuration allows for 4 subnets each represented by:
- 00|000000 (xxx.xxx.x.0)
  - IP's range from 00|000001 (1) to 00|111111 (63)
- 01|000000 (xxx.xxx.x.64)
  - IP's range from 01|000001 (65) to 01|111111 (127)
- 10|000000 (xxx.xxx.x.128)
  - IP's range from 10|000001 (129) to 01|111111 (191)
- 11|000000 (xxx.xxx.x.192)
  - IP's range from 11|000001 (193) to 11|111111 (255)
