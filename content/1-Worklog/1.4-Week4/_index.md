---
title: "Week 4 Worklog"
date: "2025-10-05"
weight: 4
chapter: false
pre: "<b>1.4.</b>"
---


### Week 4 Objectives:

* Strengthen hands-on skills with VPC creation, subnets, routing, and connectivity.
* Improve understanding of hybrid DNS and CloudFormation deployments.
* Build secure and scalable network foundations following AWS best practices.

---

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                     | Start Date | Completion Date |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- |
| 22  | - Lab03-03 – Create VPC <br> - Lab03-03.2 – Create Subnet                                                                                                                                                                 | 29/09/2025 | 29/09/2025      |
| 23  | - Lab03-03.3 – Create an Internet Gateway (IGW) <br> - Lab03-03.4 – Create Route Table for Outbound Internet Routing via IGW                                                                                              | 30/09/2025 | 30/09/2025      |
| 24  | - Lab03-03.5 – Create Security Groups <br> - Lab03-04.1 – Create EC2 Instances in Subnets                                                                                                                                 | 01/10/2025 | 01/10/2025      |
| 25  | - Lab03-04.2 – Test Connection <br> - Lab03-04.3 – Create NAT Gateway                                                                                                                                                     | 02/10/2025 | 02/10/2025      |
| 26  | Lab03-04.5 – EC2 Instance Connect Endpoint                                                                                                                                                                                | 03/10/2025 | 03/10/2025      |
| 27  | - Lab10-01 – Set up Hybrid DNS with Route 53 Resolver (Introduction) <br> - Lab10-02.1 – Generate Key Pair <br> - Lab10-02.2 – Initialize CloudFormation Template                                                        | 04/10/2025 | 04/10/2025      |
| 28  | - Lab10-02.3 – Configure Security Group <br> - Lab10-03 – Connect to RDGW <br> - Lab10-05 – Set up DNS <br> - Lab10-05.1 → 05.4 – Outbound/Inbound Endpoint, Resolver Rules, Testing <br> - Lab10-06 – Clean Up Resources | 05/10/2025 | 05/10/2025      |

---

### Week 4 Achievements:

* Strengthened hands-on proficiency in **VPC creation and subnet design**, including building a VPC from scratch, defining appropriate CIDR ranges, and creating public/private subnets based on AWS best practices.

* Configured critical **VPC Internet connectivity components**, including attaching an Internet Gateway (IGW) and designing Route Tables to correctly route outbound traffic for secure public access.

* Implemented **Security Groups** suited for subnet roles and deployed EC2 instances into corresponding subnets, ensuring secure segmentation between public-facing and private workloads.

* Validated end-to-end **network connectivity**, conducted structured connection tests, and deployed a **NAT Gateway** to allow private subnets to securely access the internet.

* Enhanced operational capability by configuring the **EC2 Instance Connect Endpoint**, enabling secure, agentless SSH access without requiring public IPs or bastion hosts.

* Gained foundational knowledge of **Hybrid DNS using Route 53 Resolver**, understanding inbound/outbound endpoints and how AWS enables DNS resolution across hybrid networks.

* Strengthened **CloudFormation skills**, including generating key pairs, initializing templates, and configuring supporting infrastructure such as Security Groups and DNS components.

* Completed a comprehensive **hybrid DNS workflow**, including:  
  * Creating outbound & inbound Resolver Endpoints  
  * Configuring Resolver Rules  
  * Testing cross-network DNS resolution  
  * Cleaning up resources to maintain hygiene and cost efficiency
