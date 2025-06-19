---
layout: pubs
title:  "coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation"
brief:  "coxHE: FPGA Acceleration for KeySwitch"
date:   2022-05-19
author: Mingqin Han
---

### Abstract

Data privacy becomes a crucial concern in the AI and big data era. Fully homomorphic encryption (FHE) is a promising data privacy protection technique where the entire computation is performed on encrypted data. However, the dramatic increase of the computation workload restrains the usage of FHE for the real-world applications. In this paper, we propose an FPFA accelerator design framework for CKKS-based HE. While the KeySwitch operations are the primary performance bottleneck of FHE computation, we propose a low latency design of KeySwitch module with reduced intra-operation data dependency. Compared with the state-of-the-art FPGA based key-switch implementation that is based on Verilog, the proposed high-level synthesis (HLS) based design reduces the operation latency by 40%. Furthermore, we propose an automated design space exploration framework which generates optimal encryption parameters and accelerators for a given application kernel and the target FPGA device. Experimental results for a set of real HE application kernels on different FPGA devices show that our HLS-based flexible design framework produces substantially better accelerator design compared with a fixed-parameter HE accelerator in terms of security, approximation error, and overall performance.

### MLA Format

Han, Mingqin, Yilan Zhu, Qian Lou, Zimeng Zhou, Shanqing Guo, Lei Ju. "coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation." 2022 Design, Automation & Test in Europe Conference & Exhibition (DATE). IEEE, 2022.

[[Paper Download]](https://ieeexplore.ieee.org/abstract/document/9774559) 