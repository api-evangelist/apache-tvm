---
title: Automating Optimization of Quantized Deep Learning Models on CUDA
url: https://tvm.apache.org/2019/04/29/opt-cuda-quantized
date: '2019-04-29'
author: Wuwei Lin
feed_url: https://tvm.apache.org/feed
---
Deep learning has been successfully applied to a variety of tasks. On real-time scenarios such as inference on autonomous vehicles, the inference speed of the model is critical. Network quantization is an effective approach to accelerating deep learning models. In quantized models, both data and model parameters are represented with low precision data types such as int8 and float16. The lowered data bandwidth reduces the inference time and memory/storage requirements, as well as the power consumption. Meanwhile, under proper quantization schemes, we can minimize the accuracy drops of the quantized models. Therefore, quantized models are of particular interests of researchers and developers as it makes large models suitable to deploy on diverse devices, such as GPU, CPU and mobile devices.
