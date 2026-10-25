# AWS CloudFormation – EC2 Infrastructure Deployment

## Overview
This project demonstrates my hands-on learning of AWS CloudFormation and Infrastructure as Code (IaC) using YAML templates.

The objective was to provision AWS resources through a template and practise updating an existing infrastructure stack.

## AWS Services Used
- AWS CloudFormation
- Amazon EC2
- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Groups
- Amazon S3

## Project Features
- Created a VPC with a public subnet.
- Configured an Internet Gateway and routing.
- Defined security group rules for HTTP and SSH.
- Provisioned an EC2 instance using CloudFormation.
- Used EC2 UserData to install and start Apache HTTP Server.
- Created an S3 bucket.
- Configured stack outputs for the EC2 instance ID, public IP, website URL, and S3 bucket name.
- Updated the YAML template to practise infrastructure changes.

## Repository Structure

```text
templates/
├── full-ec2-v2.yaml
└── update-ec2-stack.yaml
```

## Key Learnings
- Understanding Infrastructure as Code.
- Writing AWS CloudFormation templates in YAML.
- Defining AWS resources and their dependencies.
- Configuring networking resources for an EC2 instance.
- Using intrinsic functions such as `!Ref`, `!GetAtt`, `!Select`, and `!Sub`.
- Practising CloudFormation stack updates.

## Disclaimer
This project was created for educational purposes. Review security group rules, AWS resource availability, and deployment costs before deploying the templates.

## Author
Manish Yadav
