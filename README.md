# 🚀 3-Tier WordPress Architecture on AWS

## 📌 Project Overview
This project demonstrates the design and deployment of a **highly available and scalable 3-tier WordPress architecture** on AWS using industry best practices.

The architecture separates the application into three layers:
- Presentation Layer (Web Tier)
- Application Layer
- Database Layer

---

## 🏗️ Architecture Design

### 🔹 Web Tier
- Amazon EC2 instances
- Application Load Balancer (ALB)
- Auto Scaling Group for high availability

### 🔹 Application Tier
- WordPress (PHP-based application)
- Hosted on EC2 instances

### 🔹 Database Tier
- Amazon RDS (MySQL)
- Deployed in a private subnet for security

---

## 🧰 AWS Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group
- Amazon RDS (MySQL)
- Amazon VPC
- Public and Private Subnets
- Internet Gateway & NAT Gateway
- Security Groups

---

## 🌐 Key Features
- High Availability across multiple Availability Zones
- Load balancing for traffic distribution
- Auto Scaling for fault tolerance
- Secure database layer (private subnet)
- Scalable and production-ready architecture

---

## 🧩 Architecture Diagram

![architecture-diagram png](https://github.com/user-attachments/assets/037fe002-92b5-4d65-ad05-d30bff98c21c)


## 📸 Screenshots
<img width="1919" height="904" alt="ALB-setup" src="https://github.com/user-attachments/assets/6a1b8b18-8191-4943-baa9-204718e4acd3" />

### 🔹 RDS Database

<img width="1910" height="917" alt="DB-setup" src="https://github.com/user-attachments/assets/f7e779f2-e4de-4e25-a1e6-bdb4efee16d4" />


### 🔹 WordPress Application
<img width="1917" height="978" alt="wordpress png" src="https://github.com/user-attachments/assets/7f06e338-49f1-44fb-8eca-05bd8492a312" />


---

## 🚧 Challenges Faced
- Connecting EC2 instances to RDS in a private subnet
- Misconfigured security group rules
- Database connection issues in WordPress
- Understanding subnet and networking setup

---

## ✅ Solutions
- Fixed inbound/outbound rules
- Correct subnet setup
