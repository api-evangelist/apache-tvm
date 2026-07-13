---
title: "Bringing TVM into TensorFlow for Optimizing Neural Machine Translation on GPU"
url: "https://tvm.apache.org/2018/03/23/nmt-transformer-optimize"
date: "2018-03-23"
feed_url: "https://tvm.apache.org/rss.xml"
---
Author This is a guest blogpost contributed by Alibaba Group’s Machine Translation Platform team and PAI-Blade team Background Neural Machine Translation (NMT) is an end-to-end approach for automating translation, with the potential to overcome the weaknesses in conventional phrase-based translation systems. Recently, Alibaba Group is working on deploying NMT service for global e-commerce. Currently we are exploiting Transformer [1] as the major backbone in our NMT system since it is more friendly for efficient offline training with on-par (even higher) precison against classical RNN/LSTM-base
