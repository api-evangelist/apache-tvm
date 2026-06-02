---
title: Integrating TVM into PyTorch
url: https://tvm.apache.org/2019/05/30/pytorch-frontend
date: '2019-05-30'
author: Bram Wasti
feed_url: https://tvm.apache.org/feed
---
As TVM continuously demonstrates improvements to the efficiency of deep learning execution, it has become clear that PyTorch stands to benefit from directly leveraging the compiler stack. A major tenet of PyTorch is providing seamless and robust integrations that don’t get in the user’s way. To that end, PyTorch now has an official TVM-based backend, torch_tvm.
