---
layout: page
title: Comparing the Performance of DASH over HTTP/2 vs. HTTP/3
description: Quantifying how well the latest HTTP protocol handles adaptive multimedia streaming.
img: assets/img/WIP.jpeg
importance: 3
category: Projects
---

HTTP/3 is the latest iteration of the HTTP protocol, which relies on QUIC as its transport layer protocol instead of good old TCP. With the use of QUIC, HTTP/3 arguably saves more time with faster handshakes and other gains, especially on lossy connections. 

Dynamic Adaptive Streaming over HTTP (DASH) is a multimedia streaming protocol that basically adapts to the quality of the internet connection. It's currently being used by most big tech including YouTube, Netflix, Hulu, etc.

This project aims to implement the DASH video streaming algorithm in HTTP/3 and compare its quantitative performance with its HTTP/2 counterpart.
