# DataCenter Enviroment 1

To use this module Please go to (https://github.com/waleedrady/AWS_Cloud_DC_Enviroment_1A)

Terraform Module that will create the AWS Networking Stack with FGT, Apache Server, Windows Server and utilize AWS Route53 for DNS. 

The module will create the below resources:

- Networking Stack (VPC, Subnets, Route Tables, Security Groups and Internet Gateway) - Please refer to the diagram below. 
- FortiGate with 3 interfaces (Two Interfaces in two different Public Subnets and one in the Private subnets)
- Windows Server 2019 Behind the FGT Port 3 [LAN]
- Ubunutu Server with Apache installed on it behind the FGT port 3 [LAN]
- Route53 DNS Public Hosted Zones


// The DNS Hosted Zones must be sub-zones for a domain that is registered or managed by AWS Route53 //

// i.e xyz.com is the domain name and you will create the subzone Lab1.xyz.com // 


![image](https://user-images.githubusercontent.com/83562796/117002411-87a72880-acb1-11eb-911c-6f48d8bfaf74.png)
