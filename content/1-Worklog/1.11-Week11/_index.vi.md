---
title: "Week 11 Worklog (VI)"
date: "2025-11-23"
weight: 11
chapter: false
pre: "<b>1.11.</b>"
---


### Mục tiêu tuần 11:
* Nâng cao kỹ năng data engineering với S3, Firehose, Glue, Athena và QuickSight.
* Thực hành chuyên sâu với DynamoDB và mô hình NoSQL.
* Xây dựng kiến trúc serverless và event-driven thực tế.

---

### Công việc thực hiện trong tuần:

| Day | Task                                                                                                                                                                                                         | Start Date | Completion Date |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- |
| 71  | - Tạo S3 Bucket <br> - Tạo Delivery Stream (Kinesis Data Firehose)                                                                                                     | 17/11/2025 | 17/11/2025      |
| 72  | - Tạo Sample Data <br> - Tạo Glue Crawler <br> - Kiểm tra dữ liệu                                                                                                      | 18/11/2025 | 18/11/2025      |
| 73  | - Giải thích code (bản tiếng Việt) <br> - Cấu hình S3 Output <br> - Thiết lập Session Connect                                                                          | 19/11/2025 | 19/11/2025      |
| 74  | - Phân tích bằng Athena <br> - Trực quan hóa dữ liệu bằng QuickSight <br> - Dọn dẹp tài nguyên                                                                         | 20/11/2025 | 20/11/2025      |
| 75  | - Thực hành DynamoDB <br> - Khám phá DynamoDB <br> - Trải nghiệm giao diện DynamoDB Console                                                                            | 21/11/2025 | 21/11/2025      |
| 76  | - Backup DynamoDB <br> - Dọn dẹp môi trường <br> - Tìm hiểu Advanced Design Patterns for DynamoDB                                                                     | 22/11/2025 | 22/11/2025      |
| 77  | - Xây dựng & triển khai kiến trúc serverless đa vùng (Global Tables) <br> - Kiến trúc event-driven với DynamoDB Streams                                               | 23/11/2025 | 23/11/2025      |

---

### Thành tựu tuần 11:

* Củng cố nền tảng **data engineering** bằng việc tạo S3 bucket và xây dựng **Kinesis Firehose Delivery Stream**, nắm rõ quy trình ingestion dữ liệu thời gian thực.

* Phát triển kỹ năng tạo dữ liệu mẫu, thiết lập ingestion pipeline, và thực hiện phân tích dữ liệu.  
  Tạo **Glue Crawler** để phân loại dữ liệu và cập nhật Glue Data Catalog, đồng thời kiểm tra và xác thực schema.

* Nâng cao hiểu biết về ETL pipeline thông qua:
  * Giải thích logic code trong lab  
  * Lưu dữ liệu output vào S3  
  * Cấu hình session cho các tác vụ phân tích  

* Thực hiện đầy đủ quy trình phân tích dữ liệu với **Athena**, bao gồm chạy SQL trên dữ liệu S3, tối ưu truy vấn và kiểm tra kết quả.  
  Tiếp tục xây dashboard với **QuickSight** để củng cố kỹ năng BI.

* Thực hành tiêu chuẩn vận hành AWS bằng quy trình **clean up** toàn bộ tài nguyên.

* Xây dựng kiến thức từ cơ bản đến nâng cao về **DynamoDB**, bao gồm:
  * Tạo bảng  
  * Thao tác đọc/ghi  
  * Hiểu mô hình NoSQL và cách thiết kế cho ứng dụng tải cao  

* Hoàn thành thao tác **backup & restore** và học các mô hình thiết kế nâng cao như:
  * Single-table design  
  * Chiến lược partition key  
  * Tối ưu hiệu năng và chi phí  

* Xây dựng và triển khai **Global Serverless Architecture** với DynamoDB Global Tables, hỗ trợ replication đa vùng và tính sẵn sàng cao.

* Mở rộng sang **event-driven architecture** bằng cách tích hợp DynamoDB Streams với các dịch vụ serverless để xây dựng hệ thống phản ứng theo sự kiện, linh hoạt và dễ mở rộng.

