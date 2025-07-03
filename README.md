# Terraform EC2 Instance (AWS - Mumbai)

This Terraform project provisions an EC2 instance on AWS in the `ap-south-1` (Mumbai) region.

## What it does:
- Launches a `t2.micro` EC2 instance
- Uses Amazon Linux 2 AMI
- Adds a tag: `Name = TerraformEC2`

## Files:
- `provider.tf` — configures AWS provider
- `main.tf` — defines the EC2 instance

## Commands used:
```bash
terraform init
terraform apply -auto-approve
terraform destroy
