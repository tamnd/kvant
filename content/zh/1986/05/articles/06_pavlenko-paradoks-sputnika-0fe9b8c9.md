---
id: 1986-5-pavlenko-paradoks-sputnika-0fe9b8c9
issue: kvant_1986_5
year: 1986
number: "5"
title: 卫星悖论
authors:
  - Павленко Ю. Г.
rubric: raznoe
page_first: 16
page_last: 16
tag: EM9W
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4349b953335426e17a594d311fa43b2bdc4a443ccadb41c2c53d01c004c51866
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/06_pavlenko-paradoks-sputnika-0fe9b8c9.md
source_content_sha256: 8cdcc84d9235bf6763a9f1416138edc2481119fa062970e8082802f609ae876e
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

卫星悖论

物理和数学科学候选人
Y·G·帕夫连科

当人造地球卫星在大气层上层移动时，它们会受到空气的制动作用。在卫星发射之前，通过地球物理火箭的飞行获得了200公里以内的大气密度信息。后来，对卫星运动的分析使得澄清这些数据成为可能（它们显示在分布的“表格”中）。

卫星在大气层上层受到的阻力是由stolnova产生的

与空气分子。该力的方向与速度相反，可以写为
$$\vec{F}_c = -k\vec{v},$$
其中系数$k$为正，一般来说，它本身取决于速度。物体的横截面积$S$越大，大气的密度$\rho$就越大。

让我们比较阻力和吸引力赋予卫星的加速度的大小。假设一颗质量为 $m=100$ kg 的卫星，其形状为球体，横截面为$S=1$ m$^2$，在高度为 $h=160$ km 的圆形轨道上以$v=8$ km/s 的速度运行。对于近似计算，我们可以假设$k=S/v$。在这种情况下，加速度的横轴值由阻力决定，
$$a_c = \frac{kv}{m} \approx \frac{S_0v^2}{m} \approx 6.4 \cdot 10^{-4} \text{ m/c}^2.$$
从地球作用在卫星上的引力$F = G \frac{Mm}{(R+h)^2}$（$M=5976 \cdot 10^{21}$ kg 是地球的质量，$R=6371$ km 是其平均半径），赋予卫星一个指向地球中心的加速度，等于
$$a_n = G \frac{M}{(R+h)^2} \approx 9.33 \text{ m/c}^2.$$
正如您所看到的，“制动”加速度大约是向心加速度的十五分之一。然而，160公里高度大气层的影响是如此之大，以至于卫星在完成一两圈后就开始快速旋转。

苏联第一颗卫星呈球状，直径58厘米，质量83.6公斤。运载火箭的尺寸明显更大。看来，由于火箭经历了高阻力（它有更多的$S$），进入轨道后它应该落后于卫星。然而，据观察，运载火箭明显领先于卫星。让我们试着理解这个“悖论”。

目前，卫星的运动是根据牛顿定律在计算机上计算的。在阻力取决于身体速度的情况下，要解决这个问题，学校的数学知识是不够的。我们面临着基于能源信息的卫星的“悖论”。如果没有阻力，则卫星的总机械能$E$

将保持不变：
$$E = \frac{mv^2}{2} + \left(-G \frac{Mm}{r}\right) = \text{const}$$
（这里$\left(-G \frac{Mm}{r}\right)$是位于
