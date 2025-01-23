---
layout: post
date: 2024-10-29 15:59:00-0400
inline: true
related_posts: false
---

Our [arXiv preprint](https://arxiv.org/abs/2410.22269) proposes a new neural network layer, the Fourier head, which learns a continuous probability density function using Fourier series, and returns a discrete approximation of it. When to use it? Large language models are often adapted to model non-linguistic tokens. If these tokens have an underlying continuous structure, then replacing the linear classification head with the Fourier head can boost downstream performance. [Project page](https://nategillman.com/fourier-head)
