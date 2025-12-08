---
title: "Week 5 Worklog (VI)"
date: "2025-10-12"
weight: 5
chapter: false
pre: "<b>1.5.</b>"
---


### Mục tiêu tuần 5:

* Hiểu VPC Peering và mô hình giao tiếp giữa nhiều VPC.
* Nâng cao khả năng triển khai hạ tầng bằng CloudFormation.
* Nắm rõ kiến trúc Transit Gateway và cách định tuyến trong mô hình hub-and-spoke.

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                                                                                                           | Start Date | Completion Date |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 29  | Lab19-01 – Giới thiệu VPC Peering                                                                                                                                                                                                                              | 06/10/2025 | 06/10/2025      |
| 30  | - Lab19-02.1 – Khởi tạo CloudFormation Templates <br> - Lab19-02.2 – Tạo Security Group <br> - Lab19-02.3 – Tạo EC2 Instance                                                                                            | 07/10/2025 | 07/10/2025      |
| 31  | - Lab19-03 – Cập nhật Network ACLs (NACLs) <br> - Lab19-04 – Tạo kết nối Peering                                                                                                                                                                              | 08/10/2025 | 08/10/2025      |
| 32  | - Lab19-05 – Cấu hình Route Tables <br> - Lab19-06 – Bật Cross-Peer DNS                                                                                                                                                                                       | 09/10/2025 | 09/10/2025      |
| 33  | Lab19-07 – Dọn dẹp tài nguyên                                                                                                                                                                                                                                  | 10/10/2025 | 10/10/2025      |
| 34  | - Lab20-01 – Giới thiệu Transit Gateway <br> - Lab20-02 – Các bước chuẩn bị                                                                                                                                                                                   | 11/10/2025 | 11/10/2025      |
| 35  | - Lab20-03 – Tạo Transit Gateway <br> - Lab20-04 – Tạo Transit Gateway Attachments <br> - Lab20-05 – Tạo Transit Gateway Route Tables <br> - Lab20-06 – Thêm TGW Routes vào các Route Tables của VPC <br> - Lab20-07 – Dọn dẹp tài nguyên                     | 12/10/2025 | 12/10/2025      |

---

### Thành tựu tuần 5:

* Hiểu sâu về **VPC Peering**, bao gồm cách kết nối private giữa các VPC, các tình huống sử dụng phổ biến, hạn chế và các yêu cầu bảo mật.

* Cải thiện khả năng tự động hóa nhờ vào việc khởi tạo **CloudFormation templates**, giúp tạo tài nguyên VPC ở quy mô lớn và tạo sự nhất quán trong triển khai hạ tầng.

* Cấu hình **Security Groups và EC2 Instances** trong nhiều VPC khác nhau để chuẩn bị cho kịch bản giao tiếp cross-VPC với các rule inbound/outbound phù hợp.

* Tăng cường bảo mật bằng cách cập nhật **Network ACLs (NACLs)** nhằm hỗ trợ giao tiếp VPC-to-VPC nhưng vẫn đảm bảo tính bảo mật theo mô hình stateless.

* Tạo và xác thực thành công **VPC Peering Connection**, bao gồm thiết lập requester–accepter và kiểm tra kết nối.

* Thiết lập logic định tuyến xuyên VPC bằng cách cấu hình **Route Tables** và bật **Cross-Peer DNS**, cho phép các instance ở VPC khác có thể resolve private DNS names.

* Thực hành tuân thủ **vệ sinh môi trường**, dọn dẹp tài nguyên đầy đủ để tránh tốn chi phí không cần thiết.

* Hiểu nền tảng **AWS Transit Gateway**, lợi ích của TGW so với Peering trong mô hình lớn, và cách TGW đơn giản hóa mạng multi-VPC.

* Hoàn thành đầy đủ các bước với Transit Gateway:
  * Tạo Transit Gateway  
  * Tạo attachments  
  * Tạo & cấu hình Route Tables  
  * Propagate routes và thêm vào Route Tables của VPC  
  * Triển khai mô hình định tuyến tập trung  

* Hoàn thành **chu trình Transit Gateway đầy đủ**, bao gồm tạo → định tuyến → kiểm thử → dọn dẹp để tối ưu chi phí và hiệu quả vận hành.
