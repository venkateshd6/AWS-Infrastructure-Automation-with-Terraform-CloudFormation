# AWS Infrastructure Automation with Terraform & CloudFormation
## Overview
Provisioned a complete 3-tier web architecture (Web, App, DB) using Terraform and AWS CloudFormation with automated infrastructure deployment.

## Tech Stack
- AWS (EC2, RDS, S3, VPC, ALB, IAM)
- Terraform
- CloudFormation (YAML/JSON)
- GitHub

## Architecture
- VPC with public/private subnets
- EC2 instances with ALB and Auto Scaling Group
- RDS MySQL in private subnet
- S3 for static assets
- IAM roles with least-privilege access

## Features
- Modular Terraform structure with remote state
- Automated provisioning using IaC
- CloudFormation templates for quick setup
- Cost-efficient design with tagging and lifecycle policies

## How to Run
1. Clone the repo
2. cd terraform/ and terraform init
3. Update terraform.tfvars and run terraform apply
4. Use CloudFormation template for DB layer

## Outcome
- Reduced setup time from 3 hours to 15 minutes
- Fully repeatable and version-controlled infrastructure
