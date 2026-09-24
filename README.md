Project Overview

This project uses Terraform to create and manage a secure Amazon S3 bucket automatically.

Technologies Used
AWS S3
Terraform
Infrastructure as Code (IaC)
Features
Created an Amazon S3 bucket using Terraform
Enabled S3 Versioning
Enabled Server-Side Encryption (SSE-S3)
Blocked Public Access
Configured S3 Lifecycle Rules
Automated AWS infrastructure using Terraform
Project Structure
AWS_Terraform2/
├── providers.tf
├── main.tf
├── output.tf
└── README.md
How to Run
1. Initialize Terraform
terraform init
2. Validate the configuration
terraform validate
3. Preview the changes
terraform plan
4. Create the S3 bucket
terraform apply

Type:

yes
S3 Security
Versioning

Keeps previous versions of objects.

Server-Side Encryption

Protects stored data using SSE-S3 encryption.

Block Public Access

Prevents public access to the S3 bucket.

Lifecycle Rule

Automatically manages objects and expires them after 30 days.

AWS Console Verification

After deployment, verify:

S3 Bucket
Versioning — Enabled
Encryption — SSE-S3
Block Public Access — Enabled
Lifecycle Rule — Enabled
