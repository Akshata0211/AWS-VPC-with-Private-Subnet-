# AWS VPC with Private Subnet Deployment
This project demonstrates how to securely deploy an application in a private subnet using AWS services such as VPC, Bastion Host, Load Balancer, Auto Scaling Group, and NAT Gateway.

To improve resiliency and availability, servers are deployed in two Availability Zones using an Auto Scaling group and an Application Load Balancer (ALB). The servers receive requests through the load balancer and can connect to the internet via a NAT gateway deployed in both Availability Zones.
