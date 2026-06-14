# AWS VPC Networking Lab 🚀

## Project Overview

This repository contains my hands-on practice of AWS networking concepts. I created a custom Virtual Private Cloud (VPC) from scratch and configured its components to understand how AWS networking works.

## Services and Concepts Practiced

* Amazon VPC
* Subnets
* Internet Gateway (IGW)
* Route Tables
* Security Groups
* Amazon EC2

## Tasks Performed

### 1. Created a Custom VPC

* Created a new VPC with a custom CIDR block.
* Learned how a VPC provides an isolated network environment in AWS.

### 2. Created Subnets

* Created subnets inside the VPC.
* Understood how subnets divide the VPC into smaller networks.

### 3. Attached an Internet Gateway

* Created and attached an Internet Gateway to the VPC.
* Learned that an IGW enables communication between resources in the VPC and the internet.

### 4. Configured Route Tables

* Added routes to direct internet traffic through the Internet Gateway.
* Associated the route table with the subnet.

### 5. Launched an EC2 Instance

* Launched an EC2 instance inside the subnet.
* Configured security settings for connectivity.

### 6. Verified Internet Connectivity

* Connected to the EC2 instance.
* Executed:

```bash
ping google.com
```

* Successfully received replies, confirming that the instance had internet access.

## Learning Outcomes

Through this hands-on lab, I understood:

* How VPC components work together.
* The relationship between VPC, Subnets, Internet Gateway, and Route Tables.
* How internet connectivity is established for an EC2 instance.
* The importance of proper network configuration in AWS.

## Repository Contents

* Step-by-step screenshots of the complete setup process.
* Documentation of the AWS networking lab.
* Notes and observations from practical implementation.


