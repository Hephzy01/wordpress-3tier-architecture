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
![architecture-diagram png](https://github.com/user-attachments/assets/0cd6521b-4fc8-403f-9c3d-59e6e58529ba)


---

## 📸 Project Screenshots

### 🔹 VPC
<img width="1897" height="906" alt="VPC-setup" src="https://github.com/user-attachments/assets/73c18dc7-5d79-4cca-b361-a6423681a635" />


### 🔹 Load Balancer Setup
<img width="1919" height="904" alt="ALB-setup" src="https://github.com/user-attachments/assets/b0b72660-b88d-4a99-9816-44485ed44a22" />


### 🔹 RDS Database
<img width="1910" height="917" alt="DB-setup" src="https://github.com/user-attachments/assets/12a06ec4-742d-4b1f-b463-5c87d39026da" />


### 🔹 WordPress Application
<img width="1917" height="978" alt="wordpress png" src="https://github.com/user-attachments/assets/c35a2841-ee34-4613-a681-01febc3feadb" />


---

## 🚧 Challenges Faced
- Connecting EC2 instances to RDS in a private subnet
- Misconfigured security group rules
- Database connection issues in WordPress
- Understanding subnet and networking setup

---

## ✅ Solutions Implemented
- Configured correct inbound/outbound rules in security groups
- Ensured proper subnet routing (public vs private)
- Updated WordPress configuration file (`wp-config.php`)
- Verified database connectivity and credentials

---

## 🔐 Security Best Practices
- RDS deployed in private subnet (not publicly accessible)
- Controlled access using security groups
- Least privilege access configuration
- Network isolation using VPC

---

## 📚 What I Learned
- Real-world cloud architecture design
- AWS networking (VPC, subnets, routing)
- High availability and fault tolerance
- Debugging cloud deployment issues
- Deploying scalable web applications

---

## 📌 Future Improvements
- Add HTTPS using AWS Certificate Manager (SSL)
- Implement CI/CD pipeline (GitHub Actions)
- Use Terraform for Infrastructure as Code (IaC)
- Add monitoring with CloudWatch

---

## 👨‍💻 Author
**Adeola Hephzibah Akinlade**

Cloud / DevOps Engineer (Aspiring)

---

## ⭐ If you found this helpful
Give this repo a star ⭐ and connect with me on LinkedIn!
