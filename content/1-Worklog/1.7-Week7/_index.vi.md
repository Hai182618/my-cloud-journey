---
title: "Week 7 Worklog (VI)"
date: "2025-10-26"
weight: 7
chapter: false
pre: "<b>1.7.</b>"
---


### Mục tiêu tuần 7:

* Hiểu sâu hệ thống lưu trữ AWS ở cả 3 mô hình: object, block, file.  
* Thực hành toàn diện với S3, Backup, Storage Gateway và quy trình migrate VM lên AWS.  
* Nắm vững kiến trúc lưu trữ hybrid và quy mô lớn.

---

### Công việc thực hiện trong tuần:

| Day | Task                                                                                                                                                                                                                                   | Start Date | Completion Date |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 1  | Module 04-01 – Dịch vụ lưu trữ trên AWS                                                                                                                                                                                                | 20/10/2025 | 20/10/2025      |
| 2  | Module 04-02 – Amazon S3 Access Point – Storage Class                                                                                                                                                                                   | 21/10/2025 | 21/10/2025      |
| 3  | Module 04-03 – S3 Static Website, CORS, Glacier, Object Key, Performance                                                                                                                                                                | 22/10/2025 | 22/10/2025      |
| 4  | Module 04-04 – Snow Family – Storage Gateway – Backup                                                                                                                                                                                   | 23/10/2025 | 23/10/2025      |
| 5  | - Lab13-02.1 – Tạo S3 Bucket <br> - Lab13-02.2 – Deploy Infrastructure <br> - Lab13-03 – Tạo Backup Plan <br> - Lab13-04 – Cấu hình Notifications                                                                                      | 24/10/2025 | 24/10/2025      |
| 6  | - Lab14-01 – VMware Workstation <br> - Lab14-02.1 – Xuất VM <br> - Lab14-02.2 – Upload VM lên AWS <br> - Lab14-02.3 – Import VM vào AWS <br> - Lab14-02.4 – Deploy instance từ AMI                                                     | 25/10/2025 | 25/10/2025      |
| 7  | - Lab14-03.1 – Cấu hình S3 ACL <br> - Lab14-03.2 – Xuất VM từ Instance <br> - Lab14-05 – Cleanup trên AWS <br> - Lab24-2.1 – Tạo Storage Gateway <br> - Lab24-2.2 – Tạo File Shares <br> - Lab24-2.3 – Mount File Shares <br> - Lab24-3 – Cleanup | 26/10/2025 | 26/10/2025      |

---

### Thành tựu tuần 7:

* Hiểu toàn diện về **dịch vụ lưu trữ AWS**, gồm object storage, block storage và file storage, cũng như cách AWS thiết kế hệ thống lưu trữ mở rộng, bền bỉ và sẵn sàng cao.

* Nắm sâu về **Amazon S3**, bao gồm:  
  * Access Points  
  * Bucket Policy  
  * Storage Class  
  * Lifecycle  
  * Tối ưu chi phí & hiệu năng  

* Thành thạo triển khai **S3 Static Website**, cấu hình **CORS**, thiết kế **Object Key**, tối ưu hiệu năng bằng multipart upload, transfer acceleration và caching.  
  Tìm hiểu Glacier & Glacier Deep Archive cho lưu trữ dài hạn.

* Hiểu rõ hệ sinh thái lưu trữ hybrid của AWS:  
  * Snow Family (Snowcone, Snowball, Snowmobile)  
  * AWS Storage Gateway  
  * Backup và hybrid workflow  

* Thực hành chuyên sâu với S3 & Backup:  
  * Tạo và cấu hình bucket  
  * Triển khai hạ tầng bằng CloudFormation  
  * Tạo Backup Plan với lịch & retention  
  * Thiết lập SNS Notifications  

* Có kinh nghiệm thực tế về **migrate VM lên AWS**, bao gồm:  
  * Xuất VM từ VMware Workstation  
  * Upload image lên S3  
  * Import vào AWS  
  * Deploy instance từ AMI  

* Nâng cao kỹ năng quản trị S3 qua cấu hình S3 ACL, export VM images và dọn dẹp tài nguyên.

* Củng cố khả năng triển khai **AWS Storage Gateway**, tạo file share, mount lên client và cleanup đầy đủ để tối ưu chi phí.

