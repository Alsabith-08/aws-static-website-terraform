
# AWS Static Website Hosting with Terraform

A hands-on cloud computing project that defines static website hosting infrastructure on Amazon S3 using Terraform.

## Project Goals

- Build a responsive portfolio website using HTML and CSS.
- Define AWS infrastructure as code using Terraform.
- Configure an S3 bucket for static website hosting.
- Automate uploading website files to S3.
- Practice infrastructure validation and Git version control.

## Architecture

```text
Developer
   |
   v
HTML and CSS Website
   |
   v
Terraform Configuration
   |
   v
AWS Provider
   |
   v
Amazon S3 Website Hosting
```

## Technologies

- HTML5
- CSS3
- Terraform
- AWS Provider for Terraform
- Amazon S3
- Git and GitHub

## Project Structure

```text
aws-static-website-terraform/
├── website/
│   ├── index.html
│   └── error.html
├── main.tf
├── variables.tf
├── outputs.tf
├── versions.tf
├── .gitignore
└── README.md
```

## Current Status

- [x] Portfolio website created
- [x] Terraform configuration written
- [x] Terraform initialized
- [x] Terraform validation passed
- [ ] AWS deployment
- [ ] Public website URL and testing

**Deployment status:** Not deployed. No AWS resources have been created as part of this project so far.

## Local Validation

Run these commands from the project directory:

```powershell
terraform fmt
terraform init
terraform validate
```

## Cost and Security Notes

- Local development and Terraform validation do not require an AWS account.
- AWS deployment may incur charges.
- Never commit AWS credentials, Terraform state files, or secret values.
- Review S3 public-access settings and AWS costs before any deployment.
- For production websites, consider private S3 storage behind CloudFront with HTTPS.

## Learning Outcomes

This project demonstrates introductory skills in infrastructure as code, cloud storage concepts, configuration validation, and project documentation.
