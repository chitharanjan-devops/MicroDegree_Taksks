## Create a VPC

1. Go to VPC → Create VPC → Name: "MyVPC" → CIDR: 10.0.0.0/16.

## Create Subnets

Public Subnet: 10.0.1.0/24 (Enable auto-assign public IP).

Private Subnet: 10.0.2.0/24.

## Attach Internet Gateway

Create an Internet Gateway (IGW) and attach it to MyVPC.

## Configure NAT Gateway

Create NAT Gateway in Public Subnet.
Update Private Subnet's Route Table to use the NAT Gateway.