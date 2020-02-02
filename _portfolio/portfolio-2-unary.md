---
title: "UnarySim"
excerpt: "Unary computing utilizes serial bit stream as data representation, with which both the system latency and the hardware comsumption can be reduced. Exploring the efficient unary computing kernel and automate the deployment is appealing for real world appliciations."
collection: portfolio
---

Unary computing applies unary bit streams as internal data, and mitigates the conversion of data from unary to binary in converntional computers, leading to less system-level latency, as in the diagram below.

<br/><img src='/images/unary_system_diagram.png'>

Currently, unary computing has already been applied to low-density parity-check code, image processing and machine learning. We create [UnarySim](https://github.com/diwu1990/UnarySim) to accurately simulate the behavior of unary computing at cycle level. There are some related publications listed below.

__Related publications:__

2. "uGEMM: Unary Computing Architecture for GEMM Applications", submitted to _ISCA_ 2020.
1. "In-Stream Stochastic Division and Square Root via Correlation", in _DAC_ 2019. [[link](https://diwu1990.github.io/publication/2019-06-02-dac)]