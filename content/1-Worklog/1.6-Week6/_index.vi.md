---
title: "Week 6 Worklog (VI)"
date: "2025-10-19"
weight: 6
chapter: false
pre: "<b>1.6.</b>"
---


### Mục tiêu tuần 6:

* Hiểu sâu về hệ sinh thái Compute của AWS, đặc biệt là EC2.
* Nắm rõ nền tảng lưu trữ: EBS, Instance Store và Backup.
* Tăng cường tự động hóa với User Data, Metadata và Auto Scaling.
* Làm quen với hệ thống file (EFS, FSx) và công cụ Migration (MGN).

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                            | Start Date | Completion Date |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 1  | - Module 03-01 – Compute VM on AWS <br> - Module 03-01-01 – EC2 Instance Types                                                                                                  | 13/10/2025 | 13/10/2025      |
| 2  | Module 03-01-02 – AMI / Backup / Key Pair                                                                                                                                       | 14/10/2025 | 14/10/2025      |
| 3  | - Module 03-01-03 – Elastic Block Store (EBS) <br> - Module 03-01-04 – Instance Store                                                                                           | 15/10/2025 | 15/10/2025      |
| 4  | - Module 03-01-05 – User Data <br> - Module 03-01-06 – Metadata                                                                                                                 | 16/10/2025 | 16/10/2025      |
| 5  | Module 03-01-07 – EC2 Auto Scaling                                                                                                                                              | 17/10/2025 | 17/10/2025      |
| 6  | Module 03-02 – EC2 Autoscaling / EFS / FSx / Lightsail / MGN                                                                                                                    | 18/10/2025 | 18/10/2025      |
| 7  | - Lab13-01 – Triển khai AWS Backup (Giới thiệu) <br> - Lab13-02.2 – Deploy Infrastructure <br> - Lab13-03 – Tạo Backup Plan <br> - Lab13-05 – Kiểm tra Restore <br> - Lab13-06 – Dọn dẹp tài nguyên | 19/10/2025 | 19/10/2025      |

---

### Thành tựu tuần 6:

* Hiểu rõ nền tảng **Compute VM trên AWS**, bao gồm vai trò của EC2, vòng đời instance, cách provisioning và quản lý trong môi trường cloud.

* Làm chủ **các loại EC2 Instance**, gồm general purpose, compute optimized, memory optimized, storage optimized và accelerated computing.  
  Biết cách lựa chọn loại instance tối ưu cho từng workload.

* Nắm vững quản lý **AMI**, từ tạo AMI custom, phiên bản hóa, đến việc dùng AMI cho backup, scaling và khôi phục thảm họa.  
  Cải thiện bảo mật bằng quản lý Key Pair và thực hành SSH đúng chuẩn.

* Hiểu chuyên sâu về **Elastic Block Store (EBS)**: loại volume, hiệu năng, snapshot, mã hóa và các best practice khi thiết kế lưu trữ persistent.  
  Phân biệt rõ với **Instance Store** và hiểu các tình huống dùng ephemeral storage.

* Thành thạo **User Data và Instance Metadata**, bao gồm cơ chế bootstrap, cấu hình runtime, phân phối thông tin hệ thống và triển khai ứng dụng dựa trên môi trường.

* Làm chủ nguyên lý vận hành của **EC2 Auto Scaling**, gồm launch templates, scaling policies, health checks, lifecycle hooks và chiến lược tối ưu chi phí.

* Tiếp cận hệ sinh thái compute và storage rộng hơn:  
  * EC2 Autoscaling  
  * EFS  
  * FSx  
  * Lightsail  
  * AWS MGN  

* Hoàn thành toàn bộ quy trình **AWS Backup**:  
  * Triển khai hạ tầng Backup bằng CloudFormation  
  * Tạo Backup Plan (rule, schedule, lifecycle)  
  * Kiểm thử restore đảm bảo RTO/RPO  
  * Dọn dẹp tài nguyên để tiết kiệm chi phí
