# 🚀 3-Tier WordPress Architecture on AWS

## 📌 Project Overview
This project demonstrates how I designed and deployed a highly available 3-tier WordPress architecture on AWS.

## 🏗️ Architecture
- Web Tier: EC2 + Application Load Balancer
- App Tier: WordPress (PHP)
- Database Tier: Amazon RDS (MySQL)

## ⚙️ AWS Services Used
- EC2
- ALB
- Auto Scaling Group
- RDS
- VPC
- Security Groups

## 🧩 Architecture Diagram
![architecture-diagram png](https://github.com/user-attachments/assets/224182c7-f3ab-46de-b5b2-b56b95a1a0db)


## 📸 Screenshots

<img width="1919" height="904" alt="ALB-setup" src="https://github.com/user-attachments/assets/0d3fde13-a825-4e45-9279-4fa69f57691d" />


## 🚧 Challenges
- Connecting EC2 to RDS
- Security group configuration

## ✅ Solutions
- Fixed inbound/outbound rules
- Correct subnet setup
