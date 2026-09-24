# Terraform-Based-Secure-Amazon-S3-Bucket-Management
Project Overview

This project uses Terraform to create and manage a secure Amazon S3 bucket automatically.

The project focuses on improving S3 security using Versioning, Server-Side Encryption, Block Public Access, and Lifecycle Rules.

Technologies Used
AWS S3
Terraform
AWS CLI / AWS Console
Infrastructure as Code (IaC)
Features
Created an Amazon S3 bucket using Terraform
Enabled S3 Versioning
Enabled Server-Side Encryption (SSE-S3)
Blocked public access
Configured Lifecycle Rules
Used Terraform to automate infrastructure deployment
Project Structure
s3-project/
│
├── providers.tf
├── main.tf
└── output.tf
File Description
providers.tf – Configures the AWS provider and region
main.tf – Creates and configures the S3 bucket
output.tf – Displays the S3 bucket name
