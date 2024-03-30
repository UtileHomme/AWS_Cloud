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

## Default VPC Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/13528538#overview]

![1707044214865](image/VPC/1707044214865.png)

**Note - We can have only 1 Default VPC per region**

![1707044506599](image/VPC/1707044506599.png)

![1708393978121](image/VPC/1708393978121.png)

![1708393995346](image/VPC/1708393995346.png)

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

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874472#overview]

## Subnets Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874484#overview]

![1709555323887](image/IAM/1709555323887.png)

## Internet Gateway and Route Tables Handson

[https://udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874492#overview]

## Bastion Host Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874510#overview]

## Nat Instance Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874518#overview]

## Nat Gateway Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874522#overview]

## Security Groups and NACL Handson

[https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874530#overview]

## VPC Peering Handson

https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/learn/lecture/28874554#overview]
