# AWS Infrastructure
This directory contains the Terraform code to deploy infrastructure on AWS. It includes creating a VPC with public and private subnets, launching EC2 instances in the public and private subnets, EKS cluster.

## Overview
This directory uses Terraform to create the following AWS resources:

- VPC
- Internet Gateway.
- Public Route Table.
- Private Route Table.
- Public EC2 instance.
- Private EC2 instance.
- AWS IAM role for eks workers
- EKs cluster
- Security groups

## Prerequisites

- AWS account

## To get started:
Clone this repository to your local machine.
```
git clone https://github.com/AbdulrahmanElfeki/CICD-pipeline-maven-project
cd CICD-pipeline-maven-project/AWS Infrastructure
```
Run `terraform init` to download the necessary Terraform plugins.

Run `terraform plan` to preview the changes that Terraform plans to make to your infrastructure.

Run `terraform apply` to deploy your infrastructure.

