# vpc-peering-ec2-ping

Project: VPC Peering with Security Group Configuration &  EC2 Ping each other



Objective:To create VPC peering connection and configure everything from security group,route table, subnets and create two EC2 that will be able to communicate with each other.



-I logged into my AWS management console.



-Navigated to the VPC services




-Clicked on create VPC tagged





-I clicked on create





-I proceeded to the create the internet gateway by clicking create





-I then attached the internet gateway to the created vpc.





-I proceeded to create subnet.





-I clicked on create.




-I then repeated the process for the creation of a public subnet for each of the VPCs




-For the subnets they were linked to the vpc we created.





-The subnets are located in the same Region.





-I now went ahead to edit  route  tables .




- I now went ahead to launch two EC2 instances and configured all required





-The EC2 were launched on Amazon Linux AMI




-I went ahead to create VPC peering with A been the requester and B been the accepter.




-The ping request was made at first instance but it did not work.




-I went to the security groups to update inbound rules to allow Custom ICMP-ipv4 on both.



-I proceeded to make ping request on EC2 A with the private ip address from EC2 B.


-The ping request was successful.



-This process was repeated again with a ping request from EC2 B using private ip address form EC2 A
The project gave me an insight into the VPC peering configuration and security group configuration. Also the fact that I was able to make two EC2 to communicate with themselves.



In the process of carrying out this project there were places I got stuck but with the help of the team and the internet, I was able to scale through.

