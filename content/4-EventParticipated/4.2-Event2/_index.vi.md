---
title: "Tham Gia Sự Kiện – AWS DevOps Bootcamp"
date: "2025-11-17"
weight: 2
chapter: false
pre: "<b>2.</b>"
---

## Sự kiện 2 – HỘI THẢO DEVOPS TRÊN AWS

## Thông tin sự kiện
**Thời gian:** Thứ Hai, 17/11/2025, 8:30 AM – 5:00 PM  
**Địa điểm:** Văn phòng AWS Việt Nam  
**Vai trò:** Người tham dự  

---

## Mục đích sự kiện
Workshop được thiết kế nhằm cung cấp kiến thức toàn diện và trải nghiệm thực hành với các dịch vụ DevOps của AWS, bao gồm CI/CD pipelines, Infrastructure as Code, container services và giám sát – quan sát hệ thống. Mục tiêu là giúp người tham dự hiểu văn hóa, nguyên tắc DevOps và các best practice, đồng thời khám phá cách triển khai DevOps thực tế trên AWS.

---

# Tổng quan chương trình

## Buổi sáng (8:30 AM – 12:00 PM)

### **8:30 – 9:00 AM | Chào mừng & Tư duy DevOps**
- Ôn lại buổi AI/ML từ workshop trước  
- Văn hóa và nguyên tắc DevOps: sự chuyển đổi từ IT truyền thống sang DevOps, tập trung vào cộng tác, tự động hóa, cải tiến liên tục  
- Lợi ích và các chỉ số chính:
  - DORA Metrics: Deployment Frequency, Lead Time, MTTR, Change Failure Rate  
  - MTTR – Thời gian phục hồi trung bình  
  - Deployment Frequency – Tần suất triển khai phần mềm  
- Thảo luận về cách DevOps cải thiện quy trình phần mềm và vận hành  

---

### **9:00 – 10:30 AM | Dịch vụ DevOps của AWS – CI/CD Pipeline**

## Quản lý mã nguồn: AWS CodeCommit, Chiến lược Git
### AWS CodeCommit
- Dịch vụ Git fully-managed, bảo mật cao  

### Chiến lược Git
- GitFlow: Feature, develop, release branches  
- Trunk-based Development: Nhánh chính + nhánh ngắn hạn  
- Best practices tùy theo quy mô đội và dự án  

---

## Build & Test: Cấu hình CodeBuild, Testing Pipelines

### AWS CodeBuild
- Build mã nguồn, chạy test, tạo artifact  

### Build Configuration
- Buildspec  
- Environment variables  
- Build artifact  

### Testing Pipelines
- Unit test, integration test, test tự động  
- Tích hợp với framework test và chất lượng mã  

---

## Deployment: CodeDeploy với Blue/Green, Canary, Rolling
- Blue/Green: Zero downtime  
- Canary: Triển khai cho một phần nhỏ người dùng  
- Rolling updates: Triển khai dần theo batch  
- Chọn chiến lược phù hợp ứng dụng  

---

## AWS CodePipeline – Điều phối CI/CD
- Pipeline các giai đoạn: Source → Build → Test → Deploy → Approval  
- Kết nối CodeCommit, CodeBuild, CodeDeploy  
- Trigger tự động, chạy song song, giao diện trực quan  

---

### **Demo: CI/CD Pipeline hoàn chỉnh**
Bao gồm:

1. Tạo repo CodeCommit  
2. Cấu hình CodeBuild  
3. Triển khai ứng dụng với Blue/Green qua CodeDeploy  
4. Tạo CodePipeline  
5. Test pipeline bằng thay đổi mã nguồn → tự động triển khai  

---

### **10:30 – 10:45 AM | Nghỉ giải lao**

---

## **10:45 AM – 12:00 PM | Infrastructure as Code (IaC)**

## AWS CloudFormation
- Template JSON/YAML  
- Stacks  
- Drift detection  
- Change sets & rollback  
- Best practices: tổ chức template, parameterization, nested stacks  

---

## AWS CDK (Cloud Development Kit)
- Xây dựng hạ tầng bằng TypeScript, Python, Java, C#, Go  
- Constructs: thành phần dùng lại  
- Pattern dựng sẵn: VPC, ECS, serverless  
- Lợi ích: type safety, IDE support, dễ test  

---

### **Demo: CloudFormation vs CDK**
- Triển khai VPC + EC2 bằng YAML  
- Triển khai tương tự bằng CDK TypeScript  
- So sánh maintainability & developer experience  

---

### **Thảo luận: Chọn CloudFormation hay CDK**
- Dựa trên kinh nghiệm đội ngũ, độ phức tạp, yêu cầu bảo trì  
- Hybrid approaches cho từng phần hạ tầng  

---

## **Nghỉ trưa (12:00 – 1:00 PM)**

---

# Buổi chiều (1:00 – 5:00 PM)

## **1:00 – 2:30 PM | Dịch vụ Container trên AWS**

### Docker Fundamentals
- Khái niệm container, image  
- Microservices  
- Dockerfile, build image, lifecycle  
- Lợi ích: portability, consistency, resource efficiency  

---

## Amazon ECR
- Lưu trữ image bảo mật  
- Quét lỗ hổng tự động  
- Lifecycle policies  
- Tích hợp ECS/EKS  

---

## Amazon ECS & EKS
### ECS
- Orchestration fully-managed  
- Task definitions, services, scaling  
- Rolling & Blue/Green  

### EKS
- Kubernetes managed  
- Pods, services, deployments  
- Add-ons, node groups  
- Canary với Istio/App Mesh  
- Autoscaling (cluster + horizontal)  

---

## AWS App Runner
- Deployment container đơn giản  
- Auto-scaling  
- Dùng cho web/app/API  
- So sánh App Runner vs ECS vs EKS  

---

### Demo & Case Study: Triển khai Microservices
- Deploy qua App Runner  
- Deploy qua ECS Fargate  
- So sánh chi phí, độ phức tạp, vận hành  
- Case study chọn dịch vụ phù hợp  

---

### **2:30 – 2:45 PM | Nghỉ giải lao**

---

## **2:45 – 4:00 PM | Monitoring & Observability**

## Amazon CloudWatch
- Metrics  
- Logs  
- Alarms  
- Dashboards  
- Best practices  

---

## AWS X-Ray
- Distributed tracing  
- Service maps  
- Tối ưu hiệu năng  
- SDK integration  

---

### Demo: Thiết lập Observability
- CloudWatch metrics + logs  
- Dashboards  
- Alarms  
- X-Ray tracing  
- Phân tích trace  

---

## Best Practices
- Chiến lược cảnh báo  
- Dashboard theo đối tượng (dev/ops/management)  
- Quy trình on-call  
- SLO/SLI  

---

## **4:00 – 4:45 PM | DevOps Best Practices & Case Studies**

### Chiến lược triển khai
- Feature flags  
- A/B testing  
- AppConfig, LaunchDarkly  

### Automated Testing
- Testing pyramid  
- Test automation trong CI/CD  
- Quality gates  
- Coverage  

### Incident Management
- Detection → Response → Recovery  
- Postmortem không đổ lỗi  
- Cải tiến hệ thống  

### Case Studies
- Startup: tăng trưởng nhanh, tối ưu chi phí  
- Enterprise: chuyển đổi quy mô lớn  
- ROI của DevOps  

---

## **4:45 – 5:00 PM | Q&A & Tổng kết**
- Lộ trình nghề DevOps  
- Chứng chỉ AWS phù hợp  
- Tài nguyên học tập  
- Tổng kết nội dung chính  

---

# Điểm nổi bật
- Tự động hóa CI/CD với CodePipeline  
- IaC mạnh mẽ với CloudFormation & CDK  
- Nhiều lựa chọn container phù hợp từng trường hợp  
- CloudWatch + X-Ray cho observability toàn diện  
- Thành công DevOps phụ thuộc văn hóa  
- Best practices: feature flags, test automation, incident management  

---

# Bài học chính
- DevOps bắt đầu từ văn hóa  
- CI/CD cải thiện tốc độ & độ ổn định  
- IaC mang lại tính lặp lại và kiểm soát phiên bản  
- Chiến lược container phải phù hợp đội ngũ  
- Monitoring/Observability là bắt buộc  
- DevOps là quá trình học tập liên tục  

---

# Ứng dụng vào công việc
- Thiết lập CI/CD  
- Áp dụng IaC  
- Triển khai container  
- Tối ưu giám sát  
- Áp dụng nguyên tắc DevOps  
- Xây dựng quy trình sự cố  

---

# Trải nghiệm cá nhân
- Demo CI/CD rất giá trị  
- So sánh IaC giúp hiểu rõ khi nào dùng CDK/CFN  
- Container services được phân tích rõ ràng  
- Observability giúp hiểu tầm quan trọng của monitoring  
- Case studies thực tế rất hữu ích  
- Hướng nghiệp DevOps rõ ràng hơn  

---

# Takeaways
- Bắt đầu nhỏ, cải tiến dần  
- Văn hóa quan trọng hơn công cụ  
- Chọn đúng công cụ đúng việc  
- Giám sát mọi thứ  
- Học liên tục  
- Dùng DORA metrics để đo hiệu quả  

---

# Hình ảnh sự kiện

![Event photo](/images/6.png)
![Event photo](/images/7.png)
![Event photo](/images/8.png)
![Event photo](/images/9.png)
