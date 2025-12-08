
---
title: "Blog 3"
date: "2024-11-13"
weight: 3
chapter: false
pre: "<b> 3.3. </b>"
---

# Plugin Amazon Q Developer hiện đã khả dụng trong AWS Management Console

Hôm nay, Amazon Web Services (AWS) công bố ra mắt và phát hành rộng rãi **plugin Amazon Q Developer** dành cho **Datadog** và **Wiz** trong AWS Management Console. Với các plugin này, người dùng có thể truy vấn Datadog và Wiz trực tiếp trong Amazon Q bằng ngôn ngữ tự nhiên, ví dụ:

- `@datadog do I have any active alerts?`
- `@wiz what are my top 3 security issues today?`

Điều này giúp giảm việc chuyển đổi công cụ và cải thiện năng suất cho kỹ sư và đội DevOps. Plugin Amazon Q Developer giúp hợp nhất thông tin vận hành vào **một giao diện duy nhất**.

---

## Plugin Q Developer hoạt động như thế nào?

Amazon Q Developer sử dụng tiền tố trong truy vấn (`@datadog`, `@wiz`) để định tuyến yêu cầu đến plugin tương ứng. Quy trình bao gồm:

1. **Nhận diện ý định (Intent Recognition)**  
2. **Gọi API** (không gửi dữ liệu AWS hay nội dung prompt ra ngoài)  
3. **Tạo phản hồi (Response Generation)**  
4. **Kiểm tra an toàn (Guardrails)** bảo đảm kết quả đúng chuẩn  

Điều này cho phép Q Developer hiểu yêu cầu và đưa ra thông tin vận hành chính xác.

---

# Plugin Amazon Q Developer cho Datadog

Datadog cung cấp khả năng quan sát theo thời gian thực. Với tiền tố **@datadog**, bạn có thể truy vấn dữ liệu giám sát ngay trong AWS Console.

---

## Sử dụng Datadog APM trên EC2

Ví dụ truy vấn:  
`@datadog how do I use APM on my EC2 instance?`

{{< figure src="/images/blog3/Datadog-APM-1.gif" caption="Sử dụng Q Developer để hỏi về Datadog APM trên EC2." >}}

---

## Truy xuất & tóm tắt Cases và Monitors

{{< figure src="/images/blog3/Datadog-Cases-1.gif" caption="Liệt kê tất cả Datadog cases." >}}

{{< figure src="/images/blog3/Datadog-Top-Cases-1.gif" caption="Tóm tắt top cases trong Datadog." >}}

---

## Kiểm tra & liệt kê Monitors cảnh báo

{{< figure src="/images/blog3/Datadog-Monitors-1.gif" caption="Liệt kê tất cả monitors trong Datadog." >}}

{{< figure src="/images/blog3/Datadog-Alarms-1.gif" caption="Không có cảnh báo nào đang kích hoạt." >}}

---

# Plugin Amazon Q Developer cho Wiz

Wiz hỗ trợ quản lý tư thế bảo mật và phân tích rủi ro trên hạ tầng cloud. Với **@wiz**, bạn có thể xem lỗ hổng, mức độ nghiêm trọng và tình trạng bảo mật của tài nguyên.

---

## Xem các vấn đề mức độ nghiêm trọng cao

{{< figure src="/images/blog3/Wiz-top-5-critical-res-1.gif" caption="Wiz hiển thị các issue nghiêm trọng nhất." >}}

---

## Tìm tài nguyên có rủi ro cao

{{< figure src="/images/blog3/Wiz-critical-resources-1.gif" caption="Danh sách tài nguyên bị đánh giá rủi ro cao." >}}

---

## Liệt kê các vấn đề theo thuộc tính

{{< figure src="/images/blog3/Wiz-due-next-1.gif" caption="Các issue sắp đến hạn." >}}

{{< figure src="/images/blog3/Wiz-due-soon-1.gif" caption="Các issue mới phát sinh gần đây." >}}

---

# Bắt đầu sử dụng

Để kích hoạt plugin bên thứ ba trong Amazon Q Developer:

1. Đăng ký **Amazon Q Developer Pro Tier**  
2. Tạo **Amazon Q Administrator Role/User**  
3. Mở tab **Plugins** trong Amazon Q Developer Console  
4. Cung cấp thông tin kết nối Datadog và Wiz (được lưu trong AWS Secrets Manager)

{{< figure src="/images/blog3/Q-Dev-Dashboard.png" caption="Giao diện Amazon Q Developer với mục Plugins." >}}

---

## Cấu hình Datadog Plugin

{{< figure src="/images/blog3/Datadog-Plugin.png" caption="Màn hình cấu hình Datadog plugin." >}}

{{< figure src="/images/blog3/Datadog-integration.png" caption="Trang thiết lập API key của Datadog." >}}

---

## Cấu hình Wiz Plugin

{{< figure src="/images/blog3/Wiz-Plugin.png" caption="Màn hình cấu hình plugin Wiz." >}}

{{< figure src="/images/blog3/Wiz-Intergation.png" caption="Wiz credentials: Client ID, Secret, and Endpoint." >}}

---

# Truy vấn Plugins

Bạn có thể chạy các truy vấn trực tiếp trong Amazon Q:

````txt
@datadog list my current monitors
@wiz list the issues with critical severity
@datadog summarize my top cases
@wiz what issues are due next?
````

Các truy vấn này cho phép bạn thu thập nhanh thông tin cảnh báo, sự cố, mức độ rủi ro và tình trạng bảo mật trên hệ thống.

---

# Kết luận

Plugin Amazon Q Developer cho Datadog và Wiz giúp kỹ sư quan sát và đánh giá tình trạng hạ tầng mà không cần đổi công cụ. Bằng cách hợp nhất thông tin vận hành, plugin giúp tăng hiệu quả xử lý sự cố và cải thiện năng suất làm việc.

---

{{< figure src="/images/blog3/Profile_pic.jpg" caption="Tác giả: Shardul Vaidya" >}}
