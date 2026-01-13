# 🚀 AWS VPC Network Creation using Terraform

This project demonstrates how to **create a complete AWS VPC networking setup using Terraform (Infrastructure as Code)**.  
It automates the provisioning of AWS networking components in a **reliable, repeatable, and scalable** way.

---

## 📌 Project Overview

In this project, Terraform is used to create AWS infrastructure instead of manual console work.  
Using Infrastructure as Code (IaC) helps in:
- Faster infrastructure provisioning
- Reduced human errors
- Easy version control with Git
- Reusability and scalability

---

## 🛠️ Technologies Used

- **Terraform** – Infrastructure as Code tool  
- **AWS (Amazon Web Services)**  
- **Git & GitHub** – Version control  
- **AWS CLI** – Authentication & access management  

---

## 🏗️ AWS Resources Created

The following resources are created using Terraform:

- ✅ VPC (Virtual Private Cloud)
- ✅ Public Subnet
- ✅ Internet Gateway
- ✅ Route Table & Route Table Association
- ✅ EC2 Instance (optional / if included)
- ✅ Security Groups (if configured)

---

## 📂 Project Structure

AWS-VPC-Creation-using-Terraform/<br>
│<br>
├── main.tf # Main Terraform configuration<br>
├── variables.tf # Input variables<br>
├── terraform.tfvars.example # Example variables file (no secrets)<br>
├── outputs.tf # Output values<br>
├── .gitignore # Ignored files (state & secrets)<br>
└── README.md # Project documentation<br>



---

## ⚙️ Prerequisites

Before running this project, make sure you have:

- AWS Account
- Terraform installed
- AWS CLI installed
- Git installed

Configure AWS credentials using:
```bash
aws configure
enter the all the key(first create the key in aws)

<h1>🚀 How to Use This Project</h1>

1️⃣ Initialize Terraform
terraform init
2️⃣ Validate Configuration
terraform validate
3️⃣ Preview the Execution Plan
terraform plan
4️⃣ Apply the Configuration
terraform apply
Type yes when prompted.




