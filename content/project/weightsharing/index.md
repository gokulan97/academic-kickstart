---
title: Efficient convolution on GPUs by exploiting Quantization
summary: 
tags:
date: "2018-12-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: http://example.org

image:
  caption: Photo by Toa Heftiba on Unsplash
  focal_point: Smart
---
Implemented CUDA kernels to efficiently perform convolution in GPUs by Quantization. In quantized convolutional filter maps, weight values are redundant and can be `shared`, thereby reducing memory used. Overall, it was found that weight sharing did not provide any speedup over baseline model, owing to increase in book-keeping instructions needed for execution of convolution.
