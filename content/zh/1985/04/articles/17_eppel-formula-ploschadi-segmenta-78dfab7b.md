---
id: 1985-4-eppel-formula-ploschadi-segmenta-78dfab7b
issue: kvant_1985_4
year: 1985
number: "4"
title: 线段面积公式
authors:
  - Эппель Б. С.
rubric: smes
page_first: 48
page_last: 48
page_labels: "46"
tag: XYF9
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f781ccaa8f377bcc2eec5a26a88799d53f8e6ee93322882e0d503681dbdb2b85
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/17_eppel-formula-ploschadi-segmenta-78dfab7b.md
source_content_sha256: e05c471fd0853ac2408eacb85220d65674c0e55df44037bd89ed8f10983a3518
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

F912。超导线线圈中产生直流电，该线圈通过开关$K_1$（参见图）连接到电流源。此后，将两个并联的相同电容器组成的电池连接到线圈的末端。开关$K_1$打开，之后电流开始流过电容器，对它们充电。在电容器上的电压最大、电流为零的时刻，双开关$K_2$从基极1切换到基极2，使电容器串联，线圈上的电压加倍。由于线圈的电感没有改变，但电压增加了，因此通过线圈的最大电流以及存储的能量将大于第一个类似的线圈。找出上述计算中的错误。

线段面积公式

线段$AnB$ (图 1) 的面积可以使用以下公式求得

$$S_{\text{сегм}} = \frac{\pi R^2}{360^\circ} \cdot a - \frac{R^2}{2} \sin a,$$

(1)

其中圆心角$\alpha$以度表示；或者，如果相同的弧度角为 $\varphi$，则通过公式

$$S_{\text{сегм}} = \frac{R^2}{2} (\varphi - \sin \varphi).$$

(2)

公式（1）很容易推导：线段$AnB$的面积等于扇形$OAnB$（$\frac{\pi R^2}{360^\circ} \cdot a$，即1度扇形的面积，乘以度数）与三角形$OAB$（$\left(R^2/2\right) \sin a$）的面积之差。

这个有用的公式不仅在 $\alpha < 180^\circ$ 时成立（如在 图 1 上），而且适用于任何 $\alpha$，包括 $\alpha \ge 180^\circ$ (图 2, 3)。确实，在$\alpha > 180^\circ$（图 2）处，三角形$OAB$的面积必须与扇形$OAnB$的面积相加，但在这种情况下$\sin \alpha < 0$和公式（2）再次给出了正确答案！情况$\alpha = 180^\circ$也符合公式（2），从此$\sin \alpha = 0$，退化三角形$OAB$的面积等于0（图3）。

当经过角度$\alpha = 180^\circ$时，正弦符号由平面变为负；在图上，这将精确地回答阴影数字不应该被减去，而是应该相加的事实。当符号在经过角度 $\gamma = 90^\circ$ 时发生变化时，在余弦定理中也会观察到类似的效果。

V·S·埃佩尔
