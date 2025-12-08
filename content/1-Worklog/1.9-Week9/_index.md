---
title: "Week 9 Worklog"
date: "2025-11-09"
weight: 9
chapter: false
pre: "<b>1.9.</b>"
---


### Week 9 Objectives:

* Strengthen practical experience in automation, tagging, IAM, Lambda, and event-driven operations.
* Improve governance capabilities across multi-region workloads.
* Build end-to-end visibility and control through CloudTrail, Athena, and KMS integration.

---

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                   | Start Date | Completion Date |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 57  | - Lab22-2.1 – Create VPC <br> - Lab22-2.2 – Create Security Group <br> - Lab22-2.3 – Create EC2 Instance <br> - Lab22-2.4 – Incoming Webhooks Slack                                                                   | 03/11/2025 | 03/11/2025      |
| 58  | - Lab22-3 – Create Tag for Instance <br> - Lab22-4 – Create Role for Lambda <br> - Lab22-5.1 – Function Stop Instance <br> - Lab22-5.2 – Function Start Instance <br> - Lab22-6 – Check Result <br> - Lab22-7 – Cleanup | 04/11/2025 | 04/11/2025      |
| 59  | - Lab27-2.1.1 – Create EC2 Instance with Tag <br> - Lab27-2.1.2 – Managing Tags <br> - Lab27-2.1.3 – Filter Resources by Tag <br> - Lab27-2.2 – Using Tags with CLI <br> - Lab27-3 – Create Resource Group <br> - Lab27-4 – Cleanup | 05/11/2025 | 05/11/2025      |
| 60  | - Lab28-2.1 – Create IAM User <br> - Lab28-3 – Create IAM Policy <br> - Lab28-4 – Create IAM Role                                                                                                                      | 06/11/2025 | 06/11/2025      |
| 61  | - Lab28-5.1 – Switch Roles <br> - Lab28-5.2.1 – Access EC2 in Tokyo <br> - Lab28-5.2.2 – Access EC2 in North Virginia <br> - Lab28-5.2.3 – Create EC2 with missing/qualified tags <br> - Lab28-5.2.4 – Edit Resource Tag <br> - Lab28-5.2.5 – Policy Check <br> - Lab28-6 – Cleanup | 07/11/2025 | 07/11/2025      |
| 62  | - Lab30-3 – Create Restriction Policy <br> - Lab30-4 – Create Limited IAM User <br> - Lab30-5 – Test IAM User Limits <br> - Lab30-6 – Cleanup                                                                          | 08/11/2025 | 08/11/2025      |
| 63  | - Lab33-2.1 – Create Policy & Role <br> - Lab33-2.2 – Create Group & User <br> - Lab33-3 – Create KMS <br> - Lab33-4.1 – Create S3 Bucket <br> - Lab33-4.2 – Upload Data to S3 <br> - Lab33-5.1 – Create CloudTrail <br> - Lab33-5.2 – Logging to CloudTrail <br> - Lab33-5.3 – Create Athena <br> - Lab33-5.4 – Query with Athena <br> - Lab33-6 – Test & Share Encrypted S3 Data <br> - Lab33-7 – Cleanup | 09/11/2025 | 09/11/2025      |

---

### Week 9 Achievements:

* Strengthened foundational infrastructure skills by **creating a VPC, Security Group, and EC2 instance**, reinforcing cloud networking and secure deployment principles.

* Integrated cloud automation into communication workflows by configuring **Slack Incoming Webhooks**, enabling automated alerts — a key DevOps monitoring capability.

* Enhanced tagging and automation proficiency through:  
  * Creating and managing instance tags  
  * Creating Lambda execution roles  
  * Writing Lambda functions to **start/stop EC2 instances**  
  * Validating automation results  
  * Cleaning up resources to maintain a tidy environment  

* Developed strong **resource governance** skills with AWS Tags:  
  * Creating, editing, filtering, and managing tags at scale  
  * Using tags via the CLI  
  * Creating Resource Groups for structured cloud organization  

* Reinforced IAM expertise by creating **IAM Users, Policies, and Roles**, following least-privilege principles to secure identity workflows.

* Gained real-world IAM scenario experience:  
  * Switching roles across accounts  
  * Accessing EC2 in **Tokyo** and **North Virginia**  
  * Testing policy behavior with missing/restricted tags  
  * Editing resource tags  
  * Running **policy simulations**  
  * Performing complete environment cleanup  

* Strengthened security governance by creating **Restriction Policies**, limited-permission IAM users, and validating enforcement of access controls.

* Mastered an end-to-end **security visibility and data protection pipeline** by completing advanced labs:  
  * Creating IAM policies, roles, groups, and users  
  * Deploying and managing **KMS keys**  
  * Creating S3 buckets and uploading encrypted data  
  * Enabling **CloudTrail** for API auditing  
  * Querying CloudTrail logs via **Athena**  
  * Testing secure data sharing with **KMS-encrypted S3 objects**  
  * Cleaning up all resources for cost efficiency

---

