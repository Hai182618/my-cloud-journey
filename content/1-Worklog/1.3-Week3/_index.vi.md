---
title: "Week 3 Worklog (VI)"
date: "2025-09-28"
weight: 3
chapter: false
pre: "<b>1.3.</b>"
---


### Mục tiêu tuần 3:

* Hiểu nền tảng mạng AWS VPC.
* Thực hành routing, subnet, gateway và kết nối hybrid.
* Củng cố bảo mật mạng qua Security Groups và Network ACLs.

---

### Công việc thực hiện trong tuần:

| Day | Task                                                                                                                                                                        | Start Date | Completion Date |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 15  | Module 02-01 – AWS Virtual Private Cloud (VPC)                                                                                                                              | 22/09/2025 | 22/09/2025      |
| 16  | Module 02-02 – VPC Security & Multi-VPC features                                                                                                                            | 23/09/2025 | 23/09/2025      |
| 17  | Module 02-03 – VPN, DirectConnect, LoadBalancer, Extra Resources                                                                                                            | 24/09/2025 | 24/09/2025      |
| 18  | - Lab03-01 – Bắt đầu với Amazon VPC & VPN Site-to-Site <br> - Lab03-01.1 – Subnets                                                                                          | 25/09/2025 | 25/09/2025      |
| 19  | - Lab03-01.2 – Route Table <br> - Lab03-01.3 – Internet Gateway (IGW)                                                                                                       | 26/09/2025 | 26/09/2025      |
| 20  | Lab03-01.4 – NAT Gateway                                                                                                                                                     | 27/09/2025 | 27/09/2025      |
| 21  | - Lab03-02.1 – Security Group <br> - Lab03-02.2 – Network ACLs <br> - Lab03-02.3 – VPC Resource Map                                                                         | 28/09/2025 | 28/09/2025      |

---

### Thành tựu tuần 3:

* Hiểu sâu về **Amazon VPC**: CIDR, địa chỉ IP, subnet, route propagation và vai trò của VPC trong việc xây dựng môi trường mạng an toàn & tách biệt.

* Làm chủ **bảo mật VPC và kiến trúc multi-VPC**, gồm:
  * Security Groups  
  * Network ACLs  
  * VPC Peering  
  * Transit Gateway  
  * mô hình giao tiếp giữa các VPC  

* Hiểu rõ về **kết nối hybrid** như Site-to-Site VPN và AWS Direct Connect, cũng như cách chúng kết nối hệ thống on-premises với AWS.

* Nắm vững chức năng của **Elastic Load Balancing**, bao gồm phân phối traffic, health check, tăng tính sẵn sàng và cách load balancer tương tác với lớp mạng của VPC.

* Hoàn thành các lab xây dựng VPC theo chuẩn production:
  * Tạo subnet public & private  
  * Thiết kế và cấu hình Route Tables  
  * Gắn và cấu hình Internet Gateway  
  * Tạo NAT Gateway để private subnet có outbound internet an toàn  

* Nâng cao kỹ năng bảo mật mạng thông qua cấu hình Security Groups & NACLs, kiểm tra inbound/outbound traffic.

* Xây dựng hoàn chỉnh **VPC Resource Map**, hỗ trợ trực quan hóa kiến trúc mạng, luồng traffic và ranh giới bảo mật.
