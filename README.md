# AWS S3 Static Website Hosting with Terraform

## Overview

This project demonstrates how to provision an **Amazon S3 bucket** and host a **static website** using **Terraform**. The infrastructure is defined as code, making it easy to create, manage, and reproduce the environment.

## Features

* Create an Amazon S3 bucket using Terraform
* Configure the bucket for static website hosting
* Upload `index.html` and `error.html`
* Configure bucket ownership controls
* Configure public access settings for website hosting
* Apply a public-read ACL (for learning purposes)
* Deploy infrastructure using Infrastructure as Code (IaC)

## Technologies Used

* Terraform
* Amazon Web Services (AWS)
* Amazon S3
* AWS IAM
* HTML
* Git & GitHub

## Project Structure

```text
.
├── main.tf
├── provider.tf
├── variables.tf
├── terraform.tfvars
├── index.html
├── error.html
└── README.md
```

## Prerequisites

* AWS Account
* IAM User with appropriate permissions
* AWS CLI configured
* Terraform installed
* Git installed

## Deployment

Initialize Terraform:

```bash
terraform init
```

Review the execution plan:

```bash
terraform plan
```

Deploy the infrastructure:

```bash
terraform apply -auto-approve
```

Destroy the infrastructure when no longer needed:

```bash
terraform destroy
```

## Learning Outcomes

Through this project, I learned:

* Infrastructure as Code (IaC) using Terraform
* AWS S3 bucket provisioning
* Static website hosting on Amazon S3
* IAM authentication for Terraform
* Terraform state management
* Git and GitHub version control

## Future Improvements

* Use remote Terraform state with S3
* Add DynamoDB state locking
* Configure a custom domain using Route 53
* Secure the website with CloudFront and HTTPS
* Automate deployment using GitHub Actions

## Author

**Dilli Prathap**

Aspiring Cloud & DevOps Engineer

---

*This project was created as part of my hands-on learning journey in AWS Cloud and Terraform.*
