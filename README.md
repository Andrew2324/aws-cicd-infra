# aws-cicd-infra — GitHub Actions CI/CD for CloudFormation

This repo demonstrates a production-style CI/CD workflow that validates and deploys AWS infrastructure using **CloudFormation** and **GitHub Actions**.

## What this builds (per environment)
- VPC (10.20.0.0/16)
- 1 Public Subnet (10.20.1.0/24)
- Internet Gateway + Route Table
- Security Group (optional SSH)
- EC2 (t3.micro) running NGINX
- IAM Role for EC2 Systems Manager (SSM) access

## Repo Structure
