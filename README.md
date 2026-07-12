
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

<img width="1908" height="825" alt="Screenshot 2026-07-12 193429" src="https://github.com/user-attachments/assets/3c7a8cf6-2939-4063-83b6-28025c8201e2" />
<img width="1355" height="1022" alt="Screenshot 2026-07-12 193530" src="https://github.com/user-attachments/assets/a234c213-1efa-4cdd-8f2f-deaf5dfca34b" />
<img width="1391" height="835" alt="Screenshot 2026-07-12 193649" src="https://github.com/user-attachments/assets/4a73ba15-eeeb-426e-ac90-0d0a046f9d8d" />
<img width="1378" height="941" alt="Screenshot 2026-07-12 193700" src="https://github.com/user-attachments/assets/23744486-c981-4e00-92aa-15b391e9a288" />


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
