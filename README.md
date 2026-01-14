# Serverless Web Application AWS

## 📌 Project Overview
This project demonstrates a fully serverless web application built using AWS services. 
The frontend is hosted on Amazon S3, and user interactions are handled using API Gateway and AWS Lambda, with data stored in DynamoDB.

---

## 🛠️ AWS Services Used
- Amazon S3 (Static Website Hosting)
- AWS Lambda (Backend Logic)
- Amazon API Gateway (REST API)
- Amazon DynamoDB (NoSQL Database)
- Amazon CloudWatch (Monitoring & Logs)
- AWS IAM (Security & Permissions)

---

## 🔄 Architecture Flow
1. User interacts with a static website hosted on Amazon S3.
2. Button click triggers an API Gateway POST request.
3. API Gateway invokes an AWS Lambda function.
4. Lambda processes the request and stores data in DynamoDB.
5. CloudWatch monitors logs, invocations, duration, and errors.

---

## 🚀 Key Features
- Fully serverless architecture (no EC2 used)
- Scalable and highly available
- Real-time event handling using AWS Lambda
- Data persistence using DynamoDB
- Monitoring using CloudWatch metrics

---

## 📸 Project Screenshots
Screenshots demonstrating the working of the application and AWS services are included in the repository.

---

## 📚 Learning Outcome
- Hands-on experience with serverless architecture
- Practical understanding of AWS Lambda and API Gateway
- Monitoring and debugging using CloudWatch
- Secure IAM role configuration

---
