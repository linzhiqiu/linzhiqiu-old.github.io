---
cover: false
layout: project
title: 'QPyTorch'
date: 19 Oct 2019
image: /assets/img/projects/qpytorch/qpytorch.jpg
screenshot: /assets/img/projects/qpytorch/qpytorch.jpg
links:
  - title: Code
    url: https://github.com/Tiiiger/QPyTorch
  - title: Paper
    url: https://arxiv.org/abs/1910.04540
  - title: Poster
    url: assets/projects/qpytorch/zhang_qpytorch_poster.pdf
caption: |
  NeurIPS 2019 Workshop @ EMC2
description: |
  [Tianyi Zhang](https://tiiiger.github.io), [Zhiqiu Lin](https://linzhiqiu.github.io), [Guandao Yang](https://www.guandaoyang.com), [Chris De Sa](http://www.cs.cornell.edu/~cdesa/)

# accent_color: '#4fb1ba'
# accent_image:
#   background: 'linear-gradient(to bottom,#193747 0%,#233e4c 30%,#3c929e 50%,#d5d5d4 70%,#cdccc8 100%)'
#   overlay:    true
---

Low-precision training reduces computational cost and produces efficient models. Recent research in developing new low-precision training algorithms often relies on simulation to empirically evaluate the statistical effects of quantization while avoiding the substantial overhead of building specific hardware. To support this empirical research, we introduce QPyTorch, a low-precision arithmetic simulation framework. Built natively in PyTorch, QPyTorch provides a convenient interface that minimizes the efforts needed to reliably convert existing codes to study low-precision training. QPyTorch is general, and supports a variety of combinations of precisions, number formats, and rounding options. Additionally, it leverages an efficient fused-kernel approach to reduce simulator overhead, which enables simulation of large-scale, realistic problems.