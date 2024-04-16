---
title: "Whirlwind -  An Automatic Ball-Picking Robot"
collection: teaching
type: "Advised by Prof. Xiang Li"
permalink: /teaching/Whirlwind
venue: "School of Aeronautics and Astronautics, UESTC"
date: 2023-03-01
location: "Chengdu, China"
---

The robot control component of this project consists of a visual recognition module (K210) and a mechanical control module (Arduino core board). The primary task of the recognition module is to load a pre-trained visual recognition network, extract images from real-time images, pass the images into the visual recognition network to obtain recognition results, and then pass them to the control module. The main task of the control module is to accept parameters transmitted by the recognition module, convert them into control signals for various parts of the robot through algorithms, and implement functions such as ball searching, steering, motion, and ball picking. You can refer to [this video](https://www.bilibili.com/video/BV1ns4y1y7rU) for the robot's performance.

![image](https://github.com/TongZhao1030/Tongzhao1030.github.io/assets/164134563/9772756d-e12f-4561-bfff-183139268bcf "The overall structure diagram")

For code and more details, please see this [GitHub repository](https://github.com/TongZhao1030/Whirlwind).
