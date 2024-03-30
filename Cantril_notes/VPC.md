## IP Addressing Primer 

[https://youtu.be/g2JOHLHh4rI?si=wfHnQAAbBA3HIrfB&t=164]

![1707787448018](image/VPC/1707787448018.png)

![1707787546015](image/VPC/1707787546015.png)

![1707787636010](image/VPC/1707787636010.png)

![1707787682655](image/VPC/1707787682655.png)

![1707788058110](image/VPC/1707788058110.png)

![1707792675657](image/VPC/1707792675657.png)

- 255.0.0.0 means /8 = 32-8 = 2^24 = 16777216 (But we are not allowed 2 IP addresses hence) = 16777214
- 255.255.0.0 means /16 = 32-16 = 2^16 = 65536 (But we are not allowed 2 IP addresses hence) = 65534
- 255.255.255.0 means /24  = 32-24 = 2^8 = 256 (But we are not allowed 2 IP addresses hence) = 254

![1707792743481](image/VPC/1707792743481.png)

![1707792906433](image/VPC/1707792906433.png)

## Default VPC

[https://learn.cantrill.io/courses/1820301/lectures/41301619]

![1707044214865](image/VPC/1707044214865.png)

**Note - We can have only 1 Default VPC per region**

![1707044506599](image/VPC/1707044506599.png)

## Custom VPCs

![1707044877892](image/VPC/1707044877892.png)

*Custom VPCs are by default private*

Default VPC has CIDR value of 172.31.0.0/16

## Default VPC Setup (in a region)

![1707045174028](image/VPC/1707045174028.png)

**The Highter the /x number is, the smaller the network is**

## Default VPC Facts

![1707145285542](image/VPC/1707145285542.png)

## Default VPC Setup (Handson)

[https://learn.cantrill.io/courses/1820301/lectures/41301619]










