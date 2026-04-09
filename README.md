# Terraform AWS Web Application Deployment

## 📌 Project Overview

This project provisions a complete AWS infrastructure using Terraform.

Infrastructure includes:

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Instance
- Nginx Web Server

The EC2 instance automatically installs Nginx using a user_data script and serves a web page.

---

## 🧰 Technologies Used

- Terraform
- AWS EC2
- AWS VPC
- AWS Networking
- Linux
- Nginx

---

## 🏗️ Architecture

Terraform → AWS Infrastructure → EC2 → Nginx Web Server

---

## 🚀 Features

- Infrastructure as Code (IaC)
- Automated EC2 provisioning
- Automated Nginx installation
- Public web server deployment

---

## 📷 Output

Access web server:

http://<EC2_PUBLIC_IP>

Displays:

Welcome from Terraform EC2

---

## 🧹 Cleanup

To destroy infrastructure:

terraform destroy
