# Terraform AWS VPC

## Description
AWS cloud infrastructure deployed with Terraform as Infrastructure as Code (IaC).

## Resources Created
- VPC with CIDR 10.0.0.0/16
- Public Subnet
- Internet Gateway
- Route Table
- Security Group (SSH + HTTP)
- EC2 Instance (Amazon Linux 2)

## Technologies
- Terraform 1.5.7
- AWS CLI
- AWS EC2, VPC, IAM

## How to Use
1. Clone this repository
2. Configure AWS credentials with aws configure
3. Run terraform init
4. Run terraform plan
5. Run terraform apply

## Author
Manuel Alejandro Velez
Cloud Engineer in training
AWS Certified Cloud Practitioner
