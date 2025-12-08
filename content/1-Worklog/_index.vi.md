---
title: "Nhật ký công việc (Worklog)"
date: "2025-09-11"
weight: 1
chapter: false
pre: " <b> 1. </b> "
---



Trang này giới thiệu tổng quan về **nhật ký 12 tuần** trong suốt quá trình thực tập.  
Tôi trình bày **cách tôi hoàn thành chương trình**, **tôi đã học gì mỗi tuần**, và **những kỹ năng AWS nào đã được áp dụng vào thực tế**.

Trong khoảng **3 tháng**, tôi ghi lại tiến độ hằng tuần, bao gồm kiến thức nền tảng, thực hành trên các dịch vụ AWS, kỹ năng vận hành, và nghiên cứu các công nghệ thế hệ mới như **Graviton4**, **Bedrock GenAI**, và **plugin Amazon Q Developer** cho Datadog và Wiz.

---

## ⭐ Cấu trúc Worklog của tôi

Mỗi tuần bao gồm:

- Mục tiêu học tập  
- Bài tập thực hành  
- Dịch vụ AWS sử dụng  
- Bài học rút ra và ứng dụng thực tế  

Dưới đây là toàn bộ lộ trình 12 tuần:

---

### **Tuần 1:** [Làm quen với AWS và các dịch vụ cơ bản](1.1-week1/)  
Học IAM, EC2, S3, CloudWatch, VPC và cấu hình môi trường làm việc.

### **Tuần 2:** [Compute workloads & kiến trúc Graviton](1.2-week2/)  
Nghiên cứu Graviton2/3/4, SIMD, SVE2, tối ưu x265 dựa theo Blog 1: Video Encoding on Graviton.

### **Tuần 3:** [Thực hành phân tích hiệu năng video encoding](1.3-week3/)  
Chạy thử workload FFmpeg, đánh giá benchmark chi phí–hiệu năng giữa các dòng EC2.

### **Tuần 4:** [Networking hiệu năng cao với C8gn](1.4-week4/)  
Tìm hiểu C8gn (~600 Gbps) từ Blog 2 và vai trò trong analytics, HPC, và virtual appliances.

### **Tuần 5:** [DynamoDB Global Tables & tính nhất quán mạnh đa vùng](1.5-week5/)  
Nghiên cứu MRSC (zero RPO) và thử nghiệm thiết kế hệ thống chống chịu cao.

### **Tuần 6:** [Amazon Bedrock & GenAI APIs](1.6-week6/)  
Khám phá Bedrock API keys, xác thực API, multi-language trong Amazon Q in Connect.

### **Tuần 7:** [Amazon Nova Canvas & Virtual Try-on](1.7-week7/)  
Thử nghiệm pipeline tạo ảnh + style models theo Blog 2 (3D, vector, graphic novel,...).

### **Tuần 8:** [RAG Optimization với SageMaker + OpenSearch](1.8-week8/)  
Xây dựng demo RAG, tối ưu truy vấn OpenSearch.

### **Tuần 9:** [Aurora DSQL – Serverless Distributed SQL](1.9-week9/)  
Nghiên cứu khả năng mở rộng theo vùng, multi-region clusters và so sánh mô hình distributed SQL.

### **Tuần 10:** [Amazon Q Developer Plugins (Datadog & Wiz)](1.10-week10/)  
Học cơ chế hoạt động plugin: intent recognition, API invocation, guardrails… theo Blog 3.

### **Tuần 11:** [Security, Monitoring & Issue Triage](1.11-week11/)  
Thực hành truy vấn mô phỏng vận hành:  
- `@datadog list my current monitors`  
- `@wiz list the issues with critical severity`

### **Tuần 12:** [Tổng kết & Ôn tập vận hành hạ tầng thực tế](1.12-week12/)  
Tổng hợp kiến thức, chuẩn bị tài liệu cuối kỳ và liên kết toàn bộ khối lượng học tập 12 tuần.

---

Worklog này phản ánh trọn vẹn hành trình học tập—từ kiến thức nền tảng AWS đến các công nghệ hiện đại như Graviton, Bedrock và Amazon Q Developer.
