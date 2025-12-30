# Project 06 – EC2 to RDS MySQL (AWS)

## 📌 Overview
This project demonstrates secure connectivity between an Amazon EC2 instance and an Amazon RDS MySQL database using private networking within the same VPC.

## 🏗 Architecture
- EC2 instance (Amazon Linux)
- RDS MySQL (Private access)
- Same VPC & Subnets
- Security Group to Security Group communication

## 🔐 Security Configuration
- SSH (22) restricted to user IP
- MySQL (3306) allowed only from EC2 Security Group
- RDS not publicly accessible

## ⚠️ Errors Faced & Resolved
- Unknown MySQL server host (DNS issues)
- MySQL connection timeout (Security Group misconfiguration)
- MySQL client installation issues
- Password input confusion (CLI hides input)

## ✅ Final Outcome
- Successfully connected EC2 to RDS MySQL
- Verified using MySQL CLI
- Secure and production-style setup

## 📷 Screenshots
See `/screenshots` folder.

## 🧠 Skills Gained
AWS EC2, RDS, VPC, Security Groups, MySQL, Cloud Troubleshooting

