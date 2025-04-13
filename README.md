# aws-terraform-web-host
static website hosting of  portfolio publicly on an AWS S3 bucket, by using Terraform
# ☁️ AWS S3 Static Website Hosting with Terraform

This project sets up a **personal portfolio website** using **AWS S3** as a static web host. Infrastructure is managed using **Terraform**, allowing automated, repeatable, and scalable deployments.

---

## 📌 Project Overview

- 🎯 **Goal**: Host a portfolio site (HTML/CSS) publicly on AWS S3
- 🛠️ **Tools Used**:
  - **Terraform** for Infrastructure as Code (IaC)
  - **AWS S3** for static website hosting
  - Optional: Route 53 or CloudFront for domain/CDN (not included here)

---

## 📁 Project Structure

```bash
aws-portfolio-s3/
├── main.tf              # Terraform config for S3
├── variables.tf         # Input variables
├── outputs.tf           # Output values (e.g., website URL)
├── index.html           # Portfolio homepage
└── README.md            # Project documentation
