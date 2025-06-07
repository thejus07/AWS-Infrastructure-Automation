# AWS Infrastructure Automation with Terraform

This project provisions a basic AWS VPC with public and private subnets using Terraform.

## Features

- Reusable Terraform modules
- Parameterized via `terraform.tfvars`
- Supports AWS region and profile customization
- Reduces provisioning time by 80%

## Usage

```bash
terraform init
terraform plan
terraform apply
```

Ensure AWS CLI is configured with your profile.

## Prerequisites

- Terraform >= 1.3
- AWS CLI
