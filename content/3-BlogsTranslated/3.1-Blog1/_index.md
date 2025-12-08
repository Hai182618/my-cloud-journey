---
title: "Blog 1"
date: "2025-09-11"
weight: 1
chapter: false
pre: "<b> 3.1. </b>"
---

# Video Encoding on Graviton in 2025

In 2022, we published a post describing the advantages of running video encoding workloads on AWS Graviton processors. Since that time, AWS launched Graviton4 powered C8g instances which offer up to 30% better performance than Graviton3. On video encoding workloads, Graviton4 performs 12–15% better than Graviton3, depending on the encoder.

---

## Performance Improvements on x265

{{< figure src="/images/blog1/image1.png" title="Figure 1. Percent improvement comparing C8g vs C7g." >}}

Contributions to x265 improved performance across encoding presets. Some of the most time-consuming functions—SAD, convolution, DCT—were optimized, resulting in significant gains. Graviton4, with SVE2, shows the strongest improvements.

These graphs show the improvement of x265 v4.1 over 3.6. From 3.5 to 4.1, performance increased **2.3–2.5×**.

{{< figure src="/images/blog1/image2.png" title="Figure 2. Price-performance comparison for FFmpeg workloads." >}}

---

## Tips to Maximize Performance on Graviton

1. **Build from latest source** (x265 and SVT-AV1 improve frequently).  
2. **Use the newest compiler** (Clang-17+ recommended).  
3. **Prefer Clang over GCC** — up to **11% improvement** on C8g.

{{< figure src="/images/blog1/image3.png" title="Figure 3. Clang-18 vs GCC-13 performance on C8g." >}}

---

## New Instruction Support Enables More Optimizations

Graviton3 introduced SVE; Graviton4 added **SVE2**, simplifying SIMD code and enabling new optimizations.

Example:  
The function *saoCuStatsE0* in x265 gains:

- **2.7×** faster with NEON  
- **3.2×** faster with SVE2  

This is achieved by replacing five compare + five SADALP operations with a single **histseg** instruction.

---

## HDR and 10-bit Video

10/12-bit content requires twice the SIMD compute of 8-bit. Major progress has been made for x265 and SVT-AV1:

- **C8g:** +12%  
- **C7g:** +8%  
- **C6g:** +10%

{{< figure src="/images/blog1/image4.png" title="Figure 4. 10-bit encoding improvements across Graviton generations." >}}

---

## Benchmarking Method

- Workloads fully loaded all cores.  
- Used raw Y4M input encoded with x264/x265/SVT-AV1.  
- FPS aggregated across all processes.

---

## Conclusion

Graviton4 provides:

- **12% faster than Graviton3**  
- **73% faster than Graviton2**  

To maximize performance:

- Use the latest encoder builds  
- Prefer Clang  
- Monitor contributions to x265 & SVT-AV1  

---

**Author:** *Jonathan Swinney – AWS (Annapurna Labs)*
