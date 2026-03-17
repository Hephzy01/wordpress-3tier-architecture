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
![Diagram](diagrams/architecture-diagram.png)

## 📸 Screenshots
![ALB](screenshots/alb.png)

## 🚧 Challenges
- Connecting EC2 to RDS
- Security group configuration

## ✅ Solutions
- Fixed inbound/outbound rules
- Correct subnet setup