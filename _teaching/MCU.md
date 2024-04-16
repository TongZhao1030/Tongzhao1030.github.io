---
title: "Micro Control Unit Design and Optimization Based on ARM Architecture"
collection: teaching
type: "Advised by Prof. Jianhao Hu and Prof. Kaining Han"
permalink: /teaching/MCU
venue: "National Key Laboratory of Wireless Communications"
date: 2023-07-01
location: "National Key Laboratory of Wireless Communications"
---

Our design objective is to develop an MCU based on the ARM architecture capable of successfully computing convolutions of two-dimensional 32-bit vectors with dimensions of 16. The MCU operates at the behavioral level input and necessitates support for fundamental ARM instructions such as ADD, SUB, AND, OR, MOV, LDR, STR, B/BL, etc. To facilitate computations, we extended the instruction set to include multiplication (MUL) and assignment (MOV) instructions, and developed a custom multiplier module for higher operational speed. Additionally, we performed a series of optimizations on the assembly instructions.

![image](https://github.com/TongZhao1030/Tongzhao1030.github.io/assets/164134563/9d5882df-5796-45df-b9af-0f0ffe13a975 "Data Path of MCU")


Ultimately, we successfully completed testing of basic MCU instructions, simulation of convolution operations, and on-board testing, with all results being accurate. On-board testing indicated that, at a frequency of 49MHz, we completed one convolution operation in 393 clock cycles, achieving an operational speed of 148,000 convolutions per second.

For code and more details, please see this [GitHub repository](https://github.com/TongZhao1030/MCU).
