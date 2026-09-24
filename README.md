**OVERVIEW**

This project demonstrates how to use Terraform to automate the deployment and security configuration of an Amazon S3 bucket.

The bucket is configured with Versioning, Server-Side Encryption, Block Public Access, and Lifecycle Management to improve data protection and automate storage management.

**TECHNOLOGIES USED**

AWS S3

Terraform

Infrastructure as Code (IaC)

**FEATURES**

->Automated S3 bucket creation using Terraform

->Enabled S3 Versioning

->Enabled Server-Side Encryption (SSE-S3)

->Blocked public access

->Configured Lifecycle Rules

->Automated infrastructure deployment using Terraform

**PROJECT STRUCTURE**

AWS_Terraform2/


├── providers.tf

├── main.tf

├── output.tf

└── README.md

**DEPLOYMENT**

1. Initialize Terraform
terraform init

2. Validate the configuration
terraform validate

3. Review the deployment plan
terraform plan

4. Deploy the S3 bucket
terraform apply

Enter:
Yes

**SECURITY CONFIGURATION**

**S3 Versioning**

Versioning is enabled to keep previous versions of objects and help protect against accidental changes or deletion.

**Server-Side Encryption**

SSE-S3 encryption is enabled to protect data stored in the bucket.

**Block Public Access**

All public access settings are enabled to prevent unintended public access to the bucket.

**Lifecycle Management**

A lifecycle rule is configured to automatically expire objects after 30 days.

**CLEANUP**

To delete the resources after practice:

terraform destroy

Type:

yes

**KEY LEARNING**

This project helped me understand Terraform, AWS S3 security, Versioning, Encryption, Block Public Access, and Lifecycle Rules using Infrastructure as Code.
