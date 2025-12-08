---
title: "Blog 2"
date: "2025-09-11"
weight: 2
chapter: false
pre: "<b> 3.2. </b>"
---

# AWS Weekly Roundup — Các cập nhật AWS nổi bật

Mỗi thứ Hai, AWS tổng hợp những cập nhật quan trọng nhất trong tuần.  
Tuần này bao gồm các cải tiến về **Amazon Bedrock, EC2 C8gn, DynamoDB Global Tables, Aurora DSQL, Amazon Nova Canvas**, và nhiều dịch vụ khác.

---

## EC2 C8gn — Hiệu năng mạng lên đến 200 Gbps

{{< figure src="/images/blog2/image1.png" title="Hình 1. EC2 C8gn sử dụng Graviton4." >}}

EC2 C8gn được xây dựng trên **AWS Graviton4** và kiến trúc **Nitro System** mới nhất:

- Băng thông mạng **tối đa 200 Gbps**
- Hiệu năng compute cao hơn thế hệ trước
- Tối ưu cho:
  - Workload mạng hiệu năng cao  
  - Viễn thông / xử lý gói tin  
  - Hệ thống phân tán  
  - Phân tích dữ liệu thời gian thực  

---

## DynamoDB Global Tables — Strong Consistency đa vùng

AWS bổ sung **Multi-Region Strong Consistency**, cho phép:

- Đọc dữ liệu nhất quán mạnh từ *bất kỳ vùng nào*
- Đơn giản hóa xây dựng hệ thống toàn cầu
- Đảm bảo **Zero-RPO** cho dữ liệu quan trọng

---

## Amazon Nova Canvas — Nâng cấp trải nghiệm sáng tạo

Tính năng mới:

- **8 phong cách tạo ảnh mới**
- Trải nghiệm **virtual try-on** tốt hơn
- Chất lượng hình cao hơn cho e-commerce và sáng tạo nội dung

---

## Amazon Q in Connect — Hỗ trợ thêm ngôn ngữ mới

Amazon Q mở rộng hỗ trợ:

- Tiếng Anh  
- Tây Ban Nha  
- Pháp  
- Bồ Đào Nha  
- Quan Thoại  
- Nhật Bản  
- Hàn Quốc  

---

## Aurora MySQL & RDS MySQL — Tích hợp SageMaker

Cập nhật mới:

- Extract dữ liệu gần real-time  
- Hỗ trợ định dạng Iceberg  
- Kết nối tốt hơn với các engine phân tích dữ liệu  

---

## Aurora DSQL — Mở rộng sang nhiều Region mới

DSQL hiện có mặt tại:

- APAC (Seoul)  
- Nhiều Region châu Âu  

Lợi ích:

- SQL phân tán, serverless  
- Cụm dữ liệu toàn cầu  
- Khả năng mở rộng ngang không giới hạn  

---

## Tác giả

{{< figure src="/images/blog2/image2.png" title="Hình 2. Elizabeth Fuentes — AWS." >}}

**Elizabeth Fuentes**  
AWS Developer Advocate  
Chia sẻ kiến thức AWS theo cách đơn giản và dễ tiếp cận cho mọi lập trình viên.
