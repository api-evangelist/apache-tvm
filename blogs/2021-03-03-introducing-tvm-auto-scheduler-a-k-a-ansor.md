---
title: Introducing TVM Auto-scheduler (a.k.a. Ansor)
url: https://tvm.apache.org/2021/03/03/intro-auto-scheduler
date: '2021-03-03'
author: Lianmin Zheng, Chengfan Jia, Minmin Sun, Zhao Wu, Cody Hao Yu
feed_url: https://tvm.apache.org/feed
---
Optimizing the execution speed of deep neural networks is extremely hard with the growing model size, operator diversity, and hardware heterogeneity. From a computational perspective, deep neural networks are just layers and layers of tensor computations. These tensor computations, such as matmul and conv2d, can be easily described by mathematical expressions. However, providing high-performance implementations for them on modern hardware can be very challenging. We have to apply various low-level optimizations and utilize special hardware intrinsics to achieve high performance. It takes huge engineering effort to build linear algebra and neural network acceleration libraries like CuBLAS, CuDNN, oneMKL, and oneDNN.
