---
layout: pubs
title:  "GIF-FHE: A Comprehensive Implementation and Evaluation of GPU-Accelerated FHE with Integer and Floating-Point Computing Power"
brief:  "GIF-FHE: GPU-Accelerated FHE with Integer and Floating-Point Computing Power"
date:   2025-05-28
author: Fangyu Zheng
---

### Abstract

Fully Homomorphic Encryption (FHE) allows computations on encrypted data without revealing the plaintext, garnering significant interest from both academic and industrial communities. However, its broader adoption has been hindered by performance limitations. Consequently, researchers have turned to GPUs for efficient FHE implementation. Nevertheless, most have predominantly favored integer units due to their ease of use, overlooking the considerable computational potential of floating-point units in GPUs. Recognizing this untapped floating-point computational power, our paper introduces GIF-FHE, an extensive exploration and implementation of FHE, leveraging GPUs' integer and floating-point instructions for FHE acceleration. We develop a comprehensive suite of low-level and middle-level FHE primitives, offering multiple implementation variants with support for three word size configurations (64/52/32-bit). Particularly, we make innovative use of floating-point implementations, employing a novel methodology to efficiently leverage the floating-point unit's fused multiply-add (FMA) instructions. This represents the pioneering integration of floating-point units into FHE acceleration. To bridge our highly-optimized FHE primitives with practical applications, this paper also provides a high-level FHE implementation and interfaces that can be directly applied by upper-level applications such as neural network inference. Finally, we undertake a comprehensive experiment evaluation and comparison involving three types of arithmetic: FP64/INT64/INT32 with varying word size configurations and computation units. Notably, our fundamental function implementations consistently outperform counterparts on the same platform, achieving speedups ranging from 2.0× to 4.2×. In the context of CKKS FHE schemes, our homomorphic operation implementation surpasses the state-of-the-art GPU-based solution with a speedup of up to 3.8×, and exceeds the performance of the widely adopted CPU-based library, SEAL, with a remarkable speedup of over 300×.

### MLA Format

Zheng, Fangyu, Guang Fan*, Wenxu Tang, Yixuan Song, Tian Zhou, Yuan Zhao, Jiankuo Dong, Jingqiang Lin, Shoumeng Yan, and Jiwu Jing. "GIF-FHE: A Comprehensive Implementation and Evaluation of GPU-Accelerated FHE With Integer and Floating-Point Computing Power." IEEE Transactions on Parallel and Distributed Systems (2025).

[[Paper Download]](https://ieeexplore.ieee.org/abstract/document/11016794)

