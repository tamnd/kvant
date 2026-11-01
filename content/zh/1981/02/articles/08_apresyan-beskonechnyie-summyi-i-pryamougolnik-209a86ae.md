---
id: 1981-2-apresyan-beskonechnyie-summyi-i-pryamougolnik-209a86ae
issue: kvant_1981_2
year: 1981
number: "2"
title: 无限和......一个矩形
authors:
  - Апресян М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 23
page_labels: 20-21
tag: R701
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 7ebbed8bd0b578f6b80f4fe4c2d4f7c72524aa53b5f5ea0dae2261445ae31de6
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/08_apresyan-beskonechnyie-summyi-i-pryamougolnik-209a86ae.md
source_content_sha256: b845e7f4033ae0b86686a69f2c7d240c70317eef6260a23c538429c0de5d9446
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 20⟧

M·阿普雷相

连续求和...一个矩形

Stashe经典主义者知道，对于$|q| < 1$，无限几何级数$1 + q + q^2 + q^3 + \dots$的总和等于$\frac{1}{1 - q}$，并且他们知道如何通过分析证明这一点（参见手册“代数和分析的开始9”，第24段）。

对于 $q = \frac{1}{n}$，其中 $n \in \mathbb{N}$，有一种简单的几何方法可以求出这个总和。

让我们从 $n = 2$ 开始：求总和
$$1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \frac{1}{16} + \dots$$

取任意一个面积为 2 的矩形，将其切成两个大小相等（面积相同）的单位面积矩形，如图 1 所示。将其中一个矩形再次切成两等份；我们得到面积为$\frac{1}{2}$的矩形。再次对其中之一进行同样的操作 - 我们得到两个矩形区域

图 1.

图 2.

⟦folio 21⟧

图 3.

$n$ - 自然数）等于 $\frac{n}{m-n}$：为此，您需要保留 $n$ - $m$ 单位矩形不变，并将区域 1 的每个 $m$ 矩形再次切成 $n$ 相等的部分（图 3）。然后保持$n$ - $m$条状不变，各面积为$\frac{m}{n}$，并再次将$\frac{1}{n}$面积的$m^2$矩形切成$n$等份。你们已经就下一步该做什么达成一致了吗？将这种构造推向“终点”并证明其合理性。

最后，我们用面积为2的矩形来计算另一个无穷和；也就是说，我们将证明

$$1 + \frac{1}{2!} + \frac{2}{3!} + \frac{3}{4!} + \dots + \frac{n}{n+1!} + \dots = 2.$$

前两步与之前相同：将矩形切割为区域 1 的两个矩形；其中之一是面积为 $\frac{1}{2}$ (图 4) 的两个矩形。然后我们将其中一个矩形块切成三等份（每份面积$\frac{1}{6}$）。我们将$\frac{1}{6}$区域的其中一个部分切成四等份；其中一个 - 分成五个部分，等等。无限地继续这个过程，我们将得到一个区域 1 的矩形，一个区域$\frac{1}{2!}$，两个区域$\frac{1}{3!}$，三个区域$\frac{1}{4!}$，...，$n$ 区域$\frac{1}{(n+1)!}$的矩形，等等。这意味着原始矩形所需的面积，即两个。

罗伯特·伍德的伪镜头

（关于开始，请参见第 18 页）

由此，根据公式$\frac{1}{d} + \frac{1}{f} = \frac{1}{F}$，可以通过公式：$F = 19,5$cm求出伪透镜的距离。直径约为 6 毫米的伪透镜的距离约为 10 厘米。

伪透镜的工作原理是什么？甘油直线度指数$n_r = 1,47$；水直度指标为$n_B = 1,33$。水扩散到由铁和甘油组成的均质圆柱体中，会取代其中的甘油。在这种情况下，圆柱体变得不均匀，其直线度指数从中心到边缘逐渐减小。而且，正如已经提到的，该系统的行为就像一个会聚透镜。

请注意，大约一天后，组合物再次变得均匀，pseudolinza 失去了其惊人的特性。
