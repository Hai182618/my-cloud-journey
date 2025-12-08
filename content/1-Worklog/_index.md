---
title: "Worklog"
date: "2025-09-11"
weight: 1
chapter: false
pre: " <b> 1. </b> "
---



This page provides an overview of my 12-week worklog throughout the internship program.  
It describes **how I completed the learning journey**, **what weekly objectives I followed**, and **how each activity contributed to my technical growth in AWS cloud engineering**.

Over the span of approximately **three months**, I documented weekly progress covering foundational AWS knowledge, hands-on cloud computing skills, operational best practices, and exploration of new-generation AWS technologies such as **Graviton4 performance tuning**, **Amazon Bedrock**, and **Amazon Q Developer plugins**.

---

## ⭐ Structure of My Worklog

My worklog follows a weekly structure. Each week includes:

- A specific **learning objective**
- Hands-on **tasks and experiments**
- Reflection on AWS services used
- Application of concepts to real-world scenarios

Below is the weekly outline of my 12-week learning journey:

---

### **Week 1:** [Getting familiar with AWS and foundational services](1.1-week1/)  
Introduction to AWS console, IAM, VPC, EC2, S3, CloudWatch. Setting up a stable working environment.

### **Week 2:** [Working with compute workloads & Graviton instances](1.2-week2/)  
Explored AWS Graviton2/3/4 architectures and benchmark behavior based on Blog 1 (Video Encoding on Graviton). Understood SIMD, SVE2, x265 optimization insights.

### **Week 3:** [Hands-on: Video encoding performance analysis](1.3-week3/)  
Executed sample FFmpeg workloads, studied scaling benchmarks, and compared cost-performance across EC2 instance families.

### **Week 4:** [Networking & high-performance compute with C8gn](1.4-week4/)  
Researched Amazon EC2 C8gn from Blog 2. Learned how ultra-high bandwidth (~600 Gbps) impacts analytics, virtual appliances, and cluster computing workflows.

### **Week 5:** [Understanding DynamoDB global tables & strong consistency](1.5-week5/)  
Studied Multi-Region Strong Consistency (MRSC). Designed exercises on zero-RPO scenarios and resilience architecture.

### **Week 6:** [Working with Bedrock and GenAI APIs](1.6-week6/)  
Explored Amazon Bedrock API keys (Blog 2). Tested authentication models, prompt workflows, and multi-language features in Amazon Q in Connect.

### **Week 7:** [Amazon Nova Canvas & virtual try-on](1.7-week7/)  
Learned about virtual try-on generation, image pipelines, and style models for product visualization. Conducted experiments with 3D animation and vector-style generation.

### **Week 8:** [SageMaker JumpStart & OpenSearch RAG optimization](1.8-week8/)  
Followed RAG optimization guide from Blog 2. Deployed sample RAG architecture and tuned OpenSearch latency.

### **Week 9:** [Serverless distributed SQL (Aurora DSQL)](1.9-week9/)  
Investigated Aurora DSQL regional expansion and serverless cluster performance. Compared distributed SQL patterns for multi-region workloads.

### **Week 10:** [Operational insights with Amazon Q Developer Plugins](1.10-week10/)  
Studied Blog 3 in depth. Tested Datadog and Wiz plugin behaviors using sample workloads. Learned intent recognition, API invocation flow, guardrails, and plugin credential configurations.

### **Week 11:** [Security, monitoring, and issue triage workflows](1.11-week11/)  
Practiced queries such as:  
- `@datadog list my current monitors`  
- `@wiz list issues with critical severity`  
Simulated operational troubleshooting scenarios.

### **Week 12:** [Final consolidation & real-world cloud operations](1.12-week12/)  
Reviewed all concepts, connected weekly learning outcomes, and prepared final documentation and architecture summaries for the internship.

---

This worklog summarizes the complete journey—capturing both foundational cloud skills and hands-on practice with new-generation AWS technologies.
