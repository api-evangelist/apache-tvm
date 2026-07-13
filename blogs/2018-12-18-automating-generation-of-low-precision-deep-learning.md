---
title: "Automating Generation of Low Precision Deep Learning Operators"
url: "https://tvm.apache.org/2018/12/18/lowprecision-conv"
date: "2018-12-18"
feed_url: "https://tvm.apache.org/rss.xml"
---
As deep learning models grow larger and more complex, deploying them on low powered phone and IoT devices becomes challenging because of their limited compute and energy budgets. A recent trend in deep learning is the use of extremely quantized models that operate on inputs and weights of a few bits, with networks like XNOR-Net, DoReFa-Net, and HWGQ-Net making steady progress improving accuracy. An example of a low precision graph snippet is below.
