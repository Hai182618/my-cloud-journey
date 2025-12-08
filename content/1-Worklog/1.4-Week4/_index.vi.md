---
title: "Week 4 Worklog (VI)"
date: "2025-10-05"
weight: 4
chapter: false
pre: "<b>1.4.</b>"
---


### Mục tiêu tuần 4:

* Nâng cao kỹ năng thực hành tạo VPC, subnet, routing và kết nối mạng.
* Hiểu rõ Hybrid DNS và triển khai hạ tầng với CloudFormation.
* Xây dựng nền tảng mạng an toàn & mở rộng theo chuẩn AWS.

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                                                                     | Start Date | Completion Date |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- |
| 22  | - Lab03-03 – Tạo VPC <br> - Lab03-03.2 – Tạo Subnet                                                                                                                                                                       | 29/09/2025 | 29/09/2025      |
| 23  | - Lab03-03.3 – Tạo Internet Gateway (IGW) <br> - Lab03-03.4 – Tạo Route Table cho outbound internet qua IGW                                                                                                               | 30/09/2025 | 30/09/2025      |
| 24  | - Lab03-03.5 – Tạo Security Groups <br> - Lab03-04.1 – Tạo EC2 Instances trong các Subnet                                                                                                                                 | 01/10/2025 | 01/10/2025      |
| 25  | - Lab03-04.2 – Kiểm tra kết nối <br> - Lab03-04.3 – Tạo NAT Gateway                                                                                                               | 02/10/2025 | 02/10/2025      |
| 26  | Lab03-04.5 – EC2 Instance Connect Endpoint                                                                                                                                                                                | 03/10/2025 | 03/10/2025      |
| 27  | - Lab10-01 – Cài đặt Hybrid DNS với Route 53 Resolver (Giới thiệu) <br> - Lab10-02.1 – Tạo Key Pair <br> - Lab10-02.2 – Khởi tạo CloudFormation Template                          | 04/10/2025 | 04/10/2025      |
| 28  | - Lab10-02.3 – Cấu hình Security Group <br> - Lab10-03 – Kết nối RDGW <br> - Lab10-05 – Thiết lập DNS <br> - Lab10-05.1 → 05.4 – Outbound/Inbound Endpoint, Resolver Rules, Test <br> - Lab10-06 – Dọn dẹp tài nguyên | 05/10/2025 | 05/10/2025      |

---

### Thành tựu tuần 4:

* Nâng cao kỹ năng thực hành **tạo VPC và subnet**, xây dựng VPC từ đầu, thiết kế CIDR hợp lý và tạo subnet public/private theo chuẩn best practice.

* Cấu hình các thành phần **kết nối Internet** của VPC như Internet Gateway (IGW), Route Tables để đảm bảo outbound traffic ra internet hoạt động đúng và an toàn.

* Triển khai **Security Groups** phù hợp với từng loại subnet và khởi tạo EC2 trong đúng môi trường mạng, đảm bảo phân tách workload public và private.

* Kiểm thử **kết nối mạng end-to-end**, thực hiện test connection và triển khai **NAT Gateway** giúp private subnet có thể truy cập internet một cách an toàn.

* Tăng cường khả năng vận hành nhờ thiết lập **EC2 Instance Connect Endpoint**, cho phép SSH không cần public IP hoặc bastion host.

* Hiểu nền tảng **Hybrid DNS** thông qua Route 53 Resolver, bao gồm inbound/outbound endpoint và cách AWS xử lý DNS trong môi trường hybrid.

* Củng cố kỹ năng **CloudFormation**: tạo key pair, khởi tạo template, cấu hình Security Groups và thành phần DNS liên quan.

* Hoàn thiện **quy trình Hybrid DNS** đầy đủ:  
  * Tạo outbound & inbound Resolver Endpoints  
  * Cấu hình Resolver Rules  
  * Kiểm thử DNS cross-network  
  * Dọn dẹp tài nguyên giúp giảm chi phí & tối ưu môi trường
