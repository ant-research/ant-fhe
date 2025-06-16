---
layout: pubs
title:  "Towards Faster Fully Homomorphic Encryption implementation with integer and floating-point computing power of GPUs"
brief:  "FHE Acceleration with GPU Integer and Floating-Point Computing power"
date:   2023-05-19
author: Guang Fan
---

### Abstract

Fully Homomorphic Encryption (FHE) allows computations on encrypted data without knowledge of the plaintext message and currently has been the focus of both academia and industry. However, the performance issue hinders its large-scale application, highlighting the urgent requirements of high-performance FHE implementations. With noticing the tremendous potential of GPUs in the field of cryptographic acceleration, this paper comprehensively investigates how to convert the available computing resources residing in GPUs into FHE workhorses, and implement a full set of low-level and middle-level FHE primitives based on two arithmetic units (i.e., INT32 and FP64 units) with three types of data precision (i.e., INT32, INT64 and FP64). This paper gives a comprehensive evaluation and comparison based on each road-map. Our implementations of fundamental functions outperform the implementations on the same platform by 1.7× to 16.7×. Taking CKKS FHE schemes as a case study, our implementation of homomorphic multiplication achieves 3.2× speedup over the state-of-the-art GPU-based implementation, even considering the difference of platforms. The detailed evaluation and comparison of this paper would offer a vital reference for the follow-up work to choose appropriate underlying arithmetic units and important primitive optimizations in GPU-based FHE implementations.

### MLA Format

Fan, Guang, Fangyu Zheng*, Lipeng Wan, Lili Gao, Yuan Zhao, Jiankuo Dong, Yixuan Song, Yuewu Wang, and Jingqiang Lin. "Towards faster fully homomorphic encryption implementation with integer and floating-point computing power of GPUs." 2023 IEEE International Parallel and Distributed Processing Symposium (IPDPS). IEEE, 2023.

[[Paper Download]](https://ieeexplore.ieee.org/abstract/document/10177431)

