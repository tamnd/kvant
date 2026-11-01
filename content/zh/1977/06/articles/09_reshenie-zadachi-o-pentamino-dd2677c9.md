---
id: 1977-6-reshenie-zadachi-o-pentamino-dd2677c9
issue: kvant_1977_6
year: 1977
number: "6"
title: 【五联骨牌问题的解决办法】
rubric: smes
page_first: 39
page_last: 39
page_labels: "37"
tag: PRET
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 5f99be419205dfe5dae9575e2a9e3e6cb4c0210df1b63f93ecf1d5a609562d9a
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/09_reshenie-zadachi-o-pentamino-dd2677c9.md
source_content_sha256: e3d7d308b5557fe46e692bbc709c8a8ab4b9ec6b98cf9142e776b09eab7ba8f4
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

然后是两个二阶光谱等。随着光谱的阶数增加，光谱对应线之间的距离增加，从而光谱可以相互重叠。例如，对于太阳光，二阶和三阶光谱已经部分重叠。

现在我们直接进入体验环节。为了改变与某种颜色相对应的波长，需要确定光栅的周期$(d)$、光在光栅上的入射角$(\sin \theta)$的正弦以及确定到某个最大值（例如，到一阶最大值$(\sin \varphi_1)$）的方向的角度的正弦。通过播放唱片很容易找到网格周期：

$$d = \frac{\Delta R}{n \Delta t}.$$

这里$\Delta R$是$\Delta t$时间内针沿板半径运动的绝对值，$n$是单位时间内的转数。通常$d \approx 0,01$见。

您可以使用普通台灯作为光源。为了防止来自它的光干扰衍射图样的观察，用纸板制作一个带有槽的屏幕并用它盖住灯。在这种情况下，通过狭缝应该可以看到灯丝。将灯放置在房间的一堵墙附近，将板水平放置在对面墙附近，然后找到插槽的图像 (图 3)。同时，你会看到模糊的彩色条纹。这是一阶谱$(k = 1)$。很容易验证，事实是，角度$\theta$越大，获得的狭缝彩色图像越宽，并且我们可以更准确地改变我们感兴趣的波长的光的衍射角度。

要确定$\sin \varphi_1$，您需要让朋友睡觉并将卡片（或其他物体）放在插槽上，以便其在从光栅（如平面镜）反射的光中的图像与光谱的选定部分一致（参见图3）。用尺子测量$a$、$b$和$h$，我们找到$\sin \varphi_1$和$\sin \theta$：

$$\sin \varphi_1 = \frac{a}{\sqrt{a^2 + b^2}},$$

$$\sin \theta = \frac{a}{\sqrt{a^2 + h^2}}.$$

这些表达式可以稍微简化。从$b \ll a$和$h \ll a$开始，$$\frac{a}{\sqrt{a^2 + b^2}} = \frac{1}{\sqrt{1 + b^2/a^2}} \approx 1 - \frac{1}{2} \frac{b^2}{a^2}$$

和$$\frac{a}{\sqrt{a^2 + h^2}} = \frac{1}{\sqrt{1 + h^2/a^2}} \approx 1 - \frac{1}{2} \frac{h^2}{a^2}.$$

然后最后

$$\lambda = d | \sin \varphi_1 - \sin \theta | \approx d \frac{|h^2 - b^2|}{2a^2}.$$

测量了不同颜色的光的波长后，将它们与表中的值进行比较很有趣。在我们的实验中，对于仔细的图像，误差约为 $10^{-8}$ m 量级。对于可见光波长（$\lambda \sim 10^{-7}$ m），这样的波精度是可以接受的。

在今年杂志的第二期中，我们向读者提出了几个与五氨基相关的问题。两位读者（来自 Anjan 地区的 L. Mutalup 和来自 Voroshilgovgrad 地区的 Yu. Stasevich）成功解决了完整的五氨基同时两个矩形 $4 \times 5$ 和 $4 \times 10$ 集合中的一个。对于小矩形，他们的解决方案是相同的，而对于大伏特，他们的解决方案则不同：
