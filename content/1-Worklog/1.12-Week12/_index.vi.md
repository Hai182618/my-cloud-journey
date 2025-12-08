---
title: "Week 12 Worklog (VI)"
date: "2025-11-30"
weight: 12
chapter: false
pre: "<b>1.12.</b>"
---


### Mục tiêu tuần 12:
* Hoàn thiện pipeline dữ liệu từ ingestion → transform → analytics → dashboard.
* Củng cố kỹ năng thao tác AWS qua CloudShell, Console, SDK.
* Nâng cao khả năng xây dựng môi trường database và xử lý dữ liệu đầu cuối.

---

### Công việc thực hiện:

| Day | Task                                                                                                                                                                                                          | Start Date | Completion Date |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- |
| 78  | - Chuẩn bị database (Lab40-2.1) <br> - Xây dựng database (Lab40-2.2)                                                                                                   | 24/11/2025 | 24/11/2025      |
| 79  | - Kiểm tra dữ liệu trong bảng (Lab40-3.1) <br> - Phân tích chi phí (Lab40-3.2) <br> - Tagging & Cost Allocation (Lab40-3.3)                                           | 25/11/2025 | 25/11/2025      |
| 80  | - Usage Analysis (Lab40-3.4) <br> - Additional Result Query (Lab40-3.5) <br> - Clean Up Resources                                                                       | 26/11/2025 | 26/11/2025      |
| 81  | - CloudShell (Lab60-1) <br> - Console (Lab60-2) <br> - SDK (Lab60-3)                                                                                                    | 27/11/2025 | 27/11/2025      |
| 82  | - Tạo Cloud9 Instance <br> - Tải Dataset <br> - Upload Dataset lên S3                                                                                                   | 28/11/2025 | 28/11/2025      |
| 83  | - Thiết lập DataBrew <br> - Data Profiling <br> - Làm sạch & Transform dữ liệu                                                                                         | 29/11/2025 | 29/11/2025      |
| 84  | - Lab72-2 → Lab72-13: Toàn bộ vòng đời dữ liệu <br> - Lab73-3 → Lab73-5: Xây dựng, cải thiện và hoàn thiện Dashboard                                                   | 30/11/2025 | 30/11/2025      |

---

### Thành tựu tuần 12:

* Củng cố kỹ năng vận hành **database** bằng cách chuẩn bị và xây dựng một hệ thống database trên cloud, thiết kế bảng, cấu hình schema và kiểm tra dữ liệu mẫu để đảm bảo tính chính xác.

* Nâng cao nhận thức về **chi phí cloud** thông qua thực hành cost analysis:  
  * Hiểu chi phí phát sinh từ storage, compute, query  
  * Thực hành tagging và cost allocation để theo dõi và phân bổ chi phí hiệu quả  

* Thực hiện phân tích usage và chạy các truy vấn nâng cao trước khi dọn dẹp toàn bộ môi trường.

* Có kinh nghiệm thao tác AWS qua nhiều giao diện:
  * **CloudShell** (command line)  
  * **AWS Console** (UI)  
  * **AWS SDK** (programmatic access)  

* Xây dựng môi trường phát triển với **Cloud9**, tải dataset và đưa dữ liệu lên S3 phục vụ các bước xử lý tiếp theo.

* Nâng cao khả năng **data engineering** với AWS Glue DataBrew:  
  * Data Profiling  
  * Làm sạch dữ liệu  
  * Biến đổi dữ liệu (Transform)  

* Hoàn thành toàn bộ vòng đời dữ liệu (end-to-end data lifecycle) qua **Lab72**, bao gồm:

  **Ingest & Store**  
  * Thu thập và lưu dữ liệu vào S3  

  **Catalog**  
  * Phân loại và tạo metadata bằng Glue  

  **Transform**  
  * Glue interactive jobs  
  * Glue GUI jobs  
  * DataBrew transforms  
  * Xử lý phân tán bằng EMR  

  **Analyze**  
  * Athena queries  
  * Streaming analytics với Kinesis Data Analytics  

  **Visualize**  
  * Xây dashboard với Amazon QuickSight  

  **Serve**  
  * Xuất dữ liệu qua AWS Lambda  

  **Warehouse**  
  * Lưu trữ dữ liệu trong Amazon Redshift  

  **Dashboarding**  
  * Tạo, cải thiện và hoàn thiện dashboard BI  

* Hoàn thiện nhiều phiên bản dashboard, nâng cao kỹ năng:
  * Trực quan hóa  
  * Trình bày insight  
  * Tăng tính tương tác của dashboard  

