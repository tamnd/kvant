---
id: 1982-7-zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0
issue: kvant_1982_7
year: 1982
number: "7"
title: 具有“负”内阻的源
authors:
  - Зильберман А. Р.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 56
page_last: 57
page_labels: 54-55
tag: Y5N3
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 9fb38e0bcf6eae204ad61df1fd5496bacf15797dcfdee84651913d205f73473e
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/12_zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0.md
source_content_sha256: 3950f0e08dc7444ca502e5095adedde8c5685cbb296daf99e2a4aa7b871babe4
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 54⟧

A·齐伯曼

来源
与“负”
内部的
运动的

许多有趣的问题都与源的属性有关，其中电压对电流的依赖性不同于一般依赖性$U = \mathcal{E} - rI$（$\mathcal{E} - \text{ЭДС}, r$是源的内阻）。我们将使用示例���题 F727来研究其中一些问题。

F727。特定电源的电压与电流的关系如图 1 所示。绘制电压与电源关闭电压与电压电阻的关系图。

让我们将一个电阻为 $R$ 的电阻器连接到源极。其上的电压与电流之间存在简单的关系 - $U_H = RI$。在相同的图上，它显示了源电压对通过它的电流的依赖性$U(I)$，例如直线$U_H = RI$。图形$U(I)$与直线$U_H = RI$的交点不包括电流和电压。对于普通电源，压力电压越低，电流越高，不会出现更多问题——只有一个交点，并且确定的结果是明确的。

图 1.

图 2.

图 3.

⟦folio 55⟧

（有趣的是，通过使用此类来源，可以获得独立数量的链。好吧，为此您需要第二个来源。

例如，对于传统电源，其电流消耗随着电流消耗的增加而减少，可以通过输出电压变化与电流变化的比率来确定内阻值：

$$r = -\frac{\Delta U}{\Delta I}$$

在我们的例子中，在某个区域 - 在依赖 $U(I)$ 的部分 $bd$ 中 - 源的内阻结果为负。在这种情况下，部分$bd$太大，甚至电路的总电阻（$r + R$）也为负。因此，“中间”点的不稳定性和其他“奇怪现象”（包括获得独立振荡的可能性：“负”电阻可以补偿振荡系统中的损耗；当然，这一切的发生都不会违反能量守恒定律——由于源的能量）。

如果电阻同时减小和增加，如何获得整个曲线依赖性 $U(I)$

切屑的分散

（开头部分请参见第 28 页）

承担任务d）。事实证明，这些概念足以处理任何集合 $G$ 的 Kontsevich 问题。此外，有一种算法（非常适合计算机编程）可以在有限数量的步骤中解决 Kontsevich 的 $G$ 问题 - 要么确定其不可解性，要么指示 $G$ 释放的正常移动序列。该算法基于以下消息。

让我们将释放问题简化为初始位置为$A$的归一化问题。然后我们从上方和右侧画出限制给定位置$A$的水平线和垂直线；我们获得一个矩形$m \times n$，其中包含该位置的所有标记 - 所谓的问题矩形（$A_{ij} \geq 0$，以及$i > m$或$j > n$的$A_{ij} = 0$）。将直线向右上方移动两个单元格，得到问题$(m + 2) \times (n + 2)$的定位矩形$P$。我们的算法如下。

确定位置后，构造一个扩展矩形 $P$ 并执行必要的移动（以任何顺序 - 例如，水平方向，在第一个单元格中，然后在第二个单元格中，等等）。

图 8.

如果需要放置超过$P$的芯片，那么问题就无法解决。否则，通过执行所有必要的移动，我们将获得其解决方案（在 $P$ 的范围内！）。

由于篇幅有限，我们无法提供所陈述事实的证据。也许读者能够证明这一点。我们建议函授学校编程的学生编写一个程序来解决一般情况下的 Kontsevich 问题。
