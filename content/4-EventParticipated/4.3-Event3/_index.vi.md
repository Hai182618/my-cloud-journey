# HỘI THẢO AWS WELL-ARCHITECTED SECURITY PILLAR

## Thông tin sự kiện
**Thời gian:** Thứ Bảy, 29/11/2025, 8:30 AM – 12:00 PM  
**Địa điểm:** Văn phòng AWS Việt Nam  
**Vai trò:** Người tham dự  

---

## Mục đích sự kiện
Buổi workshop buổi sáng cung cấp cái nhìn chuyên sâu toàn diện về trụ cột Bảo mật (Security Pillar) trong AWS Well-Architected Framework, bao gồm cả 5 lĩnh vực bảo mật:

- Quản lý danh tính & truy cập (IAM)  
- Giám sát & phát hiện (Detection)  
- Bảo vệ hạ tầng (Infrastructure Protection)  
- Bảo vệ dữ liệu (Data Protection)  
- Ứng phó sự cố (Incident Response)  

Buổi học được thiết kế nhằm trang bị cho người tham gia kiến thức thực tế trong việc triển khai các best practice bảo mật trong môi trường AWS, đồng thời chia sẻ ví dụ thực tế từ doanh nghiệp Việt Nam.

---

# Tổng quan chương trình

## **8:30 – 8:50 AM | Khai mạc & Nền tảng bảo mật**

### Security Pillar trong Well-Architected Framework
- Vai trò của Security Pillar  
- Các nguyên tắc cốt lõi: Least Privilege – Zero Trust – Defense in Depth  
- Mô hình Trách nhiệm chia sẻ AWS (Shared Responsibility Model)  
- Các mối đe dọa bảo mật đám mây phổ biến tại Việt Nam  

---

# Trụ cột 1 — Identity & Access Management  
## **8:50 – 9:30 AM | Kiến trúc IAM hiện đại**
- IAM fundamentals: Users, Roles, Policies — tránh long-term credentials  
- IAM Identity Center: SSO, permission sets  
- SCP & Permission Boundaries trong môi trường multi-account  
- MFA, xoay vòng credentials, Access Analyzer  
- **Mini Demo:** kiểm tra IAM Policy + mô phỏng quyền truy cập  

---

# Trụ cột 2 — Detection  
## **9:30 – 9:55 AM | Giám sát & phát hiện liên tục**
- CloudTrail (org-level)  
- GuardDuty  
- Security Hub  
- Logging theo từng lớp: VPC Flow Logs, ALB logs, S3 logs  
- Cảnh báo & tự động hóa với EventBridge  
- Detection-as-Code (IaC + rule-based detection)  

---

## **9:55 – 10:10 AM | Nghỉ giải lao**

---

# Trụ cột 3 — Infrastructure Protection  
## **10:10 – 10:40 AM | Bảo mật mạng & workload**
- Phân đoạn VPC, private vs public subnet  
- Security Group vs NACL: mô hình áp dụng  
- AWS WAF + Shield + Network Firewall  
- Bảo mật workload: EC2, ECS/EKS security basics  

---

# Trụ cột 4 — Data Protection  
## **10:40 – 11:10 AM | Mã hóa, khóa & quản lý secrets**
- KMS: key policies, grants, rotation  
- Mã hóa at-rest & in-transit (S3, EBS, RDS, DynamoDB)  
- AWS Secrets Manager & Parameter Store — mô hình xoay vòng secrets  
- Phân loại dữ liệu & guardrails kiểm soát truy cập  

---

# Trụ cột 5 — Incident Response  
## **11:10 – 11:40 AM | Quy trình IR & tự động hóa**

### Chu trình IR theo AWS Framework  
### Playbooks:
- Compromised IAM key  
- S3 public exposure  
- Phát hiện malware trên EC2  
- Snapshot, cô lập, thu thập bằng chứng  
- Auto-response bằng Lambda / Step Functions  

---

## **11:40 – 12:00 PM | Tổng kết & Hỏi đáp**
- Tóm tắt 5 trụ cột bảo mật  
- Các sai lầm phổ biến & thực tiễn tại doanh nghiệp Việt Nam  
- Lộ trình học chứng chỉ bảo mật (Security Specialty, Solutions Architect Professional)  

---

# Bài học chính (Key Learnings)
- Least Privilege là nền tảng — luôn bắt đầu với quyền tối thiểu  
- Zero Trust: không giả định bất kỳ sự tin tưởng nào, kể cả trong mạng nội bộ  
- Defense in Depth yêu cầu bảo mật nhiều lớp  
- Khả năng phát hiện phải được tự động hóa và liên tục  
- IR playbook cần được ghi chép và kiểm thử định kỳ  

---

# Ứng dụng vào công việc (Application to My Work)
- Triển khai IAM Access Analyzer  
- Bật GuardDuty và Security Hub để giám sát tập trung  
- Xây dựng IR playbook cho các kịch bản phổ biến  
- Rà soát & siết Security Group theo nguyên tắc least privilege  
- Bật mã hóa cho mọi dịch vụ lưu trữ dữ liệu (S3, RDS, DynamoDB)  

---

# Trải nghiệm cá nhân (Personal Experience)
Buổi workshop cực kỳ hữu ích trong việc hiểu tổng thể bảo mật AWS:

- Các demo thực tế giúp khái niệm trở nên rõ ràng  
- Những sai lầm bảo mật thường gặp tại doanh nghiệp Việt Nam rất đáng lưu ý  
- IR playbook mang tính ứng dụng cao  
- Hiểu được mối liên kết giữa 5 trụ cột giúp thiết kế kiến trúc bảo mật toàn diện hơn  

---

# Takeaways
- Bảo mật là hành trình liên tục, không phải đích đến  
- Tự động hóa là chìa khóa để duy trì bảo mật ở quy mô lớn  
- Security Pillar cung cấp framework hoàn chỉnh  
- Cần thực hiện review bảo mật định kỳ  
- AWS cung cấp nhiều công cụ mạnh cho từng lĩnh vực bảo mật  

---

# Hình ảnh sự kiện

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/10.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/11.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/12.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/13.png)

![Photo](D:/_____________________TRUYEN/CloudRead-main/CloudRead-main/CloudRead-main/fcj-workshop-template-main/fcj-workshop-template-main/static/images/4-Events%20Participated/14.png)
