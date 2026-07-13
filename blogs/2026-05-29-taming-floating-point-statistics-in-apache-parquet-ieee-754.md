---
title: "Taming Floating-Point Statistics in Apache Parquet: IEEE 754 Total Order and NaN Counts"
url: "/blog/2026/05/29/taming-floating-point-statistics-in-apache-parquet-ieee-754-total-order-and-nan-counts/"
date: "2026-05-29"
feed_url: "https://parquet.apache.org/blog/index.xml"
---
Column statistics are the secret to Apache Parquet’s blazing fast performance. By storing compact summaries—like min , max , and null counts—for row groups, column chunks, and pages, readers can easily skip irrelevant data that doesn’t match a query. However, floating-point values throw a wrench into this simple model.
