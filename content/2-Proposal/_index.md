---
title: "Proposal"
date: "2025-11-11"
weight: 2
chapter: false
pre: " <b> 2. </b> "
---


# CloudRead – Online Ebook Reading Platform  
## A Java + AWS–based Solution for Online Reading and Ebook Management  

### 1. Executive Summary  
**CloudRead** is an academic project developed by a team of five Information Technology students, aiming to build an online platform for reading and managing digital books (ebooks) on **Amazon Web Services (AWS)**.  
Users can register accounts, search for books, and read ebooks directly through an integrated PDF viewer, while also receiving notifications and password recovery emails via **Amazon Simple Email Service (SES)**.  
The system is developed using **Spring Boot (Java 17)** for the backend and **HTML/CSS/JavaScript (Vanilla JS)** for the frontend, fully deployed across **AWS services** including **EC2, RDS, S3, CloudFront, SES, IAM, CloudWatch, and CodePipeline**.  
The project’s objective is to create a stable, scalable, secure, and low-cost academic platform for online ebook reading.  

---

### 2. Problem Statement  

*Current Issue*  
Most free ebook websites such as **nhasachmienphi.com** only allow users to download or view content online, lacking essential features such as user role management, reading statistics, or content evaluation.  
Commercial ebook platforms, on the other hand, require high costs and complex configurations, making them unsuitable for small-scale student projects.  

*Proposed Solution*  
CloudRead is designed as an educational and demonstrative platform that enables:  
- Ebook storage and distribution via **Amazon S3 + CloudFront (Signed URL)**.  
- User, book, and review management through **Amazon RDS MySQL**.  
- Backend hosting directly on **Amazon EC2 (Spring Boot)**.  
- Static frontend hosting through **S3 + CloudFront**.  
- Email verification and support via **Amazon SES (SMTP)**.  
- Automated build and deployment using **AWS CodePipeline → CodeBuild → CodeDeploy**.  
- System monitoring, logging, and cost tracking via **Amazon CloudWatch**.  

*Benefits & ROI*  
- Provides practical hands-on experience with real AWS cloud deployment.  
- Operates 24/7 with minimal cost and optimized resource usage.  
- Strengthens technical skills in distributed systems, security, and DevOps practices.  
- Can be expanded in the future with additional learning and sharing features.  

---

### 3. Solution Architecture  

CloudRead follows a **three-tier architecture integrated with AWS services**.  
Users access the platform through **Route 53**, with static content delivered by **CloudFront** from **S3 (Frontend Bucket)**.  
When users log in, search, or open an ebook, requests are handled by **EC2 (Spring Boot Backend)**, which retrieves data from **RDS MySQL** hosted in a private subnet and fetches ebook files from **S3 (Private Bucket)**.  
Email notifications and support messages are sent via **Amazon SES**.  
The backend source code is built and deployed automatically using **CodePipeline → CodeBuild → CodeDeploy**, and all logs and metrics are tracked through **CloudWatch**.  

*Key AWS Services:*  
- **Amazon EC2** – Runs the Spring Boot backend.  
- **Amazon RDS (MySQL)** – Stores user, book, and review data.  
- **Amazon S3 + CloudFront** – Hosts and distributes web assets and ebook files.  
- **Amazon SES** – Sends user notification and support emails.  
- **Amazon IAM** – Manages access permissions between EC2, S3, and SES.  
- **Amazon CodePipeline / CodeBuild / CodeDeploy** – Automates CI/CD workflow.  
- **Amazon CloudWatch** – Monitors logs, performance, and billing alerts.  

---

### 4. Technical Implementation  

*Implementation Stages*  
1. **Local Development (1–2 weeks):** Design the MySQL database, develop backend APIs, and build the HTML/JS interface with PDF.js.  
2. **AWS Configuration (2 weeks):** Set up EC2, RDS, S3, CloudFront, SES, and IAM roles with secure subnet configuration.  
3. **CI/CD Integration (1 week):** Configure CodePipeline, CodeBuild, and CodeDeploy for automated build and deployment.  
4. **Testing & Demo (1 week):** Validate all features including login, reading, reviewing, and email functions.  

*Technical Requirements*  
- Java 17 + Spring Boot  
- MySQL (local → RDS)  
- HTML/CSS/JavaScript (Vanilla JS + PDF.js)  
- AWS SDK for Java (S3 + SES integration)  
- GitHub with AWS CodePipeline/CodeBuild/CodeDeploy  
- Postman and CloudWatch for testing and monitoring  

---

### 5. Timeline & Milestones  

- **January:** Database design, backend API development, and basic UI.  
- **February:** Configure AWS RDS, S3, CloudFront, and SES.  
- **March:** Integrate CI/CD, perform system testing, and demonstrate CloudRead.  

---

### 6. Estimated Budget  

The estimated monthly operating cost for **CloudRead** running continuously is **USD 15–17**, including EC2 (~6.5), RDS (~7), S3 + CloudFront (~0.7), SES (~0.15), CI/CD (~1), and CloudWatch (~0.1).  
By leveraging **AWS Free Tier** and **AWS Student Credits ($100)**, the actual cost during the initial phase can be nearly **zero**.  

---

### 7. Risk Assessment  

Main risks include AWS connectivity issues, data exposure, and exceeding Free Tier limits.  
Mitigation strategies include configuring **private S3 buckets with Signed URLs**, setting **Billing Alarms**, verifying SES domain to ensure stable email delivery, and creating periodic **EC2 and RDS snapshots**.  
If CI/CD deployment fails, manual rollback will be used to restore a stable version.  

*Backup Plans:*  
- Maintain a local version for offline demo purposes.  
- Regularly monitor logs and system performance via CloudWatch.  
- Control monthly spending through AWS billing alerts.  

---

### 8. Expected Outcomes  

Upon completion, **CloudRead** will be a fully functional online ebook reading and management platform deployed on AWS.  
The project will equip the team with strong full-stack and DevOps experience, covering system design, cloud deployment, and cost optimization.  
In the future, CloudRead can be expanded with community-based features, book recommendations, device synchronization, and user authentication through **Amazon Cognito**.  

---
