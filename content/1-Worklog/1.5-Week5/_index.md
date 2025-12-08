---
title: "Week 5 Worklog"
date: "2025-10-12"
weight: 5
chapter: false
pre: "<b>1.5.</b>"
---


### Week 5 Objectives:

* Learn VPC Peering and multi-VPC communication patterns.
* Strengthen infrastructure provisioning with CloudFormation.
* Understand Transit Gateway architecture and routing workflows.

---

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                           | Start Date | Completion Date |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 1  | Lab19-01 – VPC Peering (Introduction)                                                                                                                                                                                                                           | 06/10/2025 | 06/10/2025      |
| 2  | - Lab19-02.1 – Initialize CloudFormation Templates <br> - Lab19-02.2 – Create Security Group <br> - Lab19-02.3 – Create EC2 Instance                                                                                                                           | 07/10/2025 | 07/10/2025      |
| 3  | - Lab19-03 – Update Network ACLs (NACLs) <br> - Lab19-04 – Create a Peering Connection                                                                                                                                                                         | 08/10/2025 | 08/10/2025      |
| 4  | - Lab19-05 – Configure Route Tables <br> - Lab19-06 – Enable Cross-Peer DNS                                                                                                                                                                                     | 09/10/2025 | 09/10/2025      |
| 5  | Lab19-07 – Clean Up Resources                                                                                                                                                                                                                                   | 10/10/2025 | 10/10/2025      |
| 6  | - Lab20-01 – Transit Gateway (Introduction) <br> - Lab20-02 – Preparation Steps                                                                                                                                                                                 | 11/10/2025 | 11/10/2025      |
| 7  | - Lab20-03 – Create Transit Gateway <br> - Lab20-04 – Create Transit Gateway Attachments <br> - Lab20-05 – Create Transit Gateway Route Tables <br> - Lab20-06 – Add Transit Gateway Routes to VPC Route Tables <br> - Lab20-07 – Clean Up Resources            | 12/10/2025 | 12/10/2025      |

---

### Week 5 Achievements:

* Gained a deep understanding of **VPC Peering**, including private connectivity, common use cases, architectural limitations, and related security considerations.

* Improved automation capabilities by initializing **CloudFormation templates**, creating VPC components at scale, and laying the foundation for consistent infrastructure provisioning workflows.

* Configured **Security Groups and EC2 instances** across separate VPCs, preparing environments for controlled cross-VPC communication with accurate inbound/outbound rule design.

* Updated and hardened **Network ACLs (NACLs)** to support VPC-to-VPC connectivity while enforcing stateless security boundaries—emphasizing layered network security.

* Successfully created and validated **VPC Peering Connections**, including requester–accepter configuration and connectivity status validation.

* Built routing logic for multi-VPC communication by configuring **Route Tables** and enabling **cross-peer DNS resolution**, allowing private DNS names to be resolved across VPCs.

* Practiced disciplined **environment hygiene** by performing complete resource clean-up to maintain cost efficiency and avoid unnecessary infrastructure retention.

* Developed foundational understanding of **AWS Transit Gateway (TGW)**, its benefits over VPC Peering in large-scale hub-and-spoke architectures, and its role in simplifying multi-VPC connectivity.

* Completed hands-on Transit Gateway tasks:  
  * Created a Transit Gateway  
  * Established VPC Attachments  
  * Built and configured TGW Route Tables  
  * Propagated and added routes to VPC Route Tables  
  * Integrated centralized routing patterns  

* Executed a **full Transit Gateway lifecycle**, including provisioning, routing setup, connectivity validation, and clean-up to ensure cost and operational efficiency.
