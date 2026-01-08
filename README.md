# AWS VPC Endpoint (S3 Gateway Endpoint) – Hands-on Project

## 📌 Project Overview
This project demonstrates a hands-on implementation of an **AWS VPC Endpoint (Gateway Endpoint for Amazon S3)**.  
The goal is to securely access AWS services **without using the public internet, NAT Gateway, or Internet Gateway**, keeping traffic within the AWS private network.
![Architecture](https://github.com/vipul132/AWS-VPC-ENDPOINT-Hands-on/blob/master/Create-VPC-Endpoint.png)

---

## 🎯 Objectives
- Understand what a VPC Endpoint is
- Learn the difference between Gateway and Interface Endpoints
- Access S3 privately from an EC2 instance
- Improve AWS network security and cost efficiency

---

## 🏗️ Architecture Overview
- Custom VPC
- Subnet
- Route Table
- Internet Gateway
- EC2 Instance
- S3 Bucket
- VPC Gateway Endpoint (S3)

---

## 🛠️ Steps Performed

### 🔹 Network Setup
1. Created a **custom VPC**
2. Created **subnet** inside the VPC
3. Configured **Internet Gateway**
4. Created and associated **Route Table**
5. Launched **EC2 instance** inside the VPC

### 🔹 Service Integration
6. Created **Amazon S3 bucket**
7. Created **VPC Gateway Endpoint for S3**
8. Updated route table to use the endpoint
9. Tested S3 access from EC2 **without internet connectivity**

---

## 🔐 Key Learnings
- Private AWS service access using VPC Endpoints
- Improved security by avoiding public internet exposure
- Cost savings by removing NAT Gateway dependency
- Real-world use cases for secure architectures

---

## 📊 VPC Endpoint Types

| Type | Services | Network |
|----|--------|--------|
| Gateway Endpoint | S3, DynamoDB | Route Table |
| Interface Endpoint | Most AWS Services | ENI with Private IP |

---

## 🎥 Video Walkthrough
👉 YouTube: https://youtu.be/pry-qwN1ADE

---

## 👨‍💻 Author
**Vipul Pandey**  
Cloud & Systems Engineer  
🌐 Website: www.vipulpandey.info  
🔗 LinkedIn: https://www.linkedin.com/in/vipul-pandey-1482b9162/

---

## ⭐ Support
If you find this project useful, please ⭐ the repository and feel free to fork it.

