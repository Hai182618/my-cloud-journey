---
title: "Blog 1"
date: "2025-09-11"
weight: 1
chapter: false
pre: "<b> 3.1. </b>"
---

# Mã hóa video trên Graviton vào năm 2025

Năm 2022, AWS công bố bài viết phân tích lợi thế khi chạy workload mã hóa video trên bộ xử lý Graviton. Graviton4 trên dòng C8g mang lại **hiệu năng cao hơn 30%** so với Graviton3, và nhanh hơn **12–15%** trong workload mã hóa video.

---

## Cải thiện hiệu năng trên x265

{{< figure src="/images/blog1/image1.png" title="Hình 1. So sánh hiệu năng C8g so với C7g." >}}

Các hàm tốn tài nguyên như SAD, convolution, DCT đã được tối ưu mạnh mẽ. Với SVE2, Graviton4 cải thiện nhiều nhất.

x265 v4.1 nhanh hơn **2.3–2.5 lần** so với v3.5.

{{< figure src="/images/blog1/image2.png" title="Hình 2. So sánh hiệu năng/chi phí FFmpeg giữa các loại instance." >}}

---

## Mẹo tối ưu hiệu năng trên Graviton

1. **Build từ source mới nhất**  
2. **Dùng compiler mới nhất (ưu tiên Clang)**  
3. **Clang tốt hơn GCC** đến **11%** trên C8g  

{{< figure src="/images/blog1/image3.png" title="Hình 3. Clang-18 vs GCC-13 trên C8g." >}}

---

## Instruction mới đem lại tối ưu hóa sâu hơn

Graviton3 hỗ trợ SVE; Graviton4 thêm **SVE2**.

Ví dụ trong hàm *saoCuStatsE0*:

- NEON: **nhanh hơn 2.7×**  
- SVE2: **nhanh hơn 3.2×**  

---

## HDR và video 10-bit

Cải thiện mã hóa 10-bit:

- **C8g:** +12%  
- **C7g:** +8%  
- **C6g:** +10%  

{{< figure src="/images/blog1/image4.png" title="Hình 4. Cải thiện mã hóa 10-bit." >}}

---

## Phương pháp Benchmark

- Tải toàn bộ nhân CPU  
- Dùng raw Y4M input  
- Tổng hợp FPS toàn workload  

---

## Kết luận

Graviton4:  
- **Nhanh hơn 12% so với Graviton3**  
- **Nhanh hơn 73% so với Graviton2**

Để tối ưu:

- Build encoder mới nhất  
- Ưu tiên Clang  
- Theo dõi cập nhật x265 & SVT-AV1  

---

**Tác giả:** *Jonathan Swinney – AWS (Annapurna Labs)*
