---
title: "Week 10 Worklog (VI)"
date: "2025-11-16"
weight: 10
chapter: false
pre: "<b>1.10.</b>"
---


### Mục tiêu tuần 10:
* Củng cố nền tảng cơ sở dữ liệu (database fundamentals) và các mô hình dữ liệu trong môi trường cloud.
* Nắm vững RDS, Aurora, Redshift và ElastiCache.
* Thực hành triển khai ứng dụng, backup, restore và migration end-to-end.

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                                                                   | Start Date | Completion Date |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 1  | - Module 06-01 – Tổng quan kiến thức cơ sở dữ liệu                                                                                                                                                                      | 10/11/2025 | 10/11/2025      |
| 2  | - Module 06-02 – Amazon RDS & Amazon Aurora                                                                                                                                                                             | 11/11/2025 | 11/11/2025      |
| 3  | - Module 06-03 – Redshift & ElastiCache                                                                                                                                                                                 | 12/11/2025 | 12/11/2025      |
| 4  | - Tạo VPC <br> - Tạo EC2 Security Group <br> - Tạo RDS Security Group <br> - Tạo DB Subnet Group                                                                                                                       | 13/11/2025 | 13/11/2025      |
| 5  | - Tạo EC2 Instance <br> - Tạo RDS Database Instance                                                                                                                                                                     | 14/11/2025 | 14/11/2025      |
| 6  | - Triển khai ứng dụng (Application Deployment) <br> - Backup & Restore                                                                                                                                                | 15/11/2025 | 15/11/2025      |
| 7  | - Dọn dẹp tài nguyên (Clean Up) <br> - Lab43-01 → 43-06 (EC2 Connect, cấu hình Oracle/MSSQL) <br> - Lab43-07 → 43-17 (Schema Conversion, Migration Tasks, Events, Logs, Troubleshooting)                             | 16/11/2025 | 16/11/2025      |

---

### Thành tựu tuần 10:

* Củng cố kiến thức nền tảng về **cơ sở dữ liệu**, bao gồm:  
  * Mô hình quan hệ & phi quan hệ  
  * Chuẩn hoá dữ liệu  
  * Indexing  
  * Transaction & Isolation Levels  
  * High Availability trong môi trường cloud  

* Hiểu sâu về **Amazon RDS và Amazon Aurora**:  
  * Các loại engine  
  * Kiến trúc lưu trữ  
  * Multi-AZ  
  * Read Replicas  
  * Backup tự động  
  * Cơ chế failover  
  * Aurora distributed storage hiệu năng cao  

* Mở rộng kiến thức phân tích & caching thông qua:  
  * **Amazon Redshift** (data warehouse)  
  * **Amazon ElastiCache** (Redis/Memcached) cho workload độ trễ thấp  

* Hoàn thành loạt lab thiết kế hạ tầng database:  
  * Tạo VPC chuyên dụng cho database  
  * Tạo Security Group cho EC2 và RDS  
  * Tạo **DB Subnet Group** trên nhiều AZ để hỗ trợ RDS  

* Tự triển khai một kiến trúc thực tế **EC2 → RDS**, đảm bảo kết nối mạng an toàn và đúng chuẩn.

* Thực hành triển khai ứng dụng kết nối EC2–RDS, kèm theo các thao tác quan trọng: **backup và restore** để kiểm chứng khả năng phục hồi dữ liệu.

* Thực hiện đầy đủ quy trình cleanup để tối ưu chi phí và giữ môi trường sạch.

* Nâng cao kỹ năng migration với một bộ lab chuyên sâu bao gồm:  
  * EC2 Connect để quản trị database  
  * Cấu hình Oracle và MSSQL  
  * Chuyển đổi schema bằng **AWS SCT**  
  * Migration bằng **AWS DMS**  
  * Theo dõi sự kiện, logs, tuning hiệu năng, troubleshooting  

* Tích lũy kinh nghiệm thực tế về **end-to-end database migration**, bao gồm chuyển đổi schema, replication, kiểm tra dữ liệu, và cleanup — giống quy trình doanh nghiệp thực tế.

