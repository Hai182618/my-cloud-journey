---
title: "Blog 3"
date: "2025-09-11"
weight: 3
chapter: false
pre: "<b> 3.3. </b>"
---

# Sử dụng Amazon Q Developer với các Plugin bên thứ ba

Bạn có thể hỏi cách Datadog hoạt động với các dịch vụ AWS, ví dụ:  
**@datadog how do I use APM on my EC2 instance?**

{{< figure src="/images/blog3/image1.png" title="Hình 1." >}}

---

## Truy xuất và tóm tắt các case và monitor

{{< figure src="/images/blog3/image2.png" title="Hình 2." >}}
{{< figure src="/images/blog3/image3.png" title="Hình 3." >}}

---

## Kiểm tra và liệt kê các monitor đang báo động

{{< figure src="/images/blog3/image4.png" title="Hình 4." >}}
{{< figure src="/images/blog3/image5.png" title="Hình 5." >}}

---

Bạn cũng có thể tiếp tục với câu hỏi như:  
**@datadog list some of the resources…**

{{< figure src="/images/blog3/image6.png" title="Hình 6." >}}
{{< figure src="/images/blog3/image7.png" title="Hình 7." >}}

---

## Xem các issue có mức độ nghiêm trọng (critical)

Bạn có thể yêu cầu Q Developer lấy danh sách các issue critical từ Wiz.  
Ví dụ: **@wiz list the issues with critical severity**

{{< figure src="/images/blog3/image8.png" title="Hình 8." >}}

---

## Tìm các tài nguyên quan trọng (critical resources)

{{< figure src="/images/blog3/image9.png" title="Hình 9." >}}

---

## Liệt kê các issue theo thuộc tính nhất định

Ví dụ: **@wiz what issues are due next?**

{{< figure src="/images/blog3/image10.png" title="Hình 10." >}}

---

## Đánh giá các issue liên quan đến lỗ hổng bảo mật (vulnerabilities)

Wiz theo dõi các lỗ hổng bên ngoài và các rủi ro liên quan tài nguyên của bạn.  
Ví dụ: **@wiz what are my issues that have been created in the last 7 days?**

{{< figure src="/images/blog3/image11.png" title="Hình 11." >}}

---

# Bắt đầu thiết lập Plugin

Để kích hoạt Plugin bên thứ ba trong Amazon Q Developer:

{{< figure src="/images/blog3/image12.png" title="Hình 12." >}}

1. **Datadog** – Tạo API key trong Datadog và cấu hình Site URL, API Key cho Q Developer.

{{< figure src="/images/blog3/image13.png" title="Hình 13." >}}

2. **Wiz** – Tạo Client ID và Secret theo tài liệu Wiz Service Account.

{{< figure src="/images/blog3/image14.png" title="Hình 14." >}}

---

# Kết luận

Bài viết giới thiệu cách Amazon Q Developer tương tác với plugin bên thứ ba qua tiền tố  
**@datadog** và **@wiz**, giúp cải thiện khả năng phân tích và hiệu suất vận hành.

{{< figure src="/images/blog3/image15.png" title="Hình 15. Tác giả Shardul Vaidya" >}}

Shardul Vaidya là Worldwide Partner Solutions Architect tại AWS, hỗ trợ khách hàng và đối tác xây dựng các trải nghiệm developer dựa trên Generative AI.
