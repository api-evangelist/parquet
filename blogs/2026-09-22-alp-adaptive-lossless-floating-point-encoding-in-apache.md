---
title: "ALP: Adaptive Lossless Floating-Point Encoding in Apache Parquet"
url: "/blog/2026/09/22/alp-adaptive-lossless-floating-point-encoding-in-apache-parquet/"
date: "2026-09-22"
feed_url: "https://parquet.apache.org/blog/index.xml"
---
Apache Parquet has added the Adaptive Lossless floating-Point (ALP) Encoding – a new lightweight floating-point encoding with compression ratios similar to zstd , much faster decompression, random-access support, and GPU- and SIMD-friendly decoding. ALP works best for decimal values stored as floating-point types (32-bit FLOAT and 64-bit DOUBLE ), such as Monetary values (exchange rates, public funds, stocks, prices, etc.) – e.g., 1.2345 or 22.03 Geographic coordinates (longitude/latitude) – e.g., 42.3584 , -71.0598 Scientific measurements (temperature, pressure, speed, degrees, etc.) – e.g., 
