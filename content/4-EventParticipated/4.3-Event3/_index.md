---
title: "Event Participation – AWS Well-Architected Security Pillar Workshop"
date: "2025-11-29"
weight: 3
chapter: false
pre: "<b>3.</b>"
---

## Event 3 – AWS WELL-ARCHITECTED SECURITY PILLAR WORKSHOP

## Event Information
**Date & Time:** Saturday, November 29, 2025, 8:30 AM – 12:00 PM  
**Location:** AWS Vietnam Office  
**Role:** Attendee  

---

## Event Purpose
This morning workshop provided a comprehensive deep-dive into the AWS Well-Architected Security Pillar, covering all five security domains:

- Identity & Access Management  
- Detection  
- Infrastructure Protection  
- Data Protection  
- Incident Response  

The session was designed to equip participants with practical knowledge on implementing security best practices in AWS environments, including real-world examples from Vietnamese enterprises.

---

# Agenda Overview

## **8:30 – 8:50 AM | Opening & Security Foundation**
### Security Pillar in Well-Architected Framework
- Role of the Security Pillar  
- Core principles:  
  - Least Privilege  
  - Zero Trust  
  - Defense in Depth  
- AWS Shared Responsibility Model  
- Top cloud security threats in Vietnam  

---

# Pillar 1 — Identity & Access Management  
## **8:50 – 9:30 AM | Modern IAM Architecture**
- IAM fundamentals: Users, Roles, Policies — avoid long-term credentials  
- IAM Identity Center: SSO, permission sets  
- SCP & Permission Boundaries for multi-account setups  
- MFA, credential rotation, Access Analyzer  
- **Mini Demo:** Validate IAM Policy + simulate access  

---

# Pillar 2 — Detection  
## **9:30 – 9:55 AM | Detection & Continuous Monitoring**
- CloudTrail (organization-level)  
- GuardDuty  
- Security Hub  
- Logging layers: VPC Flow Logs, ALB logs, S3 logs  
- Automated alerting with EventBridge  
- Detection-as-Code (IaC + rules)  

---

## **9:55 – 10:10 AM | Coffee Break**

---

# Pillar 3 — Infrastructure Protection  
## **10:10 – 10:40 AM | Network & Workload Security**
- VPC segmentation, private vs public placement  
- Security Groups vs NACLs  
- WAF + Shield + Network Firewall  
- Workload security for EC2, ECS/EKS  

---

# Pillar 4 — Data Protection  
## **10:40 – 11:10 AM | Encryption, Keys & Secrets**
- KMS key policies, grants, rotation  
- Encryption at-rest & in-transit for S3, EBS, RDS, DynamoDB  
- Secrets Manager & Parameter Store — rotation patterns  
- Data classification & access guardrails  

---

# Pillar 5 — Incident Response  
## **11:10 – 11:40 AM | IR Playbook & Automation**
### IR Lifecycle (AWS Framework)
### Playbooks:
- Compromised IAM key  
- S3 public exposure  
- EC2 malware detection  
- Snapshot, isolation, evidence collection  
- Automated response using Lambda / Step Functions  

---

## **11:40 – 12:00 PM | Wrap-Up & Q&A**
- Summary of 5 pillars  
- Common pitfalls & real-world practices in Vietnam  
- Security learning roadmap (Security Specialty, SA Pro)  

---

# Key Learnings
- Least Privilege is fundamental — always start minimally  
- Zero Trust: no implicit trust, even internal  
- Defense in Depth requires multilayer protection  
- Detection must be automated & continuous  
- IR playbooks must be documented & tested frequently  

---

# Application to My Work
- Implement IAM Access Analyzer  
- Enable GuardDuty & Security Hub for centralized monitoring  
- Create IR playbooks for common incidents  
- Review & restrict Security Group rules  
- Enable encryption across all data stores (S3, RDS, DynamoDB)  

---

# Personal Experience
This workshop provided strong practical insights:

- Demos made abstract security concepts easy to understand  
- Local enterprise security pitfalls were eye-opening  
- IR playbooks were highly actionable  
- Understanding all five pillars helped clarify holistic cloud security  

---

# Takeaways
- Security is continuous, not a destination  
- Automation is crucial for security at scale  
- The Security Pillar is a complete framework for cloud protection  
- Regular reviews and improvements are essential  
- AWS provides strong native tools for every security domain  

---

# Event Photos

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/10.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/11.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/12.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/13.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/14.png)

