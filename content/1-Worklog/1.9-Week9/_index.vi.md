---
title: "Week 9 Worklog (VI)"
date: "2025-11-09"
weight: 9
chapter: false
pre: "<b>1.9.</b>"
---


### Mục tiêu tuần 9:

* Tăng cường kỹ năng tự động hóa, tagging, IAM, Lambda và vận hành theo sự kiện.  
* Phát triển khả năng quản trị tài nguyên đa vùng (multi-region).  
* Xây dựng khả năng giám sát & bảo vệ toàn diện bằng CloudTrail, Athena và KMS.

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                                                                   | Start Date | Completion Date |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 57  | - Tạo VPC <br> - Tạo Security Group <br> - Tạo EC2 Instance <br> - Cấu hình Slack Incoming Webhooks                                                                                                                   | 03/11/2025 | 03/11/2025      |
| 58  | - Tạo Tag cho Instance <br> - Tạo Role cho Lambda <br> - Viết Lambda Stop Instance <br> - Viết Lambda Start Instance <br> - Kiểm tra kết quả <br> - Dọn dẹp tài nguyên                                               | 04/11/2025 | 04/11/2025      |
| 59  | - Tạo EC2 Instance có Tag <br> - Quản lý Tag <br> - Lọc tài nguyên theo Tag <br> - Dùng Tag với CLI <br> - Tạo Resource Group <br> - Cleanup                                                                         | 05/11/2025 | 05/11/2025      |
| 60  | - Tạo IAM User <br> - Tạo IAM Policy <br> - Tạo IAM Role                                                                                                                                                              | 06/11/2025 | 06/11/2025      |
| 61  | - Switch Roles <br> - Truy cập EC2 tại Tokyo <br> - Truy cập EC2 tại North Virginia <br> - Test tạo EC2 khi thiếu/đủ Tag <br> - Chỉnh sửa Tag <br> - Kiểm tra Policy <br> - Cleanup                                 | 07/11/2025 | 07/11/2025      |
| 62  | - Tạo Restriction Policy <br> - Tạo IAM User giới hạn quyền <br> - Test giới hạn truy cập <br> - Cleanup                                                                                                             | 08/11/2025 | 08/11/2025      |
| 63  | - Tạo Policy & Role <br> - Tạo Group & User <br> - Tạo KMS Key <br> - Tạo S3 Bucket <br> - Upload dữ liệu lên S3 <br> - Tạo CloudTrail <br> - Bật Logging <br> - Tạo Athena <br> - Query bằng Athena <br> - Chia sẻ dữ liệu mã hóa <br> - Cleanup | 09/11/2025 | 09/11/2025      |

---

### Thành tựu tuần 9:

* Củng cố kỹ năng hạ tầng bằng cách tạo **VPC, Security Group, EC2 instance**, bám sát nguyên tắc bảo mật và networking chuẩn.

* Tích hợp tự động hóa vào quy trình vận hành nhờ cấu hình **Slack Incoming Webhooks**, giúp AWS gửi thông báo tự động — rất quan trọng trong DevOps.

* Tăng cường kỹ năng tagging và automation thông qua:  
  * Tạo & quản lý Tag  
  * Tạo Lambda Execution Role  
  * Viết Lambda start/stop EC2  
  * Kiểm thử kết quả automation  
  * Cleanup theo quy trình  

* Phát triển kỹ năng **governance** với AWS Tags:  
  * Tạo, chỉnh sửa, lọc Tag  
  * Sử dụng Tag qua CLI  
  * Tạo Resource Groups để tổ chức tài nguyên  

* Củng cố kiến thức IAM qua việc tạo **User, Policy, Role**, áp dụng nguyên tắc least privilege.

* Trải nghiệm các tình huống IAM thực tế:  
  * Switch Role  
  * Truy cập EC2 ở nhiều region  
  * Test policy khi thiếu/đủ Tag  
  * Chỉnh sửa Tag  
  * Policy Simulation  
  * Dọn dẹp môi trường  

* Hoàn thiện quản trị bảo mật bằng **Restriction Policies**, IAM User giới hạn quyền và kiểm thử enforcement.

* Làm chủ pipeline **giám sát & bảo vệ dữ liệu** với:  
  * Tạo IAM Policy, Role, Group, User  
  * Tạo & quản lý KMS Key  
  * Upload & mã hóa dữ liệu S3  
  * Bật **CloudTrail** theo dõi API  
  * Query log với **Athena**  
  * Chia sẻ dữ liệu mã hóa an toàn  
  * Cleanup đầy đủ để tối ưu chi phí  

