---
id: 1975-6-rostovtsev-kak-mozhno-izmerit-tolschinu-zerkalnogo-sloya-9d16f084
issue: kvant_1975_6
year: 1975
number: "6"
title: 如何测量镜面层的厚度？
authors:
  - Ростовцев Н. М.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 20
page_last: 21
page_labels: 18-19
tag: FETD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1edb70c51c562b20daa5a9a386a7dd80a252b75bed32122e2685e221aeb568a3
prompt_sha256: draft-1
translated_from: content/ru/1975/06/articles/06_rostovtsev-kak-mozhno-izmerit-tolschinu-zerkalnogo-sloya-9d16f084.md
source_content_sha256: baa86f834e4ddece62614c2154bf50a81a1d6767d46405a2956d3256191badfd
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

如何改变镜面层的厚度？

N·M·罗斯特莫夫采夫

制作镜子时，在玻璃抛光表面涂上一层薄薄的金属，可以很好地反射光线。特别普遍的是用化学沉积在玻璃上的银制成的镜子。

但如您所知，银是一种昂贵的金属。如何控制银的消耗，即改变镜面上银层的厚度？如果您熟悉 Fizu 在 1861 年提出的方法，您将能够回答提出的问题并改变镜面层的厚度。该方法基于气味与银的化学相互作用，并且仍在实践中使用。

为了改变银镜层的厚度，将一粒光放在其上（光束 1 在 图 6 处），然后它部分地从 AgI 层的外表面反射（点 A，光线 2），部分穿过层内部，从其第二表面反射，即从与银的边界（点 B）反射，然后射出（点 C，光线 3）。由此产生的反射波（光束 2 和光束 3）是相干的，因此它们会发生干涉。干涉的结果取决于光线2和光线3的几何路径差δ，可以使用以下公式计算

$$\delta = AB + BC.$$

如果光的入射角为零或接近零，则$AB = BC$，所以

$$\delta = 2AB = 2d,$$

(1)

其中$d$是光束入射点处“线”的厚度。从层的边缘到中心，其厚度$d$逐渐增大，路径差$\delta$也增大。当用单色光（例如红色）照射时，会观察到照明最大值（红色环），其中光线路径的差异等于底层银中光的整数波长。当光线路径的差异为一半的倍数时，会形成暗环（最低照度）

⟦folio 19⟧

该物质的波长$\lambda$：

$$\delta = (2k-1)\,\frac{\lambda}{2}. \qquad (2)$$

这里$k = 1, 2, 3, \ldots$是暗环的编号。第一个是最外面的暗环。

根据关系式（1）和（2）可知，当观察到编号$k$的暗环时，可以使用以下公式计算AgI层的厚度

$$d = (2k-1)\,\frac{\lambda}{4}. \qquad (3)$$

如果最后一个编号为$k_{\max}$的暗环与中心透明点的边缘重合，则层$d_{\max}$的最大厚度等于

$$d_{\max} = (2k_{\max}-1)\,\frac{\lambda}{4}. \qquad (4)$$

实际上，最后一个暗环通常与透明点的边缘不重合，而是位于距其一定距离的位置（例如，在 图 $a$ 处）。因此，实际上$d_{\max}$略大于公式（4）计算的值。让我们尝试评估这种不准确性。相邻两个暗环对应处的“透镜”厚度之差等于波长的一半。因此，确定$d_{\max}$的误差不超过$\lambda/4$。那么，我们可以假设 $d_{\max}$ 大约等于

$$d_{\max} = (2k_{\max} - 1)\,\frac{\lambda}{4} + \frac{\lambda}{4} =$$

$$= k_{\max}\,\frac{\lambda}{2}. \qquad (5)$$

物质中光的波长$\lambda$与真空中光的波长$\lambda_0$之间存在关系式$\lambda = \dfrac{\lambda_0}{n}$，其中$n$是物质的折射率。考虑到这一点，我们写

$$d_{\max} = k_{\max}\,\frac{\lambda_0}{2n}. \qquad (6)$$

事实证明（见文章末尾的练习），镜子上银层的厚度$h$由下式决定：

⟦column⟧

以不同的方式，碘化银的最大厚度$d_{\max}$：

$$h = \frac{d_{\max}}{4} = k_{\max}\,\frac{\lambda_0}{8n}. \qquad (7)$$

对于碘化银$n = 2{,}15$。将该值代入式(7)，得到银层厚度的确定公式：

$$h = k_{\max}\,\frac{\lambda_0}{17{,}2}.$$

让图$a$处所描绘的图片通过红色滤光片（红光波长$6{,}2 \cdot 10^{-5}$cm）观察；然后

$$h = \frac{3 \cdot 6{,}2 \cdot 10^{-5}}{17{,}2} \approx 10^{-5}\ см.$$

如果在白光下进行观察，则$k_{\max}$理解为色环的数量，$\lambda$取等于$5{,}6 \cdot 10^{-5}$cm（我们的眼睛对绿光最敏感的波长）。

⟦figure⟧
暗环
透明点
$a)$
$1\ 2\ 3$
$I$
$AgI$
$Ag$
$A$
$C$
$B$
$Ag$
$б)$

2*
