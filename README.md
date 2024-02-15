# VPC-in-Production-Environment

This project focuses on implementing a highly resilient and secure infrastructure on AWS using a Virtual Private Cloud (VPC) with servers deployed in private subnets. The key features include:

High Resiliency: Servers are deployed in two Availability Zones using an Auto Scaling group and an Application Load Balancer to enhance resiliency.
Security Measures: Servers are placed in private subnets to add an extra layer of security. Access to the servers is managed through an Application Load Balancer.
Internet Connectivity: Servers have internet access through a Network Address Translation (NAT) gateway deployed in both Availability Zones, allowing for outbound communication.
Bastion Host: A bastion host is deployed in a public subnet to securely manage and access the servers.
Web Server with Route 53: An Apache server is deployed and exposed to the internet using Route 53 for domain routing.
