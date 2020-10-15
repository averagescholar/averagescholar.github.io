---
layout: post
title: Image as a function
date:   2020-10-15 14:04:37 +1100
categories: vision
tags: ["vision udacity"]
mathjax: true
---

### Image as a function
- Give value at some position of the image $$I(x,y)$$
- Gray Image: $$R^2 \rightarrow R$$
- RGB Image: $$R^2 \rightarrow R^3$$
- How to store an image so that computer can understand it ? -> Digital image
- From real image to digital image: Quantization
- Image is a function => we can have linear operation on functoin: addition, subtraction, multiply, division. Pay attention to  the scale of the image. The value could be cropped when exceed the threshold. 
- Application?: Blend images
- Noise in image: Sometimes, for some reasons, iamges have some noises in it. $$I'(x,y)=I(x,y)+n(x,y)$$
- Question: How can we reduce the noise?
- But, what are noises in image? Salt and pepper noise, Gausian noise.
- The effect of sigma on Gaussian noise.