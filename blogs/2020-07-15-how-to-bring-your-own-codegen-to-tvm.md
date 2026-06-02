---
title: How to Bring Your Own Codegen to TVM
url: https://tvm.apache.org/2020/07/15/how-to-bring-your-own-codegen-to-tvm
date: '2020-07-15'
author: Zhi Chen and Cody Yu, Amazon Web Services, Inc
feed_url: https://tvm.apache.org/feed
---
To free data scientists from worrying about the performance when developing a new model, hardware backend providers (e.g., Intel, NVIDIA, ARM, etc) either provide kernel libraries such as cuBLAS or cuDNN with many commonly used deep learning kernels, or provide frameworks such as DNNL or TensorRT with a graph engine to let users describe their models in a certain way to achieve high performance. In addition, emerging deep learning accelerators also have their own compilers, kernel libraries, or runtime frameworks.
